# Exercício 03 — Revisando uma Mudança no PetCare OS

## O que você já sabe

Você estudou que code review serve para reduzir risco, melhorar clareza e compartilhar conhecimento. Comentários devem ser específicos, acionáveis e focados em comportamento, não em pessoas.

## Cenário

Você está revisando um pull request no PetCare OS com a seguinte descrição:

> "Adiciona validação de e-mail no cadastro de tutores."

O diff mostra as seguintes mudanças:

1. Uma nova função `validaEmail` foi adicionada em `src/utils.ts`.
2. A função retorna `true` se o e-mail contiver `@` e `.`, e `false` caso contrário.
3. O arquivo `src/cadastro.ts` foi alterado para chamar `validaEmail` antes de salvar.
4. A mensagem de commit é `"ajuste"`.
5. Nenhum teste ou exemplo de uso foi adicionado.

## Tarefa

Escreva três comentários de review que você faria nesse pull request. Cada comentário deve ser acionável e focado em um aspecto diferente: um sobre possível bug, um sobre clareza e um sobre documentação ou mensagem de commit.

## Critérios de Correção

- Três comentários distintos e acionáveis.
- Um comentário sobre possível bug ou comportamento incorreto.
- Um comentário sobre clareza de código ou nome.
- Um comentário sobre documentação, commit ou exemplo de uso.
- Tom técnico e colaborativo, sem ataques pessoais.

## Corrija Sua Atividade Com IA

```text
Cenário: estou revisando um pull request no PetCare OS com a descrição "Adiciona validação de e-mail no cadastro de tutores". O diff mostra:
1. Uma função validaEmail em src/utils.ts.
2. A função retorna true se o e-mail contiver @ e ., e false caso contrário.
3. O arquivo src/cadastro.ts chama validaEmail antes de salvar.
4. A mensagem de commit é "ajuste".
5. Nenhum teste ou exemplo de uso foi adicionado.

Tarefa: escreva três comentários de code review, cada um focado em um aspecto diferente: possível bug, clareza de código e documentação/commit.

Critérios de correção:
1. Três comentários distintos e acionáveis.
2. Um sobre possível bug ou comportamento incorreto.
3. Um sobre clareza de código ou nome.
4. Um sobre documentação, commit ou exemplo de uso.
5. Tom técnico e colaborativo.

[COLE SUA RESPOSTA AQUI]

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas. Só depois mostre uma versão de referência.
```

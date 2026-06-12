# Exercício 01 — Consulta Assíncrona de Dados

## Objetivo

Praticar `Promise`, `async/await` e tratamento de erros simulando uma consulta a dados do PetCare OS.

## O que você já sabe

- Criar e consumir Promises.
- Usar `async/await` e `try/catch`.
- Estruturar objetos simples em JavaScript.

## Tarefa atual

Você vai simular uma função que busca o resumo de um pet no PetCare OS. A função recebe um `id` e, após um pequeno atraso, retorna os dados do pet ou uma mensagem de erro.

## Exercício

1. Crie uma função `buscarResumoDoPet(id)` que retorna uma `Promise`.
2. Dentro da Promise, use `setTimeout` para simular um atraso de 500ms.
3. Se o `id` for `"pet-001"`, resolva com `{ id: "pet-001", nome: "Thor", status: "Em Triagem" }`.
4. Se o `id` for `"pet-002"`, resolva com `{ id: "pet-002", nome: "Luna", status: "Aguardando Aprovação" }`.
5. Para qualquer outro `id`, rejeite com `new Error("Pet não encontrado.")`.
6. Crie uma função `mostrarStatusDoPet(id)` usando `async/await`.
7. Trate o erro com `try/catch` e exiba uma mensagem amigável.
8. Chame a função para os três casos e observe os resultados.

## Critérios de conclusão

- A função retorna uma Promise.
- O atraso está presente.
- Os dois IDs válidos retornam os dados esperados.
- IDs inválidos disparam erro tratado.
- A função assíncrona usa `await` e `try/catch`.

## Como este trabalho continuará

Funções assíncronas como essa serão usadas no projeto final deste módulo e reaparecerão nos módulos de frontend moderno, Next.js e backend, quando você consumir APIs reais do PetCare OS.

## Corrija Sua Atividade Com IA

```text
Estou estudando Promises e async/await em JavaScript. Fiz um exercício e quero correção.

Cenário: estou simulando uma consulta ao PetCare OS. A função `buscarResumoDoPet(id)` deve retornar uma Promise que, após 500ms, resolve com dados de um pet para os ids "pet-001" e "pet-002", e rejeita com erro para qualquer outro id. A função `mostrarStatusDoPet(id)` consome essa Promise com async/await e trata erros.

Tarefa: avalie o código que eu escrevi para esse exercício.

Critérios de correção:
1. A função `buscarResumoDoPet` retorna uma Promise?
2. O atraso de 500ms está simulado?
3. Os ids "pet-001" e "pet-002" retornam os dados corretos?
4. Outros ids rejeitam com mensagem clara?
5. A função `mostrarStatusDoPet` usa async/await e try/catch?
6. As mensagens de saída são claras?

[COLE SUA RESPOSTA AQUI]

Regras da correção:
- Destaque meus acertos primeiro.
- Aponte imprecisões e erros com explicações curtas.
- Dê dicas antes de mostrar uma possível solução completa.
- Não reescreva o código todo sem que eu peça.
```

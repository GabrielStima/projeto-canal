# Exercício 02 — Modelando Tipos do PetCare OS

## Objetivo

Praticar `type aliases`, `interfaces`, `unions`, `narrowing` e `módulos` modelando as entidades do PetCare OS.

## O que você já sabe

- Declarar tipos e interfaces em TypeScript.
- Usar propriedades opcionais.
- Criar unions de strings.
- Usar `export` e `import` entre arquivos.

## Tarefa atual

Você vai criar os tipos básicos do núcleo do PetCare OS e uma função que atualiza o status de um atendimento de forma segura.

## Exercício

1. Crie um arquivo `tipos.ts`.
2. Declare um type `StatusAtendimento` com os valores do ciclo de vida:
   `"Recebido"`, `"Em Triagem"`, `"Aguardando Aprovação"`, `"Em Procedimento"`, `"Pronto para Alta"`, `"Finalizado"`.
3. Declare uma `interface Pet` com `id`, `nome`, `especie` e `tutorId`.
4. Declare uma `interface Tutor` com `id`, `nome` e `email`.
5. Declare uma `interface Atendimento` com `id`, `petId`, `status` (use o type criado) e `motivo` opcional.
6. Exporte todos os tipos.
7. Crie um arquivo `atendimento.ts`.
8. Importe os tipos necessários de `tipos.ts`.
9. Exporte uma função `atualizarStatus` que recebe um `Atendimento` e um `StatusAtendimento` e retorna um novo `Atendimento` com o status atualizado.
10. Crie um arquivo `app.ts`.
11. Importe os tipos e a função.
12. Crie pelo menos um pet, um tutor e um atendimento.
13. Atualize o status do atendimento e exiba o resultado.

## Critérios de conclusão

- Os tipos estão em um arquivo separado e exportados.
- `StatusAtendimento` é uma union de strings literais.
- `Atendimento` usa `StatusAtendimento` e possui `motivo` opcional.
- A função `atualizarStatus` retorna um novo objeto sem mutar o original.
- Os módulos se comunicam por `import` e `export`.

## Como este trabalho continuará

Esses tipos e a função de atualização de status serão estendidos no projeto final deste módulo. Eles também servirão de base para o módulo de Algoritmos e Estruturas de Dados, quando você implementará a fila de prioridade da triagem.

## Corrija Sua Atividade Com IA

```text
Estou estudando type aliases, interfaces, unions e módulos em TypeScript. Fiz um exercício e quero correção.

Cenário: estou modelando o núcleo de tipos do PetCare OS. Criei um arquivo `tipos.ts` com os tipos `StatusAtendimento`, `Pet`, `Tutor` e `Atendimento`. Criei `atendimento.ts` com a função `atualizarStatus`. Criei `app.ts` para usar esses módulos.

Tarefa: avalie a modelagem e a organização dos arquivos que eu escrevi.

Critérios de correção:
1. `StatusAtendimento` é uma union com os seis valores do ciclo de atendimento?
2. `Pet`, `Tutor` e `Atendimento` possuem os campos esperados?
3. `Atendimento` tem `motivo` opcional e `status` tipado corretamente?
4. Os tipos estão exportados e importados corretamente?
5. `atualizarStatus` retorna um novo objeto sem alterar o original?
6. `app.ts` cria exemplos e demonstra o fluxo?

[COLE SUA RESPOSTA AQUI]

Regras da correção:
- Destaque meus acertos primeiro.
- Aponte imprecisões e erros com explicações curtas.
- Dê dicas antes de mostrar uma possível solução completa.
- Não reescreva o código todo sem que eu peça.
```

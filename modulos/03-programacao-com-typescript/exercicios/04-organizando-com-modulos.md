# Exercício 04 — Organizando com Módulos

## Objetivo

Praticar divisão de código em múltiplos arquivos usando `export` e `import` no contexto do PetCare OS.

## O que você já sabe

- Criar types, interfaces e funções tipadas.
- Usar `export` e `import` básicos.
- Estruturar objetos e arrays.

## Tarefa atual

Você vai reorganizar código do PetCare OS em módulos separados por responsabilidade.

## Exercício

1. Crie um arquivo `tipos.ts` com:
   - `type StatusAtendimento` com os valores `"Recebido"`, `"Em Triagem"`, `"Aguardando Aprovação"`, `"Finalizado"`.
   - `interface Pet` com `id`, `nome`, `especie` e `tutorId`.
   - `interface Tutor` com `id`, `nome` e `email`.
2. Crie um arquivo `pets.ts` que importe `Pet` e exporte:
   - Uma função `criarPet(dados)` que retorna um `Pet`.
   - Uma função `buscarPetPorId(pets, id)` que retorna o pet encontrado ou `undefined`.
3. Crie um arquivo `tutores.ts` que importe `Tutor` e exporte:
   - Uma função `criarTutor(dados)` que retorna um `Tutor`.
   - Uma função `formatarNomeDoTutor(tutor)` que retorna `"Nome: <nome> (<email>)"`.
4. Crie um arquivo `app.ts` que importe os tipos e funções dos outros módulos.
5. Em `app.ts`, crie pelo menos dois tutores, dois pets e demonstre as funções de busca e formatação.
6. Execute ou transpile o código e verifique se não há erros.

## Critérios de conclusão

- Cada arquivo tem uma responsabilidade clara.
- Tipos e funções são exportados e importados corretamente.
- Não há tipos duplicados entre arquivos.
- `app.ts` demonstra o uso integrado dos módulos.

## Como este trabalho continuará

A organização em módulos será a base do projeto final deste módulo e será estendida nos módulos de frontend moderno, Next.js e backend, quando você separar responsabilidades em camadas diferentes.

## Corrija Sua Atividade Com IA

```text
Estou estudando módulos no TypeScript. Fiz um exercício e quero correção.

Cenário: estou organizando o código do PetCare OS em módulos. `tipos.ts` contém os tipos, `pets.ts` contém funções de pet, `tutores.ts` contém funções de tutor e `app.ts` usa tudo junto.

Tarefa: avalie a organização e os imports/exports do código que eu escrevi.

Critérios de correção:
1. `tipos.ts` exporta `StatusAtendimento`, `Pet` e `Tutor`?
2. `pets.ts` importa `Pet` e exporta `criarPet` e `buscarPetPorId`?
3. `tutores.ts` importa `Tutor` e exporta `criarTutor` e `formatarNomeDoTutor`?
4. `app.ts` importa corretamente de `tipos.ts`, `pets.ts` e `tutores.ts`?
5. `app.ts` demonstra o uso das funções com exemplos reais?
6. Não há duplicação de tipos entre arquivos?

[COLE SUA RESPOSTA AQUI]

Regras da correção:
- Destaque meus acertos primeiro.
- Aponte imprecisões e erros com explicações curtas.
- Dê dicas antes de mostrar uma possível solução completa.
- Não reescreva o código todo sem que eu peça.
```

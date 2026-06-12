# Atividade Final do Módulo — Núcleo TypeScript do PetCare OS

## Objetivo

Construir um núcleo TypeScript do PetCare OS que integre tudo o que você estudou neste módulo: JavaScript moderno, tipos, funções, tratamento de erros, assincronismo e módulos.

## O que você já sabe

- Escrever código JavaScript moderno com `const`, arrow functions, destructuring e spread.
- Usar estruturas de controle e funções.
- Tratar erros com `throw`, `try` e `catch`.
- Trabalhar com `Promise`, `async` e `await`.
- Declarar tipos, interfaces, aliases, unions e usar narrowing.
- Organizar código em módulos com `export` e `import`.
- Usar classes, generics e utility types em nível introdutório.

## Tarefa atual

Você vai criar um pequeno conjunto de arquivos TypeScript que modela entidades e regras do PetCare OS. Esta atividade é **obrigatória para continuidade**, pois os próximos módulos vão assumir que você já conseguiu organizar um domínio tipado.

## Exercício

Crie os seguintes arquivos em uma pasta do seu repositório de estudos (por exemplo, `petcare-os-core/`):

### 1. `tipos.ts`

Exporte os seguintes tipos:

```typescript
type StatusAtendimento =
  | "Recebido"
  | "Em Triagem"
  | "Aguardando Aprovação"
  | "Em Procedimento"
  | "Pronto para Alta"
  | "Finalizado";

interface Pet { id, nome, especie, tutorId }
interface Tutor { id, nome, email }
interface Atendimento { id, petId, status: StatusAtendimento, motivo?: string }
interface ItemOrcamento { descricao, preco, quantidade }
```

### 2. `atendimento.ts`

Importe os tipos de `tipos.ts` e exporte:

- `criarAtendimento(petId, motivo?): Atendimento` — gera um id e status `"Recebido"`.
- `atualizarStatus(atendimento, novoStatus): Atendimento` — retorna um novo atendimento com o status atualizado.

A função `atualizarStatus` deve validar que o novo status é válido. Lance um erro se não for.

### 3. `orcamento.ts`

Importe `ItemOrcamento` de `tipos.ts` e exporte:

- `calcularTotal(itens: ItemOrcamento[]): number` — retorna o total do orçamento.
- `adicionarItem(itens, novoItem): ItemOrcamento[]` — retorna uma nova lista com o item adicionado.

### 4. `busca.ts`

Exporte uma função `buscarPetPorId(id: string): Promise<Pet>` que simula uma busca assíncrona. Após 300ms:

- Se o id for `"pet-001"`, resolva com `{ id: "pet-001", nome: "Thor", especie: "cachorro", tutorId: "tutor-001" }`.
- Caso contrário, rejeite com `new Error("Pet não encontrado.")`.

### 5. `app.ts`

Importe os módulos e:

- Crie um tutor e um pet.
- Crie um atendimento.
- Atualize o status para `"Em Triagem"`.
- Crie um orçamento com dois itens e calcule o total.
- Busque o pet por id usando `async/await` e trate possíveis erros.
- Exiba os resultados no console.

## Critérios de conclusão

- Os tipos estão bem definidos e exportados.
- `StatusAtendimento` é uma union de strings literais.
- As funções não mutam objetos recebidos; retornam novos objetos.
- O tratamento de erro impede status inválidos e ids inexistentes.
- A busca assíncrona usa `Promise` e é consumida com `async/await` e `try/catch`.
- O código está organizado em módulos com responsabilidades claras.
- Você consegue executar `app.ts` e ver os resultados no terminal.

## Como este trabalho continuará

Este núcleo TypeScript será retomado no módulo de Algoritmos e Estruturas de Dados, quando você implementará a fila de prioridade da triagem usando os tipos de `Atendimento`. Nos módulos de frontend moderno, Next.js e backend, essas mesmas entidades reaparecerão como base para componentes, rotas e APIs.

## Corrija Sua Atividade Com IA

```text
Estou finalizando o módulo Programação com TypeScript. Fiz a atividade final e quero correção.

Cenário: construí o núcleo TypeScript do PetCare OS com os arquivos `tipos.ts`, `atendimento.ts`, `orcamento.ts`, `busca.ts` e `app.ts`. O objetivo é modelar entidades (Pet, Tutor, Atendimento, ItemOrcamento), atualizar status de atendimento, calcular orçamento e simular busca assíncrona de pet.

Tarefa: avalie a organização, os tipos e as regras do código que eu escrevi.

Critérios de correção:
1. Os tipos `StatusAtendimento`, `Pet`, `Tutor`, `Atendimento` e `ItemOrcamento` estão bem definidos e exportados?
2. `StatusAtendimento` é uma union de strings literais com os seis valores do ciclo?
3. `criarAtendimento` gera um id e status "Recebido"?
4. `atualizarStatus` retorna um novo objeto e valida o status?
5. `calcularTotal` e `adicionarItem` funcionam corretamente sem mutar a lista?
6. `buscarPetPorId` simula atraso e trata id inexistente com erro?
7. `app.ts` integra todos os módulos e usa async/await com try/catch?
8. Os módulos têm responsabilidades claras?

[COLE SUA RESPOSTA AQUI]

Regras da correção:
- Destaque meus acertos primeiro.
- Aponte imprecisões e erros com explicações curtas.
- Dê dicas antes de mostrar uma possível solução completa.
- Não reescreva o código todo sem que eu peça.
```

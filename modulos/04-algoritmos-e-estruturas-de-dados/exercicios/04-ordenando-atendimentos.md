# Exercício 04 — Ordenando Atendimentos

## O que você já sabe/possui

- Como implementar loops aninhados e comparações em TypeScript.
- Os algoritmos Bubble Sort, Selection Sort e Insertion Sort.
- A ideia de critério de ordenação.

## Tarefa atual

Ordene atendimentos de uma clínica veterinária por urgência usando três algoritmos diferentes e compare o número de passos de cada um.

## Exercício/resultado a produzir

Dado o array de atendimentos abaixo:

```ts
type Appointment = {
  id: number;
  petName: string;
  urgency: number; // maior número = maior urgência
};

const appointments: Appointment[] = [
  { id: 1, petName: "Luna", urgency: 2 },
  { id: 2, petName: "Thor", urgency: 5 },
  { id: 3, petName: "Mia", urgency: 1 },
  { id: 4, petName: "Bolinha", urgency: 3 },
  { id: 5, petName: "Nina", urgency: 4 },
];
```

1. Implemente `bubbleSort(appointments)` ordenando por `urgency` em ordem decrescente.
2. Implemente `selectionSort(appointments)` ordenando por `urgency` em ordem decrescente.
3. Implemente `insertionSort(appointments)` ordenando por `urgency` em ordem decrescente.
4. Cada função deve retornar o array ordenado e o número de comparações realizadas.
5. Teste as três funções com o mesmo array e compare os resultados.

## Como solicitar correção com IA

Use a seção `Corrija Sua Atividade Com IA` ao final deste arquivo.

## Onde esse trabalho será retomado

Ordenação é fundamental para listagens, rankings, dashboards e preparação de dados para busca binária. Nos módulos futuros, você usará ordenação em consultas de banco de dados, APIs paginadas e interfaces de usuário.

## Corrija Sua Atividade Com IA

```text
Estou estudando algoritmos de ordenação (Bubble Sort, Selection Sort e Insertion Sort) em TypeScript. Este exercício é autocontido e não depende de nenhum projeto anterior.

Cenário:
Uma clínica veterinária precisa ordenar atendimentos por urgência. Quanto maior o número, mais urgente é o caso.

Dados:
```ts
type Appointment = {
  id: number;
  petName: string;
  urgency: number;
};

const appointments: Appointment[] = [
  { id: 1, petName: "Luna", urgency: 2 },
  { id: 2, petName: "Thor", urgency: 5 },
  { id: 3, petName: "Mia", urgency: 1 },
  { id: 4, petName: "Bolinha", urgency: 3 },
  { id: 5, petName: "Nina", urgency: 4 },
];
```

Tarefa:
1. Implemente bubbleSort(appointments) ordenando por urgency em ordem decrescente.
2. Implemente selectionSort(appointments) ordenando por urgency em ordem decrescente.
3. Implemente insertionSort(appointments) ordenando por urgency em ordem decrescente.
4. Cada função deve retornar o array ordenado e o número de comparações.
5. Teste as três funções com o mesmo array e compare os resultados.

Critérios de correção:
- Cada algoritmo ordena corretamente por urgency decrescente.
- O número de comparações é contado de forma consistente.
- As funções não alteram o array original.
- A comparação entre os três algoritmos é coerente.

[COLE SUA RESPOSTA AQUI]

Por favor, destaque meus acertos, aponte imprecisões e ofereça dicas antes de apresentar uma resposta completa.
```

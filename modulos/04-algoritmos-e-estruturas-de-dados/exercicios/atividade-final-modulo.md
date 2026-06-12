# Atividade Final do Módulo — Analisador de Estruturas e Algoritmos

## O que você já sabe/possui

- Arrays, linked lists, stacks, queues, hash tables, busca linear, busca binária, algoritmos de ordenação, árvores, árvore de busca binária, heaps e Heap Sort.
- TypeScript com funções, classes, tipos e módulos.
- Os exercícios anteriores deste módulo, que praticaram fila, hash table, busca e ordenação em contextos de clínica veterinária.

Nesta atividade final, você não precisa ter feito o projeto do módulo anterior. Os tipos e dados necessários serão fornecidos aqui.

## Tarefa atual

Construa um analisador de estruturas e algoritmos em TypeScript puro. O programa deve usar dados de uma clínica veterinária, executar diferentes soluções e comparar o número de passos, o uso de memória auxiliar e a clareza de cada abordagem.

## Exercício/resultado a produzir

Crie um ou mais arquivos TypeScript com o seguinte:

### 1. Tipos de dados

```ts
type Appointment = {
  id: number;
  petName: string;
  urgency: number;
  arrivalOrder: number;
};

type MedicalRecord = {
  id: number;
  petName: string;
  diagnosis: string;
};

type Medication = {
  code: string;
  name: string;
  quantity: number;
};
```

### 2. Conjuntos de dados de exemplo

- Uma lista de pelo menos 6 atendimentos.
- Uma lista de pelo menos 6 prontuários ordenados por `id`.
- Uma lista de pelo menos 4 medicamentos.

### 3. Estruturas

Implemente modelos simples de:

- `Stack<T>` com `push`, `pop` e `peek`.
- `Queue<T>` com `enqueue`, `dequeue` e `peek`.
- `HashTable<K, V>` usando `Map` com `set`, `get` e `has`.

### 4. Algoritmos

Implemente funções que retornem o resultado e o número de passos:

- Busca linear por id de atendimento.
- Busca binária por id de prontuário.
- Pelo menos três algoritmos de ordenação (por exemplo, Bubble Sort, Insertion Sort e Quick Sort) ordenando atendimentos por urgência.

### 5. Relatório

Escreva um relatório em texto no próprio arquivo TypeScript (como comentários ou com `console.log`) que compare:

- qual estrutura/algoritmo foi usado em cada caso;
- quantos passos cada operação executou;
- qual operação domina o custo;
- que trade-off existe entre tempo, espaço e clareza.

## Como solicitar correção com IA

Use a seção `Corrija Sua Atividade Com IA` ao final deste arquivo.

## Onde esse trabalho será retomado

Este analisador é o marco de síntese do módulo 04. As estruturas e algoritmos praticados aqui reaparecerão em:

- Bancos de dados (índices, joins, ordenação).
- Backend (listagens, filtros, filas).
- Frontend moderno (renderização de listas, estados, histórico).
- System design (escala, cache, filas de prioridade).

Guarde este arquivo para mostrar a evolução do seu raciocínio computacional.

> **Esta atividade é recomendada para consolidar o módulo, mas não é obrigatória para continuar a formação.**

## Corrija Sua Atividade Com IA

```text
Estou finalizando o módulo Algoritmos e Estruturas de Dados em uma trilha fullstack JavaScript/TypeScript. Esta atividade é autocontida e não depende de nenhum projeto anterior.

Cenário:
Uma clínica veterinária precisa de um analisador de estruturas e algoritmos para comparar soluções usando dados de atendimentos, prontuários e estoque.

Dados:
```ts
type Appointment = {
  id: number;
  petName: string;
  urgency: number;
  arrivalOrder: number;
};

type MedicalRecord = {
  id: number;
  petName: string;
  diagnosis: string;
};

type Medication = {
  code: string;
  name: string;
  quantity: number;
};
```

Tarefa:
1. Crie conjuntos de dados de exemplo: pelo menos 6 atendimentos, 6 prontuários ordenados por id e 4 medicamentos.
2. Implemente Stack, Queue e HashTable simples.
3. Implemente busca linear por id de atendimento, busca binária por id de prontuário e pelo menos três algoritmos de ordenação por urgência.
4. Todas as funções de busca e ordenação devem retornar o resultado e o número de passos.
5. Escreva um relatório comparando tempo, espaço e clareza de cada solução.

Critérios de correção:
- Os tipos e dados de exemplo estão presentes.
- As estruturas implementam as operações solicitadas.
- Os algoritmos de busca e ordenação estão corretos e contam passos.
- O relatório compara tempo, espaço e clareza de forma coerente.
- O código compila em TypeScript sem erros óbvios.

[COLE SUA RESPOSTA AQUI]

Por favor, destaque meus acertos, aponte imprecisões e ofereça dicas antes de apresentar uma resposta completa.
```

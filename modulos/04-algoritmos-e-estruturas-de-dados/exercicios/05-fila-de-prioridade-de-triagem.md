# Exercício 05 — Fila de Prioridade de Triagem

## O que você já sabe/possui

- Como implementar filas (queue) e heaps em TypeScript.
- Como comparar objetos por prioridade.
- Os conceitos de FIFO e de fila de prioridade estudados nas aulas sobre queues e heaps.

Neste exercício, você não precisa ter feito o projeto do módulo anterior. Os tipos e dados necessários estão descritos abaixo.

## Tarefa atual

Implemente uma fila de prioridade para a triagem de uma clínica veterinária. Cada atendimento tem um nível de urgência, e o próximo a ser chamado deve ser sempre o mais urgente, não o mais antigo.

## Exercício/resultado a produzir

Use os tipos abaixo como ponto de partida:

```ts
type Appointment = {
  id: number;
  petName: string;
  urgency: number; // maior número = maior urgência
};
```

Crie uma classe `PriorityTriageQueue` com os métodos:

- `enqueue(appointment: Appointment): void` — adiciona um atendimento na fila.
- `dequeue(): Appointment | undefined` — remove e retorna o atendimento mais urgente.
- `peek(): Appointment | undefined` — retorna o atendimento mais urgente sem remover.
- `isEmpty(): boolean` — indica se a fila está vazia.

Você pode implementar a fila de prioridade usando:

- um array e ordenar a cada inserção;
- um array e buscar o maior elemento a cada remoção;
- ou uma estrutura baseada em heap (se já se sentir confortável).

Escolha uma estratégia, justifique sua escolha e implemente.

Simule a seguinte sequência:

1. Chega o atendimento de id `1` do pet "Luna" com urgência 2.
2. Chega o atendimento de id `2` do pet "Thor" com urgência 5.
3. Chega o atendimento de id `3` do pet "Mia" com urgência 1.
4. O veterinário atende o próximo caso mais urgente.
5. Chega o atendimento de id `4` do pet "Bolinha" com urgência 4.
6. O veterinário atende o próximo caso mais urgente.

Mostre o estado da fila após cada operação.

## Como solicitar correção com IA

Use a seção `Corrija Sua Atividade Com IA` ao final deste arquivo.

## Onde esse trabalho será retomado

Esta fila de prioridade é o incremento persistente do módulo 04. O conceito será retomado nos módulos de backend, filas de mensagens e processamento assíncrono, quando você implementará filas reais com prioridade. Guarde este arquivo: ele será referência para mostrar a evolução do raciocínio computacional aplicado ao PetCare OS.

> **Esta atividade é recomendada para consolidar o módulo, mas não é obrigatória para continuar a formação.**

## Corrija Sua Atividade Com IA

```text
Estou estudando filas de prioridade em TypeScript. Este exercício é autocontido e não depende de nenhum projeto anterior.

Cenário:
Uma clínica veterinária precisa de uma fila de triagem em que o próximo atendimento seja sempre o mais urgente, não o mais antigo. Cada atendimento tem id, petName e urgency (maior número = maior urgência).

Dados iniciais:
```ts
type Appointment = {
  id: number;
  petName: string;
  urgency: number;
};
```

Tarefa:
Crie uma classe PriorityTriageQueue com os métodos enqueue, dequeue, peek e isEmpty. Simule a seguinte sequência:
1. 1 - Luna - urgência 2.
2. 2 - Thor - urgência 5.
3. 3 - Mia - urgência 1.
4. O veterinário atende o próximo caso mais urgente.
5. 4 - Bolinha - urgência 4.
6. O veterinário atende o próximo caso mais urgente.

Mostre o estado da fila após cada operação. Justifique a estratégia escolhida (array ordenado, busca pelo maior, ou heap).

Critérios de correção:
- A classe implementa os quatro métodos solicitados.
- O atendimento mais urgente sempre sai primeiro.
- A simulação está completa e consistente.
- A justificativa da estratégia menciona trade-off entre tempo e clareza.
- O código compila em TypeScript sem erros óbvios.

[COLE SUA RESPOSTA AQUI]

Por favor, destaque meus acertos, aponte imprecisões e ofereça dicas antes de apresentar uma resposta completa.
```

# Exercício 01 — Fila de Atendimentos

## O que você já sabe/possui

- Como criar arrays em TypeScript.
- Como usar classes com métodos simples.
- O conceito de FIFO (first in, first out) estudado na aula sobre queues.

## Tarefa atual

Modele uma fila de atendimentos para uma clínica veterinária. Cada atendimento tem um identificador e o nome do pet. A fila deve respeitar a ordem de chegada: o primeiro pet a chegar é o primeiro a ser atendido.

## Exercício/resultado a produzir

Crie uma classe `AppointmentQueue` em TypeScript com os métodos:

- `enqueue(appointment: { id: number; petName: string }): void` — adiciona um atendimento no final da fila.
- `dequeue(): { id: number; petName: string } | undefined` — remove e retorna o atendimento mais antigo.
- `peek(): { id: number; petName: string } | undefined` — retorna o atendimento mais antigo sem remover.
- `isEmpty(): boolean` — indica se a fila está vazia.

Simule a seguinte sequência:

1. Chega o atendimento do pet "Luna".
2. Chega o atendimento do pet "Thor".
3. Chega o atendimento do pet "Mia".
4. O veterinário atende o próximo da fila.
5. Chega o atendimento do pet "Bolinha".
6. O veterinário atende o próximo da fila.

Mostre o estado da fila após cada operação.

## Como solicitar correção com IA

Use a seção `Corrija Sua Atividade Com IA` ao final deste arquivo.

## Onde esse trabalho será retomado

Filas aparecem em vários pontos da formação: processamento de mensagens, backend, filas de prioridade e sistemas distribuídos. Este exercício prepara o terreno para a fila de prioridade de triagem, que é o desafio intermediário N3 deste módulo.

## Corrija Sua Atividade Com IA

```text
Estou estudando filas (queues) em TypeScript. Este exercício é autocontido e não depende de nenhum projeto anterior.

Cenário:
Uma clínica veterinária atende pets na ordem de chegada. Cada atendimento tem um id e o nome do pet.

Tarefa:
Implemente uma classe AppointmentQueue com os métodos enqueue, dequeue, peek e isEmpty. Simule a chegada e o atendimento dos pets Luna, Thor, Mia e Bolinha, nesta ordem:
1. Luna chega.
2. Thor chega.
3. Mia chega.
4. O veterinário atende o próximo.
5. Bolinha chega.
6. O veterinário atende o próximo.

Mostre o estado da fila após cada operação.

Critérios de correção:
- A classe implementa os quatro métodos solicitados.
- A ordem de saída respeita FIFO.
- A simulação está completa e consistente.
- O código compila em TypeScript sem erros óbvios.

[COLE SUA RESPOSTA AQUI]

Por favor, destaque meus acertos, aponte imprecisões e ofereça dicas antes de apresentar uma resposta completa.
```

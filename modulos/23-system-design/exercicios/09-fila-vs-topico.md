# Exercício 09 — Fila ou Tópico?

## Tarefa

Dentro do panteão da Mensageria Assíncrona no System Design de Eventos, qual a diferença crítica e implacável para o fluxo da sua API de um Message Broker operando de maneira "Competidora" num modelo `Point-to-Point` (Exemplo: SQS / RabbitMQ padrão com Workers em fila chupando bilhetes exclusivos) contra a genialidade distribuída do `Publish/Subscribe` de Tópicos do Apache Kafka (Onde o mesmo Bilhete pode alertar o sistema de Faturamento e o de Marketing simultaneamente)?

## Corrija Sua Atividade Com IA

```text
Cenário: Acoplamento e Fanning-out via Streaming e Tópicos (Kinesis/Kafka/SNS) X Workload Processing Padrão.

Tarefa: Meu entendimento teórico de Filas Simples x Hub de Eventos Complexo:
[COLE AQUI]

Critérios de correção:
1. Pressionei no detalhe que "Point to Point/Fila Comum" apaga a mensagem assim que 1 Consumer consome, resolvendo processamento paralelo de PDFs sem duplicar tarefas pra outros containers da aplicação?
2. Falei que `Tópicos (Fan-Out/Broadcast)` joga o aviso do banco "Pet_foi_Salvo" imutável na roleta do meio para 10 microsserviços diferentes lerem e atuarem na sua respectiva business logic sem deletar a mensagem master do Kafka?
```

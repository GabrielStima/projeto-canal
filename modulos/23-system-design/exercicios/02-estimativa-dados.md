# Exercício 02 — Estimativa de Dados

## Tarefa

No método *Back-of-the-envelope* (Estimativa de guardanapo na entrevista), não basta achar o Tráfego Médio (Average RPS). Descreva por que focar o desenho do Hardware apenas no Througput Médio sem multiplicar pela variação dos Picos Transientes de Carga (Spikes, como "Horário Nobre da Netflix" ou "Black Friday") vai invariavelmente gerar Cascatas de Falhas e OOMKilled no seu ecossistema distribuído de contêineres na Sexta à noite.

## Corrija Sua Atividade Com IA

```text
Cenário: Provisionamento de Elasticidade, Scale-Out Limites de Latência.

Tarefa: Aqui está a minha tese provando por que picos esmagam a estatística cega da Média nas contas Cloud:
[COLE AQUI A EXPLICAÇÃO]

Critérios de correção:
1. Expliquei o conceito simples que "Um servidor aguentar 1 milhão de requisições / 24h não significa que ele aguente 500.000 requisições despencando no primeiro segundo das 24h"?
2. Utilizei palavras chave como Throttling, Buffering ou Message Queuing para defender a absorção de "Rajadas HTTP"?
```

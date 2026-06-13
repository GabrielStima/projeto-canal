# Exercício 14 — Requests e Limits

## Tarefa

Se 3 sistemas num Servidor EC2 explodirem os picos físicos de Memória (`RAM`) da máquina num ambiente de Kubernetes, a infra não trava: A API caça e atira nas Cabeças "OOMKilled" sem piedade e em microssegundos se o Limits da caixa for burlado. Mas qual a diferença comportamental base de se chegar nos Limits estranguladores de de CPU (Cgroups - Throttling)? A aplicação crasheia e a Pod morre com CrashLoopBackOff também?

## Corrija Sua Atividade Com IA

```text
Cenário: Limites Físicos, Compressão de Ciclos em CPU, Cgroups do Linux.

Tarefa: Segue a diferença exata entre RAM e CPU no orquestrador:
[COLE AQUI]

Critérios de correção:
1. Mostrei como os ciclos incompressíveis e sufocantes de RAM forçam uma "Morte Prematura/Eject" e causam falhas abruptas do app?
2. Argumentei como os picos de CPU apenas esmagam/throttlam o response sem explodir a rotina em `OOMKills`?
```

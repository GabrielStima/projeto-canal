# Exercício 06 — Logging e Métricas

## Tarefa

Os logs puros (texto não formatado) limitam a busca de problemas em sistemas Cloud.
Imagine que o Agendamento de Consultas falhou silenciosamente para o tutor `userId: abc-123`.

1. Refatore na sua API o mecanismo de log, garantindo que ele não gere texto livre e sim um objeto JSON estruturado (Pode usar `Pino`, `Winston` ou implementar manualmente no Console).
2. Escreva o payload do Log Ideal para cobrir a "Falha de comunicação com o sistema legado de Agendamentos do Hospital". Garanta que o log inclua uma correlação, nível, tempo gasto e evite vazar dados proibidos (senha, CPF completo, cartões).

## Corrija Sua Atividade Com IA

```text
Cenário: Refatorando e modelando um Log Estruturado Operacional para o PetCare OS.

Tarefa: Analise o log JSON abaixo focado em resolver um Timeout de uma API Externa:

[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. O objeto possui os campos mínimos para ser rastreado? (Correlação/TraceID, Timestamp, Nível, Nome do Evento)
2. O log é inofensivo sob a ótica de segurança/LGPD (Nenhum PII forte)?
3. A mensagem descritiva (se houver) ajuda ou atrapalha a indexação (High Cardinality)?

Aponte falhas se houverem ou parabenize os pontos que facilitam meu filtro num Kibana / Datadog.
```

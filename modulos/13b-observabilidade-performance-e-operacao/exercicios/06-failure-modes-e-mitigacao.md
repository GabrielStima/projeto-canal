# Exercício 06 — Failure Modes e Mitigação

## O que você já sabe

Você possui testes, logs, métricas, trace, dashboard e alerta para um fluxo. Agora usará esses elementos para responder a uma falha conhecida.

## Sua tarefa

Escolha um failure mode plausível:

- banco lento ou indisponível;
- serviço externo com timeout;
- fila indisponível;
- cache ou rate limiter fora do ar;
- consumo excessivo de CPU ou memória.

Descreva:

1. comportamento esperado para o usuário;
2. decisão de falhar aberto, fechado ou degradar;
3. timeout, retry ou outra mitigação, quando aplicável;
4. risco de duplicidade ou inconsistência;
5. log emitido;
6. métrica alterada;
7. aparência do trace;
8. condição do alerta;
9. passo de recuperação ou reconciliação.

Inclua um teste ou simulação pequena quando for seguro no ambiente local.

## O que você vai produzir

- matriz do failure mode;
- evidência da simulação ou plano reproduzível;
- sequência de investigação;
- procedimento curto de mitigação;
- atualização final do relatório.

## Critérios de conclusão

- A decisão considera impacto e consistência.
- Retries possuem limite e condição.
- Sinais permitem distinguir sintoma e causa.
- Recuperação e reconciliação são consideradas.
- O plano não depende de uma pessoa adivinhar o que aconteceu.

## Como este trabalho continuará

A atividade final reunirá baseline, carga, instrumentação e resposta a esse failure mode.

## Corrija Sua Atividade Com IA

```text
Cenário: Modelei um failure mode para uma API, incluindo comportamento, mitigação, logs, métricas, trace, alerta e recuperação.

Tarefa: Avalie se o plano é coerente e investigável.

Critérios de correção:
1. Falhar aberto, fechado ou degradar foi justificado?
2. Timeouts e retries possuem limites seguros?
3. Duplicidade, consistência e reconciliação foram consideradas?
4. Logs, métricas e trace distinguem sintoma e causa?
5. O alerta conduz a uma ação e a recuperação é reproduzível?

Destaque os acertos, aponte imprecisões e dê dicas antes de apresentar outro desenho completo.

[COLE SUA RESPOSTA AQUI]
```

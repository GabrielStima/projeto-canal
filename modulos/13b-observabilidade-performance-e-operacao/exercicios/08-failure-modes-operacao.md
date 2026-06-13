# Exercício 08 — Failure Modes na Operação

## Tarefa

A API de Pagamento terceirizada caiu (Gateway).

1. Escreva o que deve acontecer no Módulo Financeiro do PetCare OS quando a requisição retornar Timeout de 10s em relação ao pagamento de uma fatura de vacina presencial.
2. A Clínica congela e a pessoa não pode sair de lá (Fail-Closed)?
3. A Fatura é criada como "Aguardando Confirmação em Fila" (Degradação Graciosa/Fail-Open)?
4. Qual log é emitido para recuperar a operação no dia seguinte caso a API não volte?

## Corrija Sua Atividade Com IA

```text
Cenário: Planejamento arquitetural para mitigação de Falhas (Failure Modes) com Gateway de Pagamento.

Tarefa: Abaixo descrevo como lido com a queda de uma API síncrona terceirizada num ambiente presencial da clínica.

[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. O plano de ação é condizente com a vida real de um hospital / clínica veterinária?
2. A técnica escolhida de tolerância a falhas (Circuit Breaker, Retries, Queueing) faz sentido para este cenário?
3. Há buracos lógicos na reconciliação financeira (a clínica vai tomar calote)?

Desafie meu design de falhas com um edge-case realista que eu não tenha previsto.
```

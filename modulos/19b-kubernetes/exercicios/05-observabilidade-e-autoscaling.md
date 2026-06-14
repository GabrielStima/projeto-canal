# Exercício 05 — Observabilidade e Autoscaling

## O que você já tem

Seu workload possui probes, recursos e uma estratégia de persistência.

## Tarefa

Planeje a operação do workload:

1. logs estruturados em stdout e stderr;
2. campos de correlação preservados;
3. métricas da aplicação e do cluster;
4. sinais para distinguir falha da aplicação, falta de recursos e problema de rede;
5. comandos ou consultas de diagnóstico;
6. métrica de escala e valor alvo;
7. limites mínimo e máximo de réplicas;
8. dependências necessárias para HPA;
9. risco de escalar pods sem capacidade nos nós;
10. condição em que autoscaling não resolveria o gargalo.

Esboce um HPA somente se houver uma métrica e um comportamento de carga coerentes.

## O que você vai produzir

Um plano de observabilidade e escala que será testado conceitualmente na atividade final.

## Corrija Sua Atividade Com IA

```text
Cenário: Planejei logs, métricas, diagnóstico e autoscaling para um workload Kubernetes. Defini métrica alvo, réplicas mínimas e máximas, dependências do HPA e limites da estratégia.

Tarefa: Revise meu plano de observabilidade e escala.

Critérios de correção:
1. Logs sobrevivem à recriação do pod por serem coletados externamente?
2. Correlação permite seguir uma operação entre réplicas?
3. Métricas distinguem erro, saturação e indisponibilidade?
4. HPA usa uma métrica relacionada ao trabalho real?
5. Requests estão definidos para sustentar a decisão de escala?
6. Escala de pods foi diferenciada da capacidade de nós?
7. Gargalos externos, banco e fila foram considerados?

Primeiro destaque os acertos. Depois aponte imprecisões e ofereça dicas antes de apresentar uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

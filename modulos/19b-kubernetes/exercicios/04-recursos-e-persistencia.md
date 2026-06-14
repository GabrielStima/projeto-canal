# Exercício 04 — Recursos e Persistência

## O que você já tem

O workload já possui configuração, probes, Service e controles básicos de segurança.

## Tarefa

Defina:

1. requests iniciais de CPU e memória;
2. limits justificados;
3. efeito esperado de throttling de CPU;
4. risco de `OOMKilled`;
5. métricas que permitirão ajustar valores;
6. dados temporários que podem usar armazenamento efêmero;
7. dados que precisam sobreviver ao pod;
8. decisão entre PVC, serviço gerenciado externo ou nenhuma persistência no cluster;
9. política para migrations;
10. motivo para não levar automaticamente o banco principal ao Kubernetes.

Inclua PVC somente quando o cenário realmente exigir.

## O que você vai produzir

Uma política de capacidade e dados que evita valores arbitrários e stateful workloads sem operação adequada.

## Corrija Sua Atividade Com IA

```text
Cenário: Defini requests, limits, métricas e estratégia de persistência para uma API em Kubernetes. Diferenciei CPU, memória, armazenamento efêmero, PVC e serviços gerenciados externos.

Tarefa: Avalie minhas decisões de recursos e dados.

Critérios de correção:
1. Requests representam uma necessidade inicial justificável?
2. Limits evitam abuso sem provocar instabilidade previsível?
3. Throttling de CPU e OOMKilled foram diferenciados?
4. Existe plano para ajustar valores com métricas reais?
5. Dados persistentes não dependem do filesystem efêmero do pod?
6. A escolha entre PVC e serviço externo considera backup, disponibilidade e operação?
7. O banco não foi movido ao cluster apenas por conveniência?

Comece pelos acertos. Depois indique imprecisões e dê dicas antes de apresentar uma política completa.

[COLE SUA RESPOSTA AQUI]
```

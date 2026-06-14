# Exercício 04 — Distribuição e Consistência

## O que você já tem

Você escolheu uma arquitetura-base e identificou os limites internos do PetCare OS.

## Tarefa

Escolha uma capacidade que poderia ser candidata a separação futura, como Financeiro, Notificações ou Estoque. Compare:

- mantê-la como módulo no monólito;
- separá-la como serviço independente.

Analise:

1. motivo de negócio para a separação;
2. necessidade real de deploy ou escala independente;
3. propriedade dos dados;
4. falhas de rede, latência e indisponibilidade;
5. efeitos da consistência eventual para o usuário;
6. observabilidade e operação necessárias;
7. critério objetivo que justificaria a mudança.

Conclua com **manter**, **preparar** ou **separar agora**. Permanecer no monólito é uma decisão válida.

## O que você vai produzir

Uma decisão proporcional sobre distribuição, com riscos e sinais para reavaliá-la no futuro.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou decidindo se uma capacidade de uma API deve continuar como módulo de um monólito ou virar um serviço independente. Analisei negócio, escala, dados, falhas de rede, consistência, operação e critérios futuros.

Tarefa: Revise minha decisão de manter, preparar ou separar agora.

Critérios de correção:
1. Existe uma necessidade concreta para distribuir o sistema?
2. Os custos de rede, dados, consistência e operação foram considerados?
3. A experiência do usuário durante estados inconsistentes foi descrita?
4. O critério de reavaliação é observável?
5. A conclusão decorre das evidências, sem assumir que microsserviços são evolução obrigatória?

Primeiro destaque os acertos. Depois aponte imprecisões e premissas frágeis. Ofereça dicas antes de apresentar uma decisão alternativa completa.

[COLE SUA RESPOSTA AQUI]
```

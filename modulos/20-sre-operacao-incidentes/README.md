# SRE, Operacao e Incidentes

Este modulo mostra como sistemas reais sao operados depois que chegam em producao. Ate aqui, voce ja estudou observabilidade, performance, cloud, Infrastructure as Code, CI/CD, containers e Kubernetes. Agora o foco muda para confiabilidade, resposta a falhas e tomada de decisao operacional.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar o papel de SRE em uma organizacao de engenharia;
- diferenciar SLI, SLO e SLA;
- usar error budgets para equilibrar confiabilidade e entrega;
- reconhecer sinais de capacidade, saturacao e degradacao;
- entender readiness, liveness e saude operacional de aplicacoes;
- planejar rollback, degradacao graciosa e respostas a falhas;
- escrever runbooks uteis;
- entender responsabilidades de on-call;
- participar de incident response com comunicacao, mitigacao e aprendizado;
- escrever postmortems sem cultura de culpa.

## Por Que Este Modulo Existe

Colocar uma aplicacao no ar nao encerra o trabalho. Sistemas em producao recebem trafego real, dependem de rede, banco, filas, provedores, configuracao, deploys, pessoas e limites fisicos. Quando algo falha, a pergunta deixa de ser apenas "qual linha de codigo quebrou?" e passa a ser "como reduzimos dano, mantemos usuarios atendidos e aprendemos com o que aconteceu?".

SRE, operacao e incidentes existem para transformar confiabilidade em pratica. O modulo conecta sinais de observabilidade, infraestrutura, deploy e arquitetura com decisoes concretas: quando alertar, quando reverter, quando degradar, quando pausar entrega, como documentar procedimentos e como melhorar o sistema depois de uma falha.

## Pre-requisitos

- Observabilidade, logs, metricas, tracing, monitoramento, alertas, testes de carga e failure modes.
- Cloud Fundamentals: IAM, networking, bancos gerenciados, filas, serverless, CDN, custos, backup e disaster recovery.
- Infrastructure as Code: Terraform, ambientes, state, drift, seguranca e automacao.
- DevOps, CI/CD, deploy, Docker, containers, registries e Kubernetes.
- Kubernetes: workloads, Services, configuracao, recursos, monitoramento, autoscaling e padroes de deployment.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 20.00 | [SRE, Operacao e Incidentes](20.00-sre-operacao-e-incidentes.md) | Guarda-chuva | Rascunho |
| 20.01 | [O que e SRE na Pratica](20.01-o-que-e-sre-na-pratica.md) | Especifica ampla | Rascunho |
| 20.02 | [Confiabilidade, Risco e Sistemas em Producao](20.02-confiabilidade-risco-e-sistemas-em-producao.md) | Especifica | Rascunho |
| 20.03 | [SLI, SLO e SLA](20.03-sli-slo-e-sla.md) | Especifica | Rascunho |
| 20.04 | [Error Budgets](20.04-error-budgets.md) | Especifica | Rascunho |
| 20.05 | [Capacidade e Saturacao](20.05-capacidade-e-saturacao.md) | Especifica | Rascunho |
| 20.06 | [Readiness e Liveness](20.06-readiness-e-liveness.md) | Especifica pratica | Rascunho |
| 20.07 | [Degradacao Graciosa](20.07-degradacao-graciosa.md) | Especifica | Rascunho |
| 20.08 | [Rollback](20.08-rollback.md) | Especifica pratica | Rascunho |
| 20.09 | [Runbooks](20.09-runbooks.md) | Especifica pratica | Rascunho |
| 20.10 | [On-call](20.10-on-call.md) | Especifica | Rascunho |
| 20.11 | [Incident Response](20.11-incident-response.md) | Especifica ampla | Rascunho |
| 20.12 | [Postmortems](20.12-postmortems.md) | Especifica | Rascunho |
| 20.13 | [Projeto Pratico: Operando uma API em Producao](20.13-projeto-pratico-operando-uma-api-em-producao.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Operar uma API simples como se ela estivesse em producao:

1. escolher uma API ja usada no curso;
2. definir SLIs de disponibilidade, latencia, erros e saturacao;
3. propor SLOs realistas para os fluxos principais;
4. desenhar alertas acionaveis;
5. definir endpoints de saude e criterios de readiness/liveness;
6. simular um deploy com problema;
7. decidir entre rollback, mitigacao e degradacao graciosa;
8. escrever um runbook para investigacao;
9. simular uma resposta a incidente;
10. escrever um postmortem com acoes de melhoria.

## O Que Revisar Antes de Avancar

- Logs, metricas, tracing, monitoramento e alertas.
- Testes de carga, performance, profiling e failure modes.
- CI/CD, deploy, rollback e padroes de deployment.
- Kubernetes: Pods, Deployments, Services, probes, recursos e autoscaling.
- Cloud: custos, backup, disaster recovery, networking e servicos gerenciados.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo SRE, Operacao e Incidentes de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina confiabilidade, SRE, SLI, SLO, SLA, error budgets, capacidade, saturacao, readiness, liveness, degradacao graciosa, rollback, runbooks, on-call, incident response e postmortems.
- Objetivo do modulo: Quero entender como sistemas reais sao acompanhados, operados e recuperados quando estao em producao.
- Pre-requisitos: Observabilidade, performance, cloud, Infrastructure as Code, CI/CD, containers e Kubernetes.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos de SLI, SLO e error budget;
3. cenarios de incidente para eu analisar;
4. perguntas de entrevista para backend/fullstack intermediario;
5. exemplos de aplicacao em projetos reais;
6. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Materiais internos do proprio projeto.
- Documentacao oficial do Kubernetes quando uma aula exigir probes, workloads ou configuracao operacional.
- Guias conceituais de SRE, confiabilidade, incident response e postmortems.
- Documentacao das ferramentas de observabilidade, CI/CD e cloud escolhidas para praticas especificas.

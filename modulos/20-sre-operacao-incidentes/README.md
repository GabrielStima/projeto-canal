<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# SRE, Operação e Incidentes

</div>

Este módulo mostra como sistemas reais são operados depois que chegam em produção. Até aqui, você já estudou observabilidade, performance, cloud, Infrastructure as Code, CI/CD, containers e Kubernetes. Agora o foco muda para confiabilidade, resposta a falhas e tomada de decisão operacional.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o papel de SRE em uma organização de engenharia;
- diferenciar SLI, SLO e SLA;
- usar error budgets para equilibrar confiabilidade e entrega;
- reconhecer sinais de capacidade, saturação e degradação;
- entender readiness, liveness e saúde operacional de aplicações;
- planejar rollback, degradação graciosa e respostas a falhas;
- escrever runbooks úteis;
- entender responsabilidades de on-call;
- participar de incident response com comunicação, mitigação e aprendizado;
- escrever postmortems sem cultura de culpa.

## Por Que Este Módulo Existe

Colocar uma aplicação no ar não encerra o trabalho. Sistemas em produção recebem tráfego real, dependem de rede, banco, filas, provedores, configuração, deploys, pessoas e limites físicos. Quando algo falha, a pergunta deixa de ser apenas "qual linha de código quebrou?" e passa a ser "como reduzimos dano, mantemos usuários atendidos e aprendemos com o que aconteceu?".

SRE, operação e incidentes existem para transformar confiabilidade em prática. O módulo conecta sinais de observabilidade, infraestrutura, deploy e arquitetura com decisões concretas: quando alertar, quando reverter, quando degradar, quando pausar entrega, como documentar procedimentos e como melhorar o sistema depois de uma falha.

## Pré-requisitos

- Observabilidade, logs, métricas, tracing, monitoramento, alertas, testes de carga e failure modes.
- Cloud Fundamentals: IAM, networking, bancos gerenciados, filas, serverless, CDN, custos, backup e disaster recovery.
- Infrastructure as Code: Terraform, ambientes, state, drift, segurança e automação.
- DevOps, CI/CD, deploy, Docker, containers, registries e Kubernetes.
- Kubernetes: workloads, Services, configuração, recursos, monitoramento, autoscaling e padrões de deployment.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 20.00 | [SRE, Operação e Incidentes](20.00-sre-operacao-e-incidentes.md) | Guarda-chuva | Rascunho |
| 20.01 | [O que é SRE na Prática](20.01-o-que-e-sre-na-pratica.md) | Específica ampla | Rascunho |
| 20.02 | [Confiabilidade, Risco e Sistemas em Produção](20.02-confiabilidade-risco-e-sistemas-em-producao.md) | Específica | Rascunho |
| 20.03 | [SLI, SLO e SLA](20.03-sli-slo-e-sla.md) | Específica | Rascunho |
| 20.04 | [Error Budgets](20.04-error-budgets.md) | Específica | Rascunho |
| 20.05 | [Capacidade e Saturação](20.05-capacidade-e-saturacao.md) | Específica | Rascunho |
| 20.06 | [Readiness e Liveness](20.06-readiness-e-liveness.md) | Específica prática | Rascunho |
| 20.07 | [Degradação Graciosa](20.07-degradacao-graciosa.md) | Específica | Rascunho |
| 20.08 | [Rollback](20.08-rollback.md) | Específica prática | Rascunho |
| 20.09 | [Runbooks](20.09-runbooks.md) | Específica prática | Rascunho |
| 20.10 | [On-call](20.10-on-call.md) | Específica | Rascunho |
| 20.11 | [Incident Response](20.11-incident-response.md) | Específica ampla | Rascunho |
| 20.12 | [Postmortems](20.12-postmortems.md) | Específica | Rascunho |
| 20.13 | [Projeto Prático: Operando uma API em Produção](20.13-projeto-pratico-operando-uma-api-em-producao.md) | Síntese prática | Rascunho |


## Exercícios

- [Exercício 01 — O Impacto da Queda](exercicios/01-impacto-queda.md)
- [Exercício 02 — SLI, SLO e SLA](exercicios/02-sli-slo-sla.md)
- [Exercício 03 — Análise de Saturação](exercicios/03-saturacao.md)
- [Exercício 04 — Arquitetura de Degradação](exercicios/04-degradacao.md)
- [Exercício 05 — Rollback Letal de Banco](exercicios/05-rollback-banco.md)
- [Exercício 06 — Papéis no Incidente](exercicios/06-papeis-incidente.md)
- [Atividade Final Prática: Simulacro de Incidente](exercicios/atividade-final-sre.md)

## Projeto ou Prática do Módulo

No ecossistema produtivo vivo da PetCare, você adotará o **Marco Operacional N12**. Não há mais novas 'Features'. É sobrevivência de infraestrutura em alta tensão:

1. Adapte a API Node que você criou usando Endpoints mandatórios para o Cluster: `/health/liveness` e `/health/readiness`.
2. Escreva o balanço matemático formal do "Error Budget" que o dono do hospital assinará sobre sua infra.
3. Elabore e jogue em um Github Issue o seu primeiro `Postmortem Blameless`, narrando o apagão e a timeline (MTTR) de quando a UTI Pediátrica perdeu sinal de roteamento para a Nuvem AWS.
4. Formalize os `Action Items` da resolução que consertam a Falha Estrutural do "Processo", eximindo engenheiros júniores de falhas decorrentes da automação precária (Culture Fit).

## O Que Revisar Antes de Avançar

- Logs, métricas, tracing, monitoramento e alertas.
- Testes de carga, performance, profiling e failure modes.
- CI/CD, deploy, rollback e padrões de deployment.
- Kubernetes: Pods, Deployments, Services, probes, recursos e autoscaling.
- Cloud: custos, backup, disaster recovery, networking e serviços gerenciados.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo SRE, Operação e Incidentes de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina confiabilidade, SRE, SLI, SLO, SLA, error budgets, capacidade, saturação, readiness, liveness, degradação graciosa, rollback, runbooks, on-call, incident response e postmortems.
- Objetivo do módulo: Quero entender como sistemas reais são acompanhados, operados e recuperados quando estão em produção.
- Pré-requisitos: Observabilidade, performance, cloud, Infrastructure as Code, CI/CD, containers e Kubernetes.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de SLI, SLO e error budget;
3. cenários de incidente para eu analisar;
4. perguntas de entrevista para backend/fullstack intermediário;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial do Kubernetes quando uma aula exigir probes, workloads ou configuração operacional.
- Guias conceituais de SRE, confiabilidade, incident response e postmortems.
- Documentação das ferramentas de observabilidade, CI/CD e cloud escolhidas para práticas específicas.

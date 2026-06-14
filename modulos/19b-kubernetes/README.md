<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Kubernetes

</div>

Este módulo mostra como orquestrar containers em um cluster Kubernetes: desde o primeiro contato com o cluster até padrões de deployment, autoscaling, storage e observabilidade básica.

Antes de chegar aqui, você já estudou CI/CD, empacotamento com Docker, registries, networking e segurança em containers. Agora o foco é coordenar múltiplos containers em um ambiente de orquestração, mantendo o estado desejado da aplicação e oferecendo recursos para conectividade, configuração, limites, segurança e escala.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar os conceitos centrais de Kubernetes, como cluster, desired state, workloads, Services e configuração;
- rodar uma aplicação simples em Kubernetes com configuração, recursos, conectividade e observabilidade básica;
- escolher padrões de deployment e entender quando Kubernetes ajuda ou adiciona complexidade;
- reconhecer cuidados de segurança, storage e logging em um cluster;
- decidir quando usar Kubernetes e quando containers simples ou PaaS já resolvem.

## Por Que Este Módulo Existe

Containers resolvem o problema de empacotar e executar uma aplicação de forma previsível, mas não resolvem sozinhos a coordenação de muitos containers em múltiplas máquinas. Kubernetes entra para manter o estado desejado dos workloads, expor serviços, gerenciar configurações, limitar recursos, escalar sob demanda e recuperar falhas.

Este módulo assume que você já sabe construir e publicar imagens. O foco aqui é orquestrar essas imagens com critério, sem transformar Kubernetes em destino inevitável para todo projeto.

## Pré-requisitos

- Git, GitHub, terminal, variáveis de ambiente e code review.
- Backend com Node.js, APIs, bancos de dados, migrations, logging e failure modes.
- Cloud Fundamentals: IAM, VPC/networking, storage, bancos gerenciados, CDN, backup e custos.
- Infrastructure as Code: Terraform, HCL, providers, resources, state, remote state, locking, drift e modules.
- DevOps, CI/CD e Containers: pipelines, Docker, imagens, registries, networking, persistência e segurança em containers.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 19b.00 | [Kubernetes](19b.00-kubernetes.md) | Guarda-chuva curta | Rascunho |
| 19b.01 | [Configurando Kubernetes](19b.01-configurando-kubernetes.md) | Específica prática | Rascunho |
| 19b.02 | [Rodando Aplicações no Kubernetes](19b.02-rodando-aplicacoes-no-kubernetes.md) | Específica prática | Rascunho |
| 19b.03 | [Serviços e Conectividade](19b.03-servicos-e-conectividade.md) | Específica | Rascunho |
| 19b.04 | [Configuração e Gerenciamento](19b.04-configuracao-e-gerenciamento.md) | Específica | Rascunho |
| 19b.05 | [Gerenciamento de Recursos](19b.05-gerenciamento-de-recursos.md) | Específica | Rascunho |
| 19b.06 | [Storage and Volumes](19b.06-storage-and-volumes.md) | Específica | Rascunho |
| 19b.07 | [Segurança no Kubernetes](19b.07-seguranca-no-kubernetes.md) | Específica ampla | Rascunho |
| 19b.08 | [Monitoramento e Logging no Kubernetes](19b.08-monitoramento-e-logging-no-kubernetes.md) | Específica | Rascunho |
| 19b.09 | [Autoscaling](19b.09-autoscaling.md) | Específica | Rascunho |
| 19b.10 | [Padrões de Deployment](19b.10-padroes-de-deployment.md) | Específica | Rascunho |
| 19b.11 | [Tópicos Avançados de Kubernetes](19b.11-topicos-avancados-de-kubernetes.md) | Guarda-chuva de fechamento | Rascunho |
| 19b.12 | [Projeto Prático: Deploy em Kubernetes](19b.12-projeto-pratico-deploy-em-kubernetes.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em 3 blocos. Os exercícios evoluem a mesma pasta de manifestos.

**Bloco A — Decisão, workloads e conectividade** · aulas [19b.00–19b.03]
Valida a necessidade de Kubernetes e cria a base declarativa com Deployment e Service.
Pré-requisito: imagem rastreável e desafio de containerização do módulo 19A.

**Bloco B — Configuração, recursos, storage e segurança** · aulas [19b.04–19b.07]
Separa configuração e segredos, limita recursos, decide persistência e reduz privilégios.
Pré-requisito: Bloco A.

**Bloco C — Operação, escala e entrega** · aulas [19b.08–19b.12]
Planeja observabilidade, autoscaling, rollout, rollback e avalia objetos avançados.
Pré-requisito: Bloco B.

> As dependências entre aulas dentro do bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Exercícios

- [Exercício 01 — Decisão e Base de Manifestos](exercicios/01-decisao-e-base-de-manifestos.md)
- [Exercício 02 — Workload, Configuração e Probes](exercicios/02-workload-configuracao-e-probes.md)
- [Exercício 03 — Conectividade e Segurança](exercicios/03-conectividade-e-seguranca.md)
- [Exercício 04 — Recursos e Persistência](exercicios/04-recursos-e-persistencia.md)
- [Exercício 05 — Observabilidade e Autoscaling](exercicios/05-observabilidade-e-autoscaling.md)
- [Exercício 06 — Rollout, Rollback e Tópicos Avançados](exercicios/06-rollout-rollback-e-topicos-avancados.md)
- [Atividade Final — Deploy do PetCare OS em Kubernetes](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você reutiliza a imagem publicada no 19A e evolui manifestos versionados.

Os exercícios começam pela decisão de usar Kubernetes, depois acrescentam workload, configuração, probes, Service, segurança, recursos, persistência, observabilidade e rollout. Objetos avançados são avaliados pelo problema que resolvem, sem virar requisito artificial.

Na atividade final, os manifestos são aplicados em um cluster de laboratório, uma atualização com falha é observada e o rollback é executado. Um cluster local é suficiente; a documentação deve deixar claro o que ainda faltaria para produção.

## O Que Revisar Antes de Avançar

- Docker, imagens, registries, containers, networking e persistência.
- CI/CD, pipelines e publicação de artefatos.
- IAM, VPC/networking, secrets, storage, bancos gerenciados e custos em cloud.
- Terraform, state, plan, apply, drift e modules.
- Observabilidade, logs, métricas, tracing e alertas.

## Próximo Módulo

- [20 — SRE, Operação e Incidentes](../20-sre-operacao-incidentes/): monitoramento, SLI/SLO/SLA, incident response, postmortems e runbooks.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Kubernetes de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina a orquestrar containers com Kubernetes: cluster, workloads, Services, ConfigMaps, Secrets, recursos, storage, segurança, monitoramento, autoscaling e padrões de deployment.
- Objetivo do módulo: Quero entender quando e como usar Kubernetes para rodar aplicações em ambientes modernos.
- Pré-requisitos: CI/CD, Docker, containers, registries, networking, persistência, segurança em containers, cloud fundamentals e Infrastructure as Code.

Crie uma revisão guiada com perguntas conceituais, exercícios práticos, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial do Kubernetes quando uma aula exigir detalhes de API, comandos ou configuração.
- Documentação oficial das ferramentas de CI/CD, registries e provedores de cloud quando exemplos específicos forem usados.

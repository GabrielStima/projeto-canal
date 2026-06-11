<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# DevOps, Containers e Kubernetes

</div>

Este módulo mostra como aplicações saem do repositório, viram artefatos executáveis, rodam em containers e passam a ser orquestradas em Kubernetes.

Até aqui, você já estudou fundamentos de cloud, Infrastructure as Code, Terraform, state, ambientes, segredos, observabilidade, segurança, arquitetura e aplicações backend. Agora o foco é conectar entrega, empacotamento e execução em ambientes modernos.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o papel de DevOps, CI/CD e deploy no ciclo de entrega;
- entender como Infrastructure as Code entra em pipelines com revisão, aprovação e segurança;
- construir, executar, versionar e publicar imagens de container;
- reconhecer cuidados de persistência, networking e segurança em containers;
- explicar os conceitos centrais de Kubernetes, como cluster, desired state, workloads, Services e configuração;
- rodar uma aplicação simples em Kubernetes com configuração, recursos, conectividade e observabilidade básica;
- escolher padrões de deployment e entender quando Kubernetes ajuda ou adiciona complexidade.

## Por Que Este Módulo Existe

Saber programar uma aplicação é apenas uma parte da vida dela. Em projetos reais, o código precisa passar por validação, build, empacotamento, publicação, configuração, deploy, monitoramento e operação. Sem esse caminho, cada entrega depende de passos manuais, máquinas específicas e conhecimento espalhado.

DevOps, containers e Kubernetes entram para reduzir essa distância entre código e execução. CI/CD organiza o fluxo de entrega. Docker cria uma unidade previsível de empacotamento. Kubernetes coordena containers em um cluster, mantendo o estado desejado da aplicação e oferecendo recursos para conectividade, configuração, limites, segurança e escala.

## Pré-requisitos

- Git, GitHub, terminal, variáveis de ambiente, gerenciadores de pacote e code review.
- Backend com Node.js, APIs, bancos de dados, migrations, logging e failure modes.
- Segurança na web, autenticação, autorização, segredos e princípio do menor privilégio.
- Observabilidade, logs, métricas, tracing, monitoramento, alertas e testes de carga.
- Cloud Fundamentals: IAM, VPC/networking, storage, bancos gerenciados, filas, serverless, CDN, backup, custos e FinOps.
- Infrastructure as Code: Terraform, HCL, providers, resources, variables, outputs, state, remote state, locking, drift, modules, ambientes e segurança em IaC.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 19.00 | [DevOps, Containers e Kubernetes](19.00-devops-containers-e-kubernetes.md) | Guarda-chuva | Rascunho |
| 19.01 | [O que é DevOps na Prática](19.01-o-que-e-devops-na-prática.md) | Específica ampla | Rascunho |
| 19.02 | [CI/CD](19.02-ci-cd.md) | Específica | Rascunho |
| 19.03 | [Deploy](19.03-deploy.md) | Específica | Rascunho |
| 19.04 | [Infrastructure as Code em CI/CD](19.04-infrastructure-as-code-em-ci-cd.md) | Específica | Rascunho |
| 19.05 | [Geração e Revisão de Planos de Infraestrutura](19.05-geracao-e-revisao-de-planos-de-infraestrutura.md) | Específica prática | Rascunho |
| 19.06 | [Aprovação e Aplicação Automatizada de Mudanças](19.06-aprovacao-e-aplicação-automatizada-de-mudancas.md) | Específica prática | Rascunho |
| 19.07 | [Credenciais Temporárias para Automação](19.07-credenciais-temporarias-para-automacao.md) | Específica | Rascunho |
| 19.08 | [Policy as Code](19.08-policy-as-code.md) | Específica ampla | Rascunho |
| 19.09 | [Detecção Automatizada de Drift](19.09-deteccao-automatizada-de-drift.md) | Específica | Rascunho |
| 19.10 | [Docker e Containers](19.10-docker-e-containers.md) | Guarda-chuva curta | Rascunho |
| 19.11 | [Básico de Containers](19.11-basico-de-containers.md) | Específica | Rascunho |
| 19.12 | [Building Container Images](19.12-building-container-images.md) | Específica prática | Rascunho |
| 19.13 | [Docker CLI](19.13-docker-cli.md) | Específica prática | Rascunho |
| 19.14 | [Running Containers](19.14-running-containers.md) | Específica prática | Rascunho |
| 19.15 | [Persistência de Dados](19.15-persistencia-de-dados.md) | Específica | Rascunho |
| 19.16 | [Bancos em Containers](19.16-bancos-em-containers.md) | Específica prática | Rascunho |
| 19.17 | [Networking em Containers](19.17-networking-em-containers.md) | Específica | Rascunho |
| 19.18 | [Container Registries](19.18-container-registries.md) | Específica | Rascunho |
| 19.19 | [Segurança em Containers](19.19-seguranca-em-containers.md) | Específica ampla | Rascunho |
| 19.20 | [Desafio: Containerizando o PetCare OS](19.20-desafio-containerizando-o-petcare-os.md) | Desafio intermediário | Rascunho |
| 19.21 | [Kubernetes](19.21-kubernetes.md) | Guarda-chuva curta | Rascunho |
| 19.22 | [Configurando Kubernetes](19.22-configurando-kubernetes.md) | Específica prática | Rascunho |
| 19.23 | [Rodando Aplicações no Kubernetes](19.23-rodando-aplicações-no-kubernetes.md) | Específica prática | Rascunho |
| 19.24 | [Serviços e Conectividade](19.24-servicos-e-conectividade.md) | Específica | Rascunho |
| 19.25 | [Configuração e Gerenciamento](19.25-configuração-e-gerenciamento.md) | Específica | Rascunho |
| 19.26 | [Gerenciamento de Recursos](19.26-gerenciamento-de-recursos.md) | Específica | Rascunho |
| 19.27 | [Storage and Volumes](19.27-storage-and-volumes.md) | Específica | Rascunho |
| 19.28 | [Segurança no Kubernetes](19.28-seguranca-no-kubernetes.md) | Específica ampla | Rascunho |
| 19.29 | [Monitoramento e Logging no Kubernetes](19.29-monitoramento-e-logging-no-kubernetes.md) | Específica | Rascunho |
| 19.30 | [Autoscaling](19.30-autoscaling.md) | Específica | Rascunho |
| 19.31 | [Padrões de Deployment](19.31-padrões-de-deployment.md) | Específica | Rascunho |
| 19.32 | [Tópicos Avançados de Kubernetes](19.32-topicos-avancados-de-kubernetes.md) | Guarda-chuva de fechamento | Rascunho |
| 19.33 | [Projeto Prático: Pipeline de Build, Registry e Deploy em Kubernetes](19.33-projeto-prático-pipeline-de-build-registry-e-deploy-em-kubernetes.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em três blocos que devem ser estudados nesta ordem. Dentro de cada bloco, siga a sequência da tabela.

**Bloco A — CI/CD e DevOps** · aulas 19.01–19.09
O ciclo de entrega de software: o que é DevOps na prática, como pipelines de CI/CD funcionam, como o deploy é modelado, como Infrastructure as Code entra em automação e como garantir revisão, aprovação, credenciais seguras, compliance e detecção de drift em pipelines.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Docker e Containers** · aulas 19.10–19.19
Empacotamento de aplicações: conceitos de containers, build de imagens, Docker CLI, execução, persistência de dados, bancos em containers, networking, registries e segurança em containers.
Pré-requisito: Bloco A (entender o contexto de entrega antes de empacotar a aplicação).

> **✦ Desafio de bloco — aula 19.20:** antes de avançar para Kubernetes, complete o [Desafio: Containerizando o PetCare OS](19.20-desafio-containerizando-o-petcare-os.md). O desafio aplica todo o conhecimento de containers em uma aplicação real e pede uma justificativa objetiva sobre quando Kubernetes seria overengineering. É o passo que separa quem estudou containers de quem sabe usá-los com critério.

**Bloco C — Kubernetes** · aulas 19.21–19.32
Orquestração: configuração do cluster, execução de workloads, serviços e conectividade, configuração com ConfigMaps e Secrets, gerenciamento de recursos, storage, segurança, monitoramento, autoscaling, padrões de deployment e tópicos avançados.
Pré-requisito: Bloco B + Desafio 19.20 (Kubernetes orquestra containers; sem entender containers na prática, o Kubernetes não faz sentido).

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Projeto ou Prática do Módulo

Construir um fluxo pequeno de entrega para uma aplicação já estudada na formação:

1. escolher uma API Node.js simples com endpoint de saúde;
2. definir pipeline com validação, testes e build;
3. criar imagem de container versionada;
4. publicar a imagem em um registry;
5. escrever manifestos Kubernetes para Deployment, Service, ConfigMap e Secret;
6. configurar recursos mínimos e probes;
7. aplicar em um cluster de laboratório;
8. verificar logs, eventos, saúde da aplicação e estratégia de rollback;
9. documentar riscos, permissões, custos e próximos passos.

## O Que Revisar Antes de Avançar

- Git, GitHub, branches, pull requests e code review.
- Testes em CI, qualidade, observabilidade, logs, métricas e alertas.
- Deploy de aplicações Next.js e backend com Node.js.
- IAM, VPC/networking, secrets, storage, bancos gerenciados e custos em cloud.
- Terraform, state, remote state, plan, apply, drift, modules e ambientes.
- Segurança em APIs, menor privilégio e configuração sensível.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo DevOps, Containers e Kubernetes de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina CI/CD, deploy, IaC em pipelines, Docker, containers, imagens, registries, networking, persistência, segurança em containers e fundamentos práticos de Kubernetes.
- Objetivo do módulo: Quero entender como aplicações rodam, escalam e são entregues em ambientes modernos.
- Pré-requisitos: Git, backend, APIs, bancos, segurança, observabilidade, cloud fundamentals e Infrastructure as Code.

Crie uma revisão guiada com perguntas conceituais, exercícios práticos, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial do Docker quando uma aula exigir detalhes de ferramenta.
- Documentação oficial do Kubernetes quando uma aula exigir detalhes de API, comandos ou configuração.
- Documentação oficial das ferramentas de CI/CD, registries e provedores de cloud quando exemplos específicos forem usados.

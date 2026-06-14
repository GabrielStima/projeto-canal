<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# DevOps, CI/CD e Containers

</div>

Este módulo mostra como aplicações saem do repositório, passam por validação automatizada, viram imagens executáveis e são publicadas em registries.

Até aqui, você já estudou fundamentos de cloud, Infrastructure as Code, Terraform, state, ambientes, segredos, observabilidade, segurança, arquitetura e aplicações backend. Agora o foco é conectar entrega, empacotamento e publicação de artefatos.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o papel de DevOps, CI/CD e deploy no ciclo de entrega;
- entender como Infrastructure as Code entra em pipelines com revisão, aprovação e segurança;
- construir, executar, versionar e publicar imagens de container;
- reconhecer cuidados de persistência, networking e segurança em containers;
- decidir quando containers sozinhos resolvem o problema e quando Kubernetes seria overengineering.

## Por Que Este Módulo Existe

Saber programar uma aplicação é apenas uma parte da vida dela. Em projetos reais, o código precisa passar por validação, build, empacotamento, publicação e configuração antes de chegar em produção. Sem esse caminho, cada entrega depende de passos manuais, máquinas específicas e conhecimento espalhado.

DevOps, CI/CD e containers entram para reduzir essa distância entre código e execução. CI/CD organiza o fluxo de entrega. Docker cria uma unidade previsível de empacotamento. O desafio intermediário do módulo aplica esses conceitos no PetCare OS e deixa claro o limite entre "containers são suficientes" e "precisamos de orquestração".

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
| 19a.00 | [DevOps, CI/CD e Containers](19a.00-devops-ci-cd-e-containers.md) | Guarda-chuva | Auditada |
| 19a.01 | [O que é DevOps na Prática](19a.01-o-que-e-devops-na-pratica.md) | Específica ampla | Auditada |
| 19a.02 | [CI/CD](19a.02-ci-cd.md) | Específica | Auditada |
| 19a.03 | [Deploy](19a.03-deploy.md) | Específica | Auditada |
| 19a.04 | [Infrastructure as Code em CI/CD](19a.04-infrastructure-as-code-em-ci-cd.md) | Específica | Auditada |
| 19a.05 | [Geração e Revisão de Planos de Infraestrutura](19a.05-geracao-e-revisao-de-planos-de-infraestrutura.md) | Específica prática | Auditada |
| 19a.06 | [Aprovação e Aplicação Automatizada de Mudanças](19a.06-aprovacao-e-aplicacao-automatizada-de-mudancas.md) | Específica prática | Auditada |
| 19a.07 | [Credenciais Temporárias para Automação](19a.07-credenciais-temporarias-para-automacao.md) | Específica | Auditada |
| 19a.08 | [Policy as Code](19a.08-policy-as-code.md) | Específica ampla | Auditada |
| 19a.09 | [Detecção Automatizada de Drift](19a.09-deteccao-automatizada-de-drift.md) | Específica | Auditada |
| 19a.10 | [Docker e Containers](19a.10-docker-e-containers.md) | Guarda-chuva curta | Auditada |
| 19a.11 | [Básico de Containers](19a.11-basico-de-containers.md) | Específica | Auditada |
| 19a.12 | [Building Container Images](19a.12-building-container-images.md) | Específica prática | Auditada |
| 19a.13 | [Docker CLI](19a.13-docker-cli.md) | Específica prática | Auditada |
| 19a.14 | [Running Containers](19a.14-running-containers.md) | Específica prática | Auditada |
| 19a.15 | [Persistência de Dados](19a.15-persistencia-de-dados.md) | Específica | Auditada |
| 19a.16 | [Bancos em Containers](19a.16-bancos-em-containers.md) | Específica prática | Auditada |
| 19a.17 | [Networking em Containers](19a.17-networking-em-containers.md) | Específica | Auditada |
| 19a.18 | [Container Registries](19a.18-container-registries.md) | Específica | Auditada |
| 19a.19 | [Segurança em Containers](19a.19-seguranca-em-containers.md) | Específica ampla | Auditada |
| 19a.20 | [Desafio: Containerizando o PetCare OS](19a.20-desafio-containerizando-o-petcare-os.md) | Desafio intermediário | Auditada |
| 19a.21 | [Projeto Prático: Pipeline de Build e Registry](19a.21-projeto-pratico-pipeline-de-build-e-registry.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em dois blocos que devem ser estudados nesta ordem. Dentro de cada bloco, siga a sequência da tabela.

**Bloco A — CI/CD e DevOps** · aulas 19a.01–19a.09
O ciclo de entrega de software: o que é DevOps na prática, como pipelines de CI/CD funcionam, como o deploy é modelado, como Infrastructure as Code entra em automação e como garantir revisão, aprovação, credenciais seguras, compliance e detecção de drift em pipelines.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Docker e Containers** · aulas 19a.10–19a.19
Empacotamento de aplicações: conceitos de containers, build de imagens, Docker CLI, execução, persistência de dados, bancos em containers, networking, registries e segurança em containers.
Pré-requisito: Bloco A (entender o contexto de entrega antes de empacotar a aplicação).

> **✦ Desafio de bloco — aula 19a.20:** antes de avançar para o módulo 19B, complete o [Desafio: Containerizando o PetCare OS](19a.20-desafio-containerizando-o-petcare-os.md). O desafio aplica todo o conhecimento de containers em uma aplicação real e pede uma justificativa objetiva sobre quando Kubernetes seria overengineering. É o passo que separa quem estudou containers de quem sabe usá-los com critério.

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Exercícios

- [Exercício 01 — Fluxo de Entrega e Rollback](exercicios/01-fluxo-de-entrega-e-rollback.md)
- [Exercício 02 — IaC Segura no Pipeline](exercicios/02-iac-segura-no-pipeline.md)
- [Exercício 03 — Imagem e Contrato de Execução](exercicios/03-imagem-e-contrato-de-execucao.md)
- [Exercício 04 — Stack Compose, Dados e Rede](exercicios/04-stack-compose-dados-e-rede.md)
- [Exercício 05 — Registry, Rastreabilidade e Segurança](exercicios/05-registry-rastreabilidade-e-seguranca.md)
- [Exercício 06 — Containerizando o PetCare OS](exercicios/06-containerizando-o-petcare-os.md)
- [Atividade Final — Pipeline de Build e Registry](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, uma mesma entrega evolui em duas partes.

No bloco de CI/CD, você define a política de validação, aprovação, rollback e automação segura de infraestrutura. No bloco de containers, você cria a imagem e a stack local que o pipeline utilizará.

O exercício 06 é obrigatório para continuidade: ele demonstra que Dockerfile, Compose, rede, persistência, configuração, saúde e logs funcionam como um conjunto. A atividade final então automatiza testes, build, verificação e publicação da mesma imagem em um registry.

O resultado que seguirá para o módulo 19B é uma imagem rastreável, não uma nova build criada diretamente no cluster.

## O Que Revisar Antes de Avançar

- Git, GitHub, branches, pull requests e code review.
- Testes em CI, qualidade, observabilidade, logs, métricas e alertas.
- Deploy de aplicações Next.js e backend com Node.js.
- IAM, VPC/networking, secrets, storage, bancos gerenciados e custos em cloud.
- Terraform, state, remote state, plan, apply, drift, modules e ambientes.
- Segurança em APIs, menor privilégio e configuração sensível.

## Próximo Módulo

- [19B — Kubernetes](../19b-kubernetes/): orquestração de containers, workloads, serviços, configuração, recursos, storage e padrões de deployment.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo DevOps, CI/CD e Containers de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina CI/CD, deploy, IaC em pipelines, Docker, containers, imagens, registries, networking, persistência e segurança em containers.
- Objetivo do módulo: Quero entender como aplicações são validadas, empacotadas e publicadas em ambientes modernos.
- Pré-requisitos: Git, backend, APIs, bancos, segurança, observabilidade, cloud fundamentals e Infrastructure as Code.

Crie uma revisão guiada com perguntas conceituais, exercícios práticos, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial do Docker quando uma aula exigir detalhes de ferramenta.
- Documentação oficial das ferramentas de CI/CD, registries e provedores de cloud quando exemplos específicos forem usados.

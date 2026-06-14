<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Cloud Fundamentals

</div>

Este módulo apresenta os principais blocos de construção de cloud antes de entrar em Infrastructure as Code, containers, Kubernetes, SRE e system design.

Até aqui, você já estudou aplicações web, backend, bancos de dados, APIs, segurança, observabilidade, arquitetura, sistemas distribuídos e comunicação assíncrona. Agora o foco é entender onde essas aplicações rodam quando saem da máquina local: regiões, redes, permissões, bancos gerenciados, storage, filas, serverless, CDN, segredos, custos e recuperação.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar os principais serviços e conceitos de cloud sem depender de um provedor específico;
- reconhecer como identidade, rede, dados, processamento, entrega e segurança se conectam;
- diferenciar serviço gerenciado, infraestrutura própria, serverless e recursos provisionados;
- desenhar uma infraestrutura cloud simples para uma aplicação fullstack;
- identificar riscos de exposição, custo, perda de dados e indisponibilidade;
- se preparar para estudar Infrastructure as Code, containers, Kubernetes, SRE e system design.

## Por Que Este Módulo Existe

Cloud não é apenas "um computador de outra pessoa". Para uma aplicação real funcionar em produção, ela precisa de identidade, rede, armazenamento, banco, filas, deploy, configuração, segredos, entrega de conteúdo, backup, observabilidade, segurança e controle de custos.

Sem essa base, ferramentas como Terraform, Docker e Kubernetes viram uma pilha de comandos sem contexto. Este módulo existe para ensinar o vocabulário e as escolhas fundamentais antes de automatizar infraestrutura ou operar sistemas maiores.

## Pré-requisitos

- Fundamentos de internet, DNS, HTTP, cliente/servidor, request/response e estado.
- Backend com Node.js, APIs, bancos de dados, ORMs, logging e failure modes.
- Segurança na web, autenticação, autorização, rate limiting e segurança em APIs.
- Observabilidade, métricas, tracing, monitoramento, alertas e testes de carga.
- Arquitetura de software, sistemas distribuídos, serverless em nível conceitual e Twelve-Factor Apps.
- Dados em tempo real, filas, brokers, pub/sub, background jobs e idempotência.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 17.00 | [Cloud Fundamentals](17.00-cloud-fundamentals.md) | Guarda-chuva | Auditada |
| 17.01 | [Regiões, Zonas e Modelo Global de Cloud](17.01-regioes-zonas-e-modelo-global-de-cloud.md) | Específica | Auditada |
| 17.02 | [IAM: Identidade, Permissões e Princípio do Menor Privilégio](17.02-iam-identidade-permissoes-e-principio-do-menor-privilegio.md) | Específica | Auditada |
| 17.03 | [VPC e Networking em Cloud](17.03-vpc-e-networking-em-cloud.md) | Específica ampla | Auditada |
| 17.04 | [Object Storage](17.04-object-storage.md) | Específica | Auditada |
| 17.05 | [CDN e Entrega de Conteúdo](17.05-cdn-e-entrega-de-conteudo.md) | Específica | Auditada |
| 17.06 | [Managed Databases](17.06-managed-databases.md) | Específica | Auditada |
| 17.07 | [Filas Gerenciadas](17.07-filas-gerenciadas.md) | Específica | Auditada |
| 17.08 | [Serverless na Prática](17.08-serverless-na-pratica.md) | Específica prática | Auditada |
| 17.09 | [Secrets e Configuração Sensível](17.09-secrets-e-configuracao-sensivel.md) | Específica | Auditada |
| 17.10 | [Backup e Disaster Recovery](17.10-backup-e-disaster-recovery.md) | Específica | Auditada |
| 17.11 | [Custos em Cloud](17.11-custos-em-cloud.md) | Específica | Auditada |
| 17.12 | [Fundamentos de FinOps](17.12-fundamentos-de-finops.md) | Específica ampla | Auditada |
| 17.13 | [Projeto Prático: Desenhando a Infraestrutura Cloud de uma Aplicação](17.13-projeto-pratico-desenhando-a-infraestrutura-cloud-de-uma-aplicacao.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em 4 blocos. Siga a ordem dos blocos e preserve o mesmo documento de arquitetura ao longo dos exercícios.

**Bloco A — Requisitos, identidade e rede** · aulas [17.00–17.03]
Define região, disponibilidade, responsabilidades, IAM e caminhos de tráfego.
Pré-requisito: arquitetura e segurança de aplicações.

**Bloco B — Dados e entrega** · aulas [17.04–17.06]
Escolhe storage, CDN e banco gerenciado conforme o tipo de dado e sua operação.
Pré-requisito: Bloco A.

**Bloco C — Processamento, segredos e recuperação** · aulas [17.07–17.10]
Leva o fluxo assíncrono para serviços cloud e define segredos, backup, RPO e RTO.
Pré-requisito: Bloco B e o fluxo produzido no módulo 16.

**Bloco D — Custos e síntese** · aulas [17.11–17.13]
Explicita motores de custo, ownership, orçamento, riscos e a arquitetura cloud mínima.
Pré-requisito: Bloco C.

## Exercícios

- [Exercício 01 — Requisitos e Responsabilidades Cloud](exercicios/01-requisitos-e-responsabilidades-cloud.md)
- [Exercício 02 — Identidade, Rede e Fluxo](exercicios/02-identidade-rede-e-fluxo.md)
- [Exercício 03 — Dados, Storage e Entrega](exercicios/03-dados-storage-e-entrega.md)
- [Exercício 04 — Processamento e Serviços Gerenciados](exercicios/04-processamento-e-servicos-gerenciados.md)
- [Exercício 05 — Segredos, Backup e Recuperação](exercicios/05-segredos-backup-e-recuperacao.md)
- [Exercício 06 — Custos, Tags e Orçamento](exercicios/06-custos-tags-e-orcamento.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você transformará os requisitos e fluxos já construídos em `docs/arquitetura-cloud.md`.

Os exercícios acrescentam progressivamente:

1. requisitos, região e divisão de responsabilidades;
2. topologia de rede e permissões mínimas;
3. decisões para banco, objetos, frontend, logs e backups;
4. mapeamento do fluxo assíncrono para serviços gerenciados;
5. segredos, restauração, RPO e RTO;
6. estimativa de custos, tags, orçamento e alertas.

A atividade final consolida uma arquitetura cloud mínima, independente de provedor e pronta para ser convertida em Terraform. Nenhum recurso pago precisa ser provisionado.

## O Que Revisar Antes de Avançar

- DNS, HTTP, cache, cliente/servidor e estado.
- APIs, autenticação, autorização e segurança em APIs.
- Bancos de dados, migrations, backup, restore e performance.
- Logging, métricas, tracing, monitoramento e alertas.
- Sistemas distribuídos, filas, pub/sub, background jobs e idempotência.
- Twelve-Factor Apps e serverless em nível conceitual.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Cloud Fundamentals de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina fundamentos de cloud, incluindo regiões, zonas, IAM, VPC/networking, object storage, CDN, managed databases, filas gerenciadas, serverless, secrets, backup, disaster recovery, custos e FinOps.
- Objetivo do módulo: Quero entender os principais blocos de cloud antes de estudar Infrastructure as Code, containers, Kubernetes, SRE e system design.
- Pré-requisitos: HTTP, APIs, bancos de dados, segurança, observabilidade, arquitetura, sistemas distribuídos, filas, pub/sub e idempotência.

Crie uma revisão guiada com perguntas conceituais, exercícios práticos, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial dos provedores de cloud somente quando uma aula exigir detalhes de ferramenta ou serviço específico.
- Documentação oficial de práticas de segurança, operação e custos quando necessário para aprofundamento.

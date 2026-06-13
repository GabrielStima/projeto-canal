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
| 17.00 | [Cloud Fundamentals](17.00-cloud-fundamentals.md) | Guarda-chuva | Rascunho |
| 17.01 | [Regiões, Zonas e Modelo Global de Cloud](17.01-regioes-zonas-e-modelo-global-de-cloud.md) | Específica | Rascunho |
| 17.02 | [IAM: Identidade, Permissões e Princípio do Menor Privilégio](17.02-iam-identidade-permissoes-e-principio-do-menor-privilegio.md) | Específica | Rascunho |
| 17.03 | [VPC e Networking em Cloud](17.03-vpc-e-networking-em-cloud.md) | Específica ampla | Rascunho |
| 17.04 | [Object Storage](17.04-object-storage.md) | Específica | Rascunho |
| 17.05 | [CDN e Entrega de Conteúdo](17.05-cdn-e-entrega-de-conteudo.md) | Específica | Rascunho |
| 17.06 | [Managed Databases](17.06-managed-databases.md) | Específica | Rascunho |
| 17.07 | [Filas Gerenciadas](17.07-filas-gerenciadas.md) | Específica | Rascunho |
| 17.08 | [Serverless na Prática](17.08-serverless-na-pratica.md) | Específica prática | Rascunho |
| 17.09 | [Secrets e Configuração Sensível](17.09-secrets-e-configuracao-sensivel.md) | Específica | Rascunho |
| 17.10 | [Backup e Disaster Recovery](17.10-backup-e-disaster-recovery.md) | Específica | Rascunho |
| 17.11 | [Custos em Cloud](17.11-custos-em-cloud.md) | Específica | Rascunho |
| 17.12 | [Fundamentos de FinOps](17.12-fundamentos-de-finops.md) | Específica ampla | Rascunho |
| 17.13 | [Projeto Prático: Desenhando a Infraestrutura Cloud de uma Aplicação](17.13-projeto-pratico-desenhando-a-infraestrutura-cloud-de-uma-aplicacao.md) | Síntese prática | Rascunho |


## Exercícios

- [Exercício 01 — O Fim do Localhost](exercicios/01-fim-do-localhost.md)
- [Exercício 02 — Desenhando o IAM da Clínica](exercicios/02-iam-clinica.md)
- [Exercício 03 — Isolamento via VPC](exercicios/03-isolamento-vpc.md)
- [Exercício 04 — CDN no Frontend](exercicios/04-cdn.md)
- [Exercício 05 — Casos Serverless](exercicios/05-casos-serverless.md)
- [Exercício 06 — Injeção de Segredos](exercicios/06-injecao-segredos.md)
- [Exercício 07 — Monitoramento e Tags](exercicios/07-monitoramento-finops.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você aplicará o **marco de cloud** arquitetando a topologia física e lógica em provedores como AWS/GCP/Azure para o PetCare OS:

1. Elabore o Diagrama de Rede listando o isolamento via **VPC** (Subnets públicas para Balizadores de Carga e privadas para Bancos Relacionais).
2. Modele a política base de **IAM**, usando o princípio do menor privilégio para a API do Node que consumirá os arquivos médicos armazenados no S3/Blob Storage.
3. Determine a viabilidade de alocar o histórico morto do PetCare em classes frias de Storage (Glacier) para práticas eficientes de **FinOps**.
4. Escreva as proteções básicas de **Segredos e Variáveis de Ambiente**, banindo hardcodings da aplicação rumo ao Cloud Secrets Manager.
5. Defina e justifique o **RPO/RTO** que a clínica veterinária deve adotar caso ocorra um desastre massivo num datacenter no meio da tarde.

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

# Arquitetura de Software

Este modulo marca a passagem do design interno do codigo para a organizacao de sistemas inteiros. Ate aqui, voce ja estudou frontend, backend, bancos de dados, APIs, seguranca, qualidade, testes, observabilidade, performance e design de software.

Agora o foco e entender como partes maiores de um sistema se relacionam: componentes, limites, camadas, dependencias, estilos arquiteturais, padroes, comunicacao, distribuicao e trade-offs. Arquitetura de software nao e escolher nomes bonitos para pastas. E tomar decisoes que preservam evolucao, operacao e clareza quando o sistema cresce.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar o que arquitetura de software organiza alem de arquivos e classes;
- diferenciar decisoes de design, arquitetura e infraestrutura;
- reconhecer acoplamento, coesao e boundaries em nivel de sistema;
- separar politica de negocio de detalhes tecnicos;
- comparar estilos como camadas, MVC, monolito, Clean Architecture, DDD, SOA e microservicos;
- entender os custos de sistemas distribuidos, messaging, CQRS e Event Sourcing;
- avaliar padroes arquiteturais sem tratar nenhum deles como receita universal;
- registrar trade-offs arquiteturais em uma decisao clara.

## Por Que Este Modulo Existe

No modulo anterior, voce aprendeu a organizar comportamento dentro do codigo. Mas sistemas reais crescem para alem de uma classe, uma funcao ou um endpoint. Eles passam a ter modulos, contextos, bancos, filas, APIs, jobs, deploys, observabilidade, times diferentes e mudancas acontecendo em ritmos diferentes.

Arquitetura de software existe para tornar essas decisoes explicitas. Ela ajuda a decidir onde colocar regras, onde criar limites, quando distribuir, quando nao distribuir, como proteger o dominio e como evitar que detalhes de framework, banco ou infraestrutura dominem o sistema inteiro.

## Pre-requisitos

- Saber escrever JavaScript moderno e TypeScript.
- Entender backend com Node.js, APIs, bancos de dados, ORMs e failure modes.
- Ter estudado API design, contratos, versionamento e backward compatibility.
- Ter estudado seguranca, autenticacao, autorizacao e riscos comuns de APIs.
- Entender qualidade, testes, testabilidade, observabilidade e performance.
- Ter concluido o modulo 14 de Design de Software.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 15.00 | [Arquitetura de Software](15.00-arquitetura-de-software.md) | Guarda-chuva | Rascunho |
| 15.01 | [Do Design de Software a Arquitetura](15.01-do-design-de-software-a-arquitetura.md) | Especifica ampla | Rascunho |
| 15.02 | [Principios Arquiteturais](15.02-principios-arquiteturais.md) | Guarda-chuva curta | Rascunho |
| 15.03 | [Acoplamento e Coesao em Nivel Arquitetural](15.03-acoplamento-e-coesao-em-nivel-arquitetural.md) | Especifica | Rascunho |
| 15.04 | [Principios de Componentes](15.04-principios-de-componentes.md) | Especifica ampla | Rascunho |
| 15.05 | [Boundaries](15.05-boundaries.md) | Especifica | Rascunho |
| 15.06 | [Policy vs Detail](15.06-policy-vs-detail.md) | Especifica | Rascunho |
| 15.07 | [Estilos Arquiteturais](15.07-estilos-arquiteturais.md) | Guarda-chuva | Rascunho |
| 15.08 | [Arquitetura em Camadas e Estrutura do Sistema](15.08-arquitetura-em-camadas-e-estrutura-do-sistema.md) | Especifica | Rascunho |
| 15.09 | [MVC](15.09-mvc.md) | Especifica | Rascunho |
| 15.10 | [Monolito](15.10-monolito.md) | Especifica | Rascunho |
| 15.11 | [Clean Architecture](15.11-clean-architecture.md) | Especifica ampla | Rascunho |
| 15.12 | [DDD](15.12-ddd.md) | Especifica ampla | Rascunho |
| 15.13 | [Padroes Arquiteturais](15.13-padroes-arquiteturais.md) | Guarda-chuva | Rascunho |
| 15.14 | [SOA](15.14-soa.md) | Especifica | Rascunho |
| 15.15 | [Microservicos](15.15-microservicos.md) | Especifica ampla | Rascunho |
| 15.16 | [Sistemas Distribuidos](15.16-sistemas-distribuidos.md) | Guarda-chuva curta | Rascunho |
| 15.17 | [Messaging e Filas de Mensagens](15.17-messaging-e-filas-de-mensagens.md) | Especifica | Rascunho |
| 15.18 | [CQRS](15.18-cqrs.md) | Especifica | Rascunho |
| 15.19 | [Event Sourcing](15.19-event-sourcing.md) | Especifica | Rascunho |
| 15.20 | [Serverless](15.20-serverless.md) | Especifica | Rascunho |
| 15.21 | [Twelve-Factor Apps](15.21-twelve-factor-apps.md) | Especifica pratica | Rascunho |
| 15.22 | [Service Mesh](15.22-service-mesh.md) | Especifica conceitual | Rascunho |
| 15.23 | [Blackboard](15.23-blackboard.md) | Especifica conceitual | Rascunho |
| 15.24 | [Microkernel](15.24-microkernel.md) | Especifica conceitual | Rascunho |
| 15.25 | [Projeto Pratico: Arquitetando uma API para Evolucao](15.25-projeto-pratico-arquitetando-uma-api-para-evolucao.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Arquitete a evolucao de uma API criada em modulos anteriores:

1. escolha um fluxo com regras reais;
2. identifique limites, componentes e dependencias;
3. separe politica de negocio de detalhes tecnicos;
4. escolha um estilo arquitetural simples para o contexto;
5. avalie se messaging, CQRS ou eventos fazem sentido;
6. descreva trade-offs e riscos;
7. proponha uma evolucao incremental sem reescrever tudo.

## O Que Revisar Antes de Avancar

- Design de software, SOLID, composicao, abstracoes e padroes.
- Backend com Node.js, APIs, contratos, bancos de dados e ORMs.
- Testabilidade, testes de integracao, contract tests e quality gates.
- Logging, metricas, tracing, monitoramento e failure modes.
- Autenticacao, autorizacao e seguranca em APIs.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Arquitetura de Software de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina componentes, boundaries, policy vs detail, estilos arquiteturais, padroes, DDD, MVC, monolito, microservicos, SOA, serverless, Clean Architecture, messaging, CQRS, Event Sourcing e Twelve-Factor Apps.
- Objetivo do modulo: Quero organizar sistemas alem de arquivos e classes, escolhendo limites e trade-offs com criterio.
- Pre-requisitos: Backend, APIs, bancos de dados, seguranca, qualidade, observabilidade, performance e design de software.

Crie uma revisao guiada com perguntas conceituais, exercicios de arquitetura, perguntas de entrevista, exemplos em projetos reais e uma avaliacao final.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Materiais internos do proprio projeto.
- Livros e materiais conceituais sobre arquitetura de software, Clean Architecture, DDD, sistemas distribuidos e padroes arquiteturais.
- Documentacao oficial de ferramentas especificas somente quando uma aula exigir detalhes de ferramenta.

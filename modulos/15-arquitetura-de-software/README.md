<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Arquitetura de Software

</div>

Este módulo marca a passagem do design interno do código para a organização de sistemas inteiros. Até aqui, você já estudou frontend, backend, bancos de dados, APIs, segurança, qualidade, testes, observabilidade, performance e design de software.

Agora o foco é entender como partes maiores de um sistema se relacionam: componentes, limites, camadas, dependências, estilos arquiteturais, padrões, comunicação, distribuição e trade-offs. Arquitetura de software não é escolher nomes bonitos para pastas. É tomar decisões que preservam evolução, operação e clareza quando o sistema cresce.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o que arquitetura de software organiza além de arquivos e classes;
- diferenciar decisões de design, arquitetura e infraestrutura;
- reconhecer acoplamento, coesão e boundaries em nível de sistema;
- separar política de negócio de detalhes técnicos;
- comparar estilos como camadas, MVC, monólito, Clean Architecture, DDD, SOA e microsserviços;
- entender os custos de sistemas distribuídos, messaging, CQRS e Event Sourcing;
- avaliar padrões arquiteturais sem tratar nenhum deles como receita universal;
- registrar trade-offs arquiteturais em uma decisão clara.

## Por Que Este Módulo Existe

No módulo anterior, você aprendeu a organizar comportamento dentro do código. Mas sistemas reais crescem para além de uma classe, uma função ou um endpoint. Eles passam a ter módulos, contextos, bancos, filas, APIs, jobs, deploys, observabilidade, times diferentes e mudanças acontecendo em ritmos diferentes.

Arquitetura de software existe para tornar essas decisões explícitas. Ela ajuda a decidir onde colocar regras, onde criar limites, quando distribuir, quando não distribuir, como proteger o domínio e como evitar que detalhes de framework, banco ou infraestrutura dominem o sistema inteiro.

## Pré-requisitos

- Saber escrever JavaScript moderno e TypeScript.
- Entender backend com Node.js, APIs, bancos de dados, ORMs e failure modes.
- Ter estudado API design, contratos, versionamento e backward compatibility.
- Ter estudado segurança, autenticação, autorização e riscos comuns de APIs.
- Entender qualidade, testes, testabilidade, observabilidade e performance.
- Ter concluído o módulo 14 de Design de Software.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 15.00 | [Arquitetura de Software](15.00-arquitetura-de-software.md) | Guarda-chuva | Auditada |
| 15.01 | [Do Design de Software à Arquitetura](15.01-do-design-de-software-a-arquitetura.md) | Específica ampla | Auditada |
| 15.02 | [Princípios Arquiteturais](15.02-principios-arquiteturais.md) | Guarda-chuva curta | Auditada |
| 15.03 | [Acoplamento e Coesão em Nível Arquitetural](15.03-acoplamento-e-coesao-em-nivel-arquitetural.md) | Específica | Auditada |
| 15.04 | [Princípios de Componentes](15.04-principios-de-componentes.md) | Específica ampla | Auditada |
| 15.05 | [Boundaries](15.05-boundaries.md) | Específica | Auditada |
| 15.06 | [Policy vs Detail](15.06-policy-vs-detail.md) | Específica | Auditada |
| 15.07 | [Estilos Arquiteturais](15.07-estilos-arquiteturais.md) | Guarda-chuva | Auditada |
| 15.08 | [Arquitetura em Camadas e Estrutura do Sistema](15.08-arquitetura-em-camadas-e-estrutura-do-sistema.md) | Específica | Auditada |
| 15.09 | [MVC](15.09-mvc.md) | Específica | Auditada |
| 15.10 | [Monolito](15.10-monolito.md) | Específica | Auditada |
| 15.11 | [Clean Architecture](15.11-clean-architecture.md) | Específica ampla | Auditada |
| 15.12 | [DDD](15.12-ddd.md) | Específica ampla | Auditada |
| 15.13 | [Padrões Arquiteturais](15.13-padroes-arquiteturais.md) | Guarda-chuva | Auditada |
| 15.14 | [SOA](15.14-soa.md) | Específica | Auditada |
| 15.15 | [Microsserviços](15.15-microservicos.md) | Específica ampla | Auditada |
| 15.16 | [Sistemas Distribuídos](15.16-sistemas-distribuidos.md) | Guarda-chuva curta | Auditada |
| 15.17 | [Messaging e Filas de Mensagens](15.17-messaging-e-filas-de-mensagens.md) | Específica | Auditada |
| 15.18 | [CQRS](15.18-cqrs.md) | Específica | Auditada |
| 15.19 | [Event Sourcing](15.19-event-sourcing.md) | Específica | Auditada |
| 15.20 | [Serverless](15.20-serverless.md) | Específica | Auditada |
| 15.21 | [Twelve-Factor Apps](15.21-twelve-factor-apps.md) | Específica prática | Auditada |
| 15.22 | [Service Mesh](15.22-service-mesh.md) | Específica conceitual | Auditada |
| 15.23 | [Blackboard](15.23-blackboard.md) | Específica conceitual | Auditada |
| 15.24 | [Microkernel](15.24-microkernel.md) | Específica conceitual | Auditada |
| 15.25 | [Projeto Prático: Arquitetando uma API para Evolução](15.25-projeto-pratico-arquitetando-uma-api-para-evolucao.md) | Síntese prática | Auditada |


## Trilha de Estudo

Este módulo está organizado em 5 blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Do código ao sistema** · aulas [15.00–15.02]
Transição do design de software para arquitetura e princípios arquiteturais.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Componentes e limites** · aulas [15.03–15.06]
Acoplamento, coesão, boundaries, princípios de componentes e policy vs detail.
Pré-requisito: Bloco A.

**Bloco C — Estilos arquiteturais clássicos** · aulas [15.07–15.12]
Camadas, MVC, monólito, Clean Architecture e DDD.
Pré-requisito: Bloco B.

**Bloco D — Distribuição e comunicação** · aulas [15.13–15.19]
SOA, microsserviços, sistemas distribuídos, messaging, CQRS e Event Sourcing.
Pré-requisito: Bloco C.

**Bloco E — Operação, trade-offs e prática** · aulas [15.20–15.25]
Serverless, Twelve-Factor Apps, service mesh, blackboard, microkernel e projeto prático.
Pré-requisito: Bloco D.

> Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

- [Exercício 01 — Diagnóstico e Forças Arquiteturais](exercicios/01-diagnostico-e-forcas-arquiteturais.md)
- [Exercício 02 — Componentes, Limites e Políticas](exercicios/02-componentes-limites-e-politicas.md)
- [Exercício 03 — Comparando Estilos Arquiteturais](exercicios/03-comparando-estilos-arquiteturais.md)
- [Exercício 04 — Distribuição e Consistência](exercicios/04-distribuicao-e-consistencia.md)
- [Exercício 05 — Messaging, CQRS e Eventos](exercicios/05-messaging-cqrs-e-eventos.md)
- [Exercício 06 — Operação e Alternativas Arquiteturais](exercicios/06-operacao-e-alternativas-arquiteturais.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você revisará a arquitetura atual do PetCare OS antes de adicionar infraestrutura. Os exercícios constroem progressivamente `docs/revisao-arquitetural.md`: primeiro registram forças e decisões implícitas, depois refinam componentes, limites, estilos e custos de distribuição.

Na atividade final, você produzirá:

1. um mapa dos módulos e de suas dependências;
2. uma arquitetura-base proporcional, preferencialmente um monólito modular enquanto não houver evidência para distribuir;
3. uma ADR com contexto, alternativas, decisão e consequências;
4. a especificação de um fluxo candidato a processamento assíncrono.

A fila e o worker não são implementados neste módulo. Essa especificação será retomada no módulo 16, depois que jobs, retentativas e idempotência forem estudados na prática.

## O Que Revisar Antes de Avançar

- Design de software, SOLID, composição, abstrações e padrões.
- Backend com Node.js, APIs, contratos, bancos de dados e ORMs.
- Testabilidade, testes de integração, contract tests e quality gates.
- Logging, métricas, tracing, monitoramento e failure modes.
- Autenticação, autorização e segurança em APIs.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Arquitetura de Software de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina componentes, boundaries, policy vs detail, estilos arquiteturais, padrões, DDD, MVC, monólito, microsserviços, SOA, serverless, Clean Architecture, messaging, CQRS, Event Sourcing e Twelve-Factor Apps.
- Objetivo do módulo: Quero organizar sistemas além de arquivos e classes, escolhendo limites e trade-offs com critério.
- Pré-requisitos: Backend, APIs, bancos de dados, segurança, qualidade, observabilidade, performance e design de software.

Crie uma revisão guiada com perguntas conceituais, exercícios de arquitetura, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Livros e materiais conceituais sobre arquitetura de software, Clean Architecture, DDD, sistemas distribuídos e padrões arquiteturais.
- Documentação oficial de ferramentas específicas somente quando uma aula exigir detalhes de ferramenta.

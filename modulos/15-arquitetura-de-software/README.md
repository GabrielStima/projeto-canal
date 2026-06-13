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
| 15.00 | [Arquitetura de Software](15.00-arquitetura-de-software.md) | Guarda-chuva | Rascunho |
| 15.01 | [Do Design de Software à Arquitetura](15.01-do-design-de-software-a-arquitetura.md) | Específica ampla | Rascunho |
| 15.02 | [Princípios Arquiteturais](15.02-principios-arquiteturais.md) | Guarda-chuva curta | Rascunho |
| 15.03 | [Acoplamento e Coesão em Nível Arquitetural](15.03-acoplamento-e-coesao-em-nivel-arquitetural.md) | Específica | Rascunho |
| 15.04 | [Princípios de Componentes](15.04-principios-de-componentes.md) | Específica ampla | Rascunho |
| 15.05 | [Boundaries](15.05-boundaries.md) | Específica | Rascunho |
| 15.06 | [Policy vs Detail](15.06-policy-vs-detail.md) | Específica | Rascunho |
| 15.07 | [Estilos Arquiteturais](15.07-estilos-arquiteturais.md) | Guarda-chuva | Rascunho |
| 15.08 | [Arquitetura em Camadas e Estrutura do Sistema](15.08-arquitetura-em-camadas-e-estrutura-do-sistema.md) | Específica | Rascunho |
| 15.09 | [MVC](15.09-mvc.md) | Específica | Rascunho |
| 15.10 | [Monolito](15.10-monolito.md) | Específica | Rascunho |
| 15.11 | [Clean Architecture](15.11-clean-architecture.md) | Específica ampla | Rascunho |
| 15.12 | [DDD](15.12-ddd.md) | Específica ampla | Rascunho |
| 15.13 | [Padrões Arquiteturais](15.13-padroes-arquiteturais.md) | Guarda-chuva | Rascunho |
| 15.14 | [SOA](15.14-soa.md) | Específica | Rascunho |
| 15.15 | [Microsserviços](15.15-microservicos.md) | Específica ampla | Rascunho |
| 15.16 | [Sistemas Distribuídos](15.16-sistemas-distribuidos.md) | Guarda-chuva curta | Rascunho |
| 15.17 | [Messaging e Filas de Mensagens](15.17-messaging-e-filas-de-mensagens.md) | Específica | Rascunho |
| 15.18 | [CQRS](15.18-cqrs.md) | Específica | Rascunho |
| 15.19 | [Event Sourcing](15.19-event-sourcing.md) | Específica | Rascunho |
| 15.20 | [Serverless](15.20-serverless.md) | Específica | Rascunho |
| 15.21 | [Twelve-Factor Apps](15.21-twelve-factor-apps.md) | Específica prática | Rascunho |
| 15.22 | [Service Mesh](15.22-service-mesh.md) | Específica conceitual | Rascunho |
| 15.23 | [Blackboard](15.23-blackboard.md) | Específica conceitual | Rascunho |
| 15.24 | [Microkernel](15.24-microkernel.md) | Específica conceitual | Rascunho |
| 15.25 | [Projeto Prático: Arquitetando uma API para Evolução](15.25-projeto-pratico-arquitetando-uma-api-para-evolucao.md) | Síntese prática | Rascunho |


## Exercícios

- [Exercício 01 — Diagnóstico Arquitetural](exercicios/01-diagnostico-arquitetural.md)
- [Exercício 02 — Coesão e Acoplamento em Larga Escala](exercicios/02-coesao-arquitetural.md)
- [Exercício 03 — Policy vs Detail](exercicios/03-policy-vs-detail.md)
- [Exercício 04 — Mapeando MVC e Camadas](exercicios/04-mvc-e-camadas.md)
- [Exercício 05 — Clean Architecture e DDD](exercicios/05-clean-architecture-ddd.md)
- [Exercício 06 — Microsserviços na Prática](exercicios/06-microsservicos.md)
- [Exercício 07 — Messaging no Módulo Clínico](exercicios/07-messaging.md)
- [Exercício 08 — Estilos Serverless vs Containers](exercicios/08-serverless.md)
- [Exercício 09 — Arquitetura Orientada a Eventos e Microkernel](exercicios/09-event-driven-microkernel.md)
- [Atividade Final do Módulo](exercicios/atividade-final-arquitetura.md)

## Projeto ou Prática do Módulo

Neste módulo, você aplicará o **Marco Arquitetural N6** no PetCare OS. Agora que o código interno tem bom design (N5), o foco expande para a resiliência e escala do ambiente em nuvem:

1. Elabore e crie seu primeiro **ADR** (Architecture Decision Record) detalhando o porquê adotar arquiteturas baseadas em Mensageria na clínica.
2. Isole as rotinas pesadas (Disparos em Massa, Relatórios e Processamento em Background) tirando do Loop do Controller/Express.
3. Configure a injeção simples de Filas (RabbitMQ ou Redis/BullMQ) dividindo o Monólito em Produtores (API) e Consumidores (Workers).
4. Aplique a barreira severa entre a Política (Regras do Hospital) e os Detalhes de entrega.
5. Registre e preveja como a Consistência Eventual mudará as exibições na interface do usuário (ex: Mensagens de "Processando...").

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
```

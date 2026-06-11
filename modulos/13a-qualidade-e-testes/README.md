<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Qualidade e Testes

</div>

Este módulo marca a passagem de "a aplicação funciona" para "a aplicação pode ser testada e sustentada quando cresce". Até aqui, você construiu bases de frontend, backend, bancos de dados, API design, autenticação, autorização e segurança.

Agora o foco muda para confiança. Um software profissional precisa ter critérios de qualidade, estratégia de testes proporcional ao risco e formas previsíveis de detectar regressões antes que cheguem à produção.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar qualidade de software em termos práticos;
- montar uma estratégia de testes proporcional ao risco;
- diferenciar testes unitários, de integração, end-to-end, contrato, carga e regressão;
- usar mocks, stubs e fakes sem esconder problemas importantes;
- entender como testes entram no fluxo de CI;
- reconhecer causas comuns de flaky tests;
- avaliar como arquitetura afeta testabilidade;
- interpretar análise estática, métricas e quality gates sem confundi-los com qualidade real.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a criar interfaces, APIs, bancos, contratos, autenticação e proteções básicas de segurança. Isso permite construir sistemas úteis, mas ainda não responde a perguntas comuns em projetos reais:

- como saber se uma mudança quebrou algo?
- que testes valem o custo de manter?
- como transformar falhas conhecidas em testes e decisões de design?
- quais critérios de qualidade podem ser automatizados sem eliminar julgamento humano?

Qualidade e testes são a base da confiança. Sem eles, observabilidade e performance (estudadas no próximo módulo) não têm referência do que é "certo".

## Pré-requisitos

- Entender HTTP, headers, status codes, request, response, cache e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Ter estudado frontend moderno, chamadas de API, formulários, validação, testes e performance em nível introdutório.
- Entender bancos de dados, queries, indexes, transactions e performance básica.
- Saber criar APIs backend com Node.js e lidar com erros, logs, banco, ORMs e failure modes.
- Ter estudado API design, contratos, OpenAPI, erros padronizados, idempotência, governance e contract testing introdutório.
- Ter estudado autenticação, autorização, segurança em APIs e rate limiting.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 13.00 | [Qualidade de Software](13.00-qualidade-testes-observabilidade-e-performance.md) | Guarda-chuva | Rascunho |
| 13.01 | [Qualidade de Software](13.01-qualidade-de-software.md) | Guarda-chuva curta | Rascunho |
| 13.02 | [Estratégia de Testes](13.02-estrategia-de-testes.md) | Específica ampla | Rascunho |
| 13.03 | [Pirâmide de Testes](13.03-piramide-de-testes.md) | Específica | Rascunho |
| 13.04 | [Testes Unitários](13.04-testes-unitarios.md) | Específica prática | Rascunho |
| 13.05 | [Mocks, Stubs e Fakes](13.05-mocks-stubs-e-fakes.md) | Específica | Rascunho |
| 13.06 | [Testes de Integração](13.06-testes-de-integracao.md) | Específica prática | Rascunho |
| 13.07 | [Contract Tests](13.07-contract-tests.md) | Específica prática | Rascunho |
| 13.08 | [Testes End-to-End](13.08-testes-end-to-end.md) | Específica prática | Rascunho |
| 13.09 | [Testes de Regressão](13.09-testes-de-regressao.md) | Específica | Rascunho |
| 13.10 | [Testes em CI](13.10-testes-em-ci.md) | Específica prática | Rascunho |
| 13.11 | [Flaky Tests](13.11-flaky-tests.md) | Específica | Rascunho |
| 13.12 | [Testabilidade de Arquitetura](13.12-testabilidade-de-arquitetura.md) | Guarda-chuva curta | Rascunho |
| 13.13 | [Análise Estática, Métricas e Quality Gates](13.13-analise-estatica-metricas-e-quality-gates.md) | Específica ampla | Rascunho |

## Trilha de Estudo

Este módulo está organizado em dois blocos progressivos:

**Bloco A — Fundamentos de Qualidade e Estratégia** · aulas 13.00–13.03
Qualidade de software, estratégia de testes e pirâmide. Estabelece o vocabulário para todo o restante.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Tipos de Testes e Operacionalização** · aulas 13.04–13.13
Testes unitários, mocks, integração, contract tests, end-to-end, regressão, testes em CI, flaky tests, testabilidade de arquitetura e quality gates.
Pré-requisito: Bloco A.

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Projeto ou Prática do Módulo

Evolua a API do PetCare OS criada nos módulos anteriores para uma aplicação com confiança testável:

1. Escolha fluxos críticos da API.
2. Escreva uma estratégia de testes para esses fluxos.
3. Crie testes unitários para regras pequenas.
4. Crie testes de integração para endpoints e banco.
5. Valide contratos principais da API.
6. Defina pelo menos um fluxo end-to-end.
7. Rode os testes em um fluxo de CI conceitual ou real.
8. Defina métricas e um quality gate para código novo.

## O Que Revisar Antes de Avançar

- Testes em frontend e comportamento observável.
- Performance no frontend, performance em SQL e profiling no backend.
- Logging, failure modes, idempotência e rate limiting.
- Contratos de API, OpenAPI, erros padronizados e contract testing.
- Autenticação, autorização e segurança em APIs.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Qualidade e Testes de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina qualidade de software, estratégia de testes, pirâmide, testes unitários, integração, E2E, contract tests, regressão, CI, flaky tests, testabilidade, análise estática e quality gates.
- Objetivo do módulo: Quero sair do "funciona na minha máquina" para software testável e confiável.
- Pré-requisitos: HTTP, TypeScript, frontend, backend com Node.js, bancos de dados, API design, segurança, logging, failure modes e profiling introdutório.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de estratégia de testes;
3. perguntas de entrevista para backend/fullstack iniciante-intermediário;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial das ferramentas de teste escolhidas para prática.
- Documentação oficial do framework backend escolhido para prática.
- Documentação oficial do banco de dados e ORM escolhidos para prática.
- Guias conceituais sobre CI, testes e engenharia de confiabilidade.

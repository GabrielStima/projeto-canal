# Qualidade, Testes, Observabilidade e Performance

Este modulo marca a passagem de "a aplicacao funciona" para "a aplicacao pode ser testada, medida, investigada e sustentada quando cresce". Ate aqui, voce construiu bases de frontend, backend, bancos de dados, API design, autenticacao, autorizacao e seguranca.

Agora o foco muda para confianca. Um software profissional precisa ter criterios de qualidade, estrategia de testes, sinais de observabilidade, medicao de performance e formas previsiveis de investigar falhas.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar qualidade de software em termos praticos;
- montar uma estrategia de testes proporcional ao risco;
- diferenciar testes unitarios, de integracao, end-to-end, contrato, carga e regressao;
- usar mocks, stubs e fakes sem esconder problemas importantes;
- entender como testes entram no fluxo de CI;
- reconhecer causas comuns de flaky tests;
- avaliar como arquitetura afeta testabilidade;
- analisar performance com medicao, nao com palpite;
- usar profiling para investigar gargalos;
- diferenciar logging, metricas e tracing;
- entender instrumentacao, telemetria, monitoramento e alertas;
- relacionar failure modes com testes, observabilidade e performance.

## Por Que Este Modulo Existe

Nos modulos anteriores, voce aprendeu a criar interfaces, APIs, bancos, contratos, autenticacao e protecoes basicas de seguranca. Isso permite construir sistemas uteis, mas ainda nao responde a perguntas comuns em projetos reais:

- como saber se uma mudanca quebrou algo?
- que testes valem o custo de manter?
- como investigar um erro que so acontece em producao?
- como descobrir se uma API esta lenta por causa de banco, rede, CPU ou dependencia externa?
- quando um alerta deve acordar alguem?
- como transformar falhas conhecidas em testes, logs, metricas e decisoes de design?

Qualidade, observabilidade e performance aparecem juntas porque se reforcam. Testes reduzem regressao. Observabilidade reduz cegueira. Performance depende de medicao. Failure modes mostram onde o sistema precisa de cuidado.

## Pre-requisitos

- Entender HTTP, headers, status codes, request, response, cache e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Ter estudado frontend moderno, chamadas de API, formularios, validacao, testes e performance em nivel introdutorio.
- Entender bancos de dados, queries, indexes, transactions e performance basica.
- Saber criar APIs backend com Node.js e lidar com erros, logs, banco, ORMs e failure modes.
- Ter estudado API design, contratos, OpenAPI, erros padronizados, idempotencia, governance e contract testing introdutorio.
- Ter estudado autenticacao, autorizacao, seguranca em APIs e rate limiting.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 13.00 | [Qualidade, Testes, Observabilidade e Performance](13.00-qualidade-testes-observabilidade-e-performance.md) | Guarda-chuva | Rascunho |
| 13.01 | [Qualidade de Software](13.01-qualidade-de-software.md) | Guarda-chuva curta | Rascunho |
| 13.02 | [Estrategia de Testes](13.02-estrategia-de-testes.md) | Especifica ampla | Rascunho |
| 13.03 | [Piramide de Testes](13.03-piramide-de-testes.md) | Especifica | Rascunho |
| 13.04 | [Testes Unitarios](13.04-testes-unitarios.md) | Especifica pratica | Rascunho |
| 13.05 | [Mocks, Stubs e Fakes](13.05-mocks-stubs-e-fakes.md) | Especifica | Rascunho |
| 13.06 | [Testes de Integracao](13.06-testes-de-integracao.md) | Especifica pratica | Rascunho |
| 13.07 | [Contract Tests](13.07-contract-tests.md) | Especifica pratica | Rascunho |
| 13.08 | [Testes End-to-End](13.08-testes-end-to-end.md) | Especifica pratica | Rascunho |
| 13.09 | [Testes de Regressao](13.09-testes-de-regressao.md) | Especifica | Rascunho |
| 13.10 | [Testes em CI](13.10-testes-em-ci.md) | Especifica pratica | Rascunho |
| 13.11 | [Flaky Tests](13.11-flaky-tests.md) | Especifica | Rascunho |
| 13.12 | [Testabilidade de Arquitetura](13.12-testabilidade-de-arquitetura.md) | Guarda-chuva curta | Rascunho |
| 13.13 | [Analise e Performance](13.13-analise-e-performance.md) | Guarda-chuva curta | Rascunho |
| 13.14 | [Profiling](13.14-profiling.md) | Especifica pratica | Rascunho |
| 13.15 | [Testes de Carga](13.15-testes-de-carga.md) | Especifica pratica | Rascunho |
| 13.16 | [Logging para Observabilidade](13.16-logging-para-observabilidade.md) | Especifica pratica | Rascunho |
| 13.17 | [Observabilidade](13.17-observabilidade.md) | Guarda-chuva curta | Rascunho |
| 13.18 | [Instrumentacao](13.18-instrumentacao.md) | Especifica pratica | Rascunho |
| 13.19 | [Telemetria](13.19-telemetria.md) | Especifica | Rascunho |
| 13.20 | [Metricas](13.20-metricas.md) | Especifica pratica | Rascunho |
| 13.21 | [Tracing](13.21-tracing.md) | Especifica pratica | Rascunho |
| 13.22 | [Monitoramento](13.22-monitoramento.md) | Especifica | Rascunho |
| 13.23 | [Alertas](13.23-alertas.md) | Especifica | Rascunho |
| 13.24 | [Failure Modes na Pratica](13.24-failure-modes-na-pratica.md) | Sintese conceitual/pratica | Rascunho |
| 13.25 | [Projeto Pratico: Tornando uma API Testavel, Observavel e Mensuravel](13.25-projeto-pratico-tornando-uma-api-testavel-observavel-e-mensuravel.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Evolua a API do painel de estudos criada nos modulos anteriores para uma aplicacao mais confiavel:

1. Escolha fluxos criticos da API.
2. Escreva uma estrategia de testes para esses fluxos.
3. Crie testes unitarios para regras pequenas.
4. Crie testes de integracao para endpoints e banco.
5. Valide contratos principais da API.
6. Defina pelo menos um fluxo end-to-end.
7. Rode os testes em um fluxo de CI conceitual ou real.
8. Investigue um gargalo simples com profiling.
9. Crie logs estruturados com contexto de requisicao.
10. Defina metricas de latencia, erros e volume.
11. Desenhe traces para uma requisicao importante.
12. Defina monitoramento e alertas para failure modes relevantes.

## O Que Revisar Antes de Avancar

- Testes em frontend e comportamento observavel.
- Performance no frontend, performance em SQL e profiling no backend.
- Logging, failure modes, idempotencia e rate limiting.
- Contratos de API, OpenAPI, erros padronizados e contract testing.
- Autenticacao, autorizacao e seguranca em APIs.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Qualidade, Testes, Observabilidade e Performance de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina qualidade de software, estrategia de testes, piramide, testes unitarios, integracao, E2E, contract tests, carga, regressao, CI, flaky tests, testabilidade, performance, profiling, logging, observabilidade, instrumentacao, telemetria, metricas, tracing, monitoramento, alertas e failure modes.
- Objetivo do modulo: Quero sair do "funciona na minha maquina" para software testavel, mensuravel, operavel e confiavel.
- Pre-requisitos: HTTP, TypeScript, frontend, backend com Node.js, bancos de dados, API design, seguranca, logging, failure modes e profiling introdutorio.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos de estrategia de testes;
3. exercicios de observabilidade e performance;
4. perguntas de entrevista para backend/fullstack iniciante-intermediario;
5. exemplos de aplicacao em projetos reais;
6. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Documentacao oficial das ferramentas de teste escolhidas para pratica.
- Documentacao oficial do framework backend escolhido para pratica.
- Documentacao oficial do banco de dados e ORM escolhidos para pratica.
- Guias conceituais sobre observabilidade, metricas, logs e tracing.
- Materiais de boas praticas sobre CI, testes e engenharia de confiabilidade.

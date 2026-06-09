<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Qualidade, Testes, Observabilidade é Performance

</div>

Este módulo marca a passagem de "a aplicação funciona" para "a aplicação pode ser testada, medida, investigada e sustentada quando cresce". Até aqui, você construiu bases de frontend, backend, bancos de dados, API design, autenticação, autorização e segurança.

Agora o foco muda para confiança. Um software profissional precisa ter critérios de qualidade, estratégia de testes, sinais de observabilidade, medição de performance e formas previsíveis de investigar falhas.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar qualidade de software em termos práticos;
- montar uma estratégia de testes proporcional ao risco;
- diferenciar testes unitários, de integração, end-to-end, contrato, carga e regressão;
- usar mocks, stubs e fakes sem esconder problemas importantes;
- entender como testes entram no fluxo de CI;
- reconhecer causas comuns de flaky tests;
- avaliar como arquitetura afeta testabilidade;
- interpretar análise estática, métricas e quality gates sem confundi-los com qualidade real;
- analisar performance com medição, não com palpite;
- usar profiling para investigar gargalos;
- diferenciar logging, métricas e tracing;
- entender instrumentação, telemetria, monitoramento e alertas;
- relacionar failure modes com testes, observabilidade e performance.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a criar interfaces, APIs, bancos, contratos, autenticação e proteções básicas de segurança. Isso permite construir sistemas úteis, mas ainda não responde a perguntas comuns em projetos reais:

- como saber se uma mudança quebrou algo?
- que testes valem o custo de manter?
- como investigar um erro que só acontece em produção?
- como descobrir se uma API está lenta por causa de banco, rede, CPU ou dependência externa?
- quando um alerta deve acordar alguém?
- como transformar falhas conhecidas em testes, logs, métricas e decisões de design?
- quais critérios de qualidade podem ser automatizados sem eliminar julgamento humano?

Qualidade, observabilidade e performance aparecem juntas porque se reforçam. Testes reduzem regressão. Observabilidade reduz cegueira. Performance depende de medição. Failure modes mostram onde o sistema precisa de cuidado.

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
| 13.00 | [Qualidade, Testes, Observabilidade é Performance](13.00-qualidade-testes-observabilidade-e-performance.md) | Guarda-chuva | Rascunho |
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
| 13.14 | [Análise e Performance](13.14-analise-e-performance.md) | Guarda-chuva curta | Rascunho |
| 13.15 | [Profiling](13.15-profiling.md) | Específica prática | Rascunho |
| 13.16 | [Testes de Carga](13.16-testes-de-carga.md) | Específica prática | Rascunho |
| 13.17 | [Logging para Observabilidade](13.17-logging-para-observabilidade.md) | Específica prática | Rascunho |
| 13.18 | [Observabilidade](13.18-observabilidade.md) | Guarda-chuva curta | Rascunho |
| 13.19 | [Instrumentação](13.19-instrumentacao.md) | Específica prática | Rascunho |
| 13.20 | [Telemetria](13.20-telemetria.md) | Específica | Rascunho |
| 13.21 | [Métricas](13.21-metricas.md) | Específica prática | Rascunho |
| 13.22 | [Tracing](13.22-tracing.md) | Específica prática | Rascunho |
| 13.23 | [Monitoramento](13.23-monitoramento.md) | Específica | Rascunho |
| 13.24 | [Alertas](13.24-alertas.md) | Específica | Rascunho |
| 13.25 | [Failure Modes na Prática](13.25-failure-modes-na-pratica.md) | Síntese conceitual/prática | Rascunho |
| 13.26 | [Projeto Prático: Tornando uma API Testável, Observável e Mensurável](13.26-projeto-pratico-tornando-uma-api-testavel-observavel-e-mensuravel.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Evolua a API do painel de estudos criada nos módulos anteriores para uma aplicação mais confiável:

1. Escolha fluxos críticos da API.
2. Escreva uma estratégia de testes para esses fluxos.
3. Crie testes unitários para regras pequenas.
4. Crie testes de integração para endpoints e banco.
5. Valide contratos principais da API.
6. Defina pelo menos um fluxo end-to-end.
7. Rode os testes em um fluxo de CI conceitual ou real.
8. Defina métricas e um quality gate para código novo.
9. Investigue um gargalo simples com profiling.
10. Crie logs estruturados com contexto de requisição.
11. Defina métricas de latência, erros e volume.
12. Desenhe traces para uma requisição importante.
13. Defina monitoramento e alertas para failure modes relevantes.

## O Que Revisar Antes de Avançar

- Testes em frontend e comportamento observável.
- Performance no frontend, performance em SQL e profiling no backend.
- Logging, failure modes, idempotência e rate limiting.
- Contratos de API, OpenAPI, erros padronizados e contract testing.
- Autenticação, autorização e segurança em APIs.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Qualidade, Testes, Observabilidade é Performance de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina qualidade de software, estratégia de testes, pirâmide, testes unitários, integração, E2E, contract tests, carga, regressão, CI, flaky tests, testabilidade, análise estática, quality gates, performance, profiling, logging, observabilidade, instrumentação, telemetria, métricas, tracing, monitoramento, alertas e failure modes.
- Objetivo do módulo: Quero sair do "funciona na minha máquina" para software testável, mensurável, operável e confiável.
- Pré-requisitos: HTTP, TypeScript, frontend, backend com Node.js, bancos de dados, API design, segurança, logging, failure modes e profiling introdutório.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de estratégia de testes;
3. exercícios de observabilidade e performance;
4. perguntas de entrevista para backend/fullstack iniciante-intermediário;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial das ferramentas de teste escolhidas para prática.
- Documentação oficial do framework backend escolhido para prática.
- Documentação oficial do banco de dados e ORM escolhidos para prática.
- Guias conceituais sobre observabilidade, métricas, logs e tracing.
- Materiais de boas práticas sobre CI, testes e engenharia de confiabilidade.

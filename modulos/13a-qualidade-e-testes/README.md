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
| 13.00 | [Qualidade, Testes, Observabilidade e Performance](13.00-qualidade-testes-observabilidade-e-performance.md) | Guarda-chuva | Revisada |
| 13.01 | [Qualidade de Software](13.01-qualidade-de-software.md) | Guarda-chuva curta | Revisada |
| 13.02 | [Estratégia de Testes](13.02-estrategia-de-testes.md) | Específica ampla | Revisada |
| 13.03 | [Pirâmide de Testes](13.03-piramide-de-testes.md) | Específica | Revisada |
| 13.04 | [Testes Unitários](13.04-testes-unitarios.md) | Específica prática | Revisada |
| 13.05 | [Mocks, Stubs e Fakes](13.05-mocks-stubs-e-fakes.md) | Específica | Revisada |
| 13.06 | [Testes de Integração](13.06-testes-de-integracao.md) | Específica prática | Revisada |
| 13.07 | [Contract Tests](13.07-contract-tests.md) | Específica prática | Revisada |
| 13.08 | [Testes End-to-End](13.08-testes-end-to-end.md) | Específica prática | Revisada |
| 13.09 | [Testes de Regressão](13.09-testes-de-regressao.md) | Específica | Revisada |
| 13.10 | [Testes em CI](13.10-testes-em-ci.md) | Específica prática | Revisada |
| 13.11 | [Flaky Tests](13.11-flaky-tests.md) | Específica | Revisada |
| 13.12 | [Testabilidade de Arquitetura](13.12-testabilidade-de-arquitetura.md) | Guarda-chuva curta | Revisada |
| 13.13 | [Análise Estática, Métricas e Quality Gates](13.13-analise-estatica-metricas-e-quality-gates.md) | Específica ampla | Revisada |

## Exercícios

- [Exercício 01 — Qualidade e Riscos](exercicios/01-qualidade-e-riscos.md)
- [Exercício 02 — Casos de Teste e a Pirâmide](exercicios/02-piramide-de-testes.md)
- [Exercício 03 — Testes Unitários de Domínio](exercicios/03-testes-unitarios.md)
- [Exercício 04 — Teste de Integração na API](exercicios/04-testes-de-integracao.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você evoluirá a API do **PetCare OS** criando a sua rede de segurança (Marco de Integração N4).

1. Escolha fluxos críticos da API (ex: Cadastro de Pet, Agendamento de Consulta).
2. Escreva uma estratégia de testes para esses fluxos.
3. Crie testes unitários para regras matemáticas (ex: faturamento e descontos).
4. Crie testes de integração plugando a API a um banco de testes (via Testcontainers ou local).
5. Valide os contratos principais JSON devolvidos pela sua API (Contract Testing).
6. Defina pelo menos um fluxo crítico End-to-End no seu front-end (Cypress/Playwright).
7. Rode os testes em um fluxo de CI (ex: Github Actions) impedindo merges quebrados.
8. Configure ferramentas de Análise Estática (SonarQube/ESLint) para exigir cobertura mínima.

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

- Documentação oficial do framework de Teste do backend (ex: Jest ou Vitest).
- Documentação do Cypress ou Playwright para E2E.
- O material teórico de "Test Pyramid" de Martin Fowler.
- Documentação de Integração Contínua (Github Actions ou Gitlab CI).

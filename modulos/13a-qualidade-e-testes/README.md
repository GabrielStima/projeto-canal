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
| 13.00 | [Qualidade, Testes, Observabilidade e Performance](13.00-qualidade-testes-observabilidade-e-performance.md) | Guarda-chuva | Auditada |
| 13.01 | [Qualidade de Software](13.01-qualidade-de-software.md) | Guarda-chuva curta | Auditada |
| 13.02 | [Estratégia de Testes](13.02-estrategia-de-testes.md) | Específica ampla | Auditada |
| 13.03 | [Pirâmide de Testes](13.03-piramide-de-testes.md) | Específica | Auditada |
| 13.04 | [Testes Unitários](13.04-testes-unitarios.md) | Específica prática | Auditada |
| 13.05 | [Mocks, Stubs e Fakes](13.05-mocks-stubs-e-fakes.md) | Específica | Auditada |
| 13.06 | [Testes de Integração](13.06-testes-de-integracao.md) | Específica prática | Auditada |
| 13.07 | [Contract Tests](13.07-contract-tests.md) | Específica prática | Auditada |
| 13.08 | [Testes End-to-End](13.08-testes-end-to-end.md) | Específica prática | Auditada |
| 13.09 | [Testes de Regressão](13.09-testes-de-regressao.md) | Específica | Auditada |
| 13.10 | [Testes em CI](13.10-testes-em-ci.md) | Específica prática | Auditada |
| 13.11 | [Flaky Tests](13.11-flaky-tests.md) | Específica | Auditada |
| 13.12 | [Testabilidade de Arquitetura](13.12-testabilidade-de-arquitetura.md) | Guarda-chuva curta | Auditada |
| 13.13 | [Análise Estática, Métricas e Quality Gates](13.13-analise-estatica-metricas-e-quality-gates.md) | Específica ampla | Auditada |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Os exercícios evoluem uma estratégia de qualidade única, em vez de criar suítes independentes a cada aula.

**Bloco A — Risco e estratégia** · aulas 13.00–13.03
Qualidade, risco, estratégia e escolha do nível de teste.

Ao concluir o bloco, faça o [Exercício 01 — Estratégia de Qualidade e Testes](exercicios/01-estrategia-de-qualidade-e-testes.md).

**Bloco B — Unidade e integração** · aulas 13.04–13.06
Testes unitários, doubles e integração com infraestrutura real.

Faça o [Exercício 02 — Testes Unitários e Doubles](exercicios/02-testes-unitarios-e-doubles.md) e depois o [Exercício 03 — Testes de Integração](exercicios/03-testes-de-integracao.md).

**Bloco C — Contratos, jornadas e regressões** · aulas 13.07–13.09
Proteção de contratos, fluxos end-to-end e bugs que não podem voltar.

Faça o [Exercício 04 — Contrato e Regressão](exercicios/04-contrato-e-regressao.md). O [Exercício 05 — Jornada End-to-End](exercicios/05-jornada-end-to-end.md) pode ser implementado quando houver frontend executável ou entregue como plano verificável.

**Bloco D — Automação e sustentabilidade** · aulas 13.10–13.13
CI, testes instáveis, testabilidade, análise estática e quality gates.

Faça o [Exercício 06 — Testes no CI e Flakiness](exercicios/06-testes-no-ci-e-flakiness.md) e o [Exercício 07 — Testabilidade e Quality Gate](exercicios/07-testabilidade-e-quality-gate.md). Finalize com a [Atividade Final do Módulo](exercicios/atividade-final-modulo.md).

## Exercícios

- [Exercício 01 — Estratégia de Qualidade e Testes](exercicios/01-estrategia-de-qualidade-e-testes.md)
- [Exercício 02 — Testes Unitários e Doubles](exercicios/02-testes-unitarios-e-doubles.md)
- [Exercício 03 — Testes de Integração](exercicios/03-testes-de-integracao.md)
- [Exercício 04 — Contrato e Regressão](exercicios/04-contrato-e-regressao.md)
- [Exercício 05 — Jornada End-to-End](exercicios/05-jornada-end-to-end.md)
- [Exercício 06 — Testes no CI e Flakiness](exercicios/06-testes-no-ci-e-flakiness.md)
- [Exercício 07 — Testabilidade e Quality Gate](exercicios/07-testabilidade-e-quality-gate.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você evoluirá a API do **PetCare OS** criando uma rede de segurança automatizada.

1. Escolha fluxos críticos da API (ex: Cadastro de Pet, Agendamento de Consulta).
2. Escreva uma estratégia de testes para esses fluxos.
3. Crie testes unitários para regras matemáticas (ex: faturamento e descontos).
4. Crie testes de integração usando um banco de testes isolado, local ou efêmero.
5. Valide os contratos principais JSON devolvidos pela sua API (Contract Testing).
6. Defina pelo menos um fluxo crítico end-to-end no frontend, implementando-o quando o projeto já possuir uma interface executável.
7. Rode os testes em um fluxo de CI, impedindo que mudanças com falhas sejam aprovadas.
8. Configure análise estática e um quality gate proporcional ao risco do projeto.

As práticas usam o framework de teste, o banco e o provedor de CI já escolhidos no projeto. Ferramentas citadas nas aulas são exemplos, não requisitos.

## O Que Entra e O Que Sai Deste Módulo

**O que entra dos módulos anteriores:**

- API com banco, contratos, autenticação, autorização e controles de segurança;
- critérios de aceite, erros padronizados e documentação OpenAPI;
- frontend navegável, quando disponível;
- mapa de riscos e cenários de sucesso e rejeição produzidos no módulo 12.

**O que sai deste módulo:**

- estratégia de testes orientada a risco;
- testes unitários de regras de domínio;
- testes de integração com estado isolado;
- proteção de contrato e regressões conhecidas;
- jornada end-to-end implementada ou especificada;
- pipeline de CI com ordem de feedback clara;
- análise de flakiness, testabilidade e quality gate documentado.

**Onde isso será retomado:**

- no módulo 13B, a suíte fornecerá uma referência de comportamento para medições e investigações;
- no módulo 14, dificuldades de teste ajudarão a identificar problemas de design;
- nos módulos de entrega, o pipeline será ampliado sem redefinir a estratégia do zero.

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

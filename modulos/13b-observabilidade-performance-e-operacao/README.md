<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Observabilidade, Performance e Operação

</div>

Este módulo marca a passagem de "a aplicação funciona e está testada" para "a aplicação pode ser medida, investigada e sustentada quando cresce". Até aqui, você construiu bases de frontend, backend, bancos de dados, API design, autenticação, segurança e qualidade com testes.

Agora o foco muda para operação. Um software profissional precisa de sinais claros de saúde, medição de performance, formas previsíveis de investigar falhas e alertas que acionam antes que o usuário perceba o problema.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- analisar performance com medição, não com palpite;
- usar profiling para investigar gargalos;
- diferenciar logging, métricas e tracing;
- entender instrumentação, telemetria, monitoramento e alertas;
- relacionar failure modes com observabilidade e performance;
- criar testes de carga que simulam cenários reais;
- definir alertas úteis e evitar alert fatigue.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a criar sistemas testáveis. Mas testes só capturam o que você previu. Em produção, surgem problemas inesperados: latência em cascata, vazamentos de memória, dependências lentas, picos de tráfego e falhas silenciosas.

Este módulo responde a perguntas como:

- como investigar um erro que só acontece em produção?
- como descobrir se uma API está lenta por causa de banco, rede, CPU ou dependência externa?
- quando um alerta deve acordar alguém?
- como diferenciar sintoma (latência alta) de causa (query sem índice, GC, rede)?
- como transformar falhas conhecidas em métricas, logs e decisões de operação?

Observabilidade, performance e operação aparecem juntas porque se reforçam. Observabilidade reduz cegueira. Performance depende de medição. Operação depende de sinais acionáveis.

## Pré-requisitos

- Entender HTTP, headers, status codes, request, response, cache e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Ter estudado frontend moderno, chamadas de API, formulários, validação, testes e performance em nível introdutório.
- Entender bancos de dados, queries, indexes, transactions e performance básica.
- Saber criar APIs backend com Node.js e lidar com erros, logs, banco, ORMs e failure modes.
- Ter estudado qualidade, estratégia de testes, pirâmide de testes e testabilidade.
- Ter estudado autenticação, autorização, segurança em APIs e rate limiting.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 13.14 | [Análise e Performance](13.14-analise-e-performance.md) | Guarda-chuva curta | Auditada |
| 13.15 | [Profiling](13.15-profiling.md) | Específica prática | Auditada |
| 13.16 | [Testes de Carga](13.16-testes-de-carga.md) | Específica prática | Auditada |
| 13.17 | [Logging para Observabilidade](13.17-logging-para-observabilidade.md) | Específica prática | Auditada |
| 13.18 | [Observabilidade](13.18-observabilidade.md) | Guarda-chuva curta | Auditada |
| 13.19 | [Instrumentação](13.19-instrumentacao.md) | Específica prática | Auditada |
| 13.20 | [Telemetria](13.20-telemetria.md) | Específica | Auditada |
| 13.21 | [Métricas](13.21-metricas.md) | Específica prática | Auditada |
| 13.22 | [Tracing](13.22-tracing.md) | Específica prática | Auditada |
| 13.23 | [Monitoramento](13.23-monitoramento.md) | Específica | Auditada |
| 13.24 | [Alertas](13.24-alertas.md) | Específica | Auditada |
| 13.25 | [Failure Modes na Prática](13.25-failure-modes-na-pratica.md) | Síntese conceitual/prática | Auditada |
| 13.26 | [Projeto Prático: Tornando uma API Testável, Observável e Mensurável](13.26-projeto-pratico-tornando-uma-api-testavel-observavel-e-mensuravel.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Os exercícios partem de uma medição inicial e terminam em uma investigação reproduzível, sem exigir uma plataforma de observabilidade em nuvem.

**Bloco A — Medir antes de otimizar** · aulas 13.14–13.16
Hipóteses, profiling, baseline e testes de carga.

Faça o [Exercício 01 — Diagnóstico e Profiling](exercicios/01-diagnostico-e-profiling.md) e depois o [Exercício 02 — Teste de Carga e Baseline](exercicios/02-teste-de-carga-e-baseline.md).

**Bloco B — Emitir e transportar sinais** · aulas 13.17–13.20
Logs estruturados, instrumentação, correlação e fluxo de telemetria.

Faça o [Exercício 03 — Logs, Instrumentação e Telemetria](exercicios/03-logs-instrumentacao-e-telemetria.md).

**Bloco C — Investigar com sinais** · aulas 13.21–13.22
Métricas, percentis, traces e correlação de uma operação.

Faça o [Exercício 04 — Métricas e Tracing](exercicios/04-metricas-e-tracing.md).

**Bloco D — Operar e responder** · aulas 13.23–13.26
Monitoramento, alertas e failure modes.

Faça o [Exercício 05 — Monitoramento e Alertas](exercicios/05-monitoramento-e-alertas.md) e o [Exercício 06 — Failure Modes e Mitigação](exercicios/06-failure-modes-e-mitigacao.md). Finalize com a [Atividade Final do Módulo](exercicios/atividade-final-modulo.md).

## Exercícios

- [Exercício 01 — Diagnóstico e Profiling](exercicios/01-diagnostico-e-profiling.md)
- [Exercício 02 — Teste de Carga e Baseline](exercicios/02-teste-de-carga-e-baseline.md)
- [Exercício 03 — Logs, Instrumentação e Telemetria](exercicios/03-logs-instrumentacao-e-telemetria.md)
- [Exercício 04 — Métricas e Tracing](exercicios/04-metricas-e-tracing.md)
- [Exercício 05 — Monitoramento e Alertas](exercicios/05-monitoramento-e-alertas.md)
- [Exercício 06 — Failure Modes e Mitigação](exercicios/06-failure-modes-e-mitigacao.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você continuará a evolução do PetCare OS tornando um fluxo crítico mensurável e investigável. O foco está em adicionar sinais e evidências, sem reescrever a regra de negócio:

1. Medir um endpoint e registrar uma baseline antes de otimizar.
2. Usar profiling para investigar uma hipótese de gargalo.
3. Criar um teste de carga pequeno e interpretar latência, throughput e erros.
4. Adicionar logs estruturados, duração e um identificador de correlação.
5. Definir métricas e desenhar o trace de uma operação importante.
6. Criar uma visão de monitoramento e um alerta acionável.
7. Documentar um failure mode, sua mitigação e os sinais que permitem investigá-lo.

Você pode usar ferramentas equivalentes às apresentadas nas aulas. Não é necessário contratar serviço externo, instalar uma pilha completa de observabilidade ou provar capacidade de produção a partir de um teste local.

## O Que Entra e O Que Sai Deste Módulo

**O que entra dos módulos anteriores:**

- API com suíte de testes e pipeline de CI;
- fluxos críticos e riscos já identificados;
- logs básicos, erros padronizados, autenticação e rate limiting;
- ambiente local capaz de executar a aplicação e seus testes.

**O que sai deste módulo:**

- baseline de performance de um endpoint;
- evidência de profiling e comparação antes/depois, quando houver otimização;
- cenário de carga reproduzível;
- logs estruturados com correlação e duração;
- mapa de métricas e trace de uma operação;
- dashboard e alerta especificados;
- failure mode com mitigação e sinais de investigação.

**Onde isso será retomado:**

- no módulo 14, medições e sinais ajudarão a avaliar o efeito de refatorações;
- nos módulos de cloud e SRE, os sinais locais serão conectados a infraestrutura, monitoramento e resposta a incidentes;
- os failure modes documentados orientarão decisões arquiteturais posteriores.

## O Que Revisar Antes de Avançar

- Testes de integração e E2E, para não confundir comportamento de tela com comportamento e saúde da API.
- Performance em SQL e Node.js.
- Logging estruturado.
- Contratos de API, middlewares e injeção de Headers (correlation ID).
- Autenticação e Rate Limiting, essenciais durante os testes de estresse.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Observabilidade, Performance e Operação de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina performance, profiling, testes de carga, logging, observabilidade, instrumentação, telemetria, métricas, tracing, monitoramento, alertas e failure modes.
- Objetivo do módulo: Quero sair do "funciona na minha máquina" para software mensurável, operável e confiável em produção.
- Pré-requisitos: HTTP, TypeScript, frontend, backend com Node.js, bancos de dados, API design, segurança, qualidade, testes, logging, failure modes e profiling introdutório.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de observabilidade e performance;
3. perguntas de entrevista para backend/fullstack iniciante-intermediário;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do framework backend escolhido para prática.
- Documentação de Profiling do Node.js (Node Inspector).
- Documentação do K6 ou Artillery para Load Tests.
- OpenTelemetry Documentation para Instrumentação moderna.
- The RED Method e The USE Method para definição arquitetural de Métricas.

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

## Trilha de Estudo

Este módulo está organizado em três blocos progressivos:

**Bloco A — Performance e Análise** · aulas 13.14–13.16
Análise de performance, profiling e testes de carga. Estabelece como medir antes de observar.
Pré-requisito: qualidade e testes (módulo 13A).

**Bloco B — Observabilidade** · aulas 13.17–13.25
Logging, observabilidade, instrumentação, telemetria, métricas, tracing, monitoramento, alertas e failure modes na prática.
Pré-requisito: Bloco A (entender o que medir exige saber o que é importante).

> **✦ Projeto Prático — aula 13.26:** ao final do módulo, complete o [Projeto Prático: Tornando uma API Testável, Observável e Mensurável](13.26-projeto-pratico-tornando-uma-api-testavel-observavel-e-mensuravel.md). O projeto integra performance, observabilidade e operação em um fluxo real do PetCare OS.

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Projeto ou Prática do Módulo

Evolua a API do PetCare OS para uma aplicação observável e mensurável:

1. Investigue um gargalo simples com profiling.
2. Crie logs estruturados com contexto de requisição.
3. Defina métricas de latência, erros e volume.
4. Desenhe traces para uma requisição importante.
5. Defina monitoramento e alertas para failure modes relevantes.
6. Execute testes de carga e interprete os resultados.

## O Que Revisar Antes de Avançar

- Testes em frontend e comportamento observável.
- Performance no frontend, performance em SQL e profiling no backend.
- Logging, failure modes, idempotência e rate limiting.
- Contratos de API, OpenAPI, erros padronizados e contract testing.
- Autenticação, autorização e segurança em APIs.
- Qualidade, estratégia de testes e testabilidade.

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
- Documentação oficial do banco de dados e ORM escolhidos para prática.
- Guias conceituais sobre observabilidade, métricas, logs e tracing.
- Materiais de boas práticas sobre CI, testes e engenharia de confiabilidade.

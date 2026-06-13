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
| 13.14 | [Análise e Performance](13.14-analise-e-performance.md) | Guarda-chuva curta | Revisada |
| 13.15 | [Profiling](13.15-profiling.md) | Específica prática | Revisada |
| 13.16 | [Testes de Carga](13.16-testes-de-carga.md) | Específica prática | Revisada |
| 13.17 | [Logging para Observabilidade](13.17-logging-para-observabilidade.md) | Específica prática | Revisada |
| 13.18 | [Observabilidade](13.18-observabilidade.md) | Guarda-chuva curta | Revisada |
| 13.19 | [Instrumentação](13.19-instrumentacao.md) | Específica prática | Revisada |
| 13.20 | [Telemetria](13.20-telemetria.md) | Específica | Revisada |
| 13.21 | [Métricas](13.21-metricas.md) | Específica prática | Revisada |
| 13.22 | [Tracing](13.22-tracing.md) | Específica prática | Revisada |
| 13.23 | [Monitoramento](13.23-monitoramento.md) | Específica | Revisada |
| 13.24 | [Alertas](13.24-alertas.md) | Específica | Revisada |
| 13.25 | [Failure Modes na Prática](13.25-failure-modes-na-pratica.md) | Síntese conceitual/prática | Revisada |
| 13.26 | [Projeto Prático: Tornando uma API Testável, Observável e Mensurável](13.26-projeto-pratico-tornando-uma-api-testavel-observavel-e-mensuravel.md) | Síntese prática | Revisada |

## Exercícios

- [Exercício 05 — Análise e Profiling](exercicios/05-analise-e-profiling.md)
- [Exercício 06 — Logging e Métricas](exercicios/06-logging-e-metricas.md)
- [Exercício 07 — Monitoramento e Alertas](exercicios/07-monitoramento-e-alertas.md)
- [Exercício 08 — Failure Modes na Operação](exercicios/08-failure-modes-operacao.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você continuará a evolução do PetCare OS implementando o **marco operacional**.
O código não precisará mais ser alterado na sua regra de negócio; o foco agora será envelopá-lo com confiabilidade:

1. Executar um Profiling local com Node Inspector / Clinic.js e encontrar o trecho mais custoso do Agendamento.
2. Trocar todos os `console.log` puros por `pino` ou `winston`, garantindo injeção de ID único.
3. Criar e aplicar um Teste de Carga de pico matinal usando K6 para provar a robustez em altas requisições.
4. Definir Alertas e documentar um plano de Mitigação (Fail-Open vs Fail-Closed) para dependências externas.
5. Criar Traces hipotéticos da jornada completa de Faturamento, incluindo chamadas ao Redis, Banco e API Externa.

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

<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Dados em Tempo Real e Comunicação Assíncrona

</div>

Este módulo marca a passagem do modelo tradicional de request/response para formas de comunicação em que o sistema precisa reagir, esperar, empurrar atualizações, processar trabalho depois ou coordenar partes independentes.

Até aqui, você já estudou HTTP, APIs, backend com Node.js, bancos de dados, autenticação, qualidade, observabilidade, arquitetura, sistemas distribuídos, messaging, CQRS e Event Sourcing em nível conceitual. Agora o foco é prático: escolher a forma certa de comunicação para cada problema.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- diferenciar comunicação síncrona, assíncrona e em tempo real;
- comparar short polling, long polling, SSE e WebSocket;
- reconhecer quando usar atualização servidor -> cliente e quando usar canal bidirecional;
- modelar processamento assíncrono com jobs, filas, brokers e pub/sub;
- lidar com retries, mensagens duplicadas, falhas, atraso e reprocessamento;
- aplicar idempotência em fluxos assíncronos;
- desenhar uma solução simples de notificações e jobs assíncronos para uma API.

## Por Que Este Módulo Existe

Nem toda interação cabe no fluxo "cliente faz request, servidor responde e acabou". Sistemas reais precisam atualizar telas quando algo muda, enviar notificações, processar arquivos, gerar relatórios, recalcular dados, integrar serviços e absorver picos de uso.

Tempo real e comunicação assíncrona existem para resolver esses problemas, mas também adicionam complexidade. Conexões caem, mensagens atrasam, eventos chegam duplicados, consumidores falham, filas acumulam e o usuário pode ver um estado temporariamente desatualizado.

Este módulo existe para ensinar essas escolhas sem transformar toda aplicação simples em uma arquitetura distribuída desnecessária.

## Pré-requisitos

- Fundamentos de internet, HTTP, cliente/servidor, request/response e estado.
- JavaScript assíncrono, event loop, Promises e async/await.
- Backend com Node.js, APIs, workers, failure modes, performance e message brokers em alto nível.
- API design, contratos, webhooks e idempotência.
- Segurança em APIs, CORS, autenticação, autorização e rate limiting.
- Observabilidade, métricas, tracing, monitoramento, alertas e testes de carga.
- Arquitetura de software, sistemas distribuídos, messaging, CQRS e Event Sourcing em nível conceitual.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 16.00 | [Dados em Tempo Real e Comunicação Assíncrona](16.00-dados-em-tempo-real-e-comunicacao-assincrona.md) | Guarda-chuva | Rascunho |
| 16.01 | [Do Request/Response ao Tempo Real](16.01-do-request-response-ao-tempo-real.md) | Específica ampla | Rascunho |
| 16.02 | [Short Polling](16.02-short-polling.md) | Específica | Rascunho |
| 16.03 | [Long Polling](16.03-long-polling.md) | Específica | Rascunho |
| 16.04 | [Server-Sent Events](16.04-server-sent-events.md) | Específica | Rascunho |
| 16.05 | [WebSocket](16.05-websocket.md) | Específica | Rascunho |
| 16.06 | [Tempo Real na Prática: Estado, Reconexão e Falhas](16.06-tempo-real-na-pratica-estado-reconexao-e-falhas.md) | Específica prática | Rascunho |
| 16.07 | [Processamento Assíncrono](16.07-processamento-assincrono.md) | Guarda-chuva curta | Rascunho |
| 16.08 | [Background Jobs](16.08-background-jobs.md) | Específica | Rascunho |
| 16.09 | [Filas](16.09-filas.md) | Específica | Rascunho |
| 16.10 | [Message Brokers](16.10-message-brokers.md) | Específica | Rascunho |
| 16.11 | [Pub/Sub](16.11-pub-sub.md) | Específica | Rascunho |
| 16.12 | [Operações Idempotentes em Fluxos Assíncronos](16.12-operacoes-idempotentes-em-fluxos-assincronos.md) | Específica | Rascunho |
| 16.13 | [Projeto Prático: Notificações e Jobs Assíncronos em uma API](16.13-projeto-pratico-notificacoes-e-jobs-assincronos-em-uma-api.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em 3 blocos. Siga a ordem dos blocos e preserve o mesmo fluxo prático entre os exercícios.

**Bloco A — Escolha de comunicação e recuperação** · aulas [16.00–16.06]
Compara request/response, polling, SSE e WebSocket, incluindo estado, autorização e reconexão.
Pré-requisito: arquitetura de APIs e comunicação HTTP.

**Bloco B — Processamento em background** · aulas [16.07–16.10]
Transforma uma operação demorada em job, fila e consumidor com estados, retentativas e capacidade limitada.
Pré-requisito: Bloco A e a especificação produzida no módulo 15.

**Bloco C — Eventos, idempotência e integração** · aulas [16.11–16.13]
Diferencia filas de pub/sub, protege efeitos contra duplicidade e integra o fluxo completo.
Pré-requisito: Bloco B.

## Exercícios

- [Exercício 01 — Escolha de Comunicação](exercicios/01-escolha-de-comunicacao.md)
- [Exercício 02 — Tempo Real, Reconexão e Estado](exercicios/02-tempo-real-reconexao-e-estado.md)
- [Exercício 03 — Job Assíncrono e Status](exercicios/03-job-assincrono-e-status.md)
- [Exercício 04 — Fila, Retentativas e Backpressure](exercicios/04-fila-retries-e-backpressure.md)
- [Exercício 05 — Pub/Sub e Contratos de Evento](exercicios/05-pub-sub-e-contratos-de-evento.md)
- [Exercício 06 — Idempotência e Recuperação](exercicios/06-idempotencia-e-recuperacao.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você implementará o fluxo assíncrono especificado no módulo 15. A evolução ocorre em etapas:

1. escolha uma técnica de atualização compatível com a direção, a latência e o custo do problema;
2. crie uma operação que responda `202 Accepted` e exponha o estado do job;
3. separe produtor e consumidor, limitando retentativas e concorrência;
4. diferencie uma fila de trabalho de um evento com múltiplos assinantes;
5. torne o efeito do consumidor idempotente;
6. integre atualização do cliente, recuperação após desconexão, observabilidade e testes.

O caminho mínimo usa short polling e uma fila local ou simulada. Brokers, SSE e WebSocket são escolhas possíveis, não requisitos. O resultado será retomado nos módulos de cloud e operação.

## O Que Revisar Antes de Avançar

- HTTP, cache, estado e diferença entre cliente e servidor.
- Assincronismo em JavaScript, event loop, Promises e async/await.
- APIs, workers, failure modes e message brokers em backend.
- Idempotência, webhooks e contratos de API.
- Logging, métricas, tracing, monitoramento e alertas.
- Sistemas distribuídos, messaging, CQRS e Event Sourcing.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Dados em Tempo Real e Comunicação Assíncrona de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina comunicação além do request/response tradicional, incluindo short polling, long polling, SSE, WebSocket, processamento assíncrono, background jobs, filas, brokers, pub/sub e idempotência.
- Objetivo do módulo: Quero escolher a forma correta de comunicação para cada problema e entender os riscos de falhas, duplicidade, atraso, reconexão e reprocessamento.
- Pré-requisitos: HTTP, JavaScript assíncrono, backend com Node.js, APIs, idempotência, segurança, observabilidade e arquitetura de software.

Crie uma revisão guiada com perguntas conceituais, exercícios práticos, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial de Web APIs quando uma aula exigir detalhes de browser.
- Documentação oficial de brokers e filas específicas somente quando uma aula exigir detalhes de ferramenta.

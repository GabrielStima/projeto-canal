<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Backend com Node.js

</div>

Este módulo apresenta backend com Node.js como a transição entre consumir APIs e construir serviços próprios. Até aqui, você já estudou Web, TypeScript, ferramentas, frontend moderno, Next.js e bancos de dados. Agora a pergunta muda: como criar uma aplicação que recebe requisições, executa regras, conversa com bancos e devolve respostas confiáveis?

O objetivo não é decorar frameworks. A ideia é entender o que o Node.js oferece como runtime, como um servidor processa requisições, por que frameworks existem, como APIs são organizadas e quais cuidados aparecem quando o backend passa a depender de banco, logs, filas, workers, busca e performance.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o papel do Node.js em aplicações backend;
- diferenciar runtime, linguagem, processo, módulo e framework;
- criar scripts e servidores HTTP simples com Node.js;
- entender o event loop no contexto de backend;
- organizar uma API JSON pequena;
- comparar REST, SOAP e GraphQL em alto nível;
- entender o papel de especificações OpenAPI;
- conectar um backend a bancos de dados com e sem ORM;
- construir um fluxo persistente que reutiliza schema, migrations e consultas do módulo anterior;
- reconhecer falhas comuns em serviços backend;
- usar logging, workers e profiling em nível introdutório;
- entender quando message brokers e motores de busca entram em uma arquitetura.

## Por Que Este Módulo Existe

Nos módulos anteriores, você consumiu APIs, criou endpoints introdutórios no Next.js e estudou persistência. Isso prepara o terreno, mas ainda não mostra o backend como uma aplicação própria, com ciclo de vida, processo, configuração, responsabilidades, dependências externas e riscos de falha.

Backend com Node.js aparece aqui para consolidar fundamentos antes de entrar em API Design Profissional, Autenticação, Segurança, Qualidade, Observabilidade, Performance e Arquitetura. O módulo mostra a base que esses temas vão aprofundar depois.

## Pré-requisitos

- Entender HTTP, cliente, servidor, request, response, status code e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Entender funções, objetos, arrays, módulos, promises, `async/await` e tratamento de erros.
- Saber usar terminal, gerenciadores de pacote, scripts e variáveis de ambiente.
- Entender chamadas de API, formulários, validação e Route Handlers introdutórios.
- Ter estudado SQL, NoSQL, modelagem, transactions, migrations e indexes em nível introdutório.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 10.00 | [Backend com Node.js](10.00-backend-com-nodejs.md) | Guarda-chuva | Auditada |
| 10.01 | [Node.js](10.01-nodejs.md) | Específica ampla | Auditada |
| 10.02 | [Runtime](10.02-runtime.md) | Específica conceitual | Auditada |
| 10.03 | [Event Loop no Node.js](10.03-event-loop-no-nodejs.md) | Específica | Auditada |
| 10.04 | [Módulos no Node.js](10.04-modulos-no-nodejs.md) | Específica prática | Auditada |
| 10.05 | [CLI com Node.js](10.05-cli-com-nodejs.md) | Específica prática | Auditada |
| 10.06 | [Servidor HTTP com Node.js Puro](10.06-servidor-http-com-nodejs-puro.md) | Específica prática | Auditada |
| 10.07 | [Frameworks Backend](10.07-frameworks-backend.md) | Guarda-chuva curta | Auditada |
| 10.08 | [APIs](10.08-apis.md) | Guarda-chuva curta | Auditada |
| 10.09 | [JSON APIs](10.09-json-apis.md) | Específica prática | Auditada |
| 10.10 | [REST](10.10-rest.md) | Específica ampla | Auditada |
| 10.11 | [SOAP](10.11-soap.md) | Específica comparativa | Auditada |
| 10.12 | [GraphQL](10.12-graphql.md) | Específica comparativa | Auditada |
| 10.13 | [OpenAPI Specs](10.13-openapi-specs.md) | Específica introdutória | Auditada |
| 10.14 | [Logging](10.14-logging.md) | Específica prática | Auditada |
| 10.15 | [Working with DB](10.15-working-with-db.md) | Específica prática | Auditada |
| 10.16 | [ACID no Backend](10.16-acid-no-backend.md) | Específica conceitual | Auditada |
| 10.17 | [Normalization no Backend](10.17-normalization-no-backend.md) | Específica conceitual | Auditada |
| 10.18 | [ORMs](10.18-orms.md) | Específica prática | Auditada |
| 10.19 | [Failure Modes](10.19-failure-modes.md) | Guarda-chuva curta | Auditada |
| 10.20 | [Threads e Workers](10.20-threads-e-workers.md) | Específica conceitual/prática | Auditada |
| 10.21 | [Profiling Performance](10.21-profiling-performance.md) | Específica prática | Auditada |
| 10.22 | [Message Brokers](10.22-message-brokers.md) | Guarda-chuva curta | Auditada |
| 10.23 | [Motores de Busca](10.23-motores-de-busca.md) | Específica introdutória | Auditada |
| 10.24 | [Projeto Prático: API Backend com Node.js](10.24-projeto-pratico-api-backend-com-nodejs.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Siga a ordem para evoluir uma única API sem concentrar toda a implementação no encerramento.

**Bloco A — Runtime e servidor** · aulas 10.00–10.06
Node.js, runtime, event loop, módulos, CLI e servidor HTTP nativo.
Pré-requisito: TypeScript, HTTP e a camada de dados do módulo 09.

Depois do servidor HTTP, faça o [Exercício 01 — Base do Serviço Node.js](exercicios/01-base-do-servico.md).

**Bloco B — Framework e formatos de API** · aulas 10.07–10.13
Frameworks backend, APIs JSON, REST e comparação introdutória com SOAP, GraphQL e OpenAPI.
Pré-requisito: Bloco A.

Ao concluir OpenAPI, faça o [Exercício 02 — API JSON Inicial](exercicios/02-api-json.md).

**Bloco C — Persistência e comportamento diante de falhas** · aulas 10.14–10.19
Logging, acesso a banco, ACID, normalização, ORMs e failure modes.
Pré-requisito: Bloco B e diretório `database/` produzido no módulo 09.

Depois de ORMs, faça o [Exercício 03 — Banco e Consistência](exercicios/03-banco-e-consistencia.md). Ao concluir failure modes, faça o [Exercício 04 — Logs e Falhas](exercicios/04-logs-e-falhas.md).

**Bloco D — Trabalho pesado e integrações opcionais** · aulas 10.20–10.23
Workers, profiling, message brokers e motores de busca.
Pré-requisito: Bloco C.

Faça o [Exercício 05 — Worker e Medição](exercicios/05-worker-e-medicao.md) como prática recomendada. Finalize o bloco com o [Exercício 06 — Decisões de Integração](exercicios/06-decisoes-de-integracao.md).

## Exercícios

- [Exercício 01 — Base do Serviço Node.js](exercicios/01-base-do-servico.md)
- [Exercício 02 — API JSON Inicial](exercicios/02-api-json.md)
- [Exercício 03 — Banco e Consistência](exercicios/03-banco-e-consistencia.md)
- [Exercício 04 — Logs e Falhas](exercicios/04-logs-e-falhas.md)
- [Exercício 05 — Worker e Medição](exercicios/05-worker-e-medicao.md)
- [Exercício 06 — Decisões de Integração](exercicios/06-decisoes-de-integracao.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Evolua o PetCare OS construindo uma API Node.js para consultar pets e atendimentos e aprovar um orçamento de forma persistente:

1. Preserve e use o diretório `database/` produzido no módulo 09.
2. Crie configuração, CLI e health check.
3. Comece com `node:http` e depois adote um framework backend proporcional.
4. Implemente endpoints JSON para pets, atendimentos e orçamentos.
5. Documente os endpoints com OpenAPI em nível introdutório.
6. Conecte a API ao banco relacional.
7. Proteja a aprovação de orçamento com transaction.
8. Compare SQL direto com ORM sem exigir uma migração completa.
9. Adicione logs estruturados e analise failure modes.
10. Meça um trabalho CPU-bound com e sem worker.
11. Decida se broker e motor de busca são necessários para a primeira versão.

A [Atividade Final do Módulo](exercicios/atividade-final-modulo.md) demonstra o fluxo completo e prepara a mesma API para o módulo 11.

## O Que Entra e O Que Sai Deste Módulo

**O que entra do módulo anterior:**

- schema, seed, queries, transaction, índices e migrations no diretório `database/`;
- decisão de persistência e regras de acesso;
- Portal do Tutor e seus dados simulados;
- tipos e regras de domínio acumulados na formação.

**O que sai deste módulo:**

- projeto `petcare-api` em Node.js e TypeScript;
- configuração e CLI de verificação;
- servidor, framework e health check;
- endpoints persistentes para um fluxo vertical;
- OpenAPI introdutória;
- transaction de aprovação de orçamento;
- logs estruturados e análise de falhas;
- medição opcional com worker;
- decisões proporcionais sobre ORM, broker e busca;
- README que permite executar e demonstrar a API.

**Onde isso será retomado:**

- no módulo 11, o contrato será refinado com erros padronizados, paginação, filtros, compatibilidade e testes de contrato;
- no módulo 12, a API receberá autenticação e autorização reais;
- nos módulos 13A e 13B, o fluxo ganhará testes, métricas e observabilidade;
- no módulo 16, notificações e processamento assíncrono poderão ser implementados com maior profundidade.

## O Que Revisar Antes de Avançar

- HTTP, status codes, headers, cache e estado.
- TypeScript, módulos, promises, `async/await` e tratamento de erros.
- Terminal, scripts, pacotes e variáveis de ambiente.
- Chamadas de API, validação e dados em JSON.
- Modelagem de dados, transactions, indexes e migrations.
- Diferença entre backend, backend-for-frontend e frontend.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Backend com Node.js de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina Node.js como runtime backend, servidores HTTP, frameworks, APIs, JSON APIs, REST, SOAP, GraphQL, OpenAPI, logging, banco de dados, ORMs, ACID, normalização, failure modes, workers, profiling, message brokers e motores de busca.
- Objetivo do módulo: Quero conseguir construir uma API backend pequena, entender suas dependências e reconhecer riscos comuns antes de estudar API design, segurança e observabilidade em profundidade.
- Pré-requisitos: fundamentos da Web, TypeScript, terminal, pacotes, variáveis de ambiente, chamadas de API, Next.js introdutório e bancos de dados.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em Node.js e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do Node.js.
- Documentação oficial do runtime, APIs nativas e módulos do Node.js.
- Documentação oficial do framework backend escolhido para prática.
- Documentação oficial do banco de dados e ORM escolhidos para prática.
- Documentação da MDN sobre HTTP, APIs e Web.

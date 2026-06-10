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
| 10.00 | [Backend com Node.js](10.00-backend-com-nodejs.md) | Guarda-chuva | Rascunho |
| 10.01 | [Node.js](10.01-nodejs.md) | Específica ampla | Rascunho |
| 10.02 | [Runtime](10.02-runtime.md) | Específica conceitual | Rascunho |
| 10.03 | [Event Loop no Node.js](10.03-event-loop-no-nodejs.md) | Específica | Rascunho |
| 10.04 | [Módulos no Node.js](10.04-modulos-no-nodejs.md) | Específica prática | Rascunho |
| 10.05 | [CLI com Node.js](10.05-cli-com-nodejs.md) | Específica prática | Rascunho |
| 10.06 | [Servidor HTTP com Node.js Puro](10.06-servidor-http-com-nodejs-puro.md) | Específica prática | Rascunho |
| 10.07 | [Frameworks Backend](10.07-frameworks-backend.md) | Guarda-chuva curta | Rascunho |
| 10.08 | [APIs](10.08-apis.md) | Guarda-chuva curta | Rascunho |
| 10.09 | [JSON APIs](10.09-json-apis.md) | Específica prática | Rascunho |
| 10.10 | [REST](10.10-rest.md) | Específica ampla | Rascunho |
| 10.11 | [SOAP](10.11-soap.md) | Específica comparativa | Rascunho |
| 10.12 | [GraphQL](10.12-graphql.md) | Específica comparativa | Rascunho |
| 10.13 | [OpenAPI Specs](10.13-openapi-specs.md) | Específica introdutória | Rascunho |
| 10.14 | [Logging](10.14-logging.md) | Específica prática | Rascunho |
| 10.15 | [Working with DB](10.15-working-with-db.md) | Específica prática | Rascunho |
| 10.16 | [ACID no Backend](10.16-acid-no-backend.md) | Específica conceitual | Rascunho |
| 10.17 | [Normalization no Backend](10.17-normalization-no-backend.md) | Específica conceitual | Rascunho |
| 10.18 | [ORMs](10.18-orms.md) | Específica prática | Rascunho |
| 10.19 | [Failure Modes](10.19-failure-modes.md) | Guarda-chuva curta | Rascunho |
| 10.20 | [Threads e Workers](10.20-threads-e-workers.md) | Específica conceitual/prática | Rascunho |
| 10.21 | [Profiling Performance](10.21-profiling-performance.md) | Específica prática | Rascunho |
| 10.22 | [Message Brokers](10.22-message-brokers.md) | Guarda-chuva curta | Rascunho |
| 10.23 | [Motores de Busca](10.23-motores-de-busca.md) | Específica introdutória | Rascunho |
| 10.24 | [Projeto Prático: API Backend com Node.js](10.24-projeto-pratico-api-backend-com-nodejs.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Construa uma API backend para o painel de estudos usado nos módulos anteriores:

1. Crie um projeto Node.js com TypeScript.
2. Crie uma CLI pequena para validar ambiente e dados iniciais.
3. Suba um servidor HTTP e depois evolua para um framework backend.
4. Crie endpoints JSON para aulas, tags, usuários e progresso.
5. Documente uma parte da API com OpenAPI em nível introdutório.
6. Conecte a API a um banco de dados.
7. Use transactions onde houver mudança crítica de estado.
8. Compare acesso direto ao banco com uso de ORM.
9. Adicione logs estruturados básicos.
10. Liste failure modes e testes manuais de resiliência.
11. Simule uma tarefa pesada com worker.
12. Analise um gargalo simples de performance.

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

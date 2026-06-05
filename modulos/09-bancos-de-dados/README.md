# Bancos de Dados

Este módulo apresenta bancos de dados como a base de persistência das aplicações. Até aqui, você já construiu telas, formulários, chamadas de API, rotas e aplicações Next.js pequenas. Agora a pergunta muda: onde os dados vivem quando a aplicação fecha, quando outro usuário acessa, ou quando o sistema precisa crescer?

A ideia não é decorar comandos isolados. O objetivo é entender como modelar dados, consultar informações, proteger consistência, evoluir estruturas e comparar bancos relacionais e não relacionais com bom senso.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar por que aplicações precisam de persistência;
- diferenciar bancos relacionais, SQL, NoSQL e bancos orientados a documentos;
- modelar dados simples para uma aplicação real;
- escrever consultas SQL básicas e intermediárias;
- entender `JOIN`, subqueries, views, indexes e transactions;
- reconhecer riscos de integridade, segurança, performance e backup;
- entender o papel de migrations na evolução de schema;
- usar MongoDB em nível conceitual e prático inicial;
- comparar decisões de modelagem entre SQL e NoSQL;
- chegar ao módulo de backend preparado para conectar aplicações a bancos reais.

## Por Que Este Módulo Existe

Nos módulos anteriores, muitos dados podiam ser simulados em memória, arquivos locais ou respostas falsas de API. Isso é suficiente para aprender interface, fluxo e validação, mas aplicações reais precisam lembrar informações, compartilhar dados entre usuários, proteger operações importantes e recuperar estados depois de falhas.

Bancos de dados entram nesse ponto da trilha porque conectam frontend, backend, segurança, produto e operação. Uma escolha ruim de modelagem pode complicar uma API. Uma query lenta pode derrubar uma tela. Uma migration mal feita pode quebrar produção. Um backup inexistente pode transformar erro pequeno em desastre.

Este módulo prepara o caminho para backend com Node.js, ORMs, autenticação, autorização, segurança, observabilidade, performance e system design.

## Pré-requisitos

- Entender HTTP, request, response, cliente, servidor e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Entender objetos, arrays, funções, módulos, promises e `async/await`.
- Entender formulários, validação e chamadas de API.
- Ter noções de terminal, scripts, variáveis de ambiente e projeto Next.js.
- Saber ler exemplos pequenos de dados estruturados.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 09.00 | Bancos de Dados | Guarda-chuva | Rascunho |
| 09.01 | [SQL e NoSQL](09.01-sql-e-nosql.md) | Guarda-chuva curta | Rascunho |
| 09.02 | [Modelagem de Dados](09.02-modelagem-de-dados.md) | Específica ampla | Rascunho |
| 09.03 | [SQL Básico](09.03-sql-basico.md) | Específica | Rascunho |
| 09.04 | [Integridade de Dados](09.04-integridade-de-dados.md) | Específica | Rascunho |
| 09.05 | [JOIN Queries](09.05-join-queries.md) | Específica | Rascunho |
| 09.06 | [Subqueries](09.06-subqueries.md) | Específica | Rascunho |
| 09.07 | [Funções Avançadas em SQL](09.07-funcoes-avancadas-em-sql.md) | Específica | Rascunho |
| 09.08 | [Views](09.08-views.md) | Específica | Rascunho |
| 09.09 | [Transactions](09.09-transactions.md) | Específica | Rascunho |
| 09.10 | [Indexes](09.10-indexes.md) | Específica | Rascunho |
| 09.11 | [Performance Optimization em SQL](09.11-performance-optimization-em-sql.md) | Específica ampla | Rascunho |
| 09.12 | [SQL Avançado](09.12-sql-avancado.md) | Guarda-chuva curta | Rascunho |
| 09.13 | [Stored Procedures e Functions](09.13-stored-procedures-e-functions.md) | Específica | Rascunho |
| 09.14 | [Migrations](09.14-migrations.md) | Específica prática | Rascunho |
| 09.15 | [Backup e Restore](09.15-backup-e-restore.md) | Específica | Rascunho |
| 09.16 | [Segurança em Bancos Relacionais](09.16-seguranca-em-bancos-relacionais.md) | Específica | Rascunho |
| 09.17 | [NoSQL Básico](09.17-nosql-basico.md) | Guarda-chuva curta | Rascunho |
| 09.18 | [MongoDB](09.18-mongodb.md) | Específica ampla | Rascunho |
| 09.19 | [Conceitos Úteis no MongoDB](09.19-conceitos-uteis-no-mongodb.md) | Específica | Rascunho |
| 09.20 | [Operadores de Query no MongoDB](09.20-operadores-de-query-no-mongodb.md) | Específica prática | Rascunho |
| 09.21 | [Aggregation no MongoDB](09.21-aggregation-no-mongodb.md) | Específica | Rascunho |
| 09.22 | [Transactions no MongoDB](09.22-transactions-no-mongodb.md) | Específica | Rascunho |
| 09.23 | [Scaling em Bancos de Dados](09.23-scaling-em-bancos-de-dados.md) | Guarda-chuva curta | Rascunho |
| 09.24 | [Security em NoSQL e MongoDB](09.24-security-em-nosql-e-mongodb.md) | Específica | Rascunho |
| 09.25 | [Projeto Prático: Persistência de Dados em uma Aplicação Fullstack](09.25-projeto-pratico-persistencia-de-dados-em-uma-aplicacao-fullstack.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Construa a camada de dados de uma pequena aplicação de estudos:

1. Modele usuários, materiais de estudo, tags e progresso.
2. Crie uma versão relacional do modelo.
3. Escreva consultas para listar, filtrar, relacionar e resumir dados.
4. Adicione constraints para proteger integridade.
5. Planeje uma migration simples.
6. Discuta quais índices fariam sentido.
7. Modele uma versão documental em MongoDB.
8. Compare o que ficou melhor em SQL e o que ficou mais natural em documento.
9. Liste riscos de segurança, backup, restore e crescimento.

## O Que Revisar Antes de Avançar

- HTTP, estado e APIs.
- Objetos, arrays e tipos em TypeScript.
- Validação de entrada.
- Erros e tratamento de falhas.
- Variáveis de ambiente.
- Diferença entre frontend, backend-for-frontend e backend.
- Noção de projeto com dados simulados em Next.js.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Bancos de Dados de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina persistência, modelagem, bancos relacionais, SQL, integridade, consultas, performance, migrations, backup, segurança, NoSQL e MongoDB.
- Objetivo do módulo: Quero conseguir pensar dados antes de conectar uma aplicação real a um backend.
- Pré-requisitos: fundamentos da Web, TypeScript, formulários, validação, chamadas de API, terminal, variáveis de ambiente e Next.js introdutório.

Os assuntos estudados foram:
- SQL e NoSQL
- Modelagem de dados
- SQL básico
- Integridade de dados
- JOIN queries
- Subqueries
- Funções avançadas
- Views
- Transactions
- Indexes
- Performance optimization
- SQL avançado
- Stored procedures e functions
- Migrations
- Backup e restore
- Segurança
- NoSQL básico
- MongoDB
- Operadores de query
- Aggregation
- Transactions no MongoDB
- Scaling
- Security

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de modelagem e consulta;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do PostgreSQL.
- Documentação oficial do MongoDB.
- Documentação da MDN sobre aplicações web, segurança e APIs.
- Materiais oficiais do banco escolhido para prática local.

<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Bancos de Dados

</div>

Este módulo apresenta bancos de dados como a base de persistência das aplicações. Até aqui, você já construiu telas, formulários, chamadas de API, rotas e aplicações Next.js pequenas. Agora a pergunta muda: onde os dados vivem quando a aplicação fecha, quando outro usuário acessa, ou quando o sistema precisa crescer?

A ideia não é decorar comandos isolados. O objetivo é entender como modelar dados, consultar informações, proteger a consistência, evoluir estruturas e comparar bancos relacionais e não relacionais com bom senso.

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
- produzir schema, dados iniciais, migrations e consultas que possam ser executados e verificados;
- chegar ao módulo de backend preparado para conectar aplicações a bancos reais.

## Por Que Este Módulo Existe

Nos módulos anteriores, muitos dados podiam ser simulados em memória, arquivos locais ou respostas falsas de API. Isso é suficiente para aprender interface, fluxo e validação, mas aplicações reais precisam lembrar informações, compartilhar dados entre usuários, proteger operações importantes e recuperar estados depois de falhas.

Bancos de dados entram nesse ponto da trilha porque conectam frontend, backend, segurança, produto e operação. Uma escolha ruim de modelagem pode complicar uma API. Uma query lenta pode derrubar uma tela. Uma migration mal feita pode quebrar produção. Um backup inexistente pode transformar um erro pequeno em desastre.

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
| 09.00 | [Bancos de Dados](09.00-bancos-de-dados.md) | Guarda-chuva | Auditada |
| 09.01 | [SQL e NoSQL](09.01-sql-e-nosql.md) | Guarda-chuva curta | Auditada |
| 09.02 | [Modelagem de Dados](09.02-modelagem-de-dados.md) | Específica ampla | Auditada |
| 09.03 | [SQL Básico](09.03-sql-basico.md) | Específica | Auditada |
| 09.04 | [Integridade de Dados](09.04-integridade-de-dados.md) | Específica | Auditada |
| 09.05 | [JOIN Queries](09.05-join-queries.md) | Específica | Auditada |
| 09.06 | [Subqueries](09.06-subqueries.md) | Específica | Auditada |
| 09.07 | [Funções Avançadas em SQL](09.07-funcoes-avancadas-em-sql.md) | Específica | Auditada |
| 09.08 | [Views](09.08-views.md) | Específica | Auditada |
| 09.09 | [Transactions](09.09-transactions.md) | Específica | Auditada |
| 09.10 | [Indexes](09.10-indexes.md) | Específica | Auditada |
| 09.11 | [Performance Optimization em SQL](09.11-performance-optimization-em-sql.md) | Específica ampla | Auditada |
| 09.12 | [SQL Avançado](09.12-sql-avancado.md) | Guarda-chuva curta | Auditada |
| 09.13 | [Stored Procedures e Functions](09.13-stored-procedures-e-functions.md) | Específica | Auditada |
| 09.14 | [Migrations](09.14-migrations.md) | Específica prática | Auditada |
| 09.15 | [Backup e Restore](09.15-backup-e-restore.md) | Específica | Auditada |
| 09.16 | [Segurança em Bancos Relacionais](09.16-seguranca-em-bancos-relacionais.md) | Específica | Auditada |
| 09.17 | [NoSQL Básico](09.17-nosql-basico.md) | Guarda-chuva curta | Auditada |
| 09.18 | [MongoDB](09.18-mongodb.md) | Específica ampla | Auditada |
| 09.19 | [Conceitos Úteis no MongoDB](09.19-conceitos-uteis-no-mongodb.md) | Específica | Auditada |
| 09.20 | [Operadores de Query no MongoDB](09.20-operadores-de-query-no-mongodb.md) | Específica prática | Auditada |
| 09.21 | [Aggregation no MongoDB](09.21-aggregation-no-mongodb.md) | Específica | Auditada |
| 09.22 | [Transactions no MongoDB](09.22-transactions-no-mongodb.md) | Específica | Auditada |
| 09.23 | [Scaling em Bancos de Dados](09.23-scaling-em-bancos-de-dados.md) | Guarda-chuva curta | Auditada |
| 09.24 | [Security em NoSQL e MongoDB](09.24-security-em-nosql-e-mongodb.md) | Específica | Auditada |
| 09.25 | [Projeto Prático: Persistência de Dados em uma Aplicação Fullstack](09.25-projeto-pratico-persistencia-de-dados-em-uma-aplicacao-fullstack.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em três blocos, além da introdução e da atividade final. Siga a ordem para construir a camada de dados sem concentrar toda a prática no encerramento.

**Introdução — Decisões de persistência** · aulas 09.00–09.01
Panorama do módulo e comparação inicial entre modelos relacionais e não relacionais.
Pré-requisito: aplicação Next.js com dados simulados.

**Bloco A — Modelo e consultas relacionais** · aulas 09.02–09.08
Modelagem, SQL básico, integridade, JOINs, subqueries, agregações e views.
Pré-requisito: Introdução.

Ao concluir a modelagem, faça o [Exercício 01 — Modelo Relacional do PetCare OS](exercicios/01-modelo-relacional.md). Depois de estudar views, faça o [Exercício 02 — Schema, Dados Iniciais e Consultas](exercicios/02-schema-e-consultas.md).

**Bloco B — Consistência, evolução e proteção** · aulas 09.09–09.16
Transactions, indexes, performance, recursos avançados, migrations, backup, restore e segurança.
Pré-requisito: Bloco A.

Após performance, faça o [Exercício 03 — Consistência e Performance](exercicios/03-consistencia-e-performance.md). Depois de segurança em bancos relacionais, faça o [Exercício 04 — Evolução, Recuperação e Acesso](exercicios/04-evolucao-e-recuperacao.md).

**Bloco C — Modelos não relacionais e decisão técnica** · aulas 09.17–09.24
NoSQL, MongoDB, modelagem documental, consultas, aggregation, transactions, escala e segurança.
Pré-requisito: 09.01 e 09.02. O Bloco A completo torna a comparação mais concreta.

Após aggregation, faça o [Exercício 05 — Modelo Documental para Auditoria](exercicios/05-modelo-documental.md). Ele é recomendado e não obriga o projeto a usar um segundo banco. Ao terminar o bloco, faça o [Exercício 06 — Decisão de Persistência](exercicios/06-decisao-de-persistencia.md).

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Exercícios

- [Exercício 01 — Modelo Relacional do PetCare OS](exercicios/01-modelo-relacional.md)
- [Exercício 02 — Schema, Dados Iniciais e Consultas](exercicios/02-schema-e-consultas.md)
- [Exercício 03 — Consistência e Performance](exercicios/03-consistencia-e-performance.md)
- [Exercício 04 — Evolução, Recuperação e Acesso](exercicios/04-evolucao-e-recuperacao.md)
- [Exercício 05 — Modelo Documental para Auditoria](exercicios/05-modelo-documental.md)
- [Exercício 06 — Decisão de Persistência](exercicios/06-decisao-de-persistencia.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Evolua o Portal do Tutor construído no módulo 08 para que seus dados simulados tenham uma camada de persistência planejada e verificável.

Ao longo dos exercícios, você produzirá:

1. modelo relacional de tutores, pets, atendimentos, orçamentos, itens e serviços;
2. schema SQL e dados iniciais;
3. consultas e uma view para o Portal do Tutor;
4. transaction para aprovação de orçamento;
5. índices justificados por consultas;
6. migrations versionadas;
7. plano de backup e restore;
8. regras de acesso e proteção de credenciais;
9. estudo comparativo de um modelo documental para auditoria;
10. decisão de persistência para a primeira versão.

A [Atividade Final do Módulo](exercicios/atividade-final-modulo.md) organiza e verifica esses arquivos. O resultado será retomado no módulo 10, quando uma API Node.js passará a acessar o banco.

## O Que Entra e O Que Sai Deste Módulo

**O que entra do módulo anterior:**

- Portal do Tutor em Next.js com rotas, formulários e dados simulados;
- tipos e regras das entidades construídos nos módulos de TypeScript e algoritmos;
- jornadas e requisitos definidos no módulo de produto;
- repositório com scripts, lint e fluxo de trabalho.

**O que sai deste módulo:**

- modelo relacional documentado;
- schema e seed executáveis;
- consultas SQL verificáveis e uma view de leitura;
- transaction e índices justificados;
- migrations ordenadas;
- orientações de recuperação e acesso;
- comparação SQL/NoSQL sem obrigar uma arquitetura com dois bancos;
- decisão registrada para orientar o backend.

**Onde isso será retomado:**

- no módulo 10, a API Node.js usará o schema, as regras e as consultas produzidas aqui;
- no módulo 11, as consultas ajudarão a definir recursos, filtros e contratos da API;
- no módulo 12, as regras de acesso serão aprofundadas em autenticação e autorização.

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

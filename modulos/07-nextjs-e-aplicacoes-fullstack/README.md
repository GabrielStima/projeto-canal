# Next.js e Aplicacoes Fullstack no Frontend

Este modulo apresenta o Next.js como ponte entre frontend moderno, renderizacao no servidor, backend-for-frontend e deploy de aplicacoes React.

O objetivo nao e tratar Next.js como magia nem como substituto de fundamentos. A ideia e entender quais problemas ele resolve: rotas por arquivos, layouts persistentes, componentes no servidor, componentes no cliente, busca de dados, formularios, APIs internas, tratamento de carregamento e erro, autenticacao em nivel introdutorio e publicacao da aplicacao.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar o papel do Next.js em uma aplicacao React moderna;
- criar rotas e layouts usando o App Router;
- diferenciar Server Components e Client Components;
- escolher estrategias basicas de renderizacao;
- representar loading, erro e suspense em fluxos reais;
- buscar dados e criar endpoints simples com Route Handlers;
- construir formularios com tipos e validacao;
- entender autenticacao no contexto de UI e sessao;
- preparar uma aplicacao Next.js para deploy.

## Por Que Este Modulo Existe

No modulo anterior, voce estudou React, componentes, estado, rotas, formularios, chamadas de API, testes e performance no frontend. Isso e suficiente para criar SPAs, mas muitas aplicacoes reais precisam tambem de renderizacao no servidor, melhor carregamento inicial, rotas mais integradas, busca de dados perto da tela e pequenos endpoints para atender o frontend.

Next.js aparece nessa transicao. Ele continua usando React, mas adiciona convencoes de projeto e recursos fullstack. Este modulo prepara o caminho para bancos de dados, backend com Node.js, autenticacao profunda, seguranca, observabilidade e deploy mais avancado.

## Pre-requisitos

- Entender HTTP, cliente, servidor, request, response e estado.
- Saber usar HTML, CSS, formularios, responsividade e acessibilidade em nivel pratico.
- Saber escrever JavaScript moderno e TypeScript.
- Entender promises, `async/await`, modulos e tratamento de erros.
- Entender React, componentes, renderizacao, hooks, estado, rotas e chamadas de API.
- Saber usar terminal, gerenciadores de pacote, scripts e variaveis de ambiente.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 07.00 | Next.js e Aplicacoes Fullstack no Frontend | Guarda-chuva | Rascunho |
| 07.01 | [Next.js](07.01-nextjs.md) | Especifica ampla | Rascunho |
| 07.02 | [Rotas no App Router](07.02-rotas-no-app-router.md) | Especifica | Rascunho |
| 07.03 | [Layouts](07.03-layouts.md) | Especifica | Rascunho |
| 07.04 | [Estrategias de renderizacao](07.04-estrategias-de-renderizacao.md) | Guarda-chuva curta | Rascunho |
| 07.05 | [Server Components](07.05-server-components.md) | Especifica | Rascunho |
| 07.06 | [Client Components](07.06-client-components.md) | Especifica | Rascunho |
| 07.07 | [Composicao entre Server e Client Components](07.07-composicao-entre-server-e-client-components.md) | Especifica pratica | Rascunho |
| 07.08 | [Loading states e streaming](07.08-loading-states-e-streaming.md) | Especifica | Rascunho |
| 07.09 | [Error boundaries](07.09-error-boundaries.md) | Especifica | Rascunho |
| 07.10 | [Suspense no contexto do Next.js](07.10-suspense-no-contexto-do-nextjs.md) | Especifica conceitual | Rascunho |
| 07.11 | [Chamadas de API e busca de dados](07.11-chamadas-de-api-e-busca-de-dados.md) | Especifica pratica | Rascunho |
| 07.12 | [Route Handlers e APIs no Next.js](07.12-route-handlers-e-apis-no-nextjs.md) | Especifica pratica | Rascunho |
| 07.13 | [Formularios em Next.js](07.13-formularios-em-nextjs.md) | Especifica | Rascunho |
| 07.14 | [Tipos e validacao](07.14-tipos-e-validacao.md) | Especifica | Rascunho |
| 07.15 | [Autenticacao no contexto frontend](07.15-autenticacao-no-contexto-frontend.md) | Especifica introdutoria | Rascunho |
| 07.16 | [Animacoes em aplicacoes Next.js](07.16-animacoes-em-aplicacoes-nextjs.md) | Especifica | Rascunho |
| 07.17 | [Deploy de aplicacoes Next.js](07.17-deploy-de-aplicacoes-nextjs.md) | Especifica pratica | Rascunho |
| 07.18 | [Projeto pratico: aplicacao fullstack com Next.js](07.18-projeto-pratico-aplicacao-fullstack-com-nextjs.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Construa uma pequena aplicacao de painel de estudos com Next.js e TypeScript:

1. Crie rotas para lista, detalhes e cadastro.
2. Use um layout principal com navegacao.
3. Busque dados em Server Components.
4. Use Client Components apenas onde houver interatividade.
5. Mostre estados de loading e erro.
6. Crie um Route Handler simples.
7. Construa um formulario com validacao.
8. Simule estado de usuario logado em nivel introdutorio.
9. Prepare a aplicacao para deploy.

## O Que Revisar Antes de Avancar

- React, componentes, props, estado e hooks.
- Rotas, formularios, validacao e chamadas de API.
- HTTP, cache, request, response e codigos de status.
- TypeScript, tipos em funcoes, objetos e dados de API.
- Variaveis de ambiente, scripts e build.
- Diferenca entre frontend, backend e backend-for-frontend.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Next.js e Aplicacoes Fullstack no Frontend de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina Next.js com App Router, rotas, layouts, Server Components, Client Components, renderizacao, loading, erro, Suspense, formularios, APIs, validacao, autenticacao introdutoria, animacoes e deploy.
- Objetivo do modulo: Quero conseguir criar uma aplicacao Next.js pequena, organizada e preparada para evoluir para banco de dados, backend e autenticacao profunda.
- Pre-requisitos: fundamentos da Web, React, TypeScript, chamadas de API, formularios, validacao, terminal, pacotes e variaveis de ambiente.

Os assuntos estudados foram:
- Next.js
- Rotas no App Router
- Layouts
- Estrategias de renderizacao
- Server Components
- Client Components
- Composicao entre Server e Client Components
- Loading states e streaming
- Error boundaries
- Suspense
- Chamadas de API e busca de dados
- Route Handlers
- Formularios
- Tipos e validacao
- Autenticacao no contexto frontend
- Animacoes
- Deploy

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos em Next.js e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicacao em projetos reais;
5. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Documentacao oficial do Next.js.
- Documentacao oficial do React.
- Documentacao da MDN sobre HTTP, formularios e APIs.
- Documentacao da plataforma de deploy escolhida.

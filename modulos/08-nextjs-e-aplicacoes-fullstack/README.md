# Next.js e Aplicações Fullstack no Frontend

Este módulo apresenta o Next.js como ponte entre frontend moderno, renderização no servidor, backend-for-frontend e deploy de aplicações React.

O objetivo não é tratar Next.js como magia nem como substituto de fundamentos. A ideia é entender quais problemas ele resolve: rotas por arquivos, layouts persistentes, componentes no servidor, componentes no cliente, busca de dados, formulários, APIs internas, tratamento de carregamento e erro, autenticação em nível introdutório e publicação da aplicação.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o papel do Next.js em uma aplicação React moderna;
- criar rotas e layouts usando o App Router;
- diferenciar Server Components e Client Components;
- escolher estratégias básicas de renderização;
- representar loading, erro e suspense em fluxos reais;
- buscar dados e criar endpoints simples com Route Handlers;
- construir formulários com tipos e validação;
- entender autenticação no contexto de UI e sessão;
- preparar uma aplicação Next.js para deploy.

## Por Que Este Módulo Existe

No módulo anterior, você estudou React, componentes, estado, rotas, formulários, chamadas de API, testes e performance no frontend. Isso é suficiente para criar SPAs, mas muitas aplicações reais precisam também de renderização no servidor, melhor carregamento inicial, rotas mais integradas, busca de dados perto da tela e pequenos endpoints para atender o frontend.

Next.js aparece nessa transição. Ele continua usando React, mas adiciona convenções de projeto e recursos fullstack. Este módulo prepara o caminho para bancos de dados, backend com Node.js, autenticação profunda, segurança, observabilidade e deploy mais avançado.

## Pré-requisitos

- Entender HTTP, cliente, servidor, request, response e estado.
- Saber usar HTML, CSS, formulários, responsividade e acessibilidade em nível prático.
- Saber escrever JavaScript moderno e TypeScript.
- Entender promises, `async/await`, módulos e tratamento de erros.
- Entender React, componentes, renderização, hooks, estado, rotas e chamadas de API.
- Saber usar terminal, gerenciadores de pacote, scripts e variáveis de ambiente.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 08.00 | Next.js e Aplicações Fullstack no Frontend | Guarda-chuva | Rascunho |
| 08.01 | [Next.js](08.01-nextjs.md) | Específica ampla | Rascunho |
| 08.02 | [Rotas no App Router](08.02-rotas-no-app-router.md) | Específica | Rascunho |
| 08.03 | [Layouts](08.03-layouts.md) | Específica | Rascunho |
| 08.04 | [Estratégias de renderização](08.04-estrategias-de-renderizacao.md) | Guarda-chuva curta | Rascunho |
| 08.05 | [Server Components](08.05-server-components.md) | Específica | Rascunho |
| 08.06 | [Client Components](08.06-client-components.md) | Específica | Rascunho |
| 08.07 | [Composição entre Server e Client Components](08.07-composicao-entre-server-e-client-components.md) | Específica prática | Rascunho |
| 08.08 | [Loading states e streaming](08.08-loading-states-e-streaming.md) | Específica | Rascunho |
| 08.09 | [Error boundaries](08.09-error-boundaries.md) | Específica | Rascunho |
| 08.10 | [Suspense no contexto do Next.js](08.10-suspense-no-contexto-do-nextjs.md) | Específica conceitual | Rascunho |
| 08.11 | [Chamadas de API e busca de dados](08.11-chamadas-de-api-e-busca-de-dados.md) | Específica prática | Rascunho |
| 08.12 | [Route Handlers e APIs no Next.js](08.12-route-handlers-e-apis-no-nextjs.md) | Específica prática | Rascunho |
| 08.13 | [Formulários em Next.js](08.13-formularios-em-nextjs.md) | Específica | Rascunho |
| 08.14 | [Tipos e validação](08.14-tipos-e-validacao.md) | Específica | Rascunho |
| 08.15 | [Autenticação no contexto frontend](08.15-autenticacao-no-contexto-frontend.md) | Específica introdutória | Rascunho |
| 08.16 | [Animações em aplicações Next.js](08.16-animacoes-em-aplicacoes-nextjs.md) | Específica | Rascunho |
| 08.17 | [Deploy de aplicações Next.js](08.17-deploy-de-aplicacoes-nextjs.md) | Específica prática | Rascunho |
| 08.18 | [Projeto prático: aplicação fullstack com Next.js](08.18-projeto-pratico-aplicacao-fullstack-com-nextjs.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Construa uma pequena aplicação de painel de estudos com Next.js e TypeScript:

1. Crie rotas para lista, detalhes e cadastro.
2. Use um layout principal com navegação.
3. Busque dados em Server Components.
4. Use Client Components apenas onde houver interatividade.
5. Mostre estados de loading e erro.
6. Crie um Route Handler simples.
7. Construa um formulário com validação.
8. Simule estado de usuário logado em nível introdutório.
9. Prepare a aplicação para deploy.

## O Que Revisar Antes de Avançar

- React, componentes, props, estado e hooks.
- Rotas, formulários, validação e chamadas de API.
- HTTP, cache, request, response e códigos de status.
- TypeScript, tipos em funções, objetos e dados de API.
- Variáveis de ambiente, scripts e build.
- Diferença entre frontend, backend e backend-for-frontend.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Next.js e Aplicações Fullstack no Frontend de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina Next.js com App Router, rotas, layouts, Server Components, Client Components, renderização, loading, erro, Suspense, formulários, APIs, validação, autenticação introdutória, animações e deploy.
- Objetivo do módulo: Quero conseguir criar uma aplicação Next.js pequena, organizada e preparada para evoluir para banco de dados, backend e autenticação profunda.
- Pré-requisitos: fundamentos da Web, React, TypeScript, chamadas de API, formulários, validação, terminal, pacotes e variáveis de ambiente.

Os assuntos estudados foram:
- Next.js
- Rotas no App Router
- Layouts
- Estratégias de renderização
- Server Components
- Client Components
- Composição entre Server e Client Components
- Loading states e streaming
- Error boundaries
- Suspense
- Chamadas de API e busca de dados
- Route Handlers
- Formulários
- Tipos e validação
- Autenticação no contexto frontend
- Animações
- Deploy

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em Next.js e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do Next.js.
- Documentação oficial do React.
- Documentação da MDN sobre HTTP, formulários e APIs.
- Documentação da plataforma de deploy escolhida.

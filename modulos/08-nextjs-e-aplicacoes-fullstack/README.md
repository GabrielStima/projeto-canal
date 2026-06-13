<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Next.js e Aplicações Fullstack no Frontend

</div>

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
| 08.00 | [Next.js e Aplicações Fullstack](08.00-nextjs-e-aplicacoes-fullstack.md) | Guarda-chuva | Rascunho |
| 08.01 | [Next.js](08.01-nextjs.md) | Específica ampla | Rascunho |
| 08.02 | [Configurando o Ambiente Next.js](08.02-configurando-o-ambiente-nextjs.md) | Específica prática | Rascunho |
| 08.03 | [Rotas no App Router](08.03-rotas-no-app-router.md) | Específica | Rascunho |
| 08.04 | [Layouts](08.04-layouts.md) | Específica | Rascunho |
| 08.05 | [Estratégias de renderização](08.05-estrategias-de-renderizacao.md) | Guarda-chuva curta | Rascunho |
| 08.06 | [Server Components](08.06-server-components.md) | Específica | Rascunho |
| 08.07 | [Client Components](08.07-client-components.md) | Específica | Rascunho |
| 08.08 | [Composição entre Server e Client Components](08.08-composicao-entre-server-e-client-components.md) | Específica prática | Rascunho |
| 08.09 | [Loading states e streaming](08.09-loading-states-e-streaming.md) | Específica | Rascunho |
| 08.10 | [Error boundaries](08.10-error-boundaries.md) | Específica | Rascunho |
| 08.11 | [Suspense no contexto do Next.js](08.11-suspense-no-contexto-do-nextjs.md) | Específica conceitual | Rascunho |
| 08.12 | [Chamadas de API e busca de dados](08.12-chamadas-de-api-e-busca-de-dados.md) | Específica prática | Rascunho |
| 08.13 | [Route Handlers e APIs no Next.js](08.13-route-handlers-e-apis-no-nextjs.md) | Específica prática | Rascunho |
| 08.14 | [Formulários em Next.js](08.14-formularios-em-nextjs.md) | Específica | Rascunho |
| 08.15 | [Tipos e validação](08.15-tipos-e-validacao.md) | Específica | Rascunho |
| 08.16 | [Autenticação no contexto frontend](08.16-autenticacao-no-contexto-frontend.md) | Específica introdutória | Rascunho |
| 08.17 | [Animações em aplicações Next.js](08.17-animacoes-em-aplicacoes-nextjs.md) | Específica | Rascunho |
| 08.18 | [Deploy de aplicações Next.js](08.18-deploy-de-aplicacoes-nextjs.md) | Específica prática | Rascunho |
| 08.19 | [Projeto prático: aplicação fullstack com Next.js](08.19-projeto-pratico-aplicacao-fullstack-com-nextjs.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em 4 blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Fundamentos do Next.js** · aulas [08.00–08.04]
Introdução ao Next.js, configuração do ambiente, rotas no App Router e layouts.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Renderização e Composição** · aulas [08.05–08.11]
Estratégias de renderização, Server Components, Client Components, composição, loading, erro e Suspense.
Pré-requisito: Bloco A.

**Bloco C — Dados, APIs e Formulários** · aulas [08.12–08.15]
Busca de dados, Route Handlers, formulários, tipos e validação.
Pré-requisito: Bloco B.

**Bloco D — Autenticação, Cuidados e Entrega** · aulas [08.16–08.19]
Autenticação no contexto frontend, animações, deploy e projeto prático integrador.
Pré-requisito: Bloco C.

> Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

Use nomes simples e previsíveis dentro da pasta `exercicios/`:

- [Exercício 01 — Configuração do portal](exercicios/01-configuracao-do-portal.md)
- [Exercício 02 — Rotas e layouts](exercicios/02-rotas-e-layouts.md)
- [Exercício 03 — Server Components e dados](exercicios/03-server-components-e-dados.md)
- [Exercício 04 — Client Components e interatividade](exercicios/04-client-components-e-interatividade.md)
- [Exercício 05 — Route Handlers](exercicios/05-route-handlers.md)
- [Exercício 06 — Formulários e validação](exercicios/06-formularios-e-validacao.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

Cada exercício deve ser ligado à aula que ensina o conhecimento necessário. A atividade final deve combinar habilidades já praticadas, sem introduzir uma dificuldade nova.

Cada arquivo termina com `## Corrija Sua Atividade Com IA` e um prompt copiável que:

- explica o cenário e a tarefa sem depender de arquivos externos;
- apresenta critérios específicos de correção;
- contém o marcador `[COLE SUA RESPOSTA AQUI]`;
- pede acertos, imprecisões e dicas antes de qualquer resposta completa.

Esse prompt pode reproduzir o contexto usado no exercício. Ele não substitui nem altera o `Prompt Para Estudar Com IA` das aulas.

## Projeto ou Prática do Módulo

Construa o **Portal do Tutor do PetCare OS** com Next.js e TypeScript:

1. Crie rotas para dashboard, lista de pets, detalhes, cadastro e orçamentos.
2. Use um layout principal com navegação persistente na área `/tutor`.
3. Busque dados em Server Components.
4. Use Client Components apenas onde houver interatividade (aprovação de orçamento, filtros).
5. Mostre estados de loading e erro com `loading.tsx` e `error.tsx`.
6. Crie Route Handlers simples para cadastro de pet e aprovação de orçamento.
7. Construa um formulário de cadastro de pet com validação.
8. Simule estado de usuário logado em nível introdutório.
9. Prepare a aplicação para deploy.

## O Que Entra e O Que Sai Deste Módulo

**O que entra do módulo anterior:**

- Aplicação React do Portal do Tutor construída no módulo 07, com componentes (`PetCard`, `StatusBadge`, `PetList`), rotas, chamadas de API, formulário e testes.
- Regras e tipos das entidades do PetCare OS modelados nos módulos 03 e 04.
- Visão de produto e jornadas definidas no módulo 06.
- Repositório padronizado com scripts, lint e format do módulo 05.

**O que sai deste módulo:**

- Um projeto Next.js chamado `petcare-portal` com App Router.
- Estrutura de rotas e layout da área `/tutor`.
- Server Components para listagem e detalhes de pets.
- Client Components para interatividade pontual.
- Route Handlers `/api/pets` e `/api/orcamentos/[id]`.
- Formulário de cadastro de pet com validação.
- Aplicação preparada para build e deploy.

**Onde isso será retomado:**

- No módulo 09 — Bancos de Dados, os Route Handlers serão conectados a um banco relacional. As rotas, componentes e contratos de API criados aqui serão preservados.
- No módulo 12 — Autenticação, Autorização e Segurança, a sessão simulada será substituída por autenticação real.

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

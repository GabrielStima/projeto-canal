# Frontend Moderno

Este modulo apresenta a transicao entre paginas feitas com HTML, CSS e JavaScript solto e aplicacoes frontend modernas baseadas em componentes, estado, rotas, chamadas de API, formularios, validacao, testes e performance.

O foco principal sera React, mas o objetivo nao e decorar uma biblioteca. A ideia e entender o modelo mental por tras do frontend moderno: interfaces quebradas em partes menores, dados controlando a tela, navegacao no cliente, comunicacao com APIs e cuidados para manter a aplicacao compreensivel conforme ela cresce.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar por que frameworks e bibliotecas frontend existem;
- criar interfaces com componentes React;
- entender renderizacao, props, estado e hooks em nivel pratico;
- organizar telas com rotas em uma SPA;
- buscar dados de APIs e representar carregamento, erro e sucesso;
- construir formularios controlados e validar entradas;
- escrever testes introdutorios para componentes e fluxos de UI;
- reconhecer gargalos comuns de performance no frontend;
- comparar React com Web Components em alto nivel;
- entender Module Federation e micro-frontends como temas avancados introdutorios.

## Por Que Este Modulo Existe

Nos modulos anteriores, voce aprendeu a base da Web, JavaScript, TypeScript e ferramentas de desenvolvimento. Isso permite construir paginas e pequenos projetos, mas aplicacoes reais costumam ter mais telas, mais estados, mais interacoes e mais pessoas mexendo no mesmo codigo.

Frontend moderno aparece para organizar essa complexidade. Componentes ajudam a dividir interface. Estado ajuda a conectar dados e tela. Rotas transformam uma pagina unica em uma aplicacao navegavel. Chamadas de API conectam a interface ao mundo externo. Testes e performance ajudam a manter qualidade quando o projeto cresce.

Este modulo prepara o caminho para Next.js e aplicacoes fullstack no frontend, sem antecipar os assuntos de renderizacao no servidor que serao aprofundados no modulo seguinte.

## Pre-requisitos

- Entender HTML, semantica, formularios, CSS, layout e responsividade.
- Entender JavaScript no browser, DOM, eventos e acessibilidade em nivel introdutorio.
- Saber escrever JavaScript moderno e TypeScript basico.
- Entender funcoes, modulos, objetos, arrays, promises e `async/await`.
- Saber usar terminal, gerenciadores de pacote, scripts e bundlers em nivel inicial.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 06.00 | Frontend Moderno | Guarda-chuva | Rascunho |
| 06.01 | [Frameworks e libs frontend](06.01-frameworks-e-libs-frontend.md) | Guarda-chuva curta | Rascunho |
| 06.02 | [React](06.02-react.md) | Especifica ampla | Rascunho |
| 06.03 | [Componentes](06.03-componentes.md) | Especifica | Rascunho |
| 06.04 | [Renderizacao](06.04-renderizacao.md) | Especifica conceitual | Rascunho |
| 06.05 | [Hooks](06.05-hooks.md) | Especifica | Rascunho |
| 06.06 | [Gerenciamento de estado](06.06-gerenciamento-de-estado.md) | Especifica ampla | Rascunho |
| 06.07 | [Rotas](06.07-rotas.md) | Especifica | Rascunho |
| 06.08 | [SPA vs PWA](06.08-spa-vs-pwa.md) | Especifica conceitual | Rascunho |
| 06.09 | [Chamadas de API](06.09-chamadas-de-api.md) | Especifica pratica | Rascunho |
| 06.10 | [Formularios no frontend moderno](06.10-formularios-no-frontend-moderno.md) | Especifica | Rascunho |
| 06.11 | [Validacao](06.11-validacao.md) | Especifica | Rascunho |
| 06.12 | [Testes em frontend](06.12-testes-em-frontend.md) | Especifica ampla | Rascunho |
| 06.13 | [Performance no frontend](06.13-performance-no-frontend.md) | Especifica ampla | Rascunho |
| 06.14 | [Web Components](06.14-web-components.md) | Especifica comparativa | Rascunho |
| 06.15 | [Module Federation](06.15-module-federation.md) | Especifica avancada introdutoria | Rascunho |
| 06.16 | [Micro-frontends](06.16-micro-frontends.md) | Guarda-chuva curta | Rascunho |
| 06.17 | [Projeto pratico: aplicacao frontend moderna](06.17-projeto-pratico-aplicacao-frontend-moderna.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Construa uma pequena aplicacao de catalogo com React e TypeScript:

1. Separe a interface em componentes.
2. Mostre uma lista de itens com filtros simples.
3. Crie rotas para listagem, detalhes e formulario.
4. Busque dados de uma API simulada ou publica simples.
5. Mostre estados de carregamento, erro e sucesso.
6. Crie um formulario controlado.
7. Valide campos obrigatorios e mensagens de erro.
8. Escreva testes para componentes e fluxos principais.
9. Revise acessibilidade e performance basica.

## O Que Revisar Antes de Avancar

- HTML, formularios, CSS e responsividade.
- DOM, eventos e acessibilidade.
- JavaScript moderno, TypeScript, modulos e funcoes.
- Promises, `async/await` e tratamento de erros.
- Gerenciadores de pacote, scripts e bundlers.
- Componentes, props, estado, hooks, rotas e chamadas de API.
- Formularios, validacao, testes e performance no frontend.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Frontend Moderno de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina a construir interfaces modernas com React, componentes, estado, rotas, APIs, formularios, validacao, testes e performance.
- Objetivo do modulo: Quero conseguir criar uma aplicacao frontend organizada, interativa, testavel e preparada para evoluir para Next.js.
- Pre-requisitos: fundamentos da Web, HTML, CSS, JavaScript no browser, TypeScript, assincronismo, modulos, terminal, gerenciadores de pacote e bundlers.

Os assuntos estudados foram:
- Frameworks e libs frontend
- React
- Componentes
- Renderizacao
- Hooks
- Gerenciamento de estado
- Rotas
- SPA vs PWA
- Chamadas de API
- Formularios
- Validacao
- Testes em frontend
- Performance no frontend
- Web Components
- Module Federation
- Micro-frontends

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos em React e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicacao em projetos reais;
5. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Documentacao oficial do React.
- Documentacao oficial do React Router.
- Documentacao da MDN sobre Web Components.
- Documentacao sobre Module Federation.
- Documentacao da MDN sobre Web APIs, acessibilidade e performance.

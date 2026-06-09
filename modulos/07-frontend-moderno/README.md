<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Frontend Moderno

</div>

Este módulo apresenta a transição entre páginas feitas com HTML, CSS e JavaScript solto e aplicações frontend modernas baseadas em componentes, estado, rotas, chamadas de API, formulários, validação, testes e performance.

O foco principal será React, mas o objetivo não é decorar uma biblioteca. A ideia é entender o modelo mental por trás do frontend moderno: interfaces quebradas em partes menores, dados controlando a tela, navegação no cliente, comunicação com APIs e cuidados para manter a aplicação compreensível conforme ela cresce.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar por que frameworks e bibliotecas frontend existem;
- criar interfaces com componentes React;
- entender renderização, props, estado e hooks em nível prático;
- organizar telas com rotas em uma SPA;
- buscar dados de APIs e representar carregamento, erro e sucesso;
- construir formulários controlados e validar entradas;
- escrever testes introdutórios para componentes e fluxos de UI;
- reconhecer gargalos comuns de performance no frontend;
- comparar React com Web Components em alto nível;
- entender Module Federation e micro-frontends como temas avançados introdutórios.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a base da Web, JavaScript, TypeScript e ferramentas de desenvolvimento. Isso permite construir páginas e pequenos projetos, mas aplicações reais costumam ter mais telas, mais estados, mais interações e mais pessoas mexendo no mesmo código.

Frontend moderno aparece para organizar essa complexidade. Componentes ajudam a dividir interface. Estado ajuda a conectar dados e tela. Rotas transformam uma página única em uma aplicação navegável. Chamadas de API conectam a interface ao mundo externo. Testes e performance ajudam a manter qualidade quando o projeto cresce.

Este módulo prepara o caminho para Next.js e aplicações fullstack no frontend, sem antecipar os assuntos de renderização no servidor que serão aprofundados no módulo seguinte.

## Pré-requisitos

- Entender HTML, semântica, formulários, CSS, layout e responsividade.
- Entender JavaScript no browser, DOM, eventos e acessibilidade em nível introdutório.
- Saber escrever JavaScript moderno e TypeScript básico.
- Entender funções, módulos, objetos, arrays, promises e `async/await`.
- Saber usar terminal, gerenciadores de pacote, scripts e bundlers em nível inicial.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 07.00 | Frontend Moderno | Guarda-chuva | Rascunho |
| 07.01 | [Frameworks e libs frontend](07.01-frameworks-e-libs-frontend.md) | Guarda-chuva curta | Rascunho |
| 07.02 | [React](07.02-react.md) | Específica ampla | Rascunho |
| 07.03 | [Componentes](07.03-componentes.md) | Específica | Rascunho |
| 07.04 | [Renderização](07.04-renderizacao.md) | Específica conceitual | Rascunho |
| 07.05 | [Hooks](07.05-hooks.md) | Específica | Rascunho |
| 07.06 | [Gerenciamento de estado](07.06-gerenciamento-de-estado.md) | Específica ampla | Rascunho |
| 07.07 | [Rotas](07.07-rotas.md) | Específica | Rascunho |
| 07.08 | [SPA vs PWA](07.08-spa-vs-pwa.md) | Específica conceitual | Rascunho |
| 07.09 | [Chamadas de API](07.09-chamadas-de-api.md) | Específica prática | Rascunho |
| 07.10 | [Formulários no frontend moderno](07.10-formularios-no-frontend-moderno.md) | Específica | Rascunho |
| 07.11 | [Validação](07.11-validacao.md) | Específica | Rascunho |
| 07.12 | [Testes em frontend](07.12-testes-em-frontend.md) | Específica ampla | Rascunho |
| 07.13 | [Performance no frontend](07.13-performance-no-frontend.md) | Específica ampla | Rascunho |
| 07.14 | [Web Components](07.14-web-components.md) | Específica comparativa | Rascunho |
| 07.15 | [Module Federation](07.15-module-federation.md) | Específica avançada introdutória | Rascunho |
| 07.16 | [Micro-frontends](07.16-micro-frontends.md) | Guarda-chuva curta | Rascunho |
| 07.17 | [Projeto prático: aplicação frontend moderna](07.17-projeto-pratico-aplicacao-frontend-moderna.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Construa uma pequena aplicação de catálogo com React e TypeScript:

1. Separe a interface em componentes.
2. Mostre uma lista de itens com filtros simples.
3. Crie rotas para listagem, detalhes e formulário.
4. Busque dados de uma API simulada ou pública simples.
5. Mostre estados de carregamento, erro e sucesso.
6. Crie um formulário controlado.
7. Valide campos obrigatórios e mensagens de erro.
8. Escreva testes para componentes e fluxos principais.
9. Revise acessibilidade e performance básica.

## O Que Revisar Antes de Avançar

- HTML, formulários, CSS e responsividade.
- DOM, eventos e acessibilidade.
- JavaScript moderno, TypeScript, módulos e funções.
- Promises, `async/await` e tratamento de erros.
- Gerenciadores de pacote, scripts e bundlers.
- Componentes, props, estado, hooks, rotas e chamadas de API.
- Formulários, validação, testes e performance no frontend.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Frontend Moderno de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina a construir interfaces modernas com React, componentes, estado, rotas, APIs, formulários, validação, testes e performance.
- Objetivo do módulo: Quero conseguir criar uma aplicação frontend organizada, interativa, testável e preparada para evoluir para Next.js.
- Pré-requisitos: fundamentos da Web, HTML, CSS, JavaScript no browser, TypeScript, assincronismo, módulos, terminal, gerenciadores de pacote e bundlers.

Os assuntos estudados foram:
- Frameworks e libs frontend
- React
- Componentes
- Renderização
- Hooks
- Gerenciamento de estado
- Rotas
- SPA vs PWA
- Chamadas de API
- Formulários
- Validação
- Testes em frontend
- Performance no frontend
- Web Components
- Module Federation
- Micro-frontends

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em React e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do React.
- Documentação oficial do React Router.
- Documentação da MDN sobre Web Components.
- Documentação sobre Module Federation.
- Documentação da MDN sobre Web APIs, acessibilidade e performance.

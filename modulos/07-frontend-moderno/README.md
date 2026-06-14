# Frontend Moderno

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
| 07.00 | [Frontend Moderno](07.00-frontend-moderno.md) | Guarda-chuva | Auditada |
| 07.01 | [Frameworks e libs frontend](07.01-frameworks-e-libs-frontend.md) | Guarda-chuva curta | Auditada |
| 07.02 | [React](07.02-react.md) | Específica ampla | Auditada |
| 07.03 | [Componentes](07.03-componentes.md) | Específica | Auditada |
| 07.04 | [Renderização](07.04-renderizacao.md) | Específica conceitual | Auditada |
| 07.05 | [Hooks](07.05-hooks.md) | Específica | Auditada |
| 07.06 | [Gerenciamento de estado](07.06-gerenciamento-de-estado.md) | Específica ampla | Auditada |
| 07.07 | [Rotas](07.07-rotas.md) | Específica | Auditada |
| 07.08 | [SPA vs PWA](07.08-spa-vs-pwa.md) | Específica conceitual | Auditada |
| 07.09 | [Chamadas de API](07.09-chamadas-de-api.md) | Específica prática | Auditada |
| 07.10 | [Formulários no frontend moderno](07.10-formularios-no-frontend-moderno.md) | Específica | Auditada |
| 07.11 | [Validação](07.11-validacao.md) | Específica | Auditada |
| 07.12 | [Testes em frontend](07.12-testes-em-frontend.md) | Específica ampla | Auditada |
| 07.13 | [Performance no frontend](07.13-performance-no-frontend.md) | Específica ampla | Auditada |
| 07.14 | [Web Components](07.14-web-components.md) | Específica comparativa | Auditada |
| 07.15 | [Module Federation](07.15-module-federation.md) | Específica avançada introdutória | Auditada |
| 07.16 | [Micro-frontends](07.16-micro-frontends.md) | Guarda-chuva curta | Auditada |
| 07.17 | [Projeto prático: aplicação frontend moderna](07.17-projeto-pratico-aplicacao-frontend-moderna.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em 4 blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Fundamentos do Frontend Moderno** · aulas [07.00–07.05]
Introdução ao modelo mental de componentes, estado e renderização com React.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Navegação e Comunicação** · aulas [07.06–07.09]
Gerenciamento de estado, rotas, SPA vs PWA e chamadas de API.
Pré-requisito: Bloco A.

**Bloco C — Formulários, Qualidade e Cuidados** · aulas [07.10–07.13]
Formulários controlados, validação, testes e performance no frontend.
Pré-requisito: Bloco B.

**Bloco D — Tecnologias Avançadas e Integração** · aulas [07.14–07.17]
Web Components, Module Federation, micro-frontends e projeto prático integrador.
Pré-requisito: Bloco C.

> Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

Use nomes simples e previsíveis dentro da pasta `exercicios/`:

- [Exercício 01 — Componentes reutilizáveis](exercicios/01-componentes-reutilizaveis.md)
- [Exercício 02 — Estado e filtros](exercicios/02-estado-e-filtros.md)
- [Exercício 03 — Rotas e navegação](exercicios/03-rotas-e-navegacao.md)
- [Exercício 04 — Chamadas de API](exercicios/04-chamadas-de-api.md)
- [Exercício 05 — Formulários e validação](exercicios/05-formularios-e-validacao.md)
- [Exercício 06 — Testes de componentes](exercicios/06-testes-de-componentes.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

Cada exercício deve ser ligado à aula que ensina o conhecimento necessário. A atividade final deve combinar habilidades já praticadas, sem introduzir uma dificuldade nova.

Cada arquivo deve terminar com `## Corrija Sua Atividade Com IA` e um prompt copiável que:

- explique o cenário e a tarefa sem depender de arquivos externos;
- apresente critérios específicos de correção;
- contenha o marcador `[COLE SUA RESPOSTA AQUI]`;
- peça acertos, imprecisões e dicas antes de qualquer resposta completa.

Esse prompt pode reproduzir o contexto usado no exercício. Ele não substitui nem altera o `Prompt Para Estudar Com IA` das aulas.

## Projeto ou Prática do Módulo

Construa uma pequena aplicação React com TypeScript:

1. Separe a interface em componentes.
2. Mostre uma lista de itens com filtros simples.
3. Crie rotas para listagem, detalhes e formulário.
4. Busque dados de uma API simulada ou pública simples.
5. Mostre estados de carregamento, erro e sucesso.
6. Crie um formulário controlado.
7. Valide campos obrigatórios e mensagens de erro.
8. Escreva testes para componentes e fluxos principais.
9. Revise acessibilidade e performance básica.

## O Que Entra e O Que Sai Deste Módulo

**O que entra do módulo anterior:**

- Visão de produto e jornadas do PetCare OS definidas no módulo 06.
- Regras e tipos das entidades do domínio (pets, tutores, atendimentos, orçamentos) modelados nos módulos 03 e 04.
- Interfaces navegáveis e semânticas construídas no módulo 02 com HTML, CSS e JavaScript.
- Repositório padronizado com scripts, lint e format do módulo 05.

**O que sai deste módulo:**

- Uma aplicação React com TypeScript que simula o **Portal do Tutor** do PetCare OS.
- Componentes reutilizáveis (`PetCard`, `StatusBadge`, `PetList`) mantidos para reutilização.
- Configuração de rotas para dashboard, listagem, detalhes, cadastro e orçamento.
- Padrão de chamada de API com estados de carregamento, erro e sucesso.
- Formulário controlado de cadastro de pet com validação.
- Testes de comportamento para fluxos críticos da interface.

**Onde isso será retomado:**

- No módulo 08 — Next.js, esses componentes e telas serão migrados para o App Router, separando Server Components de Client Components e adicionando renderização no servidor.
- Os componentes visuais criados aqui (`PetCard`, `StatusBadge`, formulários) serão reutilizados, e a estrutura de rotas servirá de base para as rotas dinâmicas do Next.js.

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

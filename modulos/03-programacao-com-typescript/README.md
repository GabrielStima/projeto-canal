# Programacao com TypeScript

Este modulo aprofunda a programacao com JavaScript moderno e TypeScript. Depois de usar JavaScript no browser para pequenas interacoes, agora o foco passa a ser a linguagem em si: como representar dados, controlar fluxo, criar funcoes, lidar com erros, trabalhar com assincronismo e usar tipos para escrever codigo mais claro e seguro.

TypeScript nao substitui JavaScript. Ele adiciona uma camada de checagem estatica e ferramentas melhores sobre o JavaScript que continua rodando no browser, no Node.js e em outros ambientes.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- escrever codigo JavaScript moderno com clareza;
- explicar valores, variaveis, funcoes, objetos e estruturas de controle;
- entender assincronismo, event loop, Promises e `async/await`;
- diferenciar erro de sintaxe, erro de tipo e erro em runtime;
- usar TypeScript para modelar dados e funcoes;
- aproveitar inferencia sem anotar tipos em excesso;
- usar unions, narrowing, interfaces, type aliases, classes e modulos;
- reconhecer quando generics, utility types e tipos avancados ajudam;
- preparar codigo tipado para os modulos de ferramentas, frontend moderno, Next.js e backend.

## Por Que Este Modulo Existe

Nos modulos anteriores, JavaScript apareceu como ferramenta para dar comportamento a uma pagina. Isso e suficiente para criar interacoes pequenas, mas nao basta para sustentar projetos maiores.

Aplicacoes reais precisam de funcoes reutilizaveis, dados bem definidos, tratamento de erros, codigo assincrono e arquivos organizados. TypeScript entra para tornar essas relacoes mais explicitas: ele ajuda a perceber problemas durante o desenvolvimento, melhora autocomplete, documenta intencoes e reduz erros comuns antes de o codigo chegar ao usuario.

Este modulo cria a base de linguagem para todo o restante da formacao.

## Pre-requisitos

- Entender HTML, CSS, DOM e eventos em nivel introdutorio.
- Saber o papel do JavaScript no browser.
- Conseguir criar uma pequena interacao com JavaScript puro.
- Entender cliente, servidor, request e response em alto nivel.
- Nao e necessario conhecer Node.js, npm, bundlers ou frameworks.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 03.00 | Programacao com TypeScript | Guarda-chuva | Rascunho |
| 03.01 | [JavaScript moderno](03.01-javascript-moderno.md) | Especifica ampla | Rascunho |
| 03.02 | [Sintaxe, valores e variaveis](03.02-sintaxe-valores-e-variaveis.md) | Especifica | Rascunho |
| 03.03 | [Tipos primitivos e estruturas basicas](03.03-tipos-primitivos-e-estruturas-basicas.md) | Especifica | Rascunho |
| 03.04 | [Estruturas de controle](03.04-estruturas-de-controle.md) | Especifica | Rascunho |
| 03.05 | [Funcoes](03.05-funcoes.md) | Especifica | Rascunho |
| 03.06 | [Tratamento de erros](03.06-tratamento-de-erros.md) | Especifica | Rascunho |
| 03.07 | [Assincronismo em JavaScript](03.07-assincronismo-em-javascript.md) | Especifica ampla | Rascunho |
| 03.08 | [Event loop](03.08-event-loop.md) | Especifica conceitual | Rascunho |
| 03.09 | [Promises e async/await](03.09-promises-e-async-await.md) | Especifica | Rascunho |
| 03.10 | [TypeScript: o que e e como pensar em tipos](03.10-typescript-o-que-e-e-como-pensar-em-tipos.md) | Guarda-chuva curta | Rascunho |
| 03.11 | [Inferencia de tipos](03.11-inferencia-de-tipos.md) | Especifica | Rascunho |
| 03.12 | [Anotacoes de tipos e tipos em funcoes](03.12-anotacoes-de-tipos-e-tipos-em-funcoes.md) | Especifica | Rascunho |
| 03.13 | [Compatibilidade de tipos](03.13-compatibilidade-de-tipos.md) | Especifica | Rascunho |
| 03.14 | [Narrowing](03.14-narrowing.md) | Especifica | Rascunho |
| 03.15 | [Type aliases e interfaces](03.15-type-aliases-e-interfaces.md) | Especifica comparativa | Rascunho |
| 03.16 | [Modulos](03.16-modulos.md) | Especifica | Rascunho |
| 03.17 | [Classes e POO basica](03.17-classes-e-poo-basica.md) | Especifica ampla | Rascunho |
| 03.18 | [Generics](03.18-generics.md) | Especifica | Rascunho |
| 03.19 | [Utility types](03.19-utility-types.md) | Especifica | Rascunho |
| 03.20 | [Tipos avancados](03.20-tipos-avancados.md) | Especifica ampla | Rascunho |
| 03.21 | [Decorators](03.21-decorators.md) | Especifica introdutoria | Rascunho |
| 03.22 | [Projeto pratico: mini aplicacao tipada](03.22-projeto-pratico-mini-aplicacao-tipada.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Construa uma mini aplicacao de tarefas em TypeScript puro:

1. Modele uma tarefa com titulo, status, prioridade e data opcional.
2. Crie funcoes para adicionar, concluir, listar e filtrar tarefas.
3. Use tratamento de erros para entradas invalidas.
4. Simule uma operacao assincrona com `Promise` e `async/await`.
5. Organize o codigo em modulos.
6. Use types, interfaces, narrowing e utility types quando fizer sentido.
7. Evite usar framework: o foco e linguagem.

## O Que Revisar Antes de Avancar

- JavaScript moderno.
- Valores, variaveis, objetos, arrays e funcoes.
- Estruturas de controle.
- Tratamento de erros.
- Assincronismo, event loop, Promises e `async/await`.
- TypeScript como checagem estatica sobre JavaScript.
- Inferencia e anotacao de tipos.
- Unions, narrowing, aliases, interfaces, classes e modulos.
- Generics, utility types e tipos avancados em nivel introdutorio.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Programacao com TypeScript de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo aprofunda JavaScript moderno e TypeScript como base de linguagem para o restante da formacao.
- Objetivo do modulo: Ao final, devo conseguir escrever codigo JavaScript moderno, entender assincronismo e usar TypeScript para modelar dados, funcoes e modulos com seguranca.
- Pre-requisitos: fundamentos de Web, HTML, CSS, JavaScript no browser, DOM e eventos.

Os assuntos estudados foram:
- JavaScript moderno
- Sintaxe, valores e variaveis
- Tipos primitivos e estruturas basicas
- Estruturas de controle
- Funcoes
- Tratamento de erros
- Assincronismo em JavaScript
- Event loop
- Promises e async/await
- TypeScript e tipos
- Inferencia
- Anotacoes de tipos
- Compatibilidade de tipos
- Narrowing
- Type aliases e interfaces
- Modulos
- Classes e POO basica
- Generics
- Utility types
- Tipos avancados
- Decorators

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos em JavaScript e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicacao em projetos reais;
5. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Documentacao oficial do TypeScript.
- Documentacao da MDN sobre JavaScript.
- Documentacao da MDN sobre Promises e assincronismo.


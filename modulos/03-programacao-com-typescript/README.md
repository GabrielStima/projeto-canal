<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Programação com TypeScript

</div>

Este módulo aprofunda a programação com JavaScript moderno e TypeScript. Depois de usar JavaScript no browser para pequenas interações, agora o foco passa a ser a linguagem em si: como representar dados, controlar fluxo, criar funções, lidar com erros, trabalhar com assincronismo e usar tipos para escrever código mais claro e seguro.

TypeScript não substitui JavaScript. Ele adiciona uma camada de checagem estática e ferramentas melhores sobre o JavaScript que continua rodando no browser, no Node.js e em outros ambientes.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- escrever código JavaScript moderno com clareza;
- explicar valores, variáveis, funções, objetos e estruturas de controle;
- entender assincronismo, event loop, Promises e `async/await`;
- diferenciar erro de sintaxe, erro de tipo e erro em runtime;
- usar TypeScript para modelar dados e funções;
- aproveitar inferência sem anotar tipos em excesso;
- usar unions, narrowing, interfaces, type aliases, classes e módulos;
- reconhecer quando generics, utility types e tipos avançados ajudam;
- preparar código tipado para os módulos de ferramentas, frontend moderno, Next.js e backend.

## Por Que Este Módulo Existe

Nos módulos anteriores, JavaScript apareceu como ferramenta para dar comportamento a uma página. Isso é suficiente para criar interações pequenas, mas não basta para sustentar projetos maiores.

Aplicações reais precisam de funções reutilizáveis, dados bem definidos, tratamento de erros, código assíncrono e arquivos organizados. TypeScript entra para tornar essas relações mais explícitas: ele ajuda a perceber problemas durante o desenvolvimento, melhora autocomplete, documenta intenções e reduz erros comuns antes de o código chegar ao usuário.

Este módulo cria a base de linguagem para todo o restante da formação.

## Pré-requisitos

- Entender HTML, CSS, DOM e eventos em nível introdutório.
- Saber o papel do JavaScript no browser.
- Conseguir criar uma pequena interação com JavaScript puro.
- Entender cliente, servidor, request e response em alto nível.
- Não é necessário conhecer Node.js, npm, bundlers ou frameworks.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 03.00 | [Programação com TypeScript](03.00-programacao-com-typescript.md) | Guarda-chuva | Rascunho |
| 03.01 | [JavaScript moderno](03.01-javascript-moderno.md) | Específica ampla | Rascunho |
| 03.02 | [Sintaxe, valores e variáveis](03.02-sintaxe-valores-e-variaveis.md) | Específica | Rascunho |
| 03.03 | [Tipos primitivos e estruturas básicas](03.03-tipos-primitivos-e-estruturas-basicas.md) | Específica | Rascunho |
| 03.04 | [Estruturas de controle](03.04-estruturas-de-controle.md) | Específica | Rascunho |
| 03.05 | [Funções](03.05-funcoes.md) | Específica | Rascunho |
| 03.06 | [Tratamento de erros](03.06-tratamento-de-erros.md) | Específica | Rascunho |
| 03.07 | [Assincronismo em JavaScript](03.07-assincronismo-em-javascript.md) | Específica ampla | Rascunho |
| 03.08 | [Event loop](03.08-event-loop.md) | Específica conceitual | Rascunho |
| 03.09 | [Promises e async/await](03.09-promises-e-async-await.md) | Específica | Rascunho |
| 03.10 | [TypeScript: o que é e como pensar em tipos](03.10-typescript-o-que-e-e-como-pensar-em-tipos.md) | Guarda-chuva curta | Rascunho |
| 03.11 | [Inferência de tipos](03.11-inferencia-de-tipos.md) | Específica | Rascunho |
| 03.12 | [Anotações de tipos e tipos em funções](03.12-anotacoes-de-tipos-e-tipos-em-funcoes.md) | Específica | Rascunho |
| 03.13 | [Compatibilidade de tipos](03.13-compatibilidade-de-tipos.md) | Específica | Rascunho |
| 03.14 | [Narrowing](03.14-narrowing.md) | Específica | Rascunho |
| 03.15 | [Type aliases e interfaces](03.15-type-aliases-e-interfaces.md) | Específica comparativa | Rascunho |
| 03.16 | [Módulos](03.16-modulos.md) | Específica | Rascunho |
| 03.17 | [Classes e POO básica](03.17-classes-e-poo-basica.md) | Específica ampla | Rascunho |
| 03.18 | [Generics](03.18-generics.md) | Específica | Rascunho |
| 03.19 | [Utility types](03.19-utility-types.md) | Específica | Rascunho |
| 03.20 | [Tipos avançados](03.20-tipos-avancados.md) | Específica ampla | Rascunho |
| 03.21 | [Decorators](03.21-decorators.md) | Específica introdutória | Rascunho |
| 03.22 | [Projeto prático: mini aplicação tipada](03.22-projeto-pratico-mini-aplicacao-tipada.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em dois blocos progressivos. Cada bloco constrói sobre o anterior — não pule a sequência.

**Bloco A — JavaScript Moderno** · aulas 03.01–03.09
Sintaxe, valores, variáveis, tipos primitivos, estruturas de controle, funções, tratamento de erros, assincronismo, event loop, Promises e `async/await`.
Pré-requisito: nenhum (ponto de entrada do módulo).

> **Importante:** o Bloco B pressupõe que você já escreveu código JavaScript moderno com fluidez. Se ainda hesitar em criar funções, manipular arrays ou usar `async/await`, revise o Bloco A antes de avançar.

**Bloco B — TypeScript** · aulas 03.10–03.21
O que é TypeScript, inferência, anotações, compatibilidade de tipos, narrowing, aliases, interfaces, módulos, classes, generics, utility types, tipos avançados e decorators.
Pré-requisito: Bloco A consolidado.

> **✦ Projeto de síntese — aula 03.22:** ao final do módulo, complete o [Projeto Prático: mini aplicação tipada](03.22-projeto-pratico-mini-aplicacao-tipada.md). O projeto integra JavaScript moderno e TypeScript em um único programa: você precisará de assincronismo, tratamento de erros, funções, tipos, narrowing e organização em módulos.

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.

## Projeto ou Prática do Módulo

Construa uma mini aplicação de tarefas em TypeScript puro:

1. Modele uma tarefa com título, status, prioridade e data opcional.
2. Crie funções para adicionar, concluir, listar e filtrar tarefas.
3. Use tratamento de erros para entradas inválidas.
4. Simule uma operação assíncrona com `Promise` e `async/await`.
5. Organize o código em módulos.
6. Use types, interfaces, narrowing e utility types quando fizer sentido.
7. Evite usar framework: o foco é a linguagem.

## O Que Revisar Antes de Avançar

- JavaScript moderno.
- Valores, variáveis, objetos, arrays e funções.
- Estruturas de controle.
- Tratamento de erros.
- Assincronismo, event loop, Promises e `async/await`.
- TypeScript como checagem estática sobre JavaScript.
- Inferência e anotação de tipos.
- Unions, narrowing, aliases, interfaces, classes e módulos.
- Generics, utility types e tipos avançados em nível introdutório.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Programação com TypeScript de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo aprofunda JavaScript moderno e TypeScript como base de linguagem para o restante da formação.
- Objetivo do módulo: Ao final, devo conseguir escrever código JavaScript moderno, entender assincronismo e usar TypeScript para modelar dados, funções e módulos com segurança.
- Pré-requisitos: fundamentos de Web, HTML, CSS, JavaScript no browser, DOM e eventos.

Os assuntos estudados foram:
- JavaScript moderno
- Sintaxe, valores e variáveis
- Tipos primitivos e estruturas básicas
- Estruturas de controle
- Funções
- Tratamento de erros
- Assincronismo em JavaScript
- Event loop
- Promises e async/await
- TypeScript e tipos
- Inferência
- Anotações de tipos
- Compatibilidade de tipos
- Narrowing
- Type aliases e interfaces
- Módulos
- Classes e POO básica
- Generics
- Utility types
- Tipos avançados
- Decorators

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em JavaScript e TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do TypeScript.
- Documentação da MDN sobre JavaScript.
- Documentação da MDN sobre Promises e assincronismo.

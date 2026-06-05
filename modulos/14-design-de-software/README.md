# Design de Software

Este modulo marca a passagem de "codigo que funciona" para "codigo que continua simples de entender, testar e mudar". Ate aqui, voce ja estudou TypeScript, estruturas de dados, produto, frontend, backend, bancos de dados, APIs, seguranca, qualidade, testes, observabilidade e performance.

Agora o foco e o desenho interno do software: nomes, funcoes, objetos, responsabilidades, acoplamento, coesao, abstracoes, principios e padroes. Design de software nao e enfeitar codigo. E escolher formas de organizar comportamento para que o sistema aguente mudancas reais.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar o que torna um codigo simples, legivel e sustentavel;
- reconhecer sinais de design ruim antes que eles virem arquitetura acidental;
- aplicar principios de Clean Code com senso pratico;
- comparar paradigmas e entender quando POO ajuda ou atrapalha;
- usar encapsulamento, abstracoes e composicao para reduzir acoplamento;
- entender DRY, YAGNI, SOLID, Law of Demeter, Tell Don't Ask e outros principios;
- reconhecer padroes de design como vocabulario, nao como receita obrigatoria;
- refatorar uma pequena API buscando clareza, testabilidade e evolucao.

## Por Que Este Modulo Existe

Nos modulos anteriores, voce construiu partes importantes de uma aplicacao: telas, APIs, persistencia, autenticacao, seguranca, testes e sinais de operacao. Mas sistemas crescem por dentro. Uma regra simples vira varias regras. Um endpoint ganha excecoes. Um objeto passa a carregar responsabilidades demais. Um detalhe de framework entra em lugares onde deveria existir regra de negocio.

Design de software existe para lidar com esse crescimento sem depender apenas de disciplina individual. Ele ajuda a colocar cada decisao no lugar certo, criar limites menores, escolher abstracoes com criterio e evitar complexidade cedo demais.

## Pre-requisitos

- Saber escrever JavaScript moderno e TypeScript.
- Entender funcoes, objetos, modulos, classes, interfaces, generics e tratamento de erros.
- Ter estudado requisitos, criterios de aceite e mudancas de produto.
- Entender backend com Node.js, APIs, banco de dados, ORMs e failure modes.
- Ter estudado qualidade, testes unitarios, mocks, testes de integracao e testabilidade.
- Ter nocao de performance, logging e observabilidade em nivel introdutorio.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 14.00 | [Design de Software](14.00-design-de-software.md) | Guarda-chuva | Rascunho |
| 14.01 | [Codigo Simples, Legivel e Sustentavel](14.01-codigo-simples-legivel-e-sustentavel.md) | Guarda-chuva curta | Rascunho |
| 14.02 | [Principios do Clean Code](14.02-principios-do-clean-code.md) | Especifica ampla | Rascunho |
| 14.03 | [Nomes, Funcoes Pequenas e Clareza de Intencao](14.03-nomes-funcoes-pequenas-e-clareza-de-intencao.md) | Especifica pratica | Rascunho |
| 14.04 | [Paradigmas da Programacao](14.04-paradigmas-da-programacao.md) | Guarda-chuva | Rascunho |
| 14.05 | [Features de Paradigmas](14.05-features-de-paradigmas.md) | Especifica conceitual | Rascunho |
| 14.06 | [Programacao Orientada a Objetos no Design](14.06-programacao-orientada-a-objetos-no-design.md) | Guarda-chuva curta | Rascunho |
| 14.07 | [Principios Primarios de POO](14.07-principios-primarios-de-poo.md) | Especifica ampla | Rascunho |
| 14.08 | [Encapsulamento, Estado e Invariantes](14.08-encapsulamento-estado-e-invariantes.md) | Especifica pratica | Rascunho |
| 14.09 | [Acoplamento e Coesao no Codigo](14.09-acoplamento-e-coesao-no-codigo.md) | Especifica | Rascunho |
| 14.10 | [Model-Driven Design](14.10-model-driven-design.md) | Especifica ampla | Rascunho |
| 14.11 | [Principios de Design de Software](14.11-principios-de-design-de-software.md) | Guarda-chuva | Rascunho |
| 14.12 | [DRY](14.12-dry.md) | Especifica | Rascunho |
| 14.13 | [YAGNI](14.13-yagni.md) | Especifica | Rascunho |
| 14.14 | [SOLID](14.14-solid.md) | Guarda-chuva curta | Rascunho |
| 14.15 | [Single Responsibility Principle](14.15-single-responsibility-principle.md) | Especifica | Rascunho |
| 14.16 | [Open Closed Principle](14.16-open-closed-principle.md) | Especifica | Rascunho |
| 14.17 | [Liskov Substitution Principle](14.17-liskov-substitution-principle.md) | Especifica | Rascunho |
| 14.18 | [Interface Segregation Principle](14.18-interface-segregation-principle.md) | Especifica | Rascunho |
| 14.19 | [Dependency Inversion Principle](14.19-dependency-inversion-principle.md) | Especifica | Rascunho |
| 14.20 | [Program Against Abstractions](14.20-program-against-abstractions.md) | Especifica pratica | Rascunho |
| 14.21 | [Composition Over Inheritance](14.21-composition-over-inheritance.md) | Especifica pratica | Rascunho |
| 14.22 | [Encapsulate What Varies](14.22-encapsulate-what-varies.md) | Especifica pratica | Rascunho |
| 14.23 | [Tell, Don't Ask](14.23-tell-dont-ask.md) | Especifica | Rascunho |
| 14.24 | [Law of Demeter](14.24-law-of-demeter.md) | Especifica | Rascunho |
| 14.25 | [Principio de Hollywood](14.25-principio-de-hollywood.md) | Especifica | Rascunho |
| 14.26 | [Padroes de Design](14.26-padroes-de-design.md) | Guarda-chuva | Rascunho |
| 14.27 | [GoF: Padroes Criacionais, Estruturais e Comportamentais](14.27-gof-padroes-criacionais-estruturais-e-comportamentais.md) | Guarda-chuva curta | Rascunho |
| 14.28 | [PoSA e Padroes Alem do GoF](14.28-posa-e-padroes-alem-do-gof.md) | Especifica conceitual | Rascunho |
| 14.29 | [Projeto Pratico: Refatorando uma API para Melhor Design](14.29-projeto-pratico-refatorando-uma-api-para-melhor-design.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Refatore uma pequena API criada nos modulos anteriores:

1. Escolha um fluxo com regra de negocio real.
2. Identifique responsabilidades misturadas.
3. Melhore nomes e funcoes.
4. Separe regra, validacao, persistencia e apresentacao quando fizer sentido.
5. Reduza acoplamento com dependencias externas.
6. Use composicao e abstracoes pequenas.
7. Escreva ou ajuste testes para proteger a refatoracao.
8. Registre trade-offs e decisoes de design.

## O Que Revisar Antes de Avancar

- TypeScript, interfaces, classes, generics e modulos.
- Requisitos, criterios de aceite e mudancas de produto.
- Backend com Node.js, APIs, banco de dados, ORMs e failure modes.
- Testes unitarios, mocks, testes de integracao e testabilidade.
- Logging, performance e observabilidade em nivel introdutorio.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Design de Software de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina design de codigo, Clean Code, paradigmas, POO, model-driven design, principios de design, SOLID, composicao, abstracoes e padroes.
- Objetivo do modulo: Quero escrever codigo mais simples, legivel, testavel e sustentavel.
- Pre-requisitos: TypeScript, backend, APIs, bancos de dados, qualidade, testes e testabilidade.

Crie uma revisao guiada com perguntas conceituais, exercicios de refatoracao, perguntas de entrevista, exemplos em projetos reais e uma avaliacao final.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Materiais internos do proprio projeto.
- Livros e materiais conceituais sobre Clean Code, design orientado a objetos, refatoracao e padroes de design.
- Documentacao oficial do TypeScript quando a aula exigir exemplos especificos de linguagem.

<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Design de Software

</div>

Este módulo marca a passagem de "código que funciona" para "código que continua simples de entender, testar e mudar". Até aqui, você já estudou TypeScript, estruturas de dados, produto, frontend, backend, bancos de dados, APIs, segurança, qualidade, testes, observabilidade e performance.

Agora o foco é o desenho interno do software: nomes, funções, objetos, responsabilidades, acoplamento, coesão, abstrações, princípios e padrões. Design de software não é enfeitar código. É escolher formas de organizar comportamento para que o sistema aguente mudanças reais.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o que torna um código simples, legível e sustentável;
- reconhecer sinais de design ruim antes que eles virem arquitetura acidental;
- aplicar princípios de Clean Code com senso prático;
- comparar paradigmas e entender quando POO ajuda ou atrapalha;
- usar encapsulamento, abstrações e composição para reduzir acoplamento;
- entender DRY, YAGNI, SOLID, Law of Demeter, Tell Don't Ask e outros princípios;
- reconhecer padrões de design como vocabulário, não como receita obrigatória;
- refatorar uma pequena API buscando clareza, testabilidade e evolução.

## Por Que Este Módulo Existe

Nos módulos anteriores, você construiu partes importantes de uma aplicação: telas, APIs, persistência, autenticação, segurança, testes e sinais de operação. Mas sistemas crescem por dentro. Uma regra simples vira várias regras. Um endpoint ganha exceções. Um objeto passa a carregar responsabilidades demais. Um detalhe de framework entra em lugares onde deveria existir regra de negócio.

Design de software existe para lidar com esse crescimento sem depender apenas de disciplina individual. Ele ajuda a colocar cada decisão no lugar certo, criar limites menores, escolher abstrações com critério e evitar complexidade cedo demais.

## Pré-requisitos

- Saber escrever JavaScript moderno e TypeScript.
- Entender funções, objetos, módulos, classes, interfaces, generics e tratamento de erros.
- Ter estudado requisitos, critérios de aceite e mudanças de produto.
- Entender backend com Node.js, APIs, banco de dados, ORMs e failure modes.
- Ter estudado qualidade, testes unitários, mocks, testes de integração e testabilidade.
- Ter noção de performance, logging e observabilidade em nível introdutório.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 14.00 | [Design de Software](14.00-design-de-software.md) | Guarda-chuva | Rascunho |
| 14.01 | [Código Simples, Legível e Sustentável](14.01-codigo-simples-legivel-e-sustentavel.md) | Guarda-chuva curta | Rascunho |
| 14.02 | [Princípios do Clean Code](14.02-principios-do-clean-code.md) | Especifica ampla | Rascunho |
| 14.03 | [Nomes, Funções Pequenas e Clareza de Intenção](14.03-nomes-funcoes-pequenas-e-clareza-de-intencao.md) | Especifica pratica | Rascunho |
| 14.04 | [Paradigmas da Programação](14.04-paradigmas-da-programacao.md) | Guarda-chuva | Rascunho |
| 14.05 | [Features de Paradigmas](14.05-features-de-paradigmas.md) | Especifica conceitual | Rascunho |
| 14.06 | [Programação Orientada a Objetos no Design](14.06-programacao-orientada-a-objetos-no-design.md) | Guarda-chuva curta | Rascunho |
| 14.07 | [Princípios Primários de POO](14.07-principios-primarios-de-poo.md) | Especifica ampla | Rascunho |
| 14.08 | [Encapsulamento, Estado e Invariantes](14.08-encapsulamento-estado-e-invariantes.md) | Especifica pratica | Rascunho |
| 14.09 | [Acoplamento e Coesão no Código](14.09-acoplamento-e-coesao-no-codigo.md) | Especifica | Rascunho |
| 14.10 | [Model-Driven Design](14.10-model-driven-design.md) | Especifica ampla | Rascunho |
| 14.11 | [Princípios de Design de Software](14.11-principios-de-design-de-software.md) | Guarda-chuva | Rascunho |
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
| 14.25 | [Princípio de Hollywood](14.25-principio-de-hollywood.md) | Especifica | Rascunho |
| 14.26 | [Padrões de Design](14.26-padroes-de-design.md) | Guarda-chuva | Rascunho |
| 14.27 | [GoF: Padrões Criacionais, Estruturais e Comportamentais](14.27-gof-padroes-criacionais-estruturais-e-comportamentais.md) | Guarda-chuva curta | Rascunho |
| 14.28 | [POSA e Padrões Além do GoF](14.28-posa-e-padroes-alem-do-gof.md) | Especifica conceitual | Rascunho |
| 14.29 | [Projeto Prático: Refatorando uma API para Melhor Design](14.29-projeto-pratico-refatorando-uma-api-para-melhor-design.md) | Sintese pratica | Rascunho |

## Trilha de Estudo

Este módulo está organizado em quatro blocos progressivos. Cada bloco constrói sobre o anterior — não pule a sequência.

**Bloco A — Código Limpo e Legibilidade** · aulas 14.01–14.03
O que torna código difícil de manter, princípios do Clean Code e como melhorar nomes, funções e clareza de intenção.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Paradigmas e POO** · aulas 14.04–14.10
Paradigmas da programação, features de paradigmas, POO no design, princípios primários, encapsulamento, acoplamento e coesão, e model-driven design.
Pré-requisito: Bloco A.

**Bloco C — Princípios de Design** · aulas 14.11–14.25
Princípios de design de software: DRY, YAGNI, SOLID (cinco princípios individuais), abstrações, composição, encapsulamento do que varia, tell don't ask, Law of Demeter e Princípio de Hollywood.
Pré-requisito: Bloco B.

**Bloco D — Padrões de Design** · aulas 14.26–14.28
Padrões GoF (criacionais, estruturais e comportamentais) e padrões além do GoF.
Pré-requisito: Bloco C (padrões fazem mais sentido quando os princípios estão claros).

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.


## Projeto ou Prática do Módulo

Refatore uma pequena API criada nos módulos anteriores:

1. Escolha um fluxo com regra de negócio real.
2. Identifique responsabilidades misturadas.
3. Melhore nomes e funções.
4. Separe regra, validação, persistência e apresentação quando fizer sentido.
5. Reduza acoplamento com dependências externas.
6. Use composição e abstrações pequenas.
7. Escreva ou ajuste testes para proteger a refatoração.
8. Registre trade-offs e decisões de design.

## O Que Revisar Antes de Avançar

- TypeScript, interfaces, classes, generics e módulos.
- Requisitos, critérios de aceite e mudanças de produto.
- Backend com Node.js, APIs, banco de dados, ORMs e failure modes.
- Testes unitários, mocks, testes de integração e testabilidade.
- Logging, performance e observabilidade em nível introdutório.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Design de Software de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina design de código, Clean Code, paradigmas, POO, model-driven design, princípios de design, SOLID, composição, abstrações e padrões.
- Objetivo do módulo: Quero escrever código mais simples, legível, testável e sustentável.
- Pré-requisitos: TypeScript, backend, APIs, bancos de dados, qualidade, testes e testabilidade.

Crie uma revisão guiada com perguntas conceituais, exercícios de refatoração, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Livros e materiais conceituais sobre Clean Code, design orientado a objetos, refatoração e padrões de design.
- Documentação oficial do TypeScript quando a aula exigir exemplos específicos de linguagem.

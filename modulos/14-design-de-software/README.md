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
| 14.00 | [Design de Software: Código Simples e Sustentável](14.00-design-de-software-codigo-simples-e-sustentavel.md) | Guarda-chuva | Rascunho |
| 14.01 | [Clean Code: Nomes, Funções e Clareza de Intenção](14.01-clean-code-nomes-funcoes-e-clareza-de-intencao.md) | Específica prática | Rascunho |
| 14.02 | [Paradigmas e Recursos de Linguagem em TypeScript](14.02-paradigmas-e-recursos-de-linguagem-em-typescript.md) | Guarda-chuva curta | Rascunho |
| 14.03 | [POO no Design: Encapsulamento, Abstração e Polimorfismo](14.03-poo-no-design-encapsulamento-abstracao-e-polimorfismo.md) | Específica ampla | Rascunho |
| 14.04 | [Encapsulamento, Estado e Invariantes](14.04-encapsulamento-estado-e-invariantes.md) | Específica prática | Rascunho |
| 14.05 | [Acoplamento e Coesão no Código](14.05-acoplamento-e-coesao-no-codigo.md) | Específica | Rascunho |
| 14.06 | [Model-Driven Design](14.06-model-driven-design.md) | Específica ampla | Rascunho |
| 14.07 | [Princípios de Design e Decisões de Refatoração](14.07-principios-de-design-e-decisoes-de-refatoracao.md) | Guarda-chuva curta | Rascunho |
| 14.08 | [DRY, YAGNI e Abstrações Prematuras](14.08-dry-yagni-e-abstracoes-prematuras.md) | Específica | Rascunho |
| 14.09 | [SOLID](14.09-solid.md) | Guarda-chuva curta | Rascunho |
| 14.10 | [Single Responsibility Principle](14.10-single-responsibility-principle.md) | Específica | Rascunho |
| 14.11 | [Open Closed Principle](14.11-open-closed-principle.md) | Específica | Rascunho |
| 14.12 | [Liskov Substitution Principle](14.12-liskov-substitution-principle.md) | Específica | Rascunho |
| 14.13 | [Interface Segregation Principle](14.13-interface-segregation-principle.md) | Específica | Rascunho |
| 14.14 | [Dependency Inversion e Programação Contra Abstrações](14.14-dependency-inversion-e-programacao-contra-abstracoes.md) | Específica prática | Rascunho |
| 14.15 | [Desafio: Aplicando SOLID no PetCare OS](14.15-desafio-aplicando-solid-no-petcare-os.md) | Desafio intermediário | Rascunho |
| 14.16 | [Composition Over Inheritance](14.16-composition-over-inheritance.md) | Específica prática | Rascunho |
| 14.17 | [Encapsulate What Varies](14.17-encapsulate-what-varies.md) | Específica prática | Rascunho |
| 14.18 | [Tell, Don't Ask e Law of Demeter](14.18-tell-dont-ask-e-law-of-demeter.md) | Específica | Rascunho |
| 14.19 | [Princípio de Hollywood e Inversão de Controle](14.19-principio-de-hollywood-e-inversao-de-controle.md) | Específica | Rascunho |
| 14.20 | [Padrões de Design](14.20-padroes-de-design.md) | Guarda-chuva | Rascunho |
| 14.21 | [GoF: Padrões Criacionais, Estruturais e Comportamentais](14.21-gof-padroes-criacionais-estruturais-e-comportamentais.md) | Guarda-chuva curta | Rascunho |
| 14.22 | [POSA e Padrões Além do GoF](14.22-posa-e-padroes-alem-do-gof.md) | Específica conceitual | Rascunho |
| 14.23 | [Desafio: Escolhendo Padrões de Design](14.23-desafio-escolhendo-padroes-de-design.md) | Desafio intermediário | Rascunho |
| 14.24 | [Projeto Prático: Refatorando uma API para Melhor Design](14.24-projeto-pratico-refatorando-uma-api-para-melhor-design.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em quatro blocos progressivos. Cada bloco constrói sobre o anterior — não pule a sequência.

**Bloco A — Código Limpo e Legibilidade** · aulas 14.00–14.01
O que torna código difícil de manter e como melhorar nomes, funções, limites e clareza de intenção.
Pré-requisito: nenhum (ponto de entrada do módulo).

Ao concluir o bloco, faça o [Exercício 01 — Diagnóstico e Refatoração Segura](exercicios/01-diagnostico-e-refatoracao-segura.md).

**Bloco B — Paradigmas, POO e Modelagem** · aulas 14.02–14.06
Paradigmas e recursos da linguagem, POO no design, invariantes, acoplamento, coesão e model-driven design.
Pré-requisito: Bloco A.

Faça o [Exercício 02 — Modelagem e Invariantes](exercicios/02-modelagem-e-invariantes.md).

**Bloco C — Princípios de Design** · aulas 14.07–14.19
Decisões de refatoração, DRY, YAGNI, SOLID, abstrações, composição, encapsulamento do que varia, Tell Don't Ask, Law of Demeter e inversão de controle.
Pré-requisito: Bloco B.

Comece com o [Exercício 03 — Princípios e Decisões de Refatoração](exercicios/03-principios-e-decisoes.md). Depois de Dependency Inversion, faça o [Exercício 04 — SOLID e Dependências](exercicios/04-solid-e-dependencias.md).

> **Desafio de bloco — aula 14.15:** antes de avançar para composição e princípios relacionados, complete o [Desafio: Aplicando SOLID no PetCare OS](14.15-desafio-aplicando-solid-no-petcare-os.md). O desafio converte o que você leu sobre SOLID em diagnóstico e refatoração sobre código real.

Ao concluir composição, variação e Law of Demeter, faça o [Exercício 05 — Composição e Comportamento](exercicios/05-composicao-e-comportamento.md).

**Bloco D — Padrões de Design e Síntese** · aulas 14.20–14.24
Padrões GoF (criacionais, estruturais e comportamentais) e padrões além do GoF.
Pré-requisito: Bloco C (padrões fazem mais sentido quando os princípios estão claros).

> **Desafio de bloco — aula 14.23:** antes de ir para o projeto final, complete o [Desafio: Escolhendo Padrões de Design](14.23-desafio-escolhendo-padroes-de-design.md). O desafio apresenta três cenários reais do PetCare OS onde mais de um padrão funcionaria — você precisa escolher, implementar e justificar a rejeição das alternativas.

Depois, aplique esse raciocínio ao próprio código no [Exercício 06 — Escolha de Padrão e ADR](exercicios/06-escolha-de-padrao-e-adr.md) e finalize com a [Atividade Final do Módulo](exercicios/atividade-final-modulo.md).

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.



## Exercícios

- [Exercício 01 — Diagnóstico e Refatoração Segura](exercicios/01-diagnostico-e-refatoracao-segura.md)
- [Exercício 02 — Modelagem e Invariantes](exercicios/02-modelagem-e-invariantes.md)
- [Exercício 03 — Princípios e Decisões de Refatoração](exercicios/03-principios-e-decisoes.md)
- [Exercício 04 — SOLID e Dependências](exercicios/04-solid-e-dependencias.md)
- [Exercício 05 — Composição e Comportamento](exercicios/05-composicao-e-comportamento.md)
- [Exercício 06 — Escolha de Padrão e ADR](exercicios/06-escolha-de-padrao-e-adr.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você refatorará um fluxo existente do PetCare OS sem alterar o comportamento público:

1. Registre o comportamento com testes antes de mudar a estrutura.
2. Diagnostique responsabilidades, dependências, invariantes e pontos de variação.
3. Melhore nomes e limites usando o vocabulário do domínio.
4. Separe regra e infraestrutura quando essa divisão reduzir acoplamento ou facilitar testes.
5. Use abstração, composição ou padrão somente quando existir problema e variação reais.
6. Registre a decisão, as alternativas e os custos.

Não existe obrigação de criar uma arquitetura em camadas, um repositório ou uma classe para cada conceito. A menor refatoração que reduz o risco observado é preferível.

## O Que Entra e O Que Sai Deste Módulo

**O que entra dos módulos anteriores:**

- API funcional, testada e instrumentada;
- estratégia de testes, regressões e pipeline de CI;
- medições e sinais operacionais de fluxos críticos;
- código TypeScript com regras, controllers e acesso a infraestrutura.

**O que sai deste módulo:**

- diagnóstico de design de um fluxo real;
- testes de caracterização preservando comportamento;
- modelo com invariantes protegidas quando necessário;
- dependências explícitas e responsabilidades mais coesas;
- decisão sobre abstrações, composição e padrões;
- ADR curto registrando trade-offs;
- refatoração demonstrável sem alteração do contrato externo.

**Onde isso será retomado:**

- no módulo 15, os limites encontrados no código ajudarão a discutir fronteiras arquiteturais;
- módulos posteriores reutilizarão o fluxo refatorado sem assumir que todo o sistema precisa adotar o mesmo desenho;
- testes e sinais operacionais continuarão protegendo mudanças futuras.

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

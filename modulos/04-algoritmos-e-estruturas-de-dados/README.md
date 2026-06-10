<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Algoritmos e Estruturas de Dados

</div>

Este módulo desenvolve raciocínio computacional para resolver problemas com mais critério. A ideia não é decorar nomes de algoritmos, mas aprender a escolher representações de dados, comparar soluções e entender o custo de cada escolha.

Aqui, TypeScript aparece como ferramenta de expressão: vamos escrever exemplos pequenos, tipados e diretos, usando arrays, objetos, classes e funções para enxergar como as estruturas funcionam.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o que são estruturas de dados e por que elas existem;
- comparar soluções usando complexidade de tempo e espaço;
- calcular complexidade em exemplos simples;
- implementar e usar arrays, listas ligadas, pilhas, filas e tabelas hash;
- reconhecer quando usar busca linear, busca binária e algoritmos de ordenação;
- explicar a ideia de árvores, árvores binárias, árvores de busca binária e heaps;
- entender por que alguns algoritmos dependem de recursão, divisão e conquista ou propriedades estruturais;
- aplicar esses conceitos em pequenos problemas de código.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a escrever código com JavaScript e TypeScript. Agora o foco muda: em vez de perguntar apenas "como escrevo isso?", vamos perguntar "qual solução faz sentido para este problema?".

Essa mudança importa em quase todo projeto real. Listar itens, buscar registros, ordenar resultados, evitar duplicidade, montar histórico de navegação, processar filas de tarefas e representar hierarquias são problemas comuns. Algoritmos e estruturas de dados dão vocabulário para conversar sobre essas decisões.

Este módulo também prepara assuntos futuros como bancos de dados, performance, arquitetura, backend, filas, caches, índices e system design.

## Pré-requisitos

- Saber escrever funções, condicionais e repetições em JavaScript/TypeScript.
- Entender arrays, objetos e tipos primitivos.
- Conseguir ler exemplos com classes e interfaces em TypeScript.
- Entender módulos em nível introdutório.
- Ter praticado pequenos programas sem depender de framework.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 04.00 | [Algoritmos e Estruturas de Dados](04.00-algoritmos-e-estruturas-de-dados.md) | Guarda-chuva | Rascunho |
| 04.01 | [Estruturas de dados: dados, operações e escolhas](04.01-estruturas-de-dados-dados-operacoes-e-escolhas.md) | Guarda-chuva curta | Rascunho |
| 04.02 | [Arrays](04.02-arrays.md) | Específica | Rascunho |
| 04.03 | [Complexidade de algoritmos](04.03-complexidade-de-algoritmos.md) | Guarda-chuva conceitual | Rascunho |
| 04.04 | [Tempo vs espaço](04.04-tempo-vs-espaco.md) | Específica | Rascunho |
| 04.05 | [Como calcular complexidade](04.05-como-calcular-complexidade.md) | Específica prática | Rascunho |
| 04.06 | [Linked lists](04.06-linked-lists.md) | Específica | Rascunho |
| 04.07 | [Stacks](04.07-stacks.md) | Específica | Rascunho |
| 04.08 | [Queues](04.08-queues.md) | Específica | Rascunho |
| 04.09 | [Hash tables](04.09-hash-tables.md) | Específica | Rascunho |
| 04.10 | [Algoritmos de busca](04.10-algoritmos-de-busca.md) | Guarda-chuva curta | Rascunho |
| 04.11 | [Busca linear](04.11-busca-linear.md) | Específica | Rascunho |
| 04.12 | [Busca binária](04.12-busca-binaria.md) | Específica | Rascunho |
| 04.13 | [Algoritmos de ordenação](04.13-algoritmos-de-ordenacao.md) | Guarda-chuva | Rascunho |
| 04.14 | [Bubble Sort](04.14-bubble-sort.md) | Específica | Rascunho |
| 04.15 | [Selection Sort](04.15-selection-sort.md) | Específica | Rascunho |
| 04.16 | [Insertion Sort](04.16-insertion-sort.md) | Específica | Rascunho |
| 04.17 | [Recursão e divisão e conquista](04.17-recursao-e-divisao-e-conquista.md) | Aula de suporte | Rascunho |
| 04.18 | [Merge Sort](04.18-merge-sort.md) | Específica | Rascunho |
| 04.19 | [Quick Sort](04.19-quick-sort.md) | Específica | Rascunho |
| 04.20 | [Árvores](04.20-arvores.md) | Guarda-chuva | Rascunho |
| 04.21 | [Árvore binária](04.21-arvore-binaria.md) | Específica | Rascunho |
| 04.22 | [Árvore de busca binária](04.22-arvore-de-busca-binaria.md) | Específica | Rascunho |
| 04.23 | [Heaps](04.23-heaps.md) | Aula de suporte | Rascunho |
| 04.24 | [Heap Sort](04.24-heap-sort.md) | Específica | Rascunho |
| 04.25 | [Projeto prático: analisador de estruturas e algoritmos](04.25-projeto-pratico-analisador-de-estruturas-e-algoritmos.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em cinco blocos. Os blocos A e B podem ser estudados em paralelo, mas ambos devem ser concluídos antes de C. D depende de B. E depende de D.

**Bloco A — Estruturas de Dados** · aulas 04.01–04.09
O que são estruturas de dados, como arrays funcionam, e depois as estruturas lineares: linked lists, stacks, queues e hash tables.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Complexidade de Algoritmos** · aulas 04.03–04.05
Como medir e calcular a eficiência de um algoritmo em tempo e espaço. Ler após 04.01 para ter contexto, mas pode ser estudado em paralelo com as estruturas lineares.
Pré-requisito: 04.01 (fundamentos de estruturas de dados).

**Bloco C — Algoritmos de Busca** · aulas 04.10–04.12
Busca linear e busca binária com análise de complexidade. Requer entender arrays (Bloco A) e complexidade (Bloco B).
Pré-requisito: Blocos A e B.

**Bloco D — Algoritmos de Ordenação** · aulas 04.13–04.19
Comparação de algoritmos de ordenação, com recursão como aula de suporte antes de merge sort e quick sort.
Pré-requisito: Blocos A e B.

**Bloco E — Árvores e Heaps** · aulas 04.20–04.24
Estruturas hierárquicas: árvore binária, árvore de busca binária, heaps e heap sort.
Pré-requisito: Bloco A (estruturas de dados) e Bloco D (recursão e ordenação).

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.


## Projeto ou Prática do Módulo

Construa um pequeno analisador de estruturas e algoritmos em TypeScript:

1. Crie uma lista de números e objetos de exemplo.
2. Implemente busca linear e busca binária.
3. Implemente pelo menos três algoritmos de ordenação.
4. Modele pilha, fila, tabela hash simples e árvore de busca binária.
5. Registre o número de passos principais de cada operação.
6. Compare tempo, espaço e clareza de implementação.
7. Escreva uma conclusão curta explicando quando você usaria cada abordagem.

## O Que Revisar Antes de Avançar

- Arrays, objetos, funções e estruturas de controle.
- Classes, interfaces e generics em TypeScript.
- Complexidade de tempo e espaço.
- Operações de inserção, remoção, busca e percurso.
- Diferença entre estrutura de dados e algoritmo.
- Busca linear, busca binária e pré-condições.
- Ordenação por comparação.
- Recursão, divisão e conquista e árvores.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Algoritmos e Estruturas de Dados de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo desenvolve raciocínio computacional, estruturas de dados, complexidade, busca, ordenação e árvores.
- Objetivo do módulo: Quero conseguir escolher estruturas e algoritmos simples com base no problema, no custo e na clareza da solução.
- Pré-requisitos: JavaScript moderno, TypeScript, arrays, objetos, funções, classes, módulos e generics em nível introdutório.

Os assuntos estudados foram:
- Estruturas de dados
- Arrays
- Complexidade de algoritmos
- Tempo vs espaço
- Linked lists
- Stacks e queues
- Hash tables
- Algoritmos de busca
- Busca linear e busca binária
- Algoritmos de ordenação
- Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort e Heap Sort
- Recursão e divisão e conquista
- Árvores, árvore binária, árvore de busca binária e heaps

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação da MDN sobre JavaScript.
- Documentação oficial do TypeScript.
- Livros e materiais introdutórios sobre algoritmos e estruturas de dados.

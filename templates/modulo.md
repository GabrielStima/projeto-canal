# Template de Módulo

Use este template quando um módulo da formação for criado.

O módulo deve apresentar o papel daquele grupo de aulas dentro da jornada completa.

~~~markdown
# Nome do Módulo

## Objetivo do Módulo

Explique o que o aluno deve conquistar ao terminar este módulo.

## Por Que Este Módulo Existe

Explique por que estes assuntos aparecem nesta parte da formação e como eles preparam os próximos passos.

## Pré-requisitos

- Pré-requisito 1
- Pré-requisito 2
- Pré-requisito 3

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 01 | Nome da aula | Guarda-chuva | Planejada |
| 02 | Nome da aula | Específica | Planejada |

## Trilha de Estudo

> Use esta seção em módulos com 15 ou mais aulas, ou quando o módulo tiver sub-trilhas com dependências não óbvias entre grupos de aulas.
> Em módulos pequenos e lineares, esta seção pode ser omitida.

Este módulo está organizado em [N] blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — [Nome do bloco]** · aulas [XX.01–XX.0N]
[Descrição em uma linha do que este bloco cobre.]
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — [Nome do bloco]** · aulas [XX.0N–XX.0M]
[Descrição em uma linha do que este bloco cobre.]
Pré-requisito: Bloco A.

**Bloco C — [Nome do bloco]** · aulas [XX.0M–XX.0P]
[Descrição em uma linha do que este bloco cobre.]
Pré-requisito: Bloco B.

> Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

Use nomes simples e previsíveis dentro da pasta `exercicios/`:

- [Exercício 01 — Nome claro](exercicios/01-nome-claro.md)
- [Exercício 02 — Nome claro](exercicios/02-nome-claro.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

Cada exercício deve ser ligado à aula que ensina o conhecimento necessário. A atividade final deve combinar habilidades já praticadas, sem introduzir uma dificuldade nova.

Cada arquivo deve terminar com `## Corrija Sua Atividade Com IA` e um prompt copiável que:

- explique o cenário e a tarefa sem depender de arquivos externos;
- apresente critérios específicos de correção;
- contenha o marcador `[COLE SUA RESPOSTA AQUI]`;
- peça acertos, imprecisões e dicas antes de qualquer resposta completa.

Esse prompt pode reproduzir o contexto usado no exercício. Ele não substitui nem altera o `Prompt Para Estudar Com IA` das aulas.

## Projeto ou Prática do Módulo

Descreva uma prática integradora para consolidar as aulas.

## O Que Revisar Antes de Avançar

- Conceito 1
- Conceito 2
- Conceito 3

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo [NOME DO MÓDULO] de uma formação fullstack JavaScript/TypeScript.

Os assuntos estudados foram:
- [ASSUNTO 1]
- [ASSUNTO 2]
- [ASSUNTO 3]

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos;
3. perguntas de entrevista;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Referência 1
- Referência 2
- Referência 3
~~~

# Documentacao Tecnica

Este modulo mostra como registrar decisoes, comunicar arquitetura e manter conhecimento tecnico acessivel para pessoas, times e publicos externos.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar por que documentacao tecnica faz parte do trabalho de engenharia;
- escolher o tipo certo de documento para cada necessidade;
- escrever READMEs, ADRs, RFCs, HLDs e LLDs com clareza;
- usar diagramas para comunicar sistemas sem esconder decisoes importantes;
- diferenciar documentacao interna, documentacao externa e comunicacao tecnica;
- documentar arquitetura, operacao, riscos, trade-offs e proximos passos;
- revisar documentacao para evitar texto bonito, mas desatualizado ou falso.

## Por Que Este Modulo Existe

Sistemas reais nao vivem apenas no codigo. Eles tambem vivem em decisoes, historico, restricoes, runbooks, diagramas, contratos, riscos aceitos, comandos de operacao e explicacoes que permitem outras pessoas manterem o projeto.

Depois de system design e IA para desenvolvedores, o aluno ja tem repertorio para tomar decisoes tecnicas mais complexas. Agora o foco e transformar esse raciocinio em comunicacao: documentar o que foi decidido, por que foi decidido, quais alternativas foram descartadas e como outra pessoa pode usar, operar ou evoluir o sistema.

## Pre-requisitos

- Git, GitHub, code review, terminal e documentacao minima de projeto.
- Requisitos, historias de usuario, criterios de aceite e comunicacao com produto.
- APIs, contratos, OpenAPI, versionamento e governanca de API.
- Design e arquitetura de software: boundaries, coupling, cohesion, DDD e estilos arquiteturais.
- System design: requisitos, trade-offs, componentes, dados, seguranca, confiabilidade e custos.
- SRE, runbooks, incidentes, observabilidade, riscos operacionais e melhoria continua.
- Privacidade, governanca de dados, dados sensiveis, retencao e riscos aceitos.
- IA para documentacao, validacao de respostas e revisao tecnica.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 25.00 | [Documentacao Tecnica](25.00-documentacao-tecnica.md) | Guarda-chuva | Rascunho |
| 25.01 | [Comunicacao Tecnica](25.01-comunicacao-tecnica.md) | Especifica ampla | Rascunho |
| 25.02 | [Tipos de Documentacao Tecnica](25.02-tipos-de-documentacao-tecnica.md) | Especifica ampla | Rascunho |
| 25.03 | [README Profissional](25.03-readme-profissional.md) | Especifica pratica | Rascunho |
| 25.04 | [Documentacao Para Times](25.04-documentacao-para-times.md) | Especifica pratica | Rascunho |
| 25.05 | [Documentacao Para Publico Externo](25.05-documentacao-para-publico-externo.md) | Especifica pratica | Rascunho |
| 25.06 | [ADR](25.06-adr.md) | Especifica pratica | Rascunho |
| 25.07 | [RFC](25.07-rfc.md) | Especifica pratica | Rascunho |
| 25.08 | [HLD](25.08-hld.md) | Especifica pratica | Rascunho |
| 25.09 | [C4 Model](25.09-c4-model.md) | Especifica pratica | Rascunho |
| 25.10 | [Diagramas](25.10-diagramas.md) | Especifica pratica | Rascunho |
| 25.11 | [LLD](25.11-lld.md) | Especifica pratica | Rascunho |
| 25.12 | [Projeto Pratico: Documentando Uma Arquitetura Tecnica](25.12-projeto-pratico-documentando-uma-arquitetura-tecnica.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Escolha uma aplicacao ou arquitetura ja estudada no curso e produza um pacote de documentacao tecnica:

1. README com objetivo, setup, comandos, configuracao e limites;
2. documentacao interna para onboarding e manutencao;
3. uma pagina externa ou guia de uso para consumidores;
4. um ADR registrando uma decisao arquitetural;
5. uma RFC curta propondo uma evolucao;
6. um HLD com visao de alto nivel do sistema;
7. diagramas para comunicar contexto, fluxo e implantacao;
8. um LLD para uma parte especifica da implementacao;
9. checklist de revisao para verificar se os documentos estao corretos e atualizados.

## O Que Revisar Antes de Avancar

- Documentacao minima de projeto e README.
- Requisitos, criterios de aceite e comunicacao de produto.
- Contratos de API, OpenAPI, versionamento e governanca.
- Arquitetura de software, boundaries e trade-offs.
- System design, requisitos nao funcionais, dados, seguranca, confiabilidade e custos.
- Runbooks, incidentes, observabilidade e operacao.
- Privacidade, governanca de dados e riscos aceitos.
- Uso de IA para documentacao sem inventar detalhes.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Documentacao Tecnica de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina documentacao tecnica, comunicacao tecnica, README, documentacao interna e externa, ADR, RFC, HLD, LLD, C4 Model e diagramas.
- Objetivo do modulo: Quero conseguir registrar decisoes e comunicar arquitetura com clareza para times, revisores, usuarios tecnicos e publico externo.
- Pre-requisitos: documentacao minima, requisitos, APIs, arquitetura, system design, SRE, seguranca, privacidade e IA para documentacao.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos de escrita tecnica;
3. cenarios para escolher entre README, ADR, RFC, HLD, LLD e diagramas;
4. perguntas de entrevista para backend/fullstack intermediario-avancado;
5. exemplos de aplicacao em projetos reais;
6. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Materiais internos do proprio projeto.
- Documentacao oficial das ferramentas usadas nas praticas especificas.
- Guias publicos de arquitetura, engenharia, SRE, APIs e escrita tecnica quando uma aula exigir aprofundamento.

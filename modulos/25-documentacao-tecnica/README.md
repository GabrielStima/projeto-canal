<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Documentação Técnica

</div>

Este módulo mostra como registrar decisões, comunicar arquitetura e manter conhecimento técnico acessível para pessoas, times e públicos externos.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar por que documentação técnica faz parte do trabalho de engenharia;
- escolher o tipo certo de documento para cada necessidade;
- escrever READMEs, ADRs, RFCs, HLDs e LLDs com clareza;
- usar diagramas para comunicar sistemas sem esconder decisões importantes;
- diferenciar documentação interna, documentação externa e comunicação técnica;
- documentar arquitetura, operação, riscos, trade-offs e próximos passos;
- revisar documentação para evitar texto bonito, mas desatualizado ou falso.

## Por Que Este Módulo Existe

Sistemas reais não vivem apenas no código. Eles também vivem em decisões, histórico, restrições, runbooks, diagramas, contratos, riscos aceitos, comandos de operação e explicações que permitem outras pessoas manterem o projeto.

Depois de system design e IA para desenvolvedores, o aluno já tem repertório para tomar decisões técnicas mais complexas. Agora o foco é transformar esse raciocínio em comunicação: documentar o que foi decidido, por que foi decidido, quais alternativas foram descartadas e como outra pessoa pode usar, operar ou evoluir o sistema.

## Pré-requisitos

- Git, GitHub, code review, terminal e documentação mínima de projeto.
- Requisitos, histórias de usuário, critérios de aceite e comunicação com produto.
- APIs, contratos, OpenAPI, versionamento e governança de API.
- Design e arquitetura de software: boundaries, coupling, cohesion, DDD e estilos arquiteturais.
- System design: requisitos, trade-offs, componentes, dados, segurança, confiabilidade e custos.
- SRE, runbooks, incidentes, observabilidade, riscos operacionais e melhoria contínua.
- Privacidade, governança de dados, dados sensíveis, retenção e riscos aceitos.
- IA para documentação, validação de respostas e revisão técnica.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 25.00 | [Documentação Técnica](25.00-documentacao-tecnica.md) | Guarda-chuva | Rascunho |
| 25.01 | [Comunicação Técnica](25.01-comunicacao-tecnica.md) | Específica ampla | Rascunho |
| 25.02 | [Tipos de Documentação Técnica](25.02-tipos-de-documentacao-tecnica.md) | Específica ampla | Rascunho |
| 25.03 | [README Profissional](25.03-readme-profissional.md) | Específica prática | Rascunho |
| 25.04 | [Documentação para Times](25.04-documentacao-para-times.md) | Específica prática | Rascunho |
| 25.05 | [Documentação para Público Externo](25.05-documentacao-para-publico-externo.md) | Específica prática | Rascunho |
| 25.06 | [ADR](25.06-adr.md) | Específica prática | Rascunho |
| 25.07 | [RFC](25.07-rfc.md) | Específica prática | Rascunho |
| 25.08 | [HLD](25.08-hld.md) | Específica prática | Rascunho |
| 25.09 | [C4 Model](25.09-c4-model.md) | Específica prática | Rascunho |
| 25.10 | [Diagramas](25.10-diagramas.md) | Específica prática | Rascunho |
| 25.11 | [LLD](25.11-lld.md) | Específica prática | Rascunho |
| 25.12 | [Projeto Prático: Documentando uma Arquitetura Técnica](25.12-projeto-pratico-documentando-uma-arquitetura-tecnica.md) | Síntese prática | Rascunho |


## Exercícios

- [Exercício 01 — README do PetCare OS](exercicios/01-readme-do-petcare-os.md)
- [Exercício 02 — ADR de Decisão Arquitetural](exercicios/02-adr-de-decisao-arquitetural.md)
- [Exercício 03 — HLD e C4 Nível 2](exercicios/03-hld-e-c4-nivel-2.md)
- [Exercício 04 — Diagrama de Fluxo e LLD](exercicios/04-diagrama-de-fluxo-e-lld.md)
- [Exercício 05 — Runbook Operacional](exercicios/05-runbook-operacional.md)
- [Exercício 06 — RFC para Mudança Futura](exercicios/06-rfc-para-mudanca-futura.md)
- [Atividade Final Prática: Portal Documental do PetCare OS](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo você constrói progressivamente um portal documental do PetCare OS. Cada exercício gera um artefato que será reutilizado na atividade final:

1. Escreva o README principal do repositório com instruções claras para rodar o projeto localmente.
2. Registre uma decisão arquitetural importante em um ADR com contexto, alternativas e consequências.
3. Desenhe o HLD e o C4 Model nível 2, mostrando frontend, APIs, filas, banco, cache e integrações externas.
4. Detalhe um fluxo específico em um LLD com diagrama de sequência e contratos.
5. Crie um runbook operacional para um incidente realista.
6. Proponha uma mudança futura em uma RFC com impacto, riscos e plano de migração.

Na atividade final, você consolida tudo em `docs/portal-documental.md`, organizando a documentação por público, jornada, qualidade e manutenção.

## O Que Revisar Antes de Avançar

- Documentação mínima de projeto e README.
- Requisitos, critérios de aceite e comunicação de produto.
- Contratos de API, OpenAPI, versionamento e governança.
- Arquitetura de software, boundaries e trade-offs.
- System design, requisitos não funcionais, dados, segurança, confiabilidade e custos.
- Runbooks, incidentes, observabilidade e operação.
- Privacidade, governança de dados e riscos aceitos.
- Uso de IA para documentação sem inventar detalhes.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Documentação Técnica de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina documentação técnica, comunicação técnica, README, documentação interna e externa, ADR, RFC, HLD, LLD, C4 Model e diagramas.
- Objetivo do módulo: Quero conseguir registrar decisões e comunicar arquitetura com clareza para times, revisores, usuários técnicos e público externo.
- Pré-requisitos: documentação mínima, requisitos, APIs, arquitetura, system design, SRE, segurança, privacidade e IA para documentação.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de escrita técnica;
3. cenários para escolher entre README, ADR, RFC, HLD, LLD e diagramas;
4. perguntas de entrevista para backend/fullstack intermediário-avançado;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial das ferramentas usadas nas práticas específicas.
- Guias públicos de arquitetura, engenharia, SRE, APIs e escrita técnica quando uma aula exigir aprofundamento.

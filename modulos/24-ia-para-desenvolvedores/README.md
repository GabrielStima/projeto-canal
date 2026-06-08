# IA para Desenvolvedores

Este modulo mostra como usar IA como ferramenta de trabalho sem terceirizar o raciocinio tecnico, e como projetar, integrar, avaliar, proteger e operar aplicacoes que usam IA.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- explicar os fundamentos de IA generativa, LLMs, tokens, contexto e embeddings;
- usar prompts para estudar, programar, depurar, testar e documentar com mais criterio;
- revisar codigo gerado por IA com atencao a corretude, seguranca, manutencao e testes;
- criar fluxos de trabalho com coding agents sem perder controle sobre mudancas;
- entender RAG, embeddings, vector databases, function calling e agentes com ferramentas;
- avaliar respostas de IA usando criterios, evals e guardrails;
- reconhecer riscos de privacidade, vazamento de dados, prompt injection e excesso de autonomia;
- relacionar custos, observabilidade, LLMOps e FinOps com aplicacoes reais de IA;
- construir um assistente tecnico simples com RAG ou agente controlado.

## Por Que Este Modulo Existe

IA ja aparece no editor, na busca por documentacao, no debug, na escrita de testes, na revisao de codigo, na documentacao e em produtos que conversam com usuarios. Isso muda o fluxo de trabalho do desenvolvedor, mas nao elimina fundamentos: quanto maior a autonomia da ferramenta, maior a necessidade de requisitos claros, testes, revisao, seguranca, observabilidade e bom julgamento.

Este modulo entra depois de system design porque IA deixa de ser apenas "um chat que ajuda a programar" e passa a ser parte de sistemas: ela consome dados, chama ferramentas, produz saidas probabilisticas, gera custo, cria riscos de seguranca e precisa ser avaliada.

## Pre-requisitos

- TypeScript, assincronismo, APIs e backend com Node.js.
- Git, GitHub, code review, terminal, package managers e documentacao minima.
- Engenharia de produto: requisitos, criterios de aceite e experimentos.
- Testes, mocks, analise estatica, CI, quality gates, observabilidade e performance.
- Autenticacao, autorizacao, seguranca em APIs, threat modeling e Secure SDLC.
- Privacidade, dados sensiveis, segredos, logs e governanca de dados.
- System design: requisitos, trade-offs, caching, dados, filas, observabilidade, seguranca e custos.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 24.00 | [IA para Desenvolvedores](24.00-ia-para-desenvolvedores.md) | Guarda-chuva | Rascunho |
| 24.01 | [O Que E IA Generativa](24.01-o-que-e-ia-generativa.md) | Especifica ampla | Rascunho |
| 24.02 | [LLMs, Tokens, Contexto e Visao Geral de Embeddings](24.02-llms-tokens-contexto-e-visao-geral-de-embeddings.md) | Especifica | Rascunho |
| 24.03 | [Limitacoes, Alucinacoes e Validacao](24.03-limitacoes-alucinacoes-e-validacao.md) | Especifica | Rascunho |
| 24.04 | [Privacidade, Dados Sensiveis e Segredos em IA](24.04-privacidade-dados-sensiveis-e-segredos-em-ia.md) | Especifica pratica | Rascunho |
| 24.05 | [Prompt Engineering](24.05-prompt-engineering.md) | Especifica pratica | Rascunho |
| 24.06 | [Como Usar IA Para Escrever Codigo](24.06-como-usar-ia-para-escrever-codigo.md) | Especifica pratica | Rascunho |
| 24.07 | [Como Revisar Codigo Gerado por IA](24.07-como-revisar-codigo-gerado-por-ia.md) | Especifica pratica | Rascunho |
| 24.08 | [Seguranca em Codigo Gerado por IA](24.08-seguranca-em-codigo-gerado-por-ia.md) | Especifica pratica | Rascunho |
| 24.09 | [Quality Gates Para Codigo Gerado por IA](24.09-quality-gates-para-codigo-gerado-por-ia.md) | Especifica pratica | Rascunho |
| 24.10 | [IA no Debug](24.10-ia-no-debug.md) | Especifica pratica | Rascunho |
| 24.11 | [IA Para Testes](24.11-ia-para-testes.md) | Especifica pratica | Rascunho |
| 24.12 | [IA Para Documentacao](24.12-ia-para-documentacao.md) | Especifica pratica | Rascunho |
| 24.13 | [Coding Agents](24.13-coding-agents.md) | Especifica ampla | Rascunho |
| 24.14 | [Workflows com Agentes](24.14-workflows-com-agentes.md) | Especifica pratica | Rascunho |
| 24.15 | [Function Calling e Tool Calling](24.15-function-calling-e-tool-calling.md) | Especifica | Rascunho |
| 24.16 | [Agentes com Ferramentas](24.16-agentes-com-ferramentas.md) | Especifica pratica | Rascunho |
| 24.17 | [OWASP Top 10 para LLM Applications](24.17-owasp-top-10-para-llm-applications.md) | Especifica ampla | Rascunho |
| 24.18 | [OWASP Agentic AI Top 10](24.18-owasp-agentic-ai-top-10.md) | Especifica ampla | Rascunho |
| 24.19 | [Embeddings](24.19-embeddings.md) | Especifica | Rascunho |
| 24.20 | [Vector Databases](24.20-vector-databases.md) | Especifica | Rascunho |
| 24.21 | [RAG](24.21-rag.md) | Especifica pratica | Rascunho |
| 24.22 | [Avaliacao de Respostas de IA](24.22-avaliacao-de-respostas-de-ia.md) | Especifica | Rascunho |
| 24.23 | [Evals](24.23-evals.md) | Especifica pratica | Rascunho |
| 24.24 | [Guardrails](24.24-guardrails.md) | Especifica pratica | Rascunho |
| 24.25 | [Custos e Observabilidade em Apps com IA](24.25-custos-e-observabilidade-em-apps-com-ia.md) | Especifica pratica | Rascunho |
| 24.26 | [LLMOps](24.26-llmops.md) | Especifica ampla | Rascunho |
| 24.27 | [FinOps Para IA](24.27-finops-para-ia.md) | Especifica pratica | Rascunho |
| 24.28 | [Projeto Pratico: Assistente Tecnico com RAG ou Agente Simples](24.28-projeto-pratico-assistente-tecnico-com-rag-ou-agente-simples.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Construa um assistente tecnico para consultar materiais do curso ou ajudar na manutencao de um projeto TypeScript:

1. defina o problema, o usuario e os limites do assistente;
2. classifique os dados que podem ou nao entrar no contexto;
3. escreva prompts base com criterios de resposta;
4. implemente uma versao com RAG ou um agente simples com ferramentas controladas;
5. registre custo, latencia, tokens, erros, recusas e fontes usadas;
6. crie criterios de avaliacao e alguns casos de teste;
7. defina guardrails para dados sensiveis, instrucoes maliciosas e acoes perigosas;
8. documente trade-offs, riscos aceitos e proximas melhorias.

## O Que Revisar Antes de Avancar

- Requisitos, criterios de aceite e code review.
- Testes unitarios, integracao, end-to-end, mocks, analise estatica e quality gates.
- Logs, metricas, tracing, telemetria, monitoramento e alertas.
- Autenticacao, autorizacao, menor privilegio, secrets e threat modeling.
- Privacidade, dados sensiveis, minimizacao, logs sensiveis e dados enviados para IA.
- System design, custos, confiabilidade, seguranca e trade-offs.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo IA para Desenvolvedores de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina fundamentos de IA generativa, LLMs, tokens, contexto, embeddings, prompts, uso de IA no desenvolvimento, coding agents, tool calling, agentes, RAG, avaliacao, evals, guardrails, seguranca, privacidade, LLMOps, observabilidade e custos.
- Objetivo do modulo: Quero usar IA como ferramenta de trabalho e tambem projetar aplicacoes com IA de forma segura, avaliavel e operavel.
- Pre-requisitos: TypeScript, APIs, testes, CI, seguranca, privacidade, observabilidade, Secure SDLC e system design.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos de prompts, revisao de codigo e avaliacao;
3. cenarios de risco envolvendo dados, agentes, RAG e ferramentas;
4. perguntas de entrevista para backend/fullstack intermediario-avancado;
5. exemplos de aplicacao em projetos reais;
6. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Materiais internos do proprio projeto.
- OWASP GenAI Security Project.
- OWASP Top 10 for LLM Applications 2025.
- OWASP Top 10 for Agentic Applications 2026.
- Documentacao oficial das ferramentas, modelos, SDKs e provedores usados em praticas especificas.

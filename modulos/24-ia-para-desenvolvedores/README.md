# IA para Desenvolvedores

Este módulo mostra como usar IA como ferramenta de trabalho sem terceirizar o raciocínio técnico, e como projetar, integrar, avaliar, proteger e operar aplicações que usam IA.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar os fundamentos de IA generativa, LLMs, tokens, contexto e embeddings;
- usar prompts para estudar, programar, depurar, testar e documentar com mais critério;
- revisar código gerado por IA com atenção a corretude, segurança, manutenção e testes;
- criar fluxos de trabalho com coding agents sem perder controle sobre mudanças;
- entender RAG, embeddings, vector databases, function calling e agentes com ferramentas;
- avaliar respostas de IA usando critérios, evals e guardrails;
- reconhecer riscos de privacidade, vazamento de dados, prompt injection e excesso de autonomia;
- relacionar custos, observabilidade, LLMOps e FinOps com aplicações reais de IA;
- construir um assistente técnico simples com RAG ou agente controlado.

## Por Que Este Módulo Existe

IA já aparece no editor, na busca por documentação, no debug, na escrita de testes, na revisão de código, na documentação e em produtos que conversam com usuários. Isso muda o fluxo de trabalho do desenvolvedor, mas não elimina fundamentos: quanto maior a autonomia da ferramenta, maior a necessidade de requisitos claros, testes, revisão, segurança, observabilidade e bom julgamento.

Este módulo entra depois de system design porque IA deixa de ser apenas "um chat que ajuda a programar" e passa a ser parte de sistemas: ela consome dados, chama ferramentas, produz saídas probabilísticas, gera custo, cria riscos de segurança e precisa ser avaliada.

## Pré-requisitos

- TypeScript, assincronismo, APIs e backend com Node.js.
- Git, GitHub, code review, terminal, package managers e documentação mínima.
- Engenharia de produto: requisitos, critérios de aceite e experimentos.
- Testes, mocks, análise estática, CI, quality gates, observabilidade e performance.
- Autenticação, autorização, segurança em APIs, threat modeling e Secure SDLC.
- Privacidade, dados sensíveis, segredos, logs e governança de dados.
- System design: requisitos, trade-offs, caching, dados, filas, observabilidade, segurança e custos.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 24.00 | [IA para Desenvolvedores](24.00-ia-para-desenvolvedores.md) | Guarda-chuva | Rascunho |
| 24.01 | [O Que É IA Generativa](24.01-o-que-e-ia-generativa.md) | Específica ampla | Rascunho |
| 24.02 | [LLMs, Tokens, Contexto e Visão Geral de Embeddings](24.02-llms-tokens-contexto-e-visão-geral-de-embeddings.md) | Específica | Rascunho |
| 24.03 | [Limitações, Alucinações e Validação](24.03-limitacoes-alucinacoes-e-validação.md) | Específica | Rascunho |
| 24.04 | [Privacidade, Dados Sensíveis e Segredos em IA](24.04-privacidade-dados-sensiveis-e-segredos-em-ia.md) | Específica prática | Rascunho |
| 24.05 | [Prompt Engineering](24.05-prompt-engineering.md) | Específica prática | Rascunho |
| 24.06 | [Como Usar IA Para Escrever Código](24.06-como-usar-ia-para-escrever-código.md) | Específica prática | Rascunho |
| 24.07 | [Como Revisar Código Gerado por IA](24.07-como-revisar-código-gerado-por-ia.md) | Específica prática | Rascunho |
| 24.08 | [Segurança em Código Gerado por IA](24.08-segurança-em-código-gerado-por-ia.md) | Específica prática | Rascunho |
| 24.09 | [Quality Gates Para Código Gerado por IA](24.09-quality-gates-para-código-gerado-por-ia.md) | Específica prática | Rascunho |
| 24.10 | [IA no Debug](24.10-ia-no-debug.md) | Específica prática | Rascunho |
| 24.11 | [IA Para Testes](24.11-ia-para-testes.md) | Específica prática | Rascunho |
| 24.12 | [IA Para Documentação](24.12-ia-para-documentação.md) | Específica prática | Rascunho |
| 24.13 | [Coding Agents](24.13-coding-agents.md) | Específica ampla | Rascunho |
| 24.14 | [Workflows com Agentes](24.14-workflows-com-agentes.md) | Específica prática | Rascunho |
| 24.15 | [Function Calling e Tool Calling](24.15-function-calling-e-tool-calling.md) | Específica | Rascunho |
| 24.16 | [Agentes com Ferramentas](24.16-agentes-com-ferramentas.md) | Específica prática | Rascunho |
| 24.17 | [OWASP Top 10 para LLM Applications](24.17-owasp-top-10-para-llm-applications.md) | Específica ampla | Rascunho |
| 24.18 | [OWASP Agentic AI Top 10](24.18-owasp-agentic-ai-top-10.md) | Específica ampla | Rascunho |
| 24.19 | [Embeddings](24.19-embeddings.md) | Específica | Rascunho |
| 24.20 | [Vector Databases](24.20-vector-databases.md) | Específica | Rascunho |
| 24.21 | [RAG](24.21-rag.md) | Específica prática | Rascunho |
| 24.22 | [Avaliação de Respostas de IA](24.22-avaliacao-de-respostas-de-ia.md) | Específica | Rascunho |
| 24.23 | [Evals](24.23-evals.md) | Específica prática | Rascunho |
| 24.24 | [Guardrails](24.24-guardrails.md) | Específica prática | Rascunho |
| 24.25 | [Custos e Observabilidade em Apps com IA](24.25-custos-e-observabilidade-em-apps-com-ia.md) | Específica prática | Rascunho |
| 24.26 | [LLMOps](24.26-llmops.md) | Específica ampla | Rascunho |
| 24.27 | [FinOps Para IA](24.27-finops-para-ia.md) | Específica prática | Rascunho |
| 24.28 | [Projeto Prático: Assistente Técnico com RAG ou Agente Simples](24.28-projeto-pratico-assistente-tecnico-com-rag-ou-agente-simples.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Construa um assistente técnico para consultar materiais do curso ou ajudar na manutenção de um projeto TypeScript:

1. defina o problema, o usuário e os limites do assistente;
2. classifique os dados que podem ou não entrar no contexto;
3. escreva prompts base com critérios de resposta;
4. implemente uma versão com RAG ou um agente simples com ferramentas controladas;
5. registre custo, latência, tokens, erros, recusas e fontes usadas;
6. crie critérios de avaliação e alguns casos de teste;
7. defina guardrails para dados sensíveis, instruções maliciosas e ações perigosas;
8. documente trade-offs, riscos aceitos e próximas melhorias.

## O Que Revisar Antes de Avançar

- Requisitos, critérios de aceite e code review.
- Testes unitários, integração, end-to-end, mocks, análise estática e quality gates.
- Logs, métricas, tracing, telemetria, monitoramento e alertas.
- Autenticação, autorização, menor privilégio, secrets e threat modeling.
- Privacidade, dados sensíveis, minimização, logs sensíveis e dados enviados para IA.
- System design, custos, confiabilidade, segurança e trade-offs.

## Prompt de Revisao do Módulo

```text
Estou finalizando o módulo IA para Desenvolvedores de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina fundamentos de IA generativa, LLMs, tokens, contexto, embeddings, prompts, uso de IA no desenvolvimento, coding agents, tool calling, agentes, RAG, avaliação, evals, guardrails, segurança, privacidade, LLMOps, observabilidade e custos.
- Objetivo do módulo: Quero usar IA como ferramenta de trabalho e também projetar aplicações com IA de forma segura, avaliável e operável.
- Pré-requisitos: TypeScript, APIs, testes, CI, segurança, privacidade, observabilidade, Secure SDLC e system design.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de prompts, revisão de código e avaliação;
3. cenários de risco envolvendo dados, agentes, RAG e ferramentas;
4. perguntas de entrevista para backend/fullstack intermediário-avançado;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- OWASP GenAI Security Project.
- OWASP Top 10 for LLM Applications 2025.
- OWASP Top 10 for Agentic Applications 2026.
- Documentação oficial das ferramentas, modelos, SDKs e provedores usados em práticas específicas.

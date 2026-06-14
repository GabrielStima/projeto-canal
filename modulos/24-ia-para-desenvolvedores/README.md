<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# IA para Desenvolvedores

</div>

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
| 24.00 | [IA para Desenvolvedores](24.00-ia-para-desenvolvedores.md) | Guarda-chuva | Auditada |
| 24.01 | [O Que É IA Generativa](24.01-o-que-e-ia-generativa.md) | Específica ampla | Auditada |
| 24.02 | [LLMs, Tokens, Contexto e Visão Geral de Embeddings](24.02-llms-tokens-contexto-e-visao-geral-de-embeddings.md) | Específica | Auditada |
| 24.03 | [Limitações, Alucinações e Validação](24.03-limitacoes-alucinacoes-e-validacao.md) | Específica | Auditada |
| 24.04 | [Privacidade, Dados Sensíveis e Segredos em IA](24.04-privacidade-dados-sensiveis-e-segredos-em-ia.md) | Específica prática | Auditada |
| 24.05 | [Prompt Engineering](24.05-prompt-engineering.md) | Específica prática | Auditada |
| 24.06 | [Como Usar IA Para Escrever Código](24.06-como-usar-ia-para-escrever-codigo.md) | Específica prática | Auditada |
| 24.07 | [Como Revisar Código Gerado por IA](24.07-como-revisar-codigo-gerado-por-ia.md) | Específica prática | Auditada |
| 24.08 | [Segurança em Código Gerado por IA](24.08-seguranca-em-codigo-gerado-por-ia.md) | Específica prática | Auditada |
| 24.09 | [Quality Gates Para Código Gerado por IA](24.09-quality-gates-para-codigo-gerado-por-ia.md) | Específica prática | Auditada |
| 24.10 | [IA no Debug](24.10-ia-no-debug.md) | Específica prática | Auditada |
| 24.11 | [IA Para Testes](24.11-ia-para-testes.md) | Específica prática | Auditada |
| 24.12 | [IA Para Documentação](24.12-ia-para-documentacao.md) | Específica prática | Auditada |
| 24.13 | [Coding Agents](24.13-coding-agents.md) | Específica ampla | Auditada |
| 24.14 | [Workflows com Agentes](24.14-workflows-com-agentes.md) | Específica prática | Auditada |
| 24.15 | [Function Calling e Tool Calling](24.15-function-calling-e-tool-calling.md) | Específica | Auditada |
| 24.16 | [Agentes com Ferramentas](24.16-agentes-com-ferramentas.md) | Específica prática | Auditada |
| 24.17 | [OWASP Top 10 para LLM Applications](24.17-owasp-top-10-para-llm-applications.md) | Específica ampla | Auditada |
| 24.18 | [OWASP Agentic AI Top 10](24.18-owasp-agentic-ai-top-10.md) | Específica ampla | Auditada |
| 24.19 | [Embeddings](24.19-embeddings.md) | Específica | Auditada |
| 24.20 | [Vector Databases](24.20-vector-databases.md) | Específica | Auditada |
| 24.21 | [RAG](24.21-rag.md) | Específica prática | Auditada |
| 24.22 | [Avaliação de Respostas de IA](24.22-avaliacao-de-respostas-de-ia.md) | Específica | Auditada |
| 24.23 | [Evals](24.23-evals.md) | Específica prática | Auditada |
| 24.24 | [Guardrails](24.24-guardrails.md) | Específica prática | Auditada |
| 24.25 | [Custos e Observabilidade em Apps com IA](24.25-custos-e-observabilidade-em-apps-com-ia.md) | Específica prática | Auditada |
| 24.26 | [LLMOps](24.26-llmops.md) | Específica ampla | Auditada |
| 24.27 | [FinOps Para IA](24.27-finops-para-ia.md) | Específica prática | Auditada |
| 24.28 | [Projeto Prático: Assistente Técnico com RAG ou Agente Simples](24.28-projeto-pratico-assistente-tecnico-com-rag-ou-agente-simples.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Os blocos A e B formam a base conceitual; C e D são aplicações avançadas que dependem de A e B.

**Bloco A — Fundamentos de IA Generativa** · aulas 24.01–24.04
O que é IA generativa, como LLMs funcionam (tokens, contexto, embeddings), limitações e alucinações, e como lidar com privacidade e dados sensíveis.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — IA no Fluxo de Desenvolvimento** · aulas 24.05–24.14
Prompt engineering, uso de IA para escrever código, revisar código, segurança em código gerado, quality gates, debug, testes, documentação, coding agents e workflows com agentes.
Pré-requisito: Bloco A.

**Bloco C — Segurança e Avaliação** · aulas 24.15–24.24
Function calling e tool calling, agentes com ferramentas, OWASP Top 10 para LLMs, OWASP Agentic AI, embeddings, vector databases, RAG, avaliação de respostas, evals e guardrails. Pode ser estudado em paralelo com o final do Bloco B após 24.13.
Pré-requisito: Blocos A e B.

**Bloco D — Operação e Custos** · aulas 24.25–24.27
Custos e observabilidade em aplicações com IA, LLMOps e FinOps para IA.
Pré-requisito: Bloco C (só faz sentido operar e medir o que você já sabe construir).

> As dependências entre aulas dentro de um bloco estão documentadas no campo "Onde Esta Aula Entra na Formação" de cada arquivo.



## Exercícios

- [Exercício 01 — Escopo, Limites e Dados](exercicios/01-escopo-limites-dados.md)
- [Exercício 02 — Workflow de Desenvolvimento](exercicios/02-workflow-desenvolvimento.md)
- [Exercício 03 — Ferramentas e Autonomia](exercicios/03-ferramentas-autonomia.md)
- [Exercício 04 — RAG e Recuperação](exercicios/04-rag-recuperacao.md)
- [Exercício 05 — Evals e Guardrails](exercicios/05-evals-guardrails.md)
- [Exercício 06 — Operação e Custos](exercicios/06-operacao-custos.md)
- [Atividade Final Prática — Assistente Controlado do PetCare OS](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo você evolui um assistente controlado do PetCare OS em seis entregas:

1. Especifica problema, limites, dados, riscos e métricas antes de escolher uma tecnologia.
2. Usa IA em uma mudança pequena de código com critérios de aceite, revisão e quality gates.
3. Projeta ferramentas com menor privilégio, confirmação humana, limites e auditoria.
4. Constrói uma recuperação simples sobre documentos públicos ou fictícios, com fontes e recusa quando falta evidência.
5. Cria evals e guardrails para comportamentos esperados, casos adversariais e regressões.
6. Define versionamento, rollout, rollback, observabilidade, orçamento e critérios de interrupção.

A atividade final reúne essas decisões em um protótipo pequeno. O uso de API paga, banco vetorial ou modelo hospedado não é obrigatório: uma implementação local ou um test double é suficiente quando preserva os contratos e permite demonstrar o comportamento. O assistente usa somente conteúdo aprovado e não atua como autoridade clínica.

## O Que Revisar Antes de Avançar

- Requisitos, critérios de aceite e code review.
- Testes unitários, integração, end-to-end, mocks, análise estática e quality gates.
- Logs, métricas, tracing, telemetria, monitoramento e alertas.
- Autenticação, autorização, menor privilégio, secrets e threat modeling.
- Privacidade, dados sensíveis, minimização, logs sensíveis e dados enviados para IA.
- System design, custos, confiabilidade, segurança e trade-offs.

## Prompt de Revisão do Módulo

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

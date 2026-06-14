<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# API Design Profissional

</div>

Este módulo marca a passagem de "eu sei criar endpoints" para "eu sei desenhar APIs que outras pessoas conseguem consumir, manter e evoluir". No módulo 10, você construiu a `petcare-api`: uma API Node.js que consulta pets e atendimentos e aprova orçamentos de forma persistente.

Agora o foco muda para contrato, consistência e evolução. Uma API profissional não é apenas uma lista de rotas funcionando. Ela precisa ter nomes previsíveis, respostas claras, erros padronizados, regras de paginação, filtros, ordenação, compatibilidade, versionamento, documentação útil e formas de validar que o contrato não quebrou.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- desenhar APIs pensando no consumidor;
- organizar recursos, operações, parâmetros e respostas com consistência;
- escrever contratos de API úteis;
- usar OpenAPI de forma prática;
- evoluir uma API sem quebrar clientes desnecessariamente;
- diferenciar backward compatibility de versionamento;
- padronizar erros, paginação, filtros e ordenação;
- entender idempotência em operações sensíveis;
- projetar webhooks com cuidado;
- reconhecer o papel de API governance;
- usar contract testing como validação de contrato.

## Por Que Este Módulo Existe

No módulo 10, você aprendeu a construir uma API backend pequena com Node.js. Isso resolve a pergunta "como criar um serviço?". Este módulo resolve outra pergunta: "como desenhar um serviço que continua compreensível quando cresce, ganha consumidores diferentes e precisa mudar sem quebrar tudo?".

API design profissional aparece antes de autenticação, segurança, qualidade, observabilidade e arquitetura porque muitos problemas desses módulos ficam piores quando o contrato da API é confuso. Segurança mal comunicada, logs sem contexto, testes frágeis e integrações instáveis quase sempre passam por uma API mal desenhada.

## Pré-requisitos

- Entender HTTP, métodos, headers, status codes, request, response e cache.
- Saber consumir APIs no frontend e lidar com loading, erro e validação.
- Saber escrever TypeScript, objetos, tipos, promises, `async/await` e tratamento de erros.
- Entender requisitos, critérios de aceite e comunicação entre produto e engenharia.
- Entender modelagem de dados, integridade, transactions e indexes em nível introdutório.
- Ter estudado APIs, JSON APIs, REST, GraphQL, SOAP, OpenAPI introdutório, logging e failure modes no módulo 10.
- Ter construído ou acompanhado a `petcare-api` do módulo 10, com endpoints para pets, atendimentos e orçamentos.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 11.00 | [API Design Profissional](11.00-api-design-profissional.md) | Guarda-chuva | Auditada |
| 11.01 | [Design de APIs](11.01-design-de-apis.md) | Específica ampla | Auditada |
| 11.02 | [Contratos de API](11.02-contratos-de-api.md) | Específica | Auditada |
| 11.03 | [OpenAPI na Prática](11.03-openapi-na-pratica.md) | Específica prática | Auditada |
| 11.04 | [Backward Compatibility](11.04-backward-compatibility.md) | Específica | Auditada |
| 11.05 | [Versionamento de API](11.05-versionamento-de-api.md) | Específica | Auditada |
| 11.06 | [Erros Padronizados](11.06-erros-padronizados.md) | Específica prática | Auditada |
| 11.07 | [Paginação](11.07-paginacao.md) | Específica prática | Auditada |
| 11.08 | [Filtros](11.08-filtros.md) | Específica prática | Auditada |
| 11.09 | [Ordenação](11.09-ordenacao.md) | Específica prática | Auditada |
| 11.10 | [Idempotência](11.10-idempotencia.md) | Específica | Auditada |
| 11.11 | [Webhooks](11.11-webhooks.md) | Específica prática | Auditada |
| 11.12 | [API Governance](11.12-api-governance.md) | Guarda-chuva curta | Auditada |
| 11.13 | [Contract Testing](11.13-contract-testing.md) | Específica introdutória/prática | Auditada |
| 11.14 | [Projeto Prático: Design Profissional de uma API](11.14-projeto-pratico-design-profissional-de-uma-api.md) | Síntese prática | Auditada |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Siga a ordem para evoluir a `petcare-api` sem concentrar toda a implementação no encerramento.

**Bloco A — De endpoint para API de verdade** · aulas 11.00–11.03
Design de APIs, contratos e OpenAPI na prática, usando os recursos já existentes da `petcare-api`.
Pré-requisito: módulo 10 e a `petcare-api` funcional.

Ao concluir OpenAPI, faça o [Exercício 01 — Contratos da PetCare API](exercicios/01-contratos-da-petcare-api.md).

**Bloco B — Evolução e confiança no contrato** · aulas 11.04–11.06
Backward compatibility, versionamento e erros padronizados. O objetivo é garantir que mudanças na API não quebrem os consumidores e que problemas sejam comunicados de forma previsível.
Pré-requisito: Bloco A.

Depois de erros padronizados, faça o [Exercício 02 — Erros da PetCare API](exercicios/02-erros-da-petcare-api.md).

**Bloco C — Listagens e operações seguras** · aulas 11.07–11.11
Paginação, filtros, ordenação, idempotência e webhooks. Aqui a API ganha padrões para listar dados e proteger operações sensíveis contra repetição e falha.
Pré-requisito: Bloco B.

Depois de ordenação, faça o [Exercício 03 — Listagens da PetCare API](exercicios/03-listagens-da-petcare-api.md). Ao concluir idempotência, faça o [Exercício 04 — Aprovação Idempotente](exercicios/04-aprovacao-idempotente.md). Depois de webhooks, faça o [Exercício 05 — Contrato de Webhook](exercicios/05-webhook-para-o-tutor.md) como prática exploratória.

**Bloco D — Governança e validação** · aulas 11.12–11.13
API governance e contract testing. O objetivo é criar regras para manter a API consistente e verificar que o contrato continua sendo respeitado.
Pré-requisito: Bloco C.

Ao concluir contract testing, faça o [Exercício 06 — Testes de Contrato](exercicios/06-testes-de-contrato.md).

## Exercícios

- [Exercício 01 — Contratos da PetCare API](exercicios/01-contratos-da-petcare-api.md)
- [Exercício 02 — Erros da PetCare API](exercicios/02-erros-da-petcare-api.md)
- [Exercício 03 — Listagens da PetCare API](exercicios/03-listagens-da-petcare-api.md)
- [Exercício 04 — Aprovação Idempotente](exercicios/04-aprovacao-idempotente.md)
- [Exercício 05 — Contrato de Webhook](exercicios/05-webhook-para-o-tutor.md)
- [Exercício 06 — Testes de Contrato](exercicios/06-testes-de-contrato.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Evolua a `petcare-api` construída no módulo 10 para uma API com design profissional:

1. Defina recursos principais, operações e convenções de nomes para pets, atendimentos e orçamentos.
2. Escreva contratos de request e response para cada recurso.
3. Documente endpoints principais com OpenAPI.
4. Padronize erros de validação, não encontrado, conflito e falha interna.
5. Adicione paginação, filtros e ordenação à listagem de atendimentos já existente.
6. Defina uma regra de backward compatibility para a API.
7. Decida se a API precisa ou não de versionamento.
8. Torne a aprovação de orçamento idempotente.
9. Avalie e documente, como prática exploratória, um contrato de webhook para um serviço externo de notificações.
10. Crie um checklist de API governance.
11. Escreva testes de contrato introdutórios para validar respostas principais.

A [Atividade Final do Módulo](exercicios/atividade-final-modulo.md) consolida essas melhorias e prepara a `petcare-api` para receber autenticação, autorização e segurança no módulo 12.

## O Que Entra e O Que Sai Deste Módulo

**O que entra do módulo anterior:**

- `petcare-api` em Node.js e TypeScript, com endpoints para pets, atendimentos e orçamentos;
- configuração, CLI, health check e logs estruturados;
- schema, migrations e queries do diretório `database/`;
- OpenAPI introdutória e transaction de aprovação de orçamento.

**O que sai deste módulo:**

- `petcare-api` com contratos refinados e documentação OpenAPI consistente;
- formato de erros padronizado aplicado nos endpoints;
- listagem de atendimentos paginada, filtrável e ordenável;
- operação de aprovação de orçamento idempotente;
- decisão e contrato exploratório de webhook, sem exigir sua implementação;
- checklist de API governance;
- testes de contrato introdutórios;
- decisão documentada sobre backward compatibility e versionamento.

**Onde isso será retomado:**

- no módulo 12, a API receberá autenticação, autorização e controles de segurança sobre os contratos já definidos;
- no módulo 13A, os testes de contrato ganharão profundidade junto com a estratégia de testes;
- no módulo 13B, logs, métricas e tracing serão aplicados sobre os contratos e erros padronizados;
- no módulo 16, webhooks e processamento assíncrono poderão ser implementados com maior profundidade.

## O Que Revisar Antes de Avançar

- HTTP, métodos, headers, status codes e cache.
- REST, JSON APIs e OpenAPI introdutório.
- Tratamento de erros em TypeScript.
- Validação no frontend e no backend.
- Modelagem de dados, indexes e transactions.
- Failure modes, retries, logs e operações assíncronas.
- Funcionamento da `petcare-api` construída no módulo 10.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo API Design Profissional de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina design de APIs, contratos, OpenAPI na prática, backward compatibility, versionamento, erros padronizados, paginação, filtros, ordenação, idempotência, webhooks, API governance e contract testing.
- Objetivo do módulo: Quero sair de criar endpoints isolados para desenhar APIs consistentes, evolutivas e fáceis de consumir.
- Pré-requisitos: HTTP, TypeScript, frontend consumindo APIs, bancos de dados, backend com Node.js, REST, JSON APIs, OpenAPI introdutório e failure modes.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de desenho de API;
3. perguntas de entrevista para backend iniciante/intermediário;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial da OpenAPI Specification.
- Documentação da MDN sobre HTTP.
- Documentação oficial do framework backend escolhido para prática.
- Documentação oficial das ferramentas de teste escolhidas para prática.
- Guias de estilo de APIs públicas de empresas e comunidades confiáveis.

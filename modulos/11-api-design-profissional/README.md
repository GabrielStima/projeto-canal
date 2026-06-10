<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# API Design Profissional

</div>

Este módulo marca a passagem de "eu sei criar endpoints" para "eu sei desenhar APIs que outras pessoas conseguem consumir, manter e evoluir". Até aqui, você estudou HTTP, frontend consumindo APIs, bancos de dados, backend com Node.js, REST, JSON APIs, GraphQL e OpenAPI em nível introdutório.

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

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 11.00 | [API Design Profissional](11.00-api-design-profissional.md) | Guarda-chuva | Rascunho |
| 11.01 | [Design de APIs](11.01-design-de-apis.md) | Específica ampla | Rascunho |
| 11.02 | [Contratos de API](11.02-contratos-de-api.md) | Específica | Rascunho |
| 11.03 | [OpenAPI na Prática](11.03-openapi-na-pratica.md) | Específica prática | Rascunho |
| 11.04 | [Backward Compatibility](11.04-backward-compatibility.md) | Específica | Rascunho |
| 11.05 | [Versionamento de API](11.05-versionamento-de-api.md) | Específica | Rascunho |
| 11.06 | [Erros Padronizados](11.06-erros-padronizados.md) | Específica prática | Rascunho |
| 11.07 | [Paginação](11.07-paginacao.md) | Específica prática | Rascunho |
| 11.08 | [Filtros](11.08-filtros.md) | Específica prática | Rascunho |
| 11.09 | [Ordenação](11.09-ordenacao.md) | Específica prática | Rascunho |
| 11.10 | [Idempotência](11.10-idempotencia.md) | Específica | Rascunho |
| 11.11 | [Webhooks](11.11-webhooks.md) | Específica prática | Rascunho |
| 11.12 | [API Governance](11.12-api-governance.md) | Guarda-chuva curta | Rascunho |
| 11.13 | [Contract Testing](11.13-contract-testing.md) | Específica introdutória/prática | Rascunho |
| 11.14 | [Projeto Prático: Design Profissional de uma API](11.14-projeto-pratico-design-profissional-de-uma-api.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Evolua a API do painel de estudos criada no módulo 10 para uma API com design profissional:

1. Defina recursos principais, operações e convenções de nomes.
2. Escreva contratos de request e response para aulas, tags, usuários e progresso.
3. Documente endpoints principais com OpenAPI.
4. Padronize erros de validação, autenticação simulada, não encontrado e conflito.
5. Adicione paginação, filtros e ordenação nas listagens.
6. Defina uma regra de backward compatibility.
7. Decida se a API precisa ou não de versionamento.
8. Torne uma operação crítica idempotente.
9. Desenhe um webhook para mudança de progresso do aluno.
10. Crie um checklist de API governance.
11. Escreva testes de contrato introdutórios para validar respostas principais.

## O Que Revisar Antes de Avançar

- HTTP, métodos, headers, status codes e cache.
- REST, JSON APIs e OpenAPI introdutório.
- Tratamento de erros em TypeScript.
- Validação no frontend e no backend.
- Modelagem de dados, indexes e transactions.
- Failure modes, retries, logs e operações assíncronas.

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

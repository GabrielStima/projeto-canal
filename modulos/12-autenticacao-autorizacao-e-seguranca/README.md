<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Autenticação, Autorização e Segurança

</div>

Este módulo organiza os fundamentos de segurança que aparecem quando uma aplicação deixa de ser apenas uma API funcionando e passa a lidar com identidade, permissão, dados sensíveis, sessões, tokens, browsers, banco de dados e abuso.

A ideia não é transformar segurança em uma lista de truques. O objetivo é aprender a pensar em risco: quem está fazendo a requisição, o que essa pessoa pode fazer, quais dados estão expostos, como uma falha pode ser explorada e quais proteções precisam existir desde o desenho da aplicação.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- diferenciar autenticação, autorização e segurança;
- explicar fluxos básicos de login com senha, sessão, cookie e token;
- armazenar senhas sem guardar a senha original;
- entender quando JWT ajuda e quando complica;
- reconhecer o papel de OAuth em integrações e login federado;
- proteger aplicações contra riscos comuns como CSRF, XSS e SQL injection;
- configurar CORS com mais clareza;
- aplicar rate limiting em pontos sensíveis;
- desenhar APIs com controles mínimos de segurança.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu HTTP, frontend, TypeScript, Next.js, bancos de dados, backend com Node.js e design profissional de APIs. Isso prepara o terreno para construir aplicações reais, mas aplicações reais quase sempre precisam responder perguntas que não aparecem em exemplos pequenos:

- quem é este usuário?
- como provar que ele está autenticado?
- o que ele pode acessar?
- como guardar credenciais?
- como impedir que outra página abuse da sessão dele?
- como reduzir impacto de entrada maliciosa?
- como proteger endpoints contra abuso?

Segurança aparece aqui porque depende de tudo que veio antes: HTTP, headers, cookies, estado, banco de dados, validação, contratos de API, erros, idempotência e failure modes.

## Pré-requisitos

- Entender HTTP, headers, cookies, status codes, request, response e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Entender formulários, validação, chamadas de API e estado no frontend.
- Ter estudado autenticação introdutória no contexto de Next.js.
- Entender bancos de dados, modelagem, integridade, transactions e segurança básica.
- Saber criar APIs backend e entender REST, JSON APIs, OpenAPI, logging e failure modes.
- Ter estudado contratos, erros padronizados, idempotência e API governance.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 12.00 | [Autenticação, Autorização e Segurança](12.00-autenticacao-autorizacao-e-seguranca.md) | Guarda-chuva | Rascunho |
| 12.01 | [Segurança na Web](12.01-seguranca-na-web.md) | Guarda-chuva curta | Rascunho |
| 12.02 | [Hashing de Senhas](12.02-hashing-de-senhas.md) | Específica | Rascunho |
| 12.03 | [Algoritmos de Hashing](12.03-algoritmos-de-hashing.md) | Específica conceitual | Rascunho |
| 12.04 | [Autenticação Básica](12.04-autenticacao-basica.md) | Específica prática | Rascunho |
| 12.05 | [Sessões](12.05-sessoes.md) | Específica | Rascunho |
| 12.06 | [Autenticação via Cookie](12.06-autenticacao-via-cookie.md) | Específica prática | Rascunho |
| 12.07 | [CSRF](12.07-csrf.md) | Específica | Rascunho |
| 12.08 | [Autenticação via Token](12.08-autenticacao-via-token.md) | Específica prática | Rascunho |
| 12.09 | [JWT](12.09-jwt.md) | Específica | Rascunho |
| 12.10 | [Autorização](12.10-autorizacao.md) | Específica prática | Rascunho |
| 12.11 | [OAuth](12.11-oauth.md) | Específica conceitual/prática | Rascunho |
| 12.12 | [CORS](12.12-cors.md) | Específica | Rascunho |
| 12.13 | [XSS](12.13-xss.md) | Específica | Rascunho |
| 12.14 | [SQL Injection](12.14-sql-injection.md) | Específica prática | Rascunho |
| 12.15 | [Rate Limiting](12.15-rate-limiting.md) | Específica prática | Rascunho |
| 12.16 | [Segurança em APIs](12.16-seguranca-em-apis.md) | Guarda-chuva curta | Rascunho |
| 12.17 | [Projeto Prático: Autenticação, Autorização e Segurança em uma API](12.17-projeto-pratico-autenticacao-autorizacao-e-seguranca-em-uma-api.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em 5 blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Visão geral da segurança** · aulas [12.00–12.01]
Introdução aos conceitos de autenticação, autorização e segurança na web.
Pré-requisito: nenhum (ponto de entrada do módulo).

Ao concluir o bloco, faça o [Exercício 01 — Mapa de Riscos da API](exercicios/01-mapa-de-riscos-da-api.md). Ele será usado como referência nas práticas seguintes.

**Bloco B — Identidade e sessão** · aulas [12.02–12.06]
Hashing de senhas, algoritmos, autenticação básica, sessões e cookies seguros.
Pré-requisito: Bloco A.

Depois de hashing e autenticação básica, faça o [Exercício 02 — Cadastro e Hashing](exercicios/02-cadastro-e-hashing.md). Ao concluir cookies, faça o [Exercício 03 — Login, Cookie e CSRF](exercicios/03-login-cookie-e-csrf.md).

**Bloco C — Tokens e permissões** · aulas [12.08–12.11]
Autenticação via token, JWT, autorização e OAuth.
Pré-requisito: Bloco B.

Depois de JWT, faça o [Exercício 04 — Sessão, Token e JWT](exercicios/04-sessao-token-e-jwt.md). Ao concluir autorização, faça o [Exercício 05 — Autorização por Papel e Recurso](exercicios/05-autorizacao-por-recurso.md). O [Exercício 06 — OAuth e Login Delegado](exercicios/06-oauth-e-login-delegado.md) é exploratório e não exige integração com um provedor real.

**Bloco D — Riscos e proteções da web** · aulas [12.07, 12.12–12.16]
CSRF, CORS, XSS, SQL injection, rate limiting e segurança em APIs.
Pré-requisito: Blocos B e C.

Depois de SQL injection, faça o [Exercício 07 — CORS, XSS e SQL Injection](exercicios/07-cors-xss-e-sql-injection.md). Ao concluir rate limiting e segurança em APIs, faça o [Exercício 08 — Rate Limiting e Revisão da API](exercicios/08-rate-limiting-e-revisao-da-api.md).

**Bloco E — Síntese prática** · aula [12.17]
Projeto prático que integra autenticação, autorização e controles de segurança na API.
Pré-requisito: Blocos A a D.

Finalize com a [Atividade Final do Módulo](exercicios/atividade-final-modulo.md), reutilizando as decisões e implementações dos exercícios anteriores.

> Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

- [Exercício 01 — Mapa de Riscos da API](exercicios/01-mapa-de-riscos-da-api.md)
- [Exercício 02 — Cadastro e Hashing](exercicios/02-cadastro-e-hashing.md)
- [Exercício 03 — Login, Cookie e CSRF](exercicios/03-login-cookie-e-csrf.md)
- [Exercício 04 — Sessão, Token e JWT](exercicios/04-sessao-token-e-jwt.md)
- [Exercício 05 — Autorização por Papel e Recurso](exercicios/05-autorizacao-por-recurso.md)
- [Exercício 06 — OAuth e Login Delegado](exercicios/06-oauth-e-login-delegado.md)
- [Exercício 07 — CORS, XSS e SQL Injection](exercicios/07-cors-xss-e-sql-injection.md)
- [Exercício 08 — Rate Limiting e Revisão da API](exercicios/08-rate-limiting-e-revisao-da-api.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você evoluirá a API do **PetCare OS** para transformá-la em uma aplicação com controles reais de segurança.

1. Modele usuários e credenciais para o Módulo Clínico e Portal do Tutor.
2. Implemente cadastro e login com hash de senha seguro.
3. Escolha uma estratégia de sessão (cookie ou token) e justifique.
4. Proteja rotas de prontuário e orçamento, garantindo que apenas usuários autenticados acessem.
5. Crie regras de autorização RBAC (Recepcionista, Clínico, Administrador e Tutor).
6. Configure cookies com atributos seguros (`HttpOnly`, `Secure`, `SameSite`).
7. Explique e mitigue possíveis ataques de CSRF no fluxo escolhido.
8. Garanta que anotações clínicas não renderizem XSS.
9. Utilize parâmetros no banco para evitar SQL injection na busca de pets.
10. Adicione rate limiting no login do Portal do Tutor.
11. Consolide tudo em um checklist de segurança para as próximas evoluções do PetCare OS.

As práticas são cumulativas, mas não obrigam uma tecnologia específica. Você pode usar o framework, o banco e a biblioteca de autenticação que já fazem parte da sua API. Quando uma integração externa não for necessária para consolidar o conceito, a entrega será um diagrama ou uma decisão técnica justificada.

## O Que Entra e O Que Sai Deste Módulo

**O que entra dos módulos anteriores:**

- a `petcare-api` em Node.js e TypeScript;
- contratos OpenAPI, erros padronizados e operações idempotentes;
- endpoints de pets, atendimentos e orçamentos;
- banco de dados, migrations e consultas já utilizadas pela API;
- frontend ou cliente HTTP capaz de consumir os endpoints.

**O que sai deste módulo:**

- mapa de riscos dos endpoints principais;
- cadastro com armazenamento seguro de senha;
- login com uma estratégia de autenticação escolhida e documentada;
- regras de autorização por papel e por propriedade do recurso;
- configuração de CORS e proteção contra CSRF coerentes com a estratégia escolhida;
- correções verificáveis para riscos de XSS e SQL injection;
- rate limiting em endpoint sensível;
- checklist de segurança por endpoint.

**Onde isso será retomado:**

- no módulo 13A, os fluxos de sucesso e rejeição serão protegidos por testes automatizados;
- no módulo 13B, eventos de autenticação, autorização e abuso serão observados com logs e métricas;
- nos módulos de arquitetura e operação, as decisões de identidade e segurança serão preservadas e revisadas conforme o sistema crescer.

## O Que Revisar Antes de Avançar

- HTTP, headers, cookies, cache e estado.
- Formulários, validação e chamadas de API.
- TypeScript, tratamento de erros e dados JSON.
- Bancos de dados, constraints, transactions e acesso por ORM.
- REST, contratos de API e erros padronizados.
- Logging, failure modes e idempotência.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Autenticação, Autorização e Segurança de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina segurança na web, autenticação, senhas, sessões, cookies, tokens, JWT, autorização, OAuth, CORS, CSRF, XSS, SQL injection, rate limiting e segurança em APIs.
- Objetivo do módulo: Quero conseguir construir uma API com login, permissão e proteções básicas sem confundir os conceitos.
- Pré-requisitos: HTTP, TypeScript, frontend, Next.js introdutório, bancos de dados, backend com Node.js, API design, contratos, erros padronizados e failure modes.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de desenho de autenticação e autorização;
3. perguntas de entrevista para backend iniciante/intermediário;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- OWASP Cheat Sheet Series.
- MDN Web Docs sobre HTTP, cookies, CORS e segurança web.
- RFC 7519 e RFC 8725 sobre JWT.
- RFC 6749 e RFC 9700 sobre OAuth 2.0 e práticas atuais de segurança.
- Documentação oficial do framework backend escolhido para prática.
- Documentação oficial do banco de dados e ORM escolhidos para prática.

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
| 12.00 | [Autenticação, Autorização e Segurança](12.00-autenticacao-autorizacao-e-seguranca.md) | Guarda-chuva | Revisada |
| 12.01 | [Segurança na Web](12.01-seguranca-na-web.md) | Guarda-chuva curta | Revisada |
| 12.02 | [Hashing de Senhas](12.02-hashing-de-senhas.md) | Específica | Revisada |
| 12.03 | [Algoritmos de Hashing](12.03-algoritmos-de-hashing.md) | Específica conceitual | Revisada |
| 12.04 | [Autenticação Básica](12.04-autenticacao-basica.md) | Específica prática | Revisada |
| 12.05 | [Sessões](12.05-sessoes.md) | Específica | Revisada |
| 12.06 | [Autenticação via Cookie](12.06-autenticacao-via-cookie.md) | Específica prática | Revisada |
| 12.07 | [CSRF](12.07-csrf.md) | Específica | Revisada |
| 12.08 | [Autenticação via Token](12.08-autenticacao-via-token.md) | Específica prática | Revisada |
| 12.09 | [JWT](12.09-jwt.md) | Específica | Revisada |
| 12.10 | [Autorização](12.10-autorizacao.md) | Específica prática | Revisada |
| 12.11 | [OAuth](12.11-oauth.md) | Específica conceitual/prática | Revisada |
| 12.12 | [CORS](12.12-cors.md) | Específica | Revisada |
| 12.13 | [XSS](12.13-xss.md) | Específica | Revisada |
| 12.14 | [SQL Injection](12.14-sql-injection.md) | Específica prática | Revisada |
| 12.15 | [Rate Limiting](12.15-rate-limiting.md) | Específica prática | Revisada |
| 12.16 | [Segurança em APIs](12.16-seguranca-em-apis.md) | Guarda-chuva curta | Revisada |
| 12.17 | [Projeto Prático: Autenticação, Autorização e Segurança em uma API](12.17-projeto-pratico-autenticacao-autorizacao-e-seguranca-em-uma-api.md) | Síntese prática | Revisada |

## Exercícios

- [Exercício 01 — Cadastro e Hashing](exercicios/01-cadastro-hashing.md)
- [Exercício 02 — Sessão e Login](exercicios/02-sessao-login.md)
- [Exercício 03 — Autorização e RBAC](exercicios/03-autorizacao-rbac.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você evoluirá a API do **PetCare OS** para transformá-la em uma aplicação com controles reais de segurança (Marco de Integração N4).

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

# Autenticacao, Autorizacao e Seguranca

Este modulo organiza os fundamentos de seguranca que aparecem quando uma aplicacao deixa de ser apenas uma API funcionando e passa a lidar com identidade, permissao, dados sensiveis, sessoes, tokens, browsers, banco de dados e abuso.

A ideia nao e transformar seguranca em uma lista de truques. O objetivo e aprender a pensar em risco: quem esta fazendo a requisicao, o que essa pessoa pode fazer, quais dados estao expostos, como uma falha pode ser explorada e quais protecoes precisam existir desde o desenho da aplicacao.

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- diferenciar autenticacao, autorizacao e seguranca;
- explicar fluxos basicos de login com senha, sessao, cookie e token;
- armazenar senhas sem guardar a senha original;
- entender quando JWT ajuda e quando complica;
- reconhecer o papel de OAuth em integracoes e login federado;
- proteger aplicacoes contra riscos comuns como CSRF, XSS e SQL injection;
- configurar CORS com mais clareza;
- aplicar rate limiting em pontos sensiveis;
- desenhar APIs com controles minimos de seguranca.

## Por Que Este Modulo Existe

Nos modulos anteriores, voce aprendeu HTTP, frontend, TypeScript, Next.js, bancos de dados, backend com Node.js e design profissional de APIs. Isso prepara o terreno para construir aplicacoes reais, mas aplicacoes reais quase sempre precisam responder perguntas que nao aparecem em exemplos pequenos:

- quem e este usuario?
- como provar que ele esta autenticado?
- o que ele pode acessar?
- como guardar credenciais?
- como impedir que outra pagina abuse da sessao dele?
- como reduzir impacto de entrada maliciosa?
- como proteger endpoints contra abuso?

Seguranca aparece aqui porque depende de tudo que veio antes: HTTP, headers, cookies, estado, banco de dados, validacao, contratos de API, erros, idempotencia e failure modes.

## Pre-requisitos

- Entender HTTP, headers, cookies, status codes, request, response e estado.
- Saber escrever JavaScript moderno e TypeScript.
- Entender formularios, validacao, chamadas de API e estado no frontend.
- Ter estudado autenticacao introdutoria no contexto de Next.js.
- Entender bancos de dados, modelagem, integridade, transactions e seguranca basica.
- Saber criar APIs backend e entender REST, JSON APIs, OpenAPI, logging e failure modes.
- Ter estudado contratos, erros padronizados, idempotencia e API governance.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 12.00 | Autenticacao, Autorizacao e Seguranca | Guarda-chuva | Rascunho |
| 12.01 | [Seguranca na Web](12.01-seguranca-na-web.md) | Guarda-chuva curta | Rascunho |
| 12.02 | [Hashing de Senhas](12.02-hashing-de-senhas.md) | Especifica | Rascunho |
| 12.03 | [Algoritmos de Hashing](12.03-algoritmos-de-hashing.md) | Especifica conceitual | Rascunho |
| 12.04 | [Autenticacao Basica](12.04-autenticacao-basica.md) | Especifica pratica | Rascunho |
| 12.05 | [Sessoes](12.05-sessoes.md) | Especifica | Rascunho |
| 12.06 | [Autenticacao via Cookie](12.06-autenticacao-via-cookie.md) | Especifica pratica | Rascunho |
| 12.07 | [CSRF](12.07-csrf.md) | Especifica | Rascunho |
| 12.08 | [Autenticacao via Token](12.08-autenticacao-via-token.md) | Especifica pratica | Rascunho |
| 12.09 | [JWT](12.09-jwt.md) | Especifica | Rascunho |
| 12.10 | [Autorizacao](12.10-autorizacao.md) | Especifica pratica | Rascunho |
| 12.11 | [OAuth](12.11-oauth.md) | Especifica conceitual/pratica | Rascunho |
| 12.12 | [CORS](12.12-cors.md) | Especifica | Rascunho |
| 12.13 | [XSS](12.13-xss.md) | Especifica | Rascunho |
| 12.14 | [SQL Injection](12.14-sql-injection.md) | Especifica pratica | Rascunho |
| 12.15 | [Rate Limiting](12.15-rate-limiting.md) | Especifica pratica | Rascunho |
| 12.16 | [Seguranca em APIs](12.16-seguranca-em-apis.md) | Guarda-chuva curta | Rascunho |
| 12.17 | [Projeto Pratico: Autenticacao, Autorizacao e Seguranca em uma API](12.17-projeto-pratico-autenticacao-autorizacao-e-seguranca-em-uma-api.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Evolua a API do painel de estudos criada nos modulos anteriores para uma aplicacao com controles basicos de seguranca:

1. Modele usuarios e credenciais.
2. Implemente cadastro e login com hash de senha.
3. Escolha uma estrategia de sessao, cookie ou token.
4. Proteja rotas autenticadas.
5. Crie pelo menos dois niveis de autorizacao.
6. Configure cookies com atributos seguros quando usar cookie.
7. Explique como mitigaria CSRF no fluxo escolhido.
8. Corrija um exemplo vulneravel a XSS.
9. Corrija uma query vulneravel a SQL injection.
10. Adicione rate limiting no login e em um endpoint sensivel.
11. Escreva um checklist de seguranca para a API.

## O Que Revisar Antes de Avancar

- HTTP, headers, cookies, cache e estado.
- Formularios, validacao e chamadas de API.
- TypeScript, tratamento de erros e dados JSON.
- Bancos de dados, constraints, transactions e acesso por ORM.
- REST, contratos de API e erros padronizados.
- Logging, failure modes e idempotencia.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Autenticacao, Autorizacao e Seguranca de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina seguranca na web, autenticacao, senhas, sessoes, cookies, tokens, JWT, autorizacao, OAuth, CORS, CSRF, XSS, SQL injection, rate limiting e seguranca em APIs.
- Objetivo do modulo: Quero conseguir construir uma API com login, permissao e protecoes basicas sem confundir os conceitos.
- Pre-requisitos: HTTP, TypeScript, frontend, Next.js introdutorio, bancos de dados, backend com Node.js, API design, contratos, erros padronizados e failure modes.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos de desenho de autenticacao e autorizacao;
3. perguntas de entrevista para backend iniciante/intermediario;
4. exemplos de aplicacao em projetos reais;
5. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- OWASP Cheat Sheet Series.
- MDN Web Docs sobre HTTP, cookies, CORS e seguranca web.
- RFC 7519 e RFC 8725 sobre JWT.
- RFC 6749 e RFC 9700 sobre OAuth 2.0 e praticas atuais de seguranca.
- Documentacao oficial do framework backend escolhido para pratica.
- Documentacao oficial do banco de dados e ORM escolhidos para pratica.

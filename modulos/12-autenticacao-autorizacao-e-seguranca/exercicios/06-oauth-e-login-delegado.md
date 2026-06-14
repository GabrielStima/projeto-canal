# Exercício 06 — OAuth e Login Delegado

## Antes de começar

Esta prática é exploratória. Ela não adiciona login social como requisito do PetCare OS e não exige conta, SDK ou integração com um provedor externo.

Você já conhece tokens, autorização e redirecionamentos HTTP. Agora vai analisar quando uma autorização delegada seria útil.

## Sua tarefa

Desenhe um fluxo de Authorization Code com PKCE para um aplicativo que precisa obter dados básicos de identidade de um provedor externo.

Identifique no diagrama:

- usuário;
- cliente;
- authorization server;
- resource server;
- redirect URI;
- authorization code;
- access token;
- escopos;
- onde PKCE participa.

Depois, responda:

1. por que a aplicação não deve receber a senha do provedor;
2. quais escopos mínimos seriam suficientes;
3. como validar a redirect URI;
4. por que OAuth sozinho não deve ser descrito como protocolo de login;
5. quando manter cadastro e login próprios seria mais simples.

## O que você vai produzir

- diagrama ou sequência numerada do fluxo;
- lista de escopos mínimos;
- análise curta de benefícios, riscos e situações em que a integração não compensa.

## Critérios de conclusão

- Os participantes do fluxo estão corretamente separados.
- O authorization code não é confundido com access token.
- PKCE aparece como proteção do fluxo de troca do código.
- Os escopos seguem mínimo privilégio.
- OAuth e OpenID Connect não aparecem como sinônimos.
- A integração é tratada como alternativa, não como requisito inevitável.

## Como este trabalho continuará

O resultado não precisa entrar na atividade final. Guarde-o como referência para futuras integrações com provedores externos.

## Corrija Sua Atividade Com IA

```text
Cenário: Desenhei um fluxo exploratório de OAuth 2.0 Authorization Code com PKCE. Identifiquei usuário, cliente, authorization server, resource server, redirect URI, código, token e escopos.

Tarefa: Revise o diagrama e minha análise sobre quando usar autorização delegada.

Critérios de correção:
1. Os participantes e suas responsabilidades estão corretos?
2. Authorization code e access token não foram confundidos?
3. PKCE e redirect URI foram posicionados de forma coerente?
4. Os escopos seguem mínimo privilégio?
5. OAuth foi diferenciado de OpenID Connect?
6. A análise reconhece quando login próprio é mais simples?

Aponte primeiro os acertos. Em seguida, indique imprecisões e faça perguntas ou dê dicas para eu corrigir o fluxo antes de mostrar uma versão completa.

[COLE SUA RESPOSTA AQUI]
```

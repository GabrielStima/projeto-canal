# Exercício 03 — Login, Cookie e CSRF

## O que você já sabe

Sua API já consegue cadastrar uma identidade e armazenar o hash da senha. Agora ela precisa reconhecer o usuário em requisições futuras.

Neste exercício, use uma sessão mantida pelo servidor e um cookie de sessão. Essa implementação existe para praticar sessões, cookies e CSRF. No exercício seguinte, você comparará essa escolha com tokens.

## Sua tarefa

Implemente ou descreva detalhadamente:

1. `POST /api/auth/login`;
2. criação de uma sessão com identificador imprevisível e expiração;
3. envio do identificador em cookie;
4. `POST /api/auth/logout`, invalidando a sessão no servidor;
5. proteção contra CSRF para uma operação que altera dados.

O cookie deve considerar `HttpOnly`, `Secure`, `SameSite`, `Path` e expiração. Justifique os valores escolhidos para ambiente local e produção.

Para a proteção contra CSRF, selecione uma estratégia coerente com o seu cenário, como:

- `SameSite` combinado com verificação de origem;
- token anti-CSRF;
- outra estratégia explicada e verificável.

Não use CORS como substituto de proteção contra CSRF.

## O que você vai produzir

- fluxo de login e logout;
- estrutura de armazenamento da sessão;
- cabeçalho `Set-Cookie` ou configuração equivalente;
- proteção aplicada a uma rota de mutação;
- atualização do mapa de riscos.

## Critérios de conclusão

- Usuário inexistente e senha incorreta produzem resposta pública equivalente.
- A senha é comparada pela função da biblioteca de hashing.
- O identificador de sessão é imprevisível, expira e pode ser revogado.
- Logout invalida a sessão no servidor.
- O cookie não fica acessível ao JavaScript do browser.
- A mitigação de CSRF protege uma operação que altera estado.

## Como este trabalho continuará

No próximo exercício, você comparará esta sessão com tokens opacos e JWT. A atividade final poderá manter a sessão ou adotar outra estratégia, desde que a decisão seja justificada.

## Corrija Sua Atividade Com IA

```text
Cenário: Implementei login e logout em uma API Node.js/TypeScript usando sessão no servidor e cookie de sessão. Também protegi uma rota de mutação contra CSRF.

Tarefa: Revise o fluxo, a configuração do cookie e a mitigação de CSRF.

Critérios de correção:
1. O login evita enumeração de contas e compara a senha de forma correta?
2. A sessão possui identificador imprevisível, expiração e revogação?
3. O logout invalida a sessão no servidor?
4. HttpOnly, Secure, SameSite, Path e expiração foram usados de forma coerente?
5. A proteção contra CSRF é adequada para uma autenticação baseada em cookie?
6. CORS não foi tratado como defesa suficiente contra CSRF?

Primeiro destaque os acertos e aponte riscos ou imprecisões. Depois dê dicas para eu corrigir cada problema. Não apresente uma solução completa antes da minha tentativa de ajuste.

[COLE SUA RESPOSTA AQUI]
```

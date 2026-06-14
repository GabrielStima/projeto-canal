# Exercício 04 — Sessão, Token e JWT

## O que você já sabe

Você implementou uma sessão mantida pelo servidor e viu como cookies afetam o risco de CSRF. Agora precisa avaliar alternativas sem assumir que JWT é sempre a evolução natural.

Esta é uma prática de análise e decisão. Você não precisa implementar três estratégias.

## Sua tarefa

Compare estas opções para dois clientes da `petcare-api`:

- Portal do Tutor executado no browser;
- aplicativo interno de estoque ou cliente de API que envia credenciais explicitamente.

Opções:

1. sessão no servidor com cookie;
2. token opaco;
3. JWT.

Monte uma tabela avaliando:

- onde o estado fica;
- como a credencial é enviada;
- expiração;
- revogação;
- risco em caso de vazamento;
- impacto de XSS e CSRF;
- complexidade operacional;
- necessidade real de claims.

Depois, escolha uma estratégia para a atividade final e registre a decisão em uma seção do `docs/security-review.md` ou em uma pequena decisão técnica.

Se escolher JWT, defina as claims mínimas e as validações obrigatórias. Não inclua dados pessoais ou clínicos no payload.

## O que você vai produzir

- tabela comparativa;
- decisão técnica com contexto, escolha, consequências e alternativa descartada;
- atualização do mapa de riscos;
- implementação opcional apenas se você decidir substituir a sessão criada anteriormente.

## Critérios de conclusão

- A decisão considera o tipo de cliente e não apenas popularidade.
- Revogação e expiração aparecem separadamente.
- JWT não é tratado como criptografia nem como autorização automática.
- O local de armazenamento do cliente é avaliado como parte do risco.
- A alternativa descartada continua documentada com seus benefícios.

## Como este trabalho continuará

A estratégia escolhida será usada na atividade final e nos testes do módulo 13A. Trocar a implementação é opcional; justificar a escolha é obrigatório.

## Corrija Sua Atividade Com IA

```text
Cenário: Comparei sessão com cookie, token opaco e JWT para um portal web e um cliente de API. Depois escolhi uma estratégia de autenticação para continuar o projeto.

Tarefa: Avalie minha comparação e a decisão técnica.

Critérios de correção:
1. Estado, envio, expiração e revogação foram comparados corretamente?
2. Os riscos de XSS e CSRF foram relacionados ao modo de armazenamento e envio?
3. JWT foi tratado como token assinado, não como payload secreto?
4. A escolha considera o tipo de cliente e a necessidade real de claims?
5. As consequências e a alternativa descartada foram registradas?

Destaque os acertos, identifique imprecisões ou suposições frágeis e ofereça perguntas e dicas que me ajudem a revisar a decisão. Só proponha uma decisão completa depois da minha nova tentativa.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 02 — Tempo Real, Reconexão e Estado

## O que você já tem

Você escolheu uma técnica de comunicação para cada cenário e sabe que conexões podem cair ou perder atualizações.

## Tarefa

Escolha a agenda da recepção ou outro painel do PetCare OS e desenhe um pequeno protótipo com short polling, SSE ou WebSocket.

Inclua:

1. estado inicial obtido do servidor;
2. atualização posterior;
3. indicador visual de conexão ou atualização;
4. tratamento de erro sem apagar o último estado válido;
5. estratégia de reconexão com intervalo limitado;
6. nova sincronização do estado após reconectar;
7. regra para impedir que um usuário receba dados sem autorização.

Você pode usar pseudocódigo quando o projeto atual não tiver uma interface pronta. Explique como testaria uma desconexão.

## O que você vai produzir

Um fluxo de atualização capaz de recuperar o estado correto depois de uma falha de conexão.

## Corrija Sua Atividade Com IA

```text
Cenário: Implementei ou desenhei um painel atualizado por short polling, SSE ou WebSocket. O fluxo possui estado inicial, atualização, indicação de conexão, tratamento de erro, reconexão, sincronização posterior e autorização.

Tarefa: Revise meu fluxo de estado e reconexão.

Critérios de correção:
1. O cliente obtém um estado inicial confiável?
2. Uma falha preserva o último estado válido e informa o usuário?
3. A reconexão é limitada e seguida por nova sincronização?
4. Atualizações perdidas ou fora de ordem foram consideradas?
5. A autorização protege tanto a conexão quanto os dados enviados?
6. O teste de desconexão demonstra recuperação real?

Comece pelos acertos. Depois indique imprecisões e riscos. Dê dicas graduais antes de propor uma implementação completa.

[COLE SUA RESPOSTA AQUI]
```

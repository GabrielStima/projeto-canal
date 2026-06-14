# Exercício 03 — Job Assíncrono e Status

## O que você já tem

Você possui uma operação candidata a processamento assíncrono e uma decisão sobre como o cliente acompanhará seu estado.

## Tarefa

Implemente uma primeira versão sem broker externo:

1. uma rota que valida a solicitação e responde `202 Accepted`;
2. um identificador único para o job;
3. estados `pendente`, `processando`, `concluido` e `falhou`;
4. um processador separado da rota, mesmo que execute no mesmo projeto;
5. uma rota de consulta de status;
6. um resultado ou erro seguro para o usuário;
7. testes para criação e consulta do job.

Não faça a requisição esperar o trabalho terminar. Uma estrutura em memória é suficiente para este exercício, desde que você registre suas limitações.

## O que você vai produzir

O primeiro fluxo executável de job assíncrono, que será fortalecido com fila e recuperação nos próximos exercícios.

## Corrija Sua Atividade Com IA

```text
Cenário: Implementei um job assíncrono sem broker externo. A API valida a solicitação, responde 202 com um identificador, processa o trabalho separadamente e oferece uma rota de status com estados explícitos.

Tarefa: Revise meu contrato, código ou pseudocódigo e testes.

Critérios de correção:
1. A resposta 202 ocorre antes da conclusão do trabalho?
2. O identificador permite consultar apenas o job correto?
3. As transições de estado são válidas e compreensíveis?
4. Erros internos não vazam dados sensíveis?
5. O processador está separado da responsabilidade HTTP?
6. Os testes cobrem criação, consulta e falha?
7. As limitações da solução em memória foram reconhecidas?

Mostre primeiro os acertos. Depois aponte imprecisões e ofereça dicas antes de escrever uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 04 — Aprovação Idempotente

## Objetivo

Proteger a aprovação de orçamento contra requisições repetidas e concorrentes.

## O Que Você Já Possui

- uma operação persistente de aprovação de orçamento;
- transaction para manter orçamento e atendimento consistentes;
- formato de erro padronizado;
- conhecimento de retries e failure modes.

Esta atividade é **obrigatória para continuidade**.

## Sua Tarefa

1. Defina o contrato de `POST /budgets/{budgetId}/approval`.
2. Exija o header `Idempotency-Key`.
3. Registre a chave, uma identificação da operação, o status do processamento e a resposta produzida.
4. Garanta que:
   - a primeira requisição executa a aprovação;
   - uma repetição com a mesma chave e o mesmo conteúdo devolve o resultado anterior;
   - a mesma chave com conteúdo diferente gera conflito;
   - duas requisições concorrentes não aprovam duas vezes.
5. Defina por quanto tempo o registro precisa existir.
6. Atualize a OpenAPI e documente respostas de sucesso, repetição e conflito.

Não implemente cobrança real. O objetivo é proteger a mudança de estado já existente.

## O Que Você Vai Produzir

- operação idempotente implementada;
- armazenamento persistente das chaves;
- contrato OpenAPI atualizado;
- evidência de primeira chamada, repetição e conflito.

## Critérios de Conclusão

- a chave é gerada pelo consumidor;
- a transaction protege a regra e o registro de idempotência;
- a repetição devolve resultado consistente;
- reutilizar a chave para outra requisição não é aceito;
- falhas não deixam o orçamento em estado parcialmente aprovado.

Esta operação será validada novamente na atividade final e aprofundada nos módulos de testes e sistemas assíncronos.

## Corrija Sua Atividade Com IA

```text
Estou tornando idempotente a operação POST /budgets/{budgetId}/approval da PetCare API.

O cliente envia Idempotency-Key. A primeira chamada deve aprovar o orçamento dentro de uma transaction e armazenar a chave e a resposta. Uma repetição equivalente deve devolver o resultado anterior. A mesma chave com conteúdo diferente deve gerar conflito. Requisições concorrentes não podem aplicar a aprovação duas vezes.

Critérios de correção:
1. a chave vem do consumidor;
2. o registro de idempotência é persistente;
3. aprovação e registro são coordenados contra concorrência;
4. repetição equivalente tem resultado consistente;
5. reutilização indevida da chave é rejeitada;
6. o contrato define validade da chave e respostas possíveis;
7. não existe cobrança real nem funcionalidade fora do escopo.

Revise minha estratégia e meu código. Primeiro destaque acertos. Depois aponte imprecisões, condições de corrida, estados parciais ou ambiguidades de contrato. Ofereça dicas antes de revelar uma implementação completa.

[COLE SUA RESPOSTA AQUI]
```

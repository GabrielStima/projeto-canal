# Exercício 03 — Retenção, Descarte e Backups

## O Que Você Já Possui

O inventário identifica onde os dados persistem e o fluxo de atendimento mostra quais solicitações podem exigir correção, exportação ou eliminação.

## A Tarefa

Escolha quatro categorias do inventário e adicione uma tabela de retenção a `docs/governanca-dados.md`.

Para cada categoria, defina:

1. evento que inicia a contagem;
2. prazo proposto e responsável por validá-lo;
3. finalidade durante o período;
4. destino ao final: apagar, anonimizar, agregar ou manter mediante justificativa;
5. comportamento em banco, cache, fila, índice, log, exportação e backup;
6. forma de provar que a rotina foi executada;
7. tratamento de falha e repetição segura;
8. exceções temporárias, responsável e data de revisão.

Descreva em pseudocódigo um processo idempotente de descarte. Para backups imutáveis, documente restrição de acesso, expiração, restauração controlada e reaplicação das exclusões, sem prometer remoção física imediata quando isso não for tecnicamente possível.

## O Que Você Vai Produzir

Uma política de retenção vinculada ao inventário e um processo técnico verificável de descarte.

O próximo exercício usará essas categorias para criar um conjunto analítico com menor risco.

## Corrija Sua Atividade Com IA

```text
Cenário: Defini retenção, descarte e tratamento de backups para categorias de dados do PetCare OS.

Tarefa: Revise minha tabela e o processo idempotente de descarte.

Critérios de correção:
1. Cada prazo possui evento inicial, finalidade e responsável pela validação.
2. Banco, logs, caches, filas, índices, exportações e backups foram considerados.
3. Apagar, anonimizar, agregar ou manter são decisões justificadas por categoria.
4. A rotina pode ser repetida com segurança e produz evidência sem expor o dado eliminado.
5. Backups possuem expiração, acesso restrito e procedimento de restauração coerente.
6. Exceções têm responsável, justificativa e data de revisão.

Primeiro destaque meus acertos. Depois aponte promessas difíceis de cumprir ou lacunas técnicas e ofereça dicas. Só apresente uma política completa depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

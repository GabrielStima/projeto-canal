# Atividade Final do Módulo — Camada de Dados do PetCare OS

Esta atividade é obrigatória para seguir ao módulo de backend. Você vai organizar e verificar o trabalho produzido ao longo do módulo, sem começar outro projeto.

## O Que Você Já Possui

Os exercícios anteriores produziram:

- `database/modelo-relacional.md`;
- `database/01-schema.sql`;
- `database/02-seed.sql`;
- `database/03-queries.sql`;
- `database/04-transactions.sql`;
- `database/05-indexes.sql`;
- `database/migrations/001-schema-inicial.sql`;
- `database/migrations/002-prioridade-atendimento.sql`;
- `database/plano-de-recuperacao.md`;
- `database/regras-de-acesso.md`;
- `database/modelo-auditoria-documental.md`;
- `database/decisao-de-persistencia.md`.

Se você não realizou a atividade documental recomendada, registre essa ausência na decisão final. Ela não impede a conclusão quando o banco relacional foi justificado para a primeira versão.

## Sua Tarefa

1. Revise os arquivos e corrija divergências de nomes, tipos e relacionamentos.
2. Em um banco vazio, execute `01-schema.sql`, o seed e as consultas.
3. Teste uma violação de constraint e registre o erro observado.
4. Teste a transaction em um caso de sucesso e em um caso de rollback.
5. Em outro banco vazio, execute as migrations na ordem e depois aplique o seed.
6. Compare o schema criado pelos dois caminhos.
7. Revise índices, segurança, backup e restore.
8. Crie `database/README.md` explicando os dois caminhos de criação e as decisões principais.

## O Que Você Vai Produzir

Uma camada de dados demonstrável com:

- schema relacional;
- dados iniciais;
- consultas verificáveis;
- proteção de integridade;
- transaction;
- índices justificados;
- migrations ordenadas;
- orientações de recuperação e acesso;
- decisão registrada sobre SQL e NoSQL.

## Critérios de Conclusão

- uma pessoa consegue executar os arquivos seguindo `database/README.md`;
- schema e seed executam sem edição manual em um banco vazio;
- migrations e seed executam sem edição manual em outro banco vazio;
- os dois caminhos produzem estruturas compatíveis;
- as consultas retornam dados coerentes;
- constraints rejeitam ao menos um estado inválido;
- a transaction demonstra commit e rollback;
- migrations possuem ordem clara;
- nenhum segredo real foi versionado;
- a decisão de persistência corresponde aos arquivos entregues.

No módulo 10, essa camada será conectada a uma API Node.js. Preserve nomes, regras e consultas; o objetivo será construir acesso por backend, não redesenhar tudo do zero.

## Corrija Sua Atividade Com IA

```text
Estou concluindo a camada de dados do PetCare OS para entregá-la ao próximo módulo, que criará uma API Node.js.

Minha entrega deve conter:
- modelo relacional;
- schema SQL executável;
- seed;
- consultas verificáveis;
- constraints;
- transaction com commit e rollback;
- índices justificados;
- migrations ordenadas;
- plano de backup e restore;
- regras de acesso;
- decisão sobre SQL e NoSQL;
- README com ordem de execução.

Critérios de correção:
1. nomes e tipos devem ser consistentes entre os arquivos;
2. schema e seed devem executar em um banco vazio;
3. migrations e seed devem executar em outro banco vazio;
4. os dois caminhos devem produzir estruturas compatíveis;
5. consultas devem responder perguntas do Portal do Tutor;
6. constraints devem rejeitar estados inválidos;
7. a transaction deve evitar atualização parcial;
8. migrations devem considerar dados existentes;
9. índices devem estar ligados a consultas;
10. nenhum segredo real pode aparecer;
11. a decisão escrita deve corresponder à implementação;
12. o resultado deve estar pronto para ser acessado por uma API no próximo módulo.

Analise minha entrega nesta ordem:
1. destaque os acertos e pontos concluídos corretamente;
2. aponte imprecisões, inconsistências, riscos e itens ausentes;
3. priorize as correções que bloqueiam a execução;
4. dê dicas e exemplos pequenos antes de reescrever arquivos;
5. só apresente uma solução completa depois que eu tentar corrigir.

[COLE SUA RESPOSTA AQUI]
```

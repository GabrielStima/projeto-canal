# Exercício 03 — Consistência e Performance

Esta atividade é obrigatória para a continuidade. Você vai proteger uma operação crítica e justificar índices a partir das consultas já escritas.

## O Que Você Já Possui

Use `database/01-schema.sql`, `database/02-seed.sql` e `database/03-queries.sql`. Você já estudou transactions, índices e investigação de queries lentas.

## Sua Tarefa

Acrescente ao projeto:

- `database/04-transactions.sql`;
- `database/05-indexes.sql`;
- uma seção de justificativas em `database/modelo-relacional.md`.

Em `04-transactions.sql`, represente a aprovação de um orçamento que:

1. altera o status do orçamento para `aprovado`;
2. altera o status do atendimento para `em_procedimento`;
3. confirma todas as mudanças juntas;
4. permite rollback se uma etapa falhar.

Em `05-indexes.sql`, proponha índices para três consultas reais:

- busca de pets por tutor;
- histórico de atendimentos de um pet ordenado por data;
- listagem de atendimentos por status.

Para cada índice, registre:

- qual consulta ele pretende ajudar;
- quais colunas participam;
- qual custo ele adiciona às escritas;
- por que você não criaria índices em todas as colunas.

## Critérios de Conclusão

- a transaction evita estado parcial;
- existe uma condição que impeça aprovar novamente um orçamento já processado;
- cada índice está ligado a uma consulta concreta;
- a ordem das colunas de índices compostos foi justificada;
- você diferencia hipótese de performance de medição real;
- nenhum índice foi criado apenas por intuição genérica.

Guarde os arquivos. O backend usará essas decisões ao implementar o fluxo de aprovação.

## Corrija Sua Atividade Com IA

```text
Estou protegendo consistência e performance na camada de dados do PetCare OS.

Minha transaction representa a aprovação de um orçamento:
- atualizar o orçamento para aprovado;
- atualizar o atendimento para em_procedimento;
- confirmar tudo junto;
- desfazer tudo se uma etapa falhar;
- impedir processamento duplicado.

Também propus índices para:
- buscar pets por tutor;
- listar o histórico de atendimentos de um pet por data;
- filtrar atendimentos por status.

Critérios de correção:
1. a transaction não pode deixar apenas uma das tabelas atualizada;
2. commit e rollback devem estar em posições coerentes;
3. deve existir proteção contra aprovação repetida;
4. cada índice deve corresponder a uma query real;
5. índices compostos precisam ter ordem justificável;
6. custos de escrita e armazenamento devem ser reconhecidos;
7. sugestões de performance devem ser apresentadas como hipóteses até serem medidas.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões, riscos de consistência e suposições frágeis;
3. ofereça dicas específicas para eu corrigir;
4. não reescreva tudo antes da minha tentativa;
5. apresente uma solução completa somente se eu solicitar depois.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 02 — Schema, Dados Iniciais e Consultas

Esta atividade é obrigatória para a continuidade. Você vai transformar o modelo relacional anterior em SQL executável e responder perguntas reais do Portal do Tutor.

## O Que Você Já Possui

Use o arquivo `database/modelo-relacional.md` produzido no exercício anterior. Você também já estudou SQL básico, constraints, `JOIN`, subqueries, agregações e views.

## Sua Tarefa

Crie:

- `database/01-schema.sql`;
- `database/02-seed.sql`;
- `database/03-queries.sql`.

O schema deve conter ao menos:

- `tutores`;
- `pets`;
- `atendimentos`;
- `orcamentos`;
- `itens_orcamento`;
- `servicos`.

Inclua chaves primárias, chaves estrangeiras, `NOT NULL`, uma regra `UNIQUE` útil e pelo menos uma regra `CHECK`.

O seed deve criar dados suficientes para testar:

- dois tutores;
- três pets;
- atendimentos em status diferentes;
- um orçamento com mais de um item;
- um pet ainda sem atendimento.

Escreva consultas para:

1. listar os pets de um tutor;
2. mostrar atendimentos com nome do pet e do tutor;
3. listar todos os pets, inclusive os que não possuem atendimento;
4. calcular o total de cada orçamento;
5. contar atendimentos por status;
6. criar uma view com o resumo que o Portal do Tutor precisa exibir.

## Critérios de Conclusão

- os três arquivos podem ser lidos e executados na ordem indicada;
- as foreign keys correspondem ao modelo;
- os dados iniciais exercitam casos diferentes;
- cada consulta responde uma pergunta identificável;
- a view não expõe dados desnecessários do tutor;
- você consegue explicar por que escolheu cada constraint.

Guarde os arquivos. Eles receberão transactions, índices e migrations nos próximos exercícios.

## Corrija Sua Atividade Com IA

```text
Estou criando a primeira versão SQL da camada de dados do PetCare OS.

O schema precisa conter tutores, pets, atendimentos, orçamentos, itens de orçamento e serviços. Deve usar chaves primárias, chaves estrangeiras, NOT NULL, uma regra UNIQUE útil e pelo menos uma regra CHECK.

Também criei dados iniciais para dois tutores, três pets, atendimentos em estados diferentes, um orçamento com vários itens e um pet sem atendimento.

As consultas devem:
1. listar pets de um tutor;
2. mostrar atendimentos com pet e tutor;
3. preservar pets sem atendimento;
4. calcular o total de cada orçamento;
5. contar atendimentos por status;
6. criar uma view segura para o Portal do Tutor.

Critérios de correção:
- ordem de criação das tabelas e referências;
- integridade das constraints;
- coerência dos tipos e nomes;
- diferença correta entre INNER JOIN e LEFT JOIN;
- agregações e agrupamentos válidos;
- ausência de dados sensíveis desnecessários na view;
- SQL legível e compatível com um banco relacional comum.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões, erros de sintaxe, integridade ou lógica;
3. explique o impacto de cada erro;
4. dê dicas ou pequenos trechos antes de oferecer uma solução completa;
5. só mostre arquivos completos se eu pedir após tentar corrigir.

[COLE SUA RESPOSTA AQUI]
```

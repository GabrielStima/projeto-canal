# Exercício 03 — Banco e Consistência

Esta atividade é obrigatória para a continuidade. Você vai conectar a API à camada relacional construída no módulo 09.

## O Que Você Já Possui

Você possui endpoints com dados temporários e um diretório `database/` com schema, seed, consultas, índices, transaction e migrations. Também estudou conexão, pool, separação de responsabilidades, ACID, normalização e ORMs.

## Sua Tarefa

1. Escolha um cliente compatível com o banco relacional usado no módulo 09.
2. Leia a string de conexão pelo ambiente.
3. Crie um módulo responsável pelo pool de conexões.
4. Separe handlers HTTP de funções de acesso a dados.
5. Substitua os dados temporários dos endpoints por consultas reais.
6. Implemente a aprovação de orçamento dentro de uma transaction:
   - confirme que o orçamento está pendente;
   - altere o orçamento para aprovado;
   - altere o atendimento relacionado para em procedimento;
   - faça rollback se uma etapa falhar.
7. Compare uma consulta direta com a alternativa equivalente em um ORM, sem ser obrigado a migrar toda a aplicação.

Não altere silenciosamente o schema para facilitar o código. Se houver divergência entre API e banco, documente e faça uma migration explícita.

## Critérios de Conclusão

- credenciais não aparecem no código;
- o pool não é recriado a cada requisição;
- queries recebem valores por parâmetros;
- handlers não contêm blocos grandes de SQL;
- resultados do banco são transformados antes de virar resposta pública;
- a aprovação não deixa orçamento e atendimento em estados divergentes;
- falhas provocam rollback;
- a comparação com ORM discute query gerada, conveniência e custo;
- migrations continuam sendo a fonte de evolução do schema.

Guarde essa implementação. Logs e comportamento diante de falhas serão acrescentados no próximo exercício.

## Corrija Sua Atividade Com IA

```text
Estou conectando a API Node.js do PetCare OS ao banco relacional criado no módulo anterior.

Minha implementação possui:
- configuração de conexão por ambiente;
- pool compartilhado;
- acesso a dados separado dos handlers;
- queries parametrizadas;
- endpoints lendo dados reais;
- transaction para aprovar orçamento e atualizar atendimento;
- rollback em falhas;
- comparação entre SQL direto e ORM.

Critérios de correção:
1. credenciais não podem estar no código;
2. o pool não deve ser criado por requisição;
3. entrada externa não pode ser concatenada em SQL;
4. handlers e acesso a dados devem ter responsabilidades distintas;
5. respostas públicas não devem expor linhas do banco sem transformação;
6. a transaction deve confirmar que o orçamento ainda está pendente;
7. orçamento e atendimento devem ser confirmados juntos;
8. qualquer falha deve resultar em rollback;
9. a análise de ORM não pode afirmar que SQL deixou de ser necessário.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões, riscos de conexão e falhas de consistência;
3. ofereça dicas e trechos pequenos antes de reescrever tudo;
4. permita que eu corrija primeiro;
5. só mostre uma solução completa se eu pedir depois.

[COLE SUA RESPOSTA AQUI]
```

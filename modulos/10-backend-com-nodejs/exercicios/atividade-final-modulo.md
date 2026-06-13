# Atividade Final do Módulo — API Persistente do PetCare OS

Esta atividade é obrigatória para seguir ao módulo de API Design Profissional. Você vai organizar e demonstrar o fluxo backend construído durante o módulo.

## O Que Você Já Possui

Os exercícios anteriores produziram:

- projeto Node.js com TypeScript;
- configuração e CLI de verificação;
- servidor e health check;
- API JSON em um framework;
- especificação OpenAPI introdutória;
- conexão com o banco do módulo 09;
- consultas e transaction;
- logs estruturados;
- análise de failure modes;
- laboratório opcional de worker e performance;
- decisões sobre broker e busca.

## Sua Tarefa

Entregue um fluxo vertical demonstrável:

1. iniciar a API com configuração válida;
2. consultar um pet;
3. consultar seus atendimentos;
4. consultar um orçamento pendente;
5. aprovar o orçamento;
6. confirmar que orçamento e atendimento foram atualizados juntos;
7. repetir a operação e observar a resposta de conflito;
8. provocar entrada inválida, recurso ausente e banco indisponível em ambiente de laboratório;
9. correlacionar cada operação com logs;
10. comparar o comportamento com `docs/openapi.yaml`.

Atualize o README da API com:

- requisitos e configuração;
- scripts disponíveis;
- ordem para preparar o banco;
- como iniciar o serviço;
- rotas demonstradas;
- como executar a verificação manual;
- decisões deixadas para os próximos módulos.

## O Que Você Vai Produzir

Uma API Node.js persistente para um fluxo de atendimento, com:

- configuração verificável;
- endpoints JSON;
- documentação introdutória;
- acesso a banco;
- transaction;
- logs;
- comportamento conhecido diante de falhas;
- README de execução.

## Critérios de Conclusão

- outra pessoa consegue preparar banco e API seguindo o README;
- a API inicia sem editar o código;
- as consultas usam dados persistidos;
- a aprovação é atômica;
- repetição não altera novamente um orçamento já processado;
- erros não expõem segredos nem stack traces;
- logs permitem seguir a operação por request ID;
- OpenAPI corresponde aos endpoints demonstrados;
- broker, busca, worker e ORM aparecem somente conforme as decisões tomadas;
- o projeto está pronto para ter contrato e consistência refinados no módulo 11.

No módulo seguinte, a API será evoluída com contratos mais rigorosos, erros padronizados, paginação, filtros, compatibilidade e testes de contrato. Preserve a implementação e os documentos atuais.

## Corrija Sua Atividade Com IA

```text
Estou concluindo uma API persistente do PetCare OS com Node.js e TypeScript.

Minha entrega contém:
- configuração e CLI de verificação;
- health check;
- framework backend e endpoints JSON;
- OpenAPI introdutória;
- banco relacional e queries parametrizadas;
- transaction de aprovação de orçamento;
- logs estruturados com request ID;
- análise de failure modes;
- decisões sobre ORM, workers, broker e busca;
- README de execução.

O fluxo demonstrado consulta pet, atendimentos e orçamento, aprova o orçamento, atualiza o atendimento e impede novo processamento.

Critérios de correção:
1. outra pessoa deve conseguir configurar e executar o projeto;
2. dados precisam vir do banco;
3. aprovação deve ser atômica e confirmar que o orçamento ainda está pendente;
4. repetição deve produzir conflito sem nova alteração;
5. erros não podem expor segredos ou stack traces;
6. logs devem permitir correlação;
7. OpenAPI deve corresponder ao comportamento;
8. README deve explicar banco, scripts e verificação;
9. tecnologias opcionais só devem aparecer quando justificadas;
10. a API deve estar pronta para refinamento de contrato no módulo seguinte.

Analise minha entrega nesta ordem:
1. destaque os acertos;
2. aponte imprecisões, inconsistências e bloqueios;
3. priorize correções que impedem execução ou consistência;
4. ofereça dicas e exemplos pequenos antes de reescrever arquivos;
5. só apresente uma solução completa depois que eu tentar corrigir.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 02 — Erros da PetCare API

## Objetivo

Criar um formato único de erro e aplicá-lo aos contratos e endpoints principais da `petcare-api`.

## O Que Você Já Possui

- a especificação OpenAPI refinada no exercício anterior;
- logs estruturados com `requestId`;
- endpoints de pets, atendimentos e orçamentos;
- tratamento de falhas introdutório do módulo 10.

Esta atividade é **obrigatória para continuidade**. O mesmo formato de erro será usado nos testes de contrato.

## Sua Tarefa

1. Defina um schema `ApiError` com:
   - `code`, estável e voltado para tratamento pelo consumidor;
   - `message`, legível por pessoas;
   - `requestId`, para correlação;
   - `details`, opcional e útil para validação.
2. Mapeie pelo menos estes casos:
   - pet não encontrado;
   - orçamento não encontrado;
   - orçamento em estado incompatível com aprovação;
   - request body inválido;
   - erro interno inesperado.
3. Escolha status codes coerentes.
4. Atualize a OpenAPI com o schema e exemplos.
5. Aplique o formato aos endpoints implementados, sem expor stack trace, SQL ou dados sensíveis.

## O Que Você Vai Produzir

- schema `ApiError` em `docs/openapi.yaml`;
- tabela de códigos em `docs/api-errors.md`;
- respostas de erro padronizadas na API.

## Critérios de Conclusão

- o mesmo formato é usado em todos os endpoints escolhidos;
- `code` não depende do texto de `message`;
- status HTTP e código de domínio não se contradizem;
- `requestId` pode ser localizado nos logs;
- detalhes de validação identificam campos sem revelar informações internas.

Este padrão será retomado nos endpoints de listagem, idempotência e testes de contrato.

## Corrija Sua Atividade Com IA

```text
Estou padronizando erros da PetCare API, uma API Node.js com recursos de pets, atendimentos e orçamentos.

Minha resposta deve definir um schema ApiError com code, message, requestId e details opcional. Também deve mapear pet não encontrado, orçamento não encontrado, conflito de estado do orçamento, entrada inválida e erro interno para status HTTP e códigos estáveis.

Critérios de correção:
1. todos os erros usam a mesma estrutura;
2. code é estável e independente da mensagem;
3. status HTTP representa corretamente a categoria do problema;
4. requestId permite correlação com logs;
5. details ajuda na validação sem expor stack trace, SQL ou dados sensíveis;
6. a OpenAPI documenta o schema e exemplos.

Revise minha proposta. Comece pelos acertos. Depois identifique imprecisões, vazamentos de informação ou escolhas inadequadas de status. Dê dicas para eu corrigir antes de mostrar qualquer resposta completa.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 01 — Contratos da PetCare API

## Objetivo

Transformar os endpoints já existentes da `petcare-api` em contratos explícitos e atualizar a especificação OpenAPI iniciada no módulo 10.

## O Que Você Já Possui

- uma API Node.js e TypeScript;
- os endpoints `GET /pets/{petId}`, `GET /pets/{petId}/appointments`, `GET /budgets/{budgetId}` e `PATCH /budgets/{budgetId}`;
- um arquivo OpenAPI introdutório;
- exemplos de respostas JSON e erros.

Esta atividade é **obrigatória para continuidade**. Os contratos produzidos serão refinados nos exercícios seguintes.

## Sua Tarefa

1. Escolha uma única convenção de idioma para paths e campos.
2. Registre a convenção em `docs/api-conventions.md`.
3. Atualize `docs/openapi.yaml` para documentar os quatro endpoints existentes.
4. Para cada operação, descreva:
   - parâmetros;
   - request body, quando existir;
   - resposta de sucesso;
   - pelo menos uma resposta de erro;
   - schemas reutilizáveis.
5. Inclua exemplos coerentes com o comportamento atual da API.
6. Não adicione autenticação: ela será estudada no módulo 12.

## O Que Você Vai Produzir

- `docs/api-conventions.md`;
- `docs/openapi.yaml` com OpenAPI 3.1;
- uma lista curta das diferenças encontradas entre a documentação antiga e a API real.

## Critérios de Conclusão

- todos os paths documentados existem na API;
- parâmetros de path estão marcados como obrigatórios;
- códigos de sucesso e erro correspondem ao comportamento planejado;
- schemas comuns usam `$ref`;
- exemplos respeitam os schemas;
- o documento não promete campos ou operações que ainda não existem.

Este contrato será retomado nos exercícios de erros, listagens e testes.

## Corrija Sua Atividade Com IA

```text
Estou evoluindo uma API Node.js chamada PetCare API. Ela já possui estes endpoints:
- GET /pets/{petId}
- GET /pets/{petId}/appointments
- GET /budgets/{budgetId}
- PATCH /budgets/{budgetId}

Minha tarefa foi definir uma convenção de nomes e escrever uma especificação OpenAPI 3.1 com parâmetros, request bodies, respostas de sucesso, respostas de erro, schemas reutilizáveis e exemplos.

Critérios de correção:
1. os paths devem representar somente operações existentes;
2. parâmetros de path devem ser obrigatórios;
3. request e response devem ter schemas claros;
4. erros também devem estar documentados;
5. componentes repetidos devem ser reutilizados com $ref;
6. exemplos devem respeitar os schemas;
7. não deve haver autenticação ou recursos novos.

Revise minha resposta. Primeiro destaque meus acertos. Depois aponte imprecisões técnicas ou inconsistências entre paths, schemas e exemplos. Em seguida, ofereça dicas específicas para eu corrigir sozinho. Só apresente uma resposta completa se eu pedir depois de tentar novamente.

[COLE SUA RESPOSTA AQUI]
```

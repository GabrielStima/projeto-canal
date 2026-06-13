# Exercício 03 — Listagens da PetCare API

## Objetivo

Evoluir uma listagem existente com paginação, filtros e ordenação que funcionem juntos de forma previsível.

## O Que Você Já Possui

- `GET /pets/{petId}/appointments`;
- dados persistentes e índices estudados no módulo 09;
- contratos e erros padronizados;
- conhecimento de paginação, filtros e ordenação.

Esta atividade é **obrigatória para continuidade**.

## Sua Tarefa

Evolua `GET /pets/{petId}/appointments` com:

1. paginação por `page` e `pageSize`;
2. limite máximo de itens por página;
3. filtros opcionais por `status`, `scheduledAfter` e `scheduledBefore`;
4. ordenação por `scheduledAt` ou `createdAt`;
5. direção `asc` ou `desc`;
6. desempate estável por `id`;
7. erro padronizado para parâmetros inválidos.

Atualize implementação e OpenAPI. Explique também quais índices do banco podem ajudar essa consulta, sem criar índices automaticamente sem medir.

## O Que Você Vai Produzir

- endpoint de listagem atualizado;
- contrato OpenAPI dos query params e da resposta paginada;
- exemplos de requisições válidas e inválidas;
- nota curta sobre ordenação estável e índices.

## Critérios de Conclusão

- filtros, ordenação e paginação podem ser combinados;
- a mesma requisição mantém uma ordem determinística;
- valores padrão e limites máximos estão documentados;
- campos e direções não permitidos geram erro padronizado;
- a resposta informa os dados necessários para solicitar a próxima página.

Esta listagem fará parte da demonstração final e dos testes de contrato.

## Corrija Sua Atividade Com IA

```text
Estou evoluindo o endpoint GET /pets/{petId}/appointments da PetCare API.

Ele deve aceitar:
- page e pageSize, com valores padrão e limite máximo;
- status, scheduledAfter e scheduledBefore como filtros opcionais;
- sortBy igual a scheduledAt ou createdAt;
- sortDirection igual a asc ou desc;
- id como critério final de desempate.

A resposta deve conter data e metadados de paginação. Parâmetros inválidos devem usar o formato padronizado ApiError.

Critérios de correção:
1. filtros, ordenação e paginação funcionam em conjunto;
2. a ordem é estável;
3. defaults e limites estão explícitos;
4. parâmetros inválidos não são ignorados silenciosamente;
5. a OpenAPI descreve os query params e a resposta;
6. a proposta de índices é coerente, mas não presume otimização sem medição.

Avalie minha solução destacando primeiro os acertos. Depois aponte imprecisões de contrato, consistência ou consulta. Dê dicas graduais antes de apresentar uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

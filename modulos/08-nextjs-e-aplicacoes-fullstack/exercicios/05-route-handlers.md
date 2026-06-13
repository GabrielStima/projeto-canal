# Exercício 05 — Route Handlers

## Objetivo

Criar endpoints internos no Next.js para simular a aprovação de orçamentos do PetCare OS.

## Cenário

O Portal do Tutor precisa de uma API interna para processar a aprovação de um orçamento sem expor detalhes de uma API externa ao browser. Você vai criar um Route Handler que simula essa operação.

## Tarefa

1. Crie o arquivo `src/app/api/orcamentos/[id]/route.ts`.

2. Implemente o método `POST` que:
   - receba o `id` do orçamento pela URL;
   - simule a aprovação (por exemplo, retornando `{ id, status: "aprovado" }`);
   - retorne status `200` em caso de sucesso;
   - retorne status `404` se o orçamento não existir em uma lista mockada.

3. No Client Component de aprovação do exercício anterior, substitua o estado local simples por uma chamada real a este endpoint.

## Requisitos

- O Route Handler está na rota correta do App Router.
- O método `POST` recebe e usa o parâmetro dinâmico.
- Retorna JSON com status HTTP adequado.
- O Client Component chama o endpoint e trata sucesso/erro.
- Dados mockados são suficientes; não use banco de dados.

## Critérios de avaliação

- Estrutura de arquivos do Route Handler correta.
- Uso do parâmetro dinâmico `[id]`.
- Respostas JSON com status apropriados.
- Integração entre Client Component e Route Handler.
- Tratamento básico de erro na interface.

## Onde este trabalho será retomado

Este Route Handler será integrado à atividade final. No módulo 09 — Bancos de Dados, o handler passará a consultar e atualizar um banco real, mas a rota `/api/orcamentos/[id]` e o contrato de resposta permanecem.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de Route Handlers em Next.js. Vou te enviar o endpoint de aprovação de orçamentos e o Client Component que o consome no Portal do Tutor do PetCare OS.

Cenário: o tutor aprova um orçamento pelo portal. A aprovação é processada por um Route Handler interno do Next.js, sem expor detalhes de API externa.

Tarefa: revise minha implementação considerando:
1. A estrutura do arquivo route.ts está correta?
2. O parâmetro dinâmico [id] é usado corretamente?
3. Os status HTTP fazem sentido (200, 404, etc.)?
4. O Client Component chama o endpoint e trata a resposta?
5. A interface dá feedback de sucesso e erro?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

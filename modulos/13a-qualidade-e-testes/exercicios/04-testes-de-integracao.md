# Exercício 04 — Teste de Integração na API

## Tarefa

O PetCare OS possui o endpoint `POST /api/pets`. Para ter confiança na entrega, esse endpoint precisa de um **Teste de Integração**.

Escreva como você planeja esse teste.
1. Como o banco de dados será limpo antes e depois da execução?
2. Como a requisição HTTP simulada será feita (ex: Supertest)?
3. Você baterá no ORM para checar o Assert ou lerá direto no JSON de retorno?

## Requisitos

- Explicitar o setup (banco vazio).
- Escrever um cenário de sucesso avaliando a gravação real.
- Mostrar a diferença fundamental de criar mocks do repositório VS testar o repositório integrado.

## Corrija Sua Atividade Com IA

```text
Cenário: Planejamento de Testes de Integração para inserção de Pets na API.

Tarefa: Avalie minha abordagem abaixo em relação a teardown e asserções no banco de dados.

[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. A limpeza de banco garante que execuções assíncronas concorrentes não quebrarão os testes?
2. A asserção valida o comportamento do Banco e não apenas o JSON retornado pela Controller?
3. O teste não está dependente de APIs de terceiros externas reais?

Aponte as fraquezas da minha estratégia para testar infraestrutura de dados no Node.js.
```

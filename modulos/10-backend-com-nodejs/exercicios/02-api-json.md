# Exercício 02 — API JSON Inicial

Esta atividade é obrigatória para a continuidade. Você vai evoluir o servidor puro para uma API pequena usando o framework escolhido durante a aula de frameworks backend.

## O Que Você Já Possui

O projeto `petcare-api` já possui configuração, CLI, servidor HTTP e health check. Você também estudou APIs, JSON, REST, SOAP, GraphQL e OpenAPI em nível introdutório.

## Sua Tarefa

Escolha um framework backend compatível com Node.js e TypeScript. Registre no README por que ele é proporcional ao projeto.

Implemente, ainda com dados temporários:

- `GET /health`;
- `GET /pets/:id`;
- `GET /pets/:id/atendimentos`;
- `GET /orcamentos/:id`;
- `PATCH /orcamentos/:id`.

O `PATCH` deve aceitar apenas a mudança de status entre os valores já definidos no projeto. Neste momento, não implemente autenticação, paginação, idempotência ou um padrão avançado de erros.

Crie também `docs/openapi.yaml` com:

- versão OpenAPI e informações básicas;
- os caminhos implementados;
- parâmetros de caminho obrigatórios;
- corpo esperado no `PATCH`;
- respostas de sucesso, validação e não encontrado;
- schemas reutilizáveis para `Pet`, `Atendimento`, `Orcamento` e `Erro`.

## Critérios de Conclusão

- o servidor usa o framework sem apagar o entendimento adquirido com `node:http`;
- os handlers devolvem JSON e status coerentes;
- entrada inválida é rejeitada antes de alterar dados;
- as respostas não expõem campos internos desnecessários;
- a especificação possui `openapi`, `info`, `paths` e `components`;
- parâmetros de caminho estão marcados como obrigatórios;
- a documentação corresponde ao comportamento implementado;
- decisões avançadas ficam explicitamente para o módulo 11.

Guarde os endpoints e a spec. No próximo exercício, os dados temporários serão substituídos pela camada relacional construída no módulo 09.

## Corrija Sua Atividade Com IA

```text
Estou construindo a API JSON inicial do PetCare OS com Node.js, TypeScript e um framework backend.

Implementei:
- GET /health;
- GET /pets/:id;
- GET /pets/:id/atendimentos;
- GET /orcamentos/:id;
- PATCH /orcamentos/:id para alterar status permitido;
- docs/openapi.yaml com paths, parâmetros, request body, responses e schemas.

Ainda não devo implementar autenticação profunda, paginação, idempotência nem governança de API.

Critérios de correção:
1. métodos e caminhos devem representar os recursos com clareza inicial;
2. handlers devem responder JSON com status coerentes;
3. o PATCH deve validar o status recebido;
4. respostas não devem vazar detalhes internos;
5. a spec deve conter openapi, info, paths e components;
6. parâmetros de path devem ser obrigatórios;
7. requestBody e responses devem possuir content application/json quando houver corpo;
8. schemas e comportamento real devem ser compatíveis.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões de HTTP, JSON ou OpenAPI;
3. ofereça dicas antes de reescrever rotas ou a spec;
4. deixe que eu tente corrigir;
5. só apresente uma solução completa se eu solicitar depois.

[COLE SUA RESPOSTA AQUI]
```

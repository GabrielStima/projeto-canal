# Exercício 06 — Testes de Contrato

## Objetivo

Criar verificações executáveis para detectar mudanças incompatíveis nas respostas principais da API.

## O Que Você Já Possui

- uma OpenAPI atualizada;
- erros padronizados;
- uma listagem paginada;
- Node.js e a `petcare-api` executável.

Esta atividade é **obrigatória para continuidade**. O aprofundamento em estratégia de testes fica para o módulo 13A.

## Sua Tarefa

Use `node:test` e `node:assert/strict`, ou o test runner que já exista no projeto, para validar:

1. `GET /pets/{petId}` retorna `200` e os campos obrigatórios;
2. um pet inexistente retorna `404` no formato `ApiError`;
3. a listagem de atendimentos retorna `data` e metadados de paginação;
4. um parâmetro de ordenação inválido retorna erro padronizado;
5. a resposta não troca silenciosamente nomes ou tipos prometidos.

Um ponto de partida sem biblioteca externa:

```js
import assert from "node:assert/strict";
import test from "node:test";

const baseUrl = process.env.BASE_URL ?? "http://localhost:3000";

test("GET /pets/{petId} respeita o contrato básico", async () => {
  const response = await fetch(`${baseUrl}/pets/pet-1`);
  const body = await response.json();

  assert.equal(response.status, 200);
  assert.equal(typeof body.id, "string");
  assert.equal(typeof body.name, "string");
  assert.equal(typeof body.species, "string");
  assert.equal(typeof body.tutorId, "string");
});
```

Execute com a API iniciada:

```bash
node --test tests/contracts
```

Adapte paths, dados de seed e comando ao projeto real.

## O Que Você Vai Produzir

- testes em `tests/contracts/`;
- comando documentado para executá-los;
- pelo menos um caso que falha quando um campo obrigatório é renomeado;
- nota explicando o que esses testes não cobrem.

## Critérios de Conclusão

- os testes consultam comportamento observável;
- sucesso e erro são verificados;
- nomes e tipos obrigatórios são validados;
- falhas indicam qual parte do contrato mudou;
- os testes não tentam substituir testes unitários, de integração ou E2E.

Essas verificações serão ampliadas no módulo 13A e usadas como proteção durante o módulo 12.

## Corrija Sua Atividade Com IA

```text
Estou criando testes introdutórios de contrato para uma API Node.js usando node:test e node:assert/strict.

Preciso verificar:
- GET /pets/{petId}: status 200 e campos id, name, species e tutorId;
- pet inexistente: status 404 e corpo ApiError;
- listagem de atendimentos: data e metadados de paginação;
- ordenação inválida: erro padronizado;
- quebra quando um campo obrigatório muda de nome ou tipo.

Critérios de correção:
1. os testes verificam comportamento observável da API;
2. incluem sucesso e erro;
3. assertions identificam campos e tipos prometidos;
4. o comando de execução é reproduzível;
5. existe pelo menos uma demonstração de quebra de contrato;
6. o texto reconhece que contract tests não substituem outros níveis de teste.

Revise meus testes. Destaque primeiro os acertos. Depois aponte imprecisões e verificações frágeis, ausentes ou amplas demais. Dê dicas antes de apresentar código completo corrigido.

[COLE SUA RESPOSTA AQUI]
```

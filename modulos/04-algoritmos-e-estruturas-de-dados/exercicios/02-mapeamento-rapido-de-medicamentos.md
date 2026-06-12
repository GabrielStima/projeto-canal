# Exercício 02 — Mapeamento Rápido de Medicamentos

## O que você já sabe/possui

- Como criar objetos e arrays em TypeScript.
- Como usar `Map` e `Set`.
- A ideia de chave e valor estudada na aula sobre hash tables.

## Tarefa atual

Construa um índice rápido para consultar medicamentos do estoque de uma clínica veterinária pelo código. Em seguida, use um `Set` para listar os códigos dos medicamentos que estão abaixo do estoque mínimo.

## Exercício/resultado a produzir

Dado o array de medicamentos abaixo:

```ts
type Medication = {
  code: string;
  name: string;
  quantity: number;
  minQuantity: number;
};

const medications: Medication[] = [
  { code: "MED-001", name: "Anti-inflamatório", quantity: 30, minQuantity: 10 },
  { code: "MED-002", name: "Antibiótico", quantity: 5, minQuantity: 8 },
  { code: "MED-003", name: "Soro fisiológico", quantity: 12, minQuantity: 15 },
  { code: "MED-004", name: "Vermífugo", quantity: 20, minQuantity: 5 },
];
```

1. Converta o array em um `Map<string, Medication>` indexado por `code`.
2. Implemente uma função `findMedication(code: string)` que retorne o medicamento ou `undefined`.
3. Implemente uma função `getLowStockCodes()` que retorne um `Set<string>` com os códigos dos medicamentos cuja `quantity` é menor que `minQuantity`.
4. Demonstre a consulta de pelo menos dois códigos e a lista de medicamentos abaixo do estoque mínimo.

## Como solicitar correção com IA

Use a seção `Corrija Sua Atividade Com IA` ao final deste arquivo.

## Onde esse trabalho será retomado

Hash tables são a base de índices em bancos de dados, caches e lookups rápidos. Este exercício prepara o terreno para modelagem de dados e backend, onde você consultará registros por chave.

## Corrija Sua Atividade Com IA

```text
Estou estudando hash tables (Map e Set) em TypeScript. Este exercício é autocontido e não depende de nenhum projeto anterior.

Cenário:
Uma clínica veterinária precisa consultar medicamentos do estoque pelo código e identificar os itens abaixo do estoque mínimo.

Dados:
```ts
type Medication = {
  code: string;
  name: string;
  quantity: number;
  minQuantity: number;
};

const medications: Medication[] = [
  { code: "MED-001", name: "Anti-inflamatório", quantity: 30, minQuantity: 10 },
  { code: "MED-002", name: "Antibiótico", quantity: 5, minQuantity: 8 },
  { code: "MED-003", name: "Soro fisiológico", quantity: 12, minQuantity: 15 },
  { code: "MED-004", name: "Vermífugo", quantity: 20, minQuantity: 5 },
];
```

Tarefa:
1. Converta o array em um Map<string, Medication> indexado por code.
2. Implemente findMedication(code: string) que retorne o medicamento ou undefined.
3. Implemente getLowStockCodes() que retorne um Set<string> com os códigos dos medicamentos cuja quantity é menor que minQuantity.
4. Demonstre a consulta de pelo menos dois códigos e a lista de medicamentos abaixo do estoque mínimo.

Critérios de correção:
- O Map é construído corretamente a partir do array.
- findMedication usa o Map e não percorre o array.
- getLowStockCodes retorna um Set com os códigos corretos.
- O código compila em TypeScript sem erros óbvios.

[COLE SUA RESPOSTA AQUI]

Por favor, destaque meus acertos, aponte imprecisões e ofereça dicas antes de apresentar uma resposta completa.
```

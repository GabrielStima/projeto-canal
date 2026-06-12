# Exercício 03 — Buscando Prontuários

## O que você já sabe/possui

- Como percorrer arrays em TypeScript.
- Como implementar busca linear e busca binária.
- A diferença entre dados ordenados e desordenados.

## Tarefa atual

Implemente duas estratégias de busca por prontuários de pets em uma clínica veterinária e compare o número de passos de cada uma.

## Exercício/resultado a produzir

Dado o array de prontuários abaixo:

```ts
type MedicalRecord = {
  id: number;
  petName: string;
  diagnosis: string;
};

const records: MedicalRecord[] = [
  { id: 10, petName: "Luna", diagnosis: "Otite" },
  { id: 25, petName: "Thor", diagnosis: "Dermatite" },
  { id: 32, petName: "Mia", diagnosis: "Vômito" },
  { id: 47, petName: "Bolinha", diagnosis: "Fratura" },
  { id: 53, petName: "Nina", diagnosis: "Vacinação" },
  { id: 69, petName: "Rex", diagnosis: "Ectoparasitas" },
];
```

1. Implemente `linearSearch(records, targetId)` que retorne o prontuário encontrado e o número de comparações.
2. Implemente `binarySearch(records, targetId)` que assume que os prontuários estão ordenados por `id` e retorne o prontuário encontrado e o número de comparações.
3. Busque os ids `47` e `69` com ambas as funções.
4. Explique quando a busca linear é suficiente e quando a busca binária vale a pena.

## Como solicitar correção com IA

Use a seção `Corrija Sua Atividade Com IA` ao final deste arquivo.

## Onde esse trabalho será retomado

Buscas eficientes aparecem em bancos de dados (índices), APIs (filtros e paginação) e caches. Entender a diferença entre busca linear e binária ajuda a escolher a estratégia certa para cada tamanho de dados.

## Corrija Sua Atividade Com IA

```text
Estou estudando busca linear e busca binária em TypeScript. Este exercício é autocontido e não depende de nenhum projeto anterior.

Cenário:
Uma clínica veterinária precisa localizar prontuários de pets pelo id. Os prontuários estão ordenados por id.

Dados:
```ts
type MedicalRecord = {
  id: number;
  petName: string;
  diagnosis: string;
};

const records: MedicalRecord[] = [
  { id: 10, petName: "Luna", diagnosis: "Otite" },
  { id: 25, petName: "Thor", diagnosis: "Dermatite" },
  { id: 32, petName: "Mia", diagnosis: "Vômito" },
  { id: 47, petName: "Bolinha", diagnosis: "Fratura" },
  { id: 53, petName: "Nina", diagnosis: "Vacinação" },
  { id: 69, petName: "Rex", diagnosis: "Ectoparasitas" },
];
```

Tarefa:
1. Implemente linearSearch(records, targetId) que retorne o prontuário e o número de comparações.
2. Implemente binarySearch(records, targetId) que retorne o prontuário e o número de comparações.
3. Busque os ids `47` e `69` com ambas as funções.
4. Explique quando a busca linear é suficiente e quando a busca binária vale a pena.

Critérios de correção:
- A busca linear percorre os itens um por um e conta comparações.
- A busca binária assume ordenação e descarta metade a cada passo.
- Ambas retornam o prontuário correto e o número de comparações.
- A explicação sobre quando usar cada estratégia está correta.

[COLE SUA RESPOSTA AQUI]

Por favor, destaque meus acertos, aponte imprecisões e ofereça dicas antes de apresentar uma resposta completa.
```

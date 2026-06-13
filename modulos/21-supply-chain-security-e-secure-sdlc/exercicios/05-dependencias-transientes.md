# Exercício 05 — O Pesadelo das Dependências Transientes

## Tarefa

A equipe de segurança corporativa manda você atualizar o seu pacote raiz `react-scripts`. Mas o CVE letal (Buraco Crítico apontado pelo Scanner SCA) está apontando na biblioteca `lodash` versão Velha. Mas O SEU projeto NUNCA deu `npm install lodash`. Qual a complexidade e a dor de cabeça real na vida de um programador ao lidar com CVEs em árvores de dependência gigantes/Transientes?

## Corrija Sua Atividade Com IA

```text
Cenário: Dependency Scanning e as Raízes Invisíveis do Node Modules.

Tarefa: Segue a resposta justificando o pesadelo de atualizar a 'Lodash' na unha:
[COLE AQUI]

Critérios de correção:
1. Evidenciei que dependências Transientes (Lib A chama a Lib B, que chama a Lib C Vulnerável) forçam você a depender do autor da Lib A consertar as chamadas ou você terá que forçar `Resolutions/Overrides` no seu `package.json` amarrando código que pode quebrar funções subjacentes?
```

# Exercício 05 — Rollback Letal de Banco

## Tarefa

Seja incisivo: Por que aplicar um comando de `Rollback` cego via Orquestrador (Devolver a versão da semana passada) para a imagem Node.js do PetCare Frontend/API é estupidamente inofensivo/seguro, MAS tentar dar rollback instantâneo num Banco de Dados Produtivo após uma Migration Complexa (Drop de coluna de CPF) seria um genocídio de dados de clientes e falharia miseravelmente?

## Corrija Sua Atividade Com IA

```text
Cenário: Abuso de Rollbacks em ambientes Stateful X Stateless.

Tarefa: Aqui ataco a periculosidade de reverter bancos:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Evidenciei que imagens efêmeras (`Stateless`) não guardam lógicas históricas dos últimos 10 minutos, mas bancos guardam as novas assinaturas de pagamento?
2. Argumentei sobre quebrar a estrutura da coluna do BD corrompendo inserções ou exigindo "Restores Point in time" gigantes?
```

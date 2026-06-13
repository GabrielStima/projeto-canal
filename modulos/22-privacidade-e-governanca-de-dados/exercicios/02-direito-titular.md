# Exercício 02 — O Direito do Titular

## Tarefa

A legislação (LGPD/GDPR) exige o Direito da 'Portabilidade' e de 'Acesso' do usuário aos próprios dados. Qual a complexidade técnica profunda imposta ao arquiteto do sistema quando se é obrigado a programar uma Rota da API REST do tipo `GET /api/meus-dados/export` num sistema baseado em Microsserviços com 4 bancos separados?

## Corrija Sua Atividade Com IA

```text
Cenário: O Caos Distribuído vs a Portabilidade Legal de Dados.

Tarefa: Eis a minha tese sobre as dificuldades de criar o botão de Exportar em JSON/XML:
[COLE AQUI A EXPLICAÇÃO]


[COLE SUA RESPOSTA AQUI]
Critérios de correção:
1. Expus o fato de que agrupar dados (Joins) numa máquina Monolítica é fácil, mas agregar em Microservices forçaria rotinas gigantes de Message Brokers e Sagas?
2. Apontei o perigo de vazar dados de TERCEIROS misturados dentro do `.json` gerado para o cliente solicitante?
```

# Exercício 03 — Logs, Instrumentação e Telemetria

## O que você já sabe

Você mediu um endpoint por fora. Agora adicionará sinais dentro da aplicação para saber quanto tempo foi gasto e quais eventos ocorreram.

## Sua tarefa

Instrumente o endpoint escolhido com:

1. identificador de correlação criado ou preservado na entrada;
2. horário inicial e duração total;
3. status da resposta;
4. evento de sucesso ou falha;
5. log estruturado;
6. tratamento que não registre senha, token, corpo completo ou dado sensível.

Você pode usar a biblioteca de logs atual ou outra já disponível no projeto. Não precisa instalar uma plataforma externa.

Depois desenhe o caminho da telemetria:

`aplicação → coleta → transporte → armazenamento → consulta`

Se alguma etapa ainda não existe, marque-a como decisão futura em vez de simular que está pronta.

## O que você vai produzir

- middleware ou instrumentação equivalente;
- exemplos de log de sucesso e erro;
- diagrama do fluxo de telemetria;
- política curta de dados que não devem ser coletados;
- atualização do relatório.

## Critérios de conclusão

- O mesmo identificador acompanha os eventos da requisição.
- Duração e status são registrados.
- Os campos são pesquisáveis e estáveis.
- Dados sensíveis não aparecem.
- O desenho diferencia emissão, coleta, transporte e armazenamento.

## Como este trabalho continuará

Correlação e duração serão usadas para definir métricas e desenhar o trace do próximo exercício.

## Corrija Sua Atividade Com IA

```text
Cenário: Instrumentei um endpoint com correlação, duração e logs estruturados, e desenhei o caminho da telemetria.

Tarefa: Revise os sinais, os campos dos logs e o fluxo operacional.

Critérios de correção:
1. A correlação é preservada durante a requisição?
2. Duração, status e evento permitem investigação?
3. Os campos são estruturados e pesquisáveis?
4. Segredos e dados sensíveis foram excluídos?
5. Emissão, coleta, transporte, armazenamento e consulta foram diferenciados?

Destaque os acertos, aponte imprecisões e ofereça dicas antes de mostrar uma implementação completa.

[COLE SUA RESPOSTA AQUI]
```

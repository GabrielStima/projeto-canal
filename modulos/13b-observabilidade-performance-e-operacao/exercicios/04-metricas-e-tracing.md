# Exercício 04 — Métricas e Tracing

## O que você já sabe

O endpoint já emite contexto e duração. Agora você definirá medidas agregadas e acompanhará uma requisição pelas etapas relevantes.

## Sua tarefa

Defina para o endpoint:

- taxa de requisições;
- taxa de erros;
- distribuição de duração;
- uma métrica de saturação ou dependência;
- uma métrica de negócio, se ela orientar ação.

Para cada métrica, registre pergunta respondida, unidade e valor que exigiria investigação.

Depois desenhe um trace com spans para:

- entrada HTTP;
- autenticação ou autorização, quando existir;
- regra principal;
- banco;
- dependência externa, quando existir.

Relacione `traceId` ou identificador equivalente aos logs. O trace pode ser um diagrama; não é obrigatório instalar uma infraestrutura de tracing distribuído.

## O que você vai produzir

- catálogo pequeno de métricas;
- trace da operação;
- exemplo de investigação que começa em uma métrica e chega a log ou span;
- atualização do relatório.

## Critérios de conclusão

- Métricas respondem perguntas operacionais.
- Média e percentis são diferenciados.
- Labels ou dimensões evitam dados pessoais e cardinalidade sem controle.
- Os spans representam etapas reais.
- Logs, métricas e trace têm papéis distintos e complementares.

## Como este trabalho continuará

As métricas formarão o dashboard e o trace ajudará a investigar o failure mode escolhido.

## Corrija Sua Atividade Com IA

```text
Cenário: Defini métricas de taxa, erros, duração e saturação para um endpoint e desenhei o trace da operação.

Tarefa: Avalie se métricas e spans permitem investigar comportamento e falhas.

Critérios de correção:
1. Cada métrica responde uma pergunta clara?
2. Média, percentis, taxa e contagem foram usados corretamente?
3. Labels evitam dados pessoais e cardinalidade excessiva?
4. Os spans correspondem às etapas reais?
5. Existe um caminho de investigação entre métrica, trace e log?

Destaque os acertos, aponte imprecisões e dê dicas antes de propor um catálogo completo.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 04 — Fila, Retentativas e Backpressure

## O que você já tem

Você implementou um job com estados e consulta de status, mas a primeira versão ainda não lida bem com reinício, picos ou falhas temporárias.

## Tarefa

Evolua o desenho ou a implementação com uma fila. Você pode usar uma abstração local ou uma ferramenta compatível com seu projeto.

Defina:

1. produtor, fila e consumidor;
2. payload mínimo da mensagem;
3. limite de tentativas;
4. intervalo progressivo entre tentativas;
5. destino dos jobs que esgotarem as tentativas;
6. limite de concorrência do consumidor;
7. comportamento quando a fila crescer mais rápido do que o processamento;
8. logs e métricas para atraso, falhas e tamanho da fila.

Simule ao menos uma falha temporária e uma falha permanente. Explique o que acontece com a API quando há acúmulo de jobs.

## O que você vai produzir

Um fluxo que absorve picos sem esconder saturação e que diferencia recuperação automática de intervenção manual.

## Corrija Sua Atividade Com IA

```text
Cenário: Evoluí um job assíncrono com produtor, fila e consumidor. Defini contrato, tentativas limitadas, espera progressiva, destino para falhas permanentes, concorrência, comportamento sob acúmulo e observabilidade.

Tarefa: Revise meu desenho, configuração ou pseudocódigo.

Critérios de correção:
1. Produtor, fila e consumidor possuem responsabilidades separadas?
2. Retentativas são limitadas e não pressionam imediatamente uma dependência instável?
3. Falhas permanentes podem ser investigadas e reprocessadas com controle?
4. Concorrência e crescimento da fila foram tratados como capacidade limitada?
5. A API continua disponível sem prometer processamento imediato?
6. Logs e métricas permitem detectar atraso, falhas e saturação?

Comece pelos acertos. Depois sinalize imprecisões e riscos. Dê dicas priorizadas antes de apresentar uma configuração completa.

[COLE SUA RESPOSTA AQUI]
```

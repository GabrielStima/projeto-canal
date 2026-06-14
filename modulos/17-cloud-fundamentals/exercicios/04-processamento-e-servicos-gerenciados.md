# Exercício 04 — Processamento e Serviços Gerenciados

## O que você já tem

No módulo anterior, você implementou um fluxo assíncrono com job, fila, consumidor, retentativas e idempotência.

## Tarefa

Mapeie esse fluxo para cloud e compare:

- fila operada pela equipe;
- fila gerenciada;
- função serverless como consumidor;
- processo ou serviço de longa duração como consumidor.

Registre:

1. o que muda na aplicação e o que permanece igual;
2. limites de tempo, concorrência e escala;
3. comportamento diante de picos;
4. dead letter queue e reprocessamento;
5. observabilidade necessária;
6. custo e esforço operacional;
7. alternativa escolhida e condição para reavaliá-la.

Não escolha serverless ou serviço gerenciado apenas por serem opções de cloud.

## O que você vai produzir

Uma decisão de processamento que preserva o contrato e a idempotência construídos no módulo 16.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou levando um fluxo assíncrono existente para cloud. Comparei fila própria, fila gerenciada, função serverless e consumidor de longa duração, considerando contrato, concorrência, picos, falhas, observabilidade, custo e operação.

Tarefa: Revise minha decisão de processamento.

Critérios de correção:
1. O contrato e a idempotência existentes foram preservados?
2. Limites de duração e concorrência combinam com o consumidor escolhido?
3. Pico, atraso, falha permanente e reprocessamento foram tratados?
4. A observabilidade permite acompanhar fila, tentativas e resultado?
5. O custo operacional foi comparado ao custo financeiro?
6. A decisão evita adotar serverless ou serviço gerenciado sem necessidade?

Primeiro destaque os acertos. Depois aponte imprecisões e dê dicas antes de oferecer uma arquitetura completa.

[COLE SUA RESPOSTA AQUI]
```

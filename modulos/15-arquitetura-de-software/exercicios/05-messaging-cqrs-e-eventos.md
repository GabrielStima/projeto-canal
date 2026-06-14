# Exercício 05 — Messaging, CQRS e Eventos

## O que você já tem

Você já analisou os limites do sistema e os custos de uma possível distribuição.

## Tarefa

Escolha uma operação demorada ou sujeita a picos, como gerar um relatório ou enviar lembretes. Compare três fluxos:

- processamento síncrono;
- fila de trabalho com um consumidor;
- publicação de evento para múltiplos interessados.

Para a alternativa mais adequada, defina:

1. mensagem ou evento e seus dados mínimos;
2. quem produz e quem consome;
3. estado visível ao usuário enquanto o trabalho acontece;
4. comportamento diante de atraso, falha e duplicidade;
5. métricas e logs necessários;
6. se separar leitura e escrita com CQRS traria benefício real;
7. por que Event Sourcing seria adequado ou excessivo nesse caso.

Este exercício é de desenho arquitetural. A implementação de filas e workers ocorrerá no módulo seguinte.

## O que você vai produzir

Uma especificação de comunicação assíncrona que poderá ser implementada sem depender de um broker específico.

## Corrija Sua Atividade Com IA

```text
Cenário: Comparei processamento síncrono, fila de trabalho e publicação de eventos para uma operação demorada. Defini contrato, participantes, estado do usuário, falhas, duplicidade e observabilidade. Também avaliei CQRS e Event Sourcing sem tratá-los como obrigatórios.

Tarefa: Revise minha especificação arquitetural.

Critérios de correção:
1. A alternativa escolhida corresponde ao número e ao papel dos consumidores?
2. O contrato contém apenas dados necessários e evita acoplamento indevido?
3. Atraso, falha, duplicidade e estado visível ao usuário foram tratados?
4. A avaliação de CQRS e Event Sourcing é proporcional ao problema?
5. A especificação pode ser implementada sem depender de uma ferramenta específica?

Comece pelos acertos, identifique imprecisões e ofereça dicas antes de mostrar uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 06 — Testes no CI e Flakiness

## O que você já sabe

Você possui testes com custos diferentes. Agora organizará o feedback automático e investigará uma fonte de instabilidade antes que a equipe aprenda a ignorar falhas.

## Sua tarefa

Crie ou descreva um pipeline de CI com etapas em ordem de feedback:

1. instalação reproduzível;
2. análise estática rápida;
3. testes unitários;
4. testes de integração com ambiente isolado;
5. contrato;
6. E2E, quando implementado.

Defina quais falhas bloqueiam a mudança e quais etapas podem rodar separadamente.

Depois escolha um risco de flakiness:

- tempo fixo;
- relógio global;
- estado compartilhado;
- ordem dos testes;
- dependência externa;
- concorrência no banco.

Explique como reproduzir, diagnosticar e corrigir. Não use retry como solução principal.

## O que você vai produzir

- arquivo ou pseudocódigo do pipeline;
- tabela de checks obrigatórios;
- diagnóstico de uma fonte de flakiness;
- atualização da estratégia com duração aproximada das etapas.

## Critérios de conclusão

- Etapas rápidas falham antes das caras.
- Segredos e banco de testes são tratados como ambiente de CI.
- O pipeline usa comandos que também rodam localmente.
- Falhas fornecem informação acionável.
- A correção remove a causa da instabilidade.

## Como este trabalho continuará

O pipeline será consolidado na atividade final e receberá o quality gate do próximo exercício.

## Corrija Sua Atividade Com IA

```text
Cenário: Organizei testes em um pipeline de CI e investiguei uma causa de teste instável.

Tarefa: Revise a ordem das etapas, os checks obrigatórios e o diagnóstico de flakiness.

Critérios de correção:
1. O feedback rápido vem antes das etapas caras?
2. O ambiente de integração é reproduzível?
3. Os comandos funcionam localmente e no CI?
4. A falha ajuda a localizar o problema?
5. A solução de flakiness remove a causa em vez de apenas repetir o teste?

Destaque os acertos, aponte imprecisões e dê dicas antes de fornecer um pipeline completo.

[COLE SUA RESPOSTA AQUI]
```

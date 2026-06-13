# Exercício 08 — Caching Strategies

## Tarefa

O padrão *Cache-Aside* é perfeito (O aplicativo procura a Info no Redis, não acha, vai no Banco Lento, pega no banco Lento, joga no Redis e passa a ler super rápido). Mas descreva em detalhes trágicos a tempestade do 'Cache Stampede/Dogpile Effect'. O que acontece quando o Cache da Fila da Maternidade de Animais (A página mais requisitada com 10.000 users/sec) vence a vida útil (TTL Expire) à 1 da tarde num ambiente massivamente tráfegado sem Mutex Lock?

## Corrija Sua Atividade Com IA

```text
Cenário: TTL Eviction, Multithreading Concorrido do Node.js, Banco Afogado (Thundering Herd).

Tarefa: A minha descrição da Avalanche do Stampede no Redis/DB:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Abordei que nos milisegundos que a "Cache venceu", os exatos próximos 10.000 usuários paralelos perceberão o "Cache Vazio" de uma vez na borda?
2. E o pior: Os mesmos 10.000 tentarão "Buscar no Banco Lento juntos para recriar o Redis", matando as IOPS do PostgreSQL subjacente instantaneamente por ataque DDoS de si mesmos?
```

# Exercício 05 — O Poder do CDN

## Tarefa

CDNs (Redes de Entrega de Conteúdo) distribuem lixo ou vídeos pesados instantaneamente via caches na borda (Edge) em cada cidade do cliente. Mas seja enfático: Por que uma API Endpoint simples e textual de `GET /api/banco/minha-conta/saldo` (Gerando poucos JSON bytes) jamais pode ser acoplada em um CDN, gerando um crime técnico letal se fosse acoplada? E o que *Dynamic Caching* moderno tenta aliviar nesse cenário?

## Corrija Sua Atividade Com IA

```text
Cenário: Dinamismo Extremo de JSON API vs Edge Cache Static.

Tarefa: Eis a resposta sobre o Cache Stale (Velho/Dado desatualizado) e PII Exposure:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Falei que o Saldo mudaria num Pix em tempo real, mas o CDN (Edge) entregaria o Cache desatualizado (Stale de 5 min) gerando danos catastróficos nas transferências?
2. Avisei que guardar a Rota do Usuário no cache mundial vazaria o Saldo Secreto de uma pessoa pro browser do computador do vizinho dela?
```

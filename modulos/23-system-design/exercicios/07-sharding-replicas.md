# Exercício 07 — Sharding e Replicas

## Tarefa

Dividimos nosso monstruoso banco PostgreSQL Vertical quebrando ele brutalmente usando Partições `Sharding`. Os pets dos clientes cujo nome vai de A-M ficam no Servidor Físico Alfa, N-Z no Servidor Físico Beta. O que é um Hotspot brutal se o nome do influencer canino for 'Zendaya' (Letra Z) e o vídeo da vacina dela bombar com 2 Milhões de Writes na base da clínica em apenas meia hora? A arquitetura aguenta simétrico?

## Corrija Sua Atividade Com IA

```text
Cenário: Hotspots em Chaves de Partição Pobres Num Sharded Environment Massivo (MongoDB/SQL).

Tarefa: Minha resposta justificando a falha fatal da Key de divisão baseada em Letras em vez do poder da divisão Hashing (Shard Key de Hash):
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Provei que todo o volume dos 2 milhões de cliques sobrecarregariam estritamente um único Servidor Pobre Beta, enquanto o Alfa dorme entediado (Gargalo Fatal Lógico)?
2. Expliquei o conceito crucial de Distribuição Uniforme (Consistent Hashing Key)?
```

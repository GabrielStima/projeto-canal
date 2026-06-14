# Exercício 04 — Dados, Cache e Mensageria

## O Que Você Já Possui

O caminho da requisição chega a instâncias stateless, e a matriz de consistência define o que pode atrasar ou falhar parcialmente.

## A Tarefa

Evolua `docs/system-design.md` com o desenho da camada de dados:

1. escolha a fonte de verdade para dados transacionais;
2. defina índices e consultas críticas antes de propor particionamento;
3. indique quando uma réplica de leitura ajudaria e qual lag é aceitável;
4. proponha cache apenas para uma leitura com benefício demonstrável;
5. defina chave, TTL, invalidação e proteção contra stampede;
6. escolha uma tarefa para processamento assíncrono;
7. decida se ela exige fila de consumidores concorrentes ou publicação para múltiplos interessados;
8. defina idempotência, retries, backoff e tratamento de mensagens irrecuperáveis;
9. explique quando sharding seria considerado e qual sinal justificaria essa complexidade;
10. registre o fluxo dos dados pessoais conforme a governança do módulo anterior.

## O Que Você Vai Produzir

Um desenho de dados que começa simples e adiciona cache, réplicas, mensageria ou particionamento apenas diante de necessidades concretas.

Ele será submetido a cenários de falha e observabilidade no próximo exercício.

## Corrija Sua Atividade Com IA

```text
Cenário: Desenhei banco, índices, réplicas, cache e mensageria para a jornada principal do PetCare OS.

Tarefa: Revise minhas decisões e a evolução proposta.

Critérios de correção:
1. A fonte de verdade e as exigências de consistência estão claras.
2. Índices e consultas são avaliados antes de sharding ou novo banco.
3. Cache possui chave, TTL, invalidação e proteção contra stampede.
4. Fila e pub/sub são escolhidos conforme consumidores e semântica do evento.
5. Retries, idempotência e mensagens irrecuperáveis foram tratados.
6. Réplicas, particionamento e novos componentes possuem sinais que justificam adoção.
7. O fluxo respeita classificação, minimização e retenção dos dados.

Primeiro destaque meus acertos. Depois aponte complexidade prematura, inconsistências ou modos de falha e ofereça dicas. Só apresente um desenho completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

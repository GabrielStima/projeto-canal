# Exercício 05 — Confiabilidade e Observabilidade

## O Que Você Já Possui

Seu desenho já possui caminho de requisição, aplicação, banco, cache e processamento assíncrono.

## A Tarefa

Escolha quatro falhas:

- perda de uma instância da aplicação;
- banco lento ou indisponível;
- cache indisponível;
- fila acumulando mensagens;
- provedor externo com timeout;
- indisponibilidade de uma zona.

Para cada falha, registre em `docs/system-design.md`:

1. impacto na jornada;
2. sinal de detecção ligado ao usuário;
3. métrica de recurso complementar;
4. timeout, retry, circuit breaker ou bulkhead aplicável;
5. degradação aceitável;
6. estratégia de recuperação;
7. risco de cascata;
8. evidência para confirmar estabilidade.

Revise o SLO, RTO e RPO do primeiro exercício. Identifique pontos únicos de falha e proponha a menor melhoria que atenda ao objetivo. Inclua um exercício de mesa, não uma falha provocada em produção.

## O Que Você Vai Produzir

Um plano de falhas, observabilidade, degradação e recuperação proporcional aos objetivos do sistema.

O exercício seguinte avaliará se esse desenho também é seguro, sustentável e implementável.

## Corrija Sua Atividade Com IA

```text
Cenário: Submeti a arquitetura do PetCare OS a falhas e defini detecção, contenção, degradação e recuperação.

Tarefa: Revise meus cenários e a coerência com SLO, RTO e RPO.

Critérios de correção:
1. Cada falha possui impacto observável na jornada.
2. Latência, tráfego, erros e saturação são usados com métricas específicas do componente.
3. Retries e timeouts não ampliam cascatas.
4. Degradação mantém uma função útil sem comprometer dados críticos.
5. Pontos únicos de falha são tratados conforme o objetivo, não com redundância ilimitada.
6. Recuperação e estabilidade possuem evidências verificáveis.
7. A validação proposta é controlada e não exige causar dano em produção.

Primeiro destaque meus acertos. Depois aponte riscos de cascata ou redundância insuficiente e ofereça dicas. Só apresente um plano completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 02 — Consistência e Disponibilidade

## O Que Você Já Possui

Você definiu a jornada principal, a carga esperada e os requisitos de disponibilidade e recuperação.

## A Tarefa

Acrescente a `docs/system-design.md` uma matriz para quatro operações:

- reservar um horário;
- atualizar o status de um atendimento;
- consultar uma informação de perfil;
- gerar uma métrica agregada.

Para cada operação, decida:

1. consistência necessária;
2. atraso tolerável;
3. comportamento durante partição de rede;
4. experiência quando uma réplica estiver atrasada;
5. risco de conflito ou duplicidade;
6. estratégia de deduplicação ou reconciliação;
7. condição para negar temporariamente a operação;
8. impacto da decisão nos requisitos do exercício anterior.

Inclua ao menos uma escolha que priorize consistência e outra que aceite consistência eventual. Não classifique o sistema inteiro como apenas CP ou AP; analise cada operação e seu comportamento sob falha.

## O Que Você Vai Produzir

Uma política de consistência e disponibilidade ligada às regras de negócio.

Ela orientará cache, banco, replicação, filas e degradação nos próximos exercícios.

## Corrija Sua Atividade Com IA

```text
Cenário: Defini consistência, disponibilidade e comportamento sob falha para operações do PetCare OS.

Tarefa: Revise minha matriz e os trade-offs escolhidos.

Critérios de correção:
1. Cada decisão está ligada à consequência para o usuário ou para o negócio.
2. Atraso tolerável e comportamento durante partição estão explícitos.
3. Consistência eventual não foi tratada como erro automático.
4. Operações críticas não aceitam conflitos sem estratégia de proteção.
5. Deduplicação, reconciliação e leituras atrasadas foram consideradas.
6. As escolhas respeitam os requisitos e estimativas anteriores.

Primeiro destaque meus acertos. Depois aponte contradições ou riscos e ofereça dicas. Só apresente uma matriz completa depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

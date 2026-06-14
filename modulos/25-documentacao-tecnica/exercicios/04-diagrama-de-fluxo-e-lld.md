# Exercício 04 — Diagrama de Fluxo e LLD

## O Que Você Já Possui

Você tem o HLD e o C4 nível 2 do PetCare OS. Agora você vai detalhar um fluxo específico para mostrar como as decisões arquiteturais se materializam em interações concretas.

## A Tarefa

Escolha um fluxo do PetCare OS, como:

- agendamento de consulta com confirmação assíncrona;
- checkout de pagamento com fila e worker;
- notificação de lembrete de vacina;
- login com validação de sessão e cache.

Crie `docs/arquitetura/lld-<fluxo>.md` contendo:

1. **Escolha do fluxo:** descreva o objetivo, o gatilho e o resultado esperado.
2. **Diagrama de sequência em Mermaid:** mostre as interações entre ator, frontend, API, fila, worker, banco, cache e integrações externas. Inclua:
   - chamadas síncronas e assíncronas;
   - onde a operação é idempotente;
   - onde há retry, cache ou fallback;
   - onde há validação de segurança ou privacidade.
3. **Contratos principais:** liste os endpoints, eventos ou tópicos envolvidos com métodos e responsáveis.
4. **Decisões de design:** explique duas escolhas técnicas do fluxo e como elas se relacionam ao ADR do exercício anterior.
5. **Riscos e limites:** indique falhas esperadas, como o sistema se comporta e quem precisa ser alertado.

Mantenha o LLD focado em um único fluxo. Não tente detalhar todo o sistema em um só documento.

## O Que Você Vai Produzir

Um documento de baixo nível que detalha um fluxo real do PetCare OS e será usado para construir o runbook do próximo exercício.

## Corrija Sua Atividade Com IA

```text
Cenário: Desenhei o LLD de um fluxo do PetCare OS com diagrama de sequência e contratos.

Tarefa: Revise se o documento detalha o fluxo sem misturar tudo em um único diagrama.

Critérios de correção:
1. O fluxo escolhido tem objetivo, gatilho e resultado claros.
2. O diagrama de sequência mostra ator, frontend, API, fila, worker, banco, cache e integrações.
3. As chamadas síncronas e assíncronas estão diferenciadas.
4. Idempotência, retry, cache e fallback estão indicados.
5. Os contratos listam endpoints, eventos ou tópicos com responsáveis.
6. As decisões de design se relacionam com o ADR anterior.
7. Os riscos e limites incluem comportamento esperado em falha.
8. O documento não tenta detalhar todo o sistema.

Primeiro destaque meus acertos. Depois aponte falhas de sequência, inconsistências com o HLD ou detalhes faltantes e ofereça dicas. Só apresente um LLD completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

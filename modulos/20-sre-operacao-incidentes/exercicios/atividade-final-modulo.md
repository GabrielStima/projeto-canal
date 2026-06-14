# Atividade Final Prática — Exercício de Mesa de um Incidente

## O Que Você Já Possui

Você construiu em etapas:

- uma jornada crítica e sua análise de impacto;
- SLIs, SLO e error budget;
- sinais, verificações de saúde e degradação;
- um runbook;
- um plano de resposta;
- um postmortem inicial.

## A Tarefa

Conduza sozinho ou com colegas um exercício de mesa. Ninguém precisa derrubar a aplicação: use os eventos abaixo como informações reveladas em sequência.

1. **10:00:** um deploy termina sem erro aparente.
2. **10:04:** a taxa de sucesso da jornada crítica cai e o alerta dispara.
3. **10:08:** a readiness oscila; CPU da API está normal e a latência do banco aumentou.
4. **10:12:** a equipe descobre que o deploy incluiu uma mudança compatível na aplicação, mas uma migration elevou o custo de uma consulta.
5. **10:18:** o rollback da aplicação não reduz a latência.
6. **10:24:** a degradação planejada reduz a pressão e recupera a jornada principal.
7. **10:35:** uma correção segura é aplicada e os SLIs permanecem estáveis.

Para cada evento:

- registre horário, fato conhecido, decisão, responsável e resultado esperado;
- atualize severidade e comunicação quando necessário;
- use o runbook, justificando qualquer desvio;
- separe mitigação de correção definitiva;
- defina quando declarar recuperação.

Depois do exercício:

1. atualize o postmortem com a timeline real da simulação;
2. revise as ações de melhoria por impacto e esforço;
3. confirme que liveness, readiness, alertas e runbook continuam coerentes;
4. registre uma melhoria que deverá ser considerada no pipeline seguro do próximo módulo.

## O Que Você Vai Produzir

- `docs/operacao.md` revisado;
- um runbook em `docs/runbooks/`;
- um postmortem final em `docs/postmortems/`;
- um registro de decisões do exercício de mesa.

O próximo módulo retomará o deploy e a migration como partes da cadeia de entrega que também precisam de controles preventivos.

## Corrija Sua Atividade Com IA

```text
Cenário: Conduzi um exercício de mesa de um incidente no PetCare OS, usando uma sequência de eventos após um deploy com migration de banco.

Tarefa: Revise minhas decisões, comunicações, uso do runbook, critérios de recuperação, postmortem e ações de melhoria.

Critérios de correção:
1. As decisões evoluem conforme novas evidências aparecem, sem tratar hipóteses como fatos.
2. Papéis, severidade e comunicação permanecem claros durante o incidente.
3. Rollback, degradação e correção definitiva são usados com justificativas coerentes.
4. A recuperação é confirmada pelos SLIs durante um período estável.
5. O postmortem explica fatores técnicos e de processo sem atribuir culpa individual.
6. As ações possuem responsável, prazo, prioridade e evidência de conclusão.
7. O conjunto de documentos permite que outra pessoa entenda e repita o processo.

Primeiro destaque meus acertos. Depois aponte inconsistências e ofereça perguntas ou dicas para eu melhorar. Só apresente um exemplo completo depois que eu revisar minha própria solução.

[COLE SUA RESPOSTA AQUI]
```

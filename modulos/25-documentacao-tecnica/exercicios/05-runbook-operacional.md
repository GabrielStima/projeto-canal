# Exercício 05 — Runbook Operacional

## O Que Você Já Possui

Você tem o README, o ADR, o HLD e o LLD de um fluxo do PetCare OS. Agora você vai escrever um documento de operação que pode ser seguido durante um incidente.

## A Tarefa

Escolha um dos cenários abaixo e crie `docs/runbooks/<cenario>.md`:

- latência alta no banco de dados durante a madrugada;
- fila de notificações parada ou com acúmulo de mensagens;
- erro de autenticação em massa após deploy;
- worker de pagamentos processando mensagens em duplicidade.

O runbook deve conter:

1. **Sintoma:** como o incidente se manifesta para usuários, monitoramento e logs;
2. **Impacto esperado:** quais jornadas são afetadas e em quanto tempo o problema se torna crítico;
3. **Alertas e métricas:** quais queries, dashboards ou thresholds indicam o problema;
4. **Verificações iniciais:** passos para confirmar a causa em até 10 minutos;
5. **Ações de mitigação:** comandos, configurações ou decisões que reduzem o impacto;
6. **Escalonamento:** quando e para quem chamar;
7. **Critério de resolução:** quando o incidente pode ser considerado encerrado;
8. **Pós-incidente:** o que registrar para revisão e melhoria do runbook.

Use linguagem direta, comandos reais e formatos que possam ser lidos sob pressão. Evite textos longos e parágrafos densos.

## O Que Você Vai Produzir

Um runbook operacional que será incluído no portal documental do PetCare OS.

No próximo exercício você proporá uma mudança futura que pode exigir novos runbooks.

## Corrija Sua Atividade Com IA

```text
Cenário: Escrevi um runbook operacional para um incidente do PetCare OS.

Tarefa: Revise se o runbook pode ser seguido por uma pessoa de plantão sob pressão.

Critérios de correção:
1. O sintoma é observável por usuários, monitoramento ou logs.
2. O impacto esperado indica jornadas afetadas e janela de tempo.
3. Os alertas e métricas são específicos e consultáveis.
4. As verificações iniciais podem ser feitas em até 10 minutos.
5. As ações de mitigação incluem comandos ou decisões concretas.
6. O escalonamento define quando e para quem chamar.
7. O critério de resolução é mensurável.
8. O pós-incidente prevê registro e revisão do runbook.
9. A linguagem é direta e o formato é legível sob pressão.

Primeiro destaque meus acertos. Depois aponte passos vagos, falta de comandos ou critérios de resolução imprecisos e ofereça dicas. Só apresente um runbook completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

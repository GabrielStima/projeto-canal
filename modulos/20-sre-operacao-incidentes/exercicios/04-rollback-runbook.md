# Exercício 04 — Rollback e Runbook

## O Que Você Já Possui

Você já definiu como detectar degradação e quais sinais indicam que a jornada crítica está em risco.

## A Tarefa

Escolha o cenário `erros 5xx após um deploy` ou `readiness falhando por latência no banco` e escreva um runbook em `docs/runbooks/`.

O documento deve conter:

1. nome do alerta e impacto esperado;
2. pré-requisitos e acessos necessários;
3. verificações iniciais com resultado esperado;
4. critérios para escolher rollback, roll forward ou degradação;
5. passos de mitigação em ordem segura;
6. cuidados especiais caso exista mudança de banco de dados;
7. forma de validar a recuperação pelos SLIs;
8. condição de escalonamento e informações para a próxima pessoa.

Evite comandos irreversíveis. Quando um passo puder alterar dados, indique o risco e a confirmação necessária.

## O Que Você Vai Produzir

Um runbook executável por outra pessoa, com decisões, limites e validação de recuperação.

Ele será utilizado no exercício de resposta a incidente e na atividade final.

## Corrija Sua Atividade Com IA

```text
Cenário: Escrevi um runbook para mitigar uma falha operacional no PetCare OS.

Tarefa: Revise se outra pessoa conseguiria usar o runbook com segurança durante um incidente.

Critérios de correção:
1. O alerta e o impacto estão claros antes dos comandos.
2. As verificações distinguem sintomas, mudança recente e saturação.
3. Os critérios de rollback, roll forward ou degradação são objetivos.
4. Mudanças stateful e possíveis perdas de dados recebem cuidados específicos.
5. A recuperação é validada pelos SLIs e não apenas pela execução de um comando.
6. O documento informa quando parar e escalar.

Primeiro destaque meus acertos. Depois aponte passos ambíguos ou arriscados e ofereça dicas. Só proponha uma versão completa depois que eu ajustar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

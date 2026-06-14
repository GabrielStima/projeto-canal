# Exercício 05 — Evals e Guardrails

## O Que Você Já Possui

O sistema possui escopo, ferramentas controladas e um fluxo de recuperação. Agora você precisa provar que ele funciona dentro dos limites.

## A Tarefa

Crie um conjunto de pelo menos 20 casos em `docs/sistema-ia.md`, distribuídos entre:

- perguntas respondíveis;
- perguntas sem fonte suficiente;
- assuntos fora do escopo;
- tentativas de obter dados sensíveis;
- prompt injection;
- pedidos de ação sem autorização;
- ambiguidades e entradas adversariais.

Para cada grupo, defina:

1. comportamento esperado;
2. critérios de correção;
3. verificação determinística possível;
4. avaliação humana necessária;
5. uso opcional de LLM como avaliador;
6. exemplos para calibrar o avaliador;
7. falso positivo e falso negativo aceitáveis;
8. guardrail de entrada, recuperação, saída ou ferramenta;
9. evidência armazenada sem dados sensíveis;
10. condição que bloqueia uma nova versão.
11. mensagem de recusa útil e próximo passo;
12. ação que exige confirmação explícita;
13. mecanismo de feedback ou contestação;
14. critério de escalonamento humano;
15. métrica de falso bloqueio e abandono.

Compare o avaliador automatizado com uma pequena amostra revisada por você. O avaliador não deve ser tratado como fonte infalível.

## O Que Você Vai Produzir

Uma suíte de evals e uma matriz de guardrails ligada aos riscos do sistema.

Esses controles serão usados para decidir rollout, rollback e limites operacionais.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei evals e guardrails para o assistente do PetCare OS.

Tarefa: Revise a cobertura dos casos, critérios, avaliadores e bloqueios de versão.

Critérios de correção:
1. Os casos cobrem sucesso, ausência de fonte, segurança, privacidade e autonomia.
2. Critérios são específicos o suficiente para detectar regressões.
3. Verificações determinísticas são usadas quando possíveis.
4. Avaliação humana e LLM-as-a-judge possuem papéis e limites claros.
5. O avaliador automatizado foi calibrado contra exemplos revisados.
6. Guardrails existem em mais de uma camada e são testados.
7. Recusa, confirmação, feedback e escalonamento são compreensíveis para o usuário.
8. Existe condição objetiva para bloquear uma versão.

Primeiro destaque meus acertos. Depois aponte lacunas ou métricas frágeis e ofereça dicas. Só apresente uma suíte completa depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

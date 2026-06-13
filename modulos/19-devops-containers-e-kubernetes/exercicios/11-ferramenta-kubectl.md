# Exercício 11 — A Ferramenta Kubectl

## Tarefa

Qual a diferença caótica entre a geração "Imperativa" (Ex: Forçar o comando via shell `kubectl create deployment api --image=node`) contra a filosofia e o princípio da engenharia "Declarativa" (`kubectl apply -f arquivo.yaml` guardado no Github), especialmente para ambientes maduros onde o K8S se reconstrói ou escala?

## Corrija Sua Atividade Com IA

```text
Cenário: ClickOps e BashOps vs O Desired State da Infraestrutura.

Tarefa: Veja minha argumentação contra Imperativos no K8s:
[COLE AQUI]

Critérios de correção:
1. Foi apontada a perda gigantesca do histórico, já que comandos bash evaporam num `history -c` e o `Yaml` vive protegido no controle do `git push`?
2. Entendi o conceito absoluto de conciliação do motor do K8s (Desired State vs Current State) a partir do arquivo persistido?
```

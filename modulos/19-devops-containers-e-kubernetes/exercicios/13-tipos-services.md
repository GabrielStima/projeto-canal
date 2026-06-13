# Exercício 13 — Tipos de Services

## Tarefa

O Orquestrador mascara e alivia a perda dolorosa e transiente dos endereços de memória na nuvem flutuante usando Loadbalancers internos e externos. Compare, pontuando os riscos, o caso em que um Service do tipo genérico `ClusterIP` protege (mas esconde) um Banco PostgreSQL contra um poderoso Ingress e sua subcamada Service do tipo `LoadBalancer` que abre IPs reais aos clientes.

## Corrija Sua Atividade Com IA

```text
Cenário: Routing Abstrato Layer 4 e Roteamento DNS K8s.

Tarefa: Minha análise da proteção base do Cluster:
[COLE AQUI]

Critérios de correção:
1. Pontuei o encapsulamento hermético propiciado pela rede fechada do `ClusterIP` contra port-scans que a AWS recebe todo dia no Ingress Web?
2. Fui rigoroso e cirúrgico em por que Bancos não podem receber "Serviços em LoadBalancer" a não ser por motivos nefastos ou raros?
```

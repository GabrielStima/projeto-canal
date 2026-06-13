# Exercício 15 — Logs Descentralizados

## Tarefa

Com a morte a qualquer momento de Pods devida a auto-scaling ou crash na clínica PetCare, explique em tópicos como seria a implementação nativa de 1 Container padrão Sidecar raspando a `stdout` em infraestruturas arcaicas que forçam gravação de log suja pro disco físico para não perdê-los no espaço, antes da consolidação do modelo "Fluente e Centralizado" moderno?

## Corrija Sua Atividade Com IA

```text
Cenário: Padrão Sidecar para extração persistente e efêmera de Arquivos.

Tarefa: Segue como eu imagino essa arquitetura funcionando no YAML e na prática:
[COLE AQUI]

Critérios de correção:
1. Expliquei que no mesmo POD podem viver os dois: o container principal rodando e gravando via tail num disco local/volume EmptyDir?
2. Indiquei que o "Rastreador (logstash/fluent)" lê o File System do Volume no mesmo instante da gravação com a API e espicha pra Internet fora e salva vidas analíticas?
```

# Exercício 03 — Terraform em Pipelines

## Tarefa

Esboce uma justificativa. Por que a etapa crítica `terraform apply` deve ser a última sub-etapa de um pipeline na esteira de *CD* (somente acionada após o "Merge") e por que essa automação precisa depender rigorosamente da trava nativa e trancada do S3 + DynamoDB (Remote State Locking)?

## Corrija Sua Atividade Com IA

```text
Cenário: Automação Segura de Infraestrutura.

Tarefa: Minha resposta justificando a esteira:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. O texto esclarece que testar lint e formatação em Pull Requests e só rodar apply com aprovação é o padrão de ouro da indústria?
2. Entendi o pesadelo se 2 pipelines simultâneas rodassem sem trava (Locking), atropelando os arquivos reais da Nuvem de forma irreparável?
```

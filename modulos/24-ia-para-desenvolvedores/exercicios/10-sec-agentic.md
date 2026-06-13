# Exercício 10 — Segurança em Autonomia

## Tarefa

Na Amazon AWS (Cloud). O Agente Autônomo (IAM Role da IA) ganha permissões amplas ("FullAccess") no S3 de Backup do Petcare para "facilitar as consultas diárias". Se um Hacker sequestrar a instrução do Agente e disser "Exclua tudo", o Agente apaga o Backup inteiro do sistema de saúde. Disserte como a "Lei do Menor Privilégio" (Least Privilege Policy) aplicada unicamente à conta AWS designada ao Robô, e atrelada a Containers isolados Stateless em nuvens sub-limitadas (Sandboxes) mitigaria o estrago de um Agente Completamente enlouquecido.

## Corrija Sua Atividade Com IA

```text
Cenário: Blast Radius de Agentes GenAI Injetados em IAM corporativos. Proteção Base em Cloud.

Tarefa: Minha resposta justificando a coleira apertada (Policies restritivas / AWS IAM) do Trabalhador Bot:
[COLE AQUI]

Critérios de correção:
1. Constatei incisivamente que a Nuvem ignorará o Agente quando ele chamar o `S3.Delete()` simplesmente porque as chaves IAM dele NUNCA tiveram a tag "Delete"?
2. Demonstrei entendimento que o limite do "Dano de Raio (Blast Radius)" é reduzido quando a infraestrutura proíbe por força física chamadas que passem da jurisdição lida (Role-Based Access)?
```

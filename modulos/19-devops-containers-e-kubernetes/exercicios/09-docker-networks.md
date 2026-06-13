# Exercício 09 — Conexões de Rede

## Tarefa

Em um arquivo `docker-compose.yml`, se ambos os serviços (`api` e `postgres`) compartilham uma Bridge Network intrínseca padrão, descreva e diferencie explicitamente o comando `ports: ["5432:5432"]` da cláusula puramente interna `expose: ["5432"]` na segurança cibernética do host para a internet inteira bater.

## Corrija Sua Atividade Com IA

```text
Cenário: Firewall, Mapeamento em Camada 4 OSI e Abertura em Containers.

Tarefa: Meu entendimento teórico das sintaxes de rede HCL (e Docker Yaml):
[COLE AQUI]

Critérios de correção:
1. Abordei que o `expose` atua somente como flag mental/interconectividade entre os próprios blocos e fecha as conexões ao OS?
2. Avisei que `ports` fura o firewall e roteia requests TCP públicos para os containers expostos?
```

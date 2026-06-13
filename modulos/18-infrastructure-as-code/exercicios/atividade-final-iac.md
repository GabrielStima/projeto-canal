# Atividade Final do Módulo

## O que você já tem

Os requisitos de banco, filas e servidores que a nuvem do PetCare precisa levantar. E a noção básica da HCL de Hashicorp.

## A Tarefa

O **Marco de IaC N9** consolida a automatização total do ambiente.

1. Escreva 3 arquivos Terraform locais reais (Instale o binário do TF para validar sintaxe, se possível).
2. Arquivo `main.tf`: Defina o Provider da AWS e estabeleça um State Remoto atrelado a um Bucket S3 fictício.
3. Arquivo `network.tf`: Utilize o recurso Oficial Open-Source de VPC do Registry (Hashicorp Terraform Registry) declarando uma malha simples com subnets.
4. Arquivo `variables.tf` e `outputs.tf`: Defina o dinamismo ambiental do ambiente.
5. Rode `terraform plan` no vazio do seu PC (sem chaves AWS, apenas para garantir formatação).
6. Registre os benefícios financeiros diretos do famoso `terraform destroy` nos finais de semana para os contadores da startup.

## O que você vai produzir

- Uma pasta com a base atômica para qualquer deploy corporativo seguro que suba redes complexas em 40 segundos e zero cliques.

## Corrija Sua Atividade Com IA

```text
Cenário: Projeto Final - Provisionamento N9.

Tarefa: Enviei abaixo minha modelagem base dos arquivos `main.tf` com backend S3 + DynamoDB e o `network.tf` chamando Modules Oficiais da Cloud. E minha defesa financeira de redução de custos.

[COLE AQUI O CODIGO DOS SEUS ARQUIVOS HCL E SUA REDAÇÃO SOBRE DESTROY]

Critérios de correção:
1. O bloco Remote State contém suporte para State Locking no DynamoDB previnindo atropelamento de deploys entre devs?
2. O uso do Módulo Público no `network.tf` economizou mais de 100 linhas inúteis de código declarativo manual?
3. O benefício do destroy dinâmico aos finais de semana (apagando Staging para poupar $$) faz sentido como forte prática FinOps?
```

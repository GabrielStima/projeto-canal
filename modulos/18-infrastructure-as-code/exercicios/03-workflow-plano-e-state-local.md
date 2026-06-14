# Exercício 03 — Workflow, Plano e State Local

## O que você já tem

Seu laboratório passa em formatação, inicialização e validação.

## Tarefa

Execute o ciclo local:

```bash
terraform plan -out=tfplan
terraform apply tfplan
terraform plan
terraform show
terraform destroy
```

Durante o exercício:

1. revise o primeiro plano antes de aplicar;
2. registre quantos recursos serão criados;
3. confirme que o segundo plano não propõe mudanças;
4. localize o arquivo de state e explique sua função;
5. altere uma entrada e observe o novo plano;
6. restaure o valor anterior;
7. revise o plano de destruição antes de confirmar;
8. não versione `tfplan`, `.terraform/` ou `terraform.tfstate`.

## O que você vai produzir

Evidências do workflow e uma explicação sobre configuração, state, plano e infraestrutura real.

## Corrija Sua Atividade Com IA

```text
Cenário: Executei plan, apply, um segundo plan, show e destroy em um laboratório Terraform local. Registrei as ações propostas, observei idempotência, alterei uma entrada e analisei o state.

Tarefa: Avalie meu entendimento do workflow e das evidências.

Critérios de correção:
1. O plano foi revisado antes do apply e do destroy?
2. O segundo plan ficou sem mudanças quando a configuração não mudou?
3. Configuração, state, plano e recursos gerenciados foram diferenciados?
4. A mudança de entrada gerou uma diferença compreensível?
5. Arquivos locais e sensíveis foram excluídos do versionamento?
6. A repetição do workflow foi tratada como convergência, não como garantia absoluta de segurança?

Primeiro destaque os acertos. Depois aponte imprecisões e ofereça dicas antes de apresentar uma explicação completa.

[COLE SUA RESPOSTA AQUI]
```

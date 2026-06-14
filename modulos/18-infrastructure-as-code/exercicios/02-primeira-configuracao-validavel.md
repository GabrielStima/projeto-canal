# Exercício 02 — Primeira Configuração Validável

## O que você já tem

Você delimitou o que será representado em Terraform. Agora criará um laboratório local antes de conectar um provedor cloud.

## Tarefa

Na pasta `infra/lab`, crie:

- `versions.tf`;
- `variables.tf`;
- `main.tf`;
- `outputs.tf`.

Use `terraform_data` para representar pelo menos três componentes da arquitetura cloud. Inclua:

1. versão mínima `>= 1.4.0`, compatível com `terraform_data`;
2. variável `ambiente` validando `dev`, `stg` ou `prod`;
3. local value para nomes padronizados;
4. referências entre recursos para formar dependências implícitas;
5. um output não sensível;
6. comentários apenas onde a decisão não for óbvia.

Execute:

```bash
terraform fmt -check
terraform init -backend=false
terraform validate
```

Corrija os erros até os três comandos passarem.

## O que você vai produzir

Uma configuração HCL executável, sem credenciais cloud e sem custo financeiro.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei um laboratório Terraform local com versions.tf, variables.tf, main.tf e outputs.tf. Usei terraform_data para representar componentes, validei ambiente, criei nomes locais, dependências implícitas e um output.

Tarefa: Revise meu HCL e os resultados de fmt, init e validate.

Critérios de correção:
1. Blocos, argumentos e expressões usam sintaxe HCL válida?
2. A versão mínima do Terraform é explícita?
3. A variável ambiente rejeita valores inválidos?
4. Referências criam dependências sem depends_on desnecessário?
5. O output expõe apenas informação útil e não sensível?
6. Os comandos foram executados e os erros realmente corrigidos?

Comece pelos acertos. Depois aponte imprecisões e dê dicas antes de fornecer qualquer configuração completa.

[COLE SUA RESPOSTA AQUI]
```

# Atividade Final do Módulo

## O que você já tem

Você possui a arquitetura cloud do módulo 17 e um laboratório Terraform local com workflow, state, módulos, ambientes e revisão de segurança.

## A Tarefa

Transforme a arquitetura cloud em uma especificação Terraform reproduzível.

O caminho obrigatório é um laboratório local sem custos:

1. represente os componentes da arquitetura com módulos e recursos `terraform_data`;
2. organize ao menos `dev` e `prod` em configurações raiz separadas;
3. use variáveis, locals, referências e outputs;
4. documente quais blocos seriam substituídos por recursos reais do provedor;
5. mantenha state local apenas no laboratório e documente o backend remoto recomendado;
6. inclua locking atual, controle de acesso, criptografia e recuperação na estratégia de state;
7. execute `terraform fmt -check`, `terraform init -backend=false` e `terraform validate`;
8. execute `plan`, `apply`, um segundo `plan` sem mudanças e `destroy` em `dev`;
9. salve as evidências sem versionar state ou planos binários;
10. atualize `infra/README.md` com escopo, comandos, riscos e próximos passos.

Como extensão opcional, você pode substituir parte do laboratório por recursos reais em uma conta de testes. Antes disso, estime custos, use credenciais temporárias e exija confirmação explícita para `apply`.

## O que você vai produzir

- estrutura Terraform organizada por módulos e ambientes;
- laboratório local reproduzível;
- evidências de formatação, validação, plano, aplicação idempotente e destruição;
- estratégia documentada de remote state;
- mapeamento entre laboratório e recursos cloud reais.

Esse material será reutilizado nos módulos de CI/CD e containers. Nenhum recurso pago é necessário para concluir.

## Critérios de conclusão

- outra pessoa consegue executar o laboratório seguindo o README;
- o segundo plano não apresenta mudanças;
- módulos e ambientes possuem responsabilidades claras;
- state e segredos não são versionados;
- destruição é revisada antes da confirmação;
- a transição para recursos cloud reais está documentada, não presumida.

## Corrija Sua Atividade Com IA

```text
Cenário: Concluí um laboratório Terraform que representa uma arquitetura cloud. Ele possui módulos, ambientes dev e prod, variables, locals, dependências, outputs, workflow executado, estratégia de remote state e documentação para substituir recursos locais por recursos reais.

Tarefa: Faça uma revisão crítica do código, estrutura, README e evidências.

Critérios de correção:
1. A estrutura representa a arquitetura do módulo anterior sem adicionar recursos desnecessários?
2. Módulos, roots e ambientes possuem limites claros?
3. fmt, init sem backend, validate, plan, apply, segundo plan e destroy foram demonstrados?
4. O segundo plan confirma convergência sem mudanças?
5. State, planos e segredos estão fora do versionamento?
6. A estratégia de backend remoto usa locking atual, criptografia, acesso mínimo e recuperação?
7. O mapeamento para recursos cloud reais identifica provider, resource, data source e riscos?
8. Outra pessoa consegue reproduzir o laboratório sem conta cloud e sem custos?

Primeiro destaque os acertos. Depois aponte imprecisões, riscos e lacunas por prioridade. Ofereça dicas antes de apresentar qualquer solução completa.

[COLE SUA RESPOSTA AQUI]
```

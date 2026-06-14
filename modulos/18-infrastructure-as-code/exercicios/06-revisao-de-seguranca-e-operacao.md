# Exercício 06 — Revisão de Segurança e Operação

## O que você já tem

Você possui uma configuração validável, workflow praticado, módulos, ambientes e estratégia de state.

## Tarefa

Faça uma revisão prévia à atividade final:

1. confirme que nenhum segredo está no código, variáveis padrão, outputs ou histórico Git;
2. defina como o Terraform obteria credenciais temporárias e mínimas;
3. liste mudanças de IAM, rede ou dados que exigem revisão adicional;
4. crie um checklist para revisar `terraform plan`;
5. defina quem pode aplicar em `dev` e em `prod`;
6. documente backup, rollback ou recuperação para recursos com estado;
7. acrescente `.gitignore` adequado;
8. rode novamente `terraform fmt -check` e `terraform validate`.

## O que você vai produzir

Um checklist operacional e evidências de que a base está pronta para a atividade final.

## Corrija Sua Atividade Com IA

```text
Cenário: Revisei uma base Terraform antes da entrega. Verifiquei segredos, credenciais temporárias, menor privilégio, mudanças críticas, revisão de plan, permissões de apply, recuperação, gitignore, formatação e validação.

Tarefa: Avalie minha revisão de segurança e operação.

Critérios de correção:
1. Segredos não aparecem no código, state versionado, outputs ou histórico?
2. Credenciais são temporárias e possuem permissões mínimas?
3. Mudanças críticas recebem revisão proporcional ao risco?
4. O checklist de plan detecta criação, substituição, destruição e exposição?
5. Aplicações em produção possuem controle mais forte do que em desenvolvimento?
6. Recursos com estado possuem estratégia de recuperação?
7. Formatação e validação foram executadas novamente?

Comece pelos acertos. Depois aponte imprecisões e lacunas por prioridade. Dê dicas antes de apresentar um checklist completo.

[COLE SUA RESPOSTA AQUI]
```

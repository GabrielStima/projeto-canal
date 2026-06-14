# Exercício 04 — State Remoto, Drift e Ciclo de Vida

## O que você já tem

Você trabalhou com state local e observou como o plano compara configuração, state e recursos.

## Tarefa

Acrescente a `infra/README.md` uma estratégia para um ambiente compartilhado:

1. backend remoto e controle de acesso;
2. locking e prevenção de aplicações concorrentes;
3. criptografia, versionamento e recuperação do state;
4. separação entre segredos e referências a segredos;
5. procedimento para detectar e tratar drift;
6. decisão entre importar, aceitar ou reverter uma mudança existente;
7. recursos que precisam de `prevent_destroy`;
8. mudanças que poderiam exigir `create_before_destroy`.

Se usar o backend S3 como exemplo atual, registre `use_lockfile = true`. Não use locking por DynamoDB como recomendação nova, pois essa opção está descontinuada.

Não migre o laboratório para um backend remoto real neste exercício.

## O que você vai produzir

Um plano seguro para state compartilhado e resposta a mudanças fora do Terraform.

## Corrija Sua Atividade Com IA

```text
Cenário: Planejei remote state, locking, criptografia, versionamento, recuperação, proteção de segredos, tratamento de drift, importação e lifecycle para um ambiente Terraform compartilhado.

Tarefa: Revise minha estratégia de state e ciclo de vida.

Critérios de correção:
1. O backend possui controle de acesso, criptografia, histórico e recuperação?
2. Aplicações concorrentes são bloqueadas?
3. O exemplo S3 usa locking atual com use_lockfile, sem recomendar DynamoDB para projetos novos?
4. Dados sensíveis no state foram reconhecidos?
5. Drift é investigado antes de ser revertido ou absorvido?
6. Importação foi diferenciada da escrita da configuração?
7. prevent_destroy e create_before_destroy foram aplicados apenas onde fazem sentido?

Comece pelos acertos. Depois indique imprecisões e riscos. Dê dicas antes de apresentar uma estratégia completa.

[COLE SUA RESPOSTA AQUI]
```

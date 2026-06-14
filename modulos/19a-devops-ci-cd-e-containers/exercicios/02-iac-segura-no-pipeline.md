# Exercício 02 — IaC Segura no Pipeline

## O que você já tem

Você possui uma base Terraform validável e uma política de entrega com aprovações e rollback.

## Tarefa

Desenhe um workflow de Infrastructure as Code para pull requests e branch principal.

Inclua:

1. formatação e validação;
2. geração de plano no pull request;
3. resumo legível das mudanças;
4. bloqueio para destruição ou exposição não aprovada;
5. revisão humana;
6. credenciais temporárias e permissões mínimas;
7. aplicação somente a partir de uma referência confiável;
8. locking do state;
9. detecção periódica de drift;
10. resposta diante de drift autorizado e não autorizado.

Produza um pseudocódigo YAML. Não inclua credenciais reais nem execute `apply`.

## O que você vai produzir

Uma especificação de pipeline de infraestrutura conectada ao laboratório do módulo 18.

## Corrija Sua Atividade Com IA

```text
Cenário: Modelei um pipeline de Terraform com formatação, validação, plan em pull requests, revisão, policy checks, credenciais temporárias, apply controlado, locking e detecção de drift.

Tarefa: Revise meu pseudocódigo e as decisões de segurança.

Critérios de correção:
1. Pull requests geram evidências sem alterar infraestrutura?
2. Apply ocorre apenas após revisão e a partir de código confiável?
3. Credenciais são temporárias e limitadas ao ambiente?
4. Destruição, IAM, rede pública e dados recebem controles adicionais?
5. State locking e concorrência foram considerados?
6. Drift é detectado e investigado antes de qualquer correção automática?
7. Plano e aplicação não dependem de segredos permanentes no repositório?

Comece pelos acertos. Depois indique imprecisões e dê dicas antes de fornecer um workflow completo.

[COLE SUA RESPOSTA AQUI]
```

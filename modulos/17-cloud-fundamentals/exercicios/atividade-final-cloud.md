# Atividade Final do Módulo

## O que você já tem

Um sistema assíncrono bem montado rodando em containers no seu computador. Mas você foi promovido a Arquiteto Cloud.

## A Tarefa

O **Marco da Nuvem N8** formaliza seu ingresso no mundo enterprise de nuvem.

1. Escolha a sua plataforma provedora imaginária (AWS, Azure ou GCP).
2. Você deve redigir a Documentação de Topologia da rede.
3. Descreva a organização das Subnets dentro da VPC (onde vai a sua API? Onde vai o PostgreSQL? Por quê?).
4. Documente as Roles de Acesso (IAM) que serão permitidas para a Rota de Upload do Node mandar os raios-X ao S3/Blob.
5. Estabeleça uma regra de descarte (Lifecycle Policy do S3) ou um arquivamento frio (Glacier) para prontuários de 5 anos atrás para fins de FinOps e redução de R$.
6. Determine o RPO e RTO do banco de dados perante um incêndio grave no datacenter.

## O que você vai produzir

- Uma folha de arquitetura em formato texto ou `.drawio`.
- Você deixará de pensar em classes e funções, e provará raciocínio arquitetural físico/lógico em nuvem.

## Corrija Sua Atividade Com IA

```text
Cenário: Revisão Profissional Cloud Architecture (Marco N8).

Tarefa: Entreguei abaixo a topologia, as regras de IAM, minha estratégia de VPC e o ciclo de vida FinOps do PetCare.

[COLE AQUI SUA REDAÇÃO ARQUITETURAL]

Critérios de correção:
1. O banco está perigosamente exposto na Web ou elegantemente isolado em Subnet Privada?
2. O princípio do Menor Privilégio (IAM) está coeso e a escolha do gerenciamento DaaS/PaaS do Cloud confere economia contra operações do time?
3. O Lifecycle reduz custos de prontuários antigos, alinhado à LGPD e à prática cirúrgica?

Aja como um Lead Cloud Architect validando meu projeto antes de assinar o plano corporativo anual da AWS de U$ 5.000. Seja rigoroso.
```

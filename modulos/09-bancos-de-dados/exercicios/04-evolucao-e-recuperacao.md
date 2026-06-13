# Exercício 04 — Evolução, Recuperação e Acesso

Esta atividade é obrigatória para a continuidade. Você vai evoluir o schema com segurança e registrar como os dados podem ser recuperados e protegidos.

## O Que Você Já Possui

Seu projeto já contém schema, seed, consultas, transaction e índices. Você estudou migrations, backup, restore e segurança em bancos relacionais.

## Sua Tarefa

Crie:

- `database/migrations/001-schema-inicial.sql`, preservando a criação inicial;
- `database/migrations/002-prioridade-atendimento.sql`;
- `database/plano-de-recuperacao.md`;
- `database/regras-de-acesso.md`.

A segunda migration deve adicionar uma prioridade ao atendimento sem invalidar registros antigos. Descreva:

- valor inicial para dados existentes;
- ordem segura da mudança;
- validação após executar;
- possibilidade e limite de rollback.

No plano de recuperação, defina:

- frequência de backup;
- retenção;
- local separado para armazenamento;
- passos de restore;
- como verificar se a restauração funcionou;
- perda de dados e tempo de recuperação aceitáveis para um ambiente de estudo.

Nas regras de acesso, registre:

- por que a aplicação não deve usar um usuário administrador;
- permissões mínimas de leitura e escrita;
- proteção da string de conexão;
- separação entre desenvolvimento e produção;
- uso de queries parametrizadas.

## Critérios de Conclusão

- a migration considera os dados existentes;
- o rollback não promete recuperar dados que já foram destruídos;
- backup e restore são tratados como ações diferentes;
- existe um teste de restauração;
- segredos não aparecem em arquivos versionados;
- as permissões da aplicação são menores que as de administração.

Guarde esses arquivos. Eles acompanharão o banco quando ele for conectado ao backend.

## Corrija Sua Atividade Com IA

```text
Estou evoluindo e protegendo a camada de dados do PetCare OS.

Minha entrega contém:
- uma migration inicial;
- uma migration que adiciona prioridade ao atendimento sem quebrar dados existentes;
- um plano de backup e restore;
- regras de acesso e proteção de credenciais.

Critérios de correção:
1. a migration deve ter uma ordem segura para dados existentes;
2. valores padrão e obrigatoriedade devem ser tratados conscientemente;
3. rollback não deve prometer recuperar dados perdidos;
4. o plano deve separar backup de restore;
5. deve existir uma forma objetiva de validar a restauração;
6. a string de conexão não pode ficar no repositório;
7. o usuário da aplicação deve seguir menor privilégio;
8. queries parametrizadas devem aparecer como defesa contra entrada não confiável.

Analise minha resposta nesta ordem:
1. destaque os acertos e decisões corretas;
2. aponte imprecisões, riscos ou informações ausentes;
3. faça perguntas e ofereça dicas para eu melhorar;
4. não forneça documentos completos antes da minha revisão;
5. só apresente um exemplo completo se eu pedir depois.

[COLE SUA RESPOSTA AQUI]
```

# Atividade Final do Módulo

## O que você já tem

Você construiu `docs/arquitetura-cloud.md` com requisitos, região, rede, IAM, dados, processamento, segredos, recuperação e custos.

## A Tarefa

Revise esse material e produza a arquitetura cloud mínima do PetCare OS.

1. Desenhe os componentes e os fluxos de tráfego.
2. Identifique fronteiras públicas e privadas.
3. Relacione cada componente a uma categoria de serviço cloud, sem depender de um único provedor.
4. Registre identidades e permissões mínimas.
5. Defina onde ficam banco, objetos, frontend, fila e consumidor.
6. Documente backup, restauração, RPO, RTO e cenário de desastre.
7. Inclua estimativa mensal, premissas, tags, orçamento e alertas.
8. Liste cinco riscos, com probabilidade, impacto e mitigação.
9. Separe decisões obrigatórias de melhorias futuras.
10. Crie uma tabela que indique quais componentes serão descritos em Terraform no módulo 18.

## O que você vai produzir

- `docs/arquitetura-cloud.md` consolidado;
- um diagrama textual ou visual;
- uma estimativa de custos;
- uma matriz de riscos;
- uma lista priorizada para conversão em Infrastructure as Code.

Esse documento será a especificação de entrada do módulo 18. Não provisione recursos pagos nesta atividade.

## Critérios de conclusão

- a arquitetura atende aos requisitos declarados;
- somente componentes necessários foram incluídos;
- rede, IAM e dados não dependem de acesso público irrestrito;
- recuperação possui objetivos e procedimento verificáveis;
- custos possuem premissas e alertas;
- a próxima etapa de IaC está delimitada.

## Corrija Sua Atividade Com IA

```text
Cenário: Desenhei uma arquitetura cloud mínima para uma aplicação existente. O material contém requisitos, componentes, fluxos públicos e privados, IAM, dados, processamento assíncrono, segredos, recuperação, custos, riscos e uma lista de componentes que serão convertidos em Terraform.

Tarefa: Faça uma revisão crítica da arquitetura e de sua prontidão para virar Infrastructure as Code.

Critérios de correção:
1. Os componentes atendem aos requisitos sem complexidade desnecessária?
2. Rede, identidades e permissões seguem exposição mínima?
3. Banco, objetos, frontend, fila e consumidor foram posicionados coerentemente?
4. Backup, restauração, RPO e RTO são verificáveis?
5. Estimativa, tags, orçamento e alertas tornam o custo governável?
6. A matriz de riscos prioriza problemas reais?
7. A lista para Terraform separa o que será gerenciado, apenas consultado ou mantido fora do código?

Comece pelos acertos. Depois aponte imprecisões, riscos e lacunas por prioridade. Dê dicas antes de apresentar uma arquitetura completa.

[COLE SUA RESPOSTA AQUI]
```

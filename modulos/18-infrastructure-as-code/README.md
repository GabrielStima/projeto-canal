<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Infrastructure as Code

</div>

Este módulo ensina como transformar infraestrutura em código versionado, revisável e reproduzível, usando Terraform como ferramenta principal.

Até aqui, você já estudou cloud, IAM, VPC, storage, bancos gerenciados, filas, serverless, secrets, custos, backup e disaster recovery. Agora o foco é sair do desenho manual da infraestrutura e aprender a descrevê-la em arquivos que podem ser revisados, planejados, aplicados e evoluídos com controle.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o que é Infrastructure as Code e por que ela existe;
- diferenciar infraestrutura declarativa e imperativa;
- entender como Terraform representa recursos, dependências e mudanças;
- usar o workflow básico de `init`, `plan`, `apply` e `destroy`;
- entender state, remote state, locking, drift e importação de recursos;
- organizar configurações por módulos e ambientes;
- reconhecer riscos de segurança, segredos e dados sensíveis em IaC;
- provisionar uma infraestrutura simples de aplicação como projeto prático.

## Por Que Este Módulo Existe

Cloud manual funciona para aprender conceitos, mas não escala bem para times, ambientes, auditoria e recuperação. Quando a infraestrutura vive apenas em cliques, prints, memória e documentação solta, fica difícil revisar mudanças, reproduzir ambientes, saber quem alterou o quê e voltar para um estado conhecido.

Infrastructure as Code resolve parte desse problema ao tratar infraestrutura como artefato de engenharia: código versionado, revisável, testável em algum nível e conectado ao ciclo de entrega. Este módulo prepara a entrada em DevOps, containers, Kubernetes, SRE e system design com uma base prática de provisionamento.

## Pré-requisitos

- Fundamentos de cloud: regiões, zonas, IAM, VPC, storage, bancos gerenciados, filas, serverless e CDN.
- Segurança e configuração sensível: segredos, permissões, princípio do menor privilégio e auditoria.
- Git, GitHub, code review, variáveis de ambiente e documentação mínima de projeto.
- Backend, APIs, bancos de dados, migrations, logging e failure modes.
- Idempotência em APIs e fluxos assíncronos.
- Arquitetura, Twelve-Factor Apps, sistemas distribuídos e operação básica.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 18.00 | [Infrastructure as Code](18.00-infrastructure-as-code.md) | Guarda-chuva | Rascunho |
| 18.01 | [Infraestrutura Declarativa vs Imperativa](18.01-infraestrutura-declarativa-vs-imperativa.md) | Específica | Rascunho |
| 18.02 | [Idempotência em Infraestrutura](18.02-idempotencia-em-infraestrutura.md) | Específica | Rascunho |
| 18.03 | [Benefícios e Trade-offs de IaC](18.03-beneficios-e-trade-offs-de-iac.md) | Específica | Rascunho |
| 18.04 | [Terraform e Panorama de Ferramentas IaC](18.04-terraform-e-panorama-de-ferramentas-iac.md) | Específica ampla | Rascunho |
| 18.05 | [HCL: A Linguagem de Configuração do Terraform](18.05-hcl-a-linguagem-de-configuracao-do-terraform.md) | Específica | Rascunho |
| 18.06 | [Providers](18.06-providers.md) | Específica | Rascunho |
| 18.07 | [Resources e Data Sources](18.07-resources-e-data-sources.md) | Específica | Rascunho |
| 18.08 | [Dependências e Grafo de Recursos](18.08-dependencias-e-grafo-de-recursos.md) | Específica | Rascunho |
| 18.09 | [Variables, Local Values e Outputs](18.09-variables-local-values-e-outputs.md) | Específica | Rascunho |
| 18.10 | [Workflow do Terraform: Init, Plan, Apply e Destroy](18.10-workflow-do-terraform-init-plan-apply-e-destroy.md) | Específica prática | Rascunho |
| 18.11 | [State no Terraform](18.11-state-no-terraform.md) | Específica | Rascunho |
| 18.12 | [Remote State e Locking de State](18.12-remote-state-e-locking-de-state.md) | Específica | Rascunho |
| 18.13 | [Dados Sensíveis no State](18.13-dados-sensiveis-no-state.md) | Específica | Rascunho |
| 18.14 | [Drift e Importação de Recursos Existentes](18.14-drift-e-importacao-de-recursos-existentes.md) | Específica prática | Rascunho |
| 18.15 | [Ciclo de Vida dos Recursos](18.15-ciclo-de-vida-dos-recursos.md) | Específica | Rascunho |
| 18.16 | [Modules](18.16-modules.md) | Específica | Rascunho |
| 18.17 | [Composição e Reutilização de Módulos](18.17-composicao-e-reutilizacao-de-modulos.md) | Específica prática | Rascunho |
| 18.18 | [Organização por Ambientes](18.18-organizacao-por-ambientes.md) | Específica ampla | Rascunho |
| 18.19 | [Workspaces e Suas Limitações](18.19-workspaces-e-suas-limitacoes.md) | Específica | Rascunho |
| 18.20 | [Segurança e Segredos em IaC](18.20-seguranca-e-segredos-em-iac.md) | Específica | Rascunho |
| 18.21 | [Projeto Prático: Provisionando a Infraestrutura de uma Aplicação](18.21-projeto-pratico-provisionando-a-infraestrutura-de-uma-aplicacao.md) | Síntese prática | Rascunho |


## Trilha de Estudo

Este módulo está organizado em 5 blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Fundamentos de IaC** · aulas [18.00–18.04]
O que é IaC, declarativo vs imperativo, idempotência, trade-offs e panorama de ferramentas.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — HCL, providers e recursos** · aulas [18.05–18.08]
Linguagem HCL, providers, resources, data sources e dependências.
Pré-requisito: Bloco A.

**Bloco C — Workflow e state** · aulas [18.09–18.13]
Variables, outputs, workflow init/plan/apply/destroy, state, remote state e dados sensíveis.
Pré-requisito: Bloco B.

**Bloco D — Ciclo de vida e módulos** · aulas [18.14–18.17]
Drift, importação, lifecycle, modules, composição e reutilização.
Pré-requisito: Bloco C.

**Bloco E — Ambientes, segurança e prática** · aulas [18.18–18.21]
Organização por ambientes, workspaces, segurança, segredos e projeto prático.
Pré-requisito: Bloco D.

> Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

- [Exercício 01 — O Custo do ClickOps](exercicios/01-custo-do-clickops.md)
- [Exercício 02 — O Valor da Idempotência](exercicios/02-valor-idempotencia.md)
- [Exercício 03 — Lendo HCL Básico](exercicios/03-lendo-hcl.md)
- [Exercício 04 — Criar vs Ler](exercicios/04-resource-vs-data.md)
- [Exercício 05 — Variables, Locals e Outputs](exercicios/05-variables-locals-outputs.md)
- [Exercício 06 — O Perigo do Git no State](exercicios/06-state-no-git.md)
- [Exercício 07 — Resolvendo Drifts no Terraform](exercicios/07-drifts.md)
- [Exercício 08 — Modularizando a Clínica](exercicios/08-modulos-terraform.md)
- [Exercício 09 — Isolamento Físico x Lógico](exercicios/09-workspaces-limitacoes.md)
- [Atividade Final do Módulo](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo, você atinge o **marco de IaC**. A arquitetura da clínica não mais pertencerá à AWS de forma cega; ela passará a ser propriedade versionada em seu Github através de HCL (HashiCorp Configuration Language):

1. Crie os arquivos mestres (`main.tf`, `variables.tf`, `outputs.tf`) estabelecendo a malha base do PetCare OS.
2. Defina os Providers e estabeleça Segurança Máxima transferindo o "State" de sua máquina para um bucket S3/Blob Remoto, com proteção contra concorrência e Lock via DB.
3. Desenvolva Módulos paramétricos (`DRY`) para abstrair os padrões da infraestrutura (VPC e Filas/S3), possibilitando o spawn massivo de ambientes ("Dev", "Prod", "Staging") usando exatamente o mesmo código.
4. Execute rodadas de detecção de 'Drift' (deslizamentos) nas reuniões fictícias de SysAdmin e comprove que seu código reverte invasões indesejadas no painel da Cloud.
5. Efetive as estratégias de FinOps (Módulo 17) disparando comandos robustos de `terraform destroy` que pouparão recursos durante feriados e pausas da equipe nos clones dev/staging.

## O Que Revisar Antes de Avançar

- IAM, princípio do menor privilégio e credenciais.
- VPC/networking, object storage, managed databases e filas gerenciadas.
- Secrets, configuração sensível e variáveis de ambiente.
- Git, GitHub, code review e documentação mínima.
- Idempotência, failure modes, backup, restore e custos.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Infrastructure as Code de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina Infrastructure as Code usando Terraform como ferramenta principal, incluindo infraestrutura declarativa, HCL, providers, resources, data sources, dependências, variables, outputs, workflow, state, remote state, locking, drift, importação, lifecycle, modules, ambientes, workspaces, segurança e segredos.
- Objetivo do módulo: Quero ser capaz de definir, versionar, revisar, aplicar e evoluir infraestrutura cloud com segurança.
- Pré-requisitos: Cloud fundamentals, IAM, VPC, storage, bancos gerenciados, filas, serverless, secrets, Git, code review, idempotência e operação básica.

Crie uma revisão guiada com perguntas conceituais, exercícios práticos, perguntas de entrevista, exemplos em projetos reais e uma avaliação final.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial do Terraform quando a aula exigir detalhes de ferramenta.
- Documentação oficial dos provedores de cloud somente quando um exemplo exigir detalhes específicos.

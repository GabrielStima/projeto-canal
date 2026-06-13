# Atividade Final Prática: Simulacro de Incidente

## O que você já tem

Sua API com banco tem endpoints. Você aprendeu a diferença dolorosa entre estar fora do ar vs estar operante degradado.

## A Tarefa

Neste **marco operacional**, redija a vida real SRE:
1. Descreva a Rota `GET /health/liveness` e explique na folha como seu Node responde `200` apenas checando sua sanidade própria.
2. Descreva a Rota `GET /health/readiness` provando na folha que ela falha (retorna `503`) se o banco principal MySQL estiver fora (Não serve pro LoadBalancer!).
3. Escolha uma crise fatal fictícia e desenhe um **Postmortem Blameless**.
4. O Postmortem DEVE ter: Contexto, Timeline of Events (14:00 erro, 14:05 pagers, 14:30 rollback), Root Cause Analysis (Ação do sistema, NUNCA culpa o operador humano), e os *Action Items* práticos pro JIRA da Sprint que vem.

## O que você vai produzir

- Uma rota express limpa blindando roteadores do K8S.
- E o seu primeiro documento corporativo de Autópsia Livre de Culpas de um Desastre Digital Bilionário.

## Corrija Sua Atividade Com IA

```text
Cenário: O Exame Final SRE. Liveness Probes Node + Documento Executivo Postmortem Blameless.

Tarefa: Segue meu Pseudo-código de Healthchecks de K8S, e meu texto do Postmortem Blameless sobre o incidente fatal da Clínica.

[COLE AQUI SEU CÓDIGO HEALTH E SEU POSTMORTEM (RESUMIDO) MOLDADOS NA CLÍNICA PETCARE]


[COLE SUA RESPOSTA AQUI]
Critérios de correção:
1. O readiness probe prova consultar dependências pesadas externas (Banco)? (O liveness ficou leve pra evitar reinícios burros de contêineres)?
2. A análise do PostMortem cometeu o anti-pattern tóxico e imperdoável de culpar o nome de uma pessoa, ou assumiu as defesas como falhas do Processo?
3. Há *Action Items* práticos (Ex: Adicionar trava Terraform, Melhorar alerta do Datadog) propostos contra o acontecimento do erro na autópsia técnica?

Faça o papel de VP of Engineering revisando meu trabalho corporativo. Requeira melhoria contínua dos processos.
```

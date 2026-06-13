<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Privacidade e Governança de Dados

</div>

Este módulo mostra como lidar com dados pessoais, dados sensíveis, logs, acesso, retenção, auditoria e uso de IA de forma responsável.

Até aqui, você já estudou bancos de dados, segurança, autenticação, autorização, observabilidade, cloud, IAM, secrets, IaC, operação e Secure SDLC. Agora o foco muda para uma pergunta que atravessa produto, código e operação: quais dados a aplicação coleta, por que coleta, quem acessa, por quanto tempo guarda e como reduzimos o risco para as pessoas?

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- diferenciar dados pessoais, dados sensíveis, dados anonimizados e dados pseudonimizados;
- explicar LGPD/GDPR em nível prático para desenvolvimento de software;
- mapear dados coletados, armazenados, compartilhados e descartados por uma aplicação;
- relacionar consentimento, finalidade, necessidade e minimização com decisões de produto e engenharia;
- definir políticas de acesso a dados com princípio do menor privilégio;
- criar estratégias simples de retenção, descarte e anonimização;
- evitar vazamento de dados sensíveis em logs, traces, erros, prompts e ferramentas de IA;
- desenhar trilhas de auditoria úteis sem transformar logs em uma nova fonte de risco;
- revisar uma aplicação fullstack do ponto de vista de privacidade e governança de dados.

## Por Que Este Módulo Existe

Software real quase sempre manipula informações sobre pessoas: nome, e-mail, telefone, identificadores, endereço, pagamentos, comportamento, localização, mensagens, documentos, preferências e histórico de uso. Mesmo quando uma aplicação parece simples, seus logs, backups, ferramentas de suporte, analytics, pipelines e prompts de IA podem carregar dados que identificam alguém.

Privacidade não é apenas uma camada jurídica depois que o sistema fica pronto. Ela influencia requisitos, modelagem, formulários, autorização, observabilidade, operação, incident response, contratos com terceiros e até custo de armazenamento. Governança de dados existe para transformar esse cuidado em prática repetível.

## Pré-requisitos

- Bancos de dados, modelagem, integridade, queries, backup e restore.
- APIs, contratos, erros padronizados, idempotência e API governance.
- Autenticação, autorização, sessões, tokens, OAuth, rate limiting e segurança em APIs.
- Logs, métricas, tracing, telemetria, monitoramento, alertas e failure modes.
- Cloud Fundamentals: IAM, object storage, bancos gerenciados, secrets, backup, custos e auditoria.
- Infrastructure as Code: state sensível, ambientes, permissões e revisão de mudanças.
- SRE: incident response, runbooks, postmortems, rollback e operação.
- Secure SDLC: threat modeling, secrets management, permissões mínimas, CI/CD seguro e auditoria.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 22.00 | [Privacidade e Governança de Dados](22.00-privacidade-e-governanca-de-dados.md) | Guarda-chuva | Rascunho |
| 22.01 | [Dados Pessoais, Dados Sensíveis e Ciclo de Vida do Dado](22.01-dados-pessoais-dados-sensiveis-e-ciclo-de-vida-do-dado.md) | Específica ampla | Rascunho |
| 22.02 | [LGPD/GDPR Básico Para Devs](22.02-lgpd-gdpr-basico-para-devs.md) | Específica ampla | Rascunho |
| 22.03 | [Inventário, Classificação e Governança de Dados](22.03-inventario-classificacao-e-governanca-de-dados.md) | Específica | Rascunho |
| 22.04 | [Consentimento e Finalidade de Uso](22.04-consentimento-e-finalidade-de-uso.md) | Específica | Rascunho |
| 22.05 | [Políticas de Acesso a Dados](22.05-politicas-de-acesso-a-dados.md) | Específica prática | Rascunho |
| 22.06 | [Retenção, Descarte e Minimização de Dados](22.06-retencao-descarte-e-minimizacao-de-dados.md) | Específica | Rascunho |
| 22.07 | [Anonimização e Pseudonimização](22.07-anonimizacao-e-pseudonimizacao.md) | Específica | Rascunho |
| 22.08 | [Logs com Dados Sensíveis](22.08-logs-com-dados-sensiveis.md) | Específica prática | Rascunho |
| 22.09 | [Auditoria e Rastreabilidade de Acesso a Dados](22.09-auditoria-e-rastreabilidade-de-acesso-a-dados.md) | Específica prática | Rascunho |
| 22.10 | [Dados Enviados Para IA](22.10-dados-enviados-para-ia.md) | Específica atual/prática | Rascunho |
| 22.11 | [Projeto Prático: Revisão de Privacidade de uma Aplicação Fullstack](22.11-projeto-pratico-revisao-de-privacidade-de-uma-aplicacao-fullstack.md) | Síntese prática | Rascunho |


## Exercícios

- [Exercício 01 — A Bomba Relógio](exercicios/01-bomba-relogio.md)
- [Exercício 02 — O Direito do Titular](exercicios/02-direito-titular.md)
- [Exercício 03 — Inventário PetCare](exercicios/03-inventario-petcare.md)
- [Exercício 04 — Cron de Expurgo](exercicios/04-cron-expurgo.md)
- [Exercício 05 — Máscara de Dados](exercicios/05-mascara-dados.md)
- [Exercício 06 — Sanitização de Logs](exercicios/06-sanitizacao-logs.md)
- [Atividade Final Prática: Governança do Petcare](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

A governança implanta maturidade institucional através do **marco de governança de dados**. A clínica PetCare passa por uma auditoria legal profunda. Transforme sua arquitetura base numa fortaleza limpa e ética:

1. Modifique a engine de Log (Observabilidade) nativa das APIs incorporando o filtro pesado `Redaction` que interceptará Textos e CPFs em `StdOut` transmutando-os em `***` antes de cruzarem a rede da Cloud (Evitando indexação ilegal pelo Datadog/Cloudwatch).
2. Programe e descreva a arquitetura de uma *CronJob Noturna/Background Worker* focada na expurgação cirúrgica (*Hard Delete*) de registros frios em conformidade total com expirações estritas do seu SLA Retentivo.
3. Configure Modelagens de Dados em bancos Paralelos (Data Warehouse ou Data Lake via Views Materializadas) forçando a Pseudo-anonimização dos Dados Tóxicos, blindando-os de Cientistas de Dados ou de uso irrestrito do Marketing do hospital.

## O Que Revisar Antes de Avançar

- Autenticação, autorização e menor privilégio.
- Bancos de dados, backup, restore e segurança.
- Logs, métricas, traces, telemetria e monitoramento.
- IAM, secrets, ambientes e credenciais.
- Threat modeling, incident response e Secure SDLC.
- API governance, contratos e erros seguros.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Privacidade e Governança de Dados de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina dados pessoais, dados sensíveis, LGPD/GDPR básico para devs, inventário, classificação, consentimento, finalidade, políticas de acesso, retenção, descarte, minimização, anonimização, pseudonimização, logs sensíveis, auditoria e uso de dados em IA.
- Objetivo do módulo: Quero conseguir revisar uma aplicação real do ponto de vista de privacidade, governança de dados e redução de risco.
- Pré-requisitos: bancos de dados, segurança, autenticação, autorização, observabilidade, cloud, IAM, secrets, SRE e Secure SDLC.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercícios práticos de classificação de dados;
3. cenários de produto, logs, auditoria e IA para eu avaliar;
4. perguntas de entrevista para backend/fullstack intermediário;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Lei Geral de Proteção de Dados Pessoais, Lei n. 13.709/2018.
- Autoridade Nacional de Proteção de Dados: perguntas frequentes, guias orientativos e materiais educativos.
- European Commission: GDPR e data protection explained.
- European Data Protection Board: orientações sobre consentimento, pseudonimização e outros temas de proteção de dados.
- OWASP Cheat Sheet Series quando a aula envolver segurança de aplicações, logging, secrets ou dados sensíveis.

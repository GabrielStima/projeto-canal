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
| 22.00 | [Privacidade e Governança de Dados](22.00-privacidade-e-governanca-de-dados.md) | Guarda-chuva | Auditada |
| 22.01 | [Dados Pessoais, Dados Sensíveis e Ciclo de Vida do Dado](22.01-dados-pessoais-dados-sensiveis-e-ciclo-de-vida-do-dado.md) | Específica ampla | Auditada |
| 22.02 | [LGPD/GDPR Básico Para Devs](22.02-lgpd-gdpr-basico-para-devs.md) | Específica ampla | Auditada |
| 22.03 | [Inventário, Classificação e Governança de Dados](22.03-inventario-classificacao-e-governanca-de-dados.md) | Específica | Auditada |
| 22.04 | [Consentimento e Finalidade de Uso](22.04-consentimento-e-finalidade-de-uso.md) | Específica | Auditada |
| 22.05 | [Políticas de Acesso a Dados](22.05-politicas-de-acesso-a-dados.md) | Específica prática | Auditada |
| 22.06 | [Retenção, Descarte e Minimização de Dados](22.06-retencao-descarte-e-minimizacao-de-dados.md) | Específica | Auditada |
| 22.07 | [Anonimização e Pseudonimização](22.07-anonimizacao-e-pseudonimizacao.md) | Específica | Auditada |
| 22.08 | [Logs com Dados Sensíveis](22.08-logs-com-dados-sensiveis.md) | Específica prática | Auditada |
| 22.09 | [Auditoria e Rastreabilidade de Acesso a Dados](22.09-auditoria-e-rastreabilidade-de-acesso-a-dados.md) | Específica prática | Auditada |
| 22.10 | [Dados Enviados Para IA](22.10-dados-enviados-para-ia.md) | Específica atual/prática | Auditada |
| 22.11 | [Projeto Prático: Revisão de Privacidade de uma Aplicação Fullstack](22.11-projeto-pratico-revisao-de-privacidade-de-uma-aplicacao-fullstack.md) | Síntese prática | Auditada |


## Exercícios

- [Exercício 01 — Inventário, Classificação e Finalidade](exercicios/01-inventario-finalidade-dados.md)
- [Exercício 02 — Solicitação do Titular e Política de Acesso](exercicios/02-solicitacao-titular-acesso.md)
- [Exercício 03 — Retenção, Descarte e Backups](exercicios/03-retencao-descarte-backups.md)
- [Exercício 04 — Dataset Pseudonimizado](exercicios/04-dataset-pseudonimizado.md)
- [Exercício 05 — Logs Seguros e Auditoria](exercicios/05-logs-auditoria.md)
- [Exercício 06 — Dados Enviados para IA](exercicios/06-dados-enviados-ia.md)
- [Atividade Final Prática — Revisão de Privacidade do PetCare OS](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

Neste módulo você revisa um fluxo do PetCare OS em etapas:

1. Cria um inventário com classificação, finalidade, necessidade e localizações.
2. Modela solicitações do titular e políticas de acesso.
3. Define retenção, descarte, backups e evidências de execução.
4. Desenha um dataset pseudonimizado para analytics.
5. Separa logs operacionais de eventos de auditoria.
6. Cria critérios para dados enviados a ferramentas de IA.
7. Consolida riscos e um plano de melhoria em `docs/governanca-dados.md`.

O trabalho é uma revisão técnica de privacidade. Bases legais, prazos regulatórios e declarações de conformidade devem ser validados com profissionais responsáveis pelo contexto jurídico e de privacidade.

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

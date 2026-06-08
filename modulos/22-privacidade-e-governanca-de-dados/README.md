# Privacidade e Governanca de Dados

Este modulo mostra como lidar com dados pessoais, dados sensiveis, logs, acesso, retencao, auditoria e uso de IA de forma responsavel.

Ate aqui, voce ja estudou bancos de dados, seguranca, autenticacao, autorizacao, observabilidade, cloud, IAM, secrets, IaC, operacao e Secure SDLC. Agora o foco muda para uma pergunta que atravessa produto, codigo e operacao: quais dados a aplicacao coleta, por que coleta, quem acessa, por quanto tempo guarda e como reduzimos o risco para as pessoas?

## Objetivo do Modulo

Ao final deste modulo, voce deve ser capaz de:

- diferenciar dados pessoais, dados sensiveis, dados anonimizados e dados pseudonimizados;
- explicar LGPD/GDPR em nivel pratico para desenvolvimento de software;
- mapear dados coletados, armazenados, compartilhados e descartados por uma aplicacao;
- relacionar consentimento, finalidade, necessidade e minimizacao com decisoes de produto e engenharia;
- definir politicas de acesso a dados com principio do menor privilegio;
- criar estrategias simples de retencao, descarte e anonimização;
- evitar vazamento de dados sensiveis em logs, traces, erros, prompts e ferramentas de IA;
- desenhar trilhas de auditoria uteis sem transformar logs em uma nova fonte de risco;
- revisar uma aplicacao fullstack do ponto de vista de privacidade e governanca de dados.

## Por Que Este Modulo Existe

Software real quase sempre manipula informacoes sobre pessoas: nome, e-mail, telefone, identificadores, endereco, pagamentos, comportamento, localizacao, mensagens, documentos, preferencias e historico de uso. Mesmo quando uma aplicacao parece simples, seus logs, backups, ferramentas de suporte, analytics, pipelines e prompts de IA podem carregar dados que identificam alguem.

Privacidade nao e apenas uma camada juridica depois que o sistema fica pronto. Ela influencia requisitos, modelagem, formularios, autorizacao, observabilidade, operacao, incident response, contratos com terceiros e ate custo de armazenamento. Governanca de dados existe para transformar esse cuidado em pratica repetivel.

## Pre-requisitos

- Bancos de dados, modelagem, integridade, queries, backup e restore.
- APIs, contratos, erros padronizados, idempotencia e API governance.
- Autenticacao, autorizacao, sessoes, tokens, OAuth, rate limiting e seguranca em APIs.
- Logs, metricas, tracing, telemetria, monitoramento, alertas e failure modes.
- Cloud Fundamentals: IAM, object storage, bancos gerenciados, secrets, backup, custos e auditoria.
- Infrastructure as Code: state sensivel, ambientes, permissoes e revisao de mudancas.
- SRE: incident response, runbooks, postmortems, rollback e operacao.
- Secure SDLC: threat modeling, secrets management, permissoes minimas, CI/CD seguro e auditoria.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 22.00 | [Privacidade e Governanca de Dados](22.00-privacidade-e-governanca-de-dados.md) | Guarda-chuva | Rascunho |
| 22.01 | [Dados Pessoais, Dados Sensiveis e Ciclo de Vida do Dado](22.01-dados-pessoais-dados-sensiveis-e-ciclo-de-vida-do-dado.md) | Especifica ampla | Rascunho |
| 22.02 | [LGPD/GDPR Basico Para Devs](22.02-lgpd-gdpr-basico-para-devs.md) | Especifica ampla | Rascunho |
| 22.03 | [Inventario, Classificacao e Governanca de Dados](22.03-inventario-classificacao-e-governanca-de-dados.md) | Especifica | Rascunho |
| 22.04 | [Consentimento e Finalidade de Uso](22.04-consentimento-e-finalidade-de-uso.md) | Especifica | Rascunho |
| 22.05 | [Politicas de Acesso a Dados](22.05-politicas-de-acesso-a-dados.md) | Especifica pratica | Rascunho |
| 22.06 | [Retencao, Descarte e Minimizacao de Dados](22.06-retencao-descarte-e-minimizacao-de-dados.md) | Especifica | Rascunho |
| 22.07 | [Anonimizacao e Pseudonimizacao](22.07-anonimizacao-e-pseudonimizacao.md) | Especifica | Rascunho |
| 22.08 | [Logs com Dados Sensiveis](22.08-logs-com-dados-sensiveis.md) | Especifica pratica | Rascunho |
| 22.09 | [Auditoria e Rastreabilidade de Acesso a Dados](22.09-auditoria-e-rastreabilidade-de-acesso-a-dados.md) | Especifica pratica | Rascunho |
| 22.10 | [Dados Enviados Para IA](22.10-dados-enviados-para-ia.md) | Especifica atual/pratica | Rascunho |
| 22.11 | [Projeto Pratico: Revisao de Privacidade de uma Aplicacao Fullstack](22.11-projeto-pratico-revisao-de-privacidade-de-uma-aplicacao-fullstack.md) | Sintese pratica | Rascunho |

## Projeto ou Pratica do Modulo

Revise uma aplicacao fullstack ja usada no curso:

1. liste dados coletados no frontend, API, banco, logs, analytics, suporte e IA;
2. classifique dados pessoais, sensiveis, tecnicos, publicos e anonimizados;
3. descreva a finalidade de cada coleta;
4. reduza campos desnecessarios em formularios, tabelas, respostas e logs;
5. defina politica de acesso por papel, recurso e necessidade;
6. proponha retencao e descarte para contas, pedidos, logs, backups e exports;
7. aplique uma estrategia simples de pseudonimizacao ou anonimização quando fizer sentido;
8. revise eventos de auditoria;
9. revise prompts e integrações de IA para evitar envio indevido de dados;
10. documente riscos aceitos e proximas melhorias.

## O Que Revisar Antes de Avancar

- Autenticacao, autorizacao e menor privilegio.
- Bancos de dados, backup, restore e seguranca.
- Logs, metricas, traces, telemetria e monitoramento.
- IAM, secrets, ambientes e credenciais.
- Threat modeling, incident response e Secure SDLC.
- API governance, contratos e erros seguros.

## Prompt de Revisao do Modulo

```text
Estou finalizando o modulo Privacidade e Governanca de Dados de uma formacao fullstack JavaScript/TypeScript.

Contexto do modulo:
- Descricao do modulo: O modulo ensina dados pessoais, dados sensiveis, LGPD/GDPR basico para devs, inventario, classificacao, consentimento, finalidade, politicas de acesso, retencao, descarte, minimizacao, anonimização, pseudonimizacao, logs sensiveis, auditoria e uso de dados em IA.
- Objetivo do modulo: Quero conseguir revisar uma aplicacao real do ponto de vista de privacidade, governanca de dados e reducao de risco.
- Pre-requisitos: bancos de dados, seguranca, autenticacao, autorizacao, observabilidade, cloud, IAM, secrets, SRE e Secure SDLC.

Crie uma revisao guiada com:
1. perguntas conceituais;
2. exercicios praticos de classificacao de dados;
3. cenarios de produto, logs, auditoria e IA para eu avaliar;
4. perguntas de entrevista para backend/fullstack intermediario;
5. exemplos de aplicacao em projetos reais;
6. uma avaliacao final com criterios claros.

Nao entregue respostas completas antes de eu tentar responder.
```

## Referencias Gerais

- Materiais internos do proprio projeto.
- Lei Geral de Protecao de Dados Pessoais, Lei n. 13.709/2018.
- Autoridade Nacional de Protecao de Dados: perguntas frequentes, guias orientativos e materiais educativos.
- European Commission: GDPR e data protection explained.
- European Data Protection Board: orientacoes sobre consentimento, pseudonimizacao e outros temas de protecao de dados.
- OWASP Cheat Sheet Series quando a aula envolver seguranca de aplicacoes, logging, secrets ou dados sensiveis.

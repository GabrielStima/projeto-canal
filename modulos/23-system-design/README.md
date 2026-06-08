# System Design

Este módulo mostra como pensar em sistemas maiores, escaláveis, confiáveis, seguros e operáveis. Até aqui, você já estudou web, backend, bancos de dados, APIs, segurança, observabilidade, arquitetura, comunicação assíncrona, cloud, IaC, containers, Kubernetes, SRE, Secure SDLC e governança de dados. Agora o foco é juntar essas peças para tomar decisões de desenho.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- entender system design como raciocínio de requisitos, restrições e trade-offs;
- estimar carga, capacidade e crescimento de um sistema;
- explicar disponibilidade, consistência, resiliência e alta disponibilidade;
- escolher entre DNS, CDN, load balancer, aplicação, banco, cache e mensageria com critérios claros;
- reconhecer riscos de performance, confiabilidade, dados, cloud e segurança em uma arquitetura;
- desenhar sistemas usando componentes conhecidos sem transformar ferramenta em resposta automática;
- justificar decisões técnicas em cenários reais e entrevistas.

## Por Que Este Módulo Existe

Construir uma API, uma interface ou um banco funcionando é só uma parte do trabalho. Sistemas reais precisam lidar com tráfego variável, falhas parciais, latência, custo, crescimento, dados sensíveis, deploys, observabilidade, segurança, filas, cache, regiões, dependências externas e pessoas operando tudo isso em produção.

System design existe para organizar esse raciocínio. Ele não é uma lista de receitas prontas. É a prática de entender o problema, declarar suposições, escolher limites, desenhar fluxo de dados, decidir trade-offs e explicar por que uma solução serve para aquele contexto.

## Pré-requisitos

- Fundamentos da web: DNS, HTTP, cache, cliente, servidor, request e response.
- Backend com Node.js, APIs, contratos, idempotência, bancos de dados, filas e motores de busca.
- Autenticação, autorização, rate limiting, segurança em APIs e threat modeling.
- Observabilidade, performance, testes de carga, logging, métricas, tracing e failure modes.
- Design e arquitetura de software: boundaries, coupling, cohesion, DDD, monolitos, microserviços, serverless, CQRS e Event Sourcing.
- Comunicação assíncrona: WebSocket, filas, pub/sub, background jobs e operações idempotentes.
- Cloud Fundamentals: VPC, regiões, zonas, CDN, bancos gerenciados, filas, serverless, backup, disaster recovery e custos.
- DevOps, containers, Kubernetes, autoscaling, padrões de deployment e operação.
- SRE, Secure SDLC, privacidade e governança de dados.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 23.00 | [System Design](23.00-system-design.md) | Guarda-chuva | Rascunho |
| 23.01 | [Como Pensar em Design de Sistemas](23.01-como-pensar-em-design-de-sistemas.md) | Específica ampla | Rascunho |
| 23.02 | [Requisitos, Carga e Estimativas](23.02-requisitos-carga-e-estimativas.md) | Específica prática | Rascunho |
| 23.03 | [Disponibilidade vs Consistência](23.03-disponibilidade-vs-consistencia.md) | Específica | Rascunho |
| 23.04 | [Padrões de Consistência](23.04-padroes-de-consistencia.md) | Específica | Rascunho |
| 23.05 | [Padrões de Disponibilidade](23.05-padroes-de-disponibilidade.md) | Específica | Rascunho |
| 23.06 | [DNS no System Design](23.06-dns-no-system-design.md) | Específica | Rascunho |
| 23.07 | [CDN](23.07-cdn.md) | Específica | Rascunho |
| 23.08 | [Load Balancers](23.08-load-balancers.md) | Específica | Rascunho |
| 23.09 | [Camada de Aplicação](23.09-camada-de-aplicacao.md) | Específica | Rascunho |
| 23.10 | [Database no System Design](23.10-database-no-system-design.md) | Específica ampla | Rascunho |
| 23.11 | [Gerenciamento de Dados em Cloud](23.11-gerenciamento-de-dados-em-cloud.md) | Específica | Rascunho |
| 23.12 | [Caching](23.12-caching.md) | Específica prática | Rascunho |
| 23.13 | [Assincronismo em System Design](23.13-assincronismo-em-system-design.md) | Específica | Rascunho |
| 23.14 | [Mensageria em Cloud](23.14-mensageria-em-cloud.md) | Específica prática | Rascunho |
| 23.15 | [Operações Idempotentes](23.15-operacoes-idempotentes.md) | Específica prática | Rascunho |
| 23.16 | [Performance Antipatterns](23.16-performance-antipatterns.md) | Específica | Rascunho |
| 23.17 | [Monitoramento Para System Design](23.17-monitoramento-para-system-design.md) | Específica | Rascunho |
| 23.18 | [Reliability Patterns](23.18-reliability-patterns.md) | Específica ampla | Rascunho |
| 23.19 | [Disponibilidade, Alta Disponibilidade e Resiliência](23.19-disponibilidade-alta-disponibilidade-e-resiliencia.md) | Específica ampla | Rascunho |
| 23.20 | [Padrões de Design em Cloud](23.20-padroes-de-design-em-cloud.md) | Específica ampla | Rascunho |
| 23.21 | [Design e Implementação em Cloud](23.21-design-e-implementacao-em-cloud.md) | Específica prática | Rascunho |
| 23.22 | [Segurança em System Design](23.22-seguranca-em-system-design.md) | Específica ampla | Rascunho |
| 23.23 | [Projeto Prático: Desenhando um Sistema Escalável e Confiável](23.23-projeto-pratico-desenhando-um-sistema-escalavel-e-confiavel.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Desenhar um sistema escalável e confiável para um produto conhecido, como uma plataforma de aulas, uma loja online, um encurtador de URLs, um feed de publicações ou um sistema de notificações:

1. definir requisitos funcionais e não funcionais;
2. declarar suposições de carga, crescimento e disponibilidade;
3. desenhar fluxo de leitura e escrita;
4. escolher DNS, CDN, load balancer e camada de aplicação;
5. escolher banco, modelo de dados, cache e estratégia de consistência;
6. decidir onde usar filas, jobs, pub/sub e idempotência;
7. mapear falhas, gargalos, riscos de segurança e riscos de dados;
8. definir métricas, alertas e sinais de saúde;
9. propor uma versão inicial simples e uma evolução para maior escala;
10. justificar trade-offs em uma apresentação curta.

## O Que Revisar Antes de Avançar

- DNS, HTTP, cache HTTP, APIs, contratos e idempotência.
- SQL, NoSQL, índices, transações, modelagem, backup e restore.
- Logs, métricas, tracing, profiling, testes de carga e failure modes.
- Filas, pub/sub, background jobs e comunicação assíncrona.
- Cloud: regiões, zonas, VPC, CDN, managed databases, filas, serverless, backup e custos.
- SRE: SLI, SLO, saturação, degradação graciosa, rollback e incident response.
- Segurança, IAM, least privilege, threat modeling e governança de dados.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo System Design de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina design de sistemas, requisitos, estimativas, disponibilidade, consistência, DNS, CDN, load balancers, camada de aplicação, bancos, cache, assincronismo, mensageria, idempotência, performance, monitoramento, reliability patterns, cloud e segurança.
- Objetivo do módulo: Quero conseguir desenhar sistemas maiores, explicar trade-offs e justificar decisões técnicas de forma clara.
- Pré-requisitos: web, backend, bancos de dados, APIs, segurança, observabilidade, arquitetura, comunicação assíncrona, cloud, IaC, containers, Kubernetes, SRE, Secure SDLC e governança de dados.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de estimativa e desenho;
3. cenários de arquitetura para eu avaliar trade-offs;
4. perguntas de entrevista para backend/fullstack intermediário-avançado;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação oficial dos provedores de cloud quando uma aula exigir detalhes de um serviço específico.
- Materiais clássicos de SRE, arquitetura distribuída, performance, segurança e operação.
- Documentação das ferramentas usadas em práticas específicas de observabilidade, mensageria, cache e cloud.

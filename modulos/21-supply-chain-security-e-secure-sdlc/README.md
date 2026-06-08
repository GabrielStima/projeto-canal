# Supply Chain Security e Secure SDLC

Este módulo mostra como proteger o caminho entre a ideia, o código, as dependências, o pipeline, os artefatos e os ambientes onde a aplicação roda.

Até aqui, você já estudou segurança em aplicações, testes, análise estática, quality gates, cloud, IaC, CI/CD, containers, Kubernetes e operação. Agora o foco é conectar essas peças em uma pergunta prática: como reduzir o risco de entregar software comprometido?

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- explicar o que é Secure SDLC e supply chain security;
- reconhecer riscos em código, dependências, pipelines, pacotes, imagens, artefatos e credenciais;
- aplicar threat modeling para escolher controles proporcionais;
- proteger secrets e credenciais em ambientes de desenvolvimento, CI/CD e produção;
- entender SAST, DAST, SCA, dependency scanning e SBOM sem confundir seus papéis;
- definir quality gates de segurança com bom senso;
- avaliar riscos no ecossistema npm;
- explicar assinatura, proveniência e confiança em artefatos;
- desenhar um pipeline de entrega com controles mínimos de segurança.

## Por Que Este Módulo Existe

Uma aplicação pode ter autenticação, autorização, testes e deploy automatizado, mas ainda assim ser comprometida pelo processo de entrega. Uma dependência vulnerável, um token exposto, um pipeline permissivo, um pacote malicioso ou um artefato sem rastreabilidade pode abrir caminho para ataques antes mesmo de a aplicação chegar em produção.

Supply chain security existe para proteger a cadeia de produção do software. Secure SDLC existe para colocar segurança ao longo do ciclo de desenvolvimento, em vez de tratar segurança como uma auditoria tardia no fim do projeto.

## Pré-requisitos

- Git, GitHub, branches, pull requests, code review e versionamento semântico.
- Gerenciadores de pacote, npm, `package.json`, dependências e scripts.
- Segurança na web, autenticação, autorização, APIs e princípio do menor privilégio.
- Estratégia de testes, análise estática, testes em CI e quality gates.
- Cloud Fundamentals: IAM, secrets, ambientes, credenciais e auditoria.
- Infrastructure as Code: revisão de mudanças, state sensível, ambientes e automação.
- DevOps: CI/CD, deploy, containers, registries e artefatos.
- SRE: rollback, incident response e operação de sistemas em produção.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 21.00 | [Supply Chain Security e Secure SDLC](21.00-supply-chain-security-e-secure-sdlc.md) | Guarda-chuva | Rascunho |
| 21.01 | [Secure SDLC](21.01-secure-sdlc.md) | Guarda-chuva curta | Rascunho |
| 21.02 | [Threat Modeling](21.02-threat-modeling.md) | Específica ampla | Rascunho |
| 21.03 | [Secrets Management](21.03-secrets-management.md) | Específica prática | Rascunho |
| 21.04 | [Ambientes e Credenciais](21.04-ambientes-e-credenciais.md) | Específica | Rascunho |
| 21.05 | [Permissões Mínimas](21.05-permissoes-minimas.md) | Específica | Rascunho |
| 21.06 | [Segurança em CI/CD](21.06-seguranca-em-ci-cd.md) | Específica ampla | Rascunho |
| 21.07 | [Quality Gates de Segurança e Bloqueio de Merge](21.07-quality-gates-de-seguranca-e-bloqueio-de-merge.md) | Específica prática | Rascunho |
| 21.08 | [SAST](21.08-sast.md) | Específica prática | Rascunho |
| 21.09 | [Dependency Scanning](21.09-dependency-scanning.md) | Específica prática | Rascunho |
| 21.10 | [SCA](21.10-sca.md) | Específica ampla | Rascunho |
| 21.11 | [SBOM](21.11-sbom.md) | Específica | Rascunho |
| 21.12 | [Segurança de Pacotes npm](21.12-seguranca-de-pacotes-npm.md) | Específica prática | Rascunho |
| 21.13 | [Assinatura de Artefatos](21.13-assinatura-de-artefatos.md) | Específica | Rascunho |
| 21.14 | [DAST](21.14-dast.md) | Específica prática | Rascunho |
| 21.15 | [Projeto Prático: Pipeline Seguro de Build, Validação e Entrega](21.15-projeto-pratico-pipeline-seguro-de-build-validacao-e-entrega.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Evolua um projeto Node.js/TypeScript usado nos módulos anteriores para um fluxo de entrega mais seguro:

1. modele ameaças do repositório, pipeline, dependências e deploy;
2. revise secrets, credenciais e permissões do projeto;
3. defina ambientes e acesso mínimo para automação;
4. configure validações de segurança no fluxo de CI/CD;
5. defina quality gates proporcionais ao risco;
6. gere e analise sinais de SAST, dependency scanning e SCA;
7. gere um SBOM do projeto;
8. revise riscos do ecossistema npm no projeto;
9. defina uma estratégia para assinatura ou proveniência de artefatos;
10. rode uma validação dinâmica em ambiente de teste;
11. documente exceções, riscos aceitos e próximos controles.

## O Que Revisar Antes de Avançar

- Git, GitHub, pull requests, branches e code review.
- `package.json`, scripts, dependências, lockfiles e versionamento semântico.
- Segurança em APIs, autenticação, autorização e menor privilégio.
- Testes em CI, análise estática, quality gates e flaky tests.
- IAM, secrets, ambientes, credenciais temporárias e auditoria.
- CI/CD, containers, registries, deploy e rollback.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Supply Chain Security e Secure SDLC de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina segurança no ciclo de desenvolvimento, threat modeling, secrets, credenciais, permissões mínimas, CI/CD seguro, quality gates, SAST, dependency scanning, SCA, SBOM, segurança de pacotes npm, assinatura de artefatos e DAST.
- Objetivo do módulo: Quero conseguir desenhar e revisar um processo de entrega que reduza o risco de código, dependências, pipelines, artefatos e credenciais comprometidos.
- Pré-requisitos: Git, npm, segurança em APIs, testes em CI, análise estática, cloud, IAM, secrets, IaC, CI/CD, containers e operação.

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos de análise de risco;
3. cenários de pipeline e dependências para eu avaliar;
4. perguntas de entrevista para backend/fullstack intermediário;
5. exemplos de aplicação em projetos reais;
6. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- OWASP Cheat Sheet Series e materiais da OWASP sobre software supply chain.
- Documentação oficial do npm quando a aula exigir detalhes de pacote, instalação ou publicação.
- Documentação oficial das ferramentas de CI/CD, SAST, DAST, SCA, SBOM e assinatura escolhidas para práticas específicas.

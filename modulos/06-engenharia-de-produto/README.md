<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Engenharia de Produto

</div>

Este módulo apresenta a ponte entre uma ideia e uma entrega de software. Antes de escolher componente, rota, banco de dados ou framework, uma pessoa desenvolvedora precisa entender qual problema está tentando resolver, para quem, com quais restrições e como saber se a entrega funcionou.

Engenharia de produto não substitui programação. Ela melhora a qualidade das decisões antes, durante e depois da implementação. Requisitos, histórias de usuário, critérios de aceite, feature flags e experimentos ajudam a transformar incerteza em trabalho mais claro, testável e evolutivo.

Neste módulo, você vai usar o PetCare OS como cenário recorrente: uma plataforma para rede de clínicas veterinárias e petshops, com tutores, recepcionistas, clínicos e administradores. O objetivo não é citar o PetCare OS em toda aula, mas aproveitar o domínio para tornar os conceitos de produto mais concretos.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- diferenciar ideia, problema, requisito e solução;
- levantar requisitos em nível introdutório;
- escrever histórias de usuário simples;
- transformar histórias em critérios de aceite verificáveis;
- entender como feature flags reduzem risco de entrega;
- explicar o papel de experimentos e A/B testing em produtos digitais;
- aplicar técnicas simples de product discovery para entender o problema antes de construir;
- priorizar funcionalidades usando frameworks como MoSCoW e RICE;
- definir e interpretar métricas de produto para validar entregas;
- comunicar progresso, impedimentos e mudanças de escopo para stakeholders;
- planejar uma pequena funcionalidade antes de implementar.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a construir páginas, escrever TypeScript, resolver problemas, organizar projetos e trabalhar com ferramentas profissionais. Agora entra uma pergunta diferente: o que vale a pena construir?

Em projetos reais, código quase nunca nasce de um enunciado perfeito. Ele nasce de pedidos incompletos, problemas de usuário, objetivos de negócio, restrições técnicas, prazos, riscos e conversas. Este módulo ensina o vocabulário mínimo para participar dessas conversas sem transformar tudo em código cedo demais.

Este módulo também prepara o caminho para Frontend Moderno, Next.js, backend, bancos de dados e arquitetura. Quanto mais complexa a tecnologia, maior o custo de construir a coisa errada.

## O que você já tem

O módulo 05 deixou você com o repositório base do PetCare OS (`petcare-os-base`), com estrutura de pastas, `package.json`, scripts, `.env.example`, `.gitignore`, `README.md` e histórico Git organizado. Não altere a estrutura técnica aqui. O foco deste módulo é criar a camada de documentação de produto que vai guiar as próximas implementações.

## O que você vai produzir

Ao final, você terá uma pasta `docs/produto/` dentro do repositório do PetCare OS contendo:

- `visao-de-produto.md`: problema, públicos, proposta de valor, escopo e restrições.
- `jornada-principal.md`: jornada do tutor do início ao fim do atendimento.
- `backlog-inicial.md`: funcionalidades priorizadas com justificativa e dependências.
- `decisoes-e-riscos.md`: decisões, riscos, perguntas abertas e próximos passos.

Esse pacote de documentos será retomado nos próximos módulos para construir interfaces, APIs, banco de dados e arquitetura.

## Pré-requisitos

- Entender frontend e backend como papéis na Web.
- Saber construir páginas e pequenos projetos com HTML, CSS, JavaScript e TypeScript.
- Saber ler, criar e organizar arquivos de projeto.
- Entender Git, GitHub, documentação mínima e code review em nível introdutório.
- Ter praticado pequenos projetos locais.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 06.00 | [Engenharia de Produto](06.00-engenharia-de-produto.md) | Guarda-chuva | Rascunho |
| 06.01 | [Requisitos](06.01-requisitos.md) | Específica ampla | Rascunho |
| 06.02 | [Histórias de usuário](06.02-historias-de-usuario.md) | Específica | Rascunho |
| 06.03 | [Critérios de aceite](06.03-criterios-de-aceite.md) | Específica prática | Rascunho |
| 06.04 | [Feature flags](06.04-feature-flags.md) | Específica conceitual/prática | Rascunho |
| 06.05 | [Experimentos e A/B testing](06.05-experimentos-e-ab-testing.md) | Específica introdutória | Rascunho |
| 06.07 | [Product Discovery](06.07-product-discovery.md) | Específica | Rascunho |
| 06.08 | [Priorização](06.08-priorizacao.md) | Específica | Rascunho |
| 06.09 | [Métricas de Produto](06.09-metricas-de-produto.md) | Específica | Rascunho |
| 06.10 | [Comunicação com Stakeholders](06.10-comunicacao-com-stakeholders.md) | Específica | Rascunho |
| 06.11 | [Projeto prático: da ideia à entrega controlada](06.11-projeto-pratico-da-ideia-a-entrega-controlada.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em três blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Do problema à especificação** · aulas 06.00–06.03
Entender a diferença entre ideia, problema e solução; escrever requisitos, histórias de usuário e critérios de aceite verificáveis.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Entrega controlada e aprendizado** · aulas 06.04–06.05
Reduzir risco com feature flags e aprender com experimentos controlados.
Pré-requisito: Bloco A.

**Bloco C — Decisão e comunicação** · aulas 06.07–06.10
Descobrir o problema antes de construir, priorizar funcionalidades, definir métricas e comunicar decisões para stakeholders.
Pré-requisito: Bloco B.

**Síntese prática** · aula 06.11
Consolidar tudo em um pacote de documentos de produto versionado no repositório do PetCare OS.
Pré-requisito: Blocos A, B e C.

Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

Use nomes simples e previsíveis dentro da pasta `exercicios/`:

- [Exercício 01 — Problema e Requisitos do PetCare OS](exercicios/01-problema-e-requisitos.md)
- [Exercício 02 — Histórias de Usuário e Critérios de Aceite do PetCare OS](exercicios/02-historias-e-criterios.md)
- [Exercício 03 — Feature Flag e Experimento do PetCare OS](exercicios/03-feature-flag-e-experimento.md)
- [Exercício 04 — Discovery e Priorização do PetCare OS](exercicios/04-discovery-e-priorizacao.md)
- [Atividade Final do Módulo — Visão e Backlog Inicial do PetCare OS](exercicios/atividade-final-modulo.md)

Cada exercício está ligado à aula que ensina o conhecimento necessário. A atividade final combina habilidades já praticadas, sem introduzir uma dificuldade nova.

Cada arquivo termina com `## Corrija Sua Atividade Com IA` e um prompt copiável que:

- explica o cenário e a tarefa sem depender de arquivos externos;
- apresenta critérios específicos de correção;
- contém o marcador `[COLE SUA RESPOSTA AQUI]`;
- pede acertos, imprecisões e dicas antes de qualquer resposta completa.

## Projeto ou Prática do Módulo

A prática integradora deste módulo é a [Atividade Final — Visão e Backlog Inicial do PetCare OS](exercicios/atividade-final-modulo.md). Nela, você transforma o que aprendeu em um pacote de documentos de produto versionado no repositório do PetCare OS, que será a base para as implementações dos próximos módulos.

## O Que Revisar Antes de Avançar

- Diferença entre problema e solução.
- Diferença entre requisito funcional e requisito não funcional.
- Como escrever uma história de usuário sem esconder regra importante.
- Como escrever critérios de aceite verificáveis.
- Como usar feature flags para reduzir risco.
- Por que experimentos precisam de hipótese e métrica.
- Como documentar decisões antes de abrir um pull request.
- Onde os documentos de produto serão retomados no módulo 07.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Engenharia de Produto de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina a entender problema, contexto, requisitos, histórias, critérios de aceite, entrega controlada e experimentos antes de implementar uma funcionalidade.
- Objetivo do módulo: Quero conseguir transformar uma ideia em um plano de entrega claro, verificável e menos arriscado.
- Pré-requisitos: fundamentos da Web, pequenos projetos com TypeScript, Git, GitHub, documentação mínima e code review.

Os assuntos estudados foram:
- Requisitos
- Histórias de usuário
- Critérios de aceite
- Feature flags
- Experimentos e A/B testing
- Product discovery
- Priorização
- Métricas de produto
- Comunicação com stakeholders
- Projeto prático da ideia a entrega controlada

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em uma funcionalidade pequena;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Materiais internos do próprio projeto.
- Documentação mínima de projeto do módulo 05.
- Práticas comuns de product discovery, product delivery e validação de funcionalidades.

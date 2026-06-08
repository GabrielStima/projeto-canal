# Engenharia de Produto

Este módulo apresenta a ponte entre uma ideia e uma entrega de software. Antes de escolher componente, rota, banco de dados ou framework, uma pessoa desenvolvedora precisa entender qual problema está tentando resolver, para quem, com quais restrições e como saber se a entrega funcionou.

Engenharia de produto não substitui programação. Ela melhora a qualidade das decisões antes, durante e depois da implementação. Requisitos, histórias de usuário, critérios de aceite, feature flags e experimentos ajudam a transformar incerteza em trabalho mais claro, testável e evolutivo.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- diferenciar ideia, problema, requisito e solução;
- levantar requisitos em nível introdutório;
- escrever histórias de usuário simples;
- transformar histórias em critérios de aceite verificáveis;
- entender como feature flags reduzem risco de entrega;
- explicar o papel de experimentos e A/B testing em produtos digitais;
- planejar uma pequena funcionalidade antes de implementar.

## Por Que Este Módulo Existe

Nos módulos anteriores, você aprendeu a construir páginas, escrever TypeScript, resolver problemas, organizar projetos e trabalhar com ferramentas profissionais. Agora entra uma pergunta diferente: o que vale a pena construir?

Em projetos reais, código quase nunca nasce de um enunciado perfeito. Ele nasce de pedidos incompletos, problemas de usuário, objetivos de negócio, restrições técnicas, prazos, riscos e conversas. Este módulo ensina o vocabulário mínimo para participar dessas conversas sem transformar tudo em código cedo demais.

Este módulo também prepara o caminho para Frontend Moderno, Next.js, backend, bancos de dados e arquitetura. Quanto mais complexa a tecnologia, maior o custo de construir a coisa errada.

## Pré-requisitos

- Entender frontend e backend como papéis na Web.
- Saber construir páginas e pequenos projetos com HTML, CSS, JavaScript e TypeScript.
- Saber ler, criar e organizar arquivos de projeto.
- Entender Git, GitHub, documentação mínima e code review em nível introdutório.
- Ter praticado pequenos projetos locais.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 06.00 | Engenharia de Produto | Guarda-chuva | Rascunho |
| 06.01 | [Requisitos](06.01-requisitos.md) | Específica ampla | Rascunho |
| 06.02 | [Histórias de usuário](06.02-historias-de-usuario.md) | Específica | Rascunho |
| 06.03 | [Critérios de aceite](06.03-criterios-de-aceite.md) | Específica prática | Rascunho |
| 06.04 | [Feature flags](06.04-feature-flags.md) | Específica conceitual/prática | Rascunho |
| 06.05 | [Experimentos e A/B testing](06.05-experimentos-e-ab-testing.md) | Específica introdutória | Rascunho |
| 06.06 | [Projeto prático: da ideia a entrega controlada](06.06-projeto-pratico-da-ideia-a-entrega-controlada.md) | Síntese prática | Rascunho |

## Projeto ou Prática do Módulo

Planeje uma pequena funcionalidade antes de implementar.

Sugestão: uma funcionalidade de favoritos em uma aplicação de catálogo.

1. Descreva o problema do usuário.
2. Liste requisitos funcionais e não funcionais simples.
3. Escreva duas ou três histórias de usuário.
4. Defina critérios de aceite para cada história.
5. Planeje uma feature flag para liberar a funcionalidade com controle.
6. Descreva um experimento simples para aprender se a funcionalidade gera valor.
7. Registre riscos, perguntas abertas e próximos passos.

## O Que Revisar Antes de Avançar

- Diferença entre problema e solução.
- Diferença entre requisito funcional e requisito não funcional.
- Como escrever uma história de usuário sem esconder regra importante.
- Como escrever critérios de aceite verificáveis.
- Como usar feature flags para reduzir risco.
- Por que experimentos precisam de hipótese e métrica.
- Como documentar decisões antes de abrir um pull request.

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

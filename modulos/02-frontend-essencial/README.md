<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Frontend Essencial

</div>

Este módulo apresenta a base visual e interativa da Web antes de frameworks. A ideia é entender como uma página é estruturada com HTML, apresentada com CSS e transformada em interface interativa com JavaScript no browser.

Ao longo das aulas, você vai usar o PetCare OS como pano de fundo recorrente. Alguns exemplos e exercícios usam telas do Portal do Tutor, do painel de atendimentos e da agenda da clínica para tornar os conceitos mais concretos. Nem toda aula menciona o projeto: quando um exemplo independente ensina melhor, usamos outro contexto.

O foco não é decorar todas as tags, propriedades ou APIs. O objetivo é construir repertório suficiente para criar páginas simples, entender exemplos reais, evitar erros comuns e chegar melhor preparado aos módulos de TypeScript, ferramentas e frontend moderno.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- estruturar uma página HTML simples;
- escolher elementos HTML com intenção semântica;
- criar formulários básicos e acessíveis;
- aplicar CSS para aparência e organização visual;
- entender como cascata, especificidade e herança resolvem conflitos entre regras;
- usar convenções de nomenclatura para organizar classes CSS;
- construir layouts simples e responsivos;
- usar JavaScript no browser para interações pequenas;
- entender o DOM como representação da página;
- reagir a eventos de usuário;
- reconhecer fundamentos de acessibilidade;
- considerar diferenças entre browsers e suporte de funcionalidades.

## Por Que Este Módulo Existe

Muita gente começa frontend por frameworks. Isso pode funcionar por um tempo, mas cria buracos importantes: a pessoa usa componentes sem entender HTML, estiliza sem entender layout, manipula estado sem saber o que é evento e corrige bugs sem entender o browser.

Este módulo prepara o terreno. Antes de frameworks, bundlers, validação avançada ou testes de interface, você precisa saber o que o browser recebe, interpreta, renderiza e expõe para interação.

No contexto do PetCare OS, este módulo produz a primeira versão navegável do Portal do Tutor, ainda sem framework. Essa base será revisitada e evoluída em módulos futuros de frontend moderno.

## Pré-requisitos

- Entender o papel do browser na Web.
- Entender cliente, servidor, request e response.
- Saber que frontend e backend são papéis dentro de uma aplicação.
- Ter noção do caminho completo de uma requisição web.
- Não é necessário dominar JavaScript ainda.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 02.00 | [Frontend Essencial](02.00-frontend-essencial.md) | Guarda-chuva | Rascunho |
| 02.01 | [HTML](02.01-html.md) | Específica ampla | Rascunho |
| 02.02 | [Semântica HTML](02.02-semantica-html.md) | Específica | Rascunho |
| 02.03 | [Formulários HTML](02.03-formularios-html.md) | Específica | Rascunho |
| 02.04 | [CSS](02.04-css.md) | Específica ampla | Rascunho |
| 02.05 | [Cascata, Especificidade e Herança](02.05-cascata-especificidade-e-heranca.md) | Específica | Rascunho |
| 02.06 | [Convenções de Nomenclatura](02.06-convencoes-de-nomenclatura.md) | Específica | Rascunho |
| 02.07 | [Layout com CSS](02.07-layout-com-css.md) | Específica | Rascunho |
| 02.08 | [Responsividade](02.08-responsividade.md) | Específica | Rascunho |
| 02.09 | [JavaScript no Browser](02.09-javascript-no-browser.md) | Específica ampla | Rascunho |
| 02.10 | [DOM](02.10-dom.md) | Específica | Rascunho |
| 02.11 | [Eventos](02.11-eventos.md) | Específica | Rascunho |
| 02.12 | [Acessibilidade](02.12-acessibilidade.md) | Específica transversal | Rascunho |
| 02.13 | [Browsers e Compatibilidade](02.13-browsers-e-compatibilidade.md) | Síntese | Rascunho |
| 02.14 | [Projeto Prático: Portal do Tutor Navegável](02.14-projeto-pratico-portal-do-tutor-navegavel.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco 1 — Estrutura e semântica** · aulas 02.00–02.03
HTML, semântica e formulários. Aqui você começa a dar forma ao conteúdo que será exibido no Portal do Tutor.
Pré-requisito: nenhum dentro do módulo.

**Bloco 2 — Estilo e layout** · aulas 02.04–02.08
CSS, cascata, nomenclatura, layout e responsividade. Você vai aprender a apresentar o conteúdo de forma organizada e adaptável.
Pré-requisito: Bloco 1.

**Bloco 3 — Interatividade** · aulas 02.09–02.11
JavaScript no browser, DOM e eventos. Você vai dar comportamento às páginas, como aprovar um orçamento ou atualizar um status.
Pré-requisito: Bloco 2.

**Bloco 4 — Qualidade e projeto final** · aulas 02.12–02.14
Acessibilidade, compatibilidade e o projeto prático integrador. Você vai construir a primeira versão navegável do Portal do Tutor.
Pré-requisito: Blocos 1, 2 e 3.

## Exercícios

Use os exercícios para praticar habilidades isoladas antes de juntar tudo na atividade final:

- [Exercício 01 — Card de Status do Pet](exercicios/01-card-de-status-do-pet.md)
- [Exercício 02 — Formulário de Triagem](exercicios/02-formulario-de-triagem.md)
- [Exercício 03 — Lista de Atendimentos](exercicios/03-lista-de-atendimentos.md)
- [Atividade Final do Módulo — Portal do Tutor Navegável](exercicios/atividade-final-modulo.md)

## Projeto ou Prática do Módulo

A atividade final integra todo o módulo. Você vai construir a primeira versão navegável do Portal do Tutor do PetCare OS, ainda sem framework.

Essa versão deve conter:

1. Uma tela com o status do pet (nome, espécie, tutor, status atual, previsão de alta e linha do tempo resumida).
2. Uma segunda tela com orçamento pendente ou histórico resumido.
3. Navegação entre as telas usando JavaScript, sem recarregar a página.
4. HTML semântico, CSS responsivo e acessibilidade básica.
5. Três arquivos: `index.html`, `styles.css` e `script.js`.

Este trabalho será retomado em módulos futuros de frontend moderno, quando você reconstruirá essa ideia com componentes reutilizáveis e rotas.

## O Que Revisar Antes de Avançar

- Estrutura mínima de um documento HTML.
- Diferença entre HTML estrutural e aparência visual.
- Semântica HTML.
- Formulários e labels.
- Seletores e box model em CSS.
- Cascata, especificidade e herança.
- Convenções de nomenclatura para classes CSS.
- Layout e responsividade.
- Papel do JavaScript no browser.
- DOM e eventos.
- Acessibilidade básica.
- Compatibilidade entre browsers.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Frontend Essencial de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo Frontend Essencial constrói a base visual e interativa da Web antes de frameworks, conectando HTML, CSS e JavaScript no browser.
- Objetivo do módulo: Ao final, devo conseguir estruturar páginas HTML, aplicar CSS, criar layouts responsivos, usar JavaScript no browser para interações simples, entender DOM e eventos, e revisar acessibilidade e compatibilidade.
- Pré-requisitos: fundamentos da Internet e da Web, papel do browser, cliente-servidor, request/response, HTTP, cache HTTP, frontend e backend como papéis na Web, e caminho completo de uma requisição web.

Os assuntos estudados foram:
- HTML
- Semântica HTML
- Formulários
- CSS
- Cascata, especificidade e herança
- Convenções de nomenclatura
- Layout
- Responsividade
- JavaScript no browser
- DOM
- Eventos
- Acessibilidade
- Browsers e compatibilidade

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação da MDN sobre HTML.
- Documentação da MDN sobre CSS.
- Documentação da MDN sobre JavaScript no browser.
- Documentação da MDN sobre Web APIs.
- Documentação da MDN sobre acessibilidade.

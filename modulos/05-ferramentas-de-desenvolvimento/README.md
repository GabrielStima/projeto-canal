<div align="center">

![Readme Banner](../../assets/banner-introducao.png)

# Ferramentas de Desenvolvimento

</div>

Este módulo organiza o fluxo básico de trabalho de uma pessoa desenvolvedora. Depois de aprender fundamentos de web, frontend, TypeScript, algoritmos e estruturas de dados, agora o foco passa a ser como trabalhar em projetos reais com editor, terminal, Git, GitHub, pacotes, qualidade de código e documentação mínima.

Ferramentas não substituem conhecimento de programação. Elas reduzem atrito, ajudam a repetir tarefas com segurança e criam um vocabulário comum para colaborar com outras pessoas.

## Objetivo do Módulo

Ao final deste módulo, você deve ser capaz de:

- configurar um ambiente de desenvolvimento básico;
- navegar por arquivos e executar comandos no terminal;
- entender o papel do shell;
- versionar um projeto com Git;
- publicar e colaborar em repositórios usando GitHub;
- instalar dependências com gerenciadores de pacote;
- ler e escrever scripts simples em `package.json`;
- entender versionamento semântico em nível prático;
- usar linter, formatter e bundler em nível introdutório;
- documentar o mínimo necessário para outra pessoa rodar o projeto;
- participar de code reviews com postura técnica e colaborativa.

## Por Que Este Módulo Existe

Nos módulos anteriores, você escreveu código e resolveu problemas. Em um projeto real, porém, escrever código é apenas uma parte do trabalho.

Você também precisa abrir o projeto, instalar dependências, rodar comandos, configurar variáveis, salvar histórico de alterações, compartilhar código, revisar mudanças e explicar como o projeto funciona. Esse conjunto de práticas forma o fluxo profissional de desenvolvimento.

Este módulo prepara os próximos passos da formação: frontend moderno, Next.js, backend, bancos de dados, testes, deploy, DevOps e arquitetura. Todos esses temas dependem de um ambiente de desenvolvimento minimamente organizado.

## O que você já tem

O módulo 04 deixou você com prática em algoritmos e estruturas de dados, incluindo a fila de prioridade de triagem do PetCare OS. Não altere esse trabalho aqui. O foco deste módulo é criar a base de ferramentas que permitirá evoluir qualquer código com segurança.

## O que você vai produzir

Ao final, você terá um repositório base do PetCare OS chamado `petcare-os-base`, com:

- estrutura de pastas clara;
- `package.json` com scripts `dev`, `build`, `check` e `format`;
- `.env.example` documentando variáveis de ambiente;
- `.gitignore` protegendo arquivos sensíveis e gerados;
- `README.md` com instruções mínimas;
- histórico Git com commits bem descritos;
- branch `feature/readme-inicial` criada e mergeada.

Esse repositório será retomado nos próximos módulos.

## Pré-requisitos

- Saber criar e editar arquivos de código.
- Entender HTML, CSS, JavaScript e TypeScript em nível introdutório.
- Entender módulos em TypeScript.
- Ter praticado pequenos projetos locais.
- Saber a diferença entre frontend e backend em alto nível.

## Aulas

| Ordem | Aula | Tipo | Status |
| --- | --- | --- | --- |
| 05.00 | [Ferramentas de Desenvolvimento](05.00-ferramentas-de-desenvolvimento.md) | Guarda-chuva | Rascunho |
| 05.01 | [Editor/IDE e produtividade](05.01-editor-ide-e-produtividade.md) | Específica ampla | Rascunho |
| 05.02 | [Terminal e linha de comando](05.02-terminal-e-linha-de-comando.md) | Guarda-chuva curta | Rascunho |
| 05.03 | [Shell básico](05.03-shell-basico.md) | Específica prática | Rascunho |
| 05.04 | [Ambientes de desenvolvimento](05.04-ambientes-de-desenvolvimento.md) | Específica ampla | Rascunho |
| 05.05 | [Variáveis de ambiente](05.05-variaveis-de-ambiente.md) | Específica | Rascunho |
| 05.06 | [Versionamento semântico](05.06-versionamento-semantico.md) | Específica conceitual | Rascunho |
| 05.07 | [Gerenciadores de pacote](05.07-gerenciadores-de-pacote.md) | Guarda-chuva curta | Rascunho |
| 05.08 | [npm, pnpm e yarn](05.08-npm-pnpm-e-yarn.md) | Específica comparativa | Rascunho |
| 05.09 | [VCS: controle de versão](05.09-vcs-controle-de-versao.md) | Guarda-chuva | Rascunho |
| 05.10 | [Git](05.10-git.md) | Específica prática | Rascunho |
| 05.11 | [VCS hosting](05.11-vcs-hosting.md) | Guarda-chuva curta | Rascunho |
| 05.12 | [GitHub](05.12-github.md) | Específica prática | Rascunho |
| 05.13 | [Linter e formatters](05.13-linter-e-formatters.md) | Específica | Rascunho |
| 05.14 | [Module bundlers](05.14-module-bundlers.md) | Guarda-chuva curta | Rascunho |
| 05.15 | [Documentação mínima de projeto](05.15-documentacao-minima-de-projeto.md) | Específica prática | Rascunho |
| 05.16 | [Code review](05.16-code-review.md) | Específica prática | Rascunho |
| 05.17 | [Projeto prático: fluxo profissional de desenvolvimento](05.17-projeto-pratico-fluxo-profissional-de-desenvolvimento.md) | Síntese prática | Rascunho |

## Trilha de Estudo

Este módulo está organizado em quatro blocos. Siga a ordem dos blocos. Dentro de cada bloco, siga a sequência da tabela de aulas.

**Bloco A — Ambiente de trabalho** · aulas 05.00–05.03
Editor, terminal e shell como pontapé do fluxo profissional.
Pré-requisito: nenhum (ponto de entrada do módulo).

**Bloco B — Configuração e dependências** · aulas 05.04–05.08
Ambientes, variáveis de ambiente, versionamento semântico e gerenciadores de pacote.
Pré-requisito: Bloco A.

**Bloco C — Versionamento e colaboração** · aulas 05.09–05.12
Git local, hospedagem de repositórios e fluxo de colaboração no GitHub.
Pré-requisito: Bloco B.

**Bloco D — Qualidade, documentação e revisão** · aulas 05.13–05.17
Linters, formatters, bundlers, README e code review, culminando no repositório base do PetCare OS.
Pré-requisito: Bloco C.

Aulas dentro de um mesmo bloco podem ter dependências entre si — consulte o campo "Onde Esta Aula Entra na Formação" em cada arquivo para detalhes.

## Exercícios

Use nomes simples e previsíveis dentro da pasta `exercicios/`:

- [Exercício 01 — Variáveis e ambiente do PetCare OS](exercicios/01-variaveis-e-ambiente.md)
- [Exercício 02 — Versionando uma mudança do PetCare OS](exercicios/02-versionando-com-git.md)
- [Exercício 03 — Revisando uma mudança no PetCare OS](exercicios/03-revisando-uma-mudanca.md)
- [Exercício 04 — Scripts de qualidade do PetCare OS](exercicios/04-scripts-de-qualidade.md)
- [Atividade Final do Módulo — Repositório base do PetCare OS](exercicios/atividade-final-modulo.md)

Cada exercício está ligado à aula que ensina o conhecimento necessário. A atividade final combina habilidades já praticadas, sem introduzir uma dificuldade nova.

Cada arquivo termina com `## Corrija Sua Atividade Com IA` e um prompt copiável que:

- explica o cenário e a tarefa sem depender de arquivos externos;
- apresenta critérios específicos de correção;
- contém o marcador `[COLE SUA RESPOSTA AQUI]`;
- pede acertos, imprecisões e dicas antes de qualquer resposta completa.

## Projeto ou Prática do Módulo

A prática integradora deste módulo é a [Atividade Final — Repositório base do PetCare OS](exercicios/atividade-final-modulo.md). Nela, você transforma o que aprendeu em um repositório organizado, versionado e documentado, que será a base evolutiva do projeto nos próximos módulos.

## O Que Revisar Antes de Avançar

- Como navegar por pastas e arquivos.
- Diferença entre terminal, shell e comando.
- Comandos básicos de Git: `status`, `add`, `commit`, `branch`, `switch`, `merge`, `push` e `pull`.
- `package.json`, scripts e dependências.
- Diferença entre dependência de runtime e dependência de desenvolvimento.
- Versionamento semântico.
- Papel de linter, formatter e bundler.
- Como escrever instruções mínimas para rodar um projeto.
- Como participar de uma revisão de código.

## Prompt de Revisão do Módulo

```text
Estou finalizando o módulo Ferramentas de Desenvolvimento de uma formação fullstack JavaScript/TypeScript.

Contexto do módulo:
- Descrição do módulo: O módulo ensina o fluxo básico de trabalho de uma pessoa desenvolvedora profissional.
- Objetivo do módulo: Quero conseguir abrir, configurar, versionar, executar, documentar e compartilhar um projeto JavaScript/TypeScript com segurança.
- Pré-requisitos: fundamentos de web, frontend essencial, TypeScript, módulos e pequenos projetos locais.

Os assuntos estudados foram:
- Editor/IDE e produtividade
- Terminal, linha de comando e shell
- Ambientes de desenvolvimento
- Variáveis de ambiente
- Versionamento semântico
- Gerenciadores de pacote
- npm, pnpm e yarn
- VCS, Git, VCS hosting e GitHub
- Linter e formatters
- Module bundlers
- Documentação mínima de projeto
- Code review

Crie uma revisão guiada com:
1. perguntas conceituais;
2. exercícios práticos em um projeto TypeScript;
3. perguntas de entrevista para iniciante;
4. exemplos de aplicação em projetos reais;
5. uma avaliação final com critérios claros.

Não entregue respostas completas antes de eu tentar responder.
```

## Referências Gerais

- Documentação oficial do Git.
- Documentação oficial do GitHub.
- Documentação oficial do npm.
- Documentação das ferramentas usadas no projeto.

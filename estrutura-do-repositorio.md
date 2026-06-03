# Estrutura do Repositório

Este documento descreve a estrutura definitiva do repositório para a V2.

A V2 organiza o projeto em documentos principais, templates reutilizáveis e módulos do curso.

## Estrutura Atual

```text
.
├── README.md
├── curriculo.md
├── estrutura-do-repositorio.md
├── templates/
│   ├── aula.md
│   ├── modulo.md
│   └── prompt-ia.md
└── modulos/
    ├── 00-introducao-e-metodo-de-estudo/
    ├── 01-fundamentos-da-internet-e-web/
    ├── 02-frontend-essencial/
    ├── 03-programacao-com-typescript/
    ├── 04-algoritmos-e-estruturas-de-dados/
    ├── 05-ferramentas-de-desenvolvimento/
    ├── 06-frontend-moderno/
    ├── 07-nextjs-e-aplicacoes-fullstack/
    ├── 08-bancos-de-dados/
    ├── 09-backend-com-nodejs/
    ├── 10-autenticacao-autorizacao-e-seguranca/
    ├── 11-qualidade-observabilidade-e-performance/
    ├── 12-design-de-software/
    ├── 13-arquitetura-de-software/
    ├── 14-tempo-real-e-comunicacao-assincrona/
    ├── 15-devops-containers-e-kubernetes/
    ├── 16-system-design/
    └── 17-documentacao-tecnica/
```

## Responsabilidade de Cada Área

### `README.md`

Entrada pública do projeto. Deve explicar a proposta, o status, como estudar e como navegar.

### `curriculo.md`

Matriz curricular macro. Deve mostrar a ordem recomendada, os módulos e os assuntos principais.

### `estrutura-do-repositorio.md`

Documento de arquitetura editorial do repositório. Deve explicar como os arquivos serão organizados e por quê.

### `templates/`

Modelos reutilizáveis para aulas, módulos e prompts de estudo com IA.

- `aula.md`: estrutura padrão para uma aula individual.
- `modulo.md`: estrutura padrão para a página de um módulo.
- `prompt-ia.md`: estrutura base para prompts reutilizáveis de estudo.

### `modulos/`

Conteúdo real do curso. Cada módulo deve ter um `README.md` próprio e arquivos de aula numerados quando começar a receber conteúdo.

Enquanto um módulo ainda não tiver aulas, ele pode conter apenas um arquivo `.gitkeep` para preservar a pasta no Git.

## Convenções de Nome

Arquivos e pastas devem usar:

- letras minúsculas;
- números para ordenar módulos e aulas;
- hífen entre palavras;
- nomes sem acentos para evitar problemas de compatibilidade.

Exemplo:

```text
04-algoritmos-e-estruturas-de-dados/
├── README.md
├── 04.01-complexidade-de-algoritmos.md
├── 04.02-tempo-vs-espaco.md
├── 04.03-algoritmos-de-ordenacao.md
├── 04.04-bubble-sort.md
└── 04.05-merge-sort.md
```

## Regra Sobre Ordem das Aulas

A ordem oficial do curso deve ficar documentada no currículo e refletida na numeração dos arquivos.

O repositório pode ser navegável por módulo, mas o aluno sempre deve conseguir identificar qual é a próxima aula da sequência.

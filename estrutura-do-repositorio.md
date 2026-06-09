# Estrutura do Repositório

Este documento descreve a estrutura definitiva do repositório.

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
├── assets/
├── desafio/
└── modulos/
    ├── 00-introducao-e-metodo-de-estudo/
    ├── 01-fundamentos-da-internet-e-web/
    ├── 02-frontend-essencial/
    ├── 03-programacao-com-typescript/
    ├── 04-algoritmos-e-estruturas-de-dados/
    ├── 05-ferramentas-de-desenvolvimento/
    ├── 06-engenharia-de-produto/
    ├── 07-frontend-moderno/
    ├── 08-nextjs-e-aplicacoes-fullstack/
    ├── 09-bancos-de-dados/
    ├── 10-backend-com-nodejs/
    ├── 11-api-design-profissional/
    ├── 12-autenticacao-autorizacao-e-seguranca/
    ├── 13-qualidade-observabilidade-e-performance/
    ├── 14-design-de-software/
    ├── 15-arquitetura-de-software/
    ├── 16-tempo-real-e-comunicacao-assincrona/
    ├── 17-cloud-fundamentals/
    ├── 18-infrastructure-as-code/
    ├── 19-devops-containers-e-kubernetes/
    ├── 20-sre-operacao-incidentes/
    ├── 21-supply-chain-security-e-secure-sdlc/
    ├── 22-privacidade-e-governanca-de-dados/
    ├── 23-system-design/
    ├── 24-ia-para-desenvolvedores/
    └── 25-documentacao-tecnica/
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

### `assets/`

Pasta com algumas imagens usadas nos READMEs quando necessário.

### `desafio/`

Projeto prático de portfólio que servirá como o principal **fio condutor** de toda a sua jornada de aprendizado nesta formação.

### `modulos/`

Conteúdo real da formação. Cada módulo deve ter um `README.md` próprio e arquivos de aula numerados quando começar a receber conteúdo.

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

A ordem oficial da formação deve ficar documentada no currículo e refletida na numeração dos arquivos.

O repositório pode ser navegável por módulo, mas o aluno sempre deve conseguir identificar qual é a próxima aula da sequência.

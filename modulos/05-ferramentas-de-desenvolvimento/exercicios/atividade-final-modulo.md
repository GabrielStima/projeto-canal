# Atividade Final do Módulo — Repositório Base do PetCare OS

## O que você já sabe

Neste módulo você estudou editor, terminal, shell, ambientes de desenvolvimento, variáveis de ambiente, versionamento semântico, gerenciadores de pacote, Git, GitHub, linters, formatters, module bundlers, documentação mínima e code review. Agora você vai reunir essas habilidades em um único artefato.

## Tarefa

Crie um repositório local chamado `petcare-os-base` que será a base de desenvolvimento do PetCare OS. Esse repositório deve conter:

1. Uma pasta `src/` com um arquivo `index.ts` que exporte uma função simples. Sugestão: `saudacao(nome: string): string` que retorna `"Bem-vindo ao PetCare OS, {nome}"`.
2. Um `package.json` inicializado com npm, pnpm ou yarn, contendo pelo menos os scripts:
   - `dev` — roda o projeto localmente (pode ser `node src/index.ts` ou similar);
   - `build` — prepara o projeto para produção (pode ser um `echo` ou um comando real se você souber);
   - `check` — verifica tipos ou roda validação (pode ser `tsc --noEmit` ou um comando placeholder);
   - `format` — formata o código (pode ser `echo "formatar"` se ainda não configurou Prettier).
3. Um arquivo `.env.example` com pelo menos duas variáveis de ambiente relevantes para o PetCare OS.
4. Um arquivo `.gitignore` que ignore `node_modules`, arquivos `.env` e a pasta `dist/`.
5. Um `README.md` com:
   - uma descrição curta do projeto;
   - pré-requisitos;
   - instruções de instalação;
   - instruções para criar o `.env` a partir do `.env.example`;
   - os principais scripts disponíveis.
6. Um histórico Git com pelo menos três commits pequenos e bem descritos.
7. Uma branch `feature/readme-inicial` com uma melhoria no README, mergeada de volta para a branch principal com `git merge`.

Se você não souber configurar TypeScript ou Prettier de verdade, pode usar comandos placeholder. O objetivo desta atividade é praticar a organização, versionamento e documentação, não criar uma aplicação completa.

## Onde esse trabalho será retomado

O repositório base criado aqui será evoluído nos próximos módulos. Em Frontend Moderno e Next.js você adicionará componentes e páginas. Em Backend e Banco de Dados você expandirá a estrutura com serviços e modelos. Guarde esse repositório com carinho: ele é a semente do PetCare OS.

## Critérios de Correção

- Estrutura de pastas clara (`src/` na raiz).
- `package.json` com scripts `dev`, `build`, `check` e `format`.
- `.env.example` com pelo menos duas variáveis relevantes.
- `.gitignore` contendo `node_modules`, `.env` e `dist/`.
- `README.md` com descrição, pré-requisitos, instalação, `.env` e scripts.
- Pelo menos três commits com mensagens descritivas.
- Branch `feature/readme-inicial` criada, usada e mergeada.
- Nenhum arquivo sensível real versionado.

## Corrija Sua Atividade Com IA

```text
Cenário: estou finalizando o módulo Ferramentas de Desenvolvimento e criei um repositório base chamado petcare-os-base para o PetCare OS, uma plataforma para clínicas veterinárias e petshops.

Tarefa: avalie se meu repositório atende aos critérios abaixo. Eu vou descrever a estrutura, os arquivos, os scripts e o histórico Git.

Critérios de correção:
1. Pasta src/ na raiz com um arquivo index.ts exportando uma função simples.
2. package.json com os scripts dev, build, check e format.
3. .env.example com pelo menos duas variáveis relevantes para o PetCare OS.
4. .gitignore contendo node_modules, .env e dist/.
5. README.md com descrição, pré-requisitos, instalação, instrução para criar .env e scripts.
6. Pelo menos três commits com mensagens descritivas.
7. Branch feature/readme-inicial criada, usada e mergeada.
8. Nenhum arquivo sensível real versionado.

[COLE SUA RESPOSTA AQUI]

Inclua a estrutura de pastas, o conteúdo dos arquivos e o histórico de commits.

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas. Só depois mostre uma versão de referência.
```

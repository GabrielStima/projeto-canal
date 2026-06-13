# Exercício 01 — Configuração do portal

## Objetivo

Criar e configurar o projeto Next.js que servirá de base para o Portal do Tutor do PetCare OS.

## Cenário

O portal do tutor foi construído em React puro no módulo anterior. Agora você vai criar um projeto Next.js chamado `petcare-portal` para abrigar a versão nova do portal, com rotas baseadas em arquivos, renderização no servidor e APIs internas.

## Tarefa

1. Crie um projeto Next.js com TypeScript usando o comando:

   ```bash
   npx create-next-app@latest petcare-portal --typescript --eslint --app --no-tailwind --src-dir --import-alias "@/*"
   ```

2. Rode o servidor de desenvolvimento com `npm run dev`.

3. Substitua o conteúdo da página inicial (`src/app/page.tsx`) por uma mensagem simples como "Portal do Tutor — PetCare OS".

4. Crie um arquivo `.env.local` com uma variável pública:

   ```bash
   NEXT_PUBLIC_APP_NAME=PetCare OS
   ```

5. Exiba o nome da aplicação vindo de `process.env.NEXT_PUBLIC_APP_NAME` na página inicial.

## Requisitos

- O projeto deve rodar sem erros em `http://localhost:3000`.
- A página inicial deve mostrar o nome do portal.
- O `.env.local` deve estar listado no `.gitignore` gerado.
- O alias `@/*` deve funcionar para importações.

## Critérios de avaliação

- O projeto foi criado com as flags corretas.
- O servidor de desenvolvimento inicia sem erros.
- A página inicial reflete o contexto do PetCare OS.
- A variável de ambiente pública é exibida corretamente.
- Segredos não são commitados.

## Onde este trabalho será retomado

Este projeto é a base de todos os exercícios seguintes e da atividade final. As rotas, layouts, componentes e APIs criados nos próximos arquivos serão adicionados dentro deste mesmo repositório. No módulo 09 — Bancos de Dados, você conectará os Route Handlers a um banco real.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de configuração de projeto. Vou te enviar os passos que segui para criar o projeto Next.js do Portal do Tutor do PetCare OS.

Cenário: preciso de um projeto Next.js com TypeScript, App Router, ESLint e alias de importação, pronto para receber as rotas do portal do tutor.

Tarefa: revise minha configuração considerando:
1. O comando create-next-app usou as flags corretas?
2. O servidor inicia sem erros?
3. A página inicial mostra o nome do portal?
4. A variável NEXT_PUBLIC_APP_NAME está sendo exibida?
5. O .env.local está protegido do Git?
6. O alias @/* está configurado?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

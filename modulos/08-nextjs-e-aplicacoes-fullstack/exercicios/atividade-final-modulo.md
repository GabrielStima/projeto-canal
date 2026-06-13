# Atividade Final do Módulo

## O que você vai produzir

Uma aplicação Next.js publicável que simula o **Portal do Tutor** do PetCare OS. O portal terá navegação, listagem de pets, detalhes, cadastro de pet, orçamentos pendentes e aprovação simulada. Esta aplicação será a base para o módulo 09 — Bancos de Dados, onde os dados passarão a ser persistentes.

## O que você já construiu

Nos exercícios anteriores, você criou:
- o projeto `petcare-portal` configurado com Next.js e TypeScript;
- a estrutura de rotas e o layout da área `/tutor`;
- a listagem de pets em um Server Component com `loading.tsx` e `error.tsx`;
- o botão de aprovação de orçamento como Client Component;
- o Route Handler `/api/orcamentos/[id]` para simular aprovação;
- o formulário de cadastro de pet e o Route Handler `/api/pets`.

## Tarefa

Integre os exercícios anteriores em uma aplicação coesa com as seguintes telas e funcionalidades:

1. **Página inicial** (`/`) — apresentação simples do Portal do Tutor com link para entrar na área `/tutor`.
2. **Dashboard do tutor** (`/tutor`) — resumo com quantidade de pets e orçamentos pendentes.
3. **Lista de Pets** (`/tutor/pets`) — lista com dados buscados no servidor, loading e tratamento de erro.
4. **Detalhes do Pet** (`/tutor/pets/[id]`) — informações do pet e status do último atendimento.
5. **Cadastro de Pet** (`/tutor/pets/novo`) — formulário com validação e feedback.
6. **Orçamentos** (`/tutor/orcamentos`) — lista de orçamentos pendentes com botão de aprovação que chama o Route Handler.

## Requisitos técnicos

- Use Next.js com TypeScript e App Router.
- Use Server Components para listagem e detalhes.
- Use Client Components apenas onde houver interatividade.
- Use `loading.tsx` e `error.tsx` nas rotas que buscam dados.
- Use Route Handlers para simular as operações de aprovação e cadastro.
- Valide os formulários antes de enviar.
- Simule uma sessão de tutor logado (pode ser um objeto em memória).
- Rode `npm run build` localmente e corrija erros antes de considerar a atividade pronta.
- Prepare o projeto para deploy (pode ser deploy real ou simulado em plataforma gratuita).

## Corrija Sua Atividade Com IA

```text
Você é um revisor de projeto fullstack com Next.js. Vou te enviar o código da minha aplicação Next.js que simula o Portal do Tutor do PetCare OS.

Cenário: o tutor precisa ver seus pets, cadastrar novos, acompanhar atendimentos e aprovar orçamentos. A aplicação usa Next.js, TypeScript, App Router, Server Components, Client Components, Route Handlers e validação.

Tarefa: revise minha aplicação considerando:
1. Estrutura — as rotas e o layout estão bem organizados?
2. Server Components — listagem e detalhes buscam dados no servidor?
3. Client Components — interatividade está isolada no menor componente possível?
4. Loading e erro — há loading.tsx, error.tsx e estados vazios?
5. APIs internas — os Route Handlers têm status HTTP e respostas adequados?
6. Formulários — validação, feedback e acessibilidade estão presentes?
7. Sessão simulada — a UI reage a usuário logado sem fingir segurança real?
8. Build e deploy — npm run build passa e o projeto está pronto para publicar?
9. Preparação para banco de dados — onde ficariam as consultas persistentes?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
- Ao final, indique se estou pronto para o módulo de Bancos de Dados ou se preciso revisar algum ponto.
```

## Onde esse trabalho será retomado

No **módulo 09 — Bancos de Dados**, você substituirá os dados mockados e as operações em memória por consultas reais a um banco relacional. Os Route Handlers `/api/pets` e `/api/orcamentos/[id]` serão os primeiros pontos de integração com o banco, e as telas do portal continuarão as mesmas.

## Recomendação

Esta atividade é **obrigatória para continuidade**. Sem um portal Next.js funcionando, o módulo de Bancos de Dados será significativamente mais difícil porque você precisará entender onde o banco entra em uma aplicação que já tem rotas, componentes e APIs definidos.

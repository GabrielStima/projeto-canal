# Atividade Final do Módulo

## O que você vai produzir

Uma aplicação React com TypeScript que simula o **Portal do Tutor** do PetCare OS. Essa aplicação será a base para o módulo de Next.js, onde você migrará essas telas para o App Router e adicionará renderização no servidor.

## O que você já construiu

Nos exercícios anteriores, você criou:
- componentes reutilizáveis (`PetCard`, `StatusBadge`, `PetList`);
- filtro de atendimentos com estado local e derivado;
- configuração de rotas para dashboard, pets, detalhes e orçamentos;
- chamada de API com estados de carregamento, erro e sucesso;
- formulário de cadastro de pet com validação;
- testes de componentes focados em comportamento.

## Tarefa

Integre os exercícios anteriores em uma aplicação coesa com as seguintes telas e funcionalidades:

1. **Dashboard** (`/`) — resumo com quantidade de pets, atendimentos em andamento e orçamentos pendentes.
2. **Lista de Pets** (`/pets`) — lista com filtro por nome e espécie. Use `PetCard` e `PetList`.
3. **Detalhes do Pet** (`/pets/:id`) — informações do pet e histórico de atendimentos. Use `StatusBadge` para cada atendimento.
4. **Cadastro de Pet** (`/pets/novo`) — formulário controlado com validação. Reutilize o `CadastroPet` do exercício 05.
5. **Orçamento** (`/orcamentos/:id`) — tela simples de aprovação ou recusa com botões e confirmação.

## Requisitos técnicos

- Use React com TypeScript.
- Use React Router (ou equivalente) para navegação.
- Use dados mockados ou uma API simulada (json-server, mock service worker, ou dados em memória).
- Represente estados de carregamento, erro e sucesso nas chamadas de API.
- Valide formulários antes de enviar.
- Escreva testes para pelo menos dois fluxos principais (ex: cadastro de pet e aprovação de orçamento).
- Revise acessibilidade básica (labels, foco, contraste).
- Revise performance básica (evite renderizações desnecessárias, use `key` corretamente).

## Corrija Sua Atividade Com IA

```text
Você é um revisor de projeto frontend. Vou te enviar o código da minha aplicação React que simula o Portal do Tutor do PetCare OS.

Cenário: o tutor precisa ver seus pets, cadastrar novos, acompanhar atendimentos e aprovar orçamentos. A aplicação tem 5 telas e usa React, TypeScript, React Router e testes.

Tarefa: revise minha aplicação considerando:
1. Estrutura — componentes estão bem organizados e reutilizados?
2. Rotas — navegação está correta e usa Link?
3. API — estados de carregamento, erro e sucesso estão representados?
4. Formulários — validação funciona e dá feedback claro?
5. Testes — cobrem comportamento do usuário e não detalhes internos?
6. Acessibilidade — labels, foco e semântica estão presentes?
7. Performance — há gargalos óbvios ou renderizações desnecessárias?
8. Preparação para Next.js — as telas estão prontas para migrar para App Router?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
- Ao final, indique se estou pronto para o módulo de Next.js ou se preciso revisar algum ponto.
```

## Onde esse trabalho será retomado

No **módulo 08 — Next.js**, você migrará essas telas para o App Router, separará Server Components de Client Components e adicionará renderização no servidor. Os componentes `PetCard`, `StatusBadge` e os formulários criados aqui serão reutilizados.

## Recomendação

Esta atividade é **obrigatória para continuidade**. Sem uma aplicação React funcionando, o módulo de Next.js será significativamente mais difícil porque você precisará entender o que muda na arquitetura de componentes quando o servidor entra em cena.

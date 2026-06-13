# Exercício 03 — Server Components e dados

## Objetivo

Praticar busca de dados em Server Components e representar estados de carregamento no Portal do Tutor.

## Cenário

A tela `/tutor/pets` deve mostrar a lista de pets do tutor. Como esses dados não dependem de interatividade imediata, eles podem ser buscados no servidor.

## Tarefa

1. Na página `src/app/tutor/pets/page.tsx`, crie um Server Component que busque uma lista de pets de uma função local ou de uma URL simulada.

2. Use dados mockados se preferir, mas organize a busca como se viesse de uma API:

   ```ts
   type Pet = {
     id: string;
     nome: string;
     especie: string;
     status: string;
   };
   ```

3. Renderize a lista usando componentes simples (pode ser um `<ul>` com `<li>` por enquanto).

4. Crie um arquivo `src/app/tutor/pets/loading.tsx` com uma mensagem ou skeleton simples.

5. Crie um arquivo `src/app/tutor/pets/error.tsx` para tratar falhas na busca.

## Requisitos

- A página é um Server Component (sem `'use client'`).
- A busca de dados acontece dentro do componente de página.
- Estados de carregamento e erro são representados.
- A lista vazia tem tratamento próprio.

## Critérios de avaliação

- Server Component usado corretamente.
- Dados mockados ou buscados de forma simulada.
- `loading.tsx` e `error.tsx` existem e funcionam.
- Lista vazia mostra mensagem amigável.
- Componentes visuais simples e semânticos.

## Onde este trabalho será retomado

O padrão de busca de dados no servidor e os arquivos `loading.tsx`/`error.tsx` serão reutilizados nas telas de detalhes e orçamentos da atividade final. No módulo 09 — Bancos de Dados, a função de busca será conectada a um banco real.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de Server Components em Next.js. Vou te enviar a página de listagem de pets que criei para o Portal do Tutor do PetCare OS.

Cenário: a tela /tutor/pets lista os pets do tutor. Os dados são estáticos por enquanto, mas a página deve estar preparada para buscar dados no servidor.

Tarefa: revise minha implementação considerando:
1. A página é realmente um Server Component?
2. A busca de dados está organizada em uma função separada?
3. Os estados de carregamento e erro estão representados?
4. A lista vazia tem tratamento?
5. A estrutura de componentes é simples e reutilizável?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

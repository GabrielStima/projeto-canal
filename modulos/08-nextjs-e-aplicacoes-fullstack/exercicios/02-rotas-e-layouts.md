# Exercício 02 — Rotas e layouts

## Objetivo

Praticar rotas no App Router e layouts aninhados no contexto do Portal do Tutor.

## Cenário

O tutor precisa navegar entre diferentes áreas do portal: lista de pets, detalhes de um pet, cadastro de novo pet e orçamentos pendentes. A navegação deve aparecer em todas as telas da área `/tutor`.

## Tarefa

1. Crie a seguinte árvore de rotas dentro de `src/app/tutor/`:

   ```text
   src/app/tutor/
   ├── layout.tsx
   ├── page.tsx            -> /tutor
   ├── pets/
   │   ├── page.tsx        -> /tutor/pets
   │   ├── novo/
   │   │   └── page.tsx    -> /tutor/pets/novo
   │   └── [id]/
   │       └── page.tsx    -> /tutor/pets/[id]
   └── orcamentos/
       └── page.tsx        -> /tutor/orcamentos
   ```

2. No `layout.tsx` da área `/tutor`, crie uma navegação fixa com links para:
   - `/tutor/pets`
   - `/tutor/pets/novo`
   - `/tutor/orcamentos`

3. Use o componente `Link` do Next.js para navegação interna.

4. Em cada página, exiba um título simples indicando a função da tela.

## Requisitos

- A navegação aparece em todas as rotas dentro de `/tutor`.
- As rotas usam `Link`, não âncoras comuns.
- A rota dinâmica `/tutor/pets/[id]` lê o parâmetro `id`.
- A estrutura de pastas reflete a navegação do portal.

## Critérios de avaliação

- Rotas estão mapeadas corretamente.
- Layout aninhado compartilha a navegação.
- Uso correto de `Link`.
- Parâmetro dinâmico é acessado na página de detalhes.
- Semântica HTML básica (nav, main, h1).

## Onde este trabalho será retomado

A estrutura de rotas e o layout criados aqui serão a base do Portal do Tutor na atividade final. No módulo 09 — Bancos de Dados, as rotas `/tutor/pets/[id]` e `/tutor/orcamentos` serão alimentadas por dados persistentes.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de rotas e layouts em Next.js. Vou te enviar a estrutura de rotas e o layout que criei para o Portal do Tutor do PetCare OS.

Cenário: o tutor precisa navegar entre lista de pets, cadastro de pet, detalhes de pet e orçamentos. A navegação deve ser compartilhada pela área /tutor.

Tarefa: revise minha implementação considerando:
1. A árvore de pastas está correta para as rotas desejadas?
2. O layout compartilha a navegação em todas as páginas?
3. Os links usam o componente Link do Next.js?
4. A rota dinâmica /tutor/pets/[id] lê o parâmetro corretamente?
5. A estrutura de pastas é clara e escalável?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

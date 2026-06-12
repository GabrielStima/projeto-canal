# Exercício 03 — Rotas e navegação

## Objetivo

Praticar rotas, navegação client-side e parâmetros de URL em React.

## Cenário

O portal do tutor do PetCare OS precisa de navegação entre telas: dashboard inicial, lista de pets, detalhes de um pet específico e página de aprovação de orçamento.

## Tarefa

Configure rotas usando React Router (ou equivalente) para uma aplicação com as seguintes telas:

1. `/` — Dashboard com resumo dos pets do tutor.
2. `/pets` — Lista de pets.
3. `/pets/:id` — Detalhes do pet, incluindo histórico de atendimentos.
4. `/orcamentos/:id` — Página de aprovação ou recusa de um orçamento.

## Requisitos

- Use `Link` para navegação interna (não âncoras comuns).
- A rota de detalhes do pet deve ler o parâmetro `id` da URL.
- Inclua uma rota para página não encontrada (404).
- Crie um menu de navegação visível em todas as telas.

## Critérios de avaliação

- Rotas estão configuradas corretamente com componentes de página.
- Navegação interna usa `Link` sem recarregar a página.
- Parâmetros de rota são lidos e usados.
- Rota 404 existe.
- Menu de navegação aparece em todas as telas.

## Onde este trabalho será retomado

A estrutura de rotas criada aqui (`/`, `/pets`, `/pets/:id`, `/orcamentos/:id`) será a base da navegação da atividade final. No módulo 08 — Next.js, essas rotas serão migradas para o App Router, mas os caminhos e a organização de páginas permanecem.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de código frontend. Vou te enviar a configuração de rotas de uma aplicação React para o portal do tutor de uma clínica veterinária.

Cenário: o tutor precisa navegar entre dashboard, lista de pets, detalhes de um pet e aprovação de orçamento.

Tarefa: revise minha configuração de rotas considerando:
1. Rotas — todas as telas estão mapeadas corretamente?
2. Navegação — uso `Link` em vez de âncoras comuns?
3. Parâmetros — a rota `/pets/:id` lê o ID corretamente?
4. 404 — há uma rota para páginas não encontradas?
5. Menu — a navegação aparece em todas as telas?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

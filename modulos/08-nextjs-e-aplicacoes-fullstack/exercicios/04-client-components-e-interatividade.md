# Exercício 04 — Client Components e interatividade

## Objetivo

Praticar a composição entre Server Components e Client Components no Portal do Tutor.

## Cenário

A página de orçamentos lista itens pendentes de aprovação. A listagem pode vir do servidor, mas o botão de aprovação precisa de estado local para mostrar confirmação e feedback imediato ao tutor.

## Tarefa

1. Na página `/tutor/orcamentos`, crie um Server Component que receba uma lista de orçamentos mockados.

2. Crie um Client Component `AprovacaoOrcamento` que receba o `id` e o `valor` do orçamento e exiba:
   - o valor do orçamento;
   - um botão "Aprovar orçamento";
   - após o clique, o botão deve ficar desabilitado e mostrar "Orçamento aprovado".

3. Use o Client Component dentro do Server Component da página.

## Requisitos

- A página é Server Component.
- O botão de aprovação é Client Component.
- O estado de aprovação é local ao botão.
- A interatividade não transforma a página inteira em cliente.
- Acessibilidade básica: `aria-live` e `disabled` bem usados.

## Critérios de avaliação

- Separação correta entre servidor e cliente.
- Props passadas do servidor para o cliente.
- Estado local funciona e reflete a aprovação.
- Botão desabilitado após aprovação.
- Semântica e acessibilidade básicas.

## Onde este trabalho será retomado

O componente `AprovacaoOrcamento` será reutilizado na atividade final e evoluirá para chamar um Route Handler ou Server Action. No módulo 09 — Bancos de Dados, a aprovação persistirá no banco.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de composição entre Server e Client Components em Next.js. Vou te enviar a página de orçamentos e o botão de aprovação que criei para o Portal do Tutor do PetCare OS.

Cenário: a listagem de orçamentos vem do servidor, mas o botão de aprovação precisa de interatividade no browser.

Tarefa: revise minha implementação considerando:
1. A página é Server Component e o botão é Client Component?
2. As props são passadas corretamente do servidor para o cliente?
3. O estado local reflete a aprovação sem recarregar a página?
4. A interatividade está isolada no menor componente possível?
5. Há cuidados básicos de acessibilidade?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

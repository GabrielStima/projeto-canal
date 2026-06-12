# Exercício 01 — Componentes reutilizáveis

## Objetivo

Criar componentes React simples e reutilizáveis para uma interface de petshop/clínica veterinária.

## Cenário

Você está construindo o portal do tutor do PetCare OS. A tela inicial precisa mostrar uma lista de pets, cada um com nome, espécie e status do último atendimento. Esses elementos visuais vão aparecer em várias telas diferentes.

## Tarefa

Crie três componentes React usando TypeScript:

1. `PetCard` — recebe `nome`, `especie` e `status` como props e renderiza um card com essas informações.
2. `StatusBadge` — recebe `status` (ex: `"Recebido"`, `"Em Triagem"`, `"Finalizado"`) e renderiza uma etiqueta colorida simples.
3. `PetList` — recebe uma lista de pets e renderiza um `PetCard` para cada item. Use `key` corretamente.

## Requisitos

- Use funções de componente (não classe).
- Defina tipos para as props.
- Não use estado; os dados vêm de fora.
- O `StatusBadge` deve ter pelo menos três variações visuais diferentes (pode ser só cor de fundo ou texto).

## Critérios de avaliação

- Os componentes são reutilizáveis e bem tipados.
- A lista renderiza corretamente com `key` única e estável.
- O `StatusBadge` varia conforme o status recebido.
- A estrutura de props é clara e não repete dados desnecessários.

## Onde este trabalho será retomado

Os componentes `PetCard`, `StatusBadge` e `PetList` criados aqui serão reutilizados na atividade final do módulo e migrados para o módulo 08 — Next.js. Guarde esse código em um repositório ou pasta organizada, pois ele fará parte do Portal do Tutor.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de código frontend. Vou te enviar três componentes React que criei para um portal de clínica veterinária: PetCard, StatusBadge e PetList.

Cenário: o portal do tutor precisa mostrar uma lista de pets, cada um com nome, espécie e status do último atendimento. Esses componentes serão usados em várias telas.

Tarefa: revise meus componentes considerando:
1. Tipagem das props — estão completas e corretas?
2. Reutilização — os componentes funcionam em diferentes contextos?
3. Uso de `key` na lista — é única e estável?
4. Variações do StatusBadge — cobrem pelo menos três status diferentes?
5. Estrutura — há repetição de dados ou props confusas?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

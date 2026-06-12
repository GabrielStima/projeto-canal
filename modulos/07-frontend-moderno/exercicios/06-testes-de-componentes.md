# Exercício 06 — Testes de componentes

## Objetivo

Praticar testes de componentes React focados em comportamento do usuário.

## Cenário

O componente `StatusBadge` do PetCare OS mostra o status de um atendimento. Ele precisa ser testado para garantir que renderiza corretamente para diferentes status e que interações funcionam como esperado.

## Tarefa

Escreva testes para os seguintes cenários:

1. O `StatusBadge` renderiza o texto correto para o status `"Em Triagem"`.
2. O `StatusBadge` renderiza o texto correto para o status `"Finalizado"`.
3. O `CadastroPet` (do exercício anterior) mostra mensagem de erro ao tentar enviar com nome vazio.
4. O `CadastroPet` habilita o botão de envio apenas quando todos os campos obrigatórios são válidos.
5. O `AtendimentosDoDia` (do exercício 04) mostra "Carregando..." enquanto busca dados.

## Requisitos

- Use queries orientadas ao usuário (ex: `getByText`, `getByRole`) em vez de seletores internos.
- Cada teste deve verificar comportamento, não implementação.
- Inclua pelo menos um caso de erro e um caso de sucesso.

## Critérios de avaliação

- Testes verificam comportamento visível, não detalhes internos.
- Queries são orientadas ao usuário.
- Casos de erro e sucesso estão cobertos.
- Componentes de exercícios anteriores são reutilizados.
- Testes são pequenos e verificam uma coisa de cada vez.

## Onde este trabalho será retomado

Os testes criados aqui serão expandidos na atividade final para cobrir fluxos principais do Portal do Tutor. No módulo 08 — Next.js, você aprenderá a testar componentes que misturam renderização no servidor e no cliente.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de testes frontend. Vou te enviar testes de componentes React que escrevi para uma clínica veterinária.

Cenário: preciso garantir que StatusBadge, CadastroPet e AtendimentosDoDia funcionam corretamente do ponto de vista do usuário.

Tarefa: revise meus testes considerando:
1. Foco — os testes verificam comportamento visível ou detalhes internos?
2. Queries — uso getByText, getByRole ou estou dependendo de classes/IDs?
3. Cobertura — há casos de erro e sucesso?
4. Tamanho — cada teste verifica uma coisa de cada vez?
5. Reutilização — estou testando componentes que já construí nos exercícios anteriores?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

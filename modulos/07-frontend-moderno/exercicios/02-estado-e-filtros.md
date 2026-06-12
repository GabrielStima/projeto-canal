# Exercício 02 — Estado e filtros

## Objetivo

Praticar estado local, estado derivado e levantamento de estado em React.

## Cenário

O painel da recepção do PetCare OS exibe a fila de atendimentos do dia. A recepcionista precisa filtrar por nome do pet ou por status para encontrar atendimentos rapidamente.

## Tarefa

Crie um componente `FilaDeAtendimentos` que:

1. Guarde uma lista de atendimentos em estado local (dados mockados são suficientes).
2. Tenha um campo de busca que filtra por nome do pet.
3. Tenha botões ou select que filtram por status (todos, Recebido, Em Triagem, Em Procedimento, Finalizado).
4. Mostre a lista filtrada usando componentes `AtendimentoCard`.

## Requisitos

- O estado de busca e o estado de filtro por status devem funcionar juntos (interseção).
- A lista filtrada deve ser derivada do estado, não guardada em estado separado.
- Mostre uma mensagem quando não houver resultados.

## Critérios de avaliação

- Estado local é usado corretamente para busca e filtro.
- A lista filtrada é calculada, não duplicada em estado.
- Filtros combinados funcionam (busca + status).
- Mensagem de lista vazia aparece quando necessário.
- Componentes menores são reutilizados para renderizar itens.

## Onde este trabalho será retomado

O padrão de filtro por estado derivado será usado na tela de listagem de pets da atividade final. Os componentes de lista e card criados no exercício anterior serão reaproveitados aqui e evoluirão no módulo 08 — Next.js.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de código frontend. Vou te enviar um componente React que criei para a fila de atendimentos de uma clínica veterinária.

Cenário: a recepcionista precisa filtrar a fila de atendimentos do dia por nome do pet e por status. Os filtros devem funcionar juntos.

Tarefa: revise meu componente considerando:
1. Estado local — busca e filtro por status estão em estado separado?
2. Estado derivado — a lista filtrada é calculada ou duplicada em estado?
3. Filtros combinados — busca e status funcionam juntos corretamente?
4. UX — há mensagem quando a lista está vazia?
5. Reutilização — componentes menores são usados para renderizar itens?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

# Exercício 04 — Chamadas de API

## Objetivo

Praticar chamadas de API no frontend, tratamento de estados de carregamento, erro e sucesso.

## Cenário

O painel da recepção do PetCare OS precisa buscar a lista de atendimentos do dia de uma API. A interface deve informar ao usuário o que está acontecendo em cada momento.

## Tarefa

Crie um componente `AtendimentosDoDia` que:

1. Busque atendimentos de `/api/atendimentos?hoje=true` ao montar.
2. Mostre um estado de carregamento enquanto a requisição está em andamento.
3. Mostre uma mensagem de erro amigável se a requisição falhar.
4. Mostre a lista de atendimentos quando os dados chegarem.
5. Mostre uma mensagem quando a lista estiver vazia.

## Requisitos

- Use `useEffect` para buscar dados ao montar o componente.
- Use `async/await` e `try/catch`.
- Represente pelo menos três estados visuais: carregando, erro, sucesso.
- Inclua um botão "Tentar novamente" que refaz a chamada em caso de erro.

## Critérios de avaliação

- A chamada de API acontece no momento correto.
- Estados de carregamento, erro e sucesso são representados visualmente.
- Lista vazia tem tratamento próprio.
- Botão de retry funciona.
- Não há loop infinito de requisições.

## Onde este trabalho será retomado

O componente `AtendimentosDoDia` e o padrão de estados de API serão reutilizados na tela de dashboard e detalhes da atividade final. No módulo 08 — Next.js, parte dessa busca de dados poderá ser feita no servidor, mas o modelo mental de estados de UI permanece.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de código frontend. Vou te enviar um componente React que criei para buscar atendimentos do dia em uma clínica veterinária.

Cenário: o painel da recepção busca a lista de atendimentos de hoje de uma API. A interface deve mostrar carregamento, erro, sucesso e lista vazia.

Tarefa: revise meu componente considerando:
1. Momento da chamada — a requisição acontece ao montar o componente?
2. Estados de UI — carregamento, erro, sucesso e vazio estão representados?
3. Tratamento de erro — há mensagem amigável e botão de retry?
4. Loop infinito — há risco de chamadas repetidas sem querer?
5. Separação — dados remotos estão separados de estado visual?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

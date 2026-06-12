# Exercício 05 — Formulários e validação

## Objetivo

Praticar formulários controlados, validação de campos e feedback ao usuário em React.

## Cenário

O tutor precisa cadastrar um novo pet no PetCare OS. O formulário de cadastro deve validar os dados antes de enviar e mostrar mensagens de erro claras.

## Tarefa

Crie um componente `CadastroPet` com um formulário controlado que capture:

1. Nome do pet (obrigatório, mínimo 2 caracteres).
2. Espécie (obrigatório).
3. Data de nascimento (opcional, mas deve ser uma data válida se preenchida).
4. Nome do tutor (obrigatório).

## Requisitos

- Todos os campos são controlados por estado.
- Validação acontece ao tentar enviar e também em tempo real (on blur).
- Mensagens de erro aparecem próximo aos campos inválidos.
- O botão de envio fica desabilitado enquanto houver erros.
- Simule o envio com um estado "enviando" e uma mensagem de sucesso.

## Critérios de avaliação

- Campos são controlados e sincronizados com estado.
- Validação cobre obrigatoriedade, tamanho mínimo e formato de data.
- Mensagens de erro são claras e posicionadas corretamente.
- Botão de envio respeita o estado de validação.
- Estado de envio e mensagem de sucesso são representados.

## Onde este trabalho será retomado

O componente `CadastroPet` será reutilizado na tela `/pets/novo` da atividade final e evoluído no módulo 08 — Next.js, onde parte da validação poderá ser feita com Server Actions ou rotas de API.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de código frontend. Vou te enviar um componente React de formulário de cadastro de pet que criei.

Cenário: o tutor precisa cadastrar um novo pet no sistema da clínica veterinária. O formulário deve validar dados e dar feedback claro.

Tarefa: revise meu formulário considerando:
1. Controle de campos — todos os inputs são controlados por estado?
2. Validação — há regras para obrigatoriedade, tamanho mínimo e data válida?
3. Feedback — mensagens de erro aparecem próximo aos campos e em momento adequado?
4. UX do botão — envio fica desabilitado com erros e mostra estado "enviando"?
5. Sucesso — há mensagem de confirmação após envio simulado?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

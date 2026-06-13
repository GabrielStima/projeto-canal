# Exercício 06 — Formulários e validação

## Objetivo

Construir um formulário de cadastro de pet no Next.js com validação de dados.

## Cenário

O tutor precisa cadastrar um novo pet no portal. O formulário deve capturar nome, espécie e data de nascimento aproximada, validar os campos e dar feedback claro.

## Tarefa

1. Na página `/tutor/pets/novo`, crie um formulário de cadastro de pet.

2. O formulário pode ser HTML nativo com `action` apontando para um Route Handler `POST /api/pets`, ou um Client Component controlado. Escolha a abordagem que faz mais sentido para o fluxo.

3. Valide as regras:
   - nome é obrigatório e deve ter pelo menos 2 caracteres;
   - espécie é obrigatória;
   - data de nascimento, se preenchida, deve ser uma data válida.

4. Crie o Route Handler `src/app/api/pets/route.ts` com o método `POST` que simule o cadastro retornando os dados recebidos.

5. Mostre mensagens de erro próximo aos campos e uma mensagem de sucesso após o envio.

## Requisitos

- Campos obrigatórios são validados.
- Mensagens de erro são claras e posicionadas corretamente.
- O envio simula persistência (dados em memória ou mock).
- Feedback de sucesso é mostrado ao tutor.
- Acessibilidade básica: labels associados aos inputs.

## Critérios de avaliação

- Formulário captura e envia os dados corretamente.
- Validação cobre obrigatoriedade, tamanho mínimo e formato de data.
- Mensagens de erro aparecem próximo aos campos.
- Route Handler simula o cadastro e retorna os dados.
- Sucesso é comunicado de forma clara.

## Onde este trabalho será retomado

O formulário de cadastro de pet e o Route Handler `/api/pets` serão integrados à atividade final. No módulo 09 — Bancos de Dados, o handler passará a inserir pets em uma tabela real, mas a estrutura do formulário e as regras de validação permanecem.

## Corrija Sua Atividade Com IA

```text
Você é um revisor de formulários e validação em Next.js. Vou te enviar o formulário de cadastro de pet e o Route Handler que criei para o Portal do Tutor do PetCare OS.

Cenário: o tutor cadastra um novo pet informando nome, espécie e data de nascimento. Os dados são validados antes de serem enviados.

Tarefa: revise minha implementação considerando:
1. O formulário captura todos os campos necessários?
2. A validação cobre obrigatoriedade, tamanho mínimo e data válida?
3. As mensagens de erro estão claras e posicionadas corretamente?
4. O Route Handler simula o cadastro e retorna uma resposta adequada?
5. O feedback de sucesso é claro para o tutor?

[COLE SUA RESPOSTA AQUI]

Instruções para o revisor:
- Destaque acertos e aponte imprecisões com explicações.
- Ofereça dicas de melhoria antes de apresentar uma resposta completa.
- Não entregue código pronto antes de eu tentar corrigir.
```

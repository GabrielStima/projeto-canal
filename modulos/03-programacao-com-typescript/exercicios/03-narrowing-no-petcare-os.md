# Exercício 03 — Narrowing no PetCare OS

## Objetivo

Praticar narrowing em TypeScript para tratar unions de forma segura no contexto do PetCare OS.

## O que você já sabe

- Criar unions de tipos e strings literais.
- Usar `typeof`, `in` e comparações para diferenciar valores.
- Criar funções tipadas.

## Tarefa atual

Você vai criar uma função que processa diferentes tipos de notificação do PetCare OS usando narrowing.

## Exercício

1. Crie um type `TipoNotificacao` que pode ser `"email"`, `"sms"` ou `"push"`.
2. Crie tipos diferentes para cada notificação:
   - `EmailNotificacao` com `tipo: "email"`, `destinatario: string`, `assunto: string`.
   - `SmsNotificacao` com `tipo: "sms"`, `numero: string`, `mensagem: string`.
   - `PushNotificacao` com `tipo: "push"`, `deviceId: string`, `titulo: string`.
3. Crie um type `Notificacao` como a union dos três tipos acima.
4. Crie uma função `enviarNotificacao(notificacao)` que:
   - Use narrowing para identificar o tipo da notificação.
   - Retorne uma string descrevendo o envio específico (por exemplo, `"Enviando email para ..."`).
5. Crie três exemplos de notificação e chame a função para cada um.
6. Tente chamar a função com uma notificação incompleta e observe o erro do TypeScript.

## Critérios de conclusão

- `Notificacao` é uma union discriminated pelos tipos.
- A função usa narrowing (`if`, `switch` ou outro type guard) para tratar cada caso.
- Cada caso retorna uma string específica.
- O TypeScript impede o uso de campos inexistentes fora do escopo correto.

## Como este trabalho continuará

Narrowing é essencial para manipular dados com formatos variados no PetCare OS, como diferentes tipos de eventos, canais de comunicação e estados de atendimento. Ele será usado nos módulos de backend e frontend.

## Corrija Sua Atividade Com IA

```text
Estou estudando narrowing e unions discriminadas no TypeScript. Fiz um exercício e quero correção.

Cenário: estou modelando notificações do PetCare OS. Existem três tipos: email, sms e push. Cada uma tem campos específicos. A função `enviarNotificacao` deve usar narrowing para tratar cada tipo de forma segura.

Tarefa: avalie o código que eu escrevi para esse exercício.

Critérios de correção:
1. `Notificacao` é uma union de três tipos discriminados por `tipo`?
2. Cada tipo de notificação tem os campos esperados?
3. A função `enviarNotificacao` usa narrowing para identificar o tipo?
4. Cada caso retorna uma string específica e correta?
5. O TypeScript impede acesso a campos fora do escopo correto?
6. Há exemplos para os três tipos de notificação?

[COLE SUA RESPOSTA AQUI]

Regras da correção:
- Destaque meus acertos primeiro.
- Aponte imprecisões e erros com explicações curtas.
- Dê dicas antes de mostrar uma possível solução completa.
- Não reescreva o código todo sem que eu peça.
```

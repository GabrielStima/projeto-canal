# Atividade Final do Módulo

## O que você já tem

Sua API envia arquivos pesados (ex: Upload de PDF para triagem) na thread principal e gera gargalo de requisições.

## A Tarefa

O **marco de comunicação assíncrona** divide sua aplicação.

1. Escolha uma biblioteca de fila para seu ecossistema (Node -> BullMQ, Python -> Celery, Go -> RabbitMQ driver).
2. Isole a rota bloqueante: Ela deve apenas validar os dados e colocar o JSON na fila (`await fila.add(job)`).
3. Responda imediatamente com Status `202 Accepted` e o Hash do Trabalho.
4. Crie um script à parte, o Consumidor/Worker (`worker.js`).
5. Este Consumidor recebe o Hash, imita um delay forçado (Simulando 5 segundos) usando `setTimeout` e altera o estado do objeto na base (`status: concluido`).
6. Bônus/Opcional: Suba uma conexão WebSockets na tela principal de Notificações, empurrando o Toast "Triagem processada!" no momento em que o Worker acaba.

## O que você vai produzir

- Uma arquitetura Event-Driven isolada entre Produtor e Consumidor.
- Um ganho estúpido de escalabilidade que previne que a UI fique em estado "Loading Infinito".

## Corrija Sua Atividade Com IA

```text
Cenário: Revisão do marco de comunicação assíncrona - Filas e Background Processing real-world.

Tarefa: Aqui está a lógica de como dividi meu Controller e configurei as `options` da minha Fila (Tentativas, Backoff).

[COLE AQUI O CODIGO DO CONTROLLER DA FILA E DO WORKER]


[COLE SUA RESPOSTA AQUI]
Critérios de correção:
1. O Controller principal ficou bloqueado esperando o Worker responder? (Se sim, reprovado).
2. Avalie as configurações de Backoff (O que acontece se o Job der erro? Ele tenta imediatamente de novo ou usa Backoff Exponencial?).
3. Como sênior, aponte um cenário em que a Fila pode falhar catastroficamente se houver picos de memória e como prevenir usando Dead Letter Queues (DLQ).
```

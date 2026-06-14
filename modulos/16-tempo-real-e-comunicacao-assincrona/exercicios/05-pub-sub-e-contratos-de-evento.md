# Exercício 05 — Pub/Sub e Contratos de Evento

## O que você já tem

Seu fluxo possui uma fila de trabalho para executar uma operação. Agora você avaliará se outros módulos precisam apenas saber que algo aconteceu.

## Tarefa

Escolha um fato do domínio, como `ConsultaConcluida` ou `EstoqueAbaixoDoMinimo`, e defina:

1. nome no passado, representando algo que já ocorreu;
2. identificador do evento e data de ocorrência;
3. versão do contrato;
4. dados mínimos necessários;
5. publicador;
6. dois possíveis assinantes independentes;
7. comportamento quando um assinante falhar;
8. estratégia para eventos duplicados, atrasados ou fora de ordem.

Compare esse fluxo com a fila do exercício anterior e explique por que um evento pode ter vários assinantes, enquanto uma tarefa costuma ser processada por um consumidor responsável.

## O que você vai produzir

Um contrato versionado e uma decisão clara entre distribuir trabalho e divulgar um fato.

## Corrija Sua Atividade Com IA

```text
Cenário: Modelei um evento de domínio versionado com identificador, data, dados mínimos, publicador e assinantes independentes. Também comparei pub/sub com uma fila de trabalho.

Tarefa: Avalie meu contrato e minha comparação.

Critérios de correção:
1. O nome representa um fato já ocorrido?
2. O contrato contém somente informações necessárias e possui versão?
3. Os assinantes podem falhar sem desfazer o fato publicado?
4. Duplicidade, atraso e ordem foram considerados?
5. A diferença entre distribuir uma tarefa e publicar um fato está correta?
6. O evento reduz acoplamento sem esconder dependências importantes?

Primeiro destaque os acertos. Depois aponte imprecisões e ofereça dicas antes de apresentar um contrato completo.

[COLE SUA RESPOSTA AQUI]
```

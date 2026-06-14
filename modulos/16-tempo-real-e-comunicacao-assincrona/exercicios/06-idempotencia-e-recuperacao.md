# Exercício 06 — Idempotência e Recuperação

## O que você já tem

Você possui jobs, retentativas e um contrato de evento. Como uma entrega pode se repetir, os efeitos precisam ser seguros.

## Tarefa

Escolha um efeito do seu consumidor, como registrar o resultado de um relatório ou reservar um item de estoque.

Implemente ou detalhe:

1. uma chave de idempotência estável;
2. onde a chave e o resultado serão armazenados;
3. verificação antes de repetir o efeito;
4. comportamento quando a primeira execução falhar no meio;
5. resposta para uma repetição já concluída;
6. teste que entregue a mesma mensagem duas vezes;
7. procedimento controlado para reprocessar uma falha permanente.

Evite usar cobrança real ou outro efeito irreversível no laboratório.

## O que você vai produzir

Um consumidor que tolera entrega repetida e um procedimento de recuperação que será usado na atividade final.

## Corrija Sua Atividade Com IA

```text
Cenário: Tornei um consumidor idempotente. Defini uma chave estável, armazenamento da execução, verificação antes do efeito, tratamento de falha parcial, resposta a duplicatas, teste de entrega repetida e reprocessamento controlado.

Tarefa: Revise minha estratégia e meus testes.

Critérios de correção:
1. A mesma operação lógica produz a mesma chave?
2. Verificação e efeito evitam uma janela perigosa de duplicação?
3. Uma falha parcial pode ser detectada e retomada com segurança?
4. Uma mensagem repetida não duplica o efeito?
5. O teste demonstra o comportamento, em vez de apenas verificar uma função auxiliar?
6. O reprocessamento é auditável e não ignora a causa da falha?

Comece pelos acertos. Depois identifique imprecisões e dê dicas antes de escrever uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

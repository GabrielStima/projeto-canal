# Exercício 03 — Capacidade, Saúde e Degradação

## O Que Você Já Possui

Você definiu uma jornada crítica, seus SLIs, um SLO e o limite de falhas aceitável.

## A Tarefa

Acrescente a `docs/operacao.md` uma seção `Sinais e modos de operação`:

1. Escolha quatro sinais para acompanhar a jornada, incluindo demanda, erro, latência e saturação.
2. Para cada sinal, descreva o que seria normal, preocupante e crítico.
3. Explique o que os endpoints de liveness e readiness devem verificar.
4. Proponha uma degradação graciosa para uma dependência não essencial.
5. Defina como o sistema informa ao usuário que está operando de forma limitada.
6. Registre uma condição em que a degradação não seria aceitável.

Você pode usar configuração, pseudocódigo ou código existente para representar as verificações de saúde.

## O Que Você Vai Produzir

Uma tabela de sinais operacionais e um desenho de saúde e degradação que preserve a função principal da jornada.

Esse desenho será usado para decidir quando mitigar, reverter ou escalar uma falha.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou preparando sinais, verificações de saúde e degradação graciosa para uma jornada crítica do PetCare OS.

Tarefa: Revise minha tabela de sinais e meu desenho de liveness, readiness e operação degradada.

Critérios de correção:
1. Os sinais cobrem demanda, erros, latência e saturação sem confundir causa com sintoma.
2. Liveness verifica o processo de forma leve e readiness representa capacidade de atender.
3. A degradação mantém uma função útil sem esconder falhas ou comprometer dados.
4. O usuário recebe uma mensagem coerente com o estado do serviço.
5. Os limites entre normal, preocupante e crítico ajudam uma decisão operacional.

Primeiro destaque meus acertos. Depois aponte imprecisões e ofereça dicas de melhoria. Só apresente um desenho completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

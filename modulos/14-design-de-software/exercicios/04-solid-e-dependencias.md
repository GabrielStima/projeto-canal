# Exercício 04 — SOLID e Dependências

## O que você já sabe

Seu fluxo possui comportamento protegido, modelo e uma primeira decisão de refatoração. Agora você analisará responsabilidades, contratos e dependências.

## Sua tarefa

Escolha uma regra que hoje depende diretamente de banco, cliente HTTP, relógio ou envio de mensagem.

1. Identifique o código de alto nível e o detalhe externo.
2. Defina o menor contrato exigido pelo consumidor.
3. Torne a dependência explícita por argumento ou construtor.
4. Crie um fake ou stub para o teste unitário.
5. Preserve um teste de integração para a implementação real.
6. Verifique se alguma interface está grande demais.
7. Explique se SRP, ISP, DIP ou OCP realmente melhoraram o código.

Não crie interface apenas para cumprir SOLID. A abstração precisa reduzir acoplamento ou permitir um teste relevante.

## O que você vai produzir

- contrato pequeno;
- implementação real preservada;
- double de teste;
- teste unitário e indicação do teste de integração;
- justificativa dos princípios aplicados e não aplicados.

## Critérios de conclusão

- A regra não importa diretamente o detalhe externo.
- O contrato é definido pela necessidade do consumidor.
- O double representa comportamento suficiente.
- A implementação real continua coberta por integração.
- A indireção paga seu custo.

## Como este trabalho continuará

As dependências explícitas permitirão avaliar composição, variação e padrões sem prender a regra a uma tecnologia.

## Corrija Sua Atividade Com IA

```text
Cenário: Separei uma regra de domínio de uma dependência externa usando um contrato pequeno e injeção explícita.

Tarefa: Revise a aplicação de SOLID e a estratégia de testes.

Critérios de correção:
1. Alto nível e detalhe externo foram separados?
2. O contrato pertence à necessidade do consumidor?
3. Existe interface ou indireção desnecessária?
4. O double é adequado ao teste unitário?
5. A implementação real permanece validada por integração?

Destaque os acertos, aponte imprecisões e dê dicas antes de apresentar uma estrutura completa.

[COLE SUA RESPOSTA AQUI]
```

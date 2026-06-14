# Exercício 02 — Modelagem e Invariantes

## O que você já sabe

Você possui um fluxo protegido por testes. Agora decidirá quais regras merecem um modelo com comportamento e quais dados podem permanecer simples.

## Sua tarefa

Escolha um conceito do fluxo, como agendamento, orçamento, atendimento ou movimentação de estoque.

1. Liste estados válidos e transições permitidas.
2. Identifique duas invariantes.
3. Compare três representações: função, objeto simples e classe com comportamento.
4. Escolha a menor representação que protege as regras.
5. Implemente uma operação válida e duas tentativas inválidas.
6. Escreva testes pelo comportamento público.

Use o vocabulário do domínio. Não transforme automaticamente cada tabela em classe.

## O que você vai produzir

- modelo ou função de domínio;
- testes das invariantes;
- justificativa da representação escolhida;
- atualização do diagnóstico.

## Critérios de conclusão

- As invariantes são regras reais.
- Estado inválido não pode ser criado por caminhos públicos.
- O modelo não depende de HTTP ou ORM.
- A escolha entre função, objeto ou classe foi justificada.
- Os testes não acessam detalhes privados.

## Como este trabalho continuará

O modelo será usado para avaliar coesão, abstrações e dependências nos próximos exercícios.

## Corrija Sua Atividade Com IA

```text
Cenário: Modelei um conceito de domínio em TypeScript e protegi duas invariantes com testes.

Tarefa: Avalie a escolha entre função, objeto e classe, além da proteção do estado.

Critérios de correção:
1. As invariantes representam regras reais?
2. O estado inválido pode ser criado ou alterado por fora?
3. O modelo está independente de framework e banco?
4. A representação escolhida é proporcional ao problema?
5. Os testes verificam comportamento?

Destaque os acertos, aponte imprecisões e dê dicas antes de propor outro modelo completo.

[COLE SUA RESPOSTA AQUI]
```

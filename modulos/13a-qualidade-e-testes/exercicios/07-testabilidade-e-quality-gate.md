# Exercício 07 — Testabilidade e Quality Gate

## O que você já sabe

Ao escrever testes, você encontrou partes fáceis e difíceis de isolar. Agora usará essa evidência para melhorar o design e definir regras automáticas proporcionais ao projeto.

## Sua tarefa

Escolha uma função, serviço ou controller difícil de testar. Identifique:

- regra de negócio misturada com infraestrutura;
- dependência criada internamente;
- efeito colateral;
- dado global ou relógio;
- responsabilidade excessiva.

Proponha uma refatoração pequena que torne uma regra testável sem reestruturar toda a aplicação.

Depois defina um quality gate para código novo usando os controles disponíveis, por exemplo:

- lint;
- verificação de tipos;
- testes;
- cobertura das partes alteradas;
- ausência de segredo versionado;
- revisão humana para decisões não automatizáveis.

Evite exigir 100% de cobertura ou tratar uma métrica como sinônimo de qualidade.

## O que você vai produzir

- diagnóstico e refatoração proposta;
- teste que se torna mais simples após a mudança;
- política de quality gate;
- justificativa dos limites e exceções.

## Critérios de conclusão

- A refatoração reduz acoplamento observável.
- O teste continua verificando comportamento.
- O gate diferencia regra, métrica e decisão humana.
- Limites focam código novo e risco.
- Exceções precisam de justificativa, não de desativação silenciosa.

## Como este trabalho continuará

A atividade final reunirá estratégia, suítes e gate. Os problemas de design identificados serão retomados no módulo 14.

## Corrija Sua Atividade Com IA

```text
Cenário: Analisei um trecho difícil de testar, propus uma refatoração pequena e defini um quality gate para código novo.

Tarefa: Avalie a melhoria de testabilidade e a política de aprovação.

Critérios de correção:
1. A refatoração separa regra e infraestrutura?
2. O teste ficou mais simples sem perder valor?
3. Regras, métricas e revisão humana estão diferenciadas?
4. Os limites são proporcionais ao risco?
5. Cobertura não foi tratada como qualidade absoluta?

Destaque os acertos, aponte imprecisões e ofereça dicas antes de sugerir uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

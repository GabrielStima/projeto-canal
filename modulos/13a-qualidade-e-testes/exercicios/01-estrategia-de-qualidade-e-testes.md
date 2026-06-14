# Exercício 01 — Estratégia de Qualidade e Testes

## O que você já sabe

Sua API possui contratos, autenticação, autorização e controles de segurança. No módulo anterior, você registrou riscos e cenários de sucesso e rejeição. Agora transformará esses riscos em uma estratégia de testes.

Esta atividade é obrigatória para continuidade. O documento produzido será atualizado nos exercícios seguintes.

## Sua tarefa

Escolha dois fluxos críticos já existentes, como:

- cadastro e login;
- aprovação de orçamento;
- atualização de prontuário;
- baixa de item do estoque.

Para cada fluxo:

1. descreva qualidade externa, interna e operacional;
2. liste caminho feliz, dois casos de rejeição e uma falha de infraestrutura;
3. avalie impacto e probabilidade;
4. escolha o nível de teste mais simples que reduz cada risco;
5. indique o que não será testado agora e justifique.

Use uma tabela:

| Risco ou comportamento | Impacto | Nível de teste | Evidência esperada | Prioridade |
| --- | --- | --- | --- | --- |

## O que você vai produzir

Um arquivo `docs/test-strategy.md` com os dois fluxos, a matriz de riscos e uma ordem de implementação.

## Critérios de conclusão

- Os testes são escolhidos por risco, não por preferência de ferramenta.
- A estratégia combina níveis diferentes.
- Casos negativos incluem segurança ou autorização quando aplicável.
- O custo de manutenção é considerado.
- O escopo excluído está explícito.

## Como este trabalho continuará

Os próximos exercícios implementarão partes desta estratégia e registrarão os resultados no mesmo documento.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei uma estratégia de qualidade e testes para dois fluxos de uma API fullstack. Mapeei riscos, impacto, nível de teste, evidência e prioridade.

Tarefa: Avalie se a estratégia é proporcional ao risco e se cada cenário está no nível de teste adequado.

Critérios de correção:
1. Qualidade externa, interna e operacional foram diferenciadas?
2. Existem caminhos felizes, rejeições e falhas de infraestrutura?
3. O nível escolhido oferece confiança sem custo desnecessário?
4. A estratégia evita concentrar tudo em testes unitários ou end-to-end?
5. O escopo excluído foi justificado?

Destaque os acertos, aponte imprecisões e ofereça dicas antes de sugerir uma estratégia completa.

[COLE SUA RESPOSTA AQUI]
```

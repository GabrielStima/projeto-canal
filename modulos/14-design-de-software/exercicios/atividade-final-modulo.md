# Atividade Final do Módulo

## O que você já tem

Ao longo do módulo, você escolheu um fluxo real e produziu:

- diagnóstico de responsabilidades e dependências;
- testes protegendo o comportamento;
- melhoria de nomes e limites;
- modelo com invariantes, quando necessário;
- decisões sobre abstração e princípios;
- dependências explícitas;
- composição ou comportamento encapsulado;
- escolha de padrão ou solução direta registrada em ADR.

Agora você consolidará a refatoração sem ampliar o escopo.

## Sua tarefa

Apresente a evolução do fluxo escolhido:

1. comportamento e problemas iniciais;
2. testes executados antes da mudança;
3. pequenas etapas de refatoração;
4. responsabilidades e dependências após a mudança;
5. invariantes protegidas;
6. abstrações, composição ou padrões adotados;
7. decisões de não abstrair;
8. ADR final;
9. evidência de que contrato, testes e sinais operacionais continuam válidos.

Não é obrigatório criar pastas `domain`, `use-cases` ou `infra`. Não é obrigatório usar Repository, Strategy ou container de injeção. Use essas estruturas somente se resolverem um problema demonstrado.

## O que você vai produzir

- código refatorado de um fluxo;
- testes antes e depois;
- `docs/design-review.md`;
- um ADR;
- diff ou resumo das etapas;
- limitações e próximos sinais de mudança.

## Demonstração mínima

Mostre:

- comportamento externo preservado;
- regra principal testada sem infraestrutura quando isso fizer sentido;
- integração real ainda validada;
- dependências relevantes explícitas;
- redução de pelo menos um problema do diagnóstico;
- custo introduzido pela nova estrutura.

## Critérios de conclusão

- A refatoração não adiciona feature.
- Cada mudança responde a um problema registrado.
- Princípios e padrões são usados como ferramentas, não checklist.
- A estrutura é proporcional ao fluxo.
- Testes e sinais sustentam a afirmação de que o comportamento foi preservado.
- Alternativas e riscos residuais estão documentados.

## Como este trabalho continuará

No módulo 15, você observará se os limites locais encontrados neste fluxo revelam fronteiras maiores do sistema. A arquitetura não será deduzida automaticamente de uma única refatoração.

## Corrija Sua Atividade Com IA

```text
Cenário: Refatorei um fluxo de uma aplicação TypeScript sem alterar seu comportamento externo. Registrei diagnóstico, testes, decisões, alternativas e um ADR.

Tarefa: Revise a proporcionalidade e a segurança da refatoração.

Critérios de correção:
1. Cada mudança responde a um problema observado?
2. O comportamento externo foi preservado por testes?
3. Regra e infraestrutura foram separadas somente onde necessário?
4. Invariantes, dependências e pontos de variação estão mais claros?
5. Princípios ou padrões adicionaram valor superior ao custo?
6. As decisões de não abstrair foram justificadas?
7. O ADR registra alternativas, consequências e riscos residuais?

Organize a resposta em acertos, riscos críticos, imprecisões e dicas priorizadas. Não reescreva toda a solução antes da minha tentativa de correção.

[COLE SUA RESPOSTA AQUI]
```

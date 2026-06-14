# Exercício 02 — Testes Unitários e Doubles

## O que você já sabe

Sua estratégia identificou regras que podem ser verificadas sem HTTP ou banco. Agora você testará uma unidade de comportamento e decidirá quando substituir dependências.

## Sua tarefa

Escolha uma regra de domínio existente, como cálculo de desconto, validação de data ou transição de status.

Escreva testes com:

- um caminho feliz;
- duas entradas inválidas ou casos de borda;
- nomes que descrevem comportamento;
- organização Arrange, Act, Assert ou Given, When, Then.

Depois escolha uma função que dependa de serviço externo, relógio, gerador de ID ou repositório. Defina se usará stub, fake ou mock e justifique por que esse double é o mais simples para o cenário.

Não simule o ORM em um teste que pretende validar a integração real com o banco.

## O que você vai produzir

- suíte unitária executável ou pseudocódigo compatível com o framework atual;
- registro da decisão sobre doubles;
- atualização da estratégia com o comando usado e o resultado.

## Critérios de conclusão

- Os testes verificam comportamento, não detalhes internos.
- A suíte roda sem servidor ou banco.
- Os casos de borda possuem resultados claros.
- O double substitui somente uma dependência necessária.
- Existe uma justificativa para não usar doubles em outras fronteiras.

## Como este trabalho continuará

No próximo exercício, a API e o banco serão testados juntos. Dificuldades para isolar a regra serão retomadas no exercício de testabilidade.

## Corrija Sua Atividade Com IA

```text
Cenário: Escrevi testes unitários para uma regra de domínio e escolhi um stub, fake ou mock para uma dependência externa.

Tarefa: Revise os testes e a decisão sobre o double.

Critérios de correção:
1. Os nomes descrevem comportamento observável?
2. Caminho feliz, entradas inválidas e bordas estão cobertos?
3. Os testes permanecem válidos após uma refatoração interna?
4. O double escolhido corresponde ao objetivo do teste?
5. Existe algum mock desnecessário ou uma integração real escondida?

Destaque os acertos, aponte imprecisões e dê dicas para eu revisar antes de apresentar código completo.

[COLE SUA RESPOSTA AQUI]
```

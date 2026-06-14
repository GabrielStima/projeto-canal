# Exercício 04 — Contrato e Regressão

## O que você já sabe

Sua API possui contratos definidos no módulo 11 e um ambiente de integração. Agora você protegerá a forma das respostas e transformará uma falha conhecida em regressão permanente.

## Sua tarefa

Escolha um endpoint consumido pelo frontend.

Crie:

1. um teste que valide status, campos obrigatórios e formato de erro;
2. um exemplo de mudança compatível que não deve quebrar o teste;
3. um exemplo de mudança incompatível que deve quebrá-lo.

Depois selecione um bug real ou plausível, como:

- permitir data passada;
- aprovar o mesmo orçamento duas vezes;
- acessar recurso de outro tutor;
- cadastrar identificador duplicado.

Escreva um teste de regressão no menor nível capaz de detectar o retorno do bug.

## O que você vai produzir

- teste de contrato;
- teste de regressão;
- descrição do consumidor protegido;
- atualização de `docs/test-strategy.md`.

## Critérios de conclusão

- O teste de contrato protege a interface pública, não a estrutura interna.
- Erros importantes também são validados.
- Compatibilidade e incompatibilidade estão diferenciadas.
- O teste de regressão reproduziria a falha antiga.
- O nível escolhido para regressão é proporcional ao risco.

## Como este trabalho continuará

Contrato e regressão entrarão no pipeline de CI e na atividade final.

## Corrija Sua Atividade Com IA

```text
Cenário: Escrevi um teste de contrato para um endpoint e um teste de regressão para impedir o retorno de um bug.

Tarefa: Avalie se os testes protegem comportamento público e risco real.

Critérios de correção:
1. O contrato valida status, campos obrigatórios e erros relevantes?
2. Mudanças compatíveis e incompatíveis foram classificadas corretamente?
3. O teste evita acoplamento ao banco ou à implementação interna?
4. A regressão falharia se o bug retornasse?
5. O nível de teste escolhido é o menor que oferece confiança suficiente?

Destaque os acertos, aponte imprecisões e dê dicas antes de escrever uma solução completa.

[COLE SUA RESPOSTA AQUI]
```

# Atividade Final do Módulo

## O que você já tem

Ao longo do módulo, você produziu estratégia, testes unitários, integração, contrato, regressão, jornada end-to-end, pipeline e quality gate.

Agora consolidará uma rede de segurança para **um fluxo crítico**, sem tentar testar toda a aplicação.

## Sua tarefa

Escolha um dos fluxos usados nos exercícios e entregue:

1. estratégia de risco atualizada;
2. testes unitários para ao menos uma regra;
3. testes de integração com um cenário de sucesso e um de falha;
4. proteção de contrato;
5. teste de regressão para um bug;
6. jornada E2E implementada, quando houver frontend, ou especificada de forma reproduzível;
7. pipeline de CI com os checks escolhidos;
8. quality gate proporcional ao código novo;
9. registro de uma fonte de flakiness evitada ou corrigida.

Use as ferramentas já adotadas no projeto. Não é necessário trocar framework de testes, banco ou provedor de CI.

## O que você vai produzir

- `docs/test-strategy.md`;
- suítes organizadas conforme a convenção do projeto;
- configuração de ambiente de integração;
- pipeline de CI;
- evidência de execução com resultados;
- breve registro das limitações da cobertura.

## Demonstração mínima

Mostre:

- teste unitário falhando quando a regra é quebrada;
- integração confirmando resposta e banco;
- contrato rejeitando uma mudança incompatível;
- regressão impedindo o retorno do bug;
- pipeline bloqueando uma alteração com falha.

Não é necessário buscar uma porcentagem arbitrária de cobertura. A evidência deve mostrar proteção dos riscos selecionados.

## Critérios de conclusão

- Cada teste está ligado a um risco da estratégia.
- Unidade, integração, contrato e E2E não se confundem.
- O ambiente de integração é isolado.
- O pipeline apresenta feedback em ordem eficiente.
- O quality gate combina automação e revisão humana.
- Limitações e riscos ainda não cobertos estão documentados.

## Como este trabalho continuará

No módulo 13B, o mesmo fluxo será medido e instrumentado. A suíte criada aqui servirá como referência para verificar se otimizações e instrumentação preservam o comportamento.

## Corrija Sua Atividade Com IA

```text
Cenário: Concluí uma rede de segurança para um fluxo crítico de uma aplicação fullstack. Tenho estratégia, testes unitários, integração, contrato, regressão, E2E implementado ou especificado, CI e quality gate.

Tarefa: Revise a coerência entre riscos, testes, pipeline e política de qualidade.

Critérios de correção:
1. Cada teste reduz um risco declarado?
2. Os níveis de teste estão bem separados?
3. O banco e o estado dos testes são isolados?
4. Contrato e regressão protegem comportamentos relevantes?
5. O pipeline oferece feedback rápido e bloqueia falhas importantes?
6. O quality gate é proporcional e não depende apenas de cobertura?
7. Limitações e possíveis fontes de flakiness foram registradas?

Organize a resposta em acertos, riscos críticos, imprecisões e dicas priorizadas. Não reescreva toda a solução antes da minha tentativa de correção.

[COLE SUA RESPOSTA AQUI]
```

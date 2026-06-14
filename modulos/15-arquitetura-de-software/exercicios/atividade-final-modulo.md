# Atividade Final do Módulo

## O que você já tem

Você construiu `docs/revisao-arquitetural.md` com forças arquiteturais, componentes, limites, comparação de estilos, análise de distribuição, comunicação assíncrona e alternativas operacionais.

## A Tarefa

Revise esse material e transforme-o em uma proposta arquitetural coerente para o estado atual do PetCare OS.

1. Desenhe os módulos principais e suas dependências.
2. Marque onde ficam políticas de negócio e detalhes técnicos.
3. Defina a direção permitida das dependências.
4. Escolha a arquitetura-base. O monólito modular deve ser o ponto de partida, salvo evidência concreta em favor de outra opção.
5. Selecione um fluxo candidato a processamento assíncrono e descreva seu contrato, sem implementar broker ou worker ainda.
6. Registre riscos, consequências e sinais que exigiriam reavaliar a decisão.
7. Crie `docs/adr/001-arquitetura-base.md` com contexto, decisão, alternativas consideradas e consequências.

## O que você vai produzir

- um mapa arquitetural atualizado em `docs/revisao-arquitetural.md`;
- uma ADR em `docs/adr/001-arquitetura-base.md`;
- um fluxo assíncrono especificado para ser implementado no módulo 16.

Esse material será retomado no próximo módulo para implementar comunicação assíncrona e atualização de estado para o usuário.

## Critérios de conclusão

- a arquitetura responde às restrições e aos atributos de qualidade levantados;
- cada módulo possui responsabilidade e dependências compreensíveis;
- a decisão não exige distribuição ou infraestrutura sem necessidade;
- o fluxo assíncrono foi especificado com falhas e duplicidade em mente;
- a ADR registra também custos e alternativas rejeitadas.

## Corrija Sua Atividade Com IA

```text
Cenário: Concluí uma revisão arquitetural de uma API existente. Minha proposta contém módulos, dependências, separação entre políticas e detalhes, arquitetura-base, um fluxo assíncrono ainda não implementado, riscos e uma ADR.

Tarefa: Faça uma revisão crítica da proposta e da ADR.

Critérios de correção:
1. A arquitetura é proporcional às restrições e aos atributos de qualidade?
2. Responsabilidades, limites e direção das dependências estão claros?
3. A decisão evita distribuição e infraestrutura sem evidência?
4. O fluxo assíncrono possui contrato, participantes e tratamento conceitual de falha e duplicidade?
5. A ADR apresenta contexto, decisão, alternativas e consequências reais?
6. O material permite que outra pessoa implemente o próximo passo sem adivinhar decisões essenciais?

Comece destacando os acertos. Depois aponte imprecisões, riscos e lacunas. Dê dicas priorizadas antes de apresentar qualquer proposta completa.

[COLE SUA RESPOSTA AQUI]
```

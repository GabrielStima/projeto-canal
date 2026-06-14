# Exercício 03 — Ferramentas e Limites de Autonomia

## O Que Você Já Possui

Sua especificação define o escopo do assistente e seu workflow de desenvolvimento já possui limites de atuação.

## A Tarefa

Escolha uma ferramenta somente leitura e, opcionalmente, uma ação reversível. Exemplos: consultar horários disponíveis ou preparar uma solicitação de retorno sem confirmá-la.

Acrescente a `docs/sistema-ia.md`:

1. schema de entrada e saída de cada ferramenta;
2. validação de tipos e regras de negócio fora do modelo;
3. identidade e permissões mínimas;
4. separação entre conteúdo externo e instruções confiáveis;
5. confirmação humana antes de ações com efeito;
6. idempotência e prevenção de duplicidade;
7. limites de chamadas, tempo e custo;
8. tratamento de timeout e resposta inválida;
9. registro de ferramentas chamadas e resultados;
10. cenários de prompt injection, abuso de privilégio e falha em cascata;
11. forma segura de interromper o fluxo.

O modelo pode sugerir parâmetros, mas autorização e validação devem permanecer em código.

## O Que Você Vai Produzir

Um contrato de ferramentas e autonomia que limita o impacto de interpretações ou instruções incorretas.

Esse contrato será testado nos evals e integrado ao protótipo final quando o caso de uso precisar de ferramentas.

## Corrija Sua Atividade Com IA

```text
Cenário: Projetei ferramentas e limites de autonomia para um assistente do PetCare OS.

Tarefa: Revise meus schemas, permissões, confirmações e modos de falha.

Critérios de correção:
1. Entradas e saídas possuem schemas restritos.
2. Autorização e regras de negócio são verificadas fora do modelo.
3. A identidade do agente usa menor privilégio.
4. Conteúdo recuperado não pode redefinir instruções confiáveis.
5. Ações sensíveis ou irreversíveis exigem confirmação adequada.
6. Idempotência, limites, timeouts e interrupção segura estão definidos.
7. Chamadas e decisões podem ser auditadas sem registrar dados desnecessários.

Primeiro destaque meus acertos. Depois aponte caminhos de abuso ou permissões excessivas e ofereça dicas. Só apresente um desenho completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

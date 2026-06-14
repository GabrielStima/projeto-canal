# Exercício 05 — Logs Seguros e Auditoria

## O Que Você Já Possui

Seu documento identifica dados, acessos, retenção e transformações. Agora você precisa manter observabilidade e rastreabilidade sem criar uma cópia desnecessária dos dados.

## A Tarefa

Escolha uma operação sensível, como consulta de prontuário autorizado, exportação de dados ou alteração de informações financeiras.

Adicione a `docs/governanca-dados.md`:

1. um exemplo de log operacional seguro;
2. um exemplo de evento de auditoria;
3. uma allowlist de campos permitidos para cada registro;
4. campos que devem ser removidos ou mascarados na origem;
5. retenção e grupos com acesso;
6. correlação entre evento técnico e evento auditável;
7. alerta para padrão de acesso incomum;
8. teste automatizado que falha se um campo proibido aparecer.

Prefira logs estruturados e filtragem por chave. Regex pode complementar a proteção, mas não deve ser a única barreira para payloads arbitrários.

## O Que Você Vai Produzir

Um contrato de logging e auditoria que preserva investigação, prestação de contas e minimização.

Ele também definirá quais informações podem ser usadas ao pedir ajuda a uma ferramenta de IA.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei logs operacionais e eventos de auditoria para uma operação sensível do PetCare OS.

Tarefa: Revise minha allowlist, exemplos, retenção, acesso, alerta e teste de vazamento.

Critérios de correção:
1. Log operacional e evento de auditoria possuem finalidades diferentes.
2. Payloads, tokens, cookies e dados desnecessários são removidos na origem.
3. O evento de auditoria registra ator, ação, recurso, finalidade, resultado e correlação sem copiar o conteúdo sensível.
4. Acesso e retenção são proporcionais à finalidade.
5. O alerta identifica comportamento incomum sem depender de dados excessivos.
6. O teste consegue detectar regressões de logging.

Primeiro destaque meus acertos. Depois aponte campos perigosos ou lacunas e ofereça dicas. Só apresente uma solução completa depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

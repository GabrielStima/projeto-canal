# Exercício 05 — Contrato de Webhook

## Objetivo

Desenhar um webhook sem transformar notificações em uma nova funcionalidade obrigatória da API.

## O Que Você Já Possui

- contratos OpenAPI;
- uma operação de aprovação de orçamento;
- conhecimento de idempotência, retries e erros;
- o contexto auxiliar de notificações do PetCare OS.

Esta atividade é **exploratória e recomendada**. Você vai documentar o contrato, mas não precisa implementar entrega, fila, assinatura criptográfica ou serviço de notificações agora.

## Sua Tarefa

Desenhe o evento `budget.approved` para um consumidor externo de notificações:

1. defina identificador, tipo, data de criação e versão do evento;
2. inclua somente os dados necessários para identificar orçamento, pet e tutor;
3. descreva como o consumidor evita processamento duplicado;
4. defina timeout, política limitada de retry e status esperados;
5. registre que autenticação da origem e gestão de segredos serão aprofundadas depois;
6. documente o webhook em `docs/webhooks.md` e, opcionalmente, no objeto `webhooks` da OpenAPI 3.1.

## O Que Você Vai Produzir

- `docs/webhooks.md`;
- exemplo de payload;
- tabela de comportamento para sucesso, timeout, erro transitório e evento duplicado;
- decisão explícita sobre implementar ou apenas manter o contrato nesta versão.

## Critérios de Conclusão

- o evento possui ID único e versão;
- o payload não inclui prontuário, diagnóstico ou outros dados desnecessários;
- duplicidade e ausência de ordem estão documentadas;
- retries têm limite;
- o texto diferencia claramente contrato de webhook e mecanismo real de entrega.

Este desenho poderá ser retomado no módulo 16, quando filas, jobs e comunicação assíncrona forem aprofundados.

## Corrija Sua Atividade Com IA

```text
Estou desenhando, sem implementar, um webhook budget.approved da PetCare API para um serviço externo de notificações.

O contrato deve incluir ID único do evento, tipo, versão, data de criação e apenas identificadores necessários de orçamento, pet e tutor. Também deve documentar duplicidade, possível falta de ordem, timeout, retries limitados e status HTTP esperados. Autenticação da origem e gestão de segredos serão aprofundadas em módulos posteriores.

Critérios de correção:
1. o payload é mínimo e não expõe dados clínicos desnecessários;
2. o evento tem identidade e versão;
3. o consumidor consegue deduplicar;
4. retry e timeout estão definidos;
5. o documento não promete entrega exatamente uma vez;
6. contrato e implementação estão claramente diferenciados.

Analise minha proposta. Comece pelos acertos, depois mostre imprecisões e riscos. Dê dicas para eu melhorar o contrato antes de fornecer uma resposta completa.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 06 — Decisões de Integração

Esta atividade é obrigatória para a continuidade. Você vai decidir se broker e motor de busca são necessários agora, sem ampliar o projeto por entusiasmo tecnológico.

## O Que Você Já Possui

A API persistente implementa um fluxo vertical e possui logs e análise de falhas. Você estudou message brokers e motores de busca em nível introdutório.

## Sua Tarefa

Crie `docs/decisoes-de-integracao.md` analisando dois casos:

### Notificação de orçamento aprovado

Avalie:

- fazer durante a requisição;
- executar em processo separado;
- usar fila ou broker futuramente;
- falhas, repetição e atraso aceitável.

### Busca de pets e atendimentos

Avalie:

- filtros simples no banco;
- busca textual mais rica;
- dados que poderiam ser indexados;
- dados sensíveis que não devem entrar em índice externo;
- sincronização e reindexação.

Para cada caso, registre:

1. necessidade atual;
2. solução mais simples suficiente;
3. sinais que justificariam outra tecnologia;
4. falhas adicionais introduzidas;
5. decisão para a primeira versão.

É válido decidir não usar broker nem motor de busca.

## Critérios de Conclusão

- a decisão parte de requisitos observáveis;
- trabalho assíncrono não é confundido com ausência de falhas;
- mensagens duplicadas e perdidas são reconhecidas;
- o banco continua sendo a fonte oficial quando houver índice de busca;
- dados sensíveis são considerados;
- a primeira versão evita infraestrutura sem necessidade;
- condições futuras são concretas e revisáveis.

Guarde o documento. Ele servirá de contexto nos módulos de comunicação assíncrona e system design.

## Corrija Sua Atividade Com IA

```text
Estou registrando decisões de integração para a primeira versão da API do PetCare OS.

Analisei:
- notificação após aprovação de orçamento;
- execução durante a requisição, processo separado ou broker futuro;
- busca simples no banco e busca textual especializada;
- fonte oficial, sincronização, reindexação e dados sensíveis;
- sinais que justificariam novas tecnologias.

É permitido decidir não usar broker nem motor de busca agora.

Critérios de correção:
1. decisões devem partir de requisitos atuais;
2. a solução mais simples suficiente deve ser considerada;
3. duplicidade, perda, atraso e reprocessamento devem aparecer na análise assíncrona;
4. o índice de busca não deve virar fonte oficial sem justificativa;
5. dados sensíveis não devem ser indexados indiscriminadamente;
6. sinais futuros devem ser mensuráveis;
7. novas falhas e custos operacionais devem ser reconhecidos.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões, contradições ou tecnologia sem justificativa;
3. ofereça perguntas e dicas antes de substituir minhas decisões;
4. permita que eu revise;
5. só apresente uma resposta completa se eu pedir depois.

[COLE SUA RESPOSTA AQUI]
```

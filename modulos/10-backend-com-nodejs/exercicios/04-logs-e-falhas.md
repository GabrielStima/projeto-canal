# Exercício 04 — Logs e Falhas

Esta atividade é obrigatória para a continuidade. Você vai tornar o fluxo persistente investigável e previsível diante de problemas comuns.

## O Que Você Já Possui

A API já expõe endpoints JSON e usa banco relacional com transaction. Você estudou logging estruturado e failure modes.

## Sua Tarefa

Adicione um identificador de requisição e logs estruturados para:

- início e conclusão da requisição;
- pet ou orçamento não encontrado;
- entrada inválida;
- aprovação de orçamento concluída;
- rollback da aprovação;
- banco indisponível;
- erro inesperado.

Cada log deve possuir apenas o contexto necessário, como:

- nível;
- evento;
- request ID;
- rota;
- status;
- duração;
- identificador técnico do recurso quando apropriado.

Crie `docs/failure-modes.md` analisando pelo menos:

1. payload inválido;
2. recurso inexistente;
3. orçamento já processado;
4. banco indisponível;
5. timeout;
6. erro inesperado;
7. processo encerrado durante uma requisição.

Para cada caso, registre a resposta esperada, o que será logado e o que não deve ser exposto ao cliente.

## Critérios de Conclusão

- logs são estruturados e correlacionáveis por request ID;
- senhas, tokens, strings de conexão e dados clínicos não aparecem nos logs;
- erros esperados não são todos transformados em `500`;
- erro interno não devolve stack trace ao cliente;
- rollback possui evidência de log sem dados sensíveis;
- o documento diferencia falha de entrada, conflito, dependência e erro interno;
- o encerramento do processo considera requisições em andamento.

Guarde o documento e os logs. Eles serão usados nos módulos de testes e observabilidade.

## Corrija Sua Atividade Com IA

```text
Estou adicionando logs estruturados e análise de falhas à API Node.js do PetCare OS.

Minha entrega contém:
- request ID;
- logs de início, conclusão, validação, não encontrado, aprovação, rollback, banco indisponível e erro inesperado;
- docs/failure-modes.md com payload inválido, recurso inexistente, conflito, indisponibilidade, timeout, erro inesperado e encerramento do processo.

Critérios de correção:
1. logs devem ser estruturados e correlacionáveis;
2. não podem conter segredos nem dados clínicos sensíveis;
3. erros esperados devem receber categorias e status coerentes;
4. detalhes internos e stack traces não podem chegar ao cliente;
5. duração e resultado da operação devem ser investigáveis;
6. rollback deve deixar evidência segura;
7. cada failure mode deve indicar resposta, log e informação ocultada;
8. encerramento do processo deve considerar requisições em andamento.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões e riscos de vazamento ou diagnóstico insuficiente;
3. ofereça dicas antes de fornecer código ou documento completo;
4. permita que eu revise;
5. só apresente uma solução completa se eu pedir depois.

[COLE SUA RESPOSTA AQUI]
```

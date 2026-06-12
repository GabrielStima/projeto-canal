# Exercício 03 — Lendo Uma Troca HTTP

Faça este exercício depois da aula [HTTP](../01.07-http.md).

## Cenário

O browser pediu ao servidor a página de acompanhamento de um pet:

```text
GET /pets/123/status HTTP/1.1
Host: app.petcareos.com.br
```

O servidor respondeu:

```text
HTTP/1.1 200 OK
Content-Type: text/html

<h1>Status: Em atendimento</h1>
```

## Sua Tarefa

Identifique:

| Elemento | Valor encontrado |
| --- | --- |
| Método HTTP | |
| Caminho solicitado | |
| Host | |
| Status da resposta | |
| Tipo do conteúdo | |
| Conteúdo principal | |

Depois, responda:

1. Qual parte representa a request?
2. Qual parte representa a response?
3. O que o código `200` comunica?
4. O browser recebeu uma tela pronta ou conteúdo que ainda precisa interpretar?

## Corrija Sua Atividade Com IA

Depois de concluir a atividade, copie o prompt abaixo, substitua o campo indicado pela sua resposta e envie para uma IA:

```text
Estou estudando a estrutura básica de uma troca HTTP.

Analisei esta request:

GET /pets/123/status HTTP/1.1
Host: app.petcareos.com.br

E esta response:

HTTP/1.1 200 OK
Content-Type: text/html

<h1>Status: Em atendimento</h1>

Minha tarefa foi identificar método, caminho, host, status, tipo de conteúdo e conteúdo principal. Também expliquei a diferença entre request e response, o significado geral de `200` e o papel do browser depois de receber o conteúdo.

Analise minha resposta usando estes critérios:
- método, caminho, host, status, header e body foram identificados corretamente;
- request e response foram diferenciadas;
- o status `200` foi interpretado como sucesso;
- foi reconhecido que o browser ainda precisa interpretar o HTML recebido.

Primeiro, aponte o que está correto. Depois, indique erros ou partes imprecisas sem reescrever toda a atividade por mim. Para cada problema, dê uma dica e permita que eu tente corrigir. Só apresente uma resposta completa se eu pedir.

Minha resposta:
[COLE SUA RESPOSTA AQUI]
```

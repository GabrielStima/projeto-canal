# Exercício 06 — Escalonamento Horizontal

## Tarefa

Seja direto na dor: Você provisionou 10 Contêineres rodando debaixo do mesmo Load Balancer da API do hospital. Mas o programador programou os Uploads de RX para gravarem no comando nativo `fs.writeFile('minha_pasta/exame.pdf')` e guardarem na RAM do Node as Sessões Autenticadas. Como esse terrível "Estado (Stateful)" quebra a Escalabilidade do negócio e gera os erros mais estúpidos de 'Arquivo não encontrado' e deslogadas aleatórias pros clientes no 2º Refresh?

## Corrija Sua Atividade Com IA

```text
Cenário: Aplicações Nativas da Nuvem (12-Factor Apps, Statelessness).

Tarefa: Minha explicação da ruína de não externalizar arquivos para o S3 Object Storage ou Redis do cluster:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Clarifiquei perfeitamente que o Load Balancer distribui os requests? (Ex: Request 1 joga o Exame no Node A e o Request 2 na hora de baixar a imagem cai no Node C que está estéril e retorna 404 Not Found)?
2. Pontuei que a API não confia nela mesma e não sabe onde os outros containers de cópia dela andam morando na nuvem?
```

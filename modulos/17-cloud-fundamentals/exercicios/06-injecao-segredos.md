# Exercício 06 — Injeção de Segredos

## Tarefa

Descreva os passos lógicos de como sua API Node leria e decifraria a senha do Banco de Dados usando o `AWS Secrets Manager` no momento do Deploy ou Startup, garantindo que o arquivo não ficasse exposto em um texto simples `.env` que um estagiário poderia roubar.

## Corrija Sua Atividade Com IA

```text
Cenário: Gerenciamento seguro de configuração usando Serviços Gerenciados de Secretos.

Tarefa: Segue meu fluxo:
[COLE AQUI]

Critérios de correção:
1. O Node.js se autentica no IAM via Role embarcada em vez de usar senhas hardcoded para buscar senhas?
2. O sistema de inicialização carrega as chaves apenas em memória volátil, fechando buracos no git?
```

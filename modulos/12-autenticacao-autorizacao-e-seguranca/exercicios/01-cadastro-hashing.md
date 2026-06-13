# Exercício 01 — Cadastro e Hashing

## Tarefa

Implemente mentalmente (ou escrevendo o pseudocódigo) a etapa de cadastro do Tutor no PetCare OS.

O formulário envia `email`, `nome` e `senha`. Você deve garantir que a senha original nunca chegue ao banco de dados puro, utilizando uma biblioteca como `bcrypt` ou `argon2`. O banco não precisa de uma conexão de verdade, apenas desenhe a lógica de validação, hash e inserção.

## Requisitos

- A rota recebe um POST com JSON.
- Verifica o comprimento mínimo da senha.
- Realiza o hash da senha usando um salt embutido (ex: `bcrypt.hash(password, 12)`).
- Retorna um JSON de sucesso, sem retornar dados de senha/hash na resposta.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou criando a rota de cadastro de Tutores para o PetCare OS e quero validar meu entendimento de como processar senhas com segurança no backend.

Tarefa: Escrevi o pseudocódigo / lógica de cadastro abaixo.
- A rota recebe: nome, email, senha.
- Verifica e hasheia a senha.
- Retorna o JSON de sucesso.

Critérios de correção:
1. O texto original da senha vazou para algum log ou response?
2. O hash foi gerado de forma correta (mencionou o uso de "custo" ou algoritmo apropriado)?
3. A resposta de erro dá muita dica se um email já existir?

[COLE SUA RESPOSTA AQUI]

Por favor, valide minha solução. Destaque acertos, aponte eventuais imprecisões de segurança e me faça 1 pergunta extra antes de propor um código ideal.
```

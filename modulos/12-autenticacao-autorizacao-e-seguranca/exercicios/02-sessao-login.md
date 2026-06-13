# Exercício 02 — Sessão e Login

## Tarefa

Elabore a lógica de validação de login para os veterinários e administradores no Módulo Clínico do PetCare OS, usando sessões ou tokens.

## Requisitos

- O usuário envia `email` e `senha` via POST para a rota de login.
- O sistema recupera o usuário do banco e seu respectivo hash.
- Utilize a função apropriada (ex: `bcrypt.compare`) para comparar.
- Se for inválido, emita um erro genérico (ex: "Credenciais inválidas") para não enumerar os e-mails.
- Se for válido, especifique como você criaria a sessão de fato: geraria um Token e enviaria em um Cookie `HttpOnly`, ou devolveria um Access Token no Payload.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou construindo a lógica de login dos veterinários no PetCare OS.

Tarefa: Escrevi a rota abaixo que recebe o login, compara as credenciais com bcrypt e cria uma sessão para o usuário.

Critérios de correção:
1. O fluxo de erro "usuário não encontrado" e "senha incorreta" estão dando mensagens diferentes que permitiriam um atacante descobrir quais emails são válidos?
2. A criação da sessão (cookie ou payload) foi pensada de maneira segura?
3. O fluxo está exposto a ataque de força bruta desenfreado?

[COLE SUA RESPOSTA AQUI]

Por favor, analise a segurança da minha lógica de login. Destaque meus acertos e minhas falhas. Não reescreva o código de imediato: pergunte-me como consertar as falhas antes de enviar a resposta final.
```

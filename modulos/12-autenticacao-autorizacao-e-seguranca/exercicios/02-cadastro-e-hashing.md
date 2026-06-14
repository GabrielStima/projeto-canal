# Exercício 02 — Cadastro e Hashing

## O que você já sabe

Você já sabe modelar dados, criar endpoints e armazenar informações no banco. Também identificou, no mapa de riscos, que credenciais não podem ser tratadas como dados comuns.

Nesta prática, você criará a base de identidade da API. Use uma biblioteca madura de hashing de senhas compatível com o seu projeto. Não crie um algoritmo próprio.

## Sua tarefa

Implemente ou escreva um pseudocódigo detalhado para `POST /api/auth/register`.

O fluxo deve:

1. validar nome, e-mail e senha;
2. normalizar o e-mail conforme a convenção do projeto;
3. impedir cadastro duplicado sem expor dados desnecessários;
4. gerar o hash com um algoritmo próprio para senhas;
5. salvar somente o hash;
6. retornar o usuário criado sem senha ou hash;
7. evitar que credenciais apareçam em logs e mensagens de erro.

Atualize também o modelo de dados para separar os campos de identidade dos dados de autenticação. Você pode usar a estrutura já existente no projeto; não é necessário trocar de ORM ou banco.

## O que você vai produzir

- alteração de schema ou desenho equivalente para usuário e credencial;
- implementação ou pseudocódigo executável da rota de cadastro;
- exemplo de request e response;
- atualização do mapa de riscos com os controles aplicados.

## Critérios de conclusão

- A senha em texto puro existe somente durante o processamento da requisição.
- O banco recebe o hash, nunca a senha original.
- A resposta não contém senha nem hash.
- O algoritmo e seu custo podem ser atualizados no futuro.
- Erros e logs não permitem recuperar credenciais.
- A rota mantém o formato de erros já adotado pela API.

## Como este trabalho continuará

O registro criado será usado no exercício de login. No módulo 13A, esse fluxo será coberto por testes de sucesso, duplicidade e senha inválida.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou implementando POST /api/auth/register em uma API Node.js/TypeScript. A rota valida nome, e-mail e senha, gera um hash com uma biblioteca própria para senhas, salva a credencial e retorna o usuário sem dados sensíveis.

Tarefa: Revise meu modelo de dados e o fluxo de cadastro abaixo.

Critérios de correção:
1. A senha original pode chegar ao banco, ao log ou à resposta?
2. O algoritmo escolhido é adequado para senhas e usa custo configurável?
3. O fluxo trata validação e duplicidade sem expor informações desnecessárias?
4. A resposta remove senha e hash?
5. A solução preserva o padrão de erros da API?

Antes de fornecer código completo:
- destaque os acertos;
- aponte riscos ou imprecisões;
- dê dicas específicas para eu ajustar a solução;
- espere minha nova tentativa antes de mostrar uma implementação completa.

[COLE SUA RESPOSTA AQUI]
```

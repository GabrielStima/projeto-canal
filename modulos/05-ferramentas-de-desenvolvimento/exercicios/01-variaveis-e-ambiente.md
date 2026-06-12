# Exercício 01 — Variáveis e Ambiente do PetCare OS

## O que você já sabe

Você estudou que projetos reais precisam de configurações que variam de um ambiente para outro: porta do servidor, URL da API, modo de execução e credenciais de banco. Esses valores não devem ficar fixos no código, e arquivos `.env` reais não devem ser versionados.

## Cenário

O PetCare OS é uma plataforma para clínicas veterinárias e petshops. Em desenvolvimento, ele roda localmente. Em produção, ele roda em servidores diferentes. Algumas configurações mudam entre esses ambientes:

- porta do servidor;
- URL da API;
- string de conexão com o banco;
- chave de envio de notificações.

## Tarefa

Crie um arquivo `.env.example` para o PetCare OS com quatro variáveis que façam sentido para esse projeto. Depois, escreva uma explicação curta indicando:

1. qual o valor padrão para desenvolvimento local;
2. qual variável é sensível e por quê;
3. o comando ou passo que uma pessoa nova deve seguir para criar seu próprio `.env` a partir do exemplo.

Não escreva valores reais de produção nem credenciais verdadeiras. Use apenas valores fictícios de desenvolvimento.

## Critérios de Correção

- Pelo menos quatro variáveis relevantes para um sistema de clínicas veterinárias.
- Uma delas claramente sensível (banco, chave de API, token etc.).
- Valores de desenvolvimento plausíveis e não secretos.
- Explicação de como gerar o `.env` local a partir do `.env.example`.
- Nenhuma credencial real ou valor de produção exposto.

## Corrija Sua Atividade Com IA

```text
Cenário: estou configurando o ambiente local do PetCare OS, uma plataforma para clínicas veterinárias e petshops. Preciso documentar as variáveis de ambiente esperadas sem expor segredos.

Tarefa: crie um arquivo .env.example com quatro variáveis relevantes para o projeto, defina valores fictícios de desenvolvimento, indique qual é sensível e explique como uma pessoa nova cria seu .env local.

Critérios de correção:
1. Pelo menos quatro variáveis relevantes para clínicas veterinárias.
2. Uma variável claramente sensível, com justificativa.
3. Valores de desenvolvimento plausíveis e não secretos.
4. Comando ou passo para criar o .env a partir do .env.example.
5. Nenhuma credencial real ou valor de produção exposto.

[COLE SUA RESPOSTA AQUI]

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas. Só depois mostre uma versão de referência.
```

# Exercício 01 — Base do Serviço Node.js

Esta atividade é obrigatória para a continuidade. Você vai criar a base do backend que será ampliada durante o módulo.

## O Que Você Já Possui

Você já sabe TypeScript, módulos, terminal, variáveis de ambiente, HTTP e tratamento de erros. O módulo 09 também deixou um diretório `database/` com schema, seed, consultas e migrations do PetCare OS.

## Sua Tarefa

Crie um projeto chamado `petcare-api` no mesmo repositório do projeto evolutivo. Preserve o diretório `database/`; não recrie o modelo de dados.

Organize uma base mínima:

```text
petcare-api/
├── src/
│   ├── config.ts
│   ├── health.ts
│   └── server.ts
├── database/
├── package.json
├── tsconfig.json
└── .env.example
```

Implemente:

1. configuração de porta e conexão com banco lida do ambiente;
2. uma CLI `check-env` que informa configurações ausentes e usa código de saída diferente de zero;
3. um servidor com o módulo `node:http`;
4. `GET /health` retornando JSON e status `200`;
5. resposta JSON com status `404` para caminhos desconhecidos;
6. encerramento do servidor quando o processo receber um sinal de término.

Não coloque segredos reais em `.env.example`. Use nomes e valores fictícios.

## Critérios de Conclusão

- o projeto inicia por um script do `package.json`;
- imports de módulos nativos usam o prefixo `node:`;
- a CLI falha quando uma configuração obrigatória não existe;
- `/health` devolve `Content-Type: application/json`;
- caminhos desconhecidos não devolvem `200`;
- configuração, health check e servidor ficam em módulos separados;
- o diretório `database/` recebido do módulo anterior permanece preservado.

Guarde o projeto. No próximo exercício, o servidor será evoluído para uma API JSON usando um framework.

## Corrija Sua Atividade Com IA

```text
Estou construindo a base Node.js do backend do PetCare OS.

Minha entrega possui:
- TypeScript e scripts de projeto;
- configuração por variáveis de ambiente;
- CLI check-env com código de saída;
- servidor node:http;
- GET /health em JSON;
- resposta 404;
- encerramento do servidor por sinal;
- módulos separados para configuração, health e servidor;
- diretório database preservado do módulo anterior.

Critérios de correção:
1. módulos nativos devem usar imports node:;
2. nenhum segredo real deve estar versionado;
3. configuração ausente deve produzir mensagem e código de saída de erro;
4. /health deve responder JSON com status 200;
5. rota desconhecida deve responder 404;
6. a resposta deve ser encerrada corretamente;
7. a estrutura não deve misturar toda a lógica em um único arquivo;
8. o encerramento deve parar de aceitar novas conexões antes de finalizar.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões e riscos;
3. ofereça dicas específicas antes de escrever uma solução completa;
4. permita que eu tente corrigir;
5. só apresente arquivos completos se eu pedir depois.

[COLE SUA RESPOSTA AQUI]
```

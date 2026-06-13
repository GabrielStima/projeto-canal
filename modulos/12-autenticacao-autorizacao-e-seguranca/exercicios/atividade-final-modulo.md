# Atividade Final do Módulo

## O que você já tem

Nos módulos anteriores, a API do PetCare OS foi desenhada usando frameworks modernos e padrões REST, conectando-se a um banco de dados. No entanto, ela estava aberta: qualquer cliente HTTP poderia invocar mutações nas consultas e no estoque.

## A Tarefa

Este é o **marco de integração** do Módulo 12. Sua tarefa é integrar todas as proteções em uma versão da sua aplicação. Você criará middlewares e fluxos de segurança que garantam que os dados dos pets fiquem acessíveis apenas àqueles que devem acessá-los.

Siga as etapas:
1. Adicione a entidade de Usuário/Credencial à base de dados.
2. Construa a rota genérica `POST /api/auth/register` (para novos tutores) garantindo hashing seguro (bcrypt/argon2).
3. Construa a rota `POST /api/auth/login`, definindo as sessões ou tokens.
4. Aplique Rate Limiting de forma simples nessa rota de login.
5. Crie um middleware de Autenticação (`requireAuth`) que verifica a existência de credenciais ativas na requisição (bearer token ou cookie).
6. Mapeie todas as rotas atuais da sua API e proteja-as.
7. Crie o middleware de Autorização (`requireRole(['CLINICO', 'ADMIN'])`) e use-o para trancar a rota de exclusão de cadastros.

## O que você vai produzir

- Rotas de Autenticação funcionais no seu projeto Node.js.
- Middlewares de segurança acoplados aos endpoints existentes.
- Um "Checklist de Segurança" preenchido no seu `README` ou `SECURITY.md` (auditando endpoints principais e revisando possíveis Injeções SQL na sua camada de dados).

## Como este trabalho continuará

As camadas de segurança criadas agora serão os alicerces fundamentais da qualidade no próximo módulo, quando escreveremos Testes Automatizados (E2E e Unitários) não apenas para fluxos de sucesso, mas também para os casos onde as requisições devem retornar exatamente erros `401 Unauthorized` ou `403 Forbidden`.

## Corrija Sua Atividade Com IA

Ao finalizar a refatoração, copie as seções chaves de seus middlewares e rotas de login.

```text
Cenário: Concluí o marco de segurança do projeto.

Tarefa: Estou compartilhando o código do meu "Auth Middleware" e as rotas de login/registro. Minha API agora responde com 401 para usuários não logados e 403 para usuários sem permissão adequada no RBAC.

Critérios de correção:
1. Os dados sensíveis (senhas) foram processados de forma correta e assíncrona?
2. A recuperação dos tokens ou sessão respeita a semântica HTTP? (ex: ler Header `Authorization` corretamente).
3. A manipulação de requisições falhas envia um erro descritivo o suficiente pro desenvolvedor do Front-end mas discreto o suficiente pro Atacante?
4. A query no banco está prevenida de SQL Injection, caso use query builders puros?

[COLE SUA RESPOSTA AQUI]

Por favor, faça um code review de segurança. Destaque primeiro os acertos de arquitetura e depois os riscos que encontrou. Indique as falhas com clareza para eu corrigi-las.
```

# Exercício 07 — CORS, XSS e SQL Injection

## O que você já sabe

Autenticação e autorização protegem identidade e acesso, mas não tornam toda entrada segura. Agora você revisará três fronteiras diferentes:

- o browser decidindo se uma origem pode ler a resposta;
- conteúdo controlado por usuário sendo exibido na interface;
- entrada sendo enviada ao banco de dados.

## Sua tarefa

Resolva os três casos abaixo na aplicação ou em um laboratório pequeno.

### Caso A — CORS

Defina uma política para permitir somente os frontends conhecidos do projeto. Registre:

- origens permitidas por ambiente;
- métodos e headers necessários;
- se credenciais serão aceitas;
- comportamento do preflight.

### Caso B — XSS

Escolha um campo de texto exibido no portal ou painel, como observação de atendimento. Demonstre:

- onde o dado entra;
- como ele é armazenado;
- como ele é renderizado como texto;
- que tratamento adicional seria necessário caso HTML fosse permitido.

Não crie uma função caseira de sanitização.

### Caso C — SQL injection

Encontre ou escreva uma consulta que recebe entrada do cliente. Substitua concatenação ou interpolação por parâmetros ou por uma API segura do ORM/query builder.

## O que você vai produzir

- configuração ou tabela de política CORS;
- demonstração de renderização segura;
- consulta parametrizada;
- três registros novos no mapa de riscos, com evidência da correção.

## Critérios de conclusão

- CORS não é apresentado como autenticação ou bloqueio de clientes fora do browser.
- Origens com credenciais são explícitas, sem curinga.
- Dado não confiável é renderizado como texto por padrão.
- Sanitização é reservada aos casos em que HTML realmente precisa ser aceito.
- A consulta separa comando e dado por parametrização.
- Validação não é usada como substituto de query parametrizada.

## Como este trabalho continuará

Na atividade final, você selecionará ao menos uma evidência de cada fronteira e a incluirá na revisão de segurança da API.

## Corrija Sua Atividade Com IA

```text
Cenário: Revisei três fronteiras de uma aplicação fullstack: CORS no browser, conteúdo não confiável renderizado na interface e entrada usada em uma consulta ao banco.

Tarefa: Avalie minha política CORS, minha estratégia contra XSS e minha consulta parametrizada.

Critérios de correção:
1. CORS foi explicado como política aplicada pelo browser?
2. Origens, credenciais, métodos, headers e preflight estão coerentes?
3. O conteúdo do usuário é renderizado como texto por padrão?
4. A solução evita sanitização caseira?
5. A consulta usa parametrização ou API segura do ORM?
6. Validação e parametrização não foram confundidas?

Separe a revisão em CORS, XSS e SQL injection. Destaque acertos, aponte imprecisões e dê dicas antes de apresentar qualquer solução completa.

[COLE SUA RESPOSTA AQUI]
```

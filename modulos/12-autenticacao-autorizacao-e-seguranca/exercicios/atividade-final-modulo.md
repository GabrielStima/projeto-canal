# Atividade Final do Módulo

## O que você já tem

Ao longo do módulo, você:

- mapeou riscos da API;
- criou cadastro com hashing de senha;
- praticou login, sessão, cookie e proteção contra CSRF;
- comparou sessão, token opaco e JWT;
- definiu autorização por papel e por recurso;
- analisou OAuth como alternativa exploratória;
- revisou CORS, XSS e SQL injection;
- aplicou rate limiting e concluiu um checklist por endpoint.

Agora você integrará somente as decisões necessárias para demonstrar um fluxo seguro. Não é necessário implementar OAuth nem trocar a estratégia de autenticação escolhida.

## Sua tarefa

Prepare uma versão demonstrável da `petcare-api` com o seguinte fluxo:

1. Um tutor cria uma conta sem que a senha original seja armazenada.
2. O tutor realiza login e recebe a credencial definida na sua decisão técnica.
3. Uma requisição sem credencial válida recebe `401 Unauthorized`.
4. Um tutor tenta acessar um recurso pertencente a outro tutor e recebe `403 Forbidden` ou uma resposta equivalente definida pelo contrato da API.
5. Um ator com papel permitido executa a mesma operação com sucesso.
6. Tentativas excessivas de login recebem `429 Too Many Requests`.
7. Uma consulta ao banco usa parametrização ou API segura do ORM.
8. Um campo controlado pelo usuário é exibido como texto, sem execução de código.
9. A configuração de CORS aceita somente as origens necessárias ao projeto.
10. Se a autenticação usar cookie, uma operação de mutação possui proteção contra CSRF coerente com o cenário.

Use os endpoints e recursos que já existem no seu projeto. Não crie um novo domínio apenas para esta atividade.

## O que você vai produzir

- implementação do cadastro e login;
- mecanismo de autenticação escolhido;
- regras de autorização por papel e recurso;
- rate limiting no login;
- evidências das correções contra SQL injection e XSS;
- configuração de CORS;
- proteção contra CSRF, quando aplicável;
- `docs/security-review.md` ou `SECURITY.md` com decisões, checklist e riscos residuais.

## Demonstração mínima

Registre requests e responses, testes manuais ou outra evidência reproduzível para:

| Cenário | Resultado esperado |
| --- | --- |
| Cadastro válido | Usuário criado sem senha ou hash na resposta |
| Login válido | Credencial criada conforme a estratégia escolhida |
| Login inválido | Erro genérico, sem confirmar se a conta existe |
| Requisição sem autenticação | `401 Unauthorized` |
| Usuário sem permissão | `403 Forbidden` ou resposta equivalente documentada |
| Usuário autorizado | Operação concluída |
| Excesso de tentativas | `429 Too Many Requests` |

Não é necessário criar uma suíte automatizada neste momento. Esses cenários serão transformados em testes no módulo 13A.

## Critérios de conclusão

- Todas as exigências foram praticadas em exercícios anteriores.
- Senhas, hashes, tokens e identificadores de sessão não aparecem em logs ou responses indevidos.
- A estratégia de autenticação corresponde à decisão registrada.
- Autenticação e autorização estão separadas.
- As regras consideram papel e propriedade ou vínculo com o recurso.
- CORS, CSRF, XSS e SQL injection são tratados como problemas diferentes.
- Rate limiting corresponde ao risco do endpoint.
- A documentação explica controles aplicados, decisões e riscos que permanecem.
- A demonstração pode ser repetida por outra pessoa.

## Como este trabalho continuará

No módulo 13A, os cenários desta demonstração serão convertidos em testes unitários, de integração, contrato e, quando fizer sentido, end-to-end. O documento de segurança continuará como referência para escolher os casos de maior risco.

## Corrija Sua Atividade Com IA

```text
Cenário: Concluí a revisão de segurança de uma API Node.js/TypeScript. Implementei cadastro com hashing, login, uma estratégia de autenticação, autorização por papel e recurso, rate limiting, configuração de CORS e correções contra XSS e SQL injection. Quando uso cookie, também apliquei proteção contra CSRF.

Tarefa: Faça uma revisão pedagógica e técnica dos trechos de código, decisões e evidências abaixo.

Critérios de correção:
1. Senhas, hashes, tokens e sessões são tratados sem vazamento em logs ou responses?
2. A estratégia de autenticação está coerente com a decisão documentada?
3. 401 e 403 representam situações diferentes?
4. A autorização verifica papel e propriedade ou vínculo com o recurso?
5. CORS, CSRF, XSS e SQL injection receberam controles adequados e distintos?
6. O rate limiting corresponde ao risco do login?
7. As evidências demonstram os cenários de sucesso e rejeição?
8. O documento registra decisões, alternativas e riscos residuais?

Organize a resposta assim:
- acertos;
- riscos críticos;
- imprecisões ou lacunas;
- dicas de correção em ordem de prioridade.

Não reescreva toda a solução imediatamente. Dê dicas para que eu tente corrigir os problemas antes de apresentar código completo.

[COLE SUA RESPOSTA AQUI]
```

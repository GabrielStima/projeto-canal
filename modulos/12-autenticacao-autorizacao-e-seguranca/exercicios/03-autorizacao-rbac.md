# Exercício 03 — Autorização e RBAC

## Tarefa

Desenhe as regras de acesso para o PetCare OS baseado em perfis (Roles) de usuários. O PetCare OS possui `Tutor`, `Recepcionista`, `Clinico` e `Admin`.

Para os seguintes endpoints, descreva quem deve ter permissão de acesso e se existe alguma checagem de propriedade de recurso (ex: só o dono pode acessar).

1. `GET /api/prontuarios/:id`
2. `PATCH /api/prontuarios/:id/diagnostico`
3. `POST /api/agendamentos`
4. `DELETE /api/usuarios/:id`

## Requisitos

- Apenas usuários com sessão/token válido acessam as rotas.
- Pense em que ator pode visualizar o prontuário.
- Quem tem autoridade técnica para alterar o diagnóstico?
- Quem da clínica cria agendamentos e quem aprova?
- A deleção de usuários precisa ser extremamente controlada.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou criando um middleware/regra de Role Based Access Control (RBAC) para proteger a API do PetCare OS.

Tarefa: Mapeei as permissões necessárias para 4 rotas (Visualizar Prontuário, Editar Diagnóstico, Agendar e Excluir Usuário) envolvendo Tutor, Recepcionista, Clínico e Administrador.

Critérios de correção:
1. As permissões de acesso respeitam o Princípio do Menor Privilégio?
2. Houve esquecimento da regra de negócio de "pertencimento" (ex: o Tutor não deveria poder ler o prontuário de outros Tutores, só o do próprio pet)?
3. A rota de exclusão de usuário está bloqueada para todos exceto Admin?

[COLE SUA RESPOSTA AQUI]

Valide minha matriz de permissões. Aponte se alguma regra ficou branda demais ou inviabilizou a operação do usuário. Me dê dicas de como melhorar o RBAC antes de apresentar a matriz perfeita.
```

# Exercício 05 — Autorização por Papel e Recurso

## O que você já sabe

A API já consegue identificar um usuário autenticado. Isso ainda não garante que ele possa executar qualquer ação.

Nesta prática, você combinará papel, ação e propriedade do recurso. O frontend pode esconder opções, mas a decisão final deve acontecer no backend.

## Sua tarefa

Crie uma matriz de autorização para:

| Operação | Tutor | Recepcionista | Clínico | Administrador |
| --- | --- | --- | --- | --- |
| Consultar dados de um pet |  |  |  |  |
| Criar agendamento |  |  |  |  |
| Alterar diagnóstico |  |  |  |  |
| Aprovar orçamento |  |  |  |  |
| Excluir usuário |  |  |  |  |

Para cada permissão concedida, indique se ela depende de:

- papel;
- vínculo com a clínica;
- propriedade do pet ou orçamento;
- responsabilidade pelo atendimento;
- outra condição já existente no domínio.

Depois, implemente ou escreva pseudocódigo detalhado para:

1. `requireAuth`;
2. uma checagem por papel;
3. uma checagem por propriedade ou vínculo com o recurso.

Demonstre um caso `401 Unauthorized`, um `403 Forbidden` e um acesso permitido.

## O que você vai produzir

- matriz de autorização;
- middleware ou funções de autorização;
- três exemplos verificáveis de resposta;
- atualização do mapa de riscos.

## Critérios de conclusão

- `401` representa ausência ou invalidade de autenticação.
- `403` representa identidade conhecida sem permissão.
- O papel não substitui a checagem do recurso.
- Roles ou IDs enviados pelo cliente não são usados como fonte de confiança.
- A regra fica próxima da aplicação ou do domínio, sem depender apenas da interface.

## Como este trabalho continuará

A atividade final demonstrará que cada ator acessa somente os recursos permitidos. No módulo 13A, os casos `401`, `403` e acesso permitido serão transformados em testes.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei uma matriz de autorização para Tutor, Recepcionista, Clínico e Administrador. Também implementei autenticação, checagem por papel e checagem por propriedade ou vínculo com o recurso.

Tarefa: Revise minhas regras e os exemplos de 401, 403 e acesso permitido.

Critérios de correção:
1. As permissões seguem o princípio do menor privilégio?
2. As regras diferenciam papel de propriedade ou vínculo com o recurso?
3. 401 e 403 foram usados com significados corretos?
4. A API ignora roles e IDs não confiáveis enviados pelo cliente?
5. Existe alguma permissão ampla demais ou alguma restrição que inviabiliza o fluxo?

Primeiro destaque os acertos. Depois aponte imprecisões ou regras frágeis e dê dicas para eu corrigi-las. Não entregue uma matriz ideal completa antes da minha revisão.

[COLE SUA RESPOSTA AQUI]
```

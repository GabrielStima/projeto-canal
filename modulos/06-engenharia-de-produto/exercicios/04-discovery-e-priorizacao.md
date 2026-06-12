# Exercício 04 — Discovery e Priorização do PetCare OS

## Cenário

O time do PetCare OS tem três sprints para entregar valor real aos tutores e à clínica. Depois dos primeiros documentos de requisitos, histórias e experimentos, é hora de decidir o que entra nessa janela e o que fica para depois.

As funcionalidades em discussão são:

1. **Acompanhamento de status do atendimento** pelo portal.
2. **Aprovação de orçamento** pelo portal.
3. **Notificações por e-mail/SMS** quando o status mudar.
4. **Histórico de vacinas** do pet no portal.
5. **Relatório gerencial** de atendimentos para administradores.

## Tarefa

Você vai produzir um documento chamado `discovery-e-priorizacao.md` dentro do seu repositório do PetCare OS. Ele deve conter:

1. **Duas perguntas de discovery** que você faria para tutores ou recepcionistas para validar qual funcionalidade resolve a maior dor.
2. **Uma breve hipótese de problema** baseada nas respostas esperadas.
3. **Priorização com RICE** das cinco funcionalidades, usando estimativas honestas de reach, impact, confidence e effort.
4. **Classificação MoSCoW** para a versão que será entregue nas três sprints.
5. **Uma dívida técnica ou risco** que merece entrar no backlog, mesmo não sendo funcionalidade visível.

## Critérios de Aceite

- As perguntas de discovery buscam comportamento real, não opinião sobre a funcionalidade.
- A hipótese de problema separa dor da solução.
- Os números do RICE são justificados, mesmo que sejam estimativas.
- O MoSCoW define claramente o que entra na versão e o que fica de fora.
- A dívida técnica ou risco é explicada em termos de impacto futuro.

## Exemplo de Formato

```markdown
# Discovery e Priorização — Portal do Tutor

## Perguntas de discovery
1. "Quando você deixa o pet na clínica, o que você mais quer saber durante o dia?"
2. "Você já precisou autorizar um procedimento por telefone? Como foi essa experiência?"

## Hipótese de problema
A maior dor do tutor é a incerteza sobre o status do pet e a fricção para autorizar procedimentos. Aprovação de orçamento e acompanhamento de status são candidatas a entregar valor mais cedo do que histórico de vacinas ou relatórios gerenciais.

## Priorização RICE

| Funcionalidade | Reach | Impact | Confidence | Effort | RICE |
|---|---|---|---|---|---|
| Acompanhamento de status | 8 | 3 | 0.9 | 2 | 10.8 |
| Aprovação de orçamento | 7 | 3 | 0.8 | 3 | 5.6 |
| Notificações de status | 8 | 2 | 0.8 | 2 | 6.4 |
| Histórico de vacinas | 4 | 2 | 0.7 | 4 | 1.4 |
| Relatório gerencial | 3 | 2 | 0.6 | 4 | 0.9 |

## MoSCoW para 3 sprints
- **Must have:** Acompanhamento de status, Aprovação de orçamento.
- **Should have:** Notificações de status.
- **Could have:** Histórico de vacinas.
- **Won't have (nesta versão):** Relatório gerencial.

## Dívida técnica / risco
Definir a estrutura de autenticação do tutor antes de construir telas protegidas. Se isso for postergado, cada funcionalidade nova pode exigir retrabalho de segurança.
```

## Corrija Sua Atividade Com IA

```text
Você é um revisor pedagógico de engenharia de produto.

Cenário: estou estudando product discovery e priorização em uma formação fullstack JavaScript/TypeScript. O exercício pede para escrever um documento chamado `discovery-e-priorizacao.md` para decidir o que construir primeiro no portal do tutor de uma plataforma veterinária.

Tarefa: revise o documento que eu produzi. Ele deve conter:
1. Duas perguntas de discovery para tutores ou recepcionistas.
2. Uma hipótese de problema.
3. Priorização RICE de cinco funcionalidades.
4. Classificação MoSCoW para uma versão de três sprints.
5. Uma dívida técnica ou risco para o backlog.

Critérios de correção:
- Perguntas de discovery devem buscar comportamento real, não opinião sobre funcionalidade.
- A hipótese deve separar dor de solução.
- RICE deve ter justificativa para os números, mesmo sendo estimativas.
- MoSCoW deve deixar claro o que entra e o que fica de fora.
- A dívida técnica ou risco deve ser explicada pelo impacto futuro.

[COLE SUA RESPOSTA AQUI]

Instruções de correção:
- Destaque os acertos do documento.
- Aponte perguntas que induzem respostas, hipóteses que já são soluções, RICE sem justificativa ou MoSCoW que não decide nada.
- Ofereça dicas específicas de melhoria antes de apresentar uma versão alternativa completa.
- Não entregue uma resposta pronta sem antes comentar o que está bom e o que pode evoluir.
```

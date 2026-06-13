# Atividade Final do Módulo

## O que você já tem

Um monólito Modular testado, coeso (N5 de Design) operando a clínica perfeitamente de forma síncrona.

## A Tarefa

Nesta atividade, você aplicará o **Marco Arquitetural N6**.

1. Crie e registre uma **ADR (Architecture Decision Record)** na raiz do seu projeto ou repositório.
2. Nela, documente a extração da funcionalidade mais instável (Ex: envio de laudos longos, notificações de vacina) do fluxo síncrono.
3. Arquitete e, de preferência, codifique a injeção de uma Fila de Mensagens (`BullMQ` no Node ou conexão simples no `RabbitMQ`).
4. Seu controller principal fará: `POST /api/vacinas/lote -> enviarParaFila(lote) -> Retorna 202 Accepted`.
5. Um arquivo separado (Worker) consumirá a fila e executará o script pesado.

## O que você vai produzir

- O documento `docs/ADR-001-uso-de-filas.md`.
- Um arquivo Controller focado no Domínio que publica mensagens.
- Um arquivo `worker.ts` simulando a infraestrutura que não trava a clínica.

## Corrija Sua Atividade Com IA

```text
Cenário: Finalização do Marco N6 Arquitetural e Event-Driven.

Tarefa: Eu escrevi minha ADR e configurei um Worker. Segue o texto da ADR:
[COLE AQUI SUA ADR]

Critérios de correção:
1. A ADR documenta bem o Contexto, a Decisão e as Consequências?
2. A decisão resolve o bloqueio da clínica delegando à mensageria?

Faça o papel de Staff Engineer: Critique construtivamente minha ADR como se fôssemos implementá-la em 1 semana no PetCare OS.
```

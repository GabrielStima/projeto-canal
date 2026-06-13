# Exercício 05 — Worker e Medição

Esta atividade é recomendada. Ela ensina a distinguir trabalho de CPU, I/O e gargalo de banco sem transformar workers em solução padrão.

## O Que Você Já Possui

A API possui endpoints, banco e logs. Você estudou event loop, worker threads e profiling.

## Sua Tarefa

Crie uma tarefa de laboratório que gere um resumo estatístico a partir de um conjunto grande de dados fictícios. A tarefa deve usar CPU de forma perceptível, sem acessar dados clínicos reais.

Execute três etapas:

1. rode o cálculo na thread principal e registre duração;
2. durante o cálculo, faça chamadas ao `/health` e registre o atraso;
3. mova o cálculo para `node:worker_threads` e repita a medição.

Registre em `docs/worker-e-performance.md`:

- hipótese inicial;
- tamanho da entrada;
- duração observada;
- impacto no health check;
- custo de criar e comunicar com o worker;
- conclusão sobre quando o worker ajudou;
- um exemplo de tarefa I/O-bound que não ganharia o mesmo benefício.

Não transforme esse laboratório em endpoint obrigatório do produto.

## Critérios de Conclusão

- existe uma medição antes e depois;
- o cálculo é CPU-bound;
- o health check evidencia o bloqueio da thread principal;
- o worker trata mensagem, resultado e erro;
- a conclusão reconhece custo de comunicação;
- operações comuns de banco não são enviadas para worker;
- o documento não generaliza um único teste local como verdade de produção.

Guarde o relatório. Ele será retomado no módulo de observabilidade e performance.

## Corrija Sua Atividade Com IA

```text
Estou realizando um laboratório de worker threads e profiling em uma API Node.js.

Comparei:
- um cálculo CPU-bound na thread principal;
- o impacto desse cálculo em chamadas ao /health;
- o mesmo cálculo com node:worker_threads;
- duração, atraso, comunicação e erros;
- uma tarefa I/O-bound que não precisa de worker.

Critérios de correção:
1. deve existir medição antes e depois;
2. a tarefa precisa ser realmente CPU-bound;
3. o impacto no event loop deve ser observável;
4. o worker deve tratar resultado e erro;
5. a análise deve incluir custo de criação e transferência de dados;
6. consultas comuns ao banco não devem ser classificadas como trabalho de worker;
7. conclusões locais não podem ser apresentadas como benchmark de produção.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões na medição ou interpretação;
3. ofereça dicas antes de propor código completo;
4. permita que eu ajuste o experimento;
5. só apresente uma solução completa se eu solicitar depois.

[COLE SUA RESPOSTA AQUI]
```

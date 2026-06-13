# Exercício 13 — Criando seu Juiz

## Tarefa

Sua API manda RAG. E como eu sei se meu Prompt RAG foi bom pro cliente e não sugeriu Remédios Proibidos? Se a cada milisegundo a frase sai diferente? Descreva num fluxo prático de MLOps como a arquitetura Evals automatiza um (LLM-as-a-judge): A requisição cruza a API, nós passamos o JSON do Agente num "LLM Severo e Estrito" avaliador local. Qual o System Prompt Exato que você daria pro LLM Julgador usar como Metrônomo Ético para que ele devolva no seu teste unitário CI/CD de Git (Pass / Fail)? (Crie a base do seu LLM Julgador).

## Corrija Sua Atividade Com IA

```text
Cenário: Evals, Automated Feedback Loop e Unit-Testing de Semântica Probabilística (RAG-Evals).

Tarefa: Meu framework simples e System Prompt Rígido que usarei para avaliar outras IAs sem intervenção humana de forma barata (LLM as a judge framework):
[COLE AQUI]

Critérios de correção:
1. Eu gerei um prompt do tipo: "Você é um Juiz rigoroso da ANS. Retorne apenas JSON com `{"passou": false, "motivo": "Prescreveu remédio"}`"?
2. Provei que essa chamada paralela assíncrona do "Bot Julgador" salva 5.000h de Q.A. Testing Humano rodando automações cruéis em lote sobre históricos diários salvos no CloudWatch/Datadog?
```

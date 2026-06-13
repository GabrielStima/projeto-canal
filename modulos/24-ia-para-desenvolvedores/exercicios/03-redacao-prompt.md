# Exercício 03 — Redação Antes do Prompt

## Tarefa

A Petcare quer treinar um Agente com os PDFs de Recibos Médicos para ajudar pacientes no chat. Os recibos tem Nomes, CPFs, e Doenças Crônicas dos tutores humanos em texto cru e solto. Como um Arquitetura Corporativa de Data Pipeline no Back-end processa isso (Data Masking via NER - Named Entity Recognition ou Regex) antes de sequer armazenar a string nas planilhas vetorizadas que o LLM consome? Evidencie a catástrofe do "Opt-in Training".

## Corrija Sua Atividade Com IA

```text
Cenário: Privacidade, GDPR/LGPD compliance x Modelos de Fundamentos (Foundation Models).

Tarefa: Segue a arquitetura da minha barreira defensiva antes da conversão de strings:
[COLE AQUI]

Critérios de correção:
1. Expliquei que o LLM engole o CPF sem perguntar e numa possível injeção futura vaza abertamente "Paciente Gabriel Doença Tal" pra todos do ChatBot?
2. Inseri funções Node de Substituição de Tokens (Ex: Trocar o nome literal por [USUÁRIO_X]) permitindo o Modelo extrair a semântica de negócio sem nunca ler a PI (Personal Identification)?
```

# Atividade Final do Módulo

## O que você já tem

Uma API de PetCare OS conectada ao banco, com regras de negócio, contratos e suíte de testes passando verde no GitHub Actions. Porém, ela ainda é uma "caixa preta" quando executa.

## A Tarefa

Nesta atividade, você aplicará o **Marco Operacional N4**.

Siga as etapas práticas na sua API local:
1. **Instrumentação Básica:** Crie um Middleware que envolva todas as requisições, calculando os milissegundos desde a entrada até a saída da rota.
2. **Logging Estruturado:** Instale e configure o `Pino.js` (ou `Winston`). Use a lib de uuid ou `crypto.randomUUID()` para injetar um `requestId` ou `traceId` nos headers, passando esse valor para todo objeto logado da requisição.
3. **Carga e Saturação:** Baixe o **K6** (k6.io). Crie o script `loadtest.js` que bate em `GET /api/pets` simulando 50 usuários simultâneos por 30s. Observe o output, verifique sua taxa de R/s e se houve erros HTTP.
4. **Profiling (Opcional Prático):** Rode sua API Node usando `--inspect`. Vá na aba Memory do Chrome ou aba Performance e dispare o script do K6 para visualizar o Flamechart sob estresse.

## O que você vai produzir

- Configuração de Logs na inicialização do servidor.
- Um arquivo `loadtest.js` na raiz ou subpasta `scripts/`.
- Logs printados num JSON organizado no seu terminal quando navega pelo app.

## Corrija Sua Atividade Com IA

```text
Cenário: Finalização do Marco N4 Operacional no PetCare OS.

Tarefa: Eu implementei Instrumentação simples de tempo, injeção de TraceID (Correlação), log estruturado JSON e criei meu script K6. Segue o output gerado por um Log de erro simulado e as métricas reportadas no terminal pelo K6:

[COLE SEU LOG JSON E O SUMÁRIO DO K6 AQUI]

Critérios de correção:
1. Avalie meu Log: Ele contem as chaves essenciais para ser exportado a um indexador?
2. Avalie meu K6 Report: O número de requisições sustentadas foi bom? Há presença alarmante de Requests Quebradas ou Latências altas de P95?
3. O que falta (num ambiente Cloud real) para que essas duas métricas andem de mãos dadas em um painel do grafana?

Me traga recomendações de nível Pleno/Senior sobre o que fazer agora que tenho "olhos de águia" no backend.
```

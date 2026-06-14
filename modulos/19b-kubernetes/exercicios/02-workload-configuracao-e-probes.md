# Exercício 02 — Workload, Configuração e Probes

## O que você já tem

Você definiu namespace, imagem e escopo do laboratório.

## Tarefa

Crie manifestos para:

- Namespace;
- Deployment;
- ConfigMap;
- referência a Secret sem valor real versionado.

O Deployment deve incluir:

1. labels consistentes entre selector e template;
2. imagem com tag rastreável;
3. porta do container;
4. configuração não sensível via ConfigMap;
5. segredo referenciado sem texto real no Git;
6. `startupProbe`, se a inicialização puder ser lenta;
7. `readinessProbe` para controlar recebimento de tráfego;
8. `livenessProbe` apenas para detectar travamento recuperável;
9. estratégia inicial de réplicas;
10. anotações ou documentação das decisões.

Lembre que valores em `Secret` são codificados em base64, não criptografados automaticamente.

## O que você vai produzir

O workload declarativo que será conectado e protegido nos próximos exercícios.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei Namespace, Deployment, ConfigMap e referências a Secret para uma API. Usei labels consistentes, imagem rastreável, configuração externa e probes de startup, readiness e liveness.

Tarefa: Revise meus manifestos de workload e configuração.

Critérios de correção:
1. Selector e labels do template correspondem?
2. A imagem evita latest e identifica a versão implantada?
3. ConfigMap e Secret separam dados comuns de dados sensíveis?
4. Nenhum segredo real foi versionado e base64 não foi tratado como criptografia?
5. Readiness controla tráfego sem reiniciar o processo?
6. Liveness não é agressiva a ponto de criar reinícios em cascata?
7. Startup probe protege aplicações com inicialização lenta, quando necessária?

Comece pelos acertos. Depois indique imprecisões e ofereça dicas antes de escrever manifestos completos.

[COLE SUA RESPOSTA AQUI]
```

# Exercício 04 — Stack Compose, Dados e Rede

## O que você já tem

Você possui uma imagem da API com contrato de execução definido.

## Tarefa

Crie `compose.yaml` para um ambiente local com API, banco e, se o fluxo assíncrono exigir, fila.

Inclua:

1. build ou imagem da API;
2. variáveis sem valores sensíveis versionados;
3. volume nomeado para dados persistentes;
4. rede interna entre serviços;
5. somente as portas necessárias expostas ao host;
6. healthcheck do banco e da API;
7. dependência por condição de saúde quando isso for útil;
8. procedimento de migrations e dados iniciais;
9. logs acessíveis fora de shell interativo;
10. comandos de inicialização, parada e limpeza segura.

Explique por que o banco local em container não implica manter o banco de produção da mesma forma.

## O que você vai produzir

Uma stack local reproduzível, usada como base do desafio de containerização.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei um compose.yaml para API, banco e fila. Usei volume nomeado, rede interna, exposição mínima de portas, healthchecks, configuração externa, migrations e comandos operacionais.

Tarefa: Revise meu Compose e minha documentação.

Critérios de correção:
1. Dados persistentes sobrevivem à recriação dos containers?
2. Serviços internos evitam exposição desnecessária ao host?
3. Healthchecks verificam disponibilidade real e não apenas processo ativo?
4. Dependências de inicialização não substituem retries da aplicação?
5. Segredos não foram incluídos no arquivo versionado?
6. Migrations e limpeza de volumes possuem procedimentos explícitos?
7. Desenvolvimento local e banco de produção foram tratados como contextos diferentes?

Comece pelos acertos. Depois indique imprecisões e dê dicas antes de apresentar uma configuração completa.

[COLE SUA RESPOSTA AQUI]
```

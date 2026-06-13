# Atividade Final de Bloco: Dockerização Prática

## O que você já tem

Sua API puramente dependente de instalação massiva e demorada de binários de sistema (Node, Postgres). Ela exige manuais para rodar.

## A Tarefa

Este é o **Marco Tático**. Transcenda a caixa local pro Docker.

1. Selecione as imagens certas: Baseadas em `alpine` por segurança mínima (tamanho < 50mb) no Dockerhub.
2. Formate e otimize o Cache das Camadas (COPY apenas do `package.json` -> npm install -> COPY root /app da pasta).
3. Efetue um arquivo de composição Orquestradora Local `docker-compose.yml` e alinhe o ambiente com a dependência vital `depends_on`, ativando volumes temporários efêmeros da RAM do Linux se puder.
4. Faça o laboratório de terminal `docker compose up -d` blindar seus esforços.

## O que você vai produzir

- Uma virtualização imutável rodando um laboratório inteiro de banco relacional pesado num notebook de entrada local que poderá ser levada no caminhão pra internet a qualquer hora e vai ter 100% da garantia que não quebrará em Produção.

## Corrija Sua Atividade Com IA

```text
Cenário: Entrega Tática Dockerfile + Compose e Caching Inception.

Tarefa: Mostro o arquivo e defendo o meu Caching e meu Rootless:
[COLE AQUI O DOCKERFILE]


[COLE SUA RESPOSTA AQUI]
Critérios de correção:
1. Meu Dockerfile rodou o famigerado erro crasso de copiar TUDO (`COPY . .`) antes do Download enorme do NPM sem respeitar camadas?
2. Executei os processos como superusuários absolutos do hospedeiro, falhando miseravelmente na parte de `USER node` por esquecimento ou imperícia?

Aponte agressivamente os vetores de falhas estruturais, aponte um exploit possível de escalação de privilégio ou parabenize meu trabalho.
```

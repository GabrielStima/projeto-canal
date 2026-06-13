# Exercício 08 — Bind Mounts vs Volumes Nativos

## Tarefa

No desenvolvimento local, mapear `v /c/minha_pasta_windows:/app/src` num contêiner é vida, mas em produção um Arquivo `docker-compose.yaml` com mapeamentos atrelados a caminhos enrijecidos do Sistema Operacional Físico (`Bind Mounts`) geram pesadelos gigantescos. Defenda o "Volume Nativo do Docker Engine" (Onde não sabemos onde a pasta C reside, o docker guarda).

## Corrija Sua Atividade Com IA

```text
Cenário: Persistência Eficaz de Discos Locais vs Abstratos.

Tarefa: Minha comparação e ataque ao "Bind Mount em Prod":
[COLE AQUI]

Critérios de correção:
1. Ataquei o problema de portabilidade (ex: Tentar rodar num Windows de Produção depois do Linux) quando uso atrelamentos rústicos do SO?
2. Provei que a Engine abstrata não requer mexer na árvore de root permissions com usuários pesados de Root Linux?
```

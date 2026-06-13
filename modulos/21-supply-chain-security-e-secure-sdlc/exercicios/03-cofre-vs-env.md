# Exercício 03 — A Falsidade do .env

## Tarefa

Uma empresa guarda todas as credenciais ultra-secretas do BD Produtivo num arquivo solto `.env` no disco do Ubuntu e acha que está segura ("Pois o Github ignora no .gitignore!"). Se um atacante descobre um exploit no seu App (uma página estática de download de boletos mal configurada) e acha um vetor grave de "LFI/Path Traversal", por que esse `.env` é o maior tesouro do mundo, e como um *Secrets Manager Corporativo* anularia esse pânico?

## Corrija Sua Atividade Com IA

```text
Cenário: Vazamentos Nativos de Arquivos e Gestão de Segredos via Vault/Cloud.

Tarefa: Aqui está a diferença de expor o '.env' para o uso inteligente de Injeção em Memória/Cofres Secretos:
[COLE AQUI]

Critérios de correção:
1. Expliquei que no Path Traversal o atacante dá um `GET /download?file=../../../../.env` e puxa o arquivo em texto claro direto pra casa dele?
2. Defendi o Vault evidenciando que ele não guarda arquivos locais no servidor, forçando a API a pegar a credencial temporária em tempo-de-execução, não deixando rastros no disco do sistema exposto?
```

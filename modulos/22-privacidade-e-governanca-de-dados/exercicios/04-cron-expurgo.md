# Exercício 04 — Cron de Expurgo

## Tarefa

É fácil programar um `CronJob` no Node.js rodando um script noturno no PostgreSQL que aplica um `DELETE FROM compras WHERE data < '2019'`. Mas, se a LGPD diz "Excluir definitivamente" quando o prazo acaba, como a sua empresa lida e cumpre a lei mediante aos Arquivos Massivos Compactados em Fita de **BACKUP** de anos passados (S3 Glacier/Dumps)?

## Corrija Sua Atividade Com IA

```text
Cenário: Purging em Cold Storage e a Dissonância do Disaster Recovery vs Direito a Deleção.

Tarefa: Minha resposta sobre a complexidade infinita de Purgas em Backups (Right to be Forgotten):
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Expliquei a dor técnica de tentar Descompactar `pg_dumps` em lote, limpar linha a linha e Re-Compactar (Algo computacionalmente Inviável)?
2. Refleti sobre os Adendos das Agências Governamentais (ANPD) que normalmente liberam backups da deleção bruta desde que o ciclo natural do backup se sobreponha (Rolling overwrite)?
```

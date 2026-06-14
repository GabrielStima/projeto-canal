# Exercício 01 — Escopo e Estado Desejado

## O que você já tem

No módulo 17, você produziu `docs/arquitetura-cloud.md` e listou os componentes candidatos a Infrastructure as Code.

## Tarefa

Crie `infra/README.md` e classifique cada componente como:

- gerenciado pelo Terraform;
- consultado por data source;
- configurado por outro processo;
- mantido fora de IaC, com justificativa.

Depois registre:

1. estado desejado de cada recurso gerenciado;
2. dependências principais;
3. benefício esperado de repetibilidade e revisão;
4. riscos de automatizar a mudança;
5. recursos que não podem ser destruídos sem proteção;
6. critério para considerar o ambiente reproduzível.

Compare brevemente o fluxo declarativo planejado com uma sequência de comandos imperativos.

## O que você vai produzir

Um plano de conversão que evita tentar gerenciar toda a infraestrutura de uma vez.

## Corrija Sua Atividade Com IA

```text
Cenário: Tenho uma arquitetura cloud documentada e classifiquei seus componentes entre recursos gerenciados pelo Terraform, data sources, outros processos e itens fora de IaC. Também defini estado desejado, dependências, riscos e critérios de reprodução.

Tarefa: Avalie meu plano de conversão para Infrastructure as Code.

Critérios de correção:
1. O escopo inicial é pequeno o bastante para ser revisado e testado?
2. Recursos existentes foram diferenciados de recursos que o Terraform criará?
3. Estado desejado e dependências estão claros?
4. Recursos com risco de perda possuem proteção planejada?
5. A comparação entre declarativo e imperativo está correta?
6. O critério de reprodução pode ser verificado?

Primeiro destaque meus acertos. Depois aponte imprecisões e riscos. Ofereça dicas antes de apresentar um plano completo.

[COLE SUA RESPOSTA AQUI]
```

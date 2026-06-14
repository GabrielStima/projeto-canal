# Exercício 05 — Módulos e Ambientes

## O que você já tem

Seu laboratório local funciona e você definiu como o state compartilhado seria protegido.

## Tarefa

Refatore `infra/lab`:

1. extraia um módulo local apenas para uma responsabilidade repetível;
2. declare entradas e saídas mínimas;
3. fixe versões quando houver módulos ou providers externos;
4. crie configurações raiz separadas para `dev` e `prod`;
5. use states separados;
6. altere capacidade ou nomes por ambiente sem duplicar toda a configuração;
7. documente por que workspaces não serão a única barreira entre ambientes críticos;
8. registre um caso efêmero em que workspace poderia ser útil.

Evite criar módulos genéricos para recursos usados uma única vez.

## O que você vai produzir

Uma estrutura reutilizável com limites claros entre módulo, configuração raiz e ambiente.

## Corrija Sua Atividade Com IA

```text
Cenário: Refatorei um laboratório Terraform criando um módulo local e configurações raiz separadas para dev e prod. Defini inputs, outputs, versões, states separados e uma decisão sobre workspaces.

Tarefa: Revise minha estrutura de módulos e ambientes.

Critérios de correção:
1. O módulo representa uma responsabilidade coesa e reutilizável?
2. Inputs e outputs são mínimos e compreensíveis?
3. A configuração raiz compõe módulos sem esconder decisões essenciais?
4. Dev e prod possuem state e parâmetros separados?
5. A estrutura reduz duplicação sem criar abstração prematura?
6. O uso ou não uso de workspaces está justificado pelo nível de isolamento?
7. Dependências externas possuem versões controladas?

Primeiro destaque os acertos. Depois aponte imprecisões e dê dicas antes de propor uma estrutura completa.

[COLE SUA RESPOSTA AQUI]
```

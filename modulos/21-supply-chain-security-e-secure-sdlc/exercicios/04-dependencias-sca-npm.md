# Exercício 04 — Dependências, SCA e npm

## O Que Você Já Possui

O pipeline já possui etapas e gates definidos. Agora você precisa tratar o código de terceiros que entra no build.

## A Tarefa

Use `package.json`, o lockfile e a árvore de dependências do projeto como base para uma política de dependências:

1. diferencie dependências diretas, transitivas e de desenvolvimento;
2. escolha três dependências e registre finalidade, origem e responsável pela decisão de uso;
3. explique como o lockfile contribui para builds reproduzíveis;
4. defina como avaliar severidade, explorabilidade e alcance de um alerta de SCA;
5. liste opções de resposta: atualizar, substituir, mitigar, aceitar temporariamente ou remover;
6. estabeleça regras para scripts de instalação e novas dependências;
7. defina o que bloqueia o pipeline e como uma exceção expira.

Registre a política em `docs/seguranca-cadeia.md`. Você pode usar a saída de uma ferramenta já disponível, mas a avaliação não deve se limitar ao número de alertas.

## O Que Você Vai Produzir

Uma política de dependências que combina inventário, análise de risco e decisões rastreáveis.

Ela será conectada ao SBOM e à origem do artefato no próximo exercício.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei uma política para dependências npm e achados de SCA do PetCare OS.

Tarefa: Revise meu inventário, critérios de risco, opções de resposta, gates e exceções.

Critérios de correção:
1. Dependências diretas, transitivas e de desenvolvimento são tratadas adequadamente.
2. O lockfile e os scripts de instalação entram na análise.
3. Severidade não é usada sozinha: explorabilidade e alcance também são considerados.
4. A política oferece respostas além de atualizar automaticamente.
5. Gates e exceções possuem critérios, responsável e prazo.
6. Novas dependências exigem justificativa proporcional ao risco.

Primeiro destaque meus acertos. Depois aponte decisões frágeis e ofereça dicas. Só apresente uma política completa depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

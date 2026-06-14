# Exercício 03 — Pipeline e Quality Gates

## O Que Você Já Possui

Você tem o pipeline criado anteriormente, um mapa de ameaças e uma matriz de identidades e permissões.

## A Tarefa

Revise o workflow do projeto e documente ou implemente uma proposta segura:

1. diferencie eventos de pull request, merge e publicação;
2. identifique quais jobs podem executar código não confiável;
3. mantenha secrets fora de jobs que validam contribuições externas;
4. declare permissões mínimas para cada job;
5. defina gates para lint, testes e SAST;
6. estabeleça quais achados bloqueiam o merge;
7. crie um processo de exceção com justificativa, responsável e prazo;
8. registre evidências que o pipeline deve conservar.

Acrescente o desenho e as decisões a `docs/seguranca-cadeia.md`. Caso altere o workflow, use apenas recursos que já tenham sido ensinados e mantenha a explicação junto ao documento.

## O Que Você Vai Produzir

Um pipeline segmentado por nível de confiança, com permissões explícitas, gates e tratamento de exceções.

Nos exercícios seguintes, você adicionará controles para dependências e artefatos.

## Corrija Sua Atividade Com IA

```text
Cenário: Revisei o pipeline do PetCare OS com base no mapa de ameaças e na matriz de acessos.

Tarefa: Avalie meus eventos, jobs, permissões, uso de secrets, quality gates e processo de exceção.

Critérios de correção:
1. Código não confiável não recebe credenciais privilegiadas.
2. Jobs e eventos possuem responsabilidades claras.
3. As permissões são mínimas e específicas.
4. Os gates possuem critérios objetivos de bloqueio.
5. Falsos positivos e exceções possuem revisão, responsável e validade.
6. Cada controle está ligado a uma ameaça mapeada.

Primeiro destaque meus acertos. Depois aponte riscos ou ambiguidades e ofereça dicas. Só apresente um pipeline completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

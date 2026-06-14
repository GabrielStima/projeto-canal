# Exercício 04 — RAG e Qualidade da Recuperação

## O Que Você Já Possui

O caso de uso possui limites e dados permitidos. Você estudou embeddings, busca vetorial e o fluxo de RAG.

## A Tarefa

Escolha de cinco a dez documentos públicos ou fictícios relacionados ao escopo. Projete e, se possível, implemente uma recuperação pequena.

Registre em `docs/sistema-ia.md`:

1. origem, versão, licença e responsável pelos documentos;
2. critérios de inclusão e exclusão;
3. limpeza e chunking, com sobreposição justificada;
4. metadados para fonte, versão, tema e permissão;
5. estratégia de busca e quantidade de trechos;
6. filtros de acesso antes da recuperação;
7. montagem do contexto e limite de tokens;
8. citações apresentadas ao usuário;
9. tratamento quando não houver fonte suficiente;
10. defesa contra instruções maliciosas dentro dos documentos;
11. cinco consultas de teste com trechos esperados;
12. métricas separadas para recuperação e geração.

Não presuma que RAG elimina alucinações. Se uma busca textual simples resolver o corpus, registre essa alternativa.

## O Que Você Vai Produzir

Um pipeline de recuperação verificável, independente de banco vetorial ou provedor específico.

Esse pipeline será submetido aos evals e guardrails do próximo exercício.

## Corrija Sua Atividade Com IA

```text
Cenário: Projetei um RAG pequeno para o assistente do PetCare OS usando documentos públicos ou fictícios.

Tarefa: Revise corpus, chunking, busca, permissões, citações e testes de recuperação.

Critérios de correção:
1. As fontes possuem origem, versão, permissão e responsável.
2. Chunking e metadados preservam contexto útil.
3. A busca respeita filtros de acesso antes de montar o prompt.
4. A resposta cita fontes e recusa quando a evidência é insuficiente.
5. Documentos recuperados são tratados como dados, não como instruções.
6. Recuperação e geração possuem avaliações separadas.
7. A solução é proporcional ao tamanho e à necessidade do corpus.

Primeiro destaque meus acertos. Depois aponte riscos de recuperação ou complexidade prematura e ofereça dicas. Só apresente um pipeline completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

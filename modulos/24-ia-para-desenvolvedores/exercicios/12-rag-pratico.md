# Exercício 12 — A Prática de RAG

## Tarefa

(RAG) - O Arquiteto tentou botar o livro "Manejo Cirúrgico de Gatos Vol.3" com 800 páginas dentro do RAG. Ele mandou o PDF Inteiro de uma vez pro Pinecone (Gerou 1 vetor só para o livro todo de 800 pg). O médico busca no chat "Dose de Anestesia na Gengiva", o Pinecone acha o PDF gigante e injeta as 800 páginas no Prompt do GPT como contexto. O GPT trava por limite de Token Window e dá Erro de Custo! Descreva o papel inegociável do *Text Chunking* (Picar em Chunks/Blocos de 500 palavras cada) antes de Embebedar (Embeddings) visando injetar estritamente Cirurgia apenas no contexto Limitado da resposta.

## Corrija Sua Atividade Com IA

```text
Cenário: O Calcanhar de Aquiles do RAG Básico: Context Window Flood & Chunking Strategies.

Tarefa: Minha resposta atacando o Desperdício de Tokens e a Recuperação Inútil (Noise) de mandar PDFs inteiros:
[COLE SUA RESPOSTA AQUI]

Critérios de correção:
1. Demonstrei que ao quebrar em parágrafos semânticos, o VectorDB devolveria APENAS os 3 parágrafos específicos que falam "Gengiva/Anestesia" para a API do ChatGpt, mandando um contexto minúsculo de 1000 tokens perfeitamente focado?
2. Apontei que a IA perde o foco na resposta e se perde nas informações (Lost in the Middle) quando o dev afoga o prompt injetando manuais não-picados?
```

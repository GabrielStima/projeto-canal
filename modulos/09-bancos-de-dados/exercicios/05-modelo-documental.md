# Exercício 05 — Modelo Documental para Auditoria

Esta atividade é recomendada. Ela serve para comparar modelos sem transformar MongoDB em requisito do PetCare OS.

## O Que Você Já Sabe

Você já possui um modelo relacional para os dados principais. Também estudou documentos, collections, embedding, referencing, operadores de query e aggregation no MongoDB.

## Sua Tarefa

Considere um registro de auditoria que informa:

- qual ação ocorreu;
- quando ocorreu;
- qual usuário da equipe realizou a ação;
- qual entidade foi afetada;
- quais campos mudaram;
- um resumo dos valores anteriores e novos.

Crie `database/modelo-auditoria-documental.md` com:

1. um exemplo de documento;
2. decisão sobre quais dados embutir e quais apenas referenciar;
3. três filtros MongoDB;
4. um pipeline que conte ações por tipo e por dia;
5. riscos de crescimento do documento;
6. comparação com uma tabela relacional de auditoria;
7. uma conclusão que aceite SQL, MongoDB ou outra solução conforme os requisitos.

Não implemente um segundo banco na aplicação. O objetivo é exercitar modelagem e comparação.

## Critérios de Conclusão

- o documento possui formato consistente;
- dados que mudam com frequência não são copiados sem justificativa;
- filtros respondem perguntas de auditoria;
- o pipeline possui etapas em ordem compreensível;
- a conclusão não escolhe tecnologia apenas por flexibilidade;
- segurança e retenção de dados são mencionadas.

Esse estudo será usado na decisão final sobre SQL e NoSQL.

## Corrija Sua Atividade Com IA

```text
Estou comparando uma alternativa documental para registros de auditoria do PetCare OS.

Cada registro deve informar ação, data, usuário da equipe, entidade afetada, campos alterados e resumo dos valores anteriores e novos.

Minha entrega contém:
- um documento de exemplo;
- decisões de embedding e referencing;
- três filtros MongoDB;
- um pipeline para contar ações por tipo e por dia;
- riscos de crescimento;
- comparação com uma tabela relacional;
- conclusão sem assumir que MongoDB é obrigatório.

Critérios de correção:
1. o documento deve ter formato consistente;
2. embedding e referencing devem ser justificados pelos padrões de acesso;
3. filtros devem usar operadores coerentes;
4. o pipeline deve filtrar, agrupar e projetar em ordem compreensível;
5. dados sensíveis, retenção e permissões devem ser considerados;
6. a comparação deve discutir trade-offs, não declarar vencedor universal;
7. a proposta não deve exigir um segundo banco sem necessidade comprovada.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões técnicas ou decisões sem justificativa;
3. dê dicas antes de sugerir uma estrutura completa;
4. permita que eu revise minha resposta;
5. mostre uma solução completa apenas se eu pedir depois.

[COLE SUA RESPOSTA AQUI]
```

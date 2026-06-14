# Exercício 01 — Mapa de Riscos da API

## O que você já sabe

A `petcare-api` já possui contratos, erros padronizados e endpoints para os fluxos principais do PetCare OS. Neste módulo, você começará a protegê-la sem reescrever o projeto.

Esta atividade é obrigatória para continuidade. O mapa produzido aqui será atualizado nos próximos exercícios.

## Sua tarefa

Escolha quatro endpoints que já existem na sua API. Use ao menos:

- uma consulta de dados;
- uma operação que altera dados;
- uma operação financeira ou de aprovação;
- uma operação administrativa.

Para cada endpoint, registre:

1. quais dados ou ações precisam ser protegidos;
2. quem deveria acessar;
3. como o endpoint poderia ser usado de forma indevida;
4. qual controle inicial reduziria o risco;
5. qual seria o impacto de uma falha.

Use uma tabela como esta:

| Endpoint | Dado ou ação protegida | Ator permitido | Risco | Controle inicial | Impacto |
| --- | --- | --- | --- | --- | --- |
| `PATCH /api/...` |  |  |  |  |  |

Não tente resolver tudo agora. O objetivo é identificar riscos antes de escolher ferramentas.

## O que você vai produzir

Um arquivo `docs/security-review.md` ou uma seção equivalente na documentação do projeto, com:

- os quatro endpoints analisados;
- riscos descritos em linguagem concreta;
- controles iniciais;
- duas prioridades justificadas para o restante do módulo.

## Critérios de conclusão

- Autenticação e autorização não aparecem como sinônimos.
- Pelo menos um risco envolve acesso a recurso de outra pessoa.
- Pelo menos um risco envolve entrada controlada pelo cliente.
- Os controles propostos correspondem ao risco descrito.
- As prioridades consideram probabilidade e impacto, não apenas preferência técnica.

## Como este trabalho continuará

Nos próximos exercícios, você adicionará ao mapa as decisões de autenticação, autorização, proteção de entrada e limitação de abuso. Ele será usado como checklist na atividade final.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou revisando a segurança de uma API Node.js/TypeScript de uma plataforma veterinária. Selecionei quatro endpoints existentes e registrei dados protegidos, atores permitidos, riscos, controles e impactos.

Tarefa: Avalie se meu mapa de riscos diferencia identidade, permissão, entrada maliciosa e abuso. Verifique também se as prioridades são proporcionais ao impacto.

Critérios de correção:
1. Cada risco descreve uma forma concreta de uso indevido?
2. Os controles propostos realmente reduzem os riscos correspondentes?
3. Existe ao menos uma análise de autorização por propriedade do recurso?
4. Existe ao menos uma análise de entrada controlada pelo cliente?
5. As duas prioridades foram justificadas por risco, e não por preferência de ferramenta?

Antes de sugerir uma versão melhor:
- destaque os acertos;
- aponte imprecisões, riscos vagos, controles inadequados ou conceitos confundidos;
- faça perguntas ou dê dicas para eu corrigir;
- só apresente uma versão completa se eu pedir depois de tentar novamente.

[COLE SUA RESPOSTA AQUI]
```

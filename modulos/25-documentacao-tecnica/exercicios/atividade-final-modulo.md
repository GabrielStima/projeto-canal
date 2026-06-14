# Atividade Final Prática — Portal Documental do PetCare OS

## O Que Você Já Possui

Você construiu progressivamente a documentação técnica do PetCare OS:

- `docs/README.md` com instruções de setup e navegação;
- `docs/adr/001-<decisao>.md` registrando uma decisão arquitetural;
- `docs/arquitetura/hld.md` com C4 nível 1 e nível 2;
- `docs/arquitetura/lld-<fluxo>.md` detalhando um fluxo;
- `docs/runbooks/<cenario>.md` para um incidente operacional;
- `docs/rfcs/<mudanca>.md` propondo uma mudança futura.

## A Tarefa

Crie `docs/portal-documental.md`, um índice consolidado que organize toda a documentação do PetCare OS para diferentes públicos.

O portal deve conter:

1. **Propósito:** em uma ou duas frases, para que serve esse portal e quando atualizá-lo.
2. **Mapa de públicos:** uma tabela com pelo menos quatro perfis (ex: novo desenvolvedor, engenheiro backend, pessoa de operações, auditor externo, product manager) e, para cada um:
   - onde começar;
   - quais documentos ler;
   - qual é o objetivo após a leitura.
3. **Inventário de documentos:** liste cada arquivo produzido com:
   - nome e caminho;
   - tipo (README, ADR, HLD, LLD, runbook, RFC);
   - público principal;
   - uma linha sobre o conteúdo;
   - data de última revisão sugerida.
4. **Navegação por jornada:** escolha duas jornadas do sistema e indique a sequência de documentos que uma pessoa deve ler para entender e operar cada uma. Exemplo:
   - jornada de agendamento: README → HLD → LLD do fluxo → runbook;
   - jornada de decisão arquitetural: HLD → ADR → RFC proposta.
5. **Checklist de qualidade:** crie critérios para revisar se a documentação continua confiável, como:
   - comandos testados a cada alteração de dependência;
   - diagramas atualizados quando a arquitetura muda;
   - runbooks revisados após incidentes;
   - ADRs e RFCs vinculados a pull requests relevantes.
6. **Revisão cruzada:** identifique pelo menos duas inconsistências entre os documentos que você criou e proponha correções. Exemplos: um comando no README que não corresponde ao LLD; uma decisão no ADR que não aparece no HLD; um runbook que menciona um fluxo não detalhado.
7. **Próximos passos:** liste três documentos ou revisões que ainda faltam para considerar o portal completo.

## O Que Você Vai Produzir

- `docs/portal-documental.md` consolidado;
- uma estrutura de pastas organizada para `docs/`;
- um conjunto de documentos que conversam entre si;
- um plano de manutenção da documentação.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei o portal documental do PetCare OS consolidando README, ADR, HLD, LLD, runbook e RFC.

Tarefa: Revise se o portal organiza a documentação para diferentes públicos e mantém consistência entre os documentos.

Critérios de correção:
1. O propósito do portal é claro e a regra de atualização é objetiva.
2. O mapa de públicos indica onde começar, o que ler e o objetivo de cada leitura.
3. O inventário lista todos os documentos com tipo, público, resumo e ciclo de revisão.
4. A navegação por jornada liga documentos em sequência lógica.
5. O checklist de qualidade contém critérios verificáveis.
6. A revisão cruzada aponta inconsistências reais entre os documentos anteriores.
7. Os próximos passos priorizam documentos ainda ausentes.
8. A linguagem é direta e o portal é navegável sem explicações adicionais.

Primeiro destaque meus acertos. Depois aponte inconsistências, navegação confusa ou falta de critérios de manutenção e ofereça dicas. Só apresente um portal completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

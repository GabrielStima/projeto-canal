# Atividade Final Prática — Revisão de System Design do PetCare OS

## O Que Você Já Possui

Você construiu progressivamente em `docs/system-design.md`:

- requisitos, restrições e estimativas;
- decisões de consistência e disponibilidade;
- borda e camada de aplicação;
- banco, cache e mensageria;
- falhas, observabilidade e recuperação;
- segurança, custos e plano de evolução.

## A Tarefa

A rede cresceu de 5 para 50 clínicas. Durante campanhas de vacinação, a jornada principal apresenta latência alta e parte do processamento assíncrono acumula.

Conduza uma revisão completa:

1. confira as estimativas com o novo cenário;
2. desenhe a versão atual e a próxima evolução;
3. percorra uma leitura, uma escrita e uma tarefa assíncrona de ponta a ponta;
4. justifique cada componente pelos requisitos;
5. valide consistência, idempotência, privacidade e retenção;
6. identifique pontos únicos de falha e cascatas;
7. apresente degradação, recuperação e evidências operacionais;
8. revise ameaças e fronteiras de confiança;
9. estime os principais custos e riscos operacionais;
10. registre decisões, alternativas descartadas e próximos gargalos.

Depois, faça uma apresentação curta:

- 2 minutos para problema e requisitos;
- 5 minutos para arquitetura e fluxos;
- 3 minutos para falhas, segurança e trade-offs.

O objetivo não é utilizar todos os componentes estudados. Remova qualquer elemento que não possua requisito, gargalo ou risco correspondente.

## O Que Você Vai Produzir

- `docs/system-design.md` consolidado;
- diagramas da versão atual e da próxima evolução;
- três decisões arquiteturais justificadas;
- matriz de riscos e falhas;
- roteiro de apresentação do desenho.

Esse documento servirá como base arquitetural para avaliar aplicações com IA no próximo módulo.

## Corrija Sua Atividade Com IA

```text
Cenário: Concluí o system design do PetCare OS para crescer de 5 para 50 clínicas e suportar picos de campanhas de vacinação.

Tarefa: Revise meus requisitos, estimativas, diagramas, fluxos, falhas, segurança, custos e decisões.

Critérios de correção:
1. Requisitos e estimativas orientam componentes e capacidade.
2. A arquitetura atual e a próxima evolução estão claramente separadas.
3. Leituras, escritas e tarefas assíncronas possuem fluxos coerentes.
4. Consistência, cache, mensageria e idempotência respeitam as regras do produto.
5. Falhas, degradação, recuperação e observabilidade são verificáveis.
6. Segurança, privacidade e fronteiras de confiança estão integradas ao desenho.
7. Custos e carga operacional influenciam as decisões.
8. Componentes sem justificativa foram removidos e os trade-offs estão explícitos.
9. A apresentação consegue explicar o desenho sem depender de nomes de ferramentas.

Primeiro destaque meus acertos. Depois questione suposições, aponte gargalos e ofereça dicas para eu melhorar. Só apresente uma arquitetura completa depois que eu revisar minha própria solução.

[COLE SUA RESPOSTA AQUI]
```

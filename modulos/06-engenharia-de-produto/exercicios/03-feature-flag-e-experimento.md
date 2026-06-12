# Exercício 03 — Feature Flag e Experimento do PetCare OS

## Cenário

O portal do tutor está pronto para a primeira entrega, mas a direção da rede de clínicas quer minimizar riscos. A funcionalidade de **aprovação de orçamento pelo portal** será liberada primeiro para um grupo pequeno de tutores, antes de ficar disponível para todos.

Além disso, o time quer aprender qual versão da tela de aprovação gera mais confiança para o tutor autorizar o procedimento.

## Tarefa

Você vai produzir um documento chamado `feature-flag-e-experimento.md` dentro do seu repositório do PetCare OS. Ele deve conter:

1. **Especificação de uma feature flag** para a aprovação de orçamento pelo portal, incluindo:
   - nome da flag;
   - estado inicial;
   - quem deve ver a funcionalidade em cada etapa;
   - plano de remoção da flag.
2. **Hipótese de experimento** para comparar duas versões da tela de aprovação.
3. **Métrica principal** que indica se o experimento deu certo.
4. **Riscos de interpretação** do resultado.
5. **Critério para encerrar o experimento**.

## Critérios de Aceite

- A feature flag tem nome claro, estados bem definidos e um plano de remoção realista.
- O experimento possui hipótese testável e métrica objetiva.
- A métrica mede valor para o tutor ou para a clínica, não apenas cliques.
- Os riscos de interpretação revelam armadilhas comuns em experimentos.
- O critério de encerramento define quando a flag pode ser removida ou a funcionalidade pode ser expandida.

## Exemplo de Formato

```markdown
# Feature Flag e Experimento — Aprovação de Orçamento

## Feature flag: `portal_budget_approval`

- **Estado inicial:** desligada para todos os tutores.
- **Etapa 1 (validação interna):** ligada apenas para tutores de uma única clínica parceira.
- **Etapa 2 (liberação gradual):** ligada para 20% dos tutores das clínicas participantes.
- **Etapa 3 (geral):** ligada para todos os tutores das clínicas participantes.
- **Remoção:** após 30 dias estáveis com a métrica principal acima do baseline e sem regressão no suporte.

## Experimento

**Hipótese:**
Se a tela de aprovação mostrar o valor total, a lista de itens e a estimativa de tempo de forma destacada,
então mais tutores aprovarão o orçamento sem precisar ligar para a clínica.

**Variações:**
- **Versão A:** botão "Aprovar" discreto ao final da tela, itens em lista simples.
- **Versão B:** botão "Autorizar Procedimento" destacado, com resumo visual de valor e duração no topo.

**Métrica principal:**
Percentual de orçamentos aprovados pelo portal sem intervenção da recepção.

**Riscos de interpretação:**
- Um aumento de cliques pode indicar curiosidade, não confiança.
- Tutores de procedimentos urgentes podem se comportar diferente de tutores de consultas rotineiras.
- Se houver uma promoção no mesmo período, a taxa de aprovação pode subir por motivos externos.

**Critério para encerrar:**
O experimento pode ser encerrado quando cada versão tiver pelo menos 50 aprovações completas e a diferença entre as versões se mantiver estável por 7 dias.
```

## Corrija Sua Atividade Com IA

```text
Você é um revisor pedagógico de engenharia de produto.

Cenário: estou estudando feature flags e experimentos em uma formação fullstack JavaScript/TypeScript. O exercício pede para escrever um documento chamado `feature-flag-e-experimento.md` para a funcionalidade de aprovação de orçamento pelo portal de uma plataforma veterinária.

Tarefa: revise o documento que eu produzi. Ele deve conter:
1. Uma feature flag com nome, estado inicial, liberação gradual e plano de remoção.
2. Uma hipótese de experimento testável.
3. Uma métrica principal objetiva.
4. Riscos de interpretação do resultado.
5. Critério para encerrar o experimento.

Critérios de correção:
- A feature flag deve ter nome claro e plano de remoção definido.
- A hipótese deve relacionar mudança na interface a resultado de comportamento.
- A métrica principal deve medir valor, não apenas volume de cliques.
- Os riscos devem apontar armadilhas reais de interpretação.
- O critério de encerramento deve ser objetivo.

[COLE SUA RESPOSTA AQUI]

Instruções de correção:
- Destaque os acertos do documento.
- Aponte gaps na flag, métricas de vaidade, hipóteses irreversíveis ou critérios de encerramento vagos.
- Ofereça dicas específicas de melhoria antes de apresentar uma versão alternativa completa.
- Não entregue uma resposta pronta sem antes comentar o que está bom e o que pode evoluir.
```

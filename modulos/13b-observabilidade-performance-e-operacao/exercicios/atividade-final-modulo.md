# Atividade Final do Módulo

## O que você já tem

Ao longo do módulo, você acompanhou um endpoint desde a baseline até a resposta a uma falha:

- diagnóstico e profiling;
- teste de carga;
- logs e instrumentação;
- fluxo de telemetria;
- métricas e trace;
- dashboard e alerta;
- failure mode e mitigação.

Agora você consolidará essas partes em uma demonstração operacional pequena e reproduzível.

## Sua tarefa

Use o mesmo endpoint e entregue:

1. baseline de latência e comportamento;
2. hipótese investigada com profiling;
3. cenário de carga versionado;
4. logs estruturados com correlação, duração e status;
5. catálogo de métricas;
6. trace desenhado ou instrumentado;
7. dashboard especificado;
8. alerta acionável;
9. failure mode com simulação ou plano reproduzível;
10. comparação antes e depois, caso tenha realizado otimização.

Não é necessário instalar uma plataforma completa, contratar serviço externo ou demonstrar escala de produção. Use ferramentas locais ou documentos verificáveis para as partes que dependem de infraestrutura ainda não estudada.

## O que você vai produzir

- `docs/operational-baseline.md`;
- script de carga;
- instrumentação e exemplos de logs;
- catálogo de métricas e trace;
- dashboard e regra de alerta;
- procedimento de mitigação;
- evidências e limitações da demonstração.

## Demonstração mínima

Mostre:

- uma requisição com identificador correlacionado;
- duração observada no log;
- resultado do cenário de carga;
- caminho de investigação de métrica para trace e log;
- sinal esperado durante o failure mode;
- ação indicada pelo alerta.

## Critérios de conclusão

- A comparação usa medições, não percepção.
- O teste de carga possui cenário e limites claros.
- Dados sensíveis não aparecem nos sinais.
- Logs, métricas e trace possuem funções diferentes.
- O alerta representa impacto e leva a uma ação.
- O failure mode inclui mitigação e recuperação.
- Limitações do ambiente local estão documentadas.

## Como este trabalho continuará

Nos módulos seguintes, esses sinais ajudarão a avaliar refatorações, decisões arquiteturais e implantação. Em cloud e SRE, o desenho local poderá ser conectado a ferramentas operacionais reais.

## Corrija Sua Atividade Com IA

```text
Cenário: Concluí uma demonstração operacional para um endpoint de uma API Node.js. Registrei baseline, profiling, carga, logs, correlação, métricas, trace, dashboard, alerta e um failure mode.

Tarefa: Revise a coerência entre medição, sinais, investigação e resposta.

Critérios de correção:
1. Baseline e carga são reproduzíveis?
2. A conclusão de performance usa evidência?
3. Logs estruturados evitam dados sensíveis?
4. Métricas, trace e logs se complementam?
5. O dashboard e o alerta representam impacto acionável?
6. O failure mode possui mitigação, recuperação e sinais suficientes?
7. As limitações do ambiente foram reconhecidas?

Organize a resposta em acertos, riscos críticos, imprecisões e dicas priorizadas. Não reescreva toda a solução antes da minha tentativa de correção.

[COLE SUA RESPOSTA AQUI]
```

# Atividade Final Prática — Assistente Controlado do PetCare OS

## O Que Você Já Possui

Você construiu em `docs/sistema-ia.md`:

- escopo, limites, dados e métricas;
- workflow de desenvolvimento com IA;
- contratos de ferramentas e autonomia;
- recuperação com fontes;
- evals e guardrails;
- operação, versionamento e custos.

## A Tarefa

Implemente um protótipo mínimo do caso de uso escolhido. Ele pode usar uma API real, um modelo local ou um test double determinístico. O uso de serviço pago não é obrigatório.

O protótipo deve:

1. receber uma pergunta dentro do escopo;
2. minimizar e validar a entrada;
3. recuperar fontes ou chamar uma ferramenta controlada;
4. produzir resposta com indicação de fontes ou evidências;
5. recusar ou encaminhar quando não houver suporte;
6. impedir uma ação sensível sem confirmação;
7. registrar métricas sem conteúdo sensível;
8. executar a suíte mínima de evals;
9. aplicar pelo menos um guardrail fora do prompt;
10. estimar custo normal e de pico;
11. permitir trocar modelo, prompt ou corpus de forma rastreável;
12. demonstrar um caminho de fallback quando a IA estiver indisponível.

Apresente:

- arquitetura e fluxo;
- demonstração de sucesso, recusa e tentativa adversarial;
- resultados dos evals;
- riscos residuais;
- decisão sobre publicar, limitar ou interromper o experimento.

Não inclua diagnóstico ou prescrição. Para informações de cuidado, limite o sistema a conteúdo previamente aprovado e encaminhe dúvidas clínicas para profissionais responsáveis.

## O Que Você Vai Produzir

- protótipo mínimo executável ou simulado;
- `docs/sistema-ia.md` consolidado;
- conjunto de evals e resultados;
- registro de custos e métricas;
- decisão de lançamento com limitações.

No próximo módulo, esse sistema será documentado para outros desenvolvedores e operadores.

## Corrija Sua Atividade Com IA

```text
Cenário: Implementei um protótipo controlado de assistente para o PetCare OS, com fontes ou ferramentas, evals, guardrails, observabilidade e limites.

Tarefa: Revise minha arquitetura, demonstrações, resultados e decisão de lançamento.

Critérios de correção:
1. O protótipo resolve um problema delimitado e possui alternativa sem IA.
2. Entrada, dados e contexto são minimizados e validados.
3. Fontes ou ferramentas têm permissões e evidências claras.
4. Recusas, encaminhamento e confirmação de ações funcionam.
5. Evals cobrem sucesso, ausência de fonte, privacidade, injection e autonomia.
6. Guardrails não dependem apenas do prompt.
7. Métricas e logs evitam conteúdo sensível.
8. Custos, versões, fallback e rollback estão definidos.
9. A decisão de lançamento reconhece riscos residuais e limitações.

Primeiro destaque meus acertos. Depois aponte falhas, questione evidências e ofereça dicas. Só apresente uma solução completa depois que eu revisar minha própria implementação.

[COLE SUA RESPOSTA AQUI]
```

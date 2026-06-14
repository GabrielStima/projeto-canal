# Atividade Final Prática — Assistente Controlado do PetCare OS

## O Que Você Já Possui

Você construiu em `docs/sistema-ia.md`:

- escopo, limites, dados e métricas;
- seleção de modelo e alternativa sem IA;
- contrato TypeScript, schema, estado e resiliência;
- contratos de ferramentas e autonomia;
- recuperação com fontes;
- evals e guardrails;
- operação, versionamento e custos.

## A Tarefa

Implemente um protótipo mínimo do caso de uso escolhido. Ele pode usar uma API real, um modelo local ou um test double determinístico. O uso de serviço pago não é obrigatório.

O protótipo deve:

1. receber e minimizar uma pergunta dentro do escopo;
2. chamar o modelo por uma interface substituível;
3. validar uma saída estruturada antes do uso;
4. limitar estado de sessão e evitar persistência desnecessária;
5. aplicar timeout, cancelamento e retry limitado;
6. demonstrar fallback quando a IA estiver indisponível;
7. recuperar fontes ou chamar uma ferramenta controlada;
8. produzir resposta com fontes ou evidências;
9. recusar ou encaminhar quando não houver suporte;
10. impedir ação sensível sem confirmação;
11. registrar métricas sem conteúdo sensível;
12. executar a suíte mínima de evals;
13. aplicar pelo menos um guardrail fora do prompt;
14. estimar custo normal e de pico;
15. permitir trocar modelo, prompt ou corpus de forma rastreável.

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
2. Entrada, dados, contexto, estado e retenção são minimizados.
3. Adapter, schema e validações isolam o domínio do provedor.
4. Timeout, cancelamento, retry e fallback são controlados.
5. Fontes ou ferramentas têm permissões e evidências claras.
6. Recusas, encaminhamento e confirmação de ações funcionam.
7. Evals cobrem sucesso, ausência de fonte, privacidade, injection e autonomia.
8. Guardrails não dependem apenas do prompt.
9. Métricas, custos, versões e rollback estão definidos sem conteúdo sensível.
10. A decisão de lançamento reconhece riscos residuais e limitações.

Primeiro destaque meus acertos. Depois aponte falhas, questione evidências e ofereça dicas. Só apresente uma solução completa depois que eu revisar minha própria implementação.

[COLE SUA RESPOSTA AQUI]
```

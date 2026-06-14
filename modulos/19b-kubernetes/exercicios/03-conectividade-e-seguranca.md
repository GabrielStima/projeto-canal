# Exercício 03 — Conectividade e Segurança

## O que você já tem

Seu Deployment descreve a API e suas configurações, mas ainda precisa de endereço estável e controles de execução.

## Tarefa

Acrescente:

1. Service com exposição mínima;
2. porta, targetPort e selector coerentes;
3. decisão entre acesso interno, port-forward de laboratório ou exposição externa;
4. ServiceAccount dedicado;
5. `securityContext` com usuário não-root;
6. proibição de escalada de privilégio;
7. filesystem somente leitura quando compatível;
8. capabilities removidas quando não forem necessárias;
9. esboço de RBAC apenas se a aplicação precisar acessar a API do Kubernetes;
10. fluxo textual do cliente até o pod.

Não exponha banco de dados ou serviços internos com `LoadBalancer` sem necessidade comprovada.

## O que você vai produzir

Uma camada de conectividade e segurança proporcional ao laboratório.

## Corrija Sua Atividade Com IA

```text
Cenário: Adicionei Service, ServiceAccount, securityContext, exposição mínima e um fluxo de tráfego para uma API em Kubernetes. RBAC só foi incluído se a aplicação precisar da API do cluster.

Tarefa: Revise meus manifestos e decisões.

Critérios de correção:
1. Service e Deployment usam selectors e portas compatíveis?
2. A aplicação está exposta somente da forma necessária?
3. Serviços internos permanecem internos?
4. O container executa como não-root e sem escalada de privilégio?
5. Capabilities e escrita no filesystem foram reduzidas quando possível?
6. ServiceAccount e RBAC seguem menor privilégio?
7. O fluxo do cliente até o pod pode ser explicado sem ambiguidades?

Primeiro destaque os acertos. Depois aponte imprecisões e riscos. Ofereça dicas antes de apresentar manifestos completos.

[COLE SUA RESPOSTA AQUI]
```

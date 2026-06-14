# Atividade Final do Módulo — Deploy do PetCare OS em Kubernetes

## O que você já tem

Você possui uma imagem publicada no módulo 19A e uma pasta de manifestos com workload, configuração, Service, segurança, recursos, observabilidade e rollout.

## A Tarefa

Consolide os manifestos e execute o deploy em um cluster de laboratório.

1. Confirme o contexto e o namespace antes de aplicar.
2. Valide os manifestos com as ferramentas disponíveis no projeto.
3. Aplique Namespace, ConfigMap, referências a Secret, Deployment e Service.
4. Use a imagem rastreável produzida no módulo 19A.
5. Verifique rollout, pods, eventos, logs, probes e Service.
6. Acesse a API pelo método de exposição escolhido.
7. Registre requests, limits e decisões de persistência.
8. Atualize para uma segunda tag da imagem.
9. Simule uma versão com falha e execute rollback.
10. Registre o que seria necessário antes de chamar essa configuração de produção.

Não versionar valores reais de Secret. Um cluster local é suficiente.

## O que você vai produzir

- manifestos Kubernetes versionados;
- cluster de laboratório executando a imagem do módulo 19A;
- evidências de acesso, saúde, logs, rollout e rollback;
- documentação de operação e limitações;
- decisão final sobre quando Kubernetes é ou não apropriado.

Esse material será retomado no módulo 20 para trabalhar confiabilidade, capacidade, runbooks e incidentes.

## Critérios de conclusão

- o deploy usa uma imagem rastreável;
- a aplicação só recebe tráfego quando está pronta;
- configuração e segredos estão separados;
- recursos e segurança possuem decisões explícitas;
- rollout e rollback foram observados;
- limitações do laboratório estão documentadas.

## Corrija Sua Atividade Com IA

```text
Cenário: Implantei uma aplicação containerizada em um cluster Kubernetes de laboratório. Usei manifestos versionados, imagem rastreável, configuração externa, probes, Service, securityContext, recursos e uma estratégia de rollout. Registrei acesso, logs, atualização e rollback.

Tarefa: Faça uma revisão crítica dos manifestos, evidências e documentação.

Critérios de correção:
1. Namespace, selectors, labels, portas e referências são coerentes?
2. Imagem e rollback usam versões rastreáveis?
3. Startup, readiness e liveness possuem responsabilidades adequadas?
4. ConfigMaps, Secrets e credenciais evitam dados sensíveis no Git?
5. Exposição, ServiceAccount e securityContext seguem privilégio mínimo?
6. Requests, limits, persistência e escala estão justificados?
7. Rollout, versão com falha e rollback foram realmente observados?
8. A documentação distingue laboratório de requisitos de produção?
9. O material prepara a entrada em SRE sem antecipar uma plataforma completa?

Primeiro destaque os acertos. Depois aponte imprecisões, riscos e lacunas por prioridade. Ofereça dicas antes de apresentar qualquer conjunto completo de manifestos.

[COLE SUA RESPOSTA AQUI]
```

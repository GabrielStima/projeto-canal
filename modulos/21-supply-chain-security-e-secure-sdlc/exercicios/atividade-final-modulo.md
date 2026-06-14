# Atividade Final Prática — Revisão de uma Entrega Segura

## O Que Você Já Possui

Ao longo do módulo, você construiu:

- um mapa da cadeia e de suas ameaças;
- uma matriz de identidades, segredos e permissões;
- uma proposta de pipeline e quality gates;
- uma política de dependências;
- uma cadeia de evidências do artefato;
- uma estratégia de SAST, SCA e DAST.

## A Tarefa

Revise uma entrega candidata do PetCare OS e decida se ela pode ser promovida.

1. Escolha um commit e relacione-o ao build e ao artefato candidato.
2. Verifique se os eventos e jobs do pipeline respeitam os limites de confiança.
3. Confirme que apenas as identidades necessárias acessam secrets e publicação.
4. Reúna resultados de lint, testes, SAST e SCA.
5. Associe um SBOM ao digest do artefato.
6. Registre a evidência de origem e integridade disponível.
7. Planeje ou analise o resultado de DAST em ambiente controlado.
8. Classifique achados como bloqueio, correção posterior ou exceção temporária.
9. Para cada exceção, defina justificativa, responsável, prazo e controle compensatório.
10. Emita uma decisão final: promover, corrigir e repetir, ou rejeitar.

Você não precisa adotar todas as ferramentas citadas nas aulas. Escolha opções compatíveis com o projeto e justifique como cada controle reduz uma ameaça. Assinatura de artefatos é opcional, mas a rastreabilidade entre código, build e digest é obrigatória.

## O Que Você Vai Produzir

- `docs/seguranca-cadeia.md` consolidado;
- workflow revisado ou uma proposta detalhada de alteração;
- registro dos gates e de suas evidências;
- SBOM ou exemplo representativo associado ao artefato;
- decisão de promoção com riscos e exceções.

Esse conjunto poderá ser retomado em futuras mudanças do pipeline e em incidentes envolvendo dependências, credenciais ou artefatos.

## Corrija Sua Atividade Com IA

```text
Cenário: Revisei uma entrega candidata do PetCare OS usando ameaça, acesso, pipeline, dependências, SBOM, proveniência e testes de segurança.

Tarefa: Avalie minha decisão de promover, corrigir ou rejeitar o artefato e a qualidade das evidências usadas.

Critérios de correção:
1. Cada controle está ligado a uma ameaça relevante.
2. Código não confiável não acessa secrets ou permissões de publicação.
3. Quality gates possuem critérios objetivos, e exceções têm responsável e prazo.
4. Dependências são avaliadas por severidade, explorabilidade e alcance.
5. Commit, build, SBOM e digest do artefato podem ser relacionados.
6. SAST, SCA e DAST são usados de forma complementar e dentro de seus limites.
7. A decisão final explicita riscos residuais e evidências suficientes para ser auditada.

Primeiro destaque meus acertos. Depois aponte lacunas e ofereça perguntas ou dicas para eu melhorar. Só apresente uma revisão completa depois que eu ajustar minha própria solução.

[COLE SUA RESPOSTA AQUI]
```

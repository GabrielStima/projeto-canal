# Atividade Final do Módulo — Pipeline de Build e Registry

## O que você já tem

O PetCare OS está containerizado, documentado e possui uma política de entrega e publicação.

## A Tarefa

Crie um workflow que:

1. execute lint, testes, verificação de tipos e build no pull request;
2. construa a imagem usando o Dockerfile revisado;
3. não publique artefatos quando uma validação falhar;
4. publique após integração na branch principal;
5. autentique no registry com credencial temporária ou token limitado ao job;
6. aplique uma tag imutável baseada no commit;
7. registre o digest publicado;
8. execute scanner e bloqueie conforme a política definida;
9. mantenha logs suficientes para auditoria;
10. documente como promover e reverter uma versão.

Use a imagem publicada para atualizar o `compose.yaml` ou um arquivo de homologação. Preserve a mesma imagem para o módulo 19B.

## O que você vai produzir

- workflow de CI/CD versionado;
- imagem publicada com tag rastreável;
- digest e evidência das validações;
- documentação de promoção e rollback;
- stack containerizada pronta para orquestração.

Se um registry remoto não estiver disponível, documente a limitação e demonstre build, tags e fluxo de publicação em um registry de laboratório. Não simule silenciosamente uma publicação que não ocorreu.

## Critérios de conclusão

- validações impedem a publicação de código reprovado;
- imagem e commit podem ser relacionados;
- autenticação não depende de segredo amplo e permanente;
- promoção e rollback usam versões conhecidas;
- a imagem publicada é a mesma que seguirá para Kubernetes.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei um pipeline que valida uma aplicação, constrói e verifica sua imagem, publica em registry com autenticação limitada, registra tag e digest e documenta promoção e rollback.

Tarefa: Revise meu workflow, Dockerfile, política de tags e evidências.

Critérios de correção:
1. Lint, testes, tipos e build bloqueiam etapas posteriores quando falham?
2. Publicação ocorre somente a partir de uma referência confiável?
3. A imagem publicada pode ser relacionada ao commit e ao digest?
4. Credenciais possuem duração e permissões mínimas?
5. O scanner aplica a política de vulnerabilidades definida?
6. Promoção e rollback reutilizam a mesma imagem, sem rebuild escondido?
7. As evidências distinguem claramente o que foi executado do que ficou apenas documentado?
8. A imagem está pronta para ser consumida no módulo Kubernetes?

Primeiro destaque os acertos. Depois aponte imprecisões, riscos e lacunas por prioridade. Ofereça dicas antes de apresentar qualquer workflow completo.

[COLE SUA RESPOSTA AQUI]
```

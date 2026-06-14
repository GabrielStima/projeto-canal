# Exercício 03 — Imagem e Contrato de Execução

## O que você já tem

A API do PetCare OS possui comando de build, comando de inicialização, configuração por ambiente, logs em stdout e endpoint de saúde.

## Tarefa

Crie ou revise:

- `Dockerfile`;
- `.dockerignore`;
- uma seção em `docs/entrega.md` com o contrato de execução.

O Dockerfile deve:

1. usar imagem base com versão controlada;
2. aproveitar cache ao instalar dependências antes de copiar o restante;
3. usar multi-stage quando houver build ou dependências de desenvolvimento;
4. copiar somente o necessário para a imagem final;
5. executar com usuário não-root;
6. receber configuração em tempo de execução;
7. possuir comando de inicialização apropriado;
8. expor ou documentar a porta;
9. oferecer healthcheck compatível com a aplicação.

Registre como construir, executar e identificar a imagem sem depender de `latest`.

## O que você vai produzir

Uma imagem preparada para ser usada no Compose, no registry e, posteriormente, no Kubernetes.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei um Dockerfile e .dockerignore para uma API Node.js. A imagem usa versão controlada, cache de dependências, multi-stage quando necessário, usuário não-root, configuração em runtime, comando de inicialização e healthcheck.

Tarefa: Revise meu Dockerfile e o contrato de execução.

Critérios de correção:
1. A ordem das camadas favorece reaproveitamento de cache?
2. A imagem final contém somente dependências e arquivos necessários?
3. Segredos e arquivos locais ficaram fora do contexto e da imagem?
4. O processo executa sem privilégios de root?
5. Build e configuração de runtime foram separados?
6. Healthcheck, porta e comando correspondem à aplicação real?
7. A imagem pode ser identificada por uma tag rastreável?

Primeiro destaque os acertos. Depois aponte imprecisões e ofereça dicas antes de escrever um Dockerfile completo.

[COLE SUA RESPOSTA AQUI]
```

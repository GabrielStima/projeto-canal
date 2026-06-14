# Exercício 06 — Containerizando o PetCare OS

## O que você já tem

Você criou o Dockerfile, o Compose, o contrato de execução e a política de publicação da imagem.

## Tarefa

Esta atividade é obrigatória para continuar ao módulo 19B.

Integre e revise os arquivos:

- `Dockerfile`;
- `.dockerignore`;
- `compose.yaml`;
- arquivo de exemplo de variáveis sem segredos;
- documentação de execução e diagnóstico.

Demonstre, por evidência ou registro dos resultados:

1. build da imagem;
2. inicialização da stack;
3. healthcheck saudável;
4. acesso a um endpoint da API;
5. persistência do banco após recriar containers;
6. comunicação com a fila, quando aplicável;
7. execução como usuário não-root;
8. logs disponíveis sem alterar o container;
9. parada e limpeza sem remover dados por acidente.

Depois registre:

- três cenários em que Docker Compose é suficiente;
- três sinais que justificariam avaliar orquestração;
- custos operacionais que Kubernetes adicionaria.

## O que você vai produzir

Uma stack containerizada e documentada que será publicada na atividade final e orquestrada no módulo 19B.

## Corrija Sua Atividade Com IA

```text
Cenário: Integrei Dockerfile, .dockerignore, compose.yaml, configuração de exemplo e documentação para uma API com banco e fila. Registrei build, execução, saúde, acesso, persistência, logs, usuário não-root e limpeza. Também comparei Compose com Kubernetes.

Tarefa: Faça uma revisão crítica da containerização e das evidências.

Critérios de correção:
1. Outra pessoa consegue iniciar a stack seguindo a documentação?
2. Imagem, rede, configuração e persistência possuem responsabilidades claras?
3. Dados sobrevivem à recriação sem depender do filesystem do container?
4. Segredos e privilégios foram reduzidos?
5. Healthcheck e logs ajudam a diagnosticar falhas?
6. A análise Compose versus Kubernetes considera escala, disponibilidade, equipe e custo?
7. A stack está pronta para produzir uma imagem rastreável no pipeline?

Comece pelos acertos. Depois aponte imprecisões, riscos e lacunas por prioridade. Dê dicas antes de apresentar qualquer solução completa.

[COLE SUA RESPOSTA AQUI]
```

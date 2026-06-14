# Exercício 05 — Registry, Rastreabilidade e Segurança

## O que você já tem

Sua imagem roda em uma stack local e a política de entrega define o artefato que avançará entre ambientes.

## Tarefa

Defina como a imagem será publicada e promovida:

1. registry e visibilidade escolhidos;
2. autenticação do pipeline com token de job ou identidade federada;
3. tag imutável baseada no commit;
4. tag de versão ou canal, se necessária;
5. relação entre commit, execução do pipeline e digest da imagem;
6. scanner de vulnerabilidades e limite de bloqueio;
7. política de atualização da imagem base;
8. retenção de versões;
9. procedimento para retirar ou substituir uma imagem vulnerável;
10. permissões de leitura e escrita no registry.

Não incorpore segredos à imagem e não use `latest` como única referência.

## O que você vai produzir

Uma política de publicação e promoção segura para a imagem do PetCare OS.

## Corrija Sua Atividade Com IA

```text
Cenário: Planejei a publicação de uma imagem em registry com autenticação temporária, tag do commit, digest, scanner de vulnerabilidades, retenção, atualização de base e permissões mínimas.

Tarefa: Avalie minha política de registry e segurança.

Critérios de correção:
1. É possível relacionar imagem, digest, commit e execução do pipeline?
2. Tags mutáveis não são a única referência de deploy?
3. O pipeline publica sem credencial permanente desnecessária?
4. Vulnerabilidades possuem critério de bloqueio e processo de exceção?
5. Imagens vulneráveis podem ser substituídas sem apagar evidências essenciais?
6. Permissões distinguem leitura, publicação e administração?
7. Segredos ficaram fora das camadas da imagem?

Primeiro destaque os acertos. Depois aponte imprecisões e ofereça dicas antes de apresentar uma política completa.

[COLE SUA RESPOSTA AQUI]
```

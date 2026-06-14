# Exercício 03 — Borda e Camada de Aplicação

## O Que Você Já Possui

Você conhece a carga, os picos e as operações que podem ou não aceitar atraso.

## A Tarefa

Desenhe em `docs/system-design.md` o caminho de uma requisição desde o dispositivo do tutor até a aplicação.

Inclua apenas componentes justificados:

1. DNS e estratégia de resolução;
2. CDN para conteúdos adequados, com regras que evitem cache compartilhado de dados privados;
3. proteção e controle na borda;
4. load balancer e verificações de saúde;
5. instâncias stateless da aplicação;
6. armazenamento externo para arquivos e sessões, quando necessário;
7. autoscaling, limites e proteção contra rajadas;
8. timeout e comportamento diante de dependência lenta.

Para cada componente, registre requisito atendido, falha introduzida, métrica principal e alternativa mais simples. Desenhe também a primeira versão que funcionaria antes de adicionar toda a evolução.

## O Que Você Vai Produzir

Um fluxo de borda e aplicação com evolução incremental e sem estado local incompatível com escalonamento horizontal.

O próximo exercício conectará esse fluxo às decisões de dados, cache e mensageria.

## Corrija Sua Atividade Com IA

```text
Cenário: Desenhei a borda e a camada de aplicação do PetCare OS a partir de requisitos e picos estimados.

Tarefa: Revise o fluxo, os componentes escolhidos e a evolução incremental.

Critérios de correção:
1. DNS, CDN, proteção e load balancer possuem responsabilidades distintas.
2. Dados privados ou altamente dinâmicos não entram em cache compartilhado sem regras corretas.
3. A aplicação pode escalar horizontalmente sem depender de disco ou memória local.
4. Health checks, timeouts, limites e rajadas foram considerados.
5. Cada componente responde a um requisito e apresenta custo ou modo de falha.
6. Existe uma versão inicial menor antes da arquitetura de crescimento.

Primeiro destaque meus acertos. Depois aponte componentes sem justificativa ou pontos únicos de falha e ofereça dicas. Só apresente um desenho completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

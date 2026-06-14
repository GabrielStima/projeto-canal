# Atividade Final do Módulo

## O que você já tem

Você especificou o fluxo no módulo 15 e, neste módulo, praticou escolha de comunicação, reconexão, jobs, filas, retentativas, eventos e idempotência.

## A Tarefa

Integre um fluxo assíncrono completo no PetCare OS, usando a operação escolhida nos exercícios.

1. A API deve validar a solicitação e responder `202 Accepted` com o identificador do job.
2. Um consumidor separado deve executar o trabalho e atualizar os estados do job.
3. A execução deve ter tentativas limitadas, espera progressiva e destino conhecido para falhas permanentes.
4. O consumidor deve tolerar a entrega repetida sem duplicar o efeito.
5. O cliente deve consultar ou receber o estado por short polling, SSE ou WebSocket, conforme sua tabela de decisão.
6. Após uma desconexão, o cliente deve recuperar o estado atual.
7. Logs e métricas devem permitir relacionar solicitação, job, tentativa e resultado.
8. Teste o caminho de sucesso, uma falha temporária e uma mensagem duplicada.

O caminho mínimo pode usar short polling e uma fila local ou simulada. Adote um broker ou canal persistente somente se o projeto estiver preparado para operá-lo.

## O que você vai produzir

- uma rota de criação e outra de consulta do job;
- um produtor e um consumidor separados;
- estados e política de recuperação documentados;
- idempotência demonstrada por teste;
- atualização visível para o usuário;
- evidências de logs, métricas e testes.

Esse fluxo será retomado nos módulos de cloud, infraestrutura e operação.

## Critérios de conclusão

- a requisição não espera o trabalho terminar;
- atraso e falha aparecem como estados compreensíveis;
- tentativas e concorrência possuem limites;
- duplicatas não repetem o efeito;
- o cliente recupera o estado após desconexão;
- a escolha tecnológica está justificada pelo problema.

## Corrija Sua Atividade Com IA

```text
Cenário: Implementei um fluxo assíncrono completo em uma API. Ele responde 202 com o identificador do job, usa produtor e consumidor separados, registra estados, limita retentativas, trata falhas permanentes, aplica idempotência, atualiza o cliente por uma técnica escolhida e possui observabilidade e testes.

Tarefa: Faça uma revisão crítica da implementação, arquitetura ou pseudocódigo e das evidências de teste.

Critérios de correção:
1. O contrato HTTP representa corretamente uma operação assíncrona?
2. Produtor, consumidor e consulta de status possuem responsabilidades claras?
3. Retentativas, concorrência, acúmulo e falhas permanentes têm limites e visibilidade?
4. A idempotência impede efeitos duplicados, inclusive após falha parcial?
5. A técnica de atualização do cliente é proporcional e recupera o estado após desconexão?
6. Logs e métricas correlacionam solicitação, job, tentativa e resultado?
7. Os testes demonstram sucesso, falha temporária e entrega duplicada?

Primeiro destaque os acertos. Depois aponte imprecisões, riscos e lacunas por prioridade. Ofereça dicas antes de apresentar qualquer solução completa.

[COLE SUA RESPOSTA AQUI]
```

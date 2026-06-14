# Exercício 05 — Jornada End-to-End

## Antes de começar

Esta prática é obrigatória como desenho e recomendada como implementação. Se o projeto já possui frontend executável, automatize a jornada. Caso contrário, entregue um plano verificável sem criar uma interface nova.

## Sua tarefa

Escolha uma única jornada crítica do usuário, como:

- tutor faz login e consulta um pet;
- recepcionista cria um agendamento;
- tutor aprova um orçamento.

Descreva:

1. estado inicial e dados de teste;
2. passos observáveis do usuário;
3. resultado final;
4. um erro importante;
5. seletores estáveis;
6. limpeza do estado;
7. por que essa jornada merece E2E.

Quando houver frontend, implemente um caminho feliz e um caso de rejeição. Evite repetir em E2E regras já protegidas em níveis mais baratos.

## O que você vai produzir

- especificação da jornada;
- teste automatizado quando houver frontend;
- decisão sobre o que ficou fora do E2E;
- atualização da estratégia.

## Critérios de conclusão

- A jornada representa valor ou risco para o usuário.
- O estado inicial é controlado.
- Os seletores não dependem de detalhes visuais frágeis.
- O teste observa resultado, não implementação.
- A suíte não repete toda a cobertura unitária e de integração.

## Como este trabalho continuará

O cenário poderá rodar em etapa separada do CI. Se ainda não foi implementado, a especificação fica pronta para quando o frontend estiver disponível.

## Corrija Sua Atividade Com IA

```text
Cenário: Especifiquei ou implementei uma jornada end-to-end para um fluxo crítico de uma aplicação fullstack.

Tarefa: Avalie valor, isolamento, passos, seletores, resultado e custo da jornada.

Critérios de correção:
1. O fluxo merece um teste end-to-end?
2. Estado inicial e limpeza são reproduzíveis?
3. Os passos observam comportamento do usuário?
4. Os seletores resistem a mudanças visuais?
5. Existe duplicação desnecessária com testes mais baratos?

Destaque os acertos, aponte imprecisões e ofereça dicas antes de sugerir um teste completo.

[COLE SUA RESPOSTA AQUI]
```

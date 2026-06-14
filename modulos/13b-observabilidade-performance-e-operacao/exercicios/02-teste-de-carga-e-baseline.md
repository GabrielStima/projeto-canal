# Exercício 02 — Teste de Carga e Baseline

## O que você já sabe

Você possui uma medição inicial e hipóteses sobre um endpoint. Agora observará seu comportamento sob uma carga pequena e controlada.

O objetivo não é provar capacidade de produção nem derrubar a aplicação.

## Sua tarefa

Crie um cenário de carga compatível com um uso real:

- endpoint e sequência de chamadas;
- quantidade inicial de usuários virtuais;
- duração curta;
- dados de teste seguros;
- limites para erros e latência;
- ambiente onde o teste será executado.

Execute o cenário com uma ferramenta disponível ou escreva um script equivalente. Registre:

- throughput;
- taxa de erro;
- latência mediana e percentil alto disponível;
- comportamento da aplicação;
- limitações da conclusão.

Se houver autenticação ou rate limiting, explique como o cenário evita medir apenas bloqueios ou falhas de credencial.

## O que você vai produzir

- script versionado em `scripts/` ou pasta equivalente;
- resultado bruto;
- interpretação no relatório;
- comparação com a baseline do exercício anterior.

## Critérios de conclusão

- A carga representa um cenário, não um número aleatório.
- O ambiente e os dados são controlados.
- Percentis não são confundidos com média.
- Erros fazem parte da análise.
- O resultado local não é generalizado como capacidade de produção.

## Como este trabalho continuará

O cenário será repetido após instrumentação ou melhoria, permitindo comparação antes e depois.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei e executei um teste de carga pequeno para um endpoint de uma API Node.js.

Tarefa: Revise o cenário, as métricas e as conclusões.

Critérios de correção:
1. O volume simula um uso realista?
2. Ambiente, duração e dados estão descritos?
3. Throughput, erros e percentis foram interpretados corretamente?
4. Autenticação e rate limiting não distorcem silenciosamente o teste?
5. As conclusões respeitam os limites de um ambiente local?

Destaque os acertos, aponte imprecisões e dê dicas antes de propor outro script ou cenário.

[COLE SUA RESPOSTA AQUI]
```

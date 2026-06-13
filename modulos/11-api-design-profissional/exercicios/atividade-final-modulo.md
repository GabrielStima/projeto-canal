# Atividade Final — API Com Contrato Evolutivo

## Objetivo

Consolidar a evolução da `petcare-api` em uma entrega demonstrável, documentada e protegida contra quebras de contrato.

## O Que Você Já Possui

- a API persistente construída no módulo 10;
- convenções e OpenAPI refinadas;
- erros padronizados;
- uma listagem com paginação, filtros e ordenação;
- aprovação de orçamento idempotente;
- testes de contrato;
- um desenho exploratório de webhook, caso tenha feito a atividade recomendada.

Esta atividade é **obrigatória para continuidade**. Não crie outra API e não implemente autenticação ainda.

## Sua Tarefa

Prepare uma versão demonstrável da API com:

1. convenção consistente para paths, campos e erros;
2. `docs/openapi.yaml` coerente com os endpoints reais;
3. contratos dos recursos `pets`, `appointments` e `budgets`;
4. listagem de atendimentos paginada, filtrável e ordenável;
5. aprovação de orçamento idempotente;
6. decisão documentada sobre backward compatibility e necessidade de versionamento;
7. checklist de governança aplicado aos endpoints centrais;
8. testes de contrato executáveis;
9. README com comandos de execução, validação da OpenAPI e testes.

O webhook é opcional nesta entrega. Se ele não for implementado, registre apenas a decisão e preserve o contrato para estudo futuro.

## Demonstração Esperada

Mostre:

1. uma consulta de pet bem-sucedida;
2. um erro `404` padronizado;
3. duas páginas da lista de atendimentos com ordenação estável;
4. um filtro válido e um inválido;
5. primeira aprovação de orçamento e repetição com a mesma chave;
6. conflito ao reutilizar a chave com conteúdo diferente;
7. execução dos testes de contrato;
8. evidência da validação sintática e semântica da OpenAPI.

## O Que Você Vai Produzir

- código atualizado da `petcare-api`;
- `docs/openapi.yaml`;
- `docs/api-conventions.md`;
- `docs/api-errors.md`;
- decisão de compatibilidade e versionamento;
- checklist de governança;
- testes em `tests/contracts/`;
- README atualizado;
- registro curto da demonstração.

## Critérios de Conclusão

- a documentação descreve o comportamento real;
- não existem links, paths ou schemas prometidos sem implementação;
- erros e listagens seguem o mesmo padrão;
- repetição e concorrência não duplicam a aprovação;
- testes detectam uma quebra intencional de contrato;
- a OpenAPI foi validada e a ferramenta utilizada foi registrada;
- a API continua executável pelos comandos documentados.

No módulo 12, os mesmos contratos receberão autenticação, autorização e controles de segurança. No módulo 13A, a estratégia de testes será aprofundada.

## Corrija Sua Atividade Com IA

```text
Estou concluindo o módulo de API Design Profissional com uma API Node.js chamada PetCare API.

A entrega deve conter:
- contratos consistentes para pets, appointments e budgets;
- OpenAPI coerente com a implementação;
- ApiError padronizado;
- listagem de atendimentos com paginação, filtros e ordenação estável;
- aprovação de orçamento idempotente;
- decisão sobre backward compatibility e versionamento;
- checklist de governança;
- testes de contrato executáveis;
- README com comandos de execução e validação.

O webhook é opcional e pode permanecer apenas como contrato documentado. Autenticação e autorização não fazem parte desta atividade.

Critérios de correção:
1. documentação e implementação correspondem;
2. contratos não incluem recursos inexistentes;
3. erros e listagens são consistentes;
4. idempotência trata repetição, conflito e concorrência;
5. testes detectam mudanças de nomes, tipos, status e formato de erro;
6. a OpenAPI possui evidência de validação;
7. a demonstração é reproduzível;
8. o escopo não antecipa segurança nem processamento assíncrono.

Faça uma revisão por etapas. Primeiro destaque os acertos. Depois liste imprecisões e requisitos ausentes em ordem de impacto. Ofereça dicas específicas para eu corrigir. Não apresente uma solução completa antes de eu tentar aplicar as correções.

[COLE SUA RESPOSTA AQUI]
```

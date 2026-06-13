# Atividade Final do Módulo

## O que você já tem

Sua API do PetCare OS funciona. Ela tem testes E2E e Integração passando (Módulo 13). Mas o código das regras do domínio está grudado no Express/Fastify e no Prisma/TypeORM.

## A Tarefa

O **marco de design** exige a Refatoração Arquitetural Tática da sua aplicação.

Siga as etapas:
1. **Model-Driven Design**: Identifique as entidades vitais do seu PetCare (Ex: Agendamento, Fatura, Pet). Crie classes puras de TypeScript para elas.
2. **Clean Code & SRP**: Extraia lógicas complexas dos Controllers para dentro de Classes de Uso (Use Cases / Services).
3. **Dependency Inversion**: No seu `Service`, não importe o ORM. Receba uma Interface `IPetRepository` no construtor.
4. **Implementação do Repositório**: Crie uma classe concreta `PrismaPetRepository` que implementa a interface e injete ela apenas no arquivo de Rotas ou via um container DI (como tsyringe).
5. **Testabilidade**: Com essa refatoração, o Teste Unitário do seu Serviço principal deve rodar na casa dos 5ms, sem encostar no Postgres.

## O que você vai produzir

- Uma pasta `src/domain` contendo entidades puras.
- Uma pasta `src/use-cases` com a regra limpa.
- Uma pasta `src/infra` ou `src/repositories` contendo a sujeira do ORM.
- Seu Controller vazio, chamando apenas o caso de uso.

## Corrija Sua Atividade Com IA

```text
Cenário: Refatoração Final com SOLID, DDD Tático e Clean Code.

Tarefa: Enviei abaixo a minha Interface de Repository, o meu UseCase com injeção de dependência e meu Controller limpo.

[COLE AQUI SEUS 3 ARQUIVOS]


[COLE SUA RESPOSTA AQUI]
Critérios de correção:
1. O Princípio da Inversão de Dependência foi perfeitamente aplicado (O UseCase não conhece infra)?
2. As variáveis possuem nomes que refletem a Linguagem Ubíqua (MDD)?
3. O SRP é respeitado ao redor da tríade Controller -> UseCase -> Repository?

Como Senior Software Architect, aponte um pequeno detalhe onde meu design ainda poderia acoplar ou falhar no longo prazo.
```

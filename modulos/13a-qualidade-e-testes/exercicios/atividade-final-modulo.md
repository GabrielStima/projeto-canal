# Atividade Final do Módulo

## O que você já tem

Sua API do PetCare OS funciona, possui regras de autenticação e contratos. Mas ela era manual e não inspirava confiança automática: toda vez que você mexia em algo, precisava abrir o Insomnia/Postman e clicar repetidamente nos botões para garantir que não havia quebrado algo.

## A Tarefa

O **Marco de Integração N4** exige o estabelecimento de uma rede de segurança de software contínua.
Nesta atividade prática, você integrará ferramentas de teste na API.

Siga as etapas:
1. Configure o framework de Testes Unitários e Integração (ex: Jest ou Vitest).
2. Escreva testes Unitários focados nos domínios lógicos que você possui (cálculos ou formatações), atingindo cobertura (Coverage) clara nestes arquivos.
3. Integre a ferramenta de supertest. Crie 1 Suíte de Integração cobrindo 3 endpoints completos (caminho feliz e de falha).
4. Em vez de mocks do Prisma/TypeORM, aponte seus testes de integração para um banco de dados de Teste (local ou container Docker).
5. Opcionalmente (se já construiu Frontend): crie um fluxo mínimo no Cypress/Playwright que abre seu Portal do Tutor e testa o click do "Log In".
6. Crie o pipeline CI (ex: `.github/workflows/ci.yml`) configurado para barrar Push/Merge se os testes rodarem e quebrarem.

## O que você vai produzir

- Uma pasta `tests` na raiz do seu projeto contendo pastas `unit` e `integration`.
- Relatório de Cobertura de Testes sendo gerado no seu terminal.
- Um badge `passing` / `failing` de CI acoplado ao GitHub (se optar por publicá-lo).
- Feedback loop imediato para qualquer alteração na sua aplicação.

## Corrija Sua Atividade Com IA

Com as pipelines configuradas e os testes rodando com sucesso, peça um Code Review. Copie seu pipeline de CI e um trecho do teste de integração que se comunica com o banco de dados.

```text
Cenário: Atividade Final do Módulo de Qualidade e Testes no PetCare OS.

Tarefa: Montei a infraestrutura de CI e as rotinas de Teste de Integração (em anexo).

Critérios de correção:
1. A técnica de isolamento entre suítes está madura (o banco é populado e zerado corretamente)?
2. A configuração de CI está aproveitando o cache para ser rápida? O tempo esperado parece ideal para o padrão da ferramenta (ex: Github Actions)?
3. O limite da asserção garante segurança do software ou as asserções estão triviais?

[COLE SEU CI.YML E TRECHO DE TESTE AQUI]

Por favor, atue como um Engenheiro Sênior de Qualidade: o que falta para meus testes brilharem mais, ficarem mais estáveis (menos flaky) e aprovarem a qualidade total?
```

# Exercício 01 — Problema e Requisitos do PetCare OS

## Cenário

O PetCare OS é uma plataforma usada por uma rede de clínicas veterinárias e petshops. Hoje, quando um pet é deixado para um procedimento, o tutor liga várias vezes na recepção para perguntar como ele está, se precisa de autorização extra ou quando pode buscá-lo.

A direção da rede acredita que um **portal simples para tutores** poderia reduzir essas ligações e dar mais tranquilidade aos clientes. Antes de desenhar telas ou escrever código, o time precisa entender o problema e registrar os primeiros requisitos.

## Tarefa

Você vai produzir um documento curto em Markdown chamado `problema-e-requisitos.md` dentro do seu repositório do PetCare OS. Ele deve conter:

1. **Problema:** em uma ou duas frases, qual dor do tutor e da clínica este portal tenta resolver?
2. **Público afetado:** quem são os usuários diretos e indiretos?
3. **Requisitos funcionais:** pelo menos três comportamentos que o portal deve oferecer.
4. **Requisitos não funcionais:** pelo menos duas restrições de qualidade, segurança, usabilidade ou operação.
5. **Perguntas abertas:** pelo menos três perguntas que ainda precisam ser respondidas antes de implementar.

## Critérios de Aceite

- O problema está escrito na linguagem do usuário, não na linguagem técnica.
- Os requisitos funcionais descrevem comportamentos observáveis do sistema.
- Os requisitos não funcionais são verificáveis de alguma forma.
- As perguntas abertas revelam incertezas reais sobre escopo, risco ou valor.
- Nenhum requisito escolhe tecnologia, framework ou banco de dados.

## Exemplo de Formato

```markdown
# Problema e Requisitos — Portal do Tutor

## Problema
Tutores não têm visibilidade do status do pet durante o atendimento e precisam ligar repetidamente para a clínica.

## Público afetado
- Tutor: quer saber se o pet está bem e quando pode buscá-lo.
- Recepcionista: atende muitas ligações com perguntas repetidas.
- Clínica: perde tempo operacional que poderia ser usado no atendimento.

## Requisitos funcionais
1. O tutor autenticado pode visualizar o status atual do atendimento do seu pet.
2. O tutor autenticado pode aprovar ou recusar um orçamento pelo portal.
3. A clínica pode atualizar o status do atendimento e o tutor vê a mudança.

## Requisitos não funcionais
1. O status deve ser atualizado em até 5 minutos após a mudança na clínica.
2. Apenas tutores vinculados ao pet podem ver seus dados.

## Perguntas abertas
1. O tutor precisa se cadastrar ou usamos o telefone já registrado na clínica?
2. Qual informação é segura mostrar antes da alta? Por exemplo, devemos expor diagnóstico parcial?
3. O portal será usado em computador, celular ou ambos?
```

## Corrija Sua Atividade Com IA

```text
Você é um revisor pedagógico de engenharia de produto.

Cenário: estou estudando requisitos em uma formação fullstack JavaScript/TypeScript. O exercício pede para escrever um documento curto chamado `problema-e-requisitos.md` para o início do portal do tutor de uma plataforma veterinária.

Tarefa: revise o documento que eu produzi. Ele deve conter:
1. Um problema claro na linguagem do tutor e da clínica.
2. Público afetado identificado.
3. Pelo menos três requisitos funcionais observáveis.
4. Pelo menos dois requisitos não funcionais verificáveis.
5. Pelo menos três perguntas abertas relevantes.

Critérios de correção:
- O problema deve falar de dor real, não de solução técnica.
- Requisitos funcionais devem descrever comportamentos do sistema.
- Requisitos não funcionais devem ser mensuráveis ou verificáveis.
- Nenhum requisito deve escolher tecnologia, framework ou banco de dados.
- As perguntas abertas devem revelar incerteza real sobre escopo, risco ou valor.

[COLE SUA RESPOSTA AQUI]

Instruções de correção:
- Destaque os acertos do documento.
- Aponte imprecisões, ambiguidades ou requisitos que parecem soluções disfarçadas.
- Ofereça dicas específicas de melhoria antes de apresentar uma versão alternativa completa.
- Não entregue uma resposta pronta sem antes comentar o que está bom e o que pode evoluir.
```

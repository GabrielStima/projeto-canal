# Exercício 02 — Histórias de Usuário e Critérios de Aceite do PetCare OS

## Cenário

Usando o documento de problemas e requisitos que você criou no exercício anterior, o time do PetCare OS quer transformar as necessidades do tutor em histórias de usuário pequenas e verificáveis.

A primeira funcionalidade escolhida é:

> **Tutor acompanha o status do atendimento pelo portal.**

Antes de desenhar a tela, o time precisa saber quem usa, qual valor entrega e como reconhecer quando a entrega está pronta.

## Tarefa

Você vai produzir um documento chamado `historias-e-criterios.md` dentro do seu repositório do PetCare OS. Ele deve conter:

1. **Duas ou três histórias de usuário** para a funcionalidade de acompanhamento de status. Use o formato `Como [ator], quero [ação], para [valor]`.
2. **Pelo menos três critérios de aceite** para a história principal, usando o formato `Dado ... Quando ... Então ...`.
3. **Um critério de erro ou limite**, como falha de carregamento ou ausência de conexão.
4. Uma breve justificativa de **por que a história foi fatiada dessa forma**.

## Critérios de Aceite

- As histórias têm um ator claro, uma ação observável e um valor de negócio.
- Nenhuma história esconde uma tarefa técnica como se fosse valor para o usuário.
- Os critérios de aceite são verificáveis sem depender de interpretação subjetiva.
- Pelo menos um critério cobre um caso de erro ou limite importante.
- A justificativa explica por que o fatiamento escolhido reduz risco ou entrega valor mais cedo.

## Exemplo de Formato

```markdown
# Histórias e Critérios — Acompanhamento de Status

## História principal
Como tutor,
quero visualizar o status atual do atendimento do meu pet no portal,
para saber se ele ainda está em triagem, em procedimento ou pronto para alta.

## Histórias menores
1. Como tutor, quero ver a linha do tempo do atendimento para entender o que já aconteceu.
2. Como tutor, quero receber uma indicação clara quando o status mudar para "Aguardando Aprovação" para autorizar o orçamento com segurança.

## Critérios de aceite da história principal
- Dado que o tutor está autenticado e possui um pet em atendimento,
  quando ele acessa a página de acompanhamento,
  então o status atual do atendimento é exibido de forma legível.

- Dado que o status do atendimento mudou na clínica,
  quando o tutor recarrega a página,
  então o novo status aparece em até 5 minutos.

- Dado que não há atendimento em andamento para o pet selecionado,
  quando o tutor acessa a página,
  então uma mensagem informativa é exibida orientando-o a entrar em contato com a clínica.

## Critério de erro
- Dado que a API de status está indisponível,
  quando o tutor tenta carregar a página,
  então uma mensagem de erro amigável é exibida e o sistema permite uma nova tentativa.

## Por que esse fatiamento?
A história principal entrega o valor essencial logo no início: saber o status. As histórias menores aumentam a clareza e preparam o terreno para a aprovação de orçamento, sem bloquear a primeira entrega.
```

## Corrija Sua Atividade Com IA

```text
Você é um revisor pedagógico de engenharia de produto.

Cenário: estou estudando histórias de usuário e critérios de aceite em uma formação fullstack JavaScript/TypeScript. O exercício pede para escrever um documento chamado `historias-e-criterios.md` para a funcionalidade de acompanhamento de status de um pet em uma plataforma veterinária.

Tarefa: revise o documento que eu produzi. Ele deve conter:
1. Duas ou três histórias de usuário com formato `Como [ator], quero [ação], para [valor]`.
2. Pelo menos três critérios de aceite para a história principal, usando `Dado ... Quando ... Então ...`.
3. Um critério de erro ou limite.
4. Uma justificativa do fatiamento.

Critérios de correção:
- Histórias devem ter ator, ação observável e valor claro.
- Nenhuma história pode ser uma tarefa técnica disfarçada.
- Critérios de aceite devem ser objetivos e verificáveis.
- Pelo menos um critério deve cobrir erro ou limite.
- A justificativa deve explicar o valor do fatiamento escolhido.

[COLE SUA RESPOSTA AQUI]

Instruções de correção:
- Destaque os acertos do documento.
- Aponte histórias vagas, critérios subjetivos ou falta de critério de erro.
- Ofereça dicas específicas de melhoria antes de apresentar uma versão alternativa completa.
- Não entregue uma resposta pronta sem antes comentar o que está bom e o que pode evoluir.
```

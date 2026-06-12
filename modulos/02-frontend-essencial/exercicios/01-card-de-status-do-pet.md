# Exercício 01 — Card de Status do Pet

## Objetivo

Praticar HTML semântico e CSS básico criando um card que um tutor poderia ver no portal da clínica para acompanhar o status do pet durante um atendimento.

## Cenário

Você está construindo a primeira versão do Portal do Tutor do PetCare OS. Nessa versão, o tutor acessa uma página simples que mostra, em destaque, como está o atendimento do pet na clínica.

Um atendimento pode estar em um dos seguintes momentos:

- Recebido
- Em Triagem
- Aguardando Aprovação
- Em Procedimento
- Pronto para Alta
- Finalizado

## Sua Tarefa

Crie um arquivo `index.html` e um arquivo `styles.css` que renderizem um card de status do pet.

O card deve conter:

1. Nome do pet e espécie (ex: "Thor, cachorro").
2. Nome do tutor.
3. Status atual do atendimento.
4. Horário estimado de alta ou uma mensagem como "Sem previsão ainda".
5. Uma breve linha do tempo mostrando os dois últimos status anteriores.

Use elementos HTML semânticos. Por exemplo:

- `<article>` para o card como um todo.
- `<header>` para a área do nome do pet e espécie.
- `<section>` ou `<ol>` para a linha do tempo.
- `<span>` ou `<p>` com classes significativas para o status.

No CSS:

- Defina uma largura máxima confortável para leitura.
- Dê destaque visual ao status atual (cor de fundo ou borda).
- Diferencie visualmente os status anteriores do status atual.
- Use uma fonte legível e espaçamento adequado.

## Requisitos Mínimos

- [ ] Estrutura HTML válida com `lang="pt-BR"`, `charset="utf-8"` e `viewport`.
- [ ] Pelo menos cinco elementos semânticos diferentes.
- [ ] CSS em arquivo separado.
- [ ] Status atual destacado visualmente.
- [ ] Status anteriores visíveis, mas com menor ênfase.
- [ ] Página legível sem depender de framework.

## Exemplo de Estrutura Esperada

```text
[Card]
  Thor, cachorro
  Tutor: Gabriel Rocha
  Status atual: Em Procedimento
  Previsão de alta: 14h30
  Linha do tempo:
    1. Recebido
    2. Em Triagem
```

Você pode inventar nomes, horários e status. O importante é a estrutura e o estilo.

## Dicas

- Não use `<div>` para tudo. Pense no papel de cada pedaço de informação.
- O status atual é a informação mais importante do card. Ele deve chamar atenção primeiro.
- A linha do tempo pode ser uma lista ordenada invertida ou simplesmente os dois últimos passos listados.

## Corrija Sua Atividade Com IA

```text
Estou estudando HTML semântico e CSS básico em uma trilha fullstack JavaScript/TypeScript.

Cenário da atividade:
- Preciso criar um card de status de atendimento para um portal de clínica veterinária.
- O card mostra nome do pet, espécie, nome do tutor, status atual, previsão de alta e uma linha do tempo com os dois últimos status anteriores.
- Os possíveis status são: Recebido, Em Triagem, Aguardando Aprovação, Em Procedimento, Pronto para Alta e Finalizado.

Tarefa:
- Avalie meu HTML e CSS baseado no que vou colar abaixo.
- Verifique se uso elementos semânticos adequados (article, header, section, ol, etc.).
- Verifique se o CSS destaca o status atual e diferencia os status anteriores.
- Aponte problemas de acessibilidade, como falta de contraste ou hierarquia confusa.

Critérios de correção:
1. HTML válido com lang, charset e viewport.
2. Pelo menos cinco elementos semânticos diferentes.
3. CSS separado do HTML.
4. Status atual com destaque visual claro.
5. Status anteriores com ênfase menor.
6. Layout legível e organizado.

[COLE SUA RESPOSTA AQUI]

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas específicas. Se eu estiver no caminho certo, sugira pequenos aperfeiçoamentos em vez de reescrever tudo.
```

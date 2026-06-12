# Exercício 03 — Lista de Atendimentos

## Objetivo

Praticar JavaScript no browser, manipulação do DOM e eventos criando uma lista interativa de atendimentos de uma clínica veterinária.

## Cenário

O painel interno do PetCare OS mostra a fila de atendimentos do dia. A recepcionista precisa visualizar os pets que chegaram e marcar qual está sendo atendido no momento, sem recarregar a página.

## Sua Tarefa

Crie três arquivos:

- `index.html` com a estrutura da página e uma lista de atendimentos.
- `styles.css` com o estilo da lista e do estado "em atendimento".
- `script.js` com a lógica de interação.

A lista deve conter pelo menos quatro atendimentos com:

1. Nome do pet.
2. Nome do tutor.
3. Motivo da visita.
4. Status atual.
5. Botão para marcar como "Em atendimento".

Ao clicar no botão:

- O item clicado deve receber uma classe visual indicando que é o atendimento atual.
- Os outros itens devem perder essa classe, garantindo que apenas um atendimento esteja marcado por vez.
- Uma mensagem resumida deve aparecer na tela, como "Thor está sendo atendido agora".

## Requisitos Mínimos

- [ ] HTML semântico com `<main>`, `<section>`, `<ul>`, `<li>`.
- [ ] Lista renderizada diretamente no HTML.
- [ ] CSS separado.
- [ ] JavaScript em arquivo separado, carregado com `defer`.
- [ ] Evento de clique atualizando o DOM.
- [ ] Apenas um item marcado como "Em atendimento" por vez.
- [ ] Mensagem atualizada sem recarregar a página.

## Exemplo de Estrutura Esperada

```text
Atendimentos do Dia

- Thor (Gabriel Rocha) — Emergência — Aguardando
  [Marcar em atendimento]
- Luna (Ana Souza) — Vacina — Aguardando
  [Marcar em atendimento]
- Simba (Carlos Lima) — Consulta — Aguardando
  [Marcar em atendimento]

Thor está sendo atendido agora.
```

## Dicas

- Use `querySelectorAll` para selecionar todos os botões e `classList` para adicionar/remover classes.
- Guarde a referência do item atualmente ativo para removê-lo antes de marcar o novo.
- Pense na acessibilidade: os botões devem ser navegáveis por teclado.

## Corrija Sua Atividade Com IA

```text
Estou estudando DOM e eventos no browser em uma trilha fullstack JavaScript/TypeScript.

Cenário da atividade:
- Preciso criar uma lista de atendimentos de clínica veterinária.
- Cada item da lista mostra nome do pet, nome do tutor, motivo da visita e status.
- Cada item tem um botão "Marcar em atendimento".
- Ao clicar no botão, apenas o item clicado deve ficar destacado como "Em atendimento".
- Os outros itens devem voltar ao estado normal.
- Uma mensagem na página deve indicar qual pet está sendo atendido no momento.

Tarefa:
- Avalie meu HTML, CSS e JavaScript baseado no que vou colar abaixo.
- Verifique se o JavaScript está em arquivo separado e carregado com defer.
- Verifique se uso addEventListener corretamente.
- Verifique se apenas um item fica marcado por vez.
- Verifique se a mensagem é atualizada no DOM sem recarregar a página.
- Aponte problemas de acessibilidade, como botões que não são focáveis ou falta de feedback visual.

Critérios de correção:
1. HTML semântico com lista ordenada ou não ordenada.
2. CSS separado.
3. JavaScript separado e carregado com defer.
4. Evento de clique atualizando classes no DOM.
5. Apenas um item ativo por vez.
6. Mensagem atualizada dinamicamente.

[COLE SUA RESPOSTA AQUI]

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas específicas. Se eu estiver no caminho certo, sugira pequenos aperfeiçoamentos em vez de reescrever tudo.
```

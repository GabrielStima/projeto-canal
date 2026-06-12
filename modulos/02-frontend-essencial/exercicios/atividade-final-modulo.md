# Atividade Final do Módulo — Portal do Tutor Navegável

## Objetivo

Combinar tudo o que você aprendeu no módulo para construir a primeira versão navegável do Portal do Tutor do PetCare OS, usando apenas HTML, CSS e JavaScript no browser.

## O Que Você Já Praticou

Durante este módulo, você trabalhou com:

- HTML semântico no exercício do card de status do pet.
- Formulários acessíveis no exercício de triagem.
- DOM e eventos no exercício da lista de atendimentos.
- CSS, layout, responsividade e acessibilidade nas aulas.

Agora você vai juntar essas peças em uma pequena experiência navegável.

## Sua Tarefa

Crie uma pasta `portal-do-tutor/` com três arquivos:

- `index.html`
- `styles.css`
- `script.js`

O portal deve ter pelo menos duas "telas" visíveis na mesma página, alternadas por navegação:

### Tela 1 — Status do Pet

Mostre um card com:

- Nome do pet e espécie.
- Nome do tutor.
- Status atual do atendimento.
- Previsão de alta ou mensagem de "sem previsão".
- Uma pequena linha do tempo com os dois últimos status.

### Tela 2 — Orçamento ou Histórico

Escolha uma das opções abaixo:

**Opção A — Orçamento Pendentes:**

- Lista de itens/procedimentos sugeridos.
- Valor total estimado.
- Botões "Aprovar" e "Recusar".
- Ao aprovar, mostre uma mensagem de confirmação.

**Opção B — Histórico Resumido:**

- Lista com data, procedimento e status de atendimentos anteriores.
- Pelo menos três registros.

Você pode inventar nomes, valores, datas e status. O importante é a estrutura e a navegação funcionarem.

## Requisitos Mínimos

- [ ] Navegação entre as telas usando links ou botões.
- [ ] HTML semântico (`header`, `nav`, `main`, `section`, `article`, etc.).
- [ ] CSS separado.
- [ ] Layout responsivo: legível em telas pequenas e grandes.
- [ ] JavaScript separado, carregado com `defer`.
- [ ] Alternância de telas feita com DOM e eventos, sem recarregar a página.
- [ ] Formulário ou interação funcional (aprovação de orçamento ou filtro simples de histórico).
- [ ] Labels, foco visível e contraste adequados.
- [ ] Nenhum framework.

## Sugestão de Organização

```text
portal-do-tutor/
├── index.html
├── styles.css
└── script.js
```

Dentro de `index.html`, você pode ter duas `<section>`: uma para o status e outra para orçamento/histórico. O JavaScript alterna a classe `ativa` entre elas.

## Dicas

- Faça primeiro o HTML completo das duas telas.
- Depois estilize a navegação e o layout.
- Por último, adicione o JavaScript para alternar entre as telas.
- Teste a navegação usando apenas o teclado.

## O Que Este Trabalho Se Torna Depois

Esta é a primeira versão do Portal do Tutor. Em módulos futuros de frontend moderno, você vai reconstruir essa mesma ideia com componentes reutilizáveis e rotas. Por isso, guarde esse trabalho em um lugar seguro.

## Corrija Sua Atividade Com IA

```text
Estou finalizando o módulo Frontend Essencial de uma formação fullstack JavaScript/TypeScript.

Cenário da atividade:
- Preciso criar a primeira versão navegável do Portal do Tutor de uma clínica veterinária.
- O portal deve ter pelo menos duas telas: uma com o status atual do pet e outra com orçamento pendente ou histórico de atendimentos.
- A navegação entre as telas deve ser feita com JavaScript, sem recarregar a página.
- Deve funcionar em telas pequenas e grandes.
- Não posso usar frameworks.

Tarefa:
- Avalie meu HTML, CSS e JavaScript baseado no que vou colar abaixo.
- Verifique se a navegação entre telas funciona via DOM e eventos.
- Verifique se o HTML é semântico.
- Verifique se o layout é responsivo.
- Verifique se há interação funcional (aprovação, filtro, etc.).
- Aponte problemas de acessibilidade, como falta de foco visível, labels ausentes ou baixo contraste.

Critérios de correção:
1. Duas telas distintas navegáveis.
2. HTML semântico com header, nav, main, section/article.
3. CSS separado e responsivo.
4. JavaScript separado, carregado com defer.
5. Alternância de telas sem recarregar a página.
6. Interação funcional em pelo menos uma tela.
7. Acessibilidade básica: labels, foco visível, contraste.

[COLE SUA RESPOSTA AQUI]

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas específicas. Se eu estiver no caminho certo, sugira pequenos aperfeiçoamentos em vez de reescrever tudo.
```

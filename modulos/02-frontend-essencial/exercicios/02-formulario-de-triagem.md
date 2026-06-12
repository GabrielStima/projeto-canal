# Exercício 02 — Formulário de Triagem

## Objetivo

Praticar formulários HTML, associação entre labels e campos, tipos de input adequados e validação nativa básica, tudo dentro de um contexto clínico realista.

## Cenário

Na recepção de uma clínica veterinária do PetCare OS, o recepcionista precisa registrar uma triagem inicial antes do pet ser atendido. Esse formulário não envia dados para lugar nenhum ainda — o objetivo é apenas estruturar bem os campos no browser.

## Sua Tarefa

Crie um arquivo `index.html` com um formulário de triagem e um arquivo `styles.css` para organizar visualmente os campos.

O formulário deve conter os seguintes campos:

1. Nome do tutor (obrigatório).
2. Telefone do tutor (obrigatório).
3. E-mail do tutor.
4. Nome do pet (obrigatório).
5. Espécie do pet: cachorro, gato, ave, réptil ou outro (campo de seleção).
6. Motivo da visita: consulta, vacina, emergência, retorno ou outro (campo de seleção).
7. Descrição dos sintomas ou motivo (área de texto).
8. Checkbox indicando se é um caso de urgência.
9. Botão de envio.

## Requisitos Mínimos

- [ ] Cada campo tem um `<label>` associado corretamente com `for` e `id`.
- [ ] Campos obrigatórios usam o atributo `required`.
- [ ] O campo de e-mail do tutor usa `type="email"` (se optar por incluí-lo).
- [ ] O campo de telefone do tutor usa `type="tel"` (se optar por incluí-lo).
- [ ] A espécie e o motivo da visita usam `<select>` com `<option>` claros.
- [ ] O campo de urgência usa `<input type="checkbox">`.
- [ ] O botão de envio usa `type="submit"`.
- [ ] O formulário tem um título semântico (`<h1>` ou `<h2>`).
- [ ] O CSS organiza os campos em uma coluna confortável para leitura.
- [ ] O CSS destaca visualmente o campo marcado como urgência.

## Exemplo de Estrutura Esperada

```text
Formulário de Triagem

Nome do tutor:  [________________]
Telefone:       [________________]
E-mail:         [________________]
Nome do pet:    [________________]
Espécie:        [v] Cachorro
Motivo:         [v] Emergência
Sintomas:       [                ]
                [                ]
[ ] Caso de urgência

[ Enviar Triagem ]
```

## Dicas

- Não use `placeholder` como substituto de `label`.
- Agrupe campos relacionados visualmente com espaçamento.
- O checkbox de urgência deve ser fácil de identificar. Pense em contraste e proximidade.

## Corrija Sua Atividade Com IA

```text
Estou estudando formulários HTML e acessibilidade básica em uma trilha fullstack JavaScript/TypeScript.

Cenário da atividade:
- Preciso criar um formulário de triagem para uma clínica veterinária.
- O formulário coleta nome do tutor, telefone, e-mail, nome do pet, espécie, motivo da visita, descrição dos sintomas e se é caso de urgência.
- Espécies possíveis: cachorro, gato, ave, réptil, outro.
- Motivos possíveis: consulta, vacina, emergência, retorno, outro.

Tarefa:
- Avalie meu HTML e CSS baseado no que vou colar abaixo.
- Verifique se cada campo tem label associado corretamente com for/id.
- Verifique se uso os tipos de input adequados.
- Verifique se a validação nativa está presente nos campos obrigatórios.
- Aponte problemas de semântica, acessibilidade ou organização visual.

Critérios de correção:
1. Labels associados a todos os campos.
2. Campos obrigatórios marcados com required.
3. Selects com opções claras.
4. Checkbox de urgência destacado visualmente.
5. Botão de submit semântico.
6. CSS organizado e legível.

[COLE SUA RESPOSTA AQUI]

Antes de apresentar uma resposta completa, destaque meus acertos, aponte imprecisões e ofereça dicas específicas. Se eu estiver no caminho certo, sugira pequenos aperfeiçoamentos em vez de reescrever tudo.
```

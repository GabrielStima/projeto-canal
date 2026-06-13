# Exercício 01 — Modelo Relacional do PetCare OS

Esta atividade é obrigatória para a continuidade do módulo. Você vai transformar os dados simulados do Portal do Tutor em um modelo relacional que será ampliado nos próximos exercícios.

## O Que Você Já Sabe

Nos módulos anteriores, você criou interfaces, rotas e formulários para pets e orçamentos. Agora você já sabe identificar entidades, atributos, relacionamentos, cardinalidades e campos obrigatórios.

## Sua Tarefa

Modele estas necessidades:

- um tutor pode ter vários pets;
- cada pet pertence a um tutor;
- um pet pode ter vários atendimentos;
- um atendimento possui um status e pode gerar um orçamento;
- um orçamento possui um ou mais itens;
- itens de orçamento podem referenciar serviços do catálogo.

Produza:

1. uma lista de entidades e responsabilidades;
2. os atributos essenciais de cada entidade;
3. os relacionamentos e suas cardinalidades;
4. a indicação de campos obrigatórios e opcionais;
5. um diagrama textual ou visual do modelo;
6. um arquivo `database/modelo-relacional.md` no projeto do PetCare OS.

Não inclua estoque, pagamentos ou prontuário detalhado nesta primeira versão. Eles podem aparecer em exemplos do módulo, mas não são necessários para concluir esta atividade.

## Critérios de Conclusão

- cada entidade possui um identificador;
- a relação entre tutor e pet está explícita;
- atendimento e orçamento têm responsabilidades diferentes;
- a relação entre orçamento e seus itens está representada;
- as cardinalidades são coerentes;
- o modelo não duplica os dados completos do tutor em cada pet.

Guarde o arquivo. No próximo exercício, esse modelo será transformado em tabelas, dados iniciais e consultas SQL.

## Corrija Sua Atividade Com IA

```text
Estou modelando a camada relacional do PetCare OS, uma plataforma para clínicas veterinárias.

Regras do cenário:
- um tutor pode ter vários pets;
- cada pet pertence a um tutor;
- um pet pode ter vários atendimentos;
- um atendimento possui status e pode gerar um orçamento;
- um orçamento possui um ou mais itens;
- itens podem referenciar serviços do catálogo.

Minha tarefa foi listar entidades, atributos, campos obrigatórios, relacionamentos e cardinalidades. Não preciso incluir estoque, pagamentos nem prontuário detalhado nesta versão.

Critérios de correção:
1. cada entidade deve possuir identificador;
2. tutor e pet devem ter uma relação um-para-muitos coerente;
3. atendimento e orçamento devem ter responsabilidades separadas;
4. orçamento e itens devem estar relacionados sem duplicação desnecessária;
5. campos obrigatórios e opcionais devem fazer sentido;
6. o modelo deve evitar copiar todos os dados do tutor em cada pet.

Analise minha resposta nesta ordem:
1. destaque os acertos;
2. aponte imprecisões ou relações ausentes;
3. faça perguntas que me ajudem a corrigir o modelo;
4. ofereça dicas antes de mostrar qualquer versão completa;
5. só apresente uma proposta completa se eu pedir depois de tentar corrigir.

[COLE SUA RESPOSTA AQUI]
```

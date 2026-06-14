# Exercício 03 — Testes de Integração

## O que você já sabe

Você já testou regras isoladas. Agora verificará se rota, validação, regra, repositório e banco funcionam juntos.

## Sua tarefa

Escolha um endpoint de escrita já existente. Configure ou planeje um banco de testes separado do ambiente de desenvolvimento.

Crie dois cenários:

1. uma requisição válida persiste os dados esperados;
2. uma requisição inválida ou conflitante não deixa estado incorreto.

Defina:

- como migrations ou schema serão preparados;
- como os dados iniciais serão criados;
- como cada teste ficará isolado;
- como o estado será limpo;
- como a resposta e o banco serão verificados;
- como dependências externas serão substituídas.

Use banco local, container ou outra opção isolada compatível com o projeto. A ferramenta não é o objetivo.

## O que você vai produzir

- configuração do ambiente de integração;
- dois testes executáveis ou plano detalhado;
- comando reproduzível;
- registro de duração e possíveis fontes de instabilidade.

## Critérios de conclusão

- O teste não usa o banco de desenvolvimento ou produção.
- A asserção verifica resposta e persistência.
- A limpeza não depende da ordem dos testes.
- Dependências externas reais não são chamadas.
- O cenário de falha confirma o estado final.

## Como este trabalho continuará

Esse ambiente será reutilizado na atividade final e no CI. Problemas de isolamento serão analisados no exercício sobre flakiness.

## Corrija Sua Atividade Com IA

```text
Cenário: Criei testes de integração para um endpoint de escrita usando uma API e um banco de testes isolado.

Tarefa: Avalie setup, isolamento, limpeza, asserções e tratamento de dependências externas.

Critérios de correção:
1. O banco de testes está separado dos demais ambientes?
2. Os testes independem de ordem e estado compartilhado?
3. Resposta HTTP e persistência são verificadas?
4. O caso de falha confirma que não ficou estado inválido?
5. Serviços externos foram substituídos sem simular a integração que está sendo testada?

Destaque os acertos, identifique imprecisões e ofereça dicas antes de propor uma configuração completa.

[COLE SUA RESPOSTA AQUI]
```

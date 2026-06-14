# Exercício 02 — Identidade, Rede e Fluxo

## O que você já tem

Seu documento cloud contém região, requisitos e responsabilidades iniciais.

## Tarefa

Acrescente um diagrama textual do caminho percorrido por:

- uma requisição do Portal do Tutor até a API;
- uma conexão da API com o banco;
- um worker consumindo uma mensagem;
- um upload para object storage.

Para cada trecho, informe:

1. origem e destino;
2. se o acesso precisa ser público ou privado;
3. porta ou protocolo em nível conceitual;
4. regra de rede necessária;
5. identidade utilizada;
6. permissões mínimas;
7. log de auditoria esperado.

O banco e serviços internos não devem ficar públicos apenas para facilitar o desenvolvimento.

## O que você vai produzir

Um mapa de tráfego e uma matriz de permissões que serão usados na topologia final.

## Corrija Sua Atividade Com IA

```text
Cenário: Desenhei o fluxo de tráfego de uma aplicação cloud entre cliente, API, banco, worker e object storage. Para cada conexão, defini exposição, protocolo, regra de rede, identidade, permissões mínimas e auditoria.

Tarefa: Revise meu mapa de rede e minha matriz de IAM.

Critérios de correção:
1. Somente os componentes que precisam receber tráfego externo estão públicos?
2. Banco, worker e serviços internos possuem caminhos privados ou controlados?
3. Identidades humanas e identidades de aplicação foram diferenciadas?
4. Cada identidade possui apenas as permissões necessárias?
5. As regras permitem o fluxo legítimo sem liberar acesso amplo?
6. Os eventos relevantes podem ser auditados?

Comece pelos acertos. Depois indique imprecisões, exposições e permissões excessivas. Dê dicas antes de apresentar uma topologia completa.

[COLE SUA RESPOSTA AQUI]
```

# Atividade Final Prática: Governança do Petcare

## O que você já tem

Sua Arquitetura Petcare OS foi modernizada. Tem nuvem, tem CI/CD e Observabilidade robusta. Agora você injeta o filtro da Legalidade Corporativa e Compliance LGPD/GDPR.

## A Tarefa

Neste **Marco Tático e Operacional de Governança N14**, você atua como DPO e Arquiteto-Chefe.
1. **O Banco de Dados:** Elabore uma rotina descritiva. Como seu backend executará rotinas noturnas para classificar Tabelas Mortas (Vencimento de Retenção de 5 anos estipulado pelo Governo)? Qual o comando lógico/arquitetural dessa automação de deleção hard?
2. **Logs Transparentes:** Demonstre (Em código ou pseudo-código limpo) a injeção do pacote `pino-redact` no Logger do Node.JS silenciando a Key de `{ cpf: "..." }` para sempre.
3. **Múltiplos Inquilinos de IA:** Como o SRE da equipe fará para garantir por escrito ou na AWS que seus logs gerados de PetCare não estejam treinando massivamente e enriquecendo a Base de Dados da OpenAI pública (Modelos Abertos) durante a Geração de Prompts do seu App Front-end?

## O que você vai produzir

- Uma refatoração mental e lógica dos seus projetos passados. Uma maturidade Sênior absoluta que foca no respeito ao cliente (Tutor do Pet) como base do desenvolvimento do seu produto final.

## Corrija Sua Atividade Com IA

```text
Cenário: A Defesa Estratégica Completa e Legal. Atingindo o Marco de Privacidade.

Tarefa: Segue meu Dossiê de Mudanças: O código do Pino, a Rotina de Limpeza Noturna de SQL e a Política do Provedor Nuvem AI contra scraping de Treinamento.

[COLE AQUI A SUA ESTRUTURA GERAL DA MUDANÇA]

Critérios de correção:
1. O filtro de censura (Redaction) englobou strings nativas JSON na memória antes de escrever no I/O e poupar os Loggers Cloud de indexarem crimes?
2. Cumpriu o estrito e obrigatório 'Zero Data Retention / Opt-Out of Training' da plataforma escolhida para os prompts do Petcare?

Assuma a persona do Head do Jurídico Tecnológico. Seja ácido ao procurar lacunas na minha retenção ou anonimização. Aprove minha mudança de arquitetura caso esteja impecável.
```

# Exercício 02 — Integração e Resiliência

## O Que Você Já Possui

Você definiu escopo, dados permitidos, alternativa sem IA e critérios para selecionar um modelo.

## A Tarefa

Projete e, se possível, implemente a fronteira de integração do assistente. Você pode usar uma API real, um modelo local ou um test double.

Registre em `docs/sistema-ia.md`:

1. interface TypeScript independente de provedor;
2. entrada mínima e sanitizada;
3. schema da saída, incluindo recusa e falta de evidência;
4. validação estrutural e regras de negócio fora do modelo;
5. adapter real ou fake;
6. versão de modelo e prompt registrada;
7. timeout e cancelamento;
8. política limitada de retry e backoff;
9. fallback determinístico ou mensagem de indisponibilidade;
10. tratamento de rate limit e resposta inválida;
11. estado efêmero necessário para a sessão;
12. dados que não serão persistidos;
13. isolamento por usuário ou tenant;
14. testes de sucesso, timeout, recusa e saída inválida;
15. métrica de latência e custo estimado sem conteúdo sensível.

Não repita automaticamente operações com efeito. Streaming pode melhorar a percepção de latência, mas a interface não deve tratar conteúdo parcial como resultado validado.

## O Que Você Vai Produzir

Um contrato de integração testável e resiliente, desacoplado do provedor.

Esse contrato será reutilizado por RAG, ferramentas, evals e pelo protótipo final.

## Corrija Sua Atividade Com IA

```text
Cenário: Projetei a integração de IA do PetCare OS com interface TypeScript, schema, estado e tratamento de falhas.

Tarefa: Revise meu contrato, validação, resiliência, privacidade e testes.

Critérios de correção:
1. O domínio não depende diretamente de um SDK específico.
2. Entrada e contexto são mínimos e autorizados.
3. A saída possui schema e validação de negócio.
4. Timeout, cancelamento, rate limit e retry possuem limites.
5. Existe fallback sem duplicar ações.
6. Estado e memória têm finalidade, isolamento e retenção definidos.
7. Testes simulam sucesso e falhas sem depender da API real.
8. Métricas não armazenam conteúdo sensível por padrão.

Primeiro destaque meus acertos. Depois aponte acoplamento, falhas perigosas ou persistência excessiva e ofereça dicas. Só apresente um desenho completo depois que eu revisar minha tentativa.

[COLE SUA RESPOSTA AQUI]
```

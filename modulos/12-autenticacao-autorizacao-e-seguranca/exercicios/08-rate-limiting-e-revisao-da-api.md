# Exercício 08 — Rate Limiting e Revisão da API

## O que você já sabe

Sua API já possui cadastro, login, autenticação, autorização e correções em fronteiras de entrada. Antes da integração final, você precisa limitar abuso e revisar os controles endpoint por endpoint.

## Sua tarefa

Escolha dois endpoints com perfis de abuso diferentes:

- `POST /api/auth/login`;
- outro endpoint sensível ou custoso já existente.

Para cada um, defina:

- chave do limite, como IP, usuário, token ou combinação;
- janela de tempo;
- quantidade permitida;
- resposta `429 Too Many Requests`;
- uso de `Retry-After`, quando aplicável;
- evento que será registrado sem incluir senha, token ou outro segredo;
- risco de bloquear usuários legítimos.

Implemente o limite no login ou produza pseudocódigo detalhado compatível com o framework atual.

Depois, atualize seu mapa de riscos e transforme-o em uma revisão por endpoint com estas perguntas:

1. o endpoint é público ou privado?
2. como autentica?
3. quem autoriza?
4. que entrada precisa ser validada?
5. que dado não deve sair?
6. que abuso precisa ser limitado?
7. que evento precisa ser registrado?

## O que você vai produzir

- rate limiting aplicado ou especificado para dois endpoints;
- exemplo de resposta `429`;
- revisão de segurança dos endpoints selecionados;
- versão final do `docs/security-review.md`.

## Critérios de conclusão

- O limite não usa a mesma regra para todos os endpoints.
- A estratégia não depende somente de IP sem avaliar redes compartilhadas.
- A resposta segue o padrão de erros da API.
- Logs não contêm credenciais ou tokens.
- O checklist relaciona cada controle ao endpoint correspondente.
- Riscos residuais e decisões ainda pendentes estão documentados.

## Como este trabalho continuará

O documento e a implementação serão usados diretamente na atividade final. No módulo 13A, o limite e os principais casos de rejeição poderão ser cobertos por testes.

## Corrija Sua Atividade Com IA

```text
Cenário: Defini rate limiting para o login e para outro endpoint sensível. Também concluí uma revisão de segurança por endpoint.

Tarefa: Avalie os limites, a resposta 429, os dados registrados e a cobertura do checklist.

Critérios de correção:
1. Chaves, janelas e quantidades correspondem ao risco de cada endpoint?
2. O desenho considera redes compartilhadas e bloqueios indevidos?
3. A resposta 429 segue um formato previsível e usa Retry-After quando adequado?
4. Logs evitam senhas, tokens e dados sensíveis?
5. O checklist cobre autenticação, autorização, entrada, saída, abuso e registro?
6. Riscos residuais foram reconhecidos?

Comece pelos acertos. Depois indique imprecisões, limites frágeis ou lacunas no checklist e ofereça dicas para eu revisar. Não entregue uma configuração completa antes da minha nova tentativa.

[COLE SUA RESPOSTA AQUI]
```

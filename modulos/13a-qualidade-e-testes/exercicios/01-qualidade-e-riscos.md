# Exercício 01 — Qualidade e Riscos

## Tarefa

Escolha três funcionalidades que você implementou ou planeja implementar no Módulo de Prontuários do PetCare OS.
Para cada uma, escreva uma métrica teórica (ou observação) de **Qualidade Externa**, **Interna** e **Operacional**.

Exemplo com "Criar Prontuário":
- **Externa:** O veterinário consegue preencher sem as telas travarem, em menos de 2s.
- **Interna:** O código do controller e do repositório estão separados, permitindo que eu mude o banco de dados amanhã sem alterar a lógica do veterinário.
- **Operacional:** Se a inserção no banco falhar, um log estruturado emite um Error Trace alertando a engenharia de que há falha de gravação ativa.

## Corrija Sua Atividade Com IA

```text
Cenário: Estou mapeando os eixos de Qualidade (Externa, Interna, Operacional) do PetCare OS.

Tarefa: Escrevi o mapeamento abaixo para três funcionalidades:
1. ...
2. ...
3. ...

Critérios de correção:
1. O que foi listado como qualidade externa é de fato percebido pelo usuário final?
2. A qualidade interna mapeia testabilidade, coesão, ou métricas de código?
3. A qualidade operacional foca na resiliência e investigabilidade (como monitoramento)?

[COLE SUA RESPOSTA AQUI]

Por favor, analise as minhas escolhas. Corrija alguma interpretação errada e me dê um caso real de como uma dessas três funcionalidades poderia falhar catastroficamente se a qualidade operacional fosse ignorada.
```

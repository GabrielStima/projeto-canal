# Exercício 11 — Segurança na Arquitetura

## Tarefa

Seja um Sênior projetando Camadas ISO-OSI contra invasões em massa e terrorismo digital nas Clínicas de Animais da cidade: O atacante percebeu que um ataque burro na Camada de Rede 3 (DDoS no TCP tentando fechar a porta com milhões de pings) é facilmente segurado pelos escudos da Amazon Shield/CloudFlare e resolve rodar um **Layer 7 Application Flood Attack** super inteligente: Um ataque massivo em bots distribuídos que tenta dar "Submit" num Formulário "Fale Conosco" pesado que carrega muito PHP e Gravação SQL, disfarçado de tráfego comum HTTPS perfeito. Como o `WAF (Web Application Firewall)` na borda atua cortando gargantas antes desse golpe atingir a VPC Interna e sua aplicação crua do App.js?

## Corrija Sua Atividade Com IA

```text
Cenário: Engenharia Ofensiva Camada 7 / Volumetria, Defesa Perimetral WAF (Rate Limits + IP Reputations).

Tarefa: Aqui ataco a periculosidade de falhas não impedidas na borda (Edge) e protejo com WAF na Planta do Sistema (Diagrama Cloud):
[COLE AQUI]

Critérios de correção:
1. Pontuei perfeitamente que o Load Balancer e AWS Shield enxergam apenas Tráfego Lícito e Legal e não bloqueiam (Pois é porta 443)?
2. Indiquei os filtros sintéticos poderosos do WAF que analisam IPs botnets conhecidos, Inspecionam Headers HTTP de User-Agents mentirosos, e disparam bloqueios de Limit-rate automáticos pra o cliente sem pesar no seu Kubernetes no final?
```

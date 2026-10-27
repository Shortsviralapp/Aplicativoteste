---
name: upwork-preco
description: Define o lance de uma vaga do Upwork na média do mercado para reduzir disputa por preço. Use quando o usuário colar uma vaga, um orçamento, a média de lances, "quanto cobro", "qual lance", ou dados de propostas do Upwork.
---

# Agente de preço — Upwork

Objetivo: o preço nunca pode ser o motivo de o cliente ignorar a proposta. O lance fica **na média** da vaga, nunca muito acima.

## Dados que você pede (só o que faltar)
1. Tipo de contrato: horário ou valor fixo.
2. Orçamento do cliente (faixa ou valor fixo).
3. Média de lances da vaga. O Upwork mostra em "Bid range" ou, depois do envio, em "Avg bid".
4. Número de propostas já enviadas ("Proposals: 5 to 10").
5. Gasto total e taxa de contratação do cliente.

Se o usuário não tiver o item 3, estime pela faixa de orçamento e diga que é uma estimativa.

## Regra de preço
- **Base = média dos lances.** Sem média, use o ponto médio do orçamento.
- Até 5 propostas e cliente com gasto acima de US$ 10k: até **+5%** da base.
- Mais de 15 propostas: **-5%** da base para entrar na disputa.
- Teto: o máximo do orçamento do cliente. Nunca passe dele.
- Piso: **US$ 22/h** ou **US$ 120 por vídeo**. Abaixo disso, não proponha e recomende pular a vaga.
- Valor fixo: arredonde para um número "limpo" (US$ 250, 300, 450). Nada de US$ 287.
- Projeto grande: sugira um **primeiro marco menor** (1 vídeo-teste). Assim o "sim" fica barato e o preço cheio vem depois.

## Saída (curta)
```
Lance: US$ X  (líquido após 15%: US$ Y)
Por quê: base US$ B · ajuste +/-N% (motivo em 5 palavras)
Marco inicial sugerido: US$ M — <entrega>
Pular? sim/não — <motivo, se sim>
```

Preço **não vai no texto da proposta**. Ele fica só no campo de lance.

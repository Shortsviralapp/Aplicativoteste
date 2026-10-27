---
name: upwork-proposta
description: Escreve propostas curtas para Upwork em inglês, com tom humano e profissional, sem cara de IA. Use quando o usuário colar uma vaga do Upwork, pedir "cover letter", "proposta", "resposta para cliente", ou quiser revisar uma proposta.
---

# Agente de proposta — Upwork

A conversa com o usuário é em português. **A proposta é sempre em inglês.** Ela tem **60 a 110 palavras**: curta vence longa.

## Ativos (use só se servirem à vaga, no máximo 1 ou 2)
- Portfólio: creatormateusai.com
- UGC ads: testimonial, unboxing, demo
- Montreux Nestlé Open: peça comercial de marca
- Série de personagem de IA: 72M views em 4 meses. Use só em vaga de personagem ou série.
- Assinatura: Mateus

Nunca invente número, cliente ou resultado.

## Estrutura (4 linhas curtas)
1. **Primeira frase = resposta direta à vaga + prova.** Os primeiros ~200 caracteres são tudo o que o cliente vê. Exemplo: "Here's a UGC ad close to what you described: [link]."
2. **Um detalhe que prova que você leu a vaga.** Cite o produto, o formato ou o prazo dele.
3. **Como você faria**, em uma frase concreta: o quê + em quanto tempo.
4. **Uma pergunta simples** que dê vontade de responder. Depois, "— Mateus".

Responda tudo o que o anúncio pede: "send samples", "tell me your tools", palavra-código etc.

## Proibido (soa IA ou vendedor)
- Aberturas: "I hope this message finds you well", "Dear Hiring Manager", "I came across your job", "As an AI video expert".
- Palavras: delve, leverage, seamless, elevate, cutting-edge, passionate, dedicated, tailored, unlock, game-changer, "I'd love to".
- Travessões em excesso, listas com emoji, negrito, três adjetivos seguidos.
- Repetir a vaga para o cliente, falar de preço, "available immediately", "I'm confident".

## Tom
Escreva como um profissional ocupado escreve no Slack: frases curtas, contrações (I'm, I'll, you're), verbos concretos. Uma ideia por frase. Se uma frase pode sair sem perder nada, tire.

## Checagem final (faça antes de entregar)
- [ ] A primeira linha tem link ou prova?
- [ ] Tem entre 60 e 110 palavras?
- [ ] Nenhuma palavra da lista proibida?
- [ ] Cada pedido do anúncio foi respondido?
- [ ] Termina com pergunta?

## Entrega
Mostre a proposta pronta para colar e, abaixo, **uma variação alternativa** de primeira linha. Se o usuário colar também os dados de preço, rode antes a skill `upwork-preco` e mostre o lance junto.

### Exemplo
> Here's a UGC unboxing I made for a skincare brand, close to what you're after: creatormateusai.com
>
> You mentioned 4 videos for TikTok with a female creator around 30. I'd keep the same AI creator across all four, so it reads like one real person using the product.
>
> I can send the first one in 3 days for your feedback before doing the rest.
>
> Do you already have the scripts, or should I draft the hooks too?
>
> — Mateus

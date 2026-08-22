# Provedores com free tier
> verificado em ago/2026 — números conferidos nas páginas oficiais. Free tier muda todo mês: se o número e a página oficial divergirem, acredite na página.

## Free permanente (sem cartão)

| Provedor | O que entra grátis | Limites do free tier | Link oficial |
|----------|--------------------|----------------------|--------------|
| Google AI Studio | Gemini 3 via API key grátis | Flash: ~15 req/min, ~1,5K req/dia, 1M tokens/min; Pro bem mais restrito. Número exato por modelo no console | [ai.google.dev/gemini-api/docs/rate-limits](https://ai.google.dev/gemini-api/docs/rate-limits) |
| Groq | llama, gpt-oss-120b/20b, qwen, whisper | ~30 req/min; até **14,4K req/dia** nos modelos pequenos, 1K req/dia nos grandes; ~200K tokens/dia | [console.groq.com/docs/rate-limits](https://console.groq.com/docs/rate-limits) |
| OpenRouter | centenas de modelos com sufixo `:free` | 20 req/min; **50 req/dia** — sobe para **1.000 req/dia** com ≥US$10 em créditos já comprados (aporte único, não gasto recorrente) | [openrouter.ai/docs/api-reference/limits](https://openrouter.ai/docs/api-reference/limits) |
| Cloudflare Workers AI | modelos abertos na edge | 10K neurons/dia | [developers.cloudflare.com/workers-ai/platform/pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/) |
| Mistral | plano Free (consumer): **US$10/mês em créditos de API** + modelos gratuitos (Leanstral, Mistral Moderation 2) | ver condições do plano | [mistral.ai/pricing](https://mistral.ai/pricing) |

## Créditos de avaliação (exigem cartão, acabam)

| Provedor | O que dá | Pegadinha | Link oficial |
|----------|----------|-----------|--------------|
| Cerebras | trial de US$5 por 30 dias; gpt-oss-120b e gemma-4-31b a 5 req/min, 30K tokens/min, 1M tokens/dia | exige método de pagamento verificado; **não há free tier permanente** — acabou o crédito, acabou o acesso | [inference-docs.cerebras.ai/support/rate-limits](https://inference-docs.cerebras.ai/support/rate-limits) |

## Aposentados no caminho

- **GitHub Models** — desligado em 30/07/2026 (playground, catálogo e API). Quem usava migrou para Azure AI Foundry (pago) ou para os free tiers acima. Se um blog de 2025 ainda recomenda, o blog está velho.

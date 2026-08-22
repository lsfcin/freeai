# Modelos open-weights e onde rodar de graça
> verificado em ago/2026 — pesos abertos = você pode rodar local (para sempre, no seu hardware) ou achar hospedagem grátis. "Onde de graça" remete aos provedores de [provedores.md](provedores.md).

| Modelo | Licença | Pontos fortes | Onde rodar grátis |
|--------|---------|---------------|-------------------|
| gpt-oss-120b / 20b (OpenAI) | Apache 2.0 | modelos abertos com raciocínio da OpenAI; o 20b roda em ~16GB de VRAM | Groq (1K req/dia), Cerebras (trial), local |
| Qwen3 + Qwen3-Coder (Alibaba) | Apache 2.0 | família completa (0.6B a 235B+), o Coder é ponta em código | Groq (qwen 27b), OpenRouter `:free`, local |
| GLM-4.6 / GLM-4.5 (Z.ai) | MIT | forte em código e tool-use, favorito de setups de agente | local; variantes `:free` no OpenRouter aparecem e somem — conferir o catálogo |
| DeepSeek V3.x / R1 | MIT | raciocínio barato e bom, pesos notoriamente permissivos | OpenRouter `:free`, local (quantizado) |
| Llama 4 / 3.3 (Meta) | Llama Community | onipresente: todo provedor hospeda alguma variante | Groq, OpenRouter `:free`, local |
| Kimi K2 (Moonshot) | MIT modificado | MoE de 1T parâmetros, orientado a agentes | local (quantizado; pede hardware grande) |
| Gemma 4 / 3 (Google) | Gemma | pequeno, eficiente, bom para máquina modesta | Cerebras (gemma-4-31b, trial), AI Studio, local |

## Runtimes locais — o free tier que ninguém corta

- **Ollama** — [ollama.com](https://ollama.com) — `ollama run qwen3-coder` e pronto; roda até em CPU, melhora com GPU.
- **LM Studio** — [lmstudio.ai](https://lmstudio.ai) — interface gráfica, catálogo do Hugging Face, e serve um endpoint OpenAI-compatível que qualquer harness BYO key entende.

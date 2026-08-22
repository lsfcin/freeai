# freeai
> Harness + provedor + modelo sem pagar nada: tabelas comparativas das opções gratuitas de IA para codar, com limites reais e links oficiais.

## Como ler

São quatro tabelas, cada linha com link oficial e cada tabela com carimbo de verificação. Free tier muda todo mês — a data importa mais que o número. E "grátis" tem três camadas distintas que a gente mistura sem querer: a licença do software, a cota de requests e o modelo (pesos abertos).

- [harnesses.md](harnesses.md) — agentes de terminal (Gemini CLI, OpenCode, Aider…)
- [ide.md](ide.md) — extensões de editor (Cline, Roo Code, Kilo Code, Continue, Copilot)
- [provedores.md](provedores.md) — free tiers de API (Groq, OpenRouter, AI Studio…)
- [modelos.md](modelos.md) — open-weights e runtimes locais (gpt-oss, Qwen3, GLM, Ollama)

## Quick pick — verificado em ago/2026

| Perfil | Stack | Por quê |
|--------|-------|---------|
| Quero que funcione hoje | Gemini CLI + conta Google | 60 req/min e 1.000 req/dia sem API key; Gemini 3 com contexto de 1M |
| Volume alto de requests | OpenCode + Groq | até 14,4K req/dia nos modelos pequenos (teto de ~200K tokens/dia) |
| Variedade de modelos | OpenCode ou Aider + OpenRouter `:free` | centenas de modelos; 50 req/dia, sobe pra 1.000/dia com um aporte único de US$10 |
| Sem configurar nada | Copilot Free (extensão + Copilot CLI) | 2.000 completions/mês com a conta GitHub que você já tem |
| Prefiro IDE ao terminal | Cline + OpenRouter `:free` ou Groq | BYO key: a extensão é grátis, a cota vem do provedor |
| Zero nuvem | Ollama + gpt-oss-20b ou Qwen3 | ilimitado no seu hardware — o único free tier que ninguém corta |

## Lições que valem mais que os números

- **Cota grátis morre.** A de 2.000 req/dia do Qwen Code (anunciada ago/2025) acabou em abr/2026; o GitHub Models foi desligado em jul/2026. Desconfie de qualquer lista sem carimbo de data.
- **Software grátis não é uso grátis.** OpenCode e Aider são livres, mas a conta vem do provedor de modelo — a menos que o provedor tenha free tier.
- **Trial não é free tier.** Cerebras dá US$5 por 30 dias e exige cartão; [provedores.md](provedores.md) separa os dois mundos.

## Contribuir

PR bem-vindo: número novo entra com link oficial e carimbo atualizado. Número sem fonte oficial não entra — free tier de blog aggregator é ruído um mês depois.

## License

MIT — veja [LICENSE](LICENSE).

---
[CONTEXT.md](CONTEXT.md) · [ROADMAP.md](ROADMAP.md) · [harnesses.md](harnesses.md) · [ide.md](ide.md) · [provedores.md](provedores.md) · [modelos.md](modelos.md)

# Harnesses de CLI
> verificado em ago/2026 — "grátis" aqui tem três camadas: a licença do software, a cota de requests e o modelo. A tabela diz qual camada é grátis em cada um.

| Harness | Licença | O que dá de graça | Provedores | Destaque | Link |
|---------|---------|-------------------|------------|----------|------|
| Gemini CLI | Apache 2.0 | **60 req/min e 1.000 req/dia** com conta Google pessoal (login OAuth, sem API key) — Gemini 3, contexto de 1M | Gemini (OAuth ou API key) | O free tier mais generoso entre os agentes oficiais de fabricante | [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) |
| OpenCode | MIT | Software grátis, com "free models included" no gateway próprio — e aceita o free tier de qualquer provedor | 75+, BYO key | TUI com sessões paralelas; o agente open source mais popular | [opencode.ai](https://opencode.ai) |
| Aider | Apache 2.0 | Software grátis; usa o free tier do provedor que você conectar | qualquer API OpenAI-compatível, BYO key | Git-native (commit por edição), repomap para repositórios grandes, econômico em tokens | [aider.chat](https://aider.chat) |
| Qwen Code | Apache 2.0 | Software grátis — mas a cota OAuth de 2.000 req/dia **acabou em abr/2026**; hoje exige BYO key ou coding plan pago | OpenAI, Anthropic, Gemini, Qwen, local (Ollama/vLLM) | Nasceu de um fork do Gemini CLI, otimizado para Qwen3-Coder | [github.com/QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) |
| Codex CLI | Apache 2.0 | Software grátis; o uso depende de login ChatGPT (cota varia com o plano) ou API key paga | OpenAI (login ou API key) | Agente oficial OpenAI, integrado à plataforma ChatGPT | [learn.chatgpt.com/docs/codex/cli](https://learn.chatgpt.com/docs/codex/cli) |
| Copilot CLI | proprietário | **Copilot Free**: 2.000 completions/mês + cota de chat (GitHub AI Credits); inclui o Copilot CLI | GitHub (sem BYO key) | Zero configuração para quem já vive no GitHub | [docs.github.com/copilot](https://docs.github.com/en/copilot/get-started/plans) |
| Goose | Apache 2.0 | Software grátis; BYO key — fica grátis na prática com provedor de free tier | vários, BYO key + MCP | Extensível via MCP, mantido pela Block | [github.com/block/goose](https://github.com/block/goose) |
| Crush | FOSS | Software grátis; BYO key | vários, BYO key | TUI do Charm, das ferramentas bonitas de terminal | [github.com/charmbracelet/crush](https://github.com/charmbracelet/crush) |

A lição do Qwen Code vale para a tabela toda: cota grátis nasce e morre em meses — o carimbo de data desta linha vale mais que o número dela. Antes de escolher harness pelo free tier, cheque o link da linha.

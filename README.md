## Hi, I'm yunbow

I build **[AI Dev OS](https://github.com/yunbow/ai-dev-os)** — an open framework that turns tacit developer knowledge into explicit, enforceable rules for AI coding assistants.

**The problem:** AI generates code that looks correct but violates your team's conventions, security practices, and architectural patterns. Loading more guidelines into context actually degrades output quality.

**The solution:** A layered rule architecture (Lifespan Layers) with a two-tier context strategy — 3-5 static rules during generation + comprehensive check & fix after generation. [Benchmark: 96.9/100](https://github.com/yunbow/ai-dev-os-benchmark).

### Quick Start

```bash
npx ai-dev-os init
```

### Ecosystem

| Repository | What it does |
|---|---|
| [ai-dev-os](https://github.com/yunbow/ai-dev-os) | Core framework — Lifespan Layers, Specificity Cascade, theory |
| [rules-typescript](https://github.com/yunbow/ai-dev-os-rules-typescript) | TypeScript / Next.js coding guidelines (L1–L3) |
| [rules-python](https://github.com/yunbow/ai-dev-os-rules-python) | Python / FastAPI coding guidelines (L1–L3) |
| [plugin-claude-code](https://github.com/yunbow/ai-dev-os-plugin-claude-code) | Claude Code — Skills, Agents, Hooks |
| [plugin-cursor](https://github.com/yunbow/ai-dev-os-plugin-cursor) | Cursor — .mdc rules |
| [plugin-kiro](https://github.com/yunbow/ai-dev-os-plugin-kiro) | Kiro — Steering Rules, Hooks |
| [cli](https://github.com/yunbow/ai-dev-os-cli) | `npx ai-dev-os init` — one-command setup |
| [benchmark](https://github.com/yunbow/ai-dev-os-benchmark) | Quantitative impact data — guideline effect on code quality |

75% of rules survive tool migrations. Switch between Claude Code, Cursor, and Kiro freely.

### Writing

- [Dev.to: AI Dev OS (English)](https://dev.to/yunbow/ai-dev-os-m4i)
- [Zenn: AI Dev OS (Japanese)](https://zenn.dev/yun_bow/scraps/4677df6cc83625)
- [Qiita: AI Dev OS (Japanese)](https://qiita.com/yun_bow/stocks/9dd1be4d8e04f9c5a58e)

[Zenn](https://zenn.dev/yun_bow) · [Qiita](https://qiita.com/yun_bow) · [X](https://x.com/yun_bow)

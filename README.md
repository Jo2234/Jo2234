# Johan Vaz

I build AI systems for financial research and risk — the unglamorous machinery that decides whether an AI tool is trustworthy or just fluent: eval harnesses, cited retrieval over SEC filings, and risk analytics that explain themselves.

Computer Science + Quantitative Finance at NUS. Based in Singapore.

**Site:** [johan-vaz-site.vercel.app](https://johan-vaz-site.vercel.app) — several projects below are deployed and clickable, not just readable.

**Currently:** looking for internships or junior roles in AI agents, LLM evaluation, fintech, or quant research tooling — ideally on a small team that ships.

## Selected work

| Project | What it is |
| --- | --- |
| [AI Equity Research Copilot](https://github.com/Jo2234/ai-equity-research-copilot) | Document-grounded research over SEC filings: EDGAR ingestion, chunk-level cited retrieval, structured memos — plus a finance QA eval set so citation precision, refusals, and hallucination risk are measured, not assumed. |
| [Financial LLM Eval Harness](https://github.com/Jo2234/financial-llm-eval-harness) | 50-case evaluation suite for financial QA systems: factual extraction, multi-document synthesis, refusal behavior, adversarial prompts, scoring, and regression reports. |
| [Curio](https://github.com/Jo2234/curio) | Learning-by-teaching, instrumented: teach an AI novice by voice, reasoning agents map your claims against a curriculum, then the novice teaches it back using only what it learned from you. |
| [FluentAI](https://github.com/Jo2234/FluentAI) | Agentic language tutor with adaptive lessons, evaluator/memory agents, real-time speech, and spaced repetition driven by actual conversation mistakes. |
| [finance-labs](https://github.com/Jo2234/finance-labs) | A toolkit of small, offline, test-covered risk and market-structure diagnostics: margin cascades, ETF liquidity stress, option skew, factor crowding, covenant headroom, and more. **[Live results gallery →](https://finance-labs-showcase.vercel.app)** |
| [US Market Regime Dashboard](https://github.com/Jo2234/us-market-regime-dashboard) | Macro/risk context dashboard with transparent regime rules, data-freshness checks, and exports. FastAPI + React. **[Live →](https://market-regime-dashboard-mu.vercel.app)** |
| [Portfolio Risk Copilot](https://github.com/Jo2234/portfolio-risk-copilot) | API-first portfolio risk: VaR, expected shortfall, correlations, concentration flags, stress tests, plain-English commentary. **[Live →](https://portfolio-risk-copilot-pi.vercel.app)** |

## How I work

- **Grounded, or it doesn't ship.** Generated claims trace to source chunks; when evidence is weak, the system refuses — and that behavior is tested like a feature.
- **Evaluated, not vibe-checked.** I build the eval harness before trusting the output: golden sets, regression scoring, adversarial cases.
- **Honest about failure modes.** Finance punishes overconfidence, so I document where tools break and what they must not do.

## Contact

- Email: v.johan2234@gmail.com
- LinkedIn: [sg.linkedin.com/in/johan-vaz](https://sg.linkedin.com/in/johan-vaz)

# Johan Vaz

I build evaluated AI systems and financial research tools: cited retrieval over SEC filings, financial QA evaluation, and risk analytics with inspectable inputs and calculations.

Computer Science + Quantitative Finance at NUS. Based in Singapore.

**Site:** [johan-vaz-site.vercel.app](https://johan-vaz-site.vercel.app) — several projects below are deployed and clickable, not just readable.

**Currently:** looking for internships or junior roles in AI agents, LLM evaluation, fintech, or quant research tooling — ideally on a small team that ships.

## Merged open-source contributions

- **[Apache Arrow — more reliable numerical data imports](https://github.com/apache/arrow-rs/pull/11105).** Fixed CSV values such as `+1` and `+1.5` being mistaken for text; added tests for valid numbers, overflow, and malformed input. Reviewed and merged into the official Rust implementation on 17 September 2026.

- **[Apache Arrow — faster selection for fragmented masks](https://github.com/apache/arrow-rs/pull/10368).** Added adaptive dispatch to the existing interleave kernels while preserving null handling and the contiguous-mask path. The PR's 8,192-row i32 benchmark recorded 76.889 µs → 33.676 µs, a 56.2% reduction in execution time for that workload.
- **[bt — integer allocation with nonlinear commissions](https://github.com/pmorissette/bt/pull/530).** Fixed a search that skipped an affordable share quantity and raised an error; added a regression for minimum, per-share, and capped commissions.
- **[ffn — multi-period annualization](https://github.com/pmorissette/ffn/pull/304).** Corrected frequency inference that inflated annualized ratios for 30-minute data, with coverage of the resulting Sharpe calculation.

The linked PRs contain the implementation, review discussion, validation, and any AI-assistance disclosures. Benchmark results apply to the recorded workloads and environment.

## Selected projects

| Project | What it is |
| --- | --- |
| [AI Equity Research Copilot](https://github.com/Jo2234/ai-equity-research-copilot) | Document-grounded research over SEC filings: EDGAR ingestion, chunk-level cited retrieval, structured memos — plus a finance QA eval set so citation precision, refusals, and hallucination risk are measured, not assumed. |
| [Financial LLM Eval Harness](https://github.com/Jo2234/financial-llm-eval-harness) | 50-case evaluation suite for financial QA systems: factual extraction, multi-document synthesis, refusal behavior, adversarial prompts, scoring, and regression reports. |
| [Curio](https://github.com/Jo2234/curio) | Learning-by-teaching, instrumented: teach an AI novice by voice, reasoning agents map your claims against a curriculum, then the novice teaches it back using only what it learned from you. |
| [FluentAI](https://github.com/Jo2234/FluentAI) | Agentic language tutor with adaptive lessons, evaluator/memory agents, real-time speech, and spaced repetition driven by actual conversation mistakes. |
| [finance-labs](https://github.com/Jo2234/finance-labs) | A toolkit of small, offline, test-covered risk and market-structure diagnostics: margin cascades, ETF liquidity stress, option skew, factor crowding, covenant headroom, and more. **[Live results gallery →](https://finance-labs-showcase.vercel.app)** |
| [US Market Regime Dashboard](https://github.com/Jo2234/us-market-regime-dashboard) | Macro/risk context dashboard with transparent regime rules, data-freshness checks, and exports. FastAPI + React. **[Live →](https://market-regime-dashboard-mu.vercel.app)** |

## Contact

- Email: v.johan2234@gmail.com
- LinkedIn: [sg.linkedin.com/in/johan-vaz](https://sg.linkedin.com/in/johan-vaz)

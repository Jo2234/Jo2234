# Johan Vaz

I build evaluated AI systems and financial research tools (cited retrieval over SEC filings, financial QA evals, inspectable risk analytics), and I contribute to open-source tools, with merged work in T3 Code and Apache Arrow.

NUS Computer Science with a Quantitative Finance minor; graduating May 2029. Based in Singapore. Authorized to work in Singapore. Looking for a 2027 internship, remote preferred, especially with small teams that build with coding agents: **either 15–20 h/week Jan–Jun 2027 alongside classes, or full-time May–July 2027**.

**Site:** [johan-vaz-site.vercel.app](https://johan-vaz-site.vercel.app)

## Merged open-source contributions

- **[T3 Code — 10 merged fixes to an AI coding-agent app](https://github.com/pingdotgg/t3code/pulls?q=is%3Apr+author%3AJo2234+is%3Amerged).** Reliability and usability fixes across the web client, CLI, provider and source-control integrations. Examples: opening files from [Claude and ACP tool-call diffs](https://github.com/pingdotgg/t3code/pull/29309), restoring [long-path file suggestions on web and mobile](https://github.com/pingdotgg/t3code/pull/30714), and preserving [empty replacements in OpenCode edits](https://github.com/pingdotgg/t3code/pull/30643).
- **[Apache Arrow — numerical CSV imports](https://github.com/apache/arrow-rs/pull/11105).** Fixed `+1` and `+1.5` being inferred as text; added regression coverage for valid numbers, overflow, and malformed signs. Merged into the Rust implementation on 17 September 2026.
- **[Apache Arrow — fragmented-mask selection](https://github.com/apache/arrow-rs/pull/10368).** Added adaptive dispatch to interleave kernels, preserving null handling and the contiguous-mask path. The PR's 8,192-row i32 benchmark with random 50%-true masks recorded 76.889 µs → 33.676 µs: 56.2% less execution time for that workload.
- **[bt — integer allocation with nonlinear commissions](https://github.com/pmorissette/bt/pull/530).** Fixed a search that skipped an affordable share quantity and raised an error; added a regression for minimum, per-share, and capped commissions.
- **[ffn — multi-period annualization](https://github.com/pmorissette/ffn/pull/304).** Corrected frequency inference that inflated annualized ratios for 30-minute data, with Sharpe regression coverage.

I use AI coding tools. The linked PRs contain the implementation, review discussion, validation, and AI-assistance disclosures where applicable. Benchmark results apply to the recorded workloads and environment.

## Selected projects

| Project | What it is |
| --- | --- |
| [AI Equity Research Copilot](https://github.com/Jo2234/ai-equity-research-copilot) | SEC EDGAR ingestion, chunk-level cited retrieval, and structured research memos; a synthetic finance QA suite checks citations, refusals, and unsupported claims. |
| [Financial LLM Eval Harness](https://github.com/Jo2234/financial-llm-eval-harness) | 50-case financial QA suite covering factual extraction, synthesis, refusals, and adversarial prompts, with scoring and regression reports. |
| [Curio](https://github.com/Jo2234/curio) | Teach an AI novice by voice or text; curriculum-grounded claim checks, spoken teach-back, and an inspectable learning report. |
| [FluentAI](https://github.com/Jo2234/FluentAI) | Language-learning demo with adaptive lessons, conversation, persistent learner memory, and spaced review. |
| [finance-labs](https://github.com/Jo2234/finance-labs) | Offline Python risk and market-structure diagnostics using transparent synthetic scenarios. [Results gallery](https://finance-labs-showcase.vercel.app). |
| [US Market Regime Dashboard](https://github.com/Jo2234/us-market-regime-dashboard) | Macro/risk dashboard with documented regime rules, source-freshness checks, and exports. [Live dashboard](https://market-regime-dashboard-mu.vercel.app). |

## Contact

- Email: v.johan2234@gmail.com
- LinkedIn: [sg.linkedin.com/in/johan-vaz](https://sg.linkedin.com/in/johan-vaz)

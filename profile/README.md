<div align="center">
<img src="https://raw.githubusercontent.com/automatiabcn/.github/main/profile/logo.png" alt="Automatia BCN" width="120" height="120"/>

# Automatia BCN
**Automate the Chaos**
</div>

## Who we are

Automatia BCN is a founder-led software company, founded in Barcelona and now based in Perth, Australia ([Enes Eserkan](https://github.com/enzoemir1)). We build AI developer tooling and automation products — self-hosted by default, so the code and data stay under the user's control.

## ABS Studio

An AI code editor (VS Code fork) with a self-hosted orchestration server. Your code stays where it is; the editor talks to a server you run.

- Proposed edits are graded by a judge model before you see them — score and reasoning, not a diff on faith.
- A code graph shows the blast radius of a change before it lands.
- Checks run in the OS's own sandbox and report honestly — a check that didn't run is never shown as passed.
- Checkpoint-based undo and commits that carry evidence of what was graded and what ran.

Repo: [automatiabcn/abs](https://github.com/automatiabcn/abs) — source-available (BUSL-1.1), CI + CodeQL + nightly Lighthouse, 2,600+ tests. Downloads and pricing: [automatiabcn.com](https://automatiabcn.com).

## Open source

MIT, TypeScript, tests and CI.

| Project | What it does |
|---|---|
| [leadpipe-mcp](https://github.com/automatiabcn/leadpipe-mcp) | Lead qualification — ingest, enrich, score, export to CRM |
| [invoiceflow-mcp](https://github.com/automatiabcn/invoiceflow-mcp) | Invoice automation — PDF invoices, late-payment risk, cash flow |
| [shopops-mcp](https://github.com/automatiabcn/shopops-mcp) | E-commerce operations — inventory, pricing, RFM, anomalies |
| [adops-mcp](https://github.com/automatiabcn/adops-mcp) | Google Ads & Meta Ads analytics |
| [mcp-server-starter](https://github.com/automatiabcn/mcp-server-starter) | Minimal production-ready MCP server template |
| [ai-arena-playground](https://github.com/automatiabcn/ai-arena-playground) | Compare models side by side, self-hosted |
| [cacheflow-ai](https://github.com/automatiabcn/cacheflow-ai) | AI API cost optimizer — caching and free-tier routing |
| [code-judge-bench](https://github.com/automatiabcn/code-judge-bench) | Real-bug PASS/FAIL pairs for code-review judges — dataset, eval harness, honest results |

## Principles

- Your data stays yours: self-hosted first.
- Source-available over lock-in.
- Honest engineering: a check that didn't run is never reported as passed.
- Ship small, verify, iterate.

## Contact

[automatiabcn.com](https://automatiabcn.com) · [x.com/automatiabcn](https://x.com/automatiabcn) · info@automatiabcn.com

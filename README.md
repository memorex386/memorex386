# Brad Thome

Senior full-stack product engineer in Dallas–Fort Worth. I build products where AI agents do most of the engineering and deterministic systems keep them honest.

[LinkedIn](https://www.linkedin.com/in/brad-thome/) · [vindecoded.com](https://vindecoded.com)

## VINDecoded

I founded and run [VINDecoded](https://vindecoded.com), a profitable vehicle-research platform on Android (1M+ downloads, 4.5 stars), iOS (400K+ downloads, 4.7 stars) and the web. It is operated as a one-person, agent-driven engineering team. The code is private, so here is how it works:

- **1,300+ merged PRs in 5 months**, about 84% from agent branches across Claude Code and Codex
- **Evals on real models:** frozen, labelled sets run the production code and report accuracy, cost per call and latency, and a calibrated LLM judge scores chat answers. One run found a photo-scan failure; the fix took exact match from 89.7% to 100%
- **Model output checked in code:** VIN check digits, receipt arithmetic and citations that must exist, behind kill switches and models that can be swapped without a deploy
- **Data-first design:** agents trace each screen's data, map every state and mock it before writing code
- **Every change ships dark:** 80+ remote kill switches and feature gates, per-user canaries and an A/B registry in PostHog
- **Scheduled agents** watch errors, cost, search, store rank and experiments, with explicit read/write limits
- **Deterministic guardrails underneath:** 1,700+ test files, 113 runbooks, 53 architecture decision records and one pre-approved CLI for production writes

Most of the contribution graph on this profile is that private work.

## Hopper

At Hopper (2022–2026), as a founding engineer on the Fintech AI team, I helped build a flight-shopping assistant and a generative offer platform (React/Next.js, Python/FastAPI, OpenAI/Claude/Gemini, tool calling, structured outputs, retrieval, evals). The AI-generated offer matched or beat static offers in live experiments. I also built an internal engineering agent with MCP servers, sandboxed code execution, Playwright evidence and cross-model review that produced review-ready PRs for humans to approve.

## Public work

- [verified-sudoku-coach](https://github.com/memorex386/verified-sudoku-coach): can an LLM make Sudoku coaching feel adaptive while deterministic software stays the only authority for every Sudoku fact? Product charter, trust boundaries, ADRs and an evaluation policy; implementation in progress.
- [Android-WebView-LocalWebServer](https://github.com/memorex386/Android-WebView-LocalWebServer): serve HTTP, HTTPS and FILE content on an Android device for a WebView.

**Stack:** TypeScript, React, Node.js, Python, Kotlin, Swift, SQL · Claude Code, Codex, MCP, evals · Azure, Firebase, Cloud Run, PostHog, Sentry

\# Mercor

**Status:** RESEARCHED
**Category:** Company — Focus Entity
**Value:** CRITICAL

## Overview

Mercor (mercor.com) is a San Francisco AI-labor marketplace that pairs vetted domain experts (doctors, lawyers, PhDs, senior engineers, finance professionals) with frontier AI labs that need human judgment to post-train models — RLHF preference ranking, supervised fine-tuning (SFT) pairs, grading rubrics, and agentic "RL environments." *(HIGH — Contrary Research, TechCrunch)*

Founded January 2023 as an AI-powered technical recruiting marketplace by three Bay Area high-school-debate friends: **Brendan Foody** (CEO), **Adarsh Hiremath** (CTO), and **Surya Midha** (Chairman, formerly COO). All three dropped out of college and were Thiel Fellows. Through 2024–2025 the company pivoted from recruiting placement fees toward selling expert-generated post-training data directly to AI labs, which is now the dominant revenue line. *(HIGH — Wikipedia, Contrary Research)*

## Leadership

- **Brendan Foody** — CEO, co-founder. See `../People/Brendan-Foody.md`.
- **Adarsh Hiremath** — CTO, co-founder. See `../People/Adarsh-Hiremath.md`.
- **Surya Midha** — Chairman (moved from COO, Oct 2025), co-founder. See `../People/Surya-Midha.md`.
- **Sundeep Jain** — President (joined May 2025), ex-Chief Product Officer of Uber; also held product roles at Google and Zynga. See `../People/Sundeep-Jain.md`. *(MED — LinkedIn/TheOrg via search, SF Standard)*

## Funding History

| Round | Date | Amount | Valuation | Lead | Notable participants |
|---|---|---|---|---|---|
| Seed | 2023 | $3.6M | — | General Catalyst | — |
| Series A | Sep 2024 | $32M (some sources: $250M valuation round) | ~$250M | Benchmark | — |
| Series B | Feb 2025 | $100M | $2B | Felicis | Benchmark, General Catalyst, DST Global, Menlo Ventures |
| Series C | Oct 27 2025 | $350M | $10B (5x Series B) | Felicis | Benchmark, General Catalyst, Robinhood Ventures (new) |
| In talks | Jul 9 2026 | ~$500M (reported) | $20B (term sheet reported) | — | — |

*(HIGH for Series B/C — independently verified via TechCrunch [Series C](https://techcrunch.com/2025/10/27/mercor-quintuples-valuation-to-10b-with-350m-series-c/) and [Series B](https://techcrunch.com/2025/02/20/mercor-an-ai-recruiting-startup-founded-by-21-year-olds-raises-100m-at-2b-valuation/) articles, which resolved and were directly fetched. MED for the $20B talks — verified via [TechCrunch Jul 9 2026](https://techcrunch.com/2026/07/09/mercor-is-in-talks-for-a-20b-valuation/), described in-article as "early stages.")*

Individual angel backers reported across rounds: **Peter Thiel, Jack Dorsey, Adam D'Angelo, Larry Summers**. *(MED — Bloomberg/TechCrunch via search, Sacra)*

## Revenue — CONFLICT across sources (reconcilable as a fast-moving timeline)

- Feb 2025: ~$75M ARR
- Oct 2025 (Series C): ~$450M ARR, "on track" for $500M ARR
- Year-end 2025: ~$760M annualized gross revenue
- H1 2026: $614M revenue (70% YoY growth), already exceeding full-year 2025
- June 2026 (single month, annualized): ~$2B run rate
- Jul 2026 (CEO Foody, per TechCrunch): run rate "crossed $2 billion," +100% in four months

*(MED-HIGH — multiple independent outlets converge on the trajectory and the ~$2B mid-2026 run-rate figure, but exact quarterly numbers vary by source and by gross-vs-net revenue definition. Contractors reportedly retain 60–70% of top-line/gross revenue, so net revenue is materially lower than headline ARR. Gross margin reported at 33% in Q2 2026 with guidance to ~46%. Sources: [Sacra](https://sacra.com/c/mercor/), [BigGo Finance](https://finance.biggo.com/news/865c23cb-3e0d-4c21-aa0d-6bf2a7fc8d1a), [Contrary Research](https://research.contrary.com/company/mercor), [TechCrunch](https://techcrunch.com/2026/07/09/mercor-is-in-talks-for-a-20b-valuation/).)*

Customer concentration: ~91% of H1 2026 revenue came from AI foundation-model companies; named customers include **OpenAI, Anthropic, Google DeepMind, Meta** — reportedly all top-5 AI labs and 6 of the "Magnificent 7." *(MED-HIGH — BigGo Finance, Contrary Research)*

## Products

- AI-powered candidate vetting/interview engine (originated as recruiting tech) — see `../Products/Mercor-AI-Vetting-Assessment.md`
- Post-training data suite (RLHF, SFT, Rubrics, RL Environments, APEX benchmarks) — see `../Products/Mercor-Post-Training-Suite.md`
- Agent-training simulation environments (via Deeptune acquisition, Jul 2026) — see `../Products/Deeptune-Agent-Training-Environments.md`

## Risk Factors / Negative Findings

- **March 27–31, 2026 data breach:** A supply-chain attack via a poisoned version of the open-source `LiteLLM` package (published to PyPI by threat actor "TeamPCP") harvested credentials for ~40 minutes, reportedly exposing up to 4TB of internal data — candidate PII, employer data, source code, API keys. A class-action lawsuit reportedly followed, affecting 40,000+ people. **Meta paused/suspended its Mercor contracts indefinitely** in response; OpenAI investigated exposure but did not terminate as of reporting. *(HIGH — corroborated across [TechCrunch](https://techcrunch.com/2026/04/09/after-data-breach-10b-valued-startup-mercor-is-having-a-month), MLQ News, TheNextWeb via search)*
- **Deeptune acquisition conflict-of-interest:** Foody personally angel-invested in Deeptune's $43M Series A (led by a16z) in ~April 2026, then had Mercor acquire Deeptune three months later (Jul 2026). Foody told Fortune the personal investment was "in a lot of ways the main motivation" for backing Deeptune early. No wrongdoing alleged, but it is a governance flag worth tracking (self-dealing / founder-insider-deal pattern). *(HIGH — [Fortune](https://fortune.com/2026/07/09/ai-unicorn-mercor-acquires-deeptune-brendan-foody-investor-a16z-openai-anthropic/), direct quote confirmed via fetch)*
- **Contractor relations:** Media reports (pre-dating breach) describe contractor complaints of a "stressful work environment, poor management, and declining pay." *(MED — Wikipedia summary of press coverage; not independently deep-dived in this pass — candidate for iteration 2)*
- **Customer concentration risk:** ~91% revenue from foundation-model labs; if labs build internal data-ops teams (several are known to be doing so), Mercor's core market could compress. *(MED — BigGo Finance analysis)*

## Competitive Position (see LANDSCAPE.md for full analysis)

Mercor's growth is substantially a beneficiary of the June 2025 Meta–Scale AI deal (Meta took a 49% stake in Scale for $14.3B), after which OpenAI, Google, and xAI reportedly pulled back from Scale over neutrality concerns and reallocated spend toward Mercor, Surge AI, Turing, Handshake, Invisible Technologies, Micro1, and Snorkel. Mercor's specific niche within that reshuffle is **credentialed-expert data** (PhDs, doctors, lawyers) for reasoning/domain evals, as distinct from Surge's frontier-lab RLHF breadth or Turing's coding focus. *(HIGH — Contrary Research, Teahose competitive summary via search)*

## Sources

- [Mercor — Wikipedia](https://en.wikipedia.org/wiki/Mercor) — verified, fetched
- [TechCrunch — Series C quintuples valuation to $10B](https://techcrunch.com/2025/10/27/mercor-quintuples-valuation-to-10b-with-350m-series-c/) — verified, fetched
- [TechCrunch — Series B at $2B](https://techcrunch.com/2025/02/20/mercor-an-ai-recruiting-startup-founded-by-21-year-olds-raises-100m-at-2b-valuation/) — verified, fetched
- [TechCrunch — in talks for $20B valuation](https://techcrunch.com/2026/07/09/mercor-is-in-talks-for-a-20b-valuation/) — verified, fetched
- [TechCrunch — after data breach, having a month](https://techcrunch.com/2026/04/09/after-data-breach-10b-valued-startup-mercor-is-having-a-month) — verified, fetched
- [Sacra — Mercor revenue, valuation & funding](https://sacra.com/c/mercor/) — verified, fetched
- [Contrary Research — Mercor Business Breakdown](https://research.contrary.com/company/mercor) — verified, fetched
- [BigGo Finance — H1 revenue surges past $615M](https://finance.biggo.com/news/865c23cb-3e0d-4c21-aa0d-6bf2a7fc8d1a) — verified, fetched
- [Fortune — Mercor acquires Deeptune](https://fortune.com/2026/07/09/ai-unicorn-mercor-acquires-deeptune-brendan-foody-investor-a16z-openai-anthropic/) — verified, fetched
- [CNBC — Mercor valued at $10B](https://www.cnbc.com/2025/10/27/ai-hiring-startup-mercor-funding.html) — found via search; WebFetch blocked (403, likely bot-wall) — corroborating only, not independently verified
- [Forbes — Mercor in talks for $20B](https://www.forbes.com/sites/richardnieva/2026/07/09/mercor-fundraise/) — found via search; WebFetch blocked (403) — corroborating only, not independently verified

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

## Business Model & Unit Economics

**Core mechanic: a labor marketplace with a cost-plus spread, not a SaaS/license model.** AI labs are billed an hourly "cost-plus" rate for the time a matched expert spends on a task; Mercor takes the spread between what the client pays and what the contractor is paid. *(HIGH — Value Add VC, verified via fetch)*

- **Take rate: ~35% of Gross Payment Volume (GPV).** Contractors receive an estimated **60–70% of the client-paid rate**, leaving Mercor a ~30–35% spread — in line with median BPO (business-process-outsourcing) gross margins, which several analysts flag as a meaningful framing question: is Mercor a technology marketplace (higher multiple) or a labor-sourcing/BPO channel (lower multiple)? *(HIGH — Value Add VC and selinasstack Substack independently cite the same ~35% figure and BPO-margin comparison, both verified via fetch)*
- **Hourly rate card varies enormously by domain:** general annotation/labeling work reportedly pays contractors **$15–40/hr**; software engineering and specialized technical work **$50–150+/hr**; live job listings on mercor.com in Aug 2026 showed a spread from **$65/hr (chemistry PhD, sales/marketing)** up to **$150/hr (law)**. The oft-cited "average $85–95/hr" blends across this whole range. *(HIGH for the live listings, verified via direct fetch of mercor.com; MED for the $15–40/hr low end, sourced from an aggregator (eesel AI) not independently fetched)*
- **Gross vs. net revenue matters a lot here.** Headline "ARR"/"run-rate" figures reported in the press are typically **gross payment volume** (what labs pay in), not Mercor's net take. Applying the ~35% take rate to the ~$2B mid-2026 gross run-rate implies **net revenue on the order of $600–700M/yr** — a very different number than the gross figure most headlines lead with. *(MED — this is this vault's own calculation applying the verified take-rate figure to the verified gross-revenue figure; treat as an estimate, not a disclosed number)*
- **Permanent-placement fee (legacy line):** for direct-hire placements (the original 2023 recruiting-marketplace product), Mercor charges **~30% of first-year compensation** — structurally the same take-rate logic, different billing event. *(HIGH — Contrary Research, verified via fetch)*
- **No fees to the supply side:** candidates/experts use the platform for free; all revenue comes from what clients pay. *(MED — ainativegtm Substack via search, not independently fetched, but consistent with the take-rate mechanic above)*

## Customer Acquisition (Go-to-Market)

Mercor's GTM has **diversified in step with its product line** — a bootstrapped, sales-free flywheel for the original marketplace, now layered with a high-touch enterprise motion for its newer products.

- **Marketplace side (labs + experts): historically no dedicated sales function.** Foody has said directly: *"We don't have a sales team. There isn't a single person who works on sales at Mercor outside of the founders."* Growth on the demand side (AI labs) came from **word-of-mouth and inbound interest driven by reputation** — credibility earned by delivering good early placements, which Foody describes as the real "sales tool." *(MED — ainativegtm Substack quote surfaced via search, not independently fetched — treat the direct quote as reported, not primary-verified)*
- **Supply side (expert acquisition):** free AI-powered tools used as acquisition hooks (mock interviews, resume feedback), referral programs, university-community outreach, and even automated **GitHub-profile scraping** to source engineering talent. *(MED — same source)*
- **Enterprise AI arm (newer, different motion):** "Mercor Enterprise AI" — the agent-deployment consulting product — runs a conventional **high-touch B2B motion**: no public pricing, prospects are routed to "book a demo," targeting organizations with 1,000+ employees, PE firms doing AI diligence, and specific functions (SRE/engineering, finance/ops, customer support). This is a materially different GTM from the founder-led marketplace flywheel — closer to a Forward-Deployed-Engineer (Palantir-style) consulting sales cycle. *(HIGH — verified via direct fetch of mercor.com/enterprise/)*
- **Data-monetization arm (newest):** for its "Mercor Data" product, Mercor pays a **referral bonus of up to $100K** to enterprises that bring in workflow-data licensing deals — a channel/referral-driven acquisition motion distinct from both of the above. *(HIGH — verified via direct fetch of mercor.com/data/)*
- **Named customers beyond frontier labs:** the enterprise-diversification push explicitly targets **consulting firms, financial services, and AI-application enterprises**, alongside continuing frontier-lab relationships with newer/smaller labs too (Reflection AI, Thinking Machines Lab named). *(MED — search-result synthesis, not independently fetched)*

## Revenue — CONFLICT across sources (reconcilable as a fast-moving timeline)

Full growth trajectory, pieced together across sources (figures are **gross payment volume / gross run-rate** unless noted — see Business Model section above for the gross-vs-net distinction):

- Year 1 (2023): mid-seven-figures, bootstrapped, pre-pivot recruiting revenue
- Nov 2024: ~$50M ARR
- Feb 2025: ~$75M ARR
- Mar 2025: ~$100M ARR
- Oct 2025 (Series C): **~$450M ARR per Contrary Research; ~$840M per selinasstack's analysis for the same month** — a real CONFLICT between two research write-ups covering the same period, not just rounding; TechCrunch's own Series C coverage says only that the company was "on track" for $500M ARR without giving an exact October figure
- Year-end 2025: ~$760M annualized gross revenue (Sacra)
- H1 2026: $614M revenue (70% YoY growth), already exceeding full-year 2025 (BigGo Finance)
- June 2026 (single month, annualized): ~$2B run rate
- Jul 2026 (CEO Foody, per TechCrunch): run rate "crossed $2 billion," +100% in four months

**Growth-rate framing used in press coverage:** ~6,400% YoY at the earlier (2024–2025) stage, with **41–50% month-over-month growth** during the steepest part of the curve; overall characterized as "$1M to $500M in revenue in 17 months" (fastest in this category's history, per one account) and "$0 to $2B run-rate in ~24 months." *(MED — ainativegtm Substack and Lenny's Newsletter episode framing, surfaced via search, not independently fetched — treat the specific percentages as reported claims)*

**Capital efficiency signal:** at the ~$50M ARR stage, Mercor reportedly ran on **~30 US full-time employees** (plus ~20 India-based contractors) — roughly **$1.7M revenue per US employee**, an unusually lean structure for the revenue scale, consistent with the "no sales team" GTM claim above. *(MED — same source, not independently fetched)*

*(MED-HIGH overall — multiple independent outlets converge on the trajectory and the ~$2B mid-2026 run-rate figure, but exact quarterly numbers vary by source, by gross-vs-net revenue definition, and in the Oct-2025 case, by a genuine ~2x disagreement between two analyst write-ups. Contractors reportedly retain 60–70% of top-line/gross revenue, so net revenue is materially lower than headline ARR — see Business Model section. Gross margin reported at 33% in Q2 2026 with guidance to ~46%. Sources: [Sacra](https://sacra.com/c/mercor/), [BigGo Finance](https://finance.biggo.com/news/865c23cb-3e0d-4c21-aa0d-6bf2a7fc8d1a), [Contrary Research](https://research.contrary.com/company/mercor), [TechCrunch](https://techcrunch.com/2026/07/09/mercor-is-in-talks-for-a-20b-valuation/).)*

Customer concentration: ~91% of H1 2026 revenue came from AI foundation-model companies; named customers include **OpenAI, Anthropic, Google DeepMind, Meta** — reportedly all top-5 AI labs and 6 of the "Magnificent 7." *(MED-HIGH — BigGo Finance, Contrary Research)*

## Full Product Portfolio

As of August 2026, Mercor spans **four distinct product lines**, a materially broader footprint than the "expert marketplace" framing most press coverage uses — verified directly against mercor.com's current site structure:

| Product line | What it does | Customer | Detail |
|---|---|---|---|
| **Expert Marketplace / Post-Training Data Suite** | RLHF, SFT, rubric-based grading, RL environments; the original and still-dominant revenue line | Frontier AI labs | `../Products/Mercor-Post-Training-Suite.md` |
| **APEX Benchmark family** | "AI Productivity Index" — public leaderboards benchmarking model performance on economically valuable tasks; has expanded into specialized sub-leaderboards: **APEX-Agents, APEX-Accounting, APEX-SWE** | AI labs (benchmarking/PR), enterprises (vendor evaluation) | folded into `../Products/Mercor-Post-Training-Suite.md` |
| **Mercor Enterprise AI** | Forward-Deployed-Engineer-style AI agent consulting: a 4-phase engagement — **Discover** (workflow/opportunity mapping via "AI interviews"), **Deploy** (build/integrate production agents), **Improve** (ongoing optimization), **Monetize** (data licensing, see below) | Enterprises (1,000+ employees), PE firms doing AI diligence | `../Products/Mercor-Enterprise-AI.md` (new) |
| **Mercor Data (Enterprise Workflow Data)** | Pays enterprises to anonymize and license their internal operational data (Slack/email/meetings, docs, project mgmt, CRM, code, finance/HR systems — 50+ integrations) to AI labs; SOC 2 Type II, proprietary anonymization claimed to detect 60+ sensitive-identifier types | Enterprises (as data sellers) ↔ AI labs (as data buyers) | `../Products/Mercor-Data-Monetization.md` (new) |
| **Mercor Voice / AI vetting engine** | The underlying AI-interview and candidate-screening infrastructure (originated as the 2023 recruiting product) that now also brands as "Mercor Voice" — the supply-side matching flywheel underneath every other product line | Internal infrastructure, also marketed as a standalone signal of vetting quality | `../Products/Mercor-AI-Vetting-Assessment.md` |
| **Deeptune agent-training environments** | Simulated software environments (Excel, Salesforce, Slack) for training AI agents, acquired Jul 2026 | Frontier labs, agent developers | `../Products/Deeptune-Agent-Training-Environments.md` |

*(HIGH for the product-line existence and descriptions — verified via direct fetch of mercor.com, mercor.com/enterprise/, and mercor.com/data/. The "Mercor Voice" branding and the exact boundary between what's bundled under which product name is inferred from the live site structure, not from a single canonical org chart — treat sub-brand naming as MED.)*

**Case-study metrics Mercor uses in Enterprise AI sales collateral** (i.e., what it tells prospective enterprise clients to expect): "50%+ reduction in median time to incident mitigation," "$7–9M upside run-rate savings identified" (PE due-diligence case), "$20M annual run-rate impact identified by 2031" (value-creation case), "~12,000 support requests handled per week" (customer-success deployment case). *(HIGH — verified via direct fetch; these are vendor-published case-study claims, not independently audited outcomes)*

## Metrics Mercor Tracks / Publicizes

Two distinct layers of metrics are visible: what Mercor **puts on its own homepage as of Aug 2026** (its chosen public KPIs), and what **analysts/press reconstruct** from disclosures and filings-adjacent reporting.

**On-site live counters (mercor.com homepage), confirmed present but not readable as static numbers (JS-rendered):**
- *Average contracted rate ($/hr)*
- *Roles created (k)*
- *Daily payouts ($)*

That Mercor chose these three as its headline public-facing stats is itself informative: it is marketing **marketplace liquidity and payout velocity** (i.e., "real money moving to real experts, right now") rather than a SaaS-style metric like logo count or NRR — consistent with the BPO/labor-marketplace framing raised in the Business Model section. *(HIGH that these three labels are the ones displayed, verified via direct fetch; the underlying numeric values could not be captured since they render client-side)*

**Metrics reconstructed by analysts/press** (not company-disclosed KPIs, but the numbers the market uses to evaluate Mercor):
- Take rate (~35% of GPV) and gross-vs-net revenue split
- Daily contractor payouts in dollar terms (~$1.5–2M/day reported at various points in 2025–2026)
- Revenue per (US) employee (~$1.7M at the $50M-ARR stage)
- Customer concentration (~91% of H1 2026 revenue from foundation-model labs)
- Gross margin (33% in Q2 2026, guided to ~46%)
- Contractor network size (30,000+ active, 468,000+ applicants ever evaluated)

*(See individual figures' confidence tags earlier in this file and in Business Model / Revenue sections above — this list is a summary index, not a new sourcing claim.)*

## Risk Factors / Negative Findings

- **March 27–31, 2026 data breach:** A supply-chain attack via a poisoned version of the open-source `LiteLLM` package (published to PyPI by threat actor "TeamPCP") harvested credentials for ~40 minutes, reportedly exposing up to 4TB of internal data — candidate PII, employer data, source code, API keys. A class-action lawsuit reportedly followed, affecting 40,000+ people. **Meta paused/suspended its Mercor contracts indefinitely** in response; OpenAI investigated exposure but did not terminate as of reporting. *(HIGH — corroborated across [TechCrunch](https://techcrunch.com/2026/04/09/after-data-breach-10b-valued-startup-mercor-is-having-a-month), MLQ News, TheNextWeb via search)*
- **Deeptune acquisition conflict-of-interest:** Foody personally angel-invested in Deeptune's $43M Series A (led by a16z) in ~April 2026, then had Mercor acquire Deeptune three months later (Jul 2026). Foody told Fortune the personal investment was "in a lot of ways the main motivation" for backing Deeptune early. No wrongdoing alleged, but it is a governance flag worth tracking (self-dealing / founder-insider-deal pattern). *(HIGH — [Fortune](https://fortune.com/2026/07/09/ai-unicorn-mercor-acquires-deeptune-brendan-foody-investor-a16z-openai-anthropic/), direct quote confirmed via fetch)*
- **Contractor relations — verified specific incident (Nov 2025):** contractors on a project codenamed **"Musen"** (reviewing Meta Facebook/Instagram Reels video/audio) were abruptly locked out of Slack when the project was cancelled; hours later, Mercor offered many of the same workers a new project codenamed **"Nova"** at **$16/hour — $5 below Musen's rate**, with some contractors saying they'd earned as much as $60/hr on other Mercor projects previously. Mercor's position (per Business Insider/Forbes reporting) is that this was normal project-based workforce reallocation intended to produce "greater earning stability," and disputes the characterization of the incident as a wage cut. *(HIGH for the incident occurring and the specific $16 vs. $21/hr figures — corroborated across Forbes, AOL, and LinkedIn coverage of the same Business-Insider-sourced reporting, found via search; original Forbes article itself returned 403 on direct WebFetch, so treat as press-corroborated rather than primary-verified)* This is a concrete instance of the broader "stressful work environment, poor management, declining pay" pattern Wikipedia's press summary references — no longer just an unspecified media characterization.
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
- [Mercor — homepage](https://www.mercor.com/) — verified, fetched (full product portfolio, live job listings/rates)
- [Mercor — Enterprise AI](https://www.mercor.com/enterprise/) — verified, fetched (Enterprise AI product, GTM, case-study metrics)
- [Mercor — Data](https://www.mercor.com/data/) — verified, fetched (Mercor Data product, workflow-data categories, security posture)
- [Value Add VC — How Does Mercor Make Money](https://valueaddvc.com/blog/how-does-mercor-make-money-2b-arr-20b-valuation-and-the-expert-data-marketplace-explained) — verified, fetched (take rate, unit economics)
- [selinasstack Substack — Mercor: Enduring AI Infrastructure or Cycle-Driven Winner?](https://selinasstack.substack.com/p/mercor-enduring-ai-infrastructure) — verified, fetched (take rate corroboration, Oct-2025 ARR conflict, concentration-risk framing)
- [TechCrunch — How AI labs use Mercor to get the data companies won't share](https://techcrunch.com/2025/10/29/how-ai-labs-use-mercor-to-get-the-data-companies-wont-share) — verified, fetched (customer use case, Foody quotes, competitive position)
- [ainativegtm Substack — From Zero to $100M ARR in 11 Months](https://ainativegtm.substack.com/p/from-zero-to-100m-arr-in-11-months) — found via search, not independently fetched (GTM/no-sales-team claims, early growth timeline, revenue-per-employee) — treat as MED
- [Lenny's Newsletter — Why experts writing AI evals is creating the fastest-growing companies in history (Brendan Foody)](https://www.lennysnewsletter.com/p/experts-writing-ai-evals-brendan-foody) — verified reachable via fetch; full transcript paywalled, only excerpt accessible
- [Forbes — Mercor Contractors Allege The AI Company Slashed Their Wages](https://www.forbes.com/sites/iainmartin/2025/11/12/the-worlds-youngest-self-made-billionaires-just-slashed-these-workers-wages-by-a-third/) — found via search (also corroborated via AOL/LinkedIn coverage of the same reporting); WebFetch blocked (403) — corroborating only, not independently verified

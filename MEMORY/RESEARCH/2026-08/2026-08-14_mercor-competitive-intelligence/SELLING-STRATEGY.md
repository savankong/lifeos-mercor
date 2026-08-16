\# Selling Data & Expertise Into This Market

**Status:** RESEARCHED
**Pass 5 — 2026-08-14**
**Purpose:** actionable go-to-market analysis for supplying human expertise and/or enterprise operational data into the companies profiled in this vault, prompted by a specific question: which of Mercor, Surge AI, Handshake AI (and others) have real data-vendor/partner mechanisms, and how would selling into each actually work.

**Important framing correction up front:** an earlier draft analysis circulated alongside this request claimed Handshake has an "Employer Data Program" and Surge has a "Consulting Program" as formal vendor-facing offers. I independently verified each claim against primary sources before writing anything below — some held up, one didn't quite. See the per-company notes for what changed.

---

## The three ways to sell into this market

1. **Sell enterprise operational data directly** (Slack/email/CRM/docs/code) — the model Mercor, Scale AI, and Handshake AI all now explicitly run. You (or a company you represent) are the *data source*.
2. **Sell a pipeline of vetted human expertise** — recruiting and packaging access to a specific professional population (e.g., "500 former DoD acquisition officers") that a marketplace then pays per-task/per-hour, same mechanic as the core Mercor/Surge/Micro1 marketplaces, but you're the originator of a *talent channel*, not an individual contractor.
3. **Broker/originate deals for a fee** — identify companies with valuable operational data or identify talent pools, introduce them to the buyer, take a referral fee or revenue share. This is the lowest-capital, fastest-to-test model, and — per the research below — at least two of these companies (Mercor, Scale AI) have already formalized exactly this as a paid program.

## Company-by-company: what's actually real

| Company | Program (verified name) | What they buy | Compensation — as actually stated | Engagement process | Confidence |
|---|---|---|---|---|---|
| **Mercor** | [Mercor Data](https://www.mercor.com/data/) | Enterprise workflow data: Slack/email/meetings, docs, project mgmt, CRM, code, finance/HR (50+ integrations) | Compensation for data contribution; **referral bonus up to $100K** for introducing a company that does a deal | Enterprise signs up, connects via OAuth integrations; Mercor handles anonymization/extraction | HIGH — verified via direct fetch |
| **Scale AI** | [Scale Data Partnership](https://scale.com/data-partnership) | De-identified structured records from data warehouses (BigQuery/Snowflake/Databricks), comms (Slack/Teams/email), docs (Word/Sheets/Drive), work-mgmt (Jira/Asana/Notion), business platforms (Salesforce/HubSpot/Workday/ServiceNow) | **$10K–$1M+ per partnership** (illustrative range, scales with cadence — framed as recurring, not one-time); separate **$10,000 flat referral bonus** per company introduction that signs | Book an intro call; can start with limited scope; anonymization happens inside the company's own environment before extraction; prefers companies with **40+ employees** | HIGH — verified via direct fetch |
| **Handshake AI** | [Handshake AI Data Partnerships](https://joinhandshake.com/ai/data-partnerships/) | Operational datasets reflecting "how real organizations make decisions and execute work" | **Not disclosed publicly** — "every dataset is evaluated individually; there are no automated decisions"; no referral-bonus figure published | Submit an intake form (org, data type, scale, format — no commitment) → scoping call to discuss de-identification, commercial terms, timeline | HIGH that the program exists and works this way (verified via direct fetch); MED-LOW on any compensation figure, since none is published — the claim in the earlier draft that this is "particularly interesting" is directionally right but the pricing opacity is a real gap versus Mercor/Scale |
| **Surge AI** | **No formal company/data-vendor program found** | Individual expert labor only, via its normal "Workforce" hiring funnel (e.g., a "Management Consultant — McKinsey/Bain/BCG or equivalent" role posting) | N/A — this is a job-application flow for individuals, not a company-level referral or data-partnership program | Apply as an individual expert; no published mechanism to introduce a company or a talent *pipeline* and get paid for it | **CORRECTION to the earlier draft**, which described a "Consulting Program" for exactly this — I could not find one. What exists is Surge's standard expert-hiring page, which is a different thing. Selling Surge a *pipeline* of people would require cold business-development outreach with no published terms, not a self-serve program |
| **Invisible Technologies** | [Partnerships](https://invisibletech.ai/partnerships) page | Unclear — page is a generic "where do you see opportunities for partnership?" contact form | Not disclosed at all | Contact form only, routes to a sales conversation | LOW — verified the page exists and is this generic, via direct fetch; no specifics to evaluate |
| **Turing** | **No program found** | Unclear | Not disclosed | Not disclosed | Could not verify a company-level data/vendor program in this pass. Note: search results surfaced a "Turing Partner Program" at `turing.ai` — **this is very likely a different, unrelated company** (domain and content don't match Turing.com, the AI-data company profiled elsewhere in this vault); flagging so it isn't mistaken for the same Turing |

## Corrected ranking

The earlier draft ranked opportunity as **Mercor → Handshake → Surge**. Based on verified primary sources, I'd rank it differently:

1. **Mercor and Scale AI are tied for clearest, most concrete entry point** — both have explicit dollar figures, explicit referral bonuses, and a defined intake process. Scale AI's program is arguably *more* concretely quantified (a stated $10K–$1M+ deal range plus a flat $10K referral bonus, versus Mercor's single "up to $100K" referral figure with no disclosed base deal-value range). If the goal is "fastest path to a real conversation with real numbers attached," start with **both**, not just Mercor.
2. **Handshake AI is real but opaque on price.** The program exists and is well-documented in how it *works*, but with no published compensation figures, you won't know if a deal is attractive until you're already in a scoping call — more friction than Mercor/Scale, not less.
3. **Surge AI is not a self-serve option at all**, contrary to the earlier draft's framing. Selling Surge a talent pipeline or dataset would mean identifying a human contact and pitching cold — worth doing if you have something genuinely unique, but budget for a much longer, less certain sales cycle than the other three.
4. **Invisible Technologies and Turing are undifferentiated/unverified** — treat as lower priority unless you have a specific reason to believe one of them wants what you have.

## The brokerage/origination model — is it real?

Yes, concretely, at two companies: **Mercor's $100K referral bonus and Scale AI's $10K referral bonus are both real, named, standing programs** — not something you'd need to negotiate into existence. That validates the "originate the deal, take a fee" model as a legitimate low-capital entry strategy, at least as a first move. Two caveats worth weighing before betting a business on it:

- **Referral fees are a small fraction of the deal's actual value.** Scale's own framing ($10K–$1M+ per partnership vs. a flat $10K referral) implies the referral fee could be anywhere from ~1% to effectively all of a small deal's value — it's a nice first check, not a scalable revenue model on its own unless you can originate many deals.
- **The bigger money is in *being* the data source or the talent-pipeline owner, not just the introducer** — which is a fundamentally different (and harder) business: you need something proprietary to sell (real operational data you're authorized to share, or a genuinely differentiated professional network), not just a Rolodex.

## Illustrative example: packaging a specialized professional network

One version of the "talent pipeline" strategy, using the defense/government-contracting vertical as a worked example (this is illustrative of the model, not a claim that any of these companies have specifically said they want this — that would need direct confirmation from each company):

A network of former DoD program managers, contracting officers, acquisition professionals, and defense-industry executives could plausibly generate the kind of **domain-specific reasoning and decision data** that Mercor, Surge, and Handshake all say they're short on — "how does someone with 15 years in defense acquisition actually reason through a hard tradeoff," not just their resume. This is a genuinely different pitch than "I have a dataset" — it's "I can originate and vet a supply of a specific kind of expert judgment on an ongoing basis," which is closer to what Mercor/Surge/Micro1's entire marketplace is built to consume. **Before pursuing this or any similar vertical, the open question worth answering first is the one raised in the pasted draft: which 3–5 specific data/expertise types are these companies actively paying premium rates for right now** — that's a research question this vault hasn't yet answered with hard evidence (job-posting rate data, specific RFP/contract language, or direct conversations), and would be the natural next research pass if this strategy is pursued.

## Sources

- [Mercor — Data](https://www.mercor.com/data/) — verified, fetched
- [Scale AI — Data Partnership](https://scale.com/data-partnership) — verified, fetched
- [Handshake AI — Data Partnerships](https://joinhandshake.com/ai/data-partnerships/) — verified, fetched
- [Handshake AI — Employer Data Program (blog)](https://joinhandshake.com/blog/our-team/handshake-ai-employer-data-program/) — verified, fetched
- [Invisible Technologies — Partnerships](https://invisibletech.ai/partnerships) — verified, fetched
- [Surge AI — Workforce](https://surgehq.ai/workforce) — verified, fetched (previously, Pass 4)
- Search results only for Turing partner-program claims — not resolved to a verified primary source for Turing.com specifically; flagged above

## What this doesn't cover yet

- Legal/compliance exposure of reselling "operational data" or facilitating expert data contribution (confidentiality obligations, trade-secret law, data-privacy regimes) — every company above places the compliance burden on the data-contributing organization, which is a real liability question for any brokerage play and wasn't researched in this pass.
- Actual deal economics beyond the headline referral figures (typical per-record or per-hour pricing for operational data deals; typical margin structure for expert-pipeline placements).
- Direct confirmation from any of these companies of specific data/expertise types they're short on — the "3–5 datasets" question above remains open.

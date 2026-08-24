\# Do Anthropic/OpenAI Actually Have Demand for Government-Employee Knowledge?

**Status:** RESEARCHED (deep dive, live web research)
**Pass 12 — 2026-08-16**
**The question asked directly:** does this demand actually exist? This document answers it — and the honest answer is that "demand for government employees and their knowledge" is real but splits into several different things, and the specific thing the defense/government broker pitch assumed (a scalable marketplace of ex-government experts answering structured scenario questions, the same model Mercor runs for doctors/lawyers) is the one type **not** found to exist in an open, accessible form.

## Five distinct findings — don't collapse them into one "yes"

### 1. Labs selling AI products TO government — huge, real, and currently extremely volatile

This is real demand, but it runs in the **opposite direction** from what the broker pitch needs (labs *buying* government expertise). Anthropic secured a **$200M DoD contract** in July 2025, with Claude becoming the first frontier model approved for classified networks, plus a GSA OneGov deal offering Claude to all three branches of government for **$1**. Then, dramatically: on **February 27, 2026**, President Trump directed all federal agencies to stop using Anthropic's technology, and Defense Secretary Pete Hegseth designated Anthropic a **"supply chain risk"** — a label previously reserved for firms tied to foreign adversaries — after Anthropic refused to loosen its acceptable-use policy (which bars Claude from mass domestic surveillance and fully autonomous weapons) to let the Pentagon use it "for all lawful purposes." The Pentagon shifted to **OpenAI** instead, which now holds the comparable $200M Pentagon contract. Anthropic has sued; a federal judge has reportedly blocked part of the government's action. *(HIGH — corroborated across CNBC, Mayer Brown, Taft Law, CNN, Fortune, and Anthropic's own announcement, all found via search)*

### 2. Labs directly hiring former-government/cleared individuals — real, but small-scale and via direct employment, not a marketplace

Both labs are actively recruiting people with national-security/government backgrounds — as **W-2 employees in specific senior roles**, not as marketplace contributors:

- **Anthropic:** "Public Policy Lead, National Security" (10+ years in national security agencies or Congressional offices, active TS/SCI or one held within 2 years); "Threat Intelligence Manager, CBRN-E and Advanced Weapons" (counterproliferation/WMD analysis background preferred, active TS clearance desired, salary up to **$455,000**); a Frontier Red Team within its Policy org.
- **OpenAI:** "National Security Cyber Evaluation Lead," "Senior Technical Advisor, National Security Policy" (reports to OpenAI's Head of National Security Policy), "Government Account Director, National Security," "GRC Program Manager, US Government Compliance" — clustered in Washington, DC, several requiring active clearances.

*(HIGH — verified via direct search of both companies' own job postings)*

**Why this matters for the broker pitch:** this is real evidence labs value government-domain knowledge — but it's satisfied by hiring a handful of named senior specialists directly onto the payroll for policy/safety/compliance/national-security functions, not by purchasing aggregated reasoning-trace data from a pool of contributors. It doesn't scale the way Mercor's doctor/lawyer marketplace does, and a broker has nothing to sell into a direct-hire process.

### 3. The established data vendors already hold direct government/defense contracts — a real competitive blocker

- **Mercor** holds a US federal government contract.
- **Surge AI's** verified clients include the **Army and Air Force**.
- **Scale AI** has **$300M+ in DoD contracts total**, including the **Thunderforge** prime contract (Defense Innovation Unit, partnered with Anduril and Microsoft, for military campaign planning and theater-wide resource allocation supporting INDOPACOM and EUCOM), a five-year $100M CDAO ceiling agreement, and a $99M Army R&D contract. This is the "enterprise deployment" pivot already noted in this vault's `Companies/Scale-AI.md` — Scale specifically leaned into defense as its post-Meta-deal second act.

*(HIGH — Scale figures verified via multiple corroborating sources including scale.com's own Thunderforge announcement, CNBC, Washington Post, Axios; Mercor/Surge government-client claims from Forbes reporting, see finding 4 below)*

**Why this matters:** if a scalable market for "aggregated government/defense expert judgment" exists, the players best positioned to capture it are the ones who already hold the government contracts, clearance infrastructure, and trust relationships — Mercor, Surge, and especially Scale AI — not a new entrant broker starting from zero.

### 4. A live, unresolved controversy: these same vendors are also selling to Chinese AI labs

Forbes reporting (Aug 5, 2026) found that **Surge AI and Mercor — while simultaneously serving the US government — also supply training data to Chinese AI labs**, including **Tencent** (a Pentagon-designated Chinese military company), which buys from Surge AI. Mercor declined to comment on similar claims. Scale AI founder Alexandr Wang publicly criticized this on X: *"concerning that data companies serving the US government (mercor, surge) are also working with Chinese AI labs... serving the US government should not be a commercial convenience, it must be a bedrock principle for startups."* The top six Chinese AI labs reportedly spend roughly **$500M/year** with American data-labeling companies in aggregate. *(HIGH that the reporting and the Wang quote exist and say this, verified via search of Forbes/ChinaTalk/AI Weekly coverage and the original X post; MED on the underlying allegations themselves, since Mercor/Surge declined to confirm)*

**Two-sided implication for a potential broker:** this is rising political/regulatory heat on the whole category, which could increase demand for a vendor who can credibly claim **zero China exposure** for defense-sensitive work — a real differentiator, if true and provable. But it also means compliance/vetting scrutiny is rising fast, not falling, and any future misstep in this space is now reputationally live-wire, not a hypothetical risk.

### 5. Checked directly: neither Mercor's nor Handshake AI's public expert marketplace lists a government/defense/policy category at all

Fetched both companies' live, public contributor/fellowship listings directly. **Mercor's** visible categories are entirely commercial — healthcare/insurance, sales & marketing, FP&A, product management, accounting, HR, design, quant trading, biotech. **Handshake AI's** visible categories: AI Evaluation Specialist, Energy Professional, FP&A Analyst, Game Developer, PCB Tool Specialist, Philosophy Expert, Software Engineer. **No government, defense, policy, military, national security, or intelligence category appears on either public-facing board.** *(HIGH — verified via direct fetch of both)*

**This is the most important finding for the broker pitch specifically.** Whatever government-contract work Mercor and Surge actually do is evidently not run through the same open, self-serve marketplace model they use for doctors and lawyers — almost certainly because clearance and sensitivity requirements are incompatible with an open sign-up flow. That means the "recruit ex-DoD program managers to answer structured scenarios, same as Mercor does with doctors" model the broker pitch envisioned doesn't have a visible precedent to point to. It may still be possible, but it would need to be a different, more closed, more compliance-heavy pipeline than the existing credentialed-marketplace playbook — a materially harder build than the pitch assumed.

## Answer to the question as asked

**Yes, Anthropic and OpenAI clearly value government/national-security expertise** — enough to pay up to $455K for a single cleared specialist, and enough that government contracts (in the other direction) are worth hundreds of millions to both labs. **But the specific form of demand the broker pitch needs — a scalable, marketplace-style purchase of aggregated ex-government professional judgment — was not found to exist anywhere in this research**, at either the labs directly (who hire named individuals instead) or at the intermediary vendors (whose public marketplaces exclude this category entirely, likely for clearance reasons). The three established players already hold the actual government contracts and would be the incumbents to beat, not obvious channel partners for a broker.

## What this means for the defense/government wedge specifically

This softens, but doesn't fully kill, the idea — it changes what the actual wedge would need to be:

- **Classified or clearance-gated government/defense knowledge is very likely not approachable via an open marketplace model at all** — this vault's earlier illustrative example (a network of "former DoD program managers... answering structured scenarios") implicitly assumed a Mercor-style open marketplace could work here the way it works for doctors and lawyers. The evidence above suggests that's the wrong model for this specific domain.
- **A narrower, lower-sensitivity slice might still be viable**: unclassified knowledge about *how government actually works* — budget processes, acquisition/contracting workflows, program-office structure, interagency coordination — doesn't require a clearance to discuss and could plausibly fit the open-marketplace model better than classified operational content does. This is a much smaller, softer niche than "defense and government expertise" broadly implied.
- **The single highest-value next step is unchanged from Pass 11's recommendation, and this research makes it more urgent, not less**: ask Mercor, Surge, or Scale directly whether there's a specific, unmet demand here at all before building anything — this pass found real signal that labs value this knowledge, but no evidence of an accessible channel to sell it through.

## Sources

All findings verified via live web search and direct fetch in this pass (2026-08-16) — see inline citations above. Key sources: Anthropic's own DoD contract announcement (anthropic.com), CNBC, Mayer Brown, Taft Law, CNN, Fortune (Pentagon/Anthropic ban coverage); Anthropic and OpenAI's own careers pages (job listings, search-verified); scale.com (Thunderforge announcement), CNBC, Washington Post, Axios (Scale AI DoD contracts); Forbes, ChinaTalk, AI Weekly, and Alexandr Wang's X post (China-exposure controversy); direct fetch of mercor.com and joinhandshake.com/ai/ (marketplace category check).

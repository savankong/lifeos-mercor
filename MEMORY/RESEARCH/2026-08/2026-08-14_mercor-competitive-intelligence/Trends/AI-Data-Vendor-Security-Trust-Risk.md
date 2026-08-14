\# AI-Data-Vendor Security & Trust Risk

**Status:** RESEARCHED
**Category:** Trend
**Value:** HIGH

## Overview

Trust and neutrality — not just cost or quality — have become the primary competitive currency in this market, and 2025–2026 produced two distinct trust shocks:

1. **Ownership-neutrality risk:** Meta's 49% stake in Scale AI (Jun 2025) broke Scale's neutrality and triggered the lab exodus described in `Post-Scale-Meta-Neutrality-Shift.md`.
2. **Security/supply-chain risk:** Mercor's March 2026 breach — a poisoned open-source `LiteLLM` package used to harvest credentials and exfiltrate up to 4TB of internal data — showed that even a "neutral" vendor can lose lab trust overnight via a security failure, not just an ownership conflict. **Meta paused its Mercor contracts indefinitely** in direct response, despite Meta's own Scale stake making Mercor an alternative it was actively relying on. *(HIGH — TechCrunch, verified via fetch)*

## Why it matters

Any AI-data vendor's moat now rests on a second axis beyond data quality/cost: demonstrable independence *and* demonstrable security hygiene. A single incident (ownership change, breach, leak) can move hundreds of millions in annual lab spend within weeks, as shown twice in twelve months. This is a live, ongoing risk category for every company in this vault, not a one-time historical event — worth a recurring check in future iterations of this research (any new breach, ownership change, or lab-contract termination should be logged here).

## Sources

- [TechCrunch — after data breach, having a month](https://techcrunch.com/2026/04/09/after-data-breach-10b-valued-startup-mercor-is-having-a-month) — verified, fetched
- [Contrary Research — Mercor Business Breakdown](https://research.contrary.com/company/mercor) — verified, fetched

\# Who Sells Medical Data to the AI Labs? — Three Distinct Tracks

**Status:** RESEARCHED (live web research)
**Pass 16 — 2026-08-16**
**The question asked directly:** who sells medical data to the buyers (the AI data companies/labs this vault covers)? Same lesson as the government-demand analysis in Pass 12 — "medical data" isn't one market, it's at least three, and they need to stay separate.

## Track 1: Medical expert judgment / RLHF data (doctors evaluating AI outputs)

This is the same category as the rest of this vault's research — credentialed physicians and clinicians ranking, grading, and generating gold-standard clinical reasoning for AI labs, paid by the hour.

- **Mercor** runs a dedicated **"Physician Talent Network"**: $110–250/hr for MDs, $60–120/hr for nurses, spanning diagnostic reasoning, acute-care decision-making, specialty disease management, healthcare operations, and data analytics. Positions the work explicitly as "senior-level clinical reasoning," not traditional labeling. *(HIGH — verified via direct fetch of mercor.com/experts/healthcare/)*
- **Surge AI, Scale AI (via Outlier), Handshake AI, Micro1** all recruit doctors as one of several verticals — already documented elsewhere in this vault.
- **Centaur Labs** (new to this vault — see `Companies/Centaur-Labs.md`) is the most direct **healthcare-only** analog: 58,000+ medical professionals/students, peer-reviewed accuracy claims (reportedly outperforming board-certified physicians per Memorial Sloan Kettering and Mass General Brigham studies), $31M raised. A specialized competitor for the same supply, not a generalist.
- **AfterQuery** (YC-backed) also hires domain experts across medicine, law, and finance to design tasks and grade outputs — the same company flagged in `YOUR-ROSTER-GOVERNMENT-DEMAND-ANALYSIS.md` as reportedly booking $50M+/yr from Chinese AI labs, so the same national-security/trust caveat applies here.
- **Rise Data Labs** was also named as covering healthcare annotation, but on a single, unverified source — flagged, not treated as confirmed.
- **Pre-existing physician-panel infrastructure now feeding this demand**: Sermo, M3, and GLG — established physician market-research/expert-network companies (not built for AI originally) that reportedly now also monetize via AI training work, per a "Clinicians' AI Economy" overview piece found via search, not independently verified.

*(Overall confidence: HIGH for Mercor's program and the existence of Centaur Labs/AfterQuery as real companies; MED on specific figures for Centaur Labs and Rise Data Labs, which came from search-result synthesis rather than direct fetch this pass.)*

## Track 2: Real-world clinical/EHR/claims data (a different, much larger, pre-existing industry)

This is structured patient-level data — EHR records, claims, lab results — not expert judgment, and the companies in this space are mostly **pharma-facing real-world-evidence (RWE) platforms**, not AI-native startups:

- **Truveta** — has an explicit AI-training deal: a partnership with Knit Health to train a "Large Clinical Behavior Model" on Truveta's regulatory-grade, de-identified dataset.
- **Datavant** — specializes in privacy-preserving data linkage across health-data partners.
- **Komodo Health** — patient-journey analytics and rare-disease epidemiology, with AI-enhanced tooling (MapLab/MapAI).
- **HealthVerity, Aetion, IQVIA** — all-payer longitudinal data coverage and RWE platforms, historically pharma-focused.

*(MED-HIGH — verified via search-result synthesis of industry vendor-comparison pieces, not independently fetched; the Truveta/Knit Health AI-training partnership specifically is the clearest direct evidence of this track feeding AI labs rather than only pharma.)*

**Why this track matters for Your Roster's healthcare wedge:** this is a fundamentally different, much harder business than Track 1 — large, well-capitalized, HIPAA-compliant-by-design institutions built over years around data-linkage and de-identification infrastructure, closer to Mercor's/Scale's *enterprise* data-partnership programs (`SELLING-STRATEGY.md`) than to their expert-marketplace model. Not a realistic near-term target for a pre-seed company's wedge — Track 1 (expert judgment) is the relevant comparison set, not Track 2.

## Track 3: The labs bypass vendors entirely via acquisition — a real consolidation risk

- **OpenAI acquired Torch Health** (a "unified medical memory" health-data-interoperability startup) for a reported **$60–100M** (figures vary by source — HTN/hlth.com/Silicon Republic report ~$100M, CNBC/Built In report closer to $60M) in January 2026, folding it directly into **ChatGPT Health**. Torch's co-founders joined OpenAI to lead integration. *(HIGH that the acquisition happened, MED on the exact price given source disagreement — verified via multiple corroborating outlets found via search)*
- **Anthropic launched "Claude for Health"** / "Claude for Healthcare & Life Sciences," targeting health systems and payers directly, plus an AI drug-discovery program ("Claude Science"). *(HIGH — verified via search of Anthropic's own announcements and trade press)*

**Why this matters:** mirrors the exact pattern found in the government-demand research (Pass 12) — labs increasingly prefer building or *buying* the capability outright once a vendor proves the model works, rather than sustaining an arms-length purchasing relationship. This is a real risk for any small healthcare-data vendor: success can just as easily attract an acquisition offer (or get out-competed once the lab builds the capability in-house) as it attracts a durable supply contract.

**One claim checked and found to be speculation, not evidence:** an opinion piece ("OpenAI and Anthropic want your medical data") raises concerns that ChatGPT Health/Claude for Health data could eventually be monetized to insurers or pharma companies — but names no specific vendors, deals, or figures, and both companies state health conversations won't be used for training. Treat this as a trust/privacy narrative worth watching, not as evidence of an actual data-sale arrangement. *(Verified via direct fetch — confirmed the piece is argumentative/speculative, not investigative)*

## Bottom line

"Who sells medical data to the buyers" has three different answers depending on which data type: **expert-judgment sellers** (Mercor, Surge, Scale, Handshake, Micro1, plus the specialized Centaur Labs and multi-domain AfterQuery) are the right comparison set for Your Roster's healthcare wedge — same mechanic as the government track, same buyers. **Structured clinical/EHR data sellers** (Truveta, Datavant, Komodo Health, HealthVerity, IQVIA) are a different, much harder business, not a near-term target. And **the labs themselves are increasingly buying data capability outright** (Torch Health) rather than only purchasing from vendors — a consolidation dynamic worth watching as this space matures further.

## Sources

Verified via direct fetch: mercor.com/experts/healthcare/, thehumansintheloop.ai (medical-data-concerns article). All other findings from live web search in this pass (2026-08-16) — see inline citations above for per-claim confidence.

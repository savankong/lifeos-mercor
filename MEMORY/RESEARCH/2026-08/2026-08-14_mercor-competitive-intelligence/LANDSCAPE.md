\# Landscape — The AI Expert-Data / Human-Feedback Market

*Synthesized narrative layer. Pass 4 — 2026-08-14. See ENTITIES.md for sourcing status per entity and individual Companies/People/Products/Technologies/Trends files for citations.*

## The shape of the market

Through 2023–2024 this market was dominated by a small number of large, VC-backed data-labeling vendors, with **Scale AI** as the clear leader supplying most frontier labs. That structure broke in **June 2025** when Meta bought a 49% stake in Scale for $14.3B and pulled founder Alexandr Wang in-house — instantly compromising Scale's neutrality for every other lab. Google, OpenAI, and xAI reportedly pulled back within weeks, and the resulting multi-hundred-million-dollar reallocation of annual spend is the single most important structural event shaping every company profiled in this vault. (See `Trends/Post-Scale-Meta-Neutrality-Shift.md`.)

Seven companies absorbed that reallocated spend, each with a somewhat different angle:

- **Surge AI** — bootstrapped, ~1M annotators, broad RLHF/red-teaming, reportedly "took the frontier-lab crown." The only major player with no VC/strategic-investor neutrality question — though it was reportedly in fundraising talks itself as of mid-2025, which would end that distinction.
- **Mercor** — credentialed-expert niche (doctors, lawyers, PhDs) for reasoning/professional-domain data; fastest-growing by reported ARR; now the vault's focus entity.
- **Micro1** — near-identical model to Mercor at roughly 1/7th the scale — the best available "is this Mercor-specific or category-wide" comparison point.
- **Handshake AI** — a 2014-founded university-recruiting company that pivoted an existing large network into AI data almost overnight; potentially the fastest *relative* mover, though its most eye-catching revenue figures remain unverified against a primary, non-paywalled source (see `Companies/Handshake-AI.md`).
- **Turing** — coding-data specialist, profitable, most capital-efficient of the venture-backed players (~$300M blended ARR on $225M raised at a $2.2B valuation) — but that ARR figure blends its original talent-hiring business with AI-data revenue, making it not directly comparable to Mercor's AI-data-only numbers.
- **Scale AI** — the incumbent everyone above took share from. Interim CEO Jason Droege guided 2026 revenue to ~$1B, down from ~$2B in 2025 — the clearest single quantified data point on how much value the Meta deal transferred to competitors. **As of August 10, 2026, Scale named a permanent CEO, Francis deSouza** (ex-Google Cloud COO, ex-Illumina CEO) — a very recent change, six days before this update. Not exiting the market; pivoting toward enterprise-deployment clients (Mayo Clinic, Pentagon cited) as a second act.
- **Invisible Technologies, Snorkel AI** — named repeatedly as part of the post-Scale reallocation but still only lightly profiled or PENDING — see ENTITIES.md.

## Talent-Market Segmentation: everyone sells to the same labs, but sources talent very differently

All seven companies above pitch roughly the same thing to AI labs (trustworthy human judgment for post-training). Where they actually differ — and where the real moats are — is **who supplies that judgment and how each company sources them.** This turns out to be a cleaner differentiator than the demand-side pitch:

| Company | Talent segment | Sourcing channel | Rate ceiling | Distinctive angle |
|---|---|---|---|---|
| **Mercor** | Mid-to-senior credentialed professionals (doctors, lawyers, PhDs, ex-bankers/consultants) | Open market, own AI-vetting funnel | ~$150–200/hr | Applied professional judgment from people already mid-career |
| **Surge AI** | Ultra-elite specialists (Supreme Court clerks, Pulitzer winners, McKinsey partners, Ivy professors) | Open global community, no pipeline | $200–400/hr | Highest bar in the market; scarcity/prestige positioning |
| **Handshake AI** | Students, new grads, graduate-level scholars (3M+ grad degrees, 500K+ PhDs) | Owned university pipeline — 92% of top 500 US universities | ~$100–125/hr | Near-zero incremental talent-acquisition cost via pre-existing network |
| **Turing** | Software engineers/developers globally | Geographic labor arbitrage (India, LatAm, Africa, SE Asia) | $50–150+/hr | Only player built on cost-of-living arbitrage rather than credential depth |
| **Micro1** | Early-career to PhD/industry leaders, broad domains | Open market, own AI-vetting funnel (Mercor clone) | Comparable to Mercor | Best like-for-like read on whether Mercor's model is repeatable |
| **Scale AI** | Mass-market general population (Outlier/Remotasks) + separate specialist tier | High-volume consumer gig recruiting | $20–40/hr (mass tier) | Breadth over selectivity — arguably why it was most exposed to the neutrality shock |
| **Invisible Technologies** | Not talent-tier-branded; positions on process, not people | Traditional BPO/managed-service sourcing | Not disclosed | The one player selling operational maturity, not a talent story |

*(Table synthesizes figures from each company's own "Talent Market Focus" section — see individual Companies/ files for per-cell sourcing and confidence tags; several cells are MED confidence pending primary-source verification.)*

**Reading this table:** the credential-tier players (Mercor, Surge, Micro1) are really competing for the same open-market pool of professionals and will feel each other's pricing pressure directly. Handshake and Turing aren't competing on that same pool at all — they've each captured a structurally different supply channel (university network; global engineering labor market) that the credential-tier players don't have easy access to. That makes Handshake and Turing look less like head-to-head Mercor competitors and more like **parallel bets on different labor markets**, which matters for any assessment of how "crowded" this space really is.

## Where Mercor sits

Mercor's growth (~$75M ARR Feb 2025 → ~$2B run-rate mid-2026) tracks almost exactly the post-Scale/Meta window, per Contrary Research — meaning a large share of Mercor's growth story is *market reallocation*, not necessarily durable company-specific advantage. Its actual defensibility claim is the AI-vetting/matching "flywheel" (see `Products/Mercor-AI-Vetting-Assessment.md`) plus its specific credentialed-expert positioning, which Surge (breadth-first) and Handshake (network-first) don't directly replicate — but Micro1 does, at smaller scale.

Two 2026 events complicate the growth story and are worth weighing heavily in any investment/partnership decision:

1. **The March 2026 LiteLLM supply-chain breach**, which cost Mercor its Meta contract (paused indefinitely) and exposed up to 4TB of internal/customer data. This is a direct demonstration that the "neutrality" advantage competitors gained from Scale's fall can be lost just as fast through a security failure — trust in this market is fragile in both directions. (See `Trends/AI-Data-Vendor-Security-Trust-Risk.md`.)
2. **The Deeptune acquisition governance flag** — CEO Foody personally angel-invested in Deeptune before having Mercor acquire it three months later, an insider-positioning pattern he characterized to Fortune as intentional ("the main motivation"). Not illegal or even necessarily improper, but a governance signal worth tracking, especially as Mercor pursues a reported $20B valuation raise. (See `Companies/Mercor.md`.)

## Where this needs more work (post pass-4)

Both breadth and depth gates are now met (see `ENTITIES.md`). Remaining open items, none gate-blocking:

1. **Invisible Technologies and Snorkel AI** remain thin/PENDING — lower priority since both are MEDIUM-value in this competitive set, but worth closing if the requester wants full category coverage.
2. **Handshake AI's most dramatic revenue claims** (~$1B annualized by April 2026) remain unverified against a primary, non-paywalled source after two failed fetch attempts (403, then 503) — would need a different source entirely (direct company statement, SEC-adjacent filing) to upgrade past MED confidence.
3. **Market-sizing** is now anchored to one verified primary figure (Fortune Business Insights) but the CONFLICT with other firms' estimates reflects a genuine scope disagreement in the industry (raw datasets vs. broader human-labor spend), not a research gap — flagging this as resolved-as-CONFLICT rather than pending further search.
4. **Government-contracting / federal-spend angle** — confirmed **out of scope** for this research (requester approved the neutrality/durability angle as the intended direction). Not pursued.

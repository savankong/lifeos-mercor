\# Your Roster's Opportunity in the AI Expert-Data Labor Market

**Status:** RESEARCHED
**Pass 8 — 2026-08-16**
**This is now the primary framing document for this vault.** Everything researched in Passes 1–7 (company profiles, funding, business models, talent segmentation, data-vendor programs) is preserved as supporting material — see `INDEX.md` — but the lens has changed. This vault started as generic Mercor competitive intelligence, then briefly explored a data-brokerage angle based on a misread of what this research is for. Neither was quite right. **Your Roster is a warm-intro job-search platform, not a data broker**, so the actual question is: is the AI expert-data labor market (Mercor, Scale AI, Surge AI, Handshake AI, Turing, Micro1, Invisible Technologies) a good target vertical for Your Roster's actual product?

## What Your Roster actually does (for context)

Per the product description provided directly: Your Roster ingests a user's LinkedIn connections export, cross-references those connections' employers against companies with public job boards (Greenhouse, Lever, Ashby, or a generic careers page), scores open roles on relevance + connection strength (60/40), and drafts an editable warm-intro request — the user always sends it themselves. A company is **never** surfaced without an existing (or, opt-in, multi-hop) connection there. Core users: job seekers with 5+ years of professional network who want help finding *where* to ask for an intro, not a mass-application tool.

## Why this vertical is a strong fit

1. **It's hiring aggressively, right now, in public.** Scale AI alone shows **210 open roles** on its Greenhouse board as of this research. Mercor, Handshake AI, and Scale AI are all growing headcount fast off triple-digit revenue growth (see `LANDSCAPE.md`) — exactly the hiring-velocity signal that makes a company cluster worth targeting for warm-intro discovery, since more open roles means more chances for any given user's network to actually overlap with a live opening.
2. **It's a hot, legible, story-friendly sector.** "AI's newest billion-dollar labor market" is an easy hook — three of these founders are literally the youngest self-made billionaires in the world (Mercor), one bootstrapped to $1.4B revenue with no VC (Surge AI), one is a 2014 company that reinvented itself overnight (Handshake). That's a marketing angle most B2B verticals don't have.
3. **The specific talent profile these companies recruit overlaps heavily with Your Roster's likely user base.** Mercor, Micro1, and Surge AI specifically target mid-career professionals — ex-investment bankers, consultants, lawyers, doctors, engineers (see `LANDSCAPE.md`'s talent-segmentation table) — i.e., exactly the "5+ years of professional network" user Your Roster is built for, not entry-level job seekers.
4. **The ATS/board coverage lines up with what Your Roster already parses.** See table below — this vertical isn't a stretch case for the board-discovery pipeline; it's squarely inside what it already supports.

## Target-company matrix

| Company | Job board | Your Roster compatibility | Hiring signal | Talent profile it recruits |
|---|---|---|---|---|
| **Mercor** | [jobs.ashbyhq.com/mercor](https://jobs.ashbyhq.com/mercor) — **Ashby** | Directly supported | Actively hiring (e.g. Data Partnership Lead, Healthcare Data Partnerships Lead were open reqs as of this research) | Credentialed mid/senior professionals |
| **Scale AI** | [job-boards.greenhouse.io/scaleai](https://job-boards.greenhouse.io/scaleai) — **Greenhouse** | Directly supported | **210 open roles** confirmed live on their board — the strongest hiring signal in this set | Broadest range — from mass-market gig roles to senior enterprise/BD hires (post-deSouza pivot toward enterprise deployment) |
| **Handshake AI** | [jobs.ashbyhq.com/handshake](https://jobs.ashbyhq.com/handshake) — **Ashby** | Directly supported | Growing fast off the AI-unit pivot | Mixed — corporate roles at Handshake itself skew standard tech/ops; separate from its student/grad-scholar *contractor* network |
| **Surge AI** | surgehq.ai/careers — **custom/generic page** (not a named ATS) | Supported via generic-careers-page fallback | Small team (~110–121) but a live careers page exists for corporate roles, distinct from its expert-contractor "Workforce" funnel | Small, highly selective corporate hiring |
| **Turing** | developers.turing.com — **custom platform**, not a standard ATS | Likely needs generic-page handling; may not fit the Greenhouse/Lever/Ashby pattern cleanly — worth a direct pipeline test rather than assuming | Unclear from this pass | Software engineers (global), separate from its own talent-cloud marketplace |
| **Micro1** | micro1.ai/careers — **no external ATS domain found** | Likely generic-page fallback; not independently confirmed working | Unclear from this pass | Broad credentialed professionals (Mercor-like) |
| **Invisible Technologies** | invisibletech.ai/careers — **no external ATS domain found**, page appeared to dynamically load 0 results at fetch time | Unconfirmed — worth a live pipeline test | Unclear | BPO/managed-service roles |

*(Confidence: HIGH for Mercor/Scale AI/Handshake AI's ATS platform and Scale AI's 210-role count, all verified via direct fetch. MED-LOW for Surge AI/Turing/Micro1/Invisible Technologies — their career pages didn't cleanly expose an external ATS link to WebFetch, which is a real signal about how *hard* automated parsing might be for them, not just a research gap. Worth validating directly against Your Roster's actual pipeline rather than trusting this table blindly — a JS-rendered page that defeats a research fetch could still resolve fine in a real scraper, or could be a genuine pipeline gap worth knowing about early.)*

## The alumni-network finding — a concrete proof point for the multi-hop thesis

While researching who to contact at these companies (Pass 6–7), a pattern emerged that's directly relevant to Your Roster's core product bet: **two senior Handshake AI executives came from Scale AI** — Yang Zhao (Chief Business Officer) spent 4 years at Scale AI before joining Handshake AI in January 2025; Sahil Bhaiwala (Chief Strategy and Innovation Officer) also came from Scale AI, where he ran the International Public Sector unit. Both are profiled with LinkedIn links in `People/Yang-Zhao.md` and `People/Sahil-Bhaiwala.md`.

This is a small but real illustration of exactly the graph structure Your Roster is built to exploit: **someone with a first-degree Scale AI connection has a plausible second-degree (multi-hop, opt-in) path into Handshake AI's leadership team** — not a hypothetical, a documented, named, dated case. Scale AI's own scale (thousands of employees across its history, 210 open roles today) makes it a large alumni pool feeding into this entire adjacent labor market — worth treating as a specific "source company" hypothesis to test against real user upload data: **do users with Scale AI connections show elevated multi-hop reach into Mercor, Handshake AI, Surge AI, Turing, and Micro1?** This vault can't answer that without live product data, but it's a concrete, testable hypothesis this research surfaced.

## Illustrative "who you might already know" examples

Reframed from the earlier (data-brokerage) framing — these are not outreach targets for a deal, they're examples of the kind of senior, well-documented, LinkedIn-findable people populating this vertical, useful for validating the product thesis or as example content:

- **Yang Zhao** — Handshake AI CBO. Ex-Scale AI, ex-Zumper. [LinkedIn](https://www.linkedin.com/in/yangczhao/)
- **Sahil Bhaiwala** — Handshake AI Chief Strategy Officer. Ex-Scale AI, ex-Bain & Company. (No verified LinkedIn URL found — see `People/Sahil-Bhaiwala.md`.)
- **Edwin Chen** — Surge AI founder/CEO. Ex-Google, Twitter, Dropbox, MIT. [LinkedIn](https://www.linkedin.com/in/edwinzchen/)
- **Francis deSouza** — Scale AI CEO (from Aug 10, 2026). Ex-Google Cloud, ex-Illumina, ex-Symantec.
- **Sundeep Jain** — Mercor President. Ex-Uber, ex-Google, ex-Zynga.
- **Jason Droege** — Scale AI's outgoing interim CEO. Ex-Benchmark, ex-Uber.

Anyone with a first-degree connection to Uber, Google, Bain, Scale AI, Zynga, Benchmark, or Illumina has a plausible path into this vertical's leadership — a reasonable base rate given how common those employers are among experienced professionals, which is exactly Your Roster's target user.

## GTM ideas for Your Roster (not yet validated — starting points, not recommendations)

1. **A vertical landing page / content piece**: "See who you already know at AI's hottest new labor market" featuring Mercor, Scale AI, Handshake AI, Surge AI by name — leans on the youngest-billionaires and bootstrapped-to-$1B-plus-revenue narratives that already have press attention, which lowers the cost of explaining why this company cluster matters.
2. **Targeted outreach to professionals from the exact adjacent industries these companies recruit from** — ex-banking, ex-consulting, ex-law, since Mercor/Micro1/Surge explicitly want that profile as *contractors*, and the same population is a plausible fit for Your Roster's target *user* wanting a warm intro into a *corporate* role at these companies (a distinct thing from the contractor-marketplace side — worth being careful not to conflate the two in messaging).
3. **Use Scale AI's 210-role board as a proof-of-concept dataset** for demoing the product's scoring/ranking on a company that's unambiguously growing and unambiguously has broad role diversity (engineering, enterprise sales, forward-deployed engineering, product design) — good for testing relevance-scoring range.

## What this doesn't establish

- No live test of Your Roster's actual pipeline against any of these seven companies' boards was performed — the ATS identification above is manual research, not confirmation that ingestion actually works cleanly for each.
- No user-network data was analyzed — the "Scale AI alumni feed this whole vertical" hypothesis is based on two documented individuals, not a systematic mapping of the sector's talent graph.
- No confirmation that these companies' hiring managers are receptive to warm-intro-style outreach specifically (vs. their formal ATS pipelines) — worth keeping in mind before building messaging that assumes it.

## Sources

All company/ATS/role-count facts verified via direct fetch in this pass — see individual URLs inline above. Yang Zhao / Sahil Bhaiwala background: `People/Yang-Zhao.md`, `People/Sahil-Bhaiwala.md` (Pass 6–7 sourcing carries over unchanged).

# AI Product Portfolio — Hari Hara Kumar

> **Software engineer becoming an AI Product Manager — in public.**
> Turning ambiguous AI capability into product decisions, then shipping the artifacts that prove it.

`AI/ML Product Manager` · `LLM & Agent products` · `RAG` · `Evals` · `Ex-software engineer`

<!--
  FILL-IN CHECKLIST (search for {{...}} and [ ... ] and replace, then delete this comment):
  {{github-username}} · {{linkedin-url}} · {{medium-url}} · {{x-handle}} · {{portfolio-site-url}}
  [X years] engineering experience · [primary domain] · [email or "DM on LinkedIn"]
  Update the "Currently" line and the Status column each time you ship. That's the whole maintenance job.
-->

---

## 60-second read (for hiring managers)

- **Who I am.** [X years] shipping production software ([primary domain]); now doing AI PM work end-to-end — problem framing, model/eval/cost decisions, and shipped artifacts.
- **What's here.** Four AI product projects, each documented as *decisions and outcomes*, not just code. Every project has a `DECISIONS.md` — read that first if you're short on time.
- **Start here.** → [Project 1: AI Product Teardown Series](./projects/project-1-teardown-series/) *(strongest artifact so far)*
- **Currently.** Day 11 of a 90-day AI-PM build (Phase 1 · Foundations). This repo updates roughly daily — status is honest, including what isn't done yet.

---

## What this portfolio is meant to prove

A PM's repo isn't a code-golf trophy. Its job is to show I can **scope, direct, and evaluate** AI work and make credible product calls about it. In priority order, every project here tries to demonstrate:

1. **Problem framing** — a real user pain, not an interesting model looking for a use.
2. **Judgment under AI-specific constraints** — build-vs-buy, accuracy/latency/cost tradeoffs, hallucination and safety risk, and *when not to use AI*.
3. **Technical fluency** — enough systems understanding to scope AI work credibly and talk to engineers as a peer.

---

## The projects (the spine)

The four projects below are the point of this repo. Folders under [`phase-1-foundations/`](./phase-1-foundations/) (and later phases) are the **daily working notes** that feed them — depth, not headline.

| # | Project | What it proves | Status | Read |
|---|---------|----------------|--------|------|
| 1 | **AI Product Teardown Series** | Product thinking + analytical writing across a consumer app, a B2B copilot, and a comparative piece | 🚧 In progress (Teardown 1 analysis done; publish next) | [→](./projects/project-1-teardown-series/) |
| 2 | **Prompt & Eval Suite** | The top 2026 AI-PM signal: golden dataset, multi-model eval, LLM-as-judge, failure taxonomy, red-teaming | ⏳ Planned (starts Day 23) | [→](./projects/project-2-prompt-eval-suite/) |
| 3 | **AI Feature: PRD → Prototype** | A full AI PRD (model choice, eval plan, safety, cost model) taken to a working, evaluated prototype | ⏳ Planned (starts Day 38) | [→](./projects/project-3-prd-to-prototype/) |
| 4 | **Capstone: Ship a Micro AI Product** | End-to-end: user interviews → PRD → build → evals → safety → launch → real metrics → honest retro | ⏳ Planned (starts Day 52) | [→](./projects/project-4-capstone-micro-product/) |

**Status legend:** ✅ complete · 🚧 in progress · ⏳ planned (with the day it starts)

> Why the honesty? A portfolio caught mid-build reads as *senior* when the status is truthful and the retros are candid. Success theater reads as junior. I'd rather you trust the numbers.

---

## How to navigate this repo

```
ai-pm-portfolio/
├── projects/                 ← the showcase: 4 product-framed project READMEs + DECISIONS.md
│   ├── project-1-teardown-series/
│   ├── project-2-prompt-eval-suite/
│   ├── project-3-prd-to-prototype/
│   └── project-4-capstone-micro-product/
├── phase-1-foundations/      ← daily working notes (Days 1–21): the learning + build log
│   └── day-NN-topic/README.md
├── templates/                ← reusable PM artifacts (teardown, AI PRD, eval sheet, DECISIONS)
├── DECISIONS.md              ← repo-level meta-decisions (why a monorepo, how it's structured)
└── assets/                   ← diagrams, screenshots, banner
```

- **Recruiter / hiring manager?** Stay in [`projects/`](./projects/). Each project README opens with a plain-language problem statement and a decisions-and-tradeoffs section.
- **Engineer digging deeper?** The daily notes in [`phase-1-foundations/`](./phase-1-foundations/) show the reasoning as it was built, and every project's `DECISIONS.md` records alternatives considered.

---

## How I work (the operating system)

A fixed daily loop, six days a week, for 90 days: **60 min learn · 90 min build · 30 min write**. One rule cuts across everything — **publish decisions, not just deliverables.** Anyone can show what they built; showing *why*, and what I rejected, is the product-management signal.

- **Build beats read.** When time runs short, I cut learning, never building.
- **Everything ships to GitHub the day it's made.** This repo *is* the resume.
- **Honest numbers only.** A capstone with 12 real users and a sharp retro beats inflated vanity metrics.

---

## Selected decisions (the good stuff)

The `DECISIONS.md` files are where the actual thinking lives. A few worth your time:

- **Repo structure — monorepo over per-project repos.** → [DECISIONS.md](./DECISIONS.md#d-001-one-monorepo-instead-of-four-repos)
- *(As projects ship, link 2–3 more high-signal decisions here — e.g., "RAG over fine-tuning because the knowledge base updates daily," "capped context to control latency and cost.")*

---

## Elsewhere (the spokes)

This repo is the hub. The long-form story and day-to-day thinking live here too:

- **LinkedIn** — {{linkedin-url}} *(weekly build-in-public posts, project announcements)*
- **Medium** — {{medium-url}} *(the deep-dive teardowns and case studies)*
- **X / Twitter** — {{x-handle}} *(weekly recap threads)*
- **Portfolio site** — {{portfolio-site-url}} *(coming in Phase 4)*

---

## About me

[2 lines: who I am, the problem space I care about, and the engineer→AI-PM through-line. Keep it human, not a resume paste.]

**Open to AI PM roles.** Best way to reach me: [email] or DM on LinkedIn.

---

<sub>Built as part of a structured 90-day engineer-to-AI-PM plan. Notes are written in my own words; where AI tools assisted implementation, the relevant README says so.</sub>

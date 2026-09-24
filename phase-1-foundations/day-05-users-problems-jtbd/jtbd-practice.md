# JTBD Practice — Perplexity

**Date:** 2026-09-24 · **Day 5 of 90** · Phase 1, Week 1
**Subject:** Perplexity — an AI answer engine that responds to questions with a synthesized answer plus inline citations, aimed at people who would otherwise run a web search.
**Why this app:** I use it several times a working day, so I can observe my own behaviour rather than guess at someone else's; and it is a strong Day 10 teardown candidate, which makes today's job map reusable. Full reasoning in [`DECISIONS.md`](./DECISIONS.md).

Evidence tags used throughout: `[measured]` > `[observed]` > `[stated]` > `[guessed]`

> **How to read the evidence in this document.** Nothing here is `[measured]` — I have no access to product analytics. `[observed]` means I watched it happen in my own logged sessions. `[stated]` means a real person wrote it in a review or a thread, quoted verbatim and screenshotted in `assets/`. `[guessed]` appears exactly twice and is labelled as such.

---

## Evidence base

| Source | Volume | Rung | Notes |
|---|---|---|---|
| My own sessions | 10 | observed | 2026-09-18 → 2026-09-23, logged immediately after each use: trigger, what I did next, whether I re-checked the answer |
| App-store / Play reviews | 8 quotes | stated | sorted by most recent and most critical; screenshots in `assets/reviews/` |
| Reddit / community threads | 4 | stated | searched for switching, "worth it", "alternative to" posts |

**Representative quotes** *(replace these with your own — verbatim, with source and date)*

> "‹paste the exact review sentence›" — Play Store, 2★, 2026-09 `[stated]`
> "‹paste the exact review sentence›" — App Store, 5★, 2026-08 `[stated]`
> "‹paste the exact thread comment›" — r/‹subreddit›, 2026-07 `[stated]`

### Switch timeline (self-interview, 10 min)

| Stage | What happened |
|---|---|
| First thought | Noticed I was scrolling past the first page of search results more often on technical questions, and resenting it `[observed]` |
| Passive looking | Saw citation-style AI answers mentioned in two newsletters; did nothing about it for roughly a month `[observed]` |
| The event | Spent 20 minutes reconstructing an answer I had already found the previous week, because I had not kept the tab `[observed]` |
| Active looking | Compared three options over a week: a general chat assistant, plain search, and this. Also considered simply keeping better notes `[observed]` |
| Deciding | What nearly stopped me: not trusting a synthesized answer I could not audit. What overcame it: the inline citations made auditing cheap enough to try `[observed]` |
| First use | First real use was mid-task, not exploratory — which tells me the job is an interruption job, not a research job `[observed]` |

**What the timeline changed in my thinking:** I would have written the situation as "when I want to research something." The actual trigger is an *interruption to other work*. That single correction reframes every job below.

---

## Job 1 — Keep moving through an unfamiliar patch  *(functional-dominant)*

**When** I'm mid-way through a task and hit a term or a claim I can't evaluate,
**I want to** reach a usable answer and its sources in one pass,
**so I can** keep working instead of opening six tabs and losing the thread of what I was doing.

| Dimension | What it is here |
|---|---|
| Functional | Resolve a blocking unknown without leaving the task context. Dominant. |
| Emotional | Mild frustration at being interrupted; relief at not having to context-switch. Low intensity. |
| Social | None — nobody sees this job happen. |

- **Competing alternatives:** plain web search (cheap, familiar, genuinely better for navigational queries); asking a colleague (higher quality, socially expensive, slow); guessing and moving on `[observed]`
- **Four forces:** *Push* — the cost of context-switching mid-task. *Pull* — one answer instead of ten results. *Habit* — a search box is decades of muscle memory. *Anxiety* — "is this answer even right?"
- **Outcome measures the user would recognise:** time from question to resumed work; number of tabs opened after the answer `[observed]` — if I still open five tabs, the job was not done.

---

## Job 2 — Know what I can stand behind  *(emotional-dominant)*

**When** I'm about to repeat something I learned from an AI answer to someone who knows the subject better than I do,
**I want to** know which parts of it I can stand behind,
**so I can** speak up without the quiet fear of being confidently wrong in public.

| Dimension | What it is here |
|---|---|
| Functional | Separate the load-bearing claims from the decorative ones and verify the first group. Secondary. |
| Emotional | Avoiding the specific humiliation of repeating a fabrication to an expert. Dominant, and high intensity. |
| Social | Adjacent — the fear is about how I will be seen, but the work is private. |

- **Competing alternatives:** re-verifying every claim manually (defeats the purpose); only repeating things I already knew (safe, useless); saying nothing `[observed]`
- **Four forces:** *Push* — one public correction is remembered far longer than fifty quiet successes. *Pull* — citations make spot-checking cheap. *Habit* — trusting my own reading. *Anxiety* — a citation that exists but does not support the sentence attached to it, which I hit twice in ten sessions `[observed]`
- **Why this is the most valuable job of the three:** it is the one where the product can lose. A wrong answer costs a few seconds on Job 1. A wrong answer that I repeated in front of my team costs trust, and I will not return.
- **Outcome measure:** verification effort per answer — how many citations I open before I am willing to repeat the claim `[observed]`. Across 10 sessions: 0 for low-stakes, 3+ for anything I intended to say aloud.

---

## Job 3 — Bring evidence, not opinion  *(social-dominant)*

**When** a colleague asks me where something stands and expects an answer today,
**I want to** hand over something sourced that survives their spot-check,
**so I can** be read as the person who brings evidence rather than opinions.

| Dimension | What it is here |
|---|---|
| Functional | Assemble a short, sourced summary quickly. Secondary. |
| Emotional | Pride in the output; anxiety about it being audited. |
| Social | The output is judged by other people, and it carries my name. Dominant. |

- **Competing alternatives:** forwarding a link and letting them read it (cheap, shifts the work back); asking the person who actually knows; producing nothing and saying "I'll find out" `[observed]`
- **Four forces:** *Push* — being the person who always says "not sure." *Pull* — a shareable, sourced artifact in minutes. *Habit* — forwarding links. *Anxiety* — output that reads as machine-written, which is socially worse than a short honest note `[guessed — I have not tested this with recipients, and it is the assumption I would test first]`
- **Outcome measure:** whether the recipient asks a follow-up question about the content, or about where it came from. The second is a failure.

---

## Is AI the right hire for these jobs?

Applying the five job properties from the Day 5 material:

| Property | Reading for this product |
|---|---|
| Verification cost | **The deciding factor.** Jobs 2 and 3 only work if checking is cheaper than redoing. Citations are the entire product bet. |
| Blast radius | Low for Job 1, high for Job 3 — a wrong claim escapes to other people and attaches to the user's name. |
| Variance tolerance | Acceptable for synthesis and phrasing. Not acceptable for whether a citation supports its sentence. |
| Ground truth | Exists and is checkable — the cited source either says it or does not. This is what makes evals feasible here. |
| Frequency and stakes | Many small-stakes uses (Job 1), few high-stakes ones (Job 3). The rare high-stakes use determines retention. |

**Conclusion:** AI is the right hire for the synthesis, and the wrong hire for the trust. The product succeeds or fails on the verification layer around the model, not on answer quality — which is an app-layer bet, not a model-layer one `[guessed — this is my hypothesis to test on Day 10]`.

---

## Three prioritized opportunities

1. **Make citation support visible, not just citation presence.** Twice in ten sessions a real source was attached to a sentence it did not support `[observed]`. This attacks Job 2, the highest-intensity job. What I would measure: unsupported-claim rate on a labelled sample, and verification clicks per answer.
2. **Carry task context across the interruption.** Job 1 is an interruption job, so the answer should return the user to what they were doing rather than becoming a new session. Measure: tabs opened after the answer; return-to-task rate.
3. **An export that does not look machine-written.** Job 3's anxiety is social, not factual. Measure: share rate, and follow-up questions about provenance versus content.

Ordering rationale: opportunity 1 serves the job with the highest emotional intensity and the largest downside; 2 serves the most frequent job; 3 serves the job with the most social upside but rests on my one untested assumption.

## What I was wrong about

I assumed the job was "search, but better" — a faster version of something I already did. The switch timeline says otherwise: I adopted it during an interruption, not during research, and the thing I actually buy is permission to trust an answer I did not derive myself. Speed was never the job.

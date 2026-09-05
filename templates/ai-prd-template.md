templates# AI PRD — [Feature name]

## 1. Problem & evidence
- Problem: [who, how painful, why now]
- Evidence: [data / interviews / reviews]
- Target users & JTBD: [persona → job]

## 2. Why AI (and why not)
- Model-layer vs. app-layer framing.
- Why not rules / better UX / no-build. **This paragraph is the strongest AI-PM signal in the doc.**

## 3. Solution & scope
- Core flow: [steps]
- Scope cuts (explicitly listed): [what we are NOT building]

## 4. Model & architecture
- API / model choice: [and why]
- RAG or not · context strategy · cost per user per month: [with assumptions]

## 5. Eval plan
- Golden dataset (size, sourcing) · pass criteria · judge design · quality bar to ship.

## 6. Metrics
- Adoption · quality (hallucination / refusal / task success) · latency (p50/p95) · cost per task.

## 7. Safety
- Misuse cases · prompt-injection surface · PII handling · guardrails · fallback UX.

## 8. Rollout
- Beta gates · kill criteria · iteration cadence.

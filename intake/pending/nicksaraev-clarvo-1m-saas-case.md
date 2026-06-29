# Revenue case study: Clarvo -- a $1M-ARR SaaS built with Claude Code (Nick Saraev)

Source: Nick Saraev YouTube, "I Built a $1M/y SaaS with Claude Code, Here's How" (K65vd9EYbDU),
read 2026-06-29. Clarvo = an AI-enabled power dialer for call-heavy local-service industries
(HVAC, plumbing, roofing): make more calls/hour AND lift pickup rate. All revenue figures are
the founder's UNVERIFIED claims (he is also selling the product + his Maker School program).
This is a CASE STUDY -- the durable value is the SaaS-strategy lessons, not the numbers. Scored
for FIT against the operator's portfolio (PrepBrix NEET/JEE education; the forge IP; ng-monitor;
tamiliq).

## The claimed numbers (UNVERIFIED, captured separately)
$1M ARR. Pricing $250/seat/mo, sold as multi-seat deals (a 100-seat deal = $25k MRR = $300k ARR;
a handful of deals = $1M). Claims it lifted one HVAC client's revenue ~66% (+$2M/mo) and that
value-delivered justifies negotiating 10-15% of it. Pricing was found by trial (started ~$100/mo,
raised until it got hard), not a model. Treat all as marketing claims.

## Lesson 1 -- High-touch enterprise SaaS beats low-touch self-serve NOW
The core strategic call. In an era where anyone can vibe-code any SaaS, a low-touch / low-ticket
self-serve tool is fragile: a business owner can just "pay tokens and rebuild it themselves." So go
the OTHER way -- solve a big problem, high-touch, mid-market/enterprise, multi-seat. Clarvo sells to
companies and rolls out to a pre-existing calling team, not to single users. The moat is being too
expensive-to-rebuild and too embedded to churn.

## Lesson 2 -- Pick problems that PAY (the value Venn diagram)
The bottleneck is no longer "can you build it" (everyone can; commits are skyrocketing) -- it is
"what SHOULD you build, and how to price." Aim only at the small slice that is a red-hot burning
problem in a big-budget industry with pre-existing pain and many seats. Avoid the lukewarm
nice-to-haves where ~90% of builders waste time (to-do apps, simple extensions). Clarvo picked call
pickup rate because it costs call-heavy orgs millions; they will pay anything to fix it.

## Lesson 3 -- Value-based pricing; discover the price by raising it
If you provide $X of value you can negotiate 10-15% of it (Clarvo: +$24M/yr to a client ->
negotiate ~$2.4M/yr). And discover the price empirically: pick one, sell, and keep raising until
yes becomes hard -- do not trust a statistical/AI "optimal price." (Corroborates the
[[richardyu-digital-product-business]] price-ladder lesson.)

## Lesson 4 -- Moats in an AGI world: data, regulation, human implementation
When code is free to build, the durable moats are NOT the software:
- DATA: Clarvo's historical call data powers the simulation/optimization; you need real businesses
  to test on (a chicken-and-egg moat newcomers lack).
- REGULATORY: things the model cannot bypass -- A2P phone-number registration, HIPAA in healthcare.
  Bureaucratic/legal processes are natural moats; reframe "the compliance is painful" as "the
  compliance is the barrier to entry I sit behind."
- HUMAN IMPLEMENTATION / onboarding: if the whole product is digital, AI will soon do it better;
  but human onboarding, the relationship that gets an advisory board to rubber-stamp the thing, and
  navigating regulation are durable. Prefer a SaaS that REQUIRES human implementation.

## Lesson 5 -- Frameworks are fluff; keep the codebase model-agnostic
First-hand $1M-ARR confirmation of thin-harness-fat-skills + bitter-lesson-scaffolding: they tried
Hermes, OpenClaw, ~50 context/vector-DB frameworks -- "every additional framework is inversely
correlated with money made" (distraction + regression when the prompt is mediated differently). The
intelligence is in the MODEL, not the wrapper (the "fuzzy steering-wheel cover" analogy); a marginal
framework gain gets absorbed into the next model within days. Vanilla model + a thin CLAUDE.md (he
notes Boris Cherny's own CLAUDE.md is nearly empty). AND keep the codebase MODEL-AGNOSTIC: duplicate
agents.md / claude.md / gemini.md + MCP/skill specs so you can hot-swap models (they use DeepSeek to
arbitrage token cost on long-running refactors, Codex when they hit token limits). Corroborates
llm-gateway + the multi-init-file note.

## Lesson 6 -- The build loop (reusable technique)
Define the problem -> ask the model to ENUMERATE all solutions (he spawns 10 parallel sub-agents x 10
mechanisms each, told to diverge wildly across algorithmic/behavioral/infrastructural/regulatory/
psychological/time/identity categories, no self-censoring for feasibility) -> a human filters the
200-300 ideas down to the 5-6 feasible ones -> design a simulation on historical data -> run a
statistical optimizer (e.g. Bayesian) -> iterate in the simulator -> real-life stress test (it can
fail at any step; real-world confounders break sim-only wins). Corroborates uncorrelated-context-
parallelism (parallel idea sub-agents) + eval-driven-agent-lifecycle (simulate + optimize against
data). The honest caveat he states: data + a way to deploy/parallel-test is the real moat; without a
live business to test on, this step is where most people stall.

## FIT for the portfolio
OFF the primary PrepBrix axis as a business (B2B call-center SaaS, not NEET/JEE education), so NOT a
play to adopt. But several lessons are durable and portfolio-relevant:
- Frameworks-are-fluff / model-agnostic (Lesson 5) is a first-hand revenue-stakes confirmation of the
  curriculum's thin-harness + bitter-lesson stance -- log as corroboration in ConceptForge REFERENCES.
- Pick-problems-that-pay + value-based pricing + price-by-raising (Lessons 2-3) sharpen any future
  PrepBrix monetization decision (still deferred behind the 2026-07-10 clarity milestone per GOALS.md).
- The enumerate-with-parallel-sub-agents-then-human-filter build loop (Lesson 6) is a reusable
  technique the operator can apply to the forge work directly.
Conclusion: logged as a CASE STUDY + lessons, not run as a play. The transferable kernels (anti-
framework discipline, problem-value selection, value-based pricing, the idea-mining loop) are kept;
the call-center SaaS itself is off-portfolio.

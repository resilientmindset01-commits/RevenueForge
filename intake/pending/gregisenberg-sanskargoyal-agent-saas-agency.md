# Revenue-model seed: AI-agent-as-a-service / automation agency (two independent sources, same day)

Source: two unrelated channels, same intake pass (2026-07-05), landed on the identical business
archetype -- Greg Isenberg's own video (@GregIsenberg, 83fWzQSWB10) and a guest on Sanskar Goyal's
interview show (@sanskargoyal, _Km10o29cW8, guest Arian Mahajan). Cross-referenced against
ConceptForge/intake/QUEUE.md's 2026-07-05 entries for both. All dollar figures are guest/creator
UNVERIFIED claims. Scored for FIT against the operator's current portfolio (PrepBrix NEET/JEE
education; the forge-skill-pack "Claude Code Power Pack"; ng-monitor trading; tamiliq).

## Card 1 -- Sell agent labor as a service to SMBs (the wrapper is the moat)
Source video: 83fWzQSWB10 "AI Agents are the new SaaS" (Greg Isenberg, 2026-07-01).
Model: product = the job, not the tool -- sell labor as a service. Pick a workflow with a
paycheck (5 traits: high frequency, clear finish line, touches existing software, learnable
edge cases, felt pain). Shadow the human 10-20 cases before writing any prompt; spec the agent
in 7 parts (trigger, context, tools, allowed actions, approval points, escalation, success).
Build a Minimum Useful Agent -- one of 4 shapes: draft-and-approve, triage, coordinator,
bounded-action (cites Anthropic's workflow-vs-agent framing). The "wrapper" (logs, approvals,
evals, analytics) is what makes it a sellable SaaS, not the raw agent; a 50-example eval set
doubles as a sales asset. Sell the pilot like labor (flat setup fee + monthly, migrate to
outcome/usage pricing later), then productize the repeated pattern across 3 customers in one
niche. Distribute via "workflow teardowns" (old way vs agent way). Includes a 30-day
zero-to-100 execution plan.
FIT: OFF-PORTFOLIO as a direct venture -- no existing SMB client base or services delivery
capacity. The reusable part is the METHODOLOGY, not a venture to launch: the agent-spec-7-parts,
the MUA-4-shapes, and eval-set-as-sales-asset are a clean, portable operating playbook if the
operator (or a future venture) ever sells agent work directly to clients.

## Card 2 -- Same archetype in practice: a LinkedIn-content-driven AI automation agency
Source video: _Km10o29cW8 "How This 22 Yr Old Makes 1 Crore a Month Selling AI Automations"
(Sanskar Goyal, guest Arian Mahajan, 2026-06-27).
Model: the same archetype, running live -- an agency selling "AI infrastructure for Fortune
500s," grown via personal-brand LinkedIn content. Internal tooling: a personal "AI operating
system" in Cursor, with per-client ICP.md / brand-voice.md / hooks.md files that train
Claude/Codex on that specific client's business; an AI-SDR/outbound system (lead scrape +
enrichment + LinkedIn/Reddit profile scraping for personalization + ICP-fit scoring +
automated multi-channel cadence); and a "council" pattern -- parallel consult across 8 LLMs
(GPT, Claude, Grok, Gemini, Manus, Kimi, DeepSeek, Minimax) for high-stakes strategic calls
("the Avengers, different strengths"). CHECKED: the council mechanic is a DEDUP, not new IP --
it is the same cross-vendor multi-model judgment mechanism already covered in
agent-engineering/patterns/agent-spacetime-bounds/PATTERN.md (the Karpathy LLM Council entry:
"a judgment tool, not a calculator" -- wins on open-ended design, loses on checkable/factual).
FIT: DEDUP with Card 1 on the business-model axis (same "sell AI automation as an agency/SaaS
via personal-brand content" archetype) -- same OFF-PORTFOLIO verdict as Card 1. The one fresh,
reusable mechanic: the per-client Cursor-folder-as-company-brain structure (ICP/brand-voice/hooks
files) as a concrete way to onboard an agent onto a specific client's context -- a technique
note, not new venture IP.

## Net for the portfolio
Two unrelated sources landing on the identical business archetype the same day is a real
market-validation signal, not noise: "sell AI agent labor as a service/agency, wrapped in
evals + approvals + analytics, distributed via personal-brand content" is clearly a live,
working model right now, at meaningful scale (guest claims of 1 crore/month, UNVERIFIED).
But it is OFF the operator's current portfolio (education, the skill-pack, trading, tamiliq)
-- it requires an SMB/enterprise client-services business (sales, delivery, ops) the operator
is not currently running, unlike the Koerner-menu Card 1 (sell-Claude-skills ->
[[forge-ip-claude-skill-pack]]) where the operator already owned the raw asset. Per the D10
machinery freeze: NOT recommended for action now. The active priority is converting the
forge-skill-pack asset (already gated NOT-A-PLAY-YET pending GOALS.md adoption + a dated
milestone), not adding a new off-portfolio venture on top of an already supply-heavy operation.
Logged as a menu candidate only: if the operator later wants a genuine agent-as-a-service
secondary venture (distinct from education/trading/skill-pack), this pair is the reference
case to start from -- Card 1's 7-part agent spec + MUA-4-shapes + eval-as-sales-asset is the
concrete operating playbook, and Card 2's per-client-context-folder mechanic is the reusable
client-onboarding technique. No action taken beyond this log.

# RevenueForge -- drain decisions

The verdict layer over the scored model cards in intake/pending/. Draining a card
means: score it for portfolio fit (done in the card), then decide -- GRADUATE to a
VentureForge play, DEDUP against an existing play, route to another lane, or record
an honest NO FIT. Source numbers stay UNVERIFIED; "does not fit" is a first-class
outcome. Operator may clear intake/pending/ once a card is logged here.

## Drained 2026-06-27

### athcanft-revenue-models.md -> NO FIT (no graduation)
Indie-app monetization (ship a throwaway iOS app, buy installs, ad arbitrage). Off
PrepBrix's portfolio -- PrepBrix is a graded-outcome education product, not a
throwaway subscription app. The one transferable part (the near-zero-CPM organic
DISTRIBUTION engine) was already extracted to the youtube-growth lane. No model here
graduates to a VentureForge play. Honest no-fit, logged.

### siliconvalleygirl-6-ai-business-models.md -> 1 graduated (as a lane), 1 candidate, rest dedup/off
Six sourced models, scored in the card. Decisions:
- GEO for local business (Card 2) -> ALREADY GRADUATED, and beyond a single play: it
  became its own lane, geo-distribution (README + checklist + PrepBrix baseline audit).
  This is the strongest portfolio outcome from the menu.
- Productize the forge IP (Cards 1 + 6: AI consultant / fractional Chief AI Officer /
  vertical "GPT-wrapper" product) -> CANDIDATE VentureForge play, NOT auto-graduated.
  The operator already owns the capability (the forges = a Claude/agent-mastery
  curriculum); the play would be to package it as a fractional-CAIO retainer or a
  vertical tool. Needs an operator decision: which vertical + what offer. Held as a
  candidate, not forced into a play.
- AI-native ad agency + AI-UGC at scale (Cards 4 + 5) -> DEDUP. Covered by the
  VentureForge play deronin-ai-ugc-ads-agency.md (the AI-UGC ad-creative model), now
  corroborated by a 3rd source. No new play.
- Voice-AI receptionist (Card 3) -> OFF-PORTFOLIO (local-SMB appointment-setting,
  unrelated to PrepBrix/forge IP). Logged, not pursued.

## Net
No new VentureForge play was auto-created this drain: GEO already graduated into its
own lane, the AI-UGC model dedups an existing play, and the one truly
portfolio-relevant new thread (productize the forge IP as fractional-CAIO / a vertical
tool) is a real candidate that needs an operator go (target vertical + offer) before it
becomes a play. The honest menu state: GEO is the live winner; forge-IP productization
is the next decision; everything else is off-portfolio or already covered.

## Pending-queue audit 2026-09-09 (no new scoring, no cards cleared)

Not a drain. An audit of what is actually IN intake/pending/, because 13 cards had
accumulated over 7-11 weeks with no visible state and the folder name ("awaiting
scoring") had stopped being true for several of them.

WHAT THE AUDIT FOUND, by matching each card against this file:
- ALREADY LOGGED HERE, so clearable per the rule at the top of this file: 
  athcanft-revenue-models (NO FIT, drained 06-27) and
  siliconvalleygirl-6-ai-business-models. Both are decided; only the file move is
  outstanding, and the README says that is the operator's to do.
- SCORED IN THE CARD BUT NEVER LOGGED HERE (3). The FIT judgment exists inside the
  card and the verdict layer never caught up:
  * dannywhy-ai-content-income-models -- the card reads "FIT: OFF-PORTFOLIO."
  * gregisenberg-sanskargoyal-agent-saas-agency -- the card reads "FIT: OFF-PORTFOLIO
    as a direct venture."
  Both are recorded below as OFF-PORTFOLIO on the authority of their own FIT lines.
  That is transcription, not a new judgment.
  * koerneroffice-ai-business-models -- the card reads "FIT: HIGH / most
    portfolio-relevant model on either menu." THIS IS THE ONE THAT NEEDS AN OPERATOR
    GO. A HIGH-fit card sitting unlogged for ten weeks is the most expensive item in
    the queue, because it is the one that was worth acting on.
- NOT MODEL CARDS AT ALL (3). making-money-with-claude-thread, rclaudeai-week-sweep
  and showcase-megathread-signals are SOURCE SWEEPS -- market signal logs, not models
  with a FIT score to give. They will never drain under this file's rules because
  they are not the kind of thing it scores. They belong in a references or signals
  location, not in a queue that implies a pending decision.
- STILL AWAITING A DRAIN (5): mollykeyser-digital-product-funnel,
  nicksaraev-clarvo-1m-saas-case, patrickdang-1person-claude-business,
  richardyu-digital-product-business, sandyleeai-linkedin-crm-cowork.

So the honest queue is FIVE cards plus one decision, not thirteen.

### dannywhy-ai-content-income-models.md -> OFF-PORTFOLIO (transcribed from the card)
Build-a-game-with-Claude content-income model. The card's own FIT line rules it
off-portfolio as unrelated to education or the forges. Logged here so the verdict is
in the verdict layer rather than only inside the card.

### gregisenberg-sanskargoyal-agent-saas-agency.md -> OFF-PORTFOLIO (transcribed)
Agent-as-a-service / automation agency: sell the labour, not the tool. The card rules
it off-portfolio as a direct venture on the grounds that there is no existing SMB
client base to sell into. Logged, not pursued.

### OPEN FOR THE OPERATOR: koerneroffice-ai-business-models.md
Package subject-matter expertise as a stack of Claude skills and sell that. The card
scores it HIGH and calls it the most portfolio-relevant model on either menu, which
makes it the only queue item whose delay has a real cost. It needs a GRADUATE / DEDUP
/ NO-FIT ruling, and that ruling is not one an audit can make.

### PROCESS NOTE
Three of these cards carried a FIT verdict inside them while sitting in a folder whose
name says "awaiting scoring". The scoring layer and the verdict layer drifted apart,
so the queue length stopped describing the queue. Same failure this ecosystem hit three
times on 2026-09-09 in other lanes: a record maintained faithfully by its most visible
measure -- here, file count -- while the property that mattered, decidedness, drifted.
The cheap guard is to log the verdict HERE at the moment the FIT line is written,
rather than treating the card as the record.

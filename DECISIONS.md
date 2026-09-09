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
  * koerneroffice-ai-business-models -- SEE THE CORRECTION BELOW. This bullet claimed
    it needed an operator GO. It did not: the card records its own graduation on
    2026-06-29 and the product has been built since 2026-07-09. What is open is a
    date, not a ruling.
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

### CORRECTED 2026-09-09: koerneroffice-ai-business-models.md was NEVER awaiting a ruling
The entry that stood here asked the operator for a GRADUATE / DEDUP / NO-FIT ruling on
Card 1. That request was wrong, and it was wrong because the audit read the card's FIT
line and stopped one sentence short. The next sentence says:

    GRADUATED 2026-06-29 -> VentureForge/intake/pending/forge-ip-claude-skill-pack.md

So it was graduated ten weeks ago. Asking for the ruling again invented a decision that
had already been made, and parked a built product behind it.

WHAT IS ACTUALLY TRUE, verified on disk:
- The graduated brief DOES NOT EXIST. VentureForge/intake/pending/ contains only
  _TEMPLATE.md. The graduation was recorded in the card and never landed at its
  destination, and nothing checked the link.
- The product was built anyway. `forge-skill-pack` holds the Claude Code Power Pack --
  landing.html, SELL-PLAYBOOK.md, LAUNCH-GUIDE.md, launch-posts.md, a MailerLite
  5-email funnel and the packaged zip. `forge-skill-pack-free` holds the free
  lead-magnet kit with its own index.html and vercel.json. Both last touched
  2026-07-09.
- `forge-skill-pack/GOALS-additions.md`, dated 2026-07-01, is paste-ready text for
  GOALS.md with the venture named and TWO BLANK DATES. Both blanks are still blank.

So nothing was ever blocked on a fit judgment. It was blocked on a date.

THE COST OF THE GAP. GOALS-additions.md ends "keep the clarity bar first if the two
compete." The clarity bar was the Physics Wallah head-to-head, retired unmet today
because its instrument -- a panel of student raters -- never existed. A built product
was therefore deprioritised in favour of a milestone that could not be reached. Neither
document could see the other, so neither was wrong on its own terms.

WHAT IS ACTUALLY OPEN: one date. Adopt the venture in GOALS.md and set either the
shipped-asset milestone or the revenue milestone from GOALS-additions.md. That is a
scheduling decision on finished work, not a ruling on an idea.

THE AUDIT'S OWN LESSON. This file's PROCESS NOTE below names the failure as a record
kept faithfully by its most visible measure while the property that mattered drifted.
The entry that stood here was an instance of it: it trusted the FIT line, which is the
most visible measure on the card, and never checked whether the graduation it announced
had a destination. Reading one line further, or opening the named path, would have
caught it. Check the link, not the label.

### PROCESS NOTE
Three of these cards carried a FIT verdict inside them while sitting in a folder whose
name says "awaiting scoring". The scoring layer and the verdict layer drifted apart,
so the queue length stopped describing the queue. Same failure this ecosystem hit three
times on 2026-09-09 in other lanes: a record maintained faithfully by its most visible
measure -- here, file count -- while the property that mattered, decidedness, drifted.
The cheap guard is to log the verdict HERE at the moment the FIT line is written,
rather than treating the card as the record.

# Revenue-model seed: personal LinkedIn-outreach CRM built inside Claude Cowork

Source: Sandy Lee AI (@sandyleeai) YouTube, video eUwgco46VwE "The Mom Who Left Her 9-5... With
Claude Cowork" (guest "Equi"), read 2026-07-05 as part of the @sandyleeai channel intake (logged
in ConceptForge/intake/QUEUE.md same day). All figures are the guest's UNVERIFIED claims. Scored
for FIT against the operator's current portfolio (PrepBrix NEET/JEE education; the forge-skill-
pack "Claude Code Power Pack"; ng-monitor trading; tamiliq).

## The model: a personal LinkedIn CRM as a productized service
Build a relationship/outreach CRM entirely inside Claude Cowork for solopreneurs and creators who
already have a large LinkedIn following but no system for turning engagement into relationships
or deals. The CRM tracks: contact stage, engagement history (who liked/commented/viewed your
profile), and follow-up cadence -- a real-world instance of entity memory (structured, durable
facts about each relationship), not a new memory mechanism, just a concrete application of one
already in agent-engineering/patterns/agent-memory-types/PATTERN.md.

## The stack (as demonstrated)
- Claude Cowork as the interface and orchestration layer (no separate app to build/maintain).
- Supabase as the durable data store (contacts, stages, engagement events).
- Apify for LinkedIn engagement/profile-viewer scraping -- manual copy-paste into the pipeline
  since no official LinkedIn API or Claude connector exists for this data.
- Vercel + GitHub for any lightweight deploy/hosting needs.
- Estimated stack cost: ~$49-110/month (Supabase + Apify tiers), far below a dedicated CRM SaaS
  subscription or a custom build.

## Why this is a distinct case (not a dedup)
Checked directly against RevenueForge/intake/pending/ (12 files) and VentureForge/intake/done/
(13 files) at the time of logging -- no existing case addresses a LinkedIn-specific CRM built
inside Cowork, or the Apify-manual-copy-paste workaround for the missing LinkedIn API/connector.
The closest neighbors are generic AI-SDR/outbound systems (e.g. the lead-scrape+enrichment
component of gregisenberg-sanskargoyal-agent-saas-agency.md), which serve OUTBOUND prospecting,
not INBOUND relationship-management for an existing audience -- a different job to be done.

## Who it's for / how it might be sold
- Target buyer: solopreneurs, coaches, and creators with a sizeable LinkedIn following and no
  system for converting engagement into relationships or revenue -- the same audience segment
  Patrick Dang's "Ikigai skill" funnel and the Greg Isenberg/Sanskar Goyal agent-SaaS cases target,
  but served with a narrower, LinkedIn-specific tool rather than a general automation agency.
- Possible models: (a) sell the finished CRM as a done-for-you build/setup service (one-time fee),
  (b) a monthly maintained-CRM retainer (the wrapper-is-the-moat pattern already logged in the
  agent-SaaS-agency case), or (c) package the Cowork+Supabase+Apify recipe itself as a guide/
  template product -- closer to the forge-skill-pack's own productization model.

## FIT against the operator's portfolio
LOW-MODERATE, no direct asset overlap. None of PrepBrix, forge-skill-pack, ng-monitor, or tamiliq
involve LinkedIn outreach or CRM tooling. The closest tangential link is methodological: the
operator already runs Claude Cowork sessions extensively (this very research lane), so the
Cowork-as-CRM-orchestrator pattern is a plausible template if a LinkedIn-outreach need ever
arises for the forge-skill-pack's own distribution (e.g. the operator's own LinkedIn presence),
but there is no owned audience/client base to sell this TO today.

## Net
Logged as a genuine, distinct market-signal case per the D10 freeze discipline (demand-driven
intake, not proactive mining) -- NOT actioned into a build. If the operator wants to pursue this,
the next step would be validating demand (does the operator or a known contact have a large
enough LinkedIn following to justify the stack cost) before any build work, per the charter's
conversion-first stance.

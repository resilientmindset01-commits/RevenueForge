# Agent mystery-shopper self-test -- tools.prepbrix.com and the Gumroad pages (2026-09-17)

Method (sip-agent-readiness-services.md, Card 1, applied to the operator's own funnel): a fresh agent with no prior
knowledge, web fetch and web search only, asked to find what the pack contains, price, license, refunds, free version,
updates and the checkout link, stopping before any purchase. Plus direct HTTP checks of what a crawler or agent sees.

## What worked
- The landing page is static HTML and fully readable: the eight skills, $29 one-time, single-seat license, free
  updates, the free kit and both checkout links were all found there.
- The agent reached the exact checkout URL (resilience88.gumroad.com/l/hvdgsc) from every "Get the pack" button.
- AI crawlers are not blocked (GPTBot and ClaudeBot get 200).
- Gumroad's own page carries schema.org Product data with the $29 price; the agent's fetch tool did not surface it,
  but agents that read structured data will.

## Where it stopped or had to guess
1. REFUND POLICY: not stated anywhere (landing or Gumroad). The agent would not recommend buying without it.
2. WHO SELLS IT: three names with nothing linking them -- prepbrix (domain), resilience88 (Gumroad subdomain),
   ResilientMindset (store name). No seller name or contact on the landing page.
3. TEAM LICENSE: "Ask about a team license" gives no way to ask.
4. GUMROAD PAGES ARE JAVASCRIPT-ONLY to a plain fetch: an agent sees only the product name. Whatever matters must
   also be on the landing page (it now is, except refunds and seller).
5. GUMROAD DESCRIPTIONS: the paid pack's description is one short paragraph with a broken character where a dash was
   (it shows as a replacement symbol), no skill names, no license; the free kit still says "3 free" (known item).
6. NOT FINDABLE BY SEARCH: queries for the domain, the product name and two skill names found nothing. The product
   name returned another seller's "Claude Code Power Pack" at $29 (smeltworks.com/claudecodepack) -- that URL now
   redirects to a hosting company's homepage, so the collision is UNCONFIRMED today.
7. FREE KIT NOT A SUBSET: one of the four free skills (session-handoff-memory) is not in the paid pack; the page did
   not say so.

## Fixed without operator input (forge-skill-pack-free, not yet pushed)
- Landing: schema.org Product JSON-LD with price, currency, availability and checkout URL.
- Landing: the free-kit line now says which three skills are pack samples and that session-handoff-memory is
  free-kit only.
- robots.txt (allow all, points to the sitemap), sitemap.xml, llms.txt (a plain-text summary an agent can read:
  contents, price, license, updates, free kit, install, links).

## Needs the operator (in order)
R. REFUND POLICY -- pick one; it goes on the landing FAQ, llms.txt and the Gumroad description.
   | Option | Text |
   |---|---|
   | A (recommended) | "30-day refund: if the pack is not useful, reply to your Gumroad receipt within 30 days for a full refund." |
   | B | "Digital download: no refunds once downloaded. Try the free starter kit first." |
   Why A: the long-running competitor pages offer 30 days; at $29 on a product with no reviews yet, it removes the
   reason the test agent gave for not recommending the purchase.
S. SELLER NAME AND CONTACT -- one line for the footer and llms.txt, e.g. "Sold by ResilientMindset via Gumroad.
   Questions and team licenses: <email>". Choose which email to publish.
G. GUMROAD DESCRIPTIONS -- paste the text below (Gumroad UI), after choosing R.

PASTE-READY, paid pack (hvdgsc):
Eight Agent Skills for people who use Claude Code (or any coding agent that reads Agent Skills). Each is a plain
SKILL.md markdown procedure your agent loads on demand -- no install, nothing to run.

What is inside:
- adversarial-self-critique -- a real judgment on your plan instead of agreement
- review-ai-code -- a 9-step review and pre-merge checklist for AI-written code
- self-verifying-loops -- loops that check their own work and stop or escalate
- context-curation -- keep long sessions sharp
- claude-md-rules -- a CLAUDE.md the agent actually follows
- multi-agent-finisher -- builder and judge as separate roles, bounded revision
- agent-bash-security -- stop a long run from doing anything irreversible
- skill-authoring -- turn a repeating workflow into a durable skill

One-time $29. Single-seat license: use it yourself and on your own projects; no reselling or redistribution.
Free updates -- the September 2026 update more than doubled the pack.
[REFUND LINE FROM R]
Not affiliated with, endorsed by, or sponsored by Anthropic. Claude is a trademark of Anthropic, PBC.

PASTE-READY, free kit (ngwuyp):
4 free Claude Code skills and a one-page cheatsheet: review-ai-code, claude-md-rules and context-curation (samples
from the Claude Code Power Pack) and session-handoff-memory (free kit only). Drop a skill folder into
~/.claude/skills/ and invoke it by name. The full 8-skill pack: https://tools.prepbrix.com

## Not recommended now
- Renaming the product because of the unconfirmed name collision. Revisit if the other product reappears.

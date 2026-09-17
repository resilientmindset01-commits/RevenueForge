# @everestchris6 -- 36 X Articles, 2026-01-09 to 09-15 (sweep card)

Source: Chris, founder of atonomi.ai. All 18 articles read in full on 2026-09-17 by three parallel readers; raw
extractions kept out of the repo. Verdicts are in REVENUE-WAYS section 23; this card keeps the per-article detail worth
reusing. Every number is HIS CLAIM unless marked verified.

## The articles
| Date | Title | Views | Pitch |
| --- | --- | --- | --- |
| 08-01 | how to sell high ticket ai systems ($501,153 in jobs) | 9.2K | atonomi.ai call |
| 08-09 | make money with AI agents on reddit | 111K | Telegram |
| 08-10 | how to actually sell a product | 28K | none |
| 08-11 | how to use AI to sell info products on autopilot | 16K | none |
| 08-15 | how to make money selling ai ugc to businesses | 11K | Paid partnership: Arcads |
| 08-16 | how to make money with ai agents and postcards | 26K | Telegram |
| 08-17 | how to make money with whop's partner program | 19K | whop.com/partners |
| 08-18 | how to build an automated sales machine | 96K | Telegram |
| 08-19 | how to build a reddit sales system | 78K | none |
| 08-21 | make money with grok bot on autopilot | 113K | Telegram |
| 08-23 | how to sell your product with ai ugc | 12K | Paid partnership: Arcads |
| 08-26 | how to build revenue systems with grok bot | 85K | Telegram |
| 08-28 | make money with grok bot in 6 weeks | 45K | Telegram |
| 09-01 | start ten businesses on autopilot with grok bot | 18K | Arcads, last line only |
| 09-04 | make money with claude fable 5.1 on autopilot | 33K | Telegram |
| 09-11 | how to run a b2b dropship agency on autopilot | 13K | Telegram |
| 09-13 | how to automate lead generation | 184K | Telegram |
| 09-15 | make money selling to ai agents | 57K | Telegram |

### Added after real-scroll enumeration: the 18 earlier articles (all read)
| Date | Title | Views | Pitch |
| --- | --- | --- | --- |
| 01-09 | how to actually make $10,000/mo selling AI websites to local businesses in 2026 | 2.7K | Unloopa |
| 01-11 | The $10,000/month Google Sheet method | 1.5K | none |
| 02-17 | how to sell websites to local businesses with openclaw | 66K | openclaw.unloopa.com |
| 02-18 | how to build an automated sales system with openclaw | 19K | none |
| 02-19 | nobody is talking about this OpenClaw business model | 44K | none |
| 02-21 | how I use OpenClaw to sell websites on autopilot | 300K | none |
| 02-24 | how to make $250 per day with OpenClaw | 73K | none |
| 02-26 | You're Using OpenClaw Wrong | 7.6K | none |
| 03-01 | how my SaaS hit $1k MRR in 24 hours | 29K | Unloopa $39/mo |
| 03-06 | openclaw + reddit = customers on autopilot | 24K | none |
| 03-10 | the $100k/mo OpenClaw business - full breakdown | 21K | "dm me" |
| 03-16 | how to make your first $1 with AI | 27K | none |
| 03-19 | how i automated customer acquisition with one ai agent | 16K | Adaptive.ai (undisclosed) |
| 05-14 | the $100m AI opportunity right in front of you | 28K | atonomi booking link |
| 05-16 | the world is about to change and almost nobody is acting like it | 8K | atonomi booking link |
| 06-06 | selling AI agents 101 | 19K | none |
| 06-11 | how to sell ai agents to local businesses (full guide) | 9K | Composio referral |
| 06-21 | how i made $1,000/day on reddit | 21K | Unloopa |
Verdicts: REVENUE-WAYS section 23b. Mechanics worth keeping from these: build and test each step as its own small API
before letting an agent sequence them (02-26); "the models don't know the newest models, so whenever an api is
involved, go find the current docs yourself and paste them in" (06-11).

## Reusable mechanics (tool-agnostic)
- QUALIFY ON MEASURED DATA, NOT ON THE PICTURE: roof pitch, azimuth and usable area from a solar data API, year built and
  owner-mailing-address-versus-property (rentals) from assessor records, permit history to drop recent jobs. "a model
  looking at a blurry rooftop will happily tell you a roof faces south when it doesn't". Satellite imagery "is often one
  to three years old"; check the capture date before paying for a render.
- RENDER AS AN EDIT, NOT A GENERATION: keep the house pixel-identical and add one thing; match existing shadows; give
  several reference angles; return the original beside the render for a human check. Label it a visualisation.
- GENERATED QR CODES LOOK RIGHT AND DO NOT SCAN: leave the corner blank and composite a real code. One tagged QR per
  card and one call-tracking number per campaign is the attribution.
- CARD SPEC HE USES: 6x9 (same bulk postage as 6x11, his claim), render edge to edge on the front, four or five words,
  name, phone, licence number and a QR of at least one inch on the back.
- FIRST SALE: render twenty houses in one contractor's area and offer to mail them at your cost; or send "four images of
  houses in their area and ask whether they've ever mailed to that street".
- A LANGUAGE FILE: three months of a community's posts, pulled for exact repeated phrases, what they tried and why it
  failed, the words for the emotion, and what would make them ask for a refund. Every hook, landing page headline and
  script is written from it.
- HOOK HONESTY CHECK in his prompts: "tell me what it promises, and whether my content can actually deliver that. mark
  any hook that overpromises."
- LANDING PAGES WITHOUT INVENTED PROOF: "no fake testimonials, no invented numbers, no 'join 2,000 readers' when there
  are none." A kill metric set before any traffic.
- FREE STRUCTURED FEEDS instead of scraping (his claims, not tested here): add .rss to a Reddit URL, .json to a
  Discourse forum URL, YouTube channel feeds at youtube.com/feeds/videos.xml?channel_id=, the iTunes RSS feed for app
  reviews. Reddit's own terms still govern collection (PLATFORM-RULES: Reddit).

## Claims checked
- Claude: see claude-techniques fable-5-migration ("Fable 5.1 deltas"). Claude Opus 5 as an agent model: CORRECT.
- Reddit account sale and content manipulation: VERIFIED against redditinc.com. FCC consent for marketing texts: VERIFIED.
- Whop partner sources and tiers, blueprint 10% cut: VERIFIED in part at docs.whop.com; fee and fixed rates not.
- agentskills.io is the Agent Skills spec (originally Anthropic), not a registry; skills.sh is Vercel's directory with
  install counts. clawhub not checked.
- NOT VERIFIED: "$501,153", "$1,000 a day on reddit", the Christmas light job values, lead platform costs ("$188 for
  eight leads"), "gpt image 2.5 is the best image model", "gpt-6 astra", Whop Ads at "meta's top tier".

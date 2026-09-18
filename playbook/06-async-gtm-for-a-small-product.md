# 06 -- Async go-to-market for a small product (no calls, prices in public)

playbook/01 sells a service. playbook/02 sells a digital product off a free kit.
This is the distribution half neither of them covers: how a small paid product
gets its first users when the seller cannot take sales calls.

Why it is in this estate: the operator trades on market days and cannot hold
scheduled calls then. Almost every money method read in 2026 needs calls. This one
does not, its prices are published, and the source posts dashboards rather than
screenshots of claims.

Source: @manoj_ahi, 3 X Articles and 24 posts read 2026-09-18. He sells four small
products at published prices. His revenue and user figures are his own claims and
are not carried; the METHOD is what this file keeps.

## The precondition

A product with a published price and a self-serve signup. If a buyer has to talk
to you to find out the price or to start, none of what follows works, because
every step below ends in a link rather than a conversation.

## The channels, in the order they pay off

1. NICHE DIRECTORIES, WITH AN AFFILIATE SPLIT. Submit to the directories that
   serve your buyer specifically, not the general launch sites. Offer the
   directory a share of revenue it refers rather than paying for placement -- it
   costs nothing if it does not work, and a directory that accepts the split has
   told you it expects the traffic to convert.
2. COMMUNITY REFERRAL DEALS, MADE WITH THE OWNER. Approach the admin of a
   community your buyers already sit in and agree a referral arrangement. The
   deal is with one person and is made once; it is not posting into the community
   yourself, which is the version that gets you removed.
3. A BRANDED ACCOUNT ON THE BIG FORUMS, USED HONESTLY. Post under the product's
   own name, disclose what you sell, and answer questions where the product is
   genuinely relevant. This is slower than a sockpuppet and it is the only
   version that survives being found out. See REFUSED below.
4. PROGRAMMATIC SEO PLUS AN LLMS.TXT. Generate one page per real query shape your
   buyer types, and publish an llms.txt so assistants can read the product
   accurately. This is the only channel here that compounds while you are away
   from the desk, which makes it the best fit for market days.

## The conversion mechanics

- A TIME-LIMITED TRIAL WITH FEATURES CUT, not a trial with everything on. A full
  trial teaches the buyer they can finish their job inside it; a trial with the
  expensive part withheld teaches them what they are buying.
- A NO-QUESTIONS REFUND, TREATED AS RESEARCH. Refund without argument, then ask
  one question: what did you expect that this did not do. That answer is the
  cheapest product feedback available and it arrives from the people who bought.
- PRICES ON THE PAGE. Every step above ends in a link, and a link to a page with
  no price sends the buyer to a contact form, which is the call you were avoiding.

## What to measure

One row per channel: referred visits, signups, trials started, conversions, and
refunds. Read refunds as a separate line rather than netting them off revenue --
a channel with good conversion and high refunds is sending the wrong buyer, and
netting hides it.

## The build spine, for the product this playbook then sells

A second source in the same intake shipped a small paid product and published the whole build. It is worth keeping
because it is four stages and none of them is "have an idea":
1. WRITE THE SPEC WITH A MODEL BEFORE BUILDING ANYTHING -- the data shape, the one mechanic that makes the product
   different, and what it deliberately will not do. One mega-prompt covering everything at once is the failure he
   reports; separate stages worked.
2. BUILD THE INTERFACE AGAINST MOCK DATA FIRST, with a no-code builder or otherwise. The interface is where the idea
   is tested cheaply, and mock data stops the schema being decided by whatever was easy to fetch.
3. BUILD THE ONE MECHANIC PROPERLY. In his case a scoring function with a decay half-life and a floor, deliberately
   replacing the streak counter every competitor uses. This is the only part that is not commodity, and it is the
   part to spend on.
4. PAYMENTS LAST, through a merchant of record if you are selling across borders -- it moves sales-tax filing to the
   processor, at a percentage. Check the current fee and the filing claim yourself before relying on either.
His figures are his own and none is carried; the money table's larger rows are arithmetic projections rather than
achievements, which he says. The useful negative results he reports: one mega-prompt failed, freemium converted in
the low single digits, and the build took eleven evenings rather than the weekend the title implies.

## One acquisition tactic from that source, REFUSED

He recommends building standing in a support community for a medical condition by answering threads helpfully until
your username is recognised, and then launching the product into it -- with a pre-launch checklist item to post one
unpaid, unmarked comment in the target community before launch day.
This is NOT the branded-account channel above, and the difference is the whole point. The honest version discloses
what you sell from the first post and answers questions where the product is relevant. This version is participation
performed as a means to a sale, in a vulnerable-population community, where the disclosure is withheld precisely
because it would reduce the effect. It also breaches the self-promotion rules of most such communities.
Recorded, not carried. The same source also uses unsourced health statistics as sales support and publishes an
uncited table disparaging four named competitors on price, which is the second reason nothing from its marketing
layer is carried.

## REFUSED, from the same intake

These were read in the money accounts of this batch and are not carried. Each
breaks a rule already verified in PLATFORM-RULES.md:
- Fabricated comments written to read as real viewers. FTC fake-reviews rule.
- A prompt for making generated text pass as human-written, used to defeat
  detection.
- Bot-detection evasion on freelance marketplaces -- spoofed user agents,
  randomised delays, a separate browser profile.
- Cold email tuned to stay under spam thresholds. CAN-SPAM is about consent and
  disclosure, not about staying under a threshold.
- Buying or taking over abandoned communities to mail their members.
- Harvesting contact details from a professional network into a spreadsheet.
- Guaranteeing performance metrics to a sponsor.
- Scarcity claims ("48 hours only", "100 seats") repeated with no published price.

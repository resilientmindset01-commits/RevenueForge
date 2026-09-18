# 05 -- Demand mining from complaints (score the pain before you build)

playbook/02 finds demand that is already being paid for, by reading ads.
This one finds demand nobody is serving yet, by reading complaints. Different
input, different output, and the estate needs both.

Source: @hooeem, X Article read 2026-09-18. Tool names below are his and are not
endorsements. He claims no figures for this method, which is unusual for him and
is the reason it is worth writing down.

## Scope to one buyer and one workflow

"Independent recruiters turning screening notes into client-ready summaries" is a
scope. "Recruitment" is not. Everything downstream fails if this step is loose,
because a wide scope returns complaints from people who will never be the same
buyer.

## Build the keyword set

Buyer, plus workflow, plus a pain modifier: "takes hours", "manual", "too
expensive", "alternative to", "does anyone know a tool", "still using a
spreadsheet". Ten to twenty phrases is enough.

Point collection at sources whose terms allow it. CHECK PLATFORM-RULES.md PER
SOURCE BEFORE COLLECTING, and use official endpoints where they exist rather than
scraping. Treat private communities as out of scope entirely -- people posting
there have not published, whatever the group's size.

## Land everything in one table

Raw text, source URL, date. Nothing else at capture time.

## Score each hit on six axes, out of ten

How severe the pain is; how urgent; how often it recurs; what the current
workaround is and how ugly; whether there is any sign of willingness to pay; and
how much of it a machine could actually do.

Instruct the scorer to invent nothing, to use only what is in the text, and to
score vague text low. Review by hand above a threshold. The score sorts the queue;
it does not make the decision.

## Cluster weekly, once thirty or more high scores exist

A cluster is a repeated pain with an owner, an evidence count, the workarounds
people described, and the competitors they named.

Score the cluster on volume and recurrence, severity, urgency, workaround
ugliness, buying intent, the gap against existing tools, whether it can be charged
for, and how buildable it is. Deduct for platform or legal risk, a vague buyer, no
route to reach them, and hype with no workflow under it.

## The gate

Test nothing below a high threshold, and test with a landing page plus a MANUAL
service, never with software.

Say on the page that it is an early manual beta. No invented testimonials, no
unsupported claims, customer wording only -- the FTC fake-testimonial rule in
PLATFORM-RULES.md applies to a validation page exactly as it applies to a launch.

Drive twenty to fifty direct messages to the exact buyer and read the form
answers. Build only after somebody pays for the manual version.

## What this method does not do

It does not tell you whether the pain is worth money, only that it is real and
recurring. Willingness to pay is the axis people score generously and the one the
manual test actually settles. Two clusters with identical scores can differ
entirely on that axis, and the only way to find out is to charge.

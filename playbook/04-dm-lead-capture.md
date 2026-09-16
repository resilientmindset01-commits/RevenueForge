# 04 -- DM lead capture (the missing piece of the funnel)

EARNING-MAP names the funnel and marks the EMAIL LIST as missing. youtube-growth
playbook/07 says the PrepBrix money case is "lead magnet, DM-keyword capture, then
the study pack". Neet/lead_magnets/ holds two finished PDFs that have never been
distributed. This file is the operating manual for the step between them.

Source: the Manychat channel (youtube-growth/sources/manychat.md), read 2026-09-16.
Manychat sells the tool, so their numbers are marketing. The platform rules below
were read at Meta's own developer docs and are in PLATFORM-RULES.md.

## The one rule that decides the whole design
VERIFIED, developers.facebook.com, Instagram private replies:
- "Only one message can be sent to the commenter"
- "The message must be sent within 7 days of the comment was made on the post or reel"
- "Follow-up messages can only be sent if the recipient responds, and must be sent
  within 24 hours of the response"

A comment buys exactly ONE message. So if that message is the download link, the
conversation ends there and the email can never be asked for. The first message
must instead get a TAP -- a button, a quick reply, anything the person acts on --
because their action is what opens the 24-hour window in which you may ask for the
address and send the file.

Manychat teaches exactly this, in their words: the opening DM has one job, get a
tap. On this point the vendor and the documentation agree.

The window then RESETS on every further interaction (their claim, consistent with
Meta's list of what opens a window, which includes a user reply and even a
reaction). Outside it, three routes exist and none of them is automation: a human
replying manually within 7 days under the human agent tag, a pre-approved message
tag for transactional reasons such as an order or event reminder, or a one-time
notification the person consented to. Meta's wording: message tags let businesses
"send important and personally relevant 1:1 updates" outside the window, and
misusing them "may result in restrictions on your ability to send messages."

## The build, in order
1. TRIGGER. A comment on a post or reel containing a keyword, a new follower, a
   story reply, or an inbound DM. The comment reply must be set to send a PRIVATE
   REPLY, not a public one -- this is the single most common misconfiguration.
2. FIRST MESSAGE: bait the tap. A question with a button, not the file and not an
   external link. Their claim, worth testing: an external product link in this
   first message is not allowed.
3. OPTIONAL GATE. A condition on the system field for whether the person follows
   the account, so the file can be made conditional on a follow. Use with care --
   it trades goodwill for a follower.
4. ALREADY-KNOWN CHECK. A condition on whether the email field has any value. If
   it does, skip the ask and send the file. Nobody should be asked twice.
5. THE EMAIL ASK. A Data Collection node with the reply type switched from Text to
   EMAIL, which validates the address in the conversation and re-prompts on a
   malformed one. Turn on saving to the email system field and the email opt-in
   toggle. Add a retry message and a Skip path. Note that this node BLOCKS: nothing
   downstream sends until an address arrives or the person skips.
6. DELIVER. A PDF content block: drag the file in, and the file itself goes into
   the DM -- no link and no website needed. Stated to be Flow Builder only, not
   available in the simpler quick automations.
7. PUSH THE ADDRESS OUT. "Action on reply" writes to Mailchimp, Kit, a Google
   Sheets row, or Zapier / Make / n8n. Do this on the same node, or the list lives
   only inside the tool.
8. FOLLOW UP INSIDE THE WINDOW. A 15 to 30 minute no-response nudge is inside the
   rules. A sequence that keeps nudging a silent person for days is not.

## What it costs, which decides whether to start
Manychat's own plan ladder, as stated in their pricing videos (MANYCHAT-CLAIM):
Free, Essential, Pro, Business, Advanced, priced on ACTIVE CONTACTS -- a person
you engage in the billing month, counted once no matter how many messages. Stated
allowances: Free is outgrown above 25 engaged people a month, Essential 250, Pro
2,500, Business 7,500. Pro is quoted at 39 dollars a month with 5 cents per contact
over the allowance; annual billing is said to save 18 to 30 percent; extra inbox
seats 25 dollars a month on Pro and above. Contacts reset monthly, a cap can be
set in advance, and upgrading mid-cycle forgives that month's overage.

The part that matters for a decision: the FREE tier runs the triggers -- comment,
follow, story reply, DM -- and can send a link. But EMAIL AND PHONE CAPTURE, tags
and follower checks start at Essential, and AI and WhatsApp start at Pro. So the
free tier can prove the flow works; it cannot build the list. Budget for Essential
before treating this as a list-building channel, and note that 25 contacts a month
is a pilot, not a funnel.

## What breaks
Almost every reported failure is one of six things: the flow was never published,
an action block is empty, the keyword is misspelled, the trigger is switched off,
the comment reply is not set to private reply, or the Instagram permissions have
expired (Settings, Channels, Instagram, Refresh permissions). Check those before
debugging logic.

The silent failure is different and worse: a message scheduled past the 24-hour
window simply never sends, with no warning. Manychat claims to block those
automatically rather than let them violate policy. Design so no delay can land
outside the window.

## To test before committing anything
- PDF LIMITS ARE UNSTATED. No size, page count or format limit was given, and no
  list of which channels accept a file. The two PrepBrix magnets are 1.3 MB (51
  pages) and 523 KB (41 pages). Send both through the flow to a test account before
  building anything on it.
- WHETHER TIKTOK IS EVEN AVAILABLE. TikTok has no comment automation at all -- only
  an inbound DM keyword -- and the automations are claimed to be business-account
  only and unavailable in the EU, UK and Switzerland. India is not mentioned either
  way, which for this operator is the question that matters.
- THE EXTERNAL-LINK CLAIM in the first message. Vendor-stated, not found in Meta's
  documentation during this read.

## The quiz variant
There is a ready-made quiz template: a prior-taker check, three questions whose
options carry hidden point values with the scoring built in, then branching on the
total -- low scorers get a low-risk offer, high scorers get the main one. It maps
directly onto the quiz router already written into playbook/02. It captures NO
email by itself, so the Data Collection node has to be added.

For a NEET audience the quiz is the natural fit: a short diagnostic that sorts a
student by weak chapter, then delivers the matching section of the formula booklet
and asks for the address to send the rest.

## Status
PLAYBOOK, not LIVE. Nothing here has been run. The first move is the PDF test above
on a free account, which costs nothing and answers the only question that blocks
the rest.

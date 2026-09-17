# Platform and legal rules for earning methods -- read at source

Every line here was read on the page named, on 2026-09-15, unless marked otherwise. Check a method against this file
before scoring it in REVENUE-WAYS.md. Rules change: re-read the page before acting on a line older than six months.

## Email outreach -- FTC, CAN-SPAM compliance guide (ftc.gov)
- "The law makes no exception for business-to-business email."
- Requirements: no false or misleading header information; no deceptive subject lines; identify the message as an ad;
  tell recipients where you are located (a physical postal address); tell recipients how to opt out; "Honor a
  recipient's opt-out request within 10 business days"; monitor what others do on your behalf.
- "Each separate email in violation of the law is subject to penalties of up to $53,088."

## Endorsements and affiliate links -- FTC, "Disclosures 101 for Social Media Influencers" (search-result excerpt of the page)
- A "material connection" to a brand, including a financial relationship such as being paid, must be disclosed so it
  is obvious. Commission links are a financial relationship. Do not bury the disclosure among hashtags or links.

## Amazon KDP -- content guidelines, AI-generated content
- AI-generated means "text, images, or translations created by an AI-based tool", "even if you applied substantial
  edits afterwards". AI-assisted (you created it, AI helped edit or improve) is not AI-generated.
- "We require you to inform us of AI-generated content (text, images, or translations) when you publish a new book or
  make edits to and republish an existing book through KDP." AI-assisted content needs no disclosure.
- Separately (Publishers Weekly and KDP forum reporting, September 2023, not re-read at KDP): a limit of three new
  titles per day per account, reviewed periodically.

## Google Play Books -- publisher content policies
- Prohibited: "Content that provides a poor user experience, such as gibberish, nonsensical, or repetitive text that
  provides no narrative or educational value."
- "We do not allow content that is easily found online at no charge or lacks the depth and curation necessary to
  provide a meaningful reading experience."
- Misleading metadata: titles, authors, descriptions or covers "confusingly similar to existing books" or that
  impersonate popular works.
- The policy page read does not name AI-generated books as a category.

## Etsy -- Creativity Standards (last updated 10 Jun 2025)
- "all items must incorporate a human touch". Designed-by-a-seller includes "Seller-prompted AI creations", and
  "Sellers must disclose within their listing description if an item is created with the use of AI."
- Not designed by a seller: "A bundle, collection, scan, or PDF of someone else's work" and "AI prompt bundles".
- Items made by a production partner (print-on-demand): "Sellers must disclose that an item is made by a production
  partner, and provide accurate information about where the item is dispatched from."

## Fiverr -- "Using AI on Fiverr: Guidelines for freelancers and clients"
- AI is permitted in all categories, but work must be "high-quality, original, and meaningfully refined and customized
  to the client's specific requirements. Generic, unmodified, or reused AI output does not meet Fiverr's quality
  standards."
- "Freelancers must also honor a client's explicit request for non-AI work."
- Prohibited: deepfakes of real people without consent; "Using someone's voice, image, or likeness without proper
  authorization or rights"; misrepresentation.
- Trust breach "including deception about how work was delivered, misrepresentation of AI usage" can mean a cancelled
  order, full refund, and a permanently suspended account.
- Fiverr "AI services guidelines": do not offer "a voice that you do not have the right to use", such as music in a
  known singer's voice or a cloned celebrity voice.

## YouTube -- channel monetization policies
- Inauthentic content: "Content that is repetitive or mass-produced." Not monetizable, for example "Image slideshows,
  templated storylines, or scrolling text with minimal or no narrative" and "AI-generated content made with generic or
  unoriginal templates giving the impression of mass production".
- Reused content: repurposing content "without adding significant original commentary, substantive modifications, or
  educational or entertainment value"; disallowed includes "Content that exclusively features readings of other
  materials you did not originally create".
- The policy now names more buckets than "inauthentic content" alone (support.google.com/youtube/answer/1311392, read
  2026-09-16): "Generic or repetitive content" is "Content that looks like it's made with a template, or that may feel
  repetitive to viewers after watching several videos in a row"; "Unsatisfying or off-putting content" is content that
  "relies heavily on emotionally manipulative formulas, mimics existing formats or stories to a degree that the videos
  feel interchangeable, or appears designed to shock or surprise viewers"; and "AI personas related to sensitive
  topics" covers "Channels that use AI-generated personas to deliver information on sensitive topics" such as health,
  legal, financial or political matters.
- AI tools are not banned by any of these. The reused-content policy allows AI-generated content where the creator
  shows "original, authentic insights or perspective", and the unsatisfying-content policy allows AI tools where "the
  final product must still demonstrate your creative vision". The trigger is template sameness, not the tool.

## Meta -- DM automation on Instagram and Messenger (developers.facebook.com, read 2026-09-16)
The rules that decide whether a comment-to-DM funnel is allowed to send anything. Read before building one.
- THE 24-HOUR WINDOW: "Businesses have up to 24 hours to respond to a user. Messages sent within the 24-hour window
  may contain promotional content." So the promotional message is fine -- inside the window, after the person acts.
- WHAT OPENS THE WINDOW, as listed: the user sends a message to the Page; clicks a call-to-action button such as Get
  Started; clicks a click-to-Messenger ad and starts a conversation; starts a conversation through a plugin; clicks
  an m.me link with a ref parameter on an existing thread; or REACTS to a message. Each is a user action -- there is
  no route that begins with the business messaging a stranger.
- OUTSIDE THE WINDOW you need a message tag, a One-Time Notification, news messaging (registered news pages) or a
  sponsored message. Message tags "Enable businesses to send important and personally relevant 1:1 updates to users
  outside the 24-hour standard messaging window."
- THE HUMAN AGENT TAG IS NOT AN AUTOMATION LOOPHOLE: it "allows businesses to manually respond to user messages
  within a 7-day period". Manual, by a person. Meta's stated use case is an issue that cannot be resolved inside the
  standard window, such as the business being closed for the weekend.
- ENFORCEMENT: misusing message tags "may result in restrictions on your ability to send messages."
- What this means for a lead-magnet funnel: the comment or the story reply IS the opt-in, the delivery message has to
  go out inside 24 hours, and any follow-up after that needs either a fresh user action or one of the named
  exceptions. A sequence that keeps nudging a silent person for days is outside the rules as written.
- THE COMMENT-TO-DM RULE IN FULL (developers.facebook.com, Instagram private replies, read 2026-09-16). This is the
  one that decides how the funnel must be built:
    "Only one message can be sent to the commenter"
    "The message must be sent within 7 days of the comment was made on the post or reel"
    "Follow-up messages can only be sent if the recipient responds, and must be sent within 24 hours of the response"
  So a comment buys exactly ONE message. If that message is just the download link, the conversation is over and
  there is no lawful way to ask for an email afterwards. The first message has to invite a reply -- a button or a
  question -- because the REPLY is what opens the 24-hour window in which the email can be requested and the file
  sent. Manychat teaches exactly this, and on this point they are right.
- Instagram's own messaging page states the window the same way: "Your app has 24 hours to respond to any message
  sent from an Instagram user to your app user", with the human-agent tag as the only extension, for human replies.
  Instagram DM automation also requires a professional account and the instagram_business_manage_messages permission.

## X -- paid partnerships and platform manipulation (SEARCH-LEVEL; help.x.com refuses fetches, re-read in a browser before relying on it)
- Paid partnerships policy (help.x.com/en/rules-and-policies/paid-partnerships-policy, via search excerpts 2026-09-16):
  posts with commercial intent require a disclosure, including own-brand posts by someone with a commercial interest;
  X provides a built-in "Paid Partnership" label. Paid partnerships are reported as prohibited for adult and sexual
  products, alcohol, dating, drugs, pharmaceuticals, health and wellness supplements, weight-loss products, tobacco,
  weapons, and political or social-issue content; crypto and gambling are reported as allowed except in the EU, UK and
  Australia.
- Platform manipulation and spam policy (via search excerpts 2026-09-16): coordinating multiple accounts to
  artificially boost engagement or trends, exchanging engagement, and posting the same or substantially similar content
  from multiple accounts -- even accounts you own -- are prohibited; penalties run from reduced reach and locks to
  permanent suspension.

## FTC -- final rule banning fake reviews and testimonials (ftc.gov press release, August 2024, read 2026-09-17)
- Prohibits reviews and testimonials that "misrepresent that they are by someone who does not exist, such as
  AI-generated fake reviews, or who did not have actual experience with the business."
- Businesses may not create or sell them, nor buy them or disseminate testimonials "when the business knew or should
  have known that the reviews or testimonials were fake or false."
- Also prohibits "selling or buying fake indicators of social media influence, such as followers or views generated by
  a bot or hijacked account" when misrepresenting influence for commercial purposes. Civil penalties for knowing
  violators. A US rule; it binds any seller marketing to US consumers.
- CONSEQUENCE: an AI persona reacting to a product claim as if it were a real customer is the "someone who does not
  exist" case.

## Meta -- inauthentic behavior (transparency.meta.com community standards, read 2026-09-17)
- Prohibits "The creation, use, or claimed use of Inauthentic Meta Assets (Accounts, Pages, Groups, etc.)" to "Deceive
  Meta or our users about the identity, or origin of an audience or the entity that they represent", to evade
  enforcement, or to misuse reporting.
- "Coordinated Inauthentic Behavior": networks where "false identities are central to the operation". Covers multiple
  fake accounts and automation used to manipulate how content appears and spreads.
- CONSEQUENCE: a farm of persona accounts on Instagram or Facebook is this policy, whatever the content.

## Instagram -- Terms of Use, what you can't do (facebook.com/help/instagram/581066165581870, read 2026-09-17)
- The page was served in the Tamil locale; the clause read, translated: you can't attempt to create accounts or access
  or collect information in unauthorized ways (the English terms list collecting information "in an automated way"
  under the same heading), and you can't do anything unlawful, misleading or fraudulent. Re-read the English page in a
  browser before quoting it word for word.
- CONSEQUENCE: scraping the followers of other accounts with a browser extension, then messaging them in bulk with an
  automation tool, is outside the terms on both counts -- separate from Meta's DM automation rules above, which cover
  replies to people who wrote first.

## Reddit -- User Agreement and Reddit Rules (redditinc.com, read in a browser 2026-09-17; WebFetch is refused)
- User Agreement (effective July 1, 2026): "You will not license, sell, or transfer your Account without our prior
  written approval." Also prohibits accessing, searching or collecting data "by any means (automated or otherwise)"
  except as the terms or a separate agreement permit.
- Reddit Rules, Rule 2: "Participate authentically in communities where you have a personal interest, and do not spam
  or engage in disruptive behaviors (including content manipulation)".
- CONSEQUENCE: bought or rented karma accounts, a stable of warmed accounts pushing one product, and replies written to
  sell without saying so are all outside these rules, whatever the posting method.

## US -- text messages (fcc.gov consumer guide "Stop Unwanted Robocalls and Texts", read 2026-09-17)
- "FCC rules ban text messages sent to a mobile phone using an autodialer unless the phone owner previously gave consent
  to receive the message or the message is sent for emergency purposes." "Commercial texts require written consent".
- CONSEQUENCE: automated marketing texts to scraped numbers are out. Search-level note, not checked here: business text
  sending in the US also needs carrier registration.

## Whop -- partner program and blueprints (docs.whop.com, read 2026-09-17)
- Partners earn "for as long as the referral lasts, on four separate income sources": sales (Whop's profit on product
  sales), ad_spend (the business's Whop Ads spend), transfer and card_interchange. Share rates are set per referred
  business (payout_percentages; the docs' example value 0.3 = 30%). Two tiers: direct referrals and a reduced share on
  businesses referred by your referrals. Earnings settle before they pay.
- Blueprints: complete businesses in a gallery at whop.com/blueprints; publishers earn a "10% affiliate cut" when a
  business deploys one. The page does not say whether it recurs or what it is a percentage of.
- NOT VERIFIED: the "2.7% + 30 cents" processing fee, the "30% for life" rate as a fixed figure, "partners earn 1% of ad
  spend", and Whop's agency ad accounts sitting at "meta's top tier".
- DISCLOSURE: a post or email recommending Whop with a referral link is an endorsement with a material connection (FTC
  rules above).

## Spotify -- "Spotify Strengthens AI Protections" (newsroom, 2025-09-25)
- "all music is treated equally, regardless of the tools used to make it."
- A music spam filter targets "mass uploads, duplicates, SEO hacks, artificially short track abuse, and other forms of
  slop"; "we've removed over 75 million spammy tracks" in the prior 12 months.
- New impersonation policy for AI voice clones; AI disclosures in credits through the DDEX standard.

## Google Search -- spam policies, scaled content abuse
- "Scaled content abuse is when many pages are generated for the primary purpose of manipulating search rankings and
  not helping users." First example: "Using generative AI tools or other similar tools to generate many pages without
  adding value for users".

## Google Search -- link spam (developers.google.com/search/docs/essentials/spam-policies, read 2026-09-16)
- "Link spam is the practice of creating links to or from a site primarily for the purpose of manipulating search
  rankings."
- Named examples that touch common growth advice: "Buying or selling links for ranking purposes", including "Sending
  someone a product in exchange for them writing about it and including a link"; "Excessive link exchanges ('Link to me
  and I'll link to you')"; "Using automated programs or services to create links to your site"; "Low-quality directory
  or bookmark site links"; "Keyword-rich, hidden, or low-quality links embedded in widgets that are distributed across
  various sites"; "Forum comments with optimized links in the post or signature"; and "Creating low-value content
  primarily for the purposes of manipulating linking and ranking signals".
- Consequence for a launch: listing a product on the few directories where buyers look is distribution; submitting to
  many directories for the links is the named violation. An embeddable free-tool widget must not carry keyword-rich
  links back.
- "Expired domain abuse is where an expired domain name is purchased and repurposed primarily to manipulate search
  rankings by hosting content that provides little to no value to users."

## Wikipedia -- conflict of interest (en.wikipedia.org/wiki/Wikipedia:Conflict_of_interest, read 2026-09-16)
- Editors with a conflict of interest "are strongly discouraged from editing affected articles directly" and "may
  propose changes on talk pages". Self-citation is "allowed within reason, but only if it is relevant, conforms to the
  content policies" and "is not excessive."
- So replacing a dead citation with a link to your own site is out. The accepted replacement is an archived copy of the
  original source, or a proposal on the talk page.

## Unsplash -- the Unsplash License (unsplash.com/license, read 2026-09-16)
- Images can be used "without permission from or attributing the photographer or Unsplash." Prohibited: selling
  images "without significant modification", and "Compiling images from Unsplash to replicate a similar or competing
  service".
- So uploading photos there in the hope of earning links has no footing: nobody who uses them owes you a credit.

## Adobe Stock -- generative AI content guidelines (last updated Jun 11, 2026)
- "Created using generative AI tools" checkbox: "Required for all content created with generative AI software."
- Do not put in prompts, titles or keywords: "Names of artists, real people, or fictional characters", "References to
  creative works still in copyright", "References to third-party intellectual property".
- Do not "Submit multiple versions from the same prompt or similar iterations of a prompt."
- A generative AI asset based on an identifiable person needs a model release. Violations may remove content or end
  the account.

## Audiobooks -- ACX and Spotify for Authors (read 2026-09-16)
- ACX audio submission requirements: "Your submitted audiobook must be narrated by a human unless otherwise authorized:
  Unauthorized use of text-to-speech, AI, or automated recordings in ACX titles is prohibited."
- Spotify for Authors: "Spotify for Authors accepts audiobooks produced with digital voice narration (AI narration) for
  distribution on Spotify only."

## YouTube Partner Program thresholds (support.google.com/youtube/answer/72857, read 2026-09-16)
- Ad revenue: "1,000 subscribers" plus either "4,000 qualified watch hours on long form videos in the last 365 days"
  or "10 million qualified Shorts views in the last 90 days".
- Channel memberships (fan funding): "500 subscribers" plus either "3,000 qualified watch hours on long form videos
  in the last 365 days" or "3 million qualified Shorts views in the last 90 days".
- The separate Shorts Fund described in 2021-2022 creator videos no longer exists; Shorts revenue now comes through
  the Partner Program.
- THE BAR DOUBLES ON 1 FEBRUARY 2027 (support.google.com/youtube/answer/12843009, read 2026-09-16). New creators will
  need "8,000 qualified watch hours in the last 365 days, or 20M qualified Shorts views in the last 90 days, in
  addition to still needing 1k subscribers". A channel not yet in the program has until 31 Jan 2027 to qualify at the
  current 4,000-hour / 10M-view bar. "If you are already in YPP, your status is not impacted by this update."
- STAYING IN also becomes conditional from 1 Feb 2027: at least one of "1,000 qualified watch hours in the past 365
  days", "1 million qualified Shorts views in the last 90 days", or "2 long-form videos or 5 Shorts uploaded every 90
  days", with "an extended 90-day window" to recover. Terms must be accepted in Studio "by January 31, 2027" or
  monetization features stop paying from 1 Feb 2027 until they are accepted.

## YouTube view counting -- the 2026-08-24 split (support.google.com/youtube/answer/2991785, read 2026-09-16)
- "Beginning August 24, 2026, views are counted the moment a video starts to play across all formats, including
  Shorts, long-form videos (VOD), and live streams." The public number went up without anything improving.
- The money did not move with it: "YPP earnings will still be based on 'engaged views' and 'engaged watch hours'.
  YPP eligibility will still be based on 'qualified views'." Three different metrics, one public number.
- So a rise in public views after 24 Aug 2026 is not growth, and the gap between public views and engaged views is a
  read on how many people left in the first seconds. Compare periods on engaged views only.

## Copyright in AI output -- US Copyright Office, Copyright and AI Part 2: Copyrightability (2025-01-29)
- Published 2025-01-29 (copyright.gov). Its conclusion, as reported by several law-firm summaries of the report: prompts
  alone do not give enough human control for the output to be human-authored, so prompt-only output is not
  copyrightable; human selection, arrangement and creative modification can be. Practical effect: a product that is
  raw AI output is hard to protect from copying.

## India -- the TikTok ban (VERIFIED, newsonair.gov.in, read 2026-09-16)
- Government statement of 23 August 2025: "No order has been issued to lift the ban on TikTok in India." The Ministry
  of Electronics and Information Technology called claims of unblocking "false and misleading". The ban dates from
  June 2020.
- CONSEQUENCE FOR THIS OPERATOR, who is in India: every TikTok earning path -- Creator Rewards, TikTok Shop, TikTok
  affiliate, a TikTok-first AI influencer -- is closed, and TikTok's own help and Creator Academy pages do not load
  from here either (checked 2026-09-16), which is why the TikTok rules below stay search-level.
- CapCut, also a ByteDance product: third-party sites report it blocked in India too. NOT verified against a
  government source; check before planning anything on it.

## TikTok -- AI-generated content labels (search-level; re-read before posting)
- TikTok asks creators to label realistic AI-generated content and offers an AI-generated content label.
- More detail, still search-level (2026-09-16): the label is required for AI-generated or significantly edited content
  showing realistic-looking people or scenes; minor edits and clearly artistic styles do not need it. Creators can use
  the AI-generated content setting or disclose in a caption, watermark or sticker. Using the label to deceive is a
  Terms of Service violation.
- Creator Rewards Program eligibility, search-level: 18 or older, at least 10,000 followers and 100,000 video views in
  the last 30 days, a personal account in good standing in an eligible country; qualifying videos must be original and
  at least one minute long. Unavailable in India (see the India entry above).

## Gumroad -- third-party analytics (Gumroad Help Center, via search excerpt; confirm in Settings)
- Tracking snippets are added under Settings, Third-party analytics, and run on the product page, after purchase, or
  both.

## Claude -- connectors and skills (Claude Help Center)
- Custom connector: Customize > Connectors > "+" > "Add custom connector", paste the remote MCP URL. Free plans are
  limited to one custom connector. Custom connectors reach "arbitrary services that have not been verified by
  Anthropic".
- Skills: upload a skill folder as a ZIP at Customize > Skills; needs code execution enabled.

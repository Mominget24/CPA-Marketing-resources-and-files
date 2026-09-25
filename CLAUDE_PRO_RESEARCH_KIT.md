# Claude Pro Research Kit — CPA Marketing
### How to prompt Claude Pro so it becomes your reliable CPA research partner
*Companion to `CPA_SUCCESS_PLAYBOOK.md`. Open Claude Pro → start ONE project/chat per phase → paste the context block first → then use the numbered prompts.*

---

## 0. Ground rules — how to get *reliable* output from Claude

Claude is an excellent analyst, copywriter, and planner. Its output quality follows one law: **real data in → reliable advice out.** Follow these rules and it will genuinely accelerate you:

1. **Paste real artifacts, never describe them vaguely.** Real offer terms, real tracker CSV rows, real affiliate-manager replies, your real landing-page copy. The difference between "my offer pays $2" and pasting the actual offer page text is the difference between generic advice and sharp advice.
2. **Demand the fact/assumption split.** End important prompts with: *"Separate clearly verified facts from your assumptions. If you are unsure, say so."*
3. **For anything that changes (payouts, network terms, platform rules), make Claude browse.** Claude Pro has web search — say: *"Use web search to verify this against current sources, and link them."* Never trust memorized payout numbers.
4. **Ask for the math, not the promise.** Never ask "how much can I earn?" Ask: *"Show me the break-even formula and the three numbers I must measure to know."*
5. **Make Claude red-team you.** Its highest-value use is finding holes: *"Attack this plan/landing page/offer choice. List every way it fails or violates a rule."*
6. **Never ask Claude to create:** fake testimonials, fake personas, fake reviews, spam messages, or ways around bans/TOS. Output quality drops AND you're building on the traps the playbook warns about.
7. **One thread per phase.** Keep: (1) Research thread, (2) Funnel-building thread, (3) Weekly-review thread. Claude keeps context per chat — mixing everything kills its memory.

---

## 1. MASTER CONTEXT BLOCK — paste this FIRST in every new chat

Fill the blanks once, save it in a note, paste at the start of every new Claude conversation. This is the single biggest reliability upgrade.

```
MY CPA PROJECT — CONTEXT
=========================
WHO I AM:
- Location: [country/city]
- Time available: [X] hours/day, [Y] days/week
- Devices: [phone model / PC / laptop, internet quality]
- Experience: [complete beginner / did X before]

MONEY:
- Total budget I can afford to LOSE: $[amount] (hard cap)
- Paid-ads test budget (only after organic conversions): $[amount]
- Payment rails: [PayPal verified? Payoneer? Wise?]

GOALS:
- First goal: 1 approved conversion, then first $50 payout
- Timeline: 90 days. No income promises — I want a measurable system.

RULES I FOLLOW (non-negotiable):
- Real identity everywhere; no fake personas, no fake US addresses
- No fake jobs, giveaways, gift-card bait, brand impersonation
- No self-clicks, bots, VPN leads, multiple accounts
- Every funnel includes affiliate disclosure; I only promote offers
  whose traffic rules my affiliate manager confirmed in writing

MY CURRENT STATUS:
- Networks joined: [none / CPAGrip / CPAlead / ...]
- Offers running: [none / offer name + payout]
- Traffic sources: [none / Pinterest / YouTube Shorts / ...]
- Conversions so far: [number approved / reversed]
- What I did last week: [1-2 lines]

MY ASK: act as a senior CPA affiliate who earns from compliant,
measured funnels. Be blunt. Prioritize what moves revenue. Always
separate verified facts from assumptions, and tell me what data
you need from me to be more precise.
```

---

## 2. THE PROMPT SEQUENCE — copy-paste, in order

### P0 — Kickoff (Day 1)
```
[Paste context block]

I'm starting from zero. Based on my context:
1. Confirm you understand my situation by asking me the 5 most
   important questions I haven't answered yet.
2. Then give me a week-1 checklist: what to set up, in what order,
   and what each setup costs.
Do not give me generic motivation. Give me the checklist a working
affiliate would hand a new hire.
```

### P1 — Niche research (Day 1–2)
```
[Paste context block]

Research task: propose 5 CPA niches for a beginner targeting US
traffic via Pinterest + short video, using ONLY honest angles
(skills, tools, education, genuine benefits — no prizes/giveaways/
fake jobs). For each niche give a table:
- search demand (use web search; cite sources)
- typical offer types + realistic payout ranges (mark as estimates)
- Pinterest fit (1-5) and why
- the honest "value angle" I'd give the audience
- biggest risk
Then recommend ONE for my situation and explain why.
```

### P2 — Offer selection (Day 3–4)
*(Paste this AFTER you've created network accounts and copied real offer details)*
```
[Paste context block]

Below are real offers from my [CPAGrip/CPAlead] dashboard.
[PASTE: offer name, GEO, device, action type, payout, any
restrictions shown — copy directly from the network]

Score each against this scorecard (total /25, run only ≥19):
1. Action is email submit or app install (5)
2. GEO matches US/UK/CA/AU and Pinterest traffic fits (5)
3. Payout ≥ $1.50 (3)
4. Funnel walkable on mobile (I will test; assume pending) (4)
5. AM confirmation required before running (5)
6. Offer live >2 weeks (mark unknown if unclear) (3)
Rank them, pick the best ONE, and list exactly what I must ask the
affiliate manager about it. Draft that message.
```

### P3 — Landing page build (Day 5–7)
```
[Paste context block]

My offer: [paste offer details + what the advertiser's page says].
Write landing page copy with these 7 blocks:
1. Headline (truthful promise, keyword-rich)
2. Sub-headline (what happens on click)
3. Hero image description (for Canva; no brand logos)
4. Three specific benefit bullets
5. CTA button text describing the REAL action
6. Affiliate disclosure sentence (FTC-compliant, visible)
7. Privacy line
Then give me 2 alternative headline variations.
Finally: red-team this page — list every claim that could be seen
as misleading and fix it. No fake urgency, no invented results,
no brand names I don't own.
```

### P4 — Pinterest engine (Week 2)
```
[Paste context block]

My niche: [niche]. My landing page: [paste headline + bullets].
1. Use web search to find 20 Pinterest search phrases people in
   this niche actually type (US audience). Cite where you found them.
2. Create 5 board names from those phrases.
3. Write 10 pin sets (title ≤100 chars, description ≤300 chars,
   image text suggestion) — each pin must truthfully match the
   landing page promise.
4. Give me my 30-day posting calendar (pins/day, timing, refresh rules).
```

### P5 — Affiliate manager messages (any time)
```
[Paste the AM's actual message]

Interpret this affiliate-manager reply precisely: what is allowed,
what is forbidden, what is ambiguous? List any ambiguity as a
follow-up question I should send. Draft my follow-up.
```

### P6 — WEEKLY REVIEW (every Sunday — the money prompt)
```
[Paste context block]

Here are my tracker rows this week:
[PASTE CSV ROWS from tracking_sheet.csv — every column]

Analyze like a media buyer:
1. Compute EPC, LP conversion rate, approval rate, ROI per campaign.
2. KILL list: what do I stop, and why (cite my numbers)?
3. SCALE list: what gets more volume and by how much?
4. FIX list: one hypothesis per underperformer + the exact change.
5. Next week's plan: max ONE new experiment.
Be ruthless. I'd rather kill a campaign than waste a week on it.
```

### P7 — Paid test planning (only after ≥10 organic approved conversions)
```
[Paste context block]

My organic data: [approved conversions, LP CR %, approval rate %].
My offer payout: $[X].
1. Show my break-even CPC formula with my real numbers.
2. Design a $[5-20] paid test: source, targeting, 3 truthful
   creatives, daily budget, stop-loss rules.
3. Write the decision table: what result means KILL / FIX / SCALE.
Use web search to confirm the ad source's minimums and rules today.
```

### P8 — Compliance red-team (before ANY launch)
```
Here is everything in my funnel: [landing page copy + pin/post copy +
offer details + traffic source].
Act as: (a) the network's fraud team, (b) Pinterest's trust & safety,
(c) the FTC. Each one tries to reject my funnel. List every
violation or risk they'd flag, then give me the corrected version.
```

---

## 3. WHAT TO FEED CLAUDE (your data checklist)

Reliability scales with what you paste. Collect these as you go:

| Artifact | Where it comes from | Feed it to prompt |
|---|---|---|
| Offer details (GEO, payout, action, restrictions) | Network dashboard | P2, P3 |
| Affiliate-manager replies | Network inbox | P5 |
| Landing page copy (yours) | Your builder | P3, P8 |
| Pin/post titles + descriptions | Your content | P4, P8 |
| Tracker CSV rows | tracking_sheet.csv | P6 (weekly) |
| Screenshots (Claude Pro reads images!) | Offer pages, dashboards, warnings | any — upload and ask "what exactly does this say/mean?" |
| Network warning emails | Network | P5 + STOP immediately |

---

## 4. WHAT CLAUDE CANNOT DO — don't waste the subscription

- **Cannot guarantee earnings.** Anyone/anything printing income forecasts is hallucinating. Ask for formulas and measurements instead.
- **Cannot know today's offer payouts/terms from memory.** Always add "verify with web search" for anything time-sensitive.
- **Cannot approve offers.** Only your network/AM can. Claude drafts the questions; humans at the network give the yes.
- **Cannot replace execution.** Claude compresses the *thinking* — posting daily, testing on mobile, logging numbers is still your 60–90 minutes.

---

## 5. YOUR 90-DAY RHYTHM WITH CLAUDE PRO

| When | Claude session |
|---|---|
| Day 1 | P0 kickoff → answer its 5 questions |
| Day 1–2 | P1 niche → pick one |
| Day 3–4 | Network signups → P2 offer selection → send AM questions |
| Day 5–7 | P3 landing page → P8 red-team → launch funnel |
| Week 2 | P4 Pinterest engine → start daily 2–3 pins |
| Every Sunday | P6 weekly review (never skip — this is where the money is made) |
| When AM replies | P5 interpretation |
| After 10 approved conversions | P7 paid test |
| Before every new launch | P8 red-team |

**One sentence to remember:** *Claude plans the war; your tracker wins it. Paste real numbers every Sunday and this system improves itself.*

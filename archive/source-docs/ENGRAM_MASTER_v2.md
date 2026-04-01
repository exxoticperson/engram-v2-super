# ENGRAM — Operating Bible v2
### Final. Clean. No contradictions. Move on this.

---

## WHAT ENGRAM IS

**ENGRAM is a pre-launch creative diagnostics service for short-form paid-social video ads.**

It diagnoses where an ad loses the viewer, why it happens, and delivers a concrete repair brief — before media spend.

**What it is not:**
- Not a conversion guarantee
- Not a ROAS predictor
- Not an automated video generator (not yet)
- Not a dashboard or SaaS product yet
- Not a platform
- Not a neuroscience company

**What it replaces in the buyer's workflow:**
The guesswork of "which ad do we push budget behind?" before launch. Brands and agencies currently make that decision on gut feel or by paying to find out through live spend. ENGRAM replaces that with a structured pre-launch audit delivered in 48–72 hours.

**The one sentence:**
> "We show where a short-form ad loses the viewer before you spend a dollar on media — and hand you the specific fix."

---

## THE HONEST TECHNICAL POSITION

TRIBE v2 predicts fMRI brain responses to video, audio, and text stimuli. It was trained on 1,117 hours of fMRI data from 720 subjects. It is a neuroscience research model, not a business outcome predictor.

This means:
- ENGRAM predicts **attention, comprehension, and memory salience proxies** — not ROAS, not sales, not CTR
- Every report must include this framing: *"This is a decision-support tool designed to reduce creative waste, not a guarantee of business outcomes"*
- Never say "this ad will perform better" — say "this ad is more likely to hold attention through the CTA based on these diagnostic signals"

That one distinction protects the entire business. Overclaiming once to the wrong person ends ENGRAM before it starts.

---

## THE STACK — BY PHASE

### V1 — What exists right now (the only thing that matters for 30 days)

**Manual service. No automation. No software.**

- Analyst (you) watches the ad
- Applies the ENGRAM audit framework manually
- Pulls 7-day category trend context (Grok 4.20 / X data + TikTok observation)
- Generates the delta metric diagnosis
- Writes the repair brief and hook variants
- Produces the PDF report
- Delivers in 48–72 hours

**Tools used internally (never client-facing):**
- TRIBE v2 — neural response scoring layer (run locally or via HuggingFace)
- Gemini Embedding 2 — semantic meaning mapping per scene/moment
- Grok 4.20 — real-time category trend context from X
- GPT-5.4 / Gemini 3.1 Pro — writing, repair brief generation, hook variants
- Manual scene analysis + transcript parsing

**What the client receives:**
- ENGRAM Pre-Flight Audit PDF (9 pages)
- Optional 30-min Loom walkthrough
- 30-min debrief call

That is V1. Nothing else is V1.

---

### V2 — Assisted pipeline (Months 2–4, after first retainer)

Only build after first retainer revenue is secured.

- Automated intake form (Typeform/Tally + Drive)
- Transcript extraction + scene segmentation (Whisper + ffmpeg)
- Gemini Embedding 2 semantic scoring automated
- TRIBE response curve automated
- M2.7 agent generates recut brief draft (analyst reviews and refines)
- Grok trend context automated pull
- Report template auto-populated
- Full audit time drops from 4 hours to 45 minutes

---

### V3 — Platform layer (Months 6–12, after 2+ retainers)

- Self-serve tier for agencies
- Batch processing for multiple ads
- Benchmark database becomes accessible
- Quarterly Creative Intelligence Report published
- API for embedding ENGRAM scores into agency dashboards
- Begin fine-tuning proprietary model on accumulated dataset

**Video generation (LTX 2.3 / Helios) belongs here, not V1 or V2.**
Not because it's not valuable — it is — but because it requires QA, render review, version control, and production accountability that don't belong in a service business at early stage. Add it when it makes margins better, not when it makes the pitch more impressive.

---

## THE GROK LAYER — CORRECT POSITIONING

Grok 4.20 with real-time X data access is a genuine advantage. But it needs to be positioned correctly.

**What it does internally:**
- Before every audit, scans X/TikTok for 7-day activity in the client's category
- Identifies what hook structures, visual patterns, pacing, and audio treatments are currently dominating
- Produces a "category trend context" that frames every diagnostic in the audit
- Powers the Cultural-Neural Alignment metric

**What it is:**
A research and context layer. An analyst aid. A real-time benchmark input.

**What it is not:**
The hero of the pitch. The main differentiator in outreach. A scientific pillar.

Why: X trend data is noisy. What pops on X ≠ what wins on Meta. TikTok trends move daily. Using Grok as a context layer is sound. Building the entire pitch around real-time X intelligence is fragile.

**The correct framing externally:**
Never mention Grok in outreach. In the report, the output of the Grok layer appears as the "Category Trend Snapshot" — what's working right now in the category. That is compelling to clients. The mechanism behind it stays internal.

**The Cultural-Neural Alignment metric is real and unique.** It measures whether an ad is both neurally strong AND aligned with current category patterns. No competitor does this. But it's a metric inside the report — not the headline.

---

## THE METRICS — LOCKED VOCABULARY

These nine metrics are the product language. Use them in every report, every pitch, every conversation.

| Metric | What it means |
|--------|--------------|
| **Hook Friction** | Visual stimulus is strong but semantic setup is weak — viewer is grabbed but confused |
| **Comprehension Drift** | Message complexity rises while predicted attention falls |
| **Reveal Waste** | Product/value appears after attention has already collapsed |
| **CTA Recall Gap** | CTA moment has low memory salience — won't stick |
| **Modality Conflict** | Visuals, voiceover, and captions are not reinforcing each other |
| **Branding Delay** | Brand or product identity arrives too late to encode |
| **Edit Saturation** | Too many cuts for the underlying message density |
| **Dead Air Window** | 3+ seconds where no new information is being processed |
| **Cultural-Neural Alignment** | Degree to which the creative matches current top-performing category patterns |

---

## ICP — LOCKED

**Primary (first 30 days):**
Performance creative agencies managing Meta/TikTok paid social for beauty and skincare DTC brands with $30K–$100K/month ad spend across their client base.

Why beauty/skincare first:
- Highest creative velocity in DTC (new ad variants weekly)
- Visually rich — benefits most from modality analysis
- Hook dependency is extreme (3-second rule is brutal in beauty)
- Well-understood pain: agencies know their hooks are killing hold rates
- Agencies in this space are already buying Motion, AdSpy, MagicBrief — they spend on tools

**Secondary (Month 2+):**
Fashion/apparel DTC agencies. Same velocity, same pain, slightly different creative language.

**Not yet:**
US/global brands directly, Gulf market, pharmaceutical, EdTech, architecture. These are real. They are not now.

---

## PRICING — UNIFIED LADDER (ONE VERSION, FINAL)

| Offer | Price | What's included |
|-------|-------|----------------|
| **Pilot Audit** | $2,500 | 1–2 ads, full report, 30-min debrief |
| **Pre-Flight Audit** | $5,000–$7,500 | 3–5 ads, full reports, 60-min debrief, recut briefs |
| **Pre-Production Screen** | $2,000 | Script/storyboard/rough cut scored before production |
| **Monthly Retainer** | $10,000–$15,000 | All pre-launch ads scored, monthly trend context report, priority turnaround |

**Pricing logic:**
An agency spending $50K/month on media that pushes one bad creative loses $8K–$15K finding out it didn't work. One good audit pays for itself on the first saved campaign. Price reflects value delivered, not hours worked.

Do not offer discounts in exchange for case study rights — that signals desperation. Instead, offer: "First pilot at $2,500. If it doesn't deliver clarity you can act on, I'll refund it." That's confidence, not cheapness.

---

## COMPETITOR FRAMING — HONEST VERSION

**Motion:** Excellent creative analytics and account-level learning. Post-hoc (what already worked) + "before publish" scoring. Does not explain *why* — gives scores, not diagnosis. Does not deliver repair briefs.

**Kantar LINK AI:** Enterprise-grade, norms database of 260K+ tests, 15-minute results. Expensive, slow to procure, designed for big brand teams. Not accessible to mid-size agencies.

**Neurons:** Neuroscience-backed attention/memory scoring, API available. Strong on attention maps. No cultural trend layer. No hands-on repair.

**ENGRAM's gap:**
> "Every other tool tells you what happened or gives you a number. ENGRAM tells you exactly where the creative breaks, why it breaks, what to recut, and whether the approach is aligned with what's winning in your category right now. In 48 hours."

That framing is honest, specific, and not fragile.

---

## PROOF POLICY

Include this in every client deliverable, and be ready to say it on every call:

*"ENGRAM is a creative decision-support system. Our diagnostics are based on neural response prediction and semantic analysis — they identify likely attention failures and comprehension gaps. They are not guarantees of business outcomes. The goal is to reduce creative waste and improve launch selection, not to replace your judgment."*

This is not weakness. This is what separates you from snake oil. Every credible vendor in this space has a version of this disclaimer. Saying it first builds trust.

---

## VALIDATION LOOP — EVERY AUDIT LOGS THIS

From audit #1, every engagement populates this dataset:

| Field | What to log |
|-------|------------|
| Category | Beauty, fashion, fitness, SaaS, etc. |
| Platform | Meta or TikTok |
| Ad length | In seconds |
| Input type | Final cut / rough cut / script / storyboard |
| Delta metrics triggered | Which of the 9 were flagged |
| ENGRAM Score | Composite out of 100 |
| Recommended fixes | Brief summary |
| Did client implement fixes? | Yes / No / Partial |
| Performance after launch | Hook rate, hold rate, CTR if client shares |
| Client feedback | What they said was most useful |

This is the beginning of the moat. 30 rows in this table is a pattern. 100 rows is a benchmark. 500 rows is a defensible dataset no competitor can buy.

---

## ROADMAP — PHASE-BY-PHASE

### Phase 0 — Foundation (Days 1–3)

**Day 1:**
- Watch these three competitor tools: Motion "analyze before publish," Neurons demo, Kantar LINK AI demo.
- Read TRIBE v2 paper section 3 (model architecture) and section 5 (limitations). Know the limits.
- Set up Grok 4.20 access (SuperGrok subscription).

**Day 2:**
- Pick one real beauty/skincare DTC brand ad currently running on Meta or TikTok.
- Run full ENGRAM audit on it using the audit skill.
- Produce the sample PDF. Make it look like it cost $5,000 to produce.
- This is your only credibility asset for the first 14 days.

**Day 3:**
- Build lead list: 25 performance creative agencies in beauty/skincare DTC.
- Source: LinkedIn (search "performance creative agency beauty DTC"), Twitter/X (search "hook rate skincare ads TikTok"), Clutch.co.
- Log each with: name, agency, LinkedIn, pain signal, one personalization line.

---

### Phase 1 — Validation Sprint (Days 4–14)

**Days 4–7:**
- Send 15 LinkedIn DMs using Template A from the outreach skill.
- Post one LinkedIn piece: "I audited a [beauty] DTC ad and found where it loses the viewer at second [X]. Here's the breakdown." Attach sanitized sample.
- Do NOT mass send. 15 targeted, personalized messages > 200 generic ones.

**Days 8–10:**
- Follow up non-replies at day 5.
- Get on every call you can. Discovery first: "How do you currently decide which ad goes into spend?" Listen.
- Show the sample audit live on screen during calls. Don't explain ENGRAM — show it.

**Days 11–14:**
- Close one paid pilot at $2,500.
- Run it within 48 hours of payment.
- Speed is your credibility substitute while you have no case studies.

**Hard success gate at Day 14:**
- 20+ qualified outreaches
- 5+ replies
- 3+ calls
- 1 paid pilot closed

Miss this gate: fix the message, not the market. Don't build software. Don't pivot.

---

### Phase 2 — Case Study & Revenue (Weeks 3–8)

- Complete 3–5 paid audits
- Track the validation loop on every one
- After 3 audits: identify which diagnostic metric drives the strongest client reaction — lead with that in all future outreach
- Post one sanitized case study on LinkedIn (with client permission or anonymized)
- Target: $15,000–$25,000 in audit revenue by Week 8

---

### Phase 3 — Retainer Conversion (Months 2–4)

After 2 paid audits with the same agency, pitch the retainer:
*"Instead of per-audit pricing, let's make this part of your launch process — every ad gets scored before it goes live. Monthly trend context included."*

- First retainer target: $10,000/month
- Two retainers = $20,000/month recurring
- That's the business becoming real
- Hire one analyst at this stage to help with manual audit execution

---

### Phase 4 — Technology Build (Months 3–6)

Only starts after retainer revenue covers build cost.

Build order (strict):
1. Intake form + Drive submission (Typeform/Tally) — Week 1
2. Transcript extraction + scene segmentation (Whisper + ffmpeg) — Week 2
3. TRIBE v2 automated scoring pipeline — Weeks 3–4
4. Gemini Embedding 2 semantic mapping — Weeks 5–6
5. M2.7 recut brief generation (analyst-reviewed) — Weeks 7–8
6. Grok trend context automated pull — Weeks 9–10
7. ENGRAM Score engine + report auto-generation — Weeks 11–12

Result: audit time drops from 4 hours to 45 minutes. Margins become sustainable.

---

### Phase 5 — Platform + Moat (Months 6–12)

- Self-serve tier for agencies
- Benchmark database goes live
- Quarterly Creative Intelligence Report published (free lead magnet)
- API for embedding ENGRAM into agency dashboards
- Begin fine-tuning proprietary model on accumulated audit data
- Explore video generation integration (LTX 2.3 / Helios) once pipeline is stable

---

## THE THREE PROJECTS — FINAL RANKING

**Jawab** — Don't touch it right now. Clearest pain, fastest cash, smallest credibility barrier. It's the emergency fund if ENGRAM validation fails.

**ENGRAM** — The sprint. Everything for 14 days. Then evaluate honestly.

**Fragment** — Parked. Not dead. Not now.

---

## WHAT THIS DOCUMENT IS NOT

It is not a pitch deck.
It is not a business plan.
It is not a forecast.

It is an operating document for a 14-day market test.
If the test works, everything gets bigger.
If it doesn't, you know before you've built anything.

That's the discipline.

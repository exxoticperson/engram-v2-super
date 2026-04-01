---
name: engram-audit
description: Generate a structured ENGRAM Pre-Flight Audit report for short-form paid-social video ads (Meta/TikTok). Use this skill whenever the user asks to audit a video ad, analyze creative performance, score an ad before launch, generate a neural creative diagnosis, build an ENGRAM report, or review hook/reveal/CTA performance in a video. Also use when the user wants to create a sample audit, build a client deliverable, or score creative variants against each other.
---

# ENGRAM Pre-Flight Audit Skill

ENGRAM is a creative intelligence service that predicts where short-form ads lose the viewer before media spend, diagnoses why, and delivers the repair. This skill produces structured Pre-Flight Audit reports.

## What This Skill Produces

A full ENGRAM Pre-Flight Audit delivers:
1. Cultural-Neural Trend Context (category landscape)
2. Per-ad Response Curve (attention by moment)
3. Semantic-Neural Delta breakdown
4. Moment-by-moment flags with timestamps
5. Hook / Reveal / CTA diagnosis
6. Recut recommendations + edit sequence
7. Rewritten hook variants
8. ENGRAM Composite Score
9. Launch order recommendation (if multiple variants)

---

## Step 1 — Gather Inputs

Before generating the audit, collect:
- The video ad(s) — transcript, description, or actual file
- Platform (Meta or TikTok)
- Product category (beauty, fitness, fashion, SaaS, food, etc.)
- Target audience
- Current spend level (approximate)
- Any known performance data (hook rate, hold rate, CTR) if available
- Number of variants to audit (1–5)

If inputs are missing, ask for them. Do not generate a fake audit on no information.

---

## Step 2 — Cultural-Neural Trend Context

Open every audit with a "Category Trend Snapshot" — what creative patterns are currently dominating this product category on the target platform.

Structure it as:
```
CATEGORY TREND SNAPSHOT — [Category] on [Platform]
Week of [date]

Dominant hook styles: [list 2-3]
Top-performing reveal timing: [e.g., product reveal at 4-7s performs highest]
Audio patterns: [e.g., ambient + VO outperforming music-only]
Visual pacing: [e.g., 6-8 cuts in first 5s is current sweet spot]
Oversaturated patterns to avoid: [e.g., talking-head only hooks are declining]
```

If real-time Grok/X data is available, pull actual category signals. If not, use known platform patterns and flag it as general benchmark data.

---

## Step 3 — Response Curve Analysis

Map the ad second-by-second into 5 zones:

**Zone 1 (0–3s): Hook Window**
- Does the first frame create a pattern interrupt?
- Is there a clear reason to keep watching?
- Is there audio hook alignment?

**Zone 2 (3–8s): Attention Retention**
- Is semantic clarity building or collapsing?
- Is there narrative momentum?
- Edit density appropriate?

**Zone 3 (8–15s): Product/Value Reveal**
- When does the product appear?
- Is the value proposition clear before the brain loses interest?
- Is there a comprehension spike or drop at reveal?

**Zone 4 (15–25s): Engagement Sustain**
- Does the message deepen or repeat?
- Is there new information being processed?
- Social proof / credibility moment?

**Zone 5 (25s+): CTA Window**
- Is the CTA clear?
- Is there enough memory salience built up?
- Does the final frame reinforce action?

Output this as a written curve, flagging each zone as STRONG / MODERATE / WEAK.

---

## Step 4 — Semantic-Neural Delta Metrics

Apply these eight diagnostic metrics. For each one, flag: DETECTED / CLEAR.

| Metric | Definition |
|--------|-----------|
| **Hook Friction** | Strong visual stimulus but weak semantic setup — viewer is grabbed but confused |
| **Comprehension Drift** | Semantic complexity rises while predicted engagement falls |
| **Reveal Waste** | Product/value prop arrives after attention has already collapsed |
| **CTA Recall Gap** | CTA moment has low predicted memory salience — won't stick |
| **Modality Conflict** | Visuals, voiceover, captions not reinforcing each other |
| **Branding Delay** | Brand or product identity arrives too late to encode |
| **Edit Saturation** | Too many cuts for the underlying message density — visual noise |
| **Dead Air Window** | 3+ seconds where nothing new is being encoded |

For each detected issue, provide:
- Timestamp where it occurs
- Severity (HIGH / MEDIUM / LOW)
- One-sentence explanation

---

## Step 5 — ENGRAM Composite Score

Score the ad across 8 dimensions, each out of 10:

1. **Attention Continuity** — Does it hold attention curve without major drops?
2. **Semantic Clarity** — Is the message easy to process at pace?
3. **Memory Salience** — Will the viewer remember what they saw?
4. **Reveal Timing** — Does the product appear at the right moment?
5. **CTA Retention** — Is the action clear and sticky?
6. **Modality Alignment** — Do visual + audio + text reinforce each other?
7. **Brand Imprint** — Is brand identity encoded early and reinforced?
8. **Edit Efficiency** — Is pacing appropriate for message density?

**ENGRAM Score = weighted average (out of 100)**

Scoring guide:
- 80–100: Launch ready. Optimize media, not creative.
- 60–79: Conditional launch. Fix flagged issues first.
- 40–59: Do not launch. Significant structural problems.
- Below 40: Rebuild from brief.

---

## Step 6 — Repair Recommendations

For every HIGH severity flag, provide a concrete fix:

**Format:**
```
ISSUE: [Metric name] at [timestamp]
DIAGNOSIS: [What's happening and why it kills performance]
FIX: [Specific edit, rewrite, or structural change]
IMPACT: [What this fix will improve in the response curve]
```

Then provide:
- **Recut sequence**: Recommended edit order if restructuring
- **Hook rewrites**: 3 alternative opening lines/visuals
- **CTA variants**: 2 alternative CTA phrasings
- **Optional**: Flag whether AI variant regeneration (LTX 2.3) is appropriate

---

## Step 7 — Launch Recommendation

If multiple variants:
- Rank them by ENGRAM Score
- Flag which to launch first and why
- Note which to recut before secondary push

If single ad:
- Clear GO / CONDITIONAL GO / NO GO verdict
- Specific conditions for Conditional GO

---

## Output Format

```
═══════════════════════════════════════
ENGRAM PRE-FLIGHT AUDIT
[Client/Brand] | [Date] | [Platform]
═══════════════════════════════════════

CATEGORY TREND SNAPSHOT
[Section content]

RESPONSE CURVE
[Zone-by-zone analysis]

SEMANTIC-NEURAL DELTA DIAGNOSTICS
[Table of metrics]

ENGRAM COMPOSITE SCORE: [X/100]
[8-dimension breakdown]

REPAIR RECOMMENDATIONS
[Flagged issues with fixes]

HOOK VARIANTS
[3 alternatives]

LAUNCH RECOMMENDATION
[GO / CONDITIONAL / NO GO + reasoning]

═══════════════════════════════════════
```

---

## Notes

- Never fabricate specific performance data (CTR, ROAS) unless provided by client
- Flag when trend context is benchmark-based vs real-time
- Keep language in business terms — no "fMRI," no "brain scan," no "neural network" in client reports
- If a pre-production input (script/storyboard) is provided instead of a finished ad, note this is a pre-production score and adjust Zone analysis accordingly
- Pricing for reference: Pre-production audit $1,500–$2,000 | Pre-flight audit $3,500–$8,000 | Retainer $12,000–$15,000/mo

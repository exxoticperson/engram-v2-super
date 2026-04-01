---
name: engram-audit
description: Produce ENGRAM Pre-Flight Audits for short-form paid-social ads and pre-production creative inputs. Use this skill for ad diagnosis, scorecards, repair recommendations, launch verdicts, and sample audit creation. This version is the live canonical audit workflow in V2 Super.
---

# ENGRAM Audit

Use this skill to create every ENGRAM audit in the live system.

## Operating stance

- Manual service first
- No performance guarantees
- No internal model names in client-facing output
- No fabricated performance data
- One revision round per audit
- Current audit wording is a temporary baseline until the new diagnostic report is provided

## Required inputs

- ad file, public link, transcript, or structured description
- platform
- category
- ad length

Useful if available:

- target audience
- campaign objective
- performance data
- variant count

For pre-production:

- script
- storyboard
- shot list
- rough cut
- creative brief

## Confidence labels

- HIGH: final cut plus platform data
- MEDIUM: final cut without platform data
- LOW: script, storyboard, or rough cut
- CONTEXT-LIMITED: description only

Adjust certainty language to the confidence level.

## Required report structure

Follow the live template in `ENGRAM_SAMPLE_AUDIT_TEMPLATE.txt`.

The required sequence is:

1. Cover
2. Executive Summary
3. Category Trend Snapshot
4. Response Curve
5. Diagnostic Breakdown
6. ENGRAM Scorecard
7. Repair Recommendations
8. Recut Brief
9. Launch Recommendation

## Locked metric system

Use these nine metrics only:

1. Hook Friction
2. Comprehension Drift
3. Reveal Waste
4. CTA Recall Gap
5. Modality Conflict
6. Branding Delay
7. Edit Saturation
8. Dead Air Window
9. Cultural-Neural Alignment

Never fall back to an eight-metric version.

## Score dimensions

Score these nine dimensions:

- Attention Continuity
- Semantic Clarity
- Memory Salience
- Reveal Timing
- CTA Retention
- Modality Alignment
- Brand Imprint
- Edit Efficiency
- Cultural-Neural Alignment

Composite score is out of 100.

Interpretation bands:

- 80 to 100: Launch ready
- 60 to 79: Conditional launch
- 40 to 59: Do not launch yet
- below 40: Rebuild from brief

## Repair rules

- Prioritize high-severity structural problems
- Limit repair section to the three most important actions
- Make each fix specific enough that an editor or creator can act on it immediately
- Recut brief stays written; V1 does not promise generated replacement footage

## Mandatory proof policy

Every report must include this exact statement:

> ENGRAM diagnostics are based on neural response prediction and semantic analysis signals. They identify likely attention failures and comprehension gaps. They are not guarantees of business outcomes. This is a decision-support tool designed to improve launch selection and reduce creative waste, not a predictor of conversion rate, ROAS, or sales.

## Logging after delivery

Capture at minimum:

- category and platform
- input type
- metrics triggered
- composite score
- top repair recommendation
- implementation status if known
- client feedback
- outcome data if shared

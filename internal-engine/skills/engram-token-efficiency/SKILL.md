---
name: engram-token-efficiency
description: Reduce token and model spend for ENGRAM only when output quality is preserved. Use this skill for repetitive internal workflows, batch research, routing decisions, and draft-generation steps where cheaper execution will not materially weaken the final result.
---

# ENGRAM Token Efficiency

Use this skill to save tokens only when quality stays intact.

## Core rule

If quality would materially drop, do not optimize for spend.

This skill exists to remove waste, not to make ENGRAM cheaper at the expense of trust, clarity, or conversion.

## Safe use cases

- internal research summaries
- lead qualification batches
- battle-card first drafts
- trend clustering
- CSV or YAML updates
- router or asset hygiene checks
- repetitive formatting transforms

## Unsafe use cases

- final client-facing audits
- final outreach for high-value targets without review
- pricing or business-model changes
- proof assets shown to prospects without review
- design-direction decisions without human judgment

## Optimization levers

- use the smallest capable model for low-risk structured work
- keep prompts tight and artifact-oriented
- batch similar tasks together
- avoid re-reading large files when a focused excerpt is enough
- stop loops when the next action is already clear
- store reusable structure in assets instead of regenerating it

## Required review standard

Before using a cheaper path, ask:

1. Is this internal-only?
2. Is the output easy to verify quickly?
3. Would a weaker draft still be acceptable because a stronger review comes after it?
4. If this were slightly worse, would it hurt trust, revenue, or strategic quality?

If the answer to 4 is yes, do not optimize.

## Collaboration

Use with:

- `engram-agentic-workflows`
- `engram-skill-lab`
- `engram-business-overseer`

## Asset

Use `assets/ops/token_efficiency_checklist.txt`.

## Good output

The result should tell the operator:

- where to save tokens safely
- where not to save tokens
- what model tier or workflow tier fits each task
- what still needs high-quality review

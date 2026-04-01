---
name: engram-skill-lab
description: Research, create, refine, merge, and prune ENGRAM skills so the system keeps evolving toward higher leverage. Use this skill when the user wants to improve existing skills, identify gaps, write new skills, collapse overlaps, or run a skill-R&D loop for the business.
---

# ENGRAM Skill Lab

Use this skill as the meta-layer for improving the ENGRAM skill system itself.

## What this skill owns

- skill gap analysis
- skill overlap detection
- new skill creation
- refinement of weak skills
- pruning of redundant skills
- routing improvements in the root operator system

## Core questions

- which workflows are still manual and repetitive
- which skills overlap too much
- which skills have weak triggers or vague outputs
- which business bottlenecks need new skills
- which skills should become assets, not prose

## Review standard

For each candidate skill or change:

- what user problem it solves
- what trigger should invoke it
- what it should output
- what assets it depends on
- whether it should be public-facing, internal-only, or operator-only

## Rules

- prefer fewer strong skills over many weak ones
- do not create a skill for a one-off task
- if a skill is mostly reusable structure, add assets too
- keep skill names specific and triggerable
- update the root router when the live set changes

## Assets

Use:

- `assets/ops/skill_refinement_loop.txt`
- `assets/ops/agent_handoff_protocol.txt`
- `assets/research/skill_backlog.csv`

## Best uses

- weekly skill review
- pre-implementation architecture pass
- bundle cleanup after several iterations
- deciding what new capability belongs in ENGRAM next

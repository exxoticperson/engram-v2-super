# START HERE
## ENGRAM V2 Super bootstrap and project state

This file is the fastest way for a fresh Codex session to understand the project, where it stands, and what to do next.

## What this project is

ENGRAM is a pre-launch creative diagnostics service for short-form paid-social video ads.

The current live wedge is:

- performance creative agencies
- Meta and TikTok paid social
- beauty and skincare DTC brands

The current business model is:

- manual service first
- no software-first positioning
- diagnosis, repair, and decision support before spend

## Folder split

The repo is now intentionally split into two layers:

- `client-facing/` for selling material and proof assets
- `internal-engine/` for doctrine, skills, workflows, agents, and internal operating logic

Use `archive/` only for reference.

## The most important files to read first

Read these in order:

1. `START_HERE.md`
2. `PROJECT_STATE.md`
3. `DECISIONS_LOG.md`
4. `client-facing/START_SELLING.md`
5. `internal-engine/SKILL.md`
6. `internal-engine/ENGRAM_CORE.md`
7. `client-facing/ENGRAM_OFFER.md`
8. `internal-engine/ENGRAM_EXECUTION.md`
9. `client-facing/ENGRAM_SAMPLE_AUDIT_TEMPLATE.md`
10. `client-facing/ENGRAM_CONTRACTS.md`
11. `internal-engine/internal/ENGRAM_CORE_AGENTS.md`
12. `internal-engine/internal/ENGRAM_AGENTIC_EXECUTION.md`
13. `internal-engine/internal/ENGRAM_OVERSIGHT_AGENT.md`

Then inspect:

- `client-facing/`
- `internal-engine/skills/`
- `internal-engine/assets/`
- `archive/`

## What has already been done

### Canonicalization

The project was cleaned into a curated `V2 Super` bundle and then split into:

- a client-facing layer
- an internal-engine layer

That included:

- one live doctrine
- one live offer ladder
- one proof boundary
- one live audit vocabulary
- one active skill system
- archived legacy docs and skills for reference

### Skills

The repo contains:

- core ENGRAM operating skills
- outreach and email automation skills
- agentic workflow and skill-R&D skills
- transferred and adapted "superpower" skills that fit ENGRAM
- business oversight skill
- two core project agents
- design-language and client-experience design skills
- a guarded token-efficiency skill

### Assets

The repo includes working assets for:

- intake
- pipeline tracking
- audit scorecards
- benchmark logging
- outreach snippets
- discovery calls
- client emails
- contract templates
- agent loops and handoff rules
- design research
- business review

### GitHub

This bundle has already been pushed to GitHub as:

`exxoticperson/engram-v2-super`

## The two core agents

These are the two agents closest to revenue right now:

### 1. Outbound Commander

Owns:

- target prioritization
- lead qualification
- battle cards
- personalization
- outreach drafting
- follow-up priorities
- pipeline momentum

### 2. Proof Architect

Owns:

- sample audit refinement
- proof packaging
- report clarity
- client-facing trust quality
- design-system application to proof assets

They share the same handoff protocol:

- `assets/ops/agent_handoff_protocol.txt`

## Current project state

The architecture is strong enough.

The next bottleneck is not more system-building.

The next bottleneck is:

- tightening the flagship sample audit
- selecting or validating a design direction for proof assets
- running outreach on a real target batch

## What is still unfinished

These items are intentionally not fully locked yet:

1. The final audit/report wording
   The current sample audit template is a strong baseline, but the final diagnostic report still needs to be applied.

2. The flagship sample audit asset
   The structure exists, but the actual best-in-class client-facing proof asset still needs a final pass.

3. Real data in the operator files
   Some CSVs still contain placeholder starter rows and should be populated with real targets, real reviews, and real outreach runs.

4. Minor tree cleanup
   There may be a stale empty skill folder from a merge. It does not affect operation, but can be removed later.

## What to do next

If the goal is revenue now, do this in order:

1. Ingest the latest diagnostic report or audit preview
2. Upgrade the sample audit into the flagship proof asset
3. Pick one real agency or a small lead batch
4. Run the Outbound Commander workflow
5. Send outreach
6. Track replies and improve from reality, not from theory

## Recommended startup prompt for a fresh Codex session

Use something like this:

> Read `START_HERE.md`, `PROJECT_STATE.md`, and `DECISIONS_LOG.md`, then read `client-facing/START_SELLING.md` and `internal-engine/SKILL.md`. After that, inspect the client-facing layer and the internal-engine layer, summarize where the project stands, and help me execute the next revenue-focused step.

## Ground truth rule

If there is any conflict:

- root docs beat archive files
- live skills beat archived skills
- current assets beat old assumptions
- execution and revenue beat architecture theater

## Final note

This repo is not just documentation.

It is an operating system for ENGRAM with a separate selling layer.

Use:

- `client-facing/` to validate demand
- `internal-engine/` to support execution
- reality to decide what gets built next

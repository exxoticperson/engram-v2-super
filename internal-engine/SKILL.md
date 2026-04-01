---
name: engram-operator-os
description: Operate the live ENGRAM business system. Use this skill whenever the user asks to run, package, position, sell, deliver, or improve ENGRAM as a manual pre-launch creative diagnostics service. This root skill routes work to the active ENGRAM modules and keeps the bundle on the canonical doctrine.
---

# ENGRAM Operator OS

This is the root entrypoint for the live ENGRAM system inside `V2 Super`.

Use this package in the following order:

1. Read `ENGRAM_CORE.txt` for the canonical doctrine.
2. Read `../client-facing/ENGRAM_OFFER.txt` for positioning, pricing, and proof policy.
3. Read `ENGRAM_EXECUTION.txt` for the chronological operating order.
4. Read `../client-facing/ENGRAM_SAMPLE_AUDIT_TEMPLATE.txt` for the current report structure.
5. Read `../client-facing/ENGRAM_CONTRACTS.txt` for payment and scope templates.
6. Use `assets/` for internal operator templates and `../client-facing/assets/` for selling materials.

## Routing rules

Route to the active skill that matches the job:

- `skills/engram-audit/SKILL.md` for audit generation, scoring, repair recommendations, and sample audit work
- `skills/engram-outreach/SKILL.md` for lead sourcing, messaging, and outreach planning
- `skills/engram-outbound-commander/SKILL.md` for the core outreach-and-pipeline execution agent
- `skills/engram-execution-coordinator/SKILL.md` for keeping the first-client stack moving without reopening strategy
- `skills/engram-ops/SKILL.md` for intake, delivery, debrief, revisions, and logging
- `skills/engram-pipeline/SKILL.md` for CRM tracking and follow-up prioritization
- `skills/engram-trend-research/SKILL.md` for category trend context and benchmark-based snapshots
- `skills/engram-benchmark/SKILL.md` for quarterly analysis and benchmark reporting
- `skills/engram-positioning/SKILL.md` for messaging, FAQ, objections, and packaging
- `skills/engram-proof-architect/SKILL.md` for the core proof-and-sample-audit refinement agent
- `skills/engram-sales-call/SKILL.md` for discovery calls, pilot closes, and retainer conversion
- `skills/engram-email-automation/SKILL.md` for email sequencing, reply handling, and semi-automated outbound
- `skills/engram-agentic-workflows/SKILL.md` for recurring loops, workflow orchestration, and automation-ready execution
- `skills/engram-skill-lab/SKILL.md` for skill discovery, refinement, and capability R&D
- `skills/engram-business-overseer/SKILL.md` for top-level business review, change review, backtesting, and noise reduction
- `skills/engram-token-efficiency/SKILL.md` for safe token-spend reduction when quality will not be harmed
- `skills/engram-battlecards/SKILL.md` for prospect-specific and competitor-specific battle cards
- `skills/engram-pain-mining/SKILL.md` for extracting buyer pain and usable language from public conversations
- `skills/engram-trend-radar/SKILL.md` for commercially relevant trend detection
- `skills/engram-ad-spy/SKILL.md` for competitor and category ad observation
- `skills/engram-offer-gap-research/SKILL.md` for wedge research and future offer discovery
- `skills/engram-roi-math/SKILL.md` for commercial math and avoided-waste framing
- `skills/engram-hook-lab/SKILL.md` for hooks, openings, reveal setups, and CTA variations
- `skills/engram-persona-stress-test/SKILL.md` for message stress-testing across buyer mindsets
- `skills/engram-brand-trust-audit/SKILL.md` for credibility and premium-positioning audits
- `skills/engram-design-language-lab/SKILL.md` for premium design-language research and visual direction across formats
- `skills/engram-client-experience-design/SKILL.md` for reports, onboarding, decks, proposals, and client-facing UX quality
- `skills/engram-case-study-forge/SKILL.md` for case studies, proof packaging, and sales collateral
- `skills/engram-tribe-interpreter/SKILL.md` only for internal R&D, stack interpretation, and technical setup

## Hard rules

- The live ICP is beauty and skincare DTC agencies first
- The live offer is a manual service first
- The live metric system has nine metrics only
- Public-facing work must not name internal models or overclaim outcomes
- Archived skills and docs are reference only and must not be treated as active instructions

## Operator assets

Use these non-Markdown assets for day-to-day operations:

- `assets/ops/intake_form_schema.yaml`
- `assets/ops/pipeline_template.csv`
- `assets/ops/lead_batch_001.csv`
- `assets/ops/audit_scorecard_template.csv`
- `assets/ops/benchmark_log_template.csv`
- `assets/ops/first_client_execution_checklist.txt`
- `assets/ops/reply_review_log.csv`
- `assets/ops/booking_setup.txt`
- `assets/ops/manual_payment_workaround.txt`
- `assets/agents/agent_registry.yaml`
- `assets/email/outreach_email_automation.yaml`
- `assets/ops/agent_handoff_protocol.txt`
- `assets/ops/agentic_loops.yaml`
- `assets/ops/skill_refinement_loop.txt`
- `assets/ops/token_efficiency_checklist.txt`
- `assets/research/skill_backlog.csv`
- `assets/strategy/business_review_scorecard.csv`
- `assets/strategy/change_review_log.csv`
- `assets/design/design_language_research.csv`
- `assets/design/artifact_design_backlog.csv`
- `assets/design/design_direction_brief.txt`
- `../client-facing/assets/sales/outreach_snippets.txt`
- `../client-facing/assets/sales/first_client_message_pack.txt`
- `../client-facing/assets/sales/discovery_call_script.txt`
- `../client-facing/assets/sales/objection_handling.txt`
- `../client-facing/assets/sales/loom_walkthrough_template.txt`
- `../client-facing/assets/email/client_emails.txt`
- `../client-facing/assets/email/outreach_email_sequences.txt`
- `../client-facing/assets/email/outreach_email_automation.yaml`
- `../client-facing/assets/contracts/*.txt`

## Audit status note

The report structure in this bundle is the current baseline. Final audit language should be updated once the new diagnostic report is supplied.

## Agentic execution note

Use `internal/ENGRAM_AGENTIC_EXECUTION.txt` with `skills/engram-agentic-workflows/SKILL.md` when the goal is to set up recurring research, outbound, proof, or skill-refinement loops.

Use `internal/ENGRAM_OVERSIGHT_AGENT.txt` with `skills/engram-business-overseer/SKILL.md` when the goal is to review the business model, assess recent changes, cut noise, rank leverage, and coordinate other ENGRAM agents.

Use `internal/ENGRAM_CORE_AGENTS.txt` with `skills/engram-execution-coordinator/SKILL.md`, `skills/engram-outbound-commander/SKILL.md`, and `skills/engram-proof-architect/SKILL.md` when the goal is to focus on the first-client jobs that matter right now: sequence discipline, outreach, and proof.

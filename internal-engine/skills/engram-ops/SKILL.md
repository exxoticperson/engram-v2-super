---
name: engram-ops
description: Run the operational workflow for ENGRAM from payment through debrief and benchmark logging. Use this skill for intake, turnaround, delivery, revision handling, and client communication standards.
---

# ENGRAM Operations

This skill governs the live operator workflow for each engagement.

## Intake

Preferred intake tools:

- Tally
- Typeform

Build the intake directly from `assets/ops/intake_form_schema.yaml`.

Required fields:

1. brand name
2. platform
3. category
4. campaign objective
5. target audience
6. ad file or public link
7. ad length
8. performance data if available
9. number of variants
10. analyst notes

Pre-production add-ons:

- script
- storyboard
- shot list
- creative brief
- shoot date if known

## SLA

Use this exact turnaround ladder:

- Pilot Audit: 48 hours
- Pre-Flight Audit: 72 hours
- Pre-Production Screen: 48 hours
- Rush: 24 hours with surcharge if offered

The clock starts when all required inputs are received.

## Live deliverable definition

Every client gets:

1. audit PDF
2. optional Loom walkthrough
3. live debrief call

## File naming

`ENGRAM_[BrandName]_[Platform]_[YYYYMMDD].pdf`

## Debrief structure

0 to 5 minutes:

- restate verdict
- restate composite score
- restate the single biggest issue

5 to 20 minutes:

- walk only the two or three most important findings
- explain what is happening, why it matters, and what to change

20 to 28 minutes:

- answer questions
- explain methodology in plain language only

28 to 30 minutes:

- confirm next step
- ask for implementation feedback later

## Revision policy

- one revision round included
- revisions requested within 5 business days
- clarification and updated framing allowed
- changing the score without new information is not a valid revision

## Required logging after every audit

- date
- category
- platform
- ad length
- input type
- confidence label
- metrics detected
- highest-severity issue
- composite score
- top repair recommendation
- implementation status
- performance after launch if shared
- client feedback

Use:

- `assets/ops/audit_scorecard_template.csv` for audit-level logging
- `assets/ops/benchmark_log_template.csv` for weekly category or trend notes
- `assets/ops/pipeline_template.csv` when client delivery status needs to be reflected in the sales flow
- `assets/ops/agent_handoff_protocol.txt` when work moves between research, outreach, audit, and proof packaging

## Communication rules

- respond quickly
- write clearly
- avoid corporate filler
- keep ownership language strong

## Failure handling

If late:

- notify before the deadline

If wrong:

- own it
- correct the affected section

If disputed:

- ask what evidence the client has
- update only if new information changes the analysis

If refund is owed:

- process it fast
- log the feedback

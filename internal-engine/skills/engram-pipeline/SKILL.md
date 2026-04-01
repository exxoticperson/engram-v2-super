---
name: engram-pipeline
description: Track ENGRAM leads from first sourcing through paid pilot and retainer conversion. Use this skill to manage stages, follow-ups, weekly reviews, and pipeline reporting.
---

# ENGRAM Pipeline

This is the lightweight CRM system for the live sales process.

Use `assets/ops/pipeline_template.csv` as the default working file.

## Stages

`SOURCED -> CONTACTED -> REPLIED -> CALLED -> CLOSED`

Additional statuses:

- COLD
- LOST
- RETAINER

## Stage definitions

- SOURCED: qualified lead not yet contacted
- CONTACTED: first message sent
- REPLIED: lead engaged
- CALLED: discovery call completed
- CLOSED: paid pilot confirmed
- COLD: no response after two follow-ups
- LOST: declined or disqualified
- RETAINER: converted to ongoing relationship

## Required lead fields

- ID
- first name
- last name
- title
- agency
- LinkedIn URL
- email
- category
- spend tier
- stage
- first contact date
- last contact date
- next follow-up date
- channel
- pain signal
- sample sent
- call booked
- call notes
- pilot offered
- pilot status
- notes

## Follow-up cadence

- Day 0: first outreach
- Day 5: first follow-up
- Day 10: second follow-up
- Day 14: mark COLD if still inactive
- Day 30: optional re-touch with new context

## Weekly review

Check:

- who advanced this week
- who needs follow-up now
- current reply rate
- current call rate
- current close rate
- how many new qualified leads were added

## Trigger rules

- after a call, send recap and next step within 24 hours
- after the second successful paid audit, pitch the retainer
- after a strong pilot, ask for one referral

For stage-aware email automation tied to pipeline changes, use `skills/engram-email-automation/SKILL.md`.

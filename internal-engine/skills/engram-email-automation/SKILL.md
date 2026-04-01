---
name: engram-email-automation
description: Build, refine, and operate ENGRAM outbound email sequences with personalization logic, send rules, stop conditions, and stage-aware follow-ups. Use this skill when the user wants cold email templates, automated follow-up logic, email workflows tied to lead stages, or an outreach sequence generated from research.
---

# ENGRAM Email Automation

Use this skill to turn ENGRAM outreach from one-off emails into a repeatable outbound engine.

## What this skill owns

- cold email sequences
- follow-up cadence
- personalization fields
- stop rules
- lead-stage triggers
- message variants by pain signal
- reply handling logic
- send-window guidance
- pipeline update rules

## Required inputs

- who the target is
- why they are qualified
- what pain signal triggered them
- what proof asset is available
- what next step should be asked for

## Default sequence

1. first-touch email
2. day-4 or day-5 follow-up
3. day-9 or day-10 follow-up
4. stop or recycle decision

## Message goals by step

- first-touch: earn permission to send the sample audit or book a call
- follow-up 1: restate relevance using one new angle
- follow-up 2: use a sharper proof or category observation

## Rules

- do not offer a free audit
- do not overexplain the stack
- keep each email easy to skim
- personalize with one real observation
- stop sequences after low-signal repetition
- tie every email to the next pipeline action
- use the sample audit as the proof asset by default
- keep the goal binary: reply, sample send, or call

## Reply handling

For positive replies:

- send the sample quickly or move to a call

For curious replies:

- answer briefly
- keep language concrete
- give one clean next step

For skeptical replies:

- reduce abstraction
- use one example of a hook or reveal failure
- restate the decision-support boundary without sounding defensive

## Assets

Use:

- `client-facing/assets/email/outreach_email_automation.yaml`
- `client-facing/assets/email/outreach_email_sequences.txt`
- `assets/ops/pipeline_template.csv`

## Output format

When building or refining a sequence, provide:

- sequence logic
- email drafts
- personalization fields
- send windows
- stop conditions
- pipeline update rule
- reply handling snippets

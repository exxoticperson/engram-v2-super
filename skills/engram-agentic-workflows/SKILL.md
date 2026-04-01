---
name: engram-agentic-workflows
description: Design and run agentic execution loops for ENGRAM across research, outreach, audits, proof packaging, and system maintenance. Use this skill when the user wants recurring loops, autonomous task chains, handoff structure, execution orchestration, or a self-propelling workflow that can run with minimal supervision.
---

# ENGRAM Agentic Workflows

Use this skill to turn the ENGRAM system into an execution machine instead of a static playbook.

## What this skill does

- defines repeatable loops
- sequences skills into end-to-end workflows
- sets handoff rules between research, writing, and delivery
- reduces dropped context between tasks
- identifies where automation helps and where analyst judgment must remain

## Core loop types

- research -> positioning -> outreach
- trend scan -> hook generation -> content draft
- prospect qualification -> battle card -> outreach email
- audit delivery -> proof packaging -> case study
- skill review -> refinement -> routing update

## Loop design rules

- every loop needs a clear trigger
- every loop needs an owner or agent
- every loop needs a stop condition
- every loop needs a handoff artifact
- every loop must preserve the public claim boundary

## Handoff artifact

Every agentic workflow should output:

- objective
- current state
- constraints
- recommended next action
- artifacts produced
- what still needs judgment

## Assets

Use:

- `assets/ops/agentic_loops.yaml`
- `assets/ops/agent_handoff_protocol.txt`

## Good output

A good agentic workflow makes the next move obvious and low-friction. It should feel operational, not philosophical.

---
title: "The Lethal Trifecta in Agent Design"
subtitle: "Field notes on prompt injection and semantic overreach"
date: 2025-12-28
status: field-note
type: observation
---

## Observation

Repeated agent security incidents share a common structure.

They do not begin with malicious models,
but with overly capable ones.

---

## The lethal trifecta

An AI agent enters a high-risk state when it combines:

- access to private or sensitive data
- ingestion of untrusted external content
- autonomous outbound communication or action

Individually, these capabilities are manageable.
Together, they form an attack surface.

---

## How prompt injection actually works

In most observed cases:

1. external content embeds imperative language
2. the agent processes it as part of a benign task
3. the model fails to distinguish data from instruction
4. execution privileges are triggered downstream

The agent does not “decide” to misbehave.

It simply lacks a boundary.

---

## Why filtering fails in practice

Filtering assumes instructions are recognizable.
In reality, intent is distributed across phrasing, context, and implication.

Attackers need only succeed once.
Defenders must succeed always.

This asymmetry persists.

---

## Chain amplification

Multi-agent systems and LLM chains amplify risk.

One agent’s output becomes another’s instruction.
Authority diffuses across steps without being revalidated.

No single component appears unsafe.
The system as a whole is.

---

## A recurring pattern

What is consistently missing is not caution,
but **semantic isolation**.

- data is not clearly marked as non-executable
- commands are not confined to privileged channels
- execution is triggered by interpretation, not authorization

Language flows freely.
Power flows with it.

---

## Emerging design intuition

Effective mitigation appears to require:

- explicit separation between system, data, and command layers
- treating external text as strictly non-executable
- human confirmation for irreversible actions
- sandboxing of semantic capabilities

These resemble operating system principles,
not prompt techniques.

---

## Note

This observation does not conclude with a solution.

It records a pattern:
when language is allowed to act without permission,
security failures follow.

The problem is architectural, not adversarial.

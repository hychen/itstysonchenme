---
title: "Field Note: Agent Operational Space (v0.1)"
date: 2025-12-28
draft: true
tags:
  - agent-native
  - research-notes
  - governance
  - systems
categories:
  - field-notes
---

## Context

This field note records an **early-stage observation**, not a conclusion.

The original motivation was simple but unsettling:

> Current LLM-based agents do not possess beliefs, commitments, or long-term self-constraint.
> As a result, expecting agents to "hold principles" internally is structurally unsound.

Rather than attempting to fix this at the model or alignment level, this work explores a different question:

**In what kinds of spaces can agents be allowed to operate, without requiring them to have beliefs at all?**

This note documents the emerging structure of that space.

---

## Working Assumption

- Agents are **probabilistic action generators**, not moral or institutional subjects.
- Principles cannot be safely embedded inside agents.
- Any durable principle must be enforced **externally**, as structure.

Therefore:

> This research does not study *how agents think*.
> It studies **where agents may act**.

---

## Agent Types (Operational Roles)

The following agent types are not personas or model variants.

They are **distinct permission bundles**:  
each agent is defined by what it is *allowed* to do — and more importantly, what it is *forbidden* from doing.

### 1. Exploration Agent

**Allowed**
- Generate alternative framings
- Expand hypothesis space
- Produce extreme or unconventional variants

**Forbidden**
- Final conclusions
- Value judgments
- Recommendations

**Function**
To stretch the problem space without collapsing it.

---

### 2. Adversarial Agent

**Allowed**
- Search for counterexamples
- Stress-test assumptions
- Deliberately misinterpret premises

**Forbidden**
- Proposing fixes
- Refining the original hypothesis

**Function**
To expose structural weak points and failure modes.

---

### 3. Consistency Agent

**Allowed**
- Detect internal contradictions
- Flag undefined terms
- Enforce vocabulary alignment

**Forbidden**
- Introducing new concepts
- Resolving contradictions

**Function**
To prevent premature coherence.

---

### 4. Reduction Agent

**Allowed**
- Attempt to decompose judgments into steps
- Identify non-decomposable segments
- Mark points requiring human authority

**Forbidden**
- Assuming decomposability
- Filling gaps with external heuristics

**Function**
To probe the limits of delegability.

---

### 5. Execution Simulator

**Allowed**
- Simulate execution paths
- Amplify error propagation
- Model cascading effects

**Forbidden**
- Rationalizing outcomes
- Assuming perfect compliance

**Function**
To surface systemic risk before deployment.

---

## Non-Agent Roles (Structural Components)

Agents alone are insufficient.

The following components are **structural**, not cognitive.

### Protocol

A protocol defines:
- Intent (what kind of action is being attempted)
- Allowed actions
- Forbidden actions
- Termination conditions
- Output constraints

Protocols constrain *behavior*, not *thought*.

---

### Gate / Validator

All agent outputs pass through a gate.

If an output violates protocol constraints:
- It is rejected
- The attempt is logged
- The agent must retry or terminate

Principles are enforced by **rejection**, not persuasion.

---

### Trace / Log

Every action produces an append-only trace:
- Agent type
- Protocol ID
- Input hash
- Output hash
- Human override (if any)

Research progress is measured by **where systems fail**, not by answers produced.

---

### Human Authority

Humans are not "smarter agents".

They hold exclusive rights to:
- Terminate a run
- Accept unresolved ambiguity
- Decide that something must *not* be formalized

This authority is intentionally non-delegable.

---

## Agent Operational Space (AOS)

The **Agent Operational Space** is defined as:

> The set of actions that agents may perform
> under explicit structural constraints,
> without assuming internal belief, alignment, or values.

This space is bounded by the following axes:

### 1. Reversibility
- Can the action be rolled back?
- Does it create irreversible external effects?

Irreversible actions require human authority.

---

### 2. Responsibility Localization
- Can responsibility be traced to a specific step?
- Can failure be replayed and examined?

Diffuse responsibility collapses the space.

---

### 3. Semantic Stability
- Are the meanings of terms stable?
- Or are boundaries still being defined?

Agents operate only *inside* stable semantic regions.

---

### 4. Value Ordering
- Are values already ordered?
- Or is prioritization still contested?

Agents may optimize, but must not rank values.

---

### 5. Stoppability
- Is "stop" a valid outcome?
- Can the system terminate without justification?

If stopping is not allowed, agents will rationalize.

---

## Non-Agentable Zones (Observed)

Some actions consistently resist agentization:

- Final go / no-go decisions
- Value trade-off resolutions
- Declaring something "out of scope"
- Accepting unresolved contradiction
- Defining agent boundaries themselves

These zones are not failures.
They are **structural invariants**.

---

## Current Status

- No fixed research question.
- No claim of completeness.
- This document functions as a **map-in-progress**.

The research proceeds by:
- Letting agents operate
- Observing where protocols break
- Recording where human authority is repeatedly invoked

Those invocation points are the data.

---

## Closing Note

This work assumes that:

> A system that requires agents to have beliefs is fragile.
> A system that constrains agents structurally may scale.

This field note captures the space between those two statements,
before conclusions are forced.

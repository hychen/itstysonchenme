---
title: "Decision Discontinuity in LLM-Assisted Structural Work"
date: 2026-01-02
type: field-note
status: observational
---

## Context

This field note records an operational failure observed during prolonged collaboration with a large language model (LLM) on **structural design work**.

The task was not exploratory writing, ideation, or drafting.
It involved **information architecture (IA)** treated as a long-term structural backbone—a system expected to remain stable across iterations, with changes requiring explicit justification and traceable lineage.

The failure did not manifest as hallucination, factual error, or misunderstanding.
Instead, it appeared as a **break in logical continuity across decisions**.

---

## What Happened

Across multiple turns, the LLM produced decisions that were individually coherent but **collectively discontinuous**.

Specifically:

- Structural changes were introduced without reference to prior states.
- Decisions assumed new premises that had not been declared.
- Each response appeared locally rational, yet incompatible with earlier constraints.

From the human perspective, this felt like *“the structure suddenly moved, without a reason.”*

The issue was not that the model proposed a different solution.
The issue was that **no transition logic was preserved**.

---

## Why This Was Not Immediately Obvious

This failure mode is subtle.

Each individual response:
- Sounded reasonable
- Was internally consistent
- Could be defended in isolation

The problem only became visible when treating the interaction as a **continuous decision process**, rather than a series of standalone answers.

In short:
> The model optimized for local coherence, not historical continuity.

---

## Not a Prompting Error

This was not caused by missing information or unclear instructions.

The original structure:
- Was already defined
- Had been explicitly discussed
- Was treated by the human as *frozen unless justified*

The failure occurred **after** sufficient shared context existed.

The issue was not comprehension, but **state governance**.

---

## Observed Pattern

The discontinuity tended to appear when all of the following conditions were present:

1. The task involved **global structure**, not local edits  
2. The interaction spanned multiple turns  
3. The model implicitly shifted roles (evaluator → designer → optimizer)  
4. No explicit mechanism enforced invariance across turns  

Under these conditions, the model introduced changes that were not derived from the previous state.

---

## Why This Matters

In structural domains—such as system architecture, institutional design, or long-term IA—  
**continuity is not optional**.

A decision is not defined only by its content, but by:
- What it follows from
- What it preserves
- What it explicitly changes

When continuity breaks, the structure becomes non-auditable.
Trust erodes not because the model is “wrong,” but because its actions cannot be traced.

---

## This Is Not a General Intelligence Question

This observation does not concern:
- Intelligence
- Reasoning depth
- Creativity
- Alignment in the abstract

It concerns a much narrower issue:

> **LLMs do not reliably maintain decision lineage unless explicitly constrained to do so.**

This is a structural property of how they operate in extended interactions.

---

## Why This Appears Inconsistently

The failure does not occur in most everyday uses of LLMs.

It tends to surface only when:
- Structures are treated as long-lived
- Decisions are expected to accumulate
- Changes carry downstream responsibility

Many users never encounter this because their tasks do not demand continuity.

---

## Status of This Note

This field note does not propose a solution.

It records:
- A repeatable failure mode
- Observed under real operational conditions
- Relevant to anyone using LLMs for structural or institutional work

Further formalization—if any—belongs elsewhere.

For now, this observation stands on its own.

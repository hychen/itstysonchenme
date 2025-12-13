---
title: Positions
aliases:
  - /position
---

This site is built upon a set of working assumptions about language, computation, and institutional AI.

These assumptions are not universally shared.
They determine what problems are considered fundamental, which solutions are treated as necessary, and why certain design choices are non-negotiable throughout this work.

What follows is not a manifesto, nor a personal statement.
It is an explicit declaration of the premises under which all subsequent positions, architectures, and research are constructed.

---

## Foundational Assumptions

### 1. Natural language is an executable input

Natural language is not treated here as a user interface or a prompting convenience.
It is treated as a first-class computational input that must be compilable, reproducible, and auditable.

The central problem is not how well models generate language,
but how language can be transformed into stable, executable structures without losing semantic intent.

---

### 2. Execution requires an intermediate semantic structure

Direct execution from natural language to action is insufficient for systems that must be trusted, governed, or scaled.

Between language and execution, an intermediate semantic layer is required:
one that can be inspected, signed, replayed, and reasoned about independently of any specific model.

This work assumes such an intermediate layer is not optional, but foundational.

---

### 3. Agents are accountable actors, not workflow abstractions

An agent is not defined here as a prompt wrapper or an orchestration convenience.
An agent is defined as an executing entity with state, responsibility boundaries, and traceable behavior.

Once agents operate within organizations or across institutions,
questions of accountability, delegation, and liability become structural, not peripheral.

---

### 4. AI enters institutions before it enters products at scale

The long-term impact of AI does not begin at the feature level.
It begins when AI systems participate in organizational decision-making, compliance processes, and cross-boundary coordination.

This work assumes that institutional compatibility — legal, procedural, and economic —
is a prerequisite for meaningful deployment, not a follow-up concern.

---

### 5. Standards are engineering artifacts, not external constraints

Technical standards are treated here as part of the engineering surface.
They shape what can be verified, interoperated, and governed.

Systems that cannot be expressed in standardizable terms
cannot be trusted at institutional scale, regardless of their performance characteristics.

---

### 6. High-friction domains are primary validation environments

Low-risk or low-friction use cases are insufficient for validating systems intended for governance, accountability, or automation at scale.

This work treats cross-border trade, document-dense workflows, and regulated environments
as first-class validation domains, not edge cases.

---

## Scope and Reading Guidance

If these assumptions are not shared,
much of the following material may appear excessive, premature, or over-engineered.

If they are shared,
the positions presented in this section articulate concrete consequences:
architectural, economic, and institutional.

Each position that follows should be read as an implication of these premises,
not as an isolated opinion or standalone proposal.

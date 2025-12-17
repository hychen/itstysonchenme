---
title: "Building Trust in Artificial Intelligence: Accountability and the Role of Reproducibility"
date: 2024-01-17
weight: 100
---

## Introduction

In recent discussions on artificial intelligence governance—particularly those emerging from public policy and academic forums—there is a recurring claim that certain aspects of AI systems are fundamentally *unexplainable*, and that society must simply learn to accept this fact.

But what does *unexplainable* actually imply in practice?

In many organizational contexts, especially within Taiwanese corporate culture, the absence of explanation is often resolved through informal substitutes: managerial apologies, symbolic accountability rituals, or interpersonal mediation. These mechanisms may restore social equilibrium, but they do not scale, nor do they constitute a reliable foundation for trust in AI systems.

As AI systems increasingly participate in consequential decision-making, the question of trust cannot be resolved at the level of explanation alone. This paper argues that **accountability, reversibility, and reproducibility**—rather than full interpretability—form the core engineering foundations of trustworthy AI.

---

## Accountability vs. Responsibility

Two terms are frequently conflated in AI discourse: **responsibility** and **accountability**.

- **Responsibility** refers to the obligation of system builders and operators to act with due care—ensuring that AI systems are developed, deployed, and maintained in a manner that is safe and socially beneficial.
- **Accountability** concerns what happens *when something goes wrong*: who can be identified, who must respond, and through what mechanisms remediation occurs.

While responsibility is continuous, accountability is event-driven. Importantly, there is no global consensus on how accountability in AI should be defined or enforced; interpretations vary by jurisdiction, institutional role, and legal framework.

Without clear accountability structures, calls for “explainable AI” risk becoming symbolic rather than operational.

---

## The Limits of Explainability

A commonly cited example comes from the U.S. credit scoring system operated by FICO. Credit scores influence life-altering decisions—loans, housing, employment—yet the explanations produced for these scores often fail to meet the interpretive needs of all stakeholders.

Efforts such as explainable AI competitions have revealed a deeper issue:  
explanations meaningful to machine learning researchers are often unintelligible or irrelevant to regulators, domain experts, or end users.

Explanation is not a universal artifact. It is audience-dependent, role-dependent, and context-dependent.

As a result, insisting on explainability as a universal requirement may not only be impractical, but counterproductive.

---

## Accepting Partial Unexplainability

Society already operates on trust without full explanation.

Most people drive cars without understanding internal combustion engines. When a car fails, trust is not maintained through explanation of thermodynamics, but through **support structures**: roadside assistance, repair networks, insurance, warranties, and liability regimes.

The trust resides in *recoverability*, not comprehension.

In contrast, AI systems often lack these visible remediation structures. When an algorithm fails, users perceive a void, not because the system is complex, but because responsibility pathways are unclear.

This asymmetry—not opacity itself—is what erodes trust.

---

## Reversibility as an Engineering Principle

**Reversibility** refers to the ability to undo, roll back, or remediate the effects of an AI system’s decision.

In software engineering, reversibility is a well-established practice: undo operations, version rollback, transactional guarantees. These mechanisms do not eliminate errors, but they make systems *governable*.

Applied to AI systems, reversibility allows:

- mitigation of harm,
- structured remediation,
- and meaningful accountability without requiring full interpretability.

Reversibility shifts the trust question from *“Why did this happen?”* to *“Can we recover from it?”*

---

## Why Reproducibility Matters

Reproducibility is a prerequisite for accountability.

If a system’s behavior cannot be reproduced under controlled conditions, then:

- failures cannot be investigated,
- responsibility cannot be assigned,
- and claims of compliance cannot be verified.

In AI product development, this manifests as the familiar problem:  
> “It works on my machine.”

To address this, industries have long relied on **golden samples**—reference artifacts that define acceptable behavior and quality. While AI outputs are probabilistic, the *conditions of execution* must remain traceable down to the smallest accountable unit.

Reproducibility anchors accountability to artifacts rather than intentions.

---

## Why Version Control and Containers Are Not Enough

Traditional version control systems (e.g., Git) track source code, but not the full execution environment.

Containers improve portability, but often fail to guarantee long-term reproducibility. Rebuilding the same container at different times may yield different binaries, dependencies, or runtime behavior.

For accountability, it is insufficient to know *what* code was used; we must also know *how* it was built, *with what*, and *under which constraints*.

---

## The Role—and Limits—of Nix

Tools such as **Nix** offer a promising approach by treating software environments as declarative, reproducible artifacts. This makes them attractive for reproducible research and trustworthy system construction.

However, Nix also presents adoption challenges:

- limited commercial ecosystem,
- steep learning curve,
- and a scarcity of experienced practitioners.

Despite these constraints, such tools point toward an important insight:  
**trustworthy AI requires infrastructure-level reproducibility**, not just model-level transparency.

---

## Regulatory Implications

As regulatory frameworks evolve—most notably the EU AI Act—expectations around accountability will increasingly materialize as *engineering requirements*, not ethical aspirations.

Fines, liability, and compliance verification will depend less on whether a model can explain itself, and more on whether its behavior can be audited, reproduced, and remediated.

Reproducibility thus becomes a strategic capability, not merely a research concern.

---

## Conclusion

Trustworthy AI cannot be built on explanation alone.

Instead, it rests on three interlocking foundations:

1. **Responsibility** — clear obligations in design and deployment  
2. **Accountability** — identifiable remediation pathways when failures occur  
3. **Reproducibility** — artifact-level traceability enabling investigation and recovery  

Among these, reproducibility is the operational keystone.  
Without it, accountability collapses into rhetoric.

As AI systems scale into infrastructure, reproducibility will determine not only technical reliability, but institutional trust.

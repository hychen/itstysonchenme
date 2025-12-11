---
title: Semantic DSL
status: stable
use_for:
- ai-systems
- runtime
- standards
summary: >
  Semantic DSL defines the structured intent layer that normalizes human
  or model-generated tasks into capability-constrained semantic programs,
  forming the authoritative source representation from which deterministic
  execution can be compiled.
type: concept
schema:
  type: Concept
  version: "0.1"
weight: 2
keywords: []
citations: []
---

## Definition

When intent is expressed directly in natural language, its structural ambiguity
prevents reliable compilation, capability checking, or reconstruction of meaning.
The absence of a formal intent layer results in fragile execution behavior and
non-attributable decisions.

**Semantic DSL** defines a structured form of intent that is:

- capability-aware,
- machine-interpretable,
- deterministically lowerable into Semantic ISA,
- reconstructable from execution traces.

Semantic DSL is not a prompt format and not a general-purpose programming language.
It is the **semantic program layer** that precedes execution and constrains how
intent becomes admissible for compilation.

## Role in the Execution Stack

Semantic DSL occupies the highest layer of the semantic execution hierarchy:

```
Semantic DSL → Semantic ISA → AgentIDL → Execution
```

Its role is to:

- normalize intent into structured semantic programs,
- enforce capability constraints defined by AgentIDL,
- ensure every admissible semantic term has a deterministic ISA mapping,
- preserve semantic meaning independently of the underlying model.

Without this structured layer, language-driven systems collapse intent and computation into an inseparable operation, preventing reliable auditing or comprehension.

## Motivation

As AI systems transition from suggestion engines to operational participants,
the primary failure modes arise not from incorrect content but from unstable or
ill-formed intent structures. Typical issues include:

- intent expressions that vary semantically across models or linguistic phrasing,
- inability to ensure consistency across repeated runs,
- ambiguity in determining whether an action aligns with declared capabilities,
- loss of semantic provenance once execution begins.

Semantic DSL resolves these issues by providing a **stable, capability-aligned
semantic surface** where intent can be validated, transformed, and compiled.

## Architectural Position

Semantic DSL serves a role analogous to a high-level programming model,
but grounded in semantic rather than syntactic constructs.

Its defining properties are:

- **Structure**  
  Intent is expressed in a normalized semantic form, not free text.

- **Capability Alignment**  
  Every DSL term must correspond to an admissible capability in AgentIDL.

- **Deterministic Lowerability**  
  DSL structures compile into unique Semantic ISA graphs.

- **Reconstructability**  
  DSL terms act as anchors that permit reverse interpretation from execution traces.

Semantic DSL does not replace natural language.  
It provides the **first point of semantic commitment** before compilation.

## Scope

Semantic DSL concerns:

- admissible forms of structured intent,
- validation of semantic programs against declared capabilities,
- preservation of intent meaning through lowering into execution layers,
- providing the human-aligned interpretive basis for post-execution reconstruction.

It does not concern itself with:

- surface syntax preferences,
- optimization strategies,
- runtime execution mechanics,
- vendor- or model-specific prompt conventions.

Those concerns belong elsewhere in the semantic execution stack.

## What This Work Is Not

Semantic DSL is not:

- a general-purpose programming language,
- a prompt template or instruction tuning format,
- a workflow engine or agent scripting scheme,
- a domain ontology or reasoning formalism.

Such systems may consume or produce Semantic DSL, but they do not define it.

## Relationship to AgentIDL and Semantic ISA

**AgentIDL** defines the space of admissible capabilities.  
**Semantic DSL** expresses intent *within* those boundaries.  
**Semantic ISA** provides deterministic execution semantics for DSL terms.

Their relationships are directional:

```
AgentIDL → Semantic DSL → Semantic ISA
```

AgentIDL constrains the DSL.  
The DSL compiles into ISA.  
ISA maps into execution substrates.

The layers are distinct and non-interchangeable.

## Status

This concept is considered stable.

Ongoing work focuses on DSL schema refinement, capability alignment rules,
and formal compilation mappings into Semantic ISA, rather than changes to
the architectural boundary defined here.

---
title: "An Architectural Critique of RAG and MCP"
weight: 4
---

Retrieval-Augmented Generation (RAG) and Model Context Protocols (MCP) are often presented as architectural advances for large language models.

This paper argues that they are not.

RAG and MCP are compensatory techniques that emerge from model-centric system design. They attempt to patch the absence of persistent semantic architecture by overloading the context window with responsibilities it was never designed to bear.

From a systems perspective, this represents regression engineering rather than architectural progress.

This paper critiques RAG and MCP as token-level compensations for missing semantics, and situates them against over a century of work in artificial intelligence and cognitive system design.

---

## The Core Misdiagnosis

The central assumption underlying RAG and MCP is that failures of reasoning and coherence stem from insufficient context.

The proposed remedy is to inject more tokens:
- retrieved documents
- external memories
- structured prompts
- extended context windows

This diagnosis is incorrect.

The fundamental limitation of model-centric systems is not the quantity of tokens available to the model, but the absence of a persistent, addressable, and governable semantic layer.

Injecting tokens into a transient context window does not create memory, meaning, or understanding. It merely conditions inference on a larger surface representation.

---

## Token-Level Processing Has No Intrinsic Semantics

Tokens do not carry meaning.

They are statistical surface representations derived from textual corpora, not semantic units grounded in concepts, reference, or intention.

No amount of retrieval, re-ranking, or in-context structuring can transform tokens into semantics. These operations remain conditioning mechanisms over symbol sequences rather than operations over meaning.

Systems that operate exclusively at the token level cannot:
- distinguish concept from description
- maintain identity across contexts
- reason over abstraction hierarchies
- assign responsibility or intent

These limitations are architectural, not parametric.

---

## Context Windows Are Not Cognitive Substrates

RAG and MCP treat the context window as a surrogate for:
- memory
- knowledge
- ontology
- execution trace
- reasoning substrate

This constitutes a clear violation of architectural layering.

A context window is a transient buffer optimized for short-term conditioning of inference. It is not a semantic address space, nor a substrate for long-term cognition.

Expanding a system’s context window in response to missing semantics is analogous to increasing CPU register size to compensate for the absence of a memory hierarchy.

The result is not intelligence, but temporary coherence under tightly controlled conditions.

---

## Regression Against the History of AI Systems

The design trajectory embodied by RAG and MCP represents a retreat from foundational insights established over the last 120 years of artificial intelligence and cognitive science.

These systems explicitly abandon:
- Frege’s distinction between sense and reference
- Peirce’s triadic model of sign, object, and interpretant
- Newell and Simon’s Physical Symbol System hypothesis
- Minsky’s Society of Mind
- Cognitive architectures with explicit memory and control (e.g., SOAR, ACT-R)

In their place, RAG and MCP substitute token co-occurrence conditioning as the primary mechanism of system behavior.

This is not progress; it is a deliberate collapse of semantic structure into statistical surface processing.

---

## Why RAG and MCP Appear to Work

RAG and MCP are effective in narrow contexts precisely because they avoid the hard problem of semantics.

They:
- enable rapid prototyping
- exploit existing textual corpora
- avoid explicit representation design
- deliver convincing demonstrations on constrained tasks

This short-term utility should not be confused with architectural viability.

The apparent success of RAG and MCP stems from structured use imposed by human operators, not from intrinsic system intelligence.

---

## Why They Fail Under Complexity

As task complexity, temporal scope, or governance requirements increase, RAG and MCP systems degrade systematically.

They exhibit:
- instability across contexts
- loss of identity over time
- poor abstraction handling
- brittle prompt dependence
- non-auditable behavior
- absence of responsibility attribution

These failures are not fixable through larger models, longer contexts, or better retrieval heuristics.

They arise from the absence of a semantic substrate outside the inference loop.

---

## Semantic Architecture Cannot Be Simulated In-Context

Semantic structure cannot be retrofitted through prompt engineering or retrieval pipelines.

Meaning requires:
- persistent representations
- symbolic reference
- explicit state
- separation of memory and computation
- governance mechanisms

When these elements are absent, all downstream techniques merely simulate structure rather than implement it.

RAG and MCP therefore function as emergency scaffolding, not as cognitive architecture.

---

## Reclassifying RAG and MCP

RAG and MCP should be understood not as intelligent architectures, but as compensatory interfaces over model-centric systems.

They serve to:
- mask semantic absence
- defer architectural commitments
- enable short-term usability

They do not constitute a path toward artificial intelligence capable of agency, meta-cognition, or governed evolution.

---

## Architectural Implications

The continued optimization of context windows, retrieval strategies, and prompt complexity reflects an industry-wide attempt to solve semantic problems at the token layer.

This strategy is structurally unsound.

Intelligent systems require semantic architectures that exist outside and prior to inference, within which models operate as replaceable reasoning components.

Until such architectures are adopted, techniques like RAG and MCP will remain transient workarounds rather than foundations for intelligence.

---

## Closing Statement

RAG and MCP do not represent the future of artificial intelligence.

They represent the cost of building intelligence atop models that were never designed to hold meaning.

Expanding context windows does not add memory.  
Retrieval does not create semantics.  
Conditioning is not cognition.

Architectural intelligence begins where token processing ends.

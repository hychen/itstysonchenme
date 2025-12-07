---
title: "AgentIDL"
---

## AgentIDL: Semantic Interface Layer

The Agent Interface Definition Language (AgentIDL) is key to achieving semantic interoperability across agents and systems. It provides a standardized way to describe an agent's semantic capabilities, its acceptable semantic commitments, and its behavioral patterns.

### Core Functions

*   **Capability Abstraction**: AgentIDL allows agents to declare which semantic concepts they can "understand" and "execute" without exposing their internal implementation details. For example, a payment agent might declare support for `urn:slashlife:payment:execute` semantics.
*   **Interface Standardization**: It provides a common communication contract for agents built by different developers and organizations. Systems can dynamically discover and understand another agent's semantic interface for secure interaction.
*   **Semantic Orchestration**: Based on AgentIDL, higher-level applications or orchestrators can arrange the semantic capabilities of multiple agents into complex workflows.

AgentIDL acts as the glue that connects independent semantic entities into an ordered, composable network.
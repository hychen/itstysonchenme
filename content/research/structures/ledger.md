---
title: "Semantic Ledger"
---

## Semantic Ledger: Traceable Mechanism for Order

The Semantic Ledger is the traceability and audibility mechanism for "Executable Semantic Order." It is a distributed, typically immutable, record-keeping system specifically designed to log key semantic events occurring within the network.

### Content of Records

Unlike traditional blockchains that record financial transactions, the Semantic Ledger records:

*   **Creation of Semantic Commitments**: When an agent publicly commits to a semantic contract, the commitment itself and its metadata (e.g., timestamp, committing party's identity) are recorded.
*   **Cross-Agent Semantic Interactions**: Key semantic interaction events between two or more agents, such as one agent issuing an `AgentIDL`-based semantic call to another.
*   **Results of Behavior Verification**: The outcome of verifying whether an agent's behavior aligns with its semantic commitments (whether success or failure) is recorded as trusted third-party proof.
*   **Attribution of Responsibility Events**: In case of errors or violations, the final attribution of responsibility is recorded.

### Core Value

The Semantic Ledger provides a shared, trusted "source of truth," enabling complex multi-party AI systems to collaborate without full mutual trust. In the event of issues, it offers clear, reliable traceability. It serves as the technical cornerstone for establishing AI accountability and compliance.
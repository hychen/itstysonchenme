---
title: "Verifiable Statements as Acceptance Tests in AI OEM Delivery"
date: 2023-07-18
type: field-note
tags:
  - OEM
  - AI governance
  - verifiable statements
  - DAO
  - model delivery
  - acceptance testing
---

### Observation

In traditional OEM and ODM processes, suppliers provide a *manifest* alongside delivered hardware or software.  
This document functions as evidence that contractual deliverables have been met and is later referenced in acceptance tests or disputes.

In AI model delivery, this role is weak or absent.  
Models are often delivered as opaque binaries, leaving the purchaser unable to verify provenance, training conditions, or behavioral claims.

This creates a structural asymmetry:  
the supplier knows what the model is, while the purchaser bears the operational and legal risk.

---

### Structural Reframing

The acceptance test can be reinterpreted as a **verifiable, executable statement** rather than static documentation.

In this framing:

- The release process is governed by an agent-like structure (e.g., a Model DAO).
- The acceptance condition becomes a **Verifiable Statement**, functionally equivalent to a traditional OEM manifest.
- The statement can be instantiated as a non-fungible, non-homogenized claim object (conceptually similar to an NFT, but without speculative intent).

This Verifiable Statement encodes:

- Training data lineage
- Training and evaluation procedures
- Expected operational behavior
- Reproducible inference environment
- Quality reports and operational constraints

---

### Operational Flow

1. **Supplier delivery**  
   The supplier delivers:
   - Full model source code (or auditable build artifacts)
   - A Verifiable Statement describing operational claims

2. **Purchaser verification**  
   The purchaser re-runs the model under the conditions described in the Verifiable Statement.

3. **Behavioral matching**  
   - If observed behavior matches the statement, acceptance proceeds.
   - If behavior diverges, the statement becomes evidence of misrepresentation.

4. **Economic commitment**  
   The Verifiable Statement is pledged with economic value (tokens, insurance premiums, or escrowed guarantees).

---

### Consequence Structure

This architecture introduces **consequence symmetry**:

- Suppliers gain incentives to deliver honestly.
- Purchasers gain verifiable grounds for acceptance or dispute.
- Legal recourse becomes grounded in reproducible technical evidence rather than interpretive claims.

In contrast to binary delivery, responsibility becomes traceable:
failure can be attributed to data, training process, or deployment conditions.

---

### Implication

This structure does not primarily aim at decentralization or automation.  
Its function is institutional:

- Making AI delivery auditable
- Making acceptance conditions explicit
- Making deception costly

In effect, the Verifiable Statement acts as a **machine-verifiable OEM manifest**, restoring contractual clarity in AI supply chains.

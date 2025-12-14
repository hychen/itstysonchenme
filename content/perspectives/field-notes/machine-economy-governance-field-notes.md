+++
title = "The Zero Marginal Cost Society*: A Personal Timeline and Three Cases（2015-2019）"
description = "A retrospective reflection on IoT, distributed production, collaborative commons, and early experiments in machine-to-machine governance between 2015-2019"
date = 2024-01-21
slug = "zero-marginal-cost-society-reflection"
categories = ["reflections"]
tags = [
  "iot",
  "sustainability",
  "machine-economy",
  "governance",
  "web3",
  "m2m"
]
+++

*This post reflects on a book published in 2015, revisited from the perspective of 2024.*

---

*The Zero Marginal Cost Society* (2015) presents a sweeping vision:

Humanity, in order to preserve a clean and sustainable planet, must transition from centralized production to distributed production. We must build highly efficient energy networks, logistics networks, and information networks (the internet), eliminate inefficient labor and unnecessary intermediaries, integrate production and consumption, and embrace open collaboration and shared resources. The goal is to maximize resource utilization, minimize environmental depletion, shift from ownership to access, and prioritize collective ecological well-being over private accumulation.

<!-- more -->

Despite its popular framing around the “Internet of Things,” the book is ultimately less about devices and more about **collaborative commons** and the **decline—or transformation—of traditional capitalism**.

---

## Commons, Scale, and the Limits of Self-Governance

The book references *Governing the Commons* (1990), which challenges Garrett Hardin’s famous *Tragedy of the Commons* by arguing that shared resources can be sustainably managed through collective self-governance and social norms such as shame.

What is less commonly discussed is that Hardin revisited the argument decades later.

In a lesser-known 1993 follow-up, he observed that self-governance mechanisms tend to break down beyond a certain scale. One cited example involved religious communal settlements:

> These colonies appear to function as unmanaged commons, but appearances are deceptive. Population size matters. Once the community exceeds roughly 150 members, individuals begin to under-contribute and over-consume. Below this threshold, shame-based governance remains effective; above it, its influence weakens.

This number—around 150—is now widely known as **Dunbar’s number**, proposed by anthropologist Robin Dunbar in 1996. It suggests a cognitive limit to the number of stable social relationships humans can maintain.

The implication is clear: **scaling commons requires more than goodwill**.

---

## 2015: IoT, Web Standards, and a Fork in the Road

When I first read the book in 2015, there was genuine optimism around the web-based evolution of IoT.

The W3C Web of Things (WoT) initiative aimed to address fragmentation in IoT by using open web standards. I was invited to participate in some early discussions, though I never became deeply involved.

At the same time, attention began shifting elsewhere—toward blockchain.

This was not the first time “Web3” had appeared. The term had already been used in 1998 by Tim Berners-Lee in the context of the Semantic Web. What emerged around 2015 was a second incarnation, and by 2022, a third—dominated by blockchain-based infrastructure such as IPFS and Arweave.

Berners-Lee himself was dissatisfied with this trajectory and later launched the Solid project to reclaim a different vision of the web.

---

## Embedded Systems, OTA, and Changing Assumptions

My closest hands-on exposure to IoT came not from theory, but from consumer hardware—most notably the Furbo pet camera.

In 2015, I argued that embedded systems development should learn from web practices: CI/CD, remote updates, continuous deployment. This idea was controversial at the time.

I even ran a survey among semiconductor and OEM professionals. The dominant response was:

> Embedded systems prioritize stability. Frequent updates are dangerous.

Today, over-the-air updates—exemplified by Tesla OTA—are taken for granted.

The world changed faster than expected.

---

## 2019: Sustainability, Governance, and M2M Economies

In August 2019, massive fires in the Amazon drew global attention. Conversations around Sustainable Development Governance (SDG) intensified, particularly among technologists exploring environmental applications.

That year, I spoke with Fang-Jui Chang, who had just moved from Taiwan’s PDIS to Dark Matter Labs in the UK. She described a UN-related project in Eastern Europe attempting to address corruption in environmental permit approvals.

The proposal was radical: eliminate human discretion where bribery occurs by directly linking environmental sensors to permit approval processes—**machine-to-machine governance**.

The term at the time was *M2M economy*.

---

## Three Case Snapshots

### 1. Blockchain-Based Permits

Rodolfo B. (2019) proposed storing permits and licenses on-chain, allowing stakeholders to verify approval status transparently.

The idea raised difficult questions:  
What does a blockchain-backed permit mean without state authority?  
And if state authority exists, why use a blockchain at all?

### 2. Decentralized Sustainability

David Dao’s 2018 essay explored satellite and aerial monitoring of forests and wildlife, combined with smart contracts acting as automated arbiters of environmental outcomes.

This work was speculative—but conceptually rich. It treated governance itself as a programmable system.

### 3. The Whale Carbon Plus Project

More recently, the Whale Carbon Plus project attempts to assign economic value to large whales by quantifying their contribution to carbon sequestration and ecosystem resilience, creating a financial market to incentivize conservation.

Whether one agrees with the approach or not, it illustrates how far the idea of **machine-mediated environmental governance** has progressed.

---

## Looking Forward

It is now 2024.

The phrase “Internet of Things” no longer carries the same excitement it did a decade ago. But the deeper questions raised in *The Zero Marginal Cost Society*—about distributed systems, shared resources, and post-human-scale governance—remain unresolved.

Whether the world described in the book will fully materialize is uncertain.

But the trajectory is still unfolding.

---

## Further Reading

- Rodolfo B. (2019), *Using Blockchain to Manage Permits & Licences*
- David Dao (2018), *Decentralized Sustainability*
- John Waldron (2021), *The Machine Economy Is Coming*
- The Whale Carbon Plus Project

## Notes for Future Research

This reflection leaves several questions unresolved. They are recorded here not as conclusions, but as markers for future inquiry.

### 1. Scaling Governance Beyond Human Cognitive Limits

The discussion around commons governance and Dunbar’s number raises a structural problem:  
human-centered governance mechanisms do not scale indefinitely.

A key research direction is whether **machine-mediated governance systems** can extend collective decision-making beyond human cognitive and social limits, without collapsing into rigid centralization or opaque automation.

This includes exploring:
- machine-enforced rulesets
- delegated decision authority
- non-human actors operating within institutional constraints

---

### 2. From Interoperability to Executable Semantics

Early efforts such as the Web of Things focused on interoperability but struggled to address governance and accountability.

A future research question is whether **semantic execution layers**—rather than mere data exchange—are required for distributed systems to participate meaningfully in institutional processes.

This suggests a shift from:
- data standards → executable commitments  
- interfaces → verifiable action structures

---

### 3. Continuous Update as a Governance Primitive

The historical resistance to OTA updates in embedded systems reflects a deeper assumption: that stability and governance are mutually exclusive.

This assumption may no longer hold.

Future research should examine **updatability, rollback, and auditability** as first-class governance primitives, especially in systems that make or influence decisions over time.

---

### 4. Machine-to-Machine Decision Chains and Legitimacy

Experiments linking environmental sensors directly to permit approvals raise unresolved questions of legitimacy.

If decisions are made by machines:
- Where does authority reside?
- How is responsibility assigned?
- What constitutes consent, appeal, or override?

This line of inquiry intersects with credential systems, delegated authority, and institutional accountability.

---

### 5. Authority, Not Just Infrastructure

Several blockchain-based proposals fail not for technical reasons, but because they conflate infrastructure with legitimacy.

Future work must distinguish clearly between:
- verification and authorization  
- transparency and authority  
- ledgers and institutions  

The central question is how authority can be **encoded, delegated, and audited**, rather than merely recorded.

---

### 6. Non-Human Actors as Institutional Participants

Projects that assign economic or regulatory roles to non-human entities (e.g. environmental systems, animals, or sensors) challenge existing assumptions about institutional membership.

This opens a research space around:
- representational agents
- delegated personhood
- responsibility without anthropomorphism

---

These notes are not intended to predict outcomes.

They exist to preserve unresolved tensions observed in the field—  
tensions that may only become tractable as tools, institutions, and conceptual frameworks mature.

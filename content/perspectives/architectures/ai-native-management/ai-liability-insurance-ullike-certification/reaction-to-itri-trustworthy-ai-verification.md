+++
title = "On ITRI’s Trustworthy AI Verification Framework"
date = 2023-05-19
slug = "itri-trustworthy-ai-verification"
categories = ["perspectives"]
tags = [
  "trustworthy-ai",
  "ai-governance",
  "verification",
  "liability",
  "human-in-the-loop"
]
+++

*This article reflects my assessment of Taiwan’s early attempts to institutionalize trustworthy AI verification, written in 2023, prior to the widespread deployment of large language models.*

---

In recent years, the Industrial Technology Research Institute (ITRI) in Taiwan has invested heavily in artificial intelligence infrastructure. One of its key initiatives is the development of a localized **Trustworthy AI Evaluation and Verification System**, aligned with international standards.

The framework emphasizes several core dimensions:

- **Understanding AI** (traceability, causal reasoning, and normative constraints)
- **Maintaining AI** (embedding ethical principles into model training)
- **Stabilizing AI** (continuous monitoring, detection, and corrective mechanisms)
- **Optimizing AI** (ongoing bias detection and performance improvement)

Below, I outline my perspective on each of these dimensions, and the structural challenges they reveal.

<!-- more -->

## Understanding AI: Traceability, Causality, and Norms

Interacting with AI systems is often compared to learning a new game: one must understand the rules and how actions lead to outcomes. In AI systems, this translates into understanding **how decisions are made**, and whether those decisions can be explained and constrained.

Explainable AI (XAI) techniques aim to make decision processes visible by exposing contributing factors. However, trust in explainability remains uneven, particularly in regulated industries.

As noted by Chang Chih-Hsing, CTO of E.SUN Bank:

> In the banking sector, it is common for people to distrust AI decisions simply because they cannot understand them. This mirrors the confusion many felt watching AlphaGo play—moves that appeared unintuitive to human experts. Building trust requires time, starting with helping regulators understand how AI decisions are made and how different decision paths compare. Objective evaluation and parallel verification are essential.

Explainability, however, is not a sufficient condition for trust. It is only one component of a broader verification structure.

---

## Maintaining AI: Ethics Embedded in Training

Training AI systems resembles education: we are not only imparting knowledge, but shaping behavior. Concepts such as **fairness-aware machine learning** attempt to mitigate bias and ensure equitable outcomes.

Yet, many ethical frameworks and fairness definitions originate in Western institutional contexts. Without sufficient input from Asian socio-cultural perspectives, these frameworks may encode implicit assumptions that do not generalize well.

Compounding this issue, generative AI accelerates us into a post-truth environment, where defining “ground truth” becomes increasingly unstable. Legal and geopolitical dynamics further complicate any static definition of fairness.

Even from a technical standpoint, fairness verification faces skepticism. Legal scholars, policymakers, and engineers often disagree on responsibility allocation between AI vendors and evaluation bodies.

Roman Yampolskiy has gone so far as to argue that fairness in machine learning may be fundamentally unattainable. His conclusion points toward an important insight: **regulation cannot be an external add-on**. Like regulators in communication theory, governance mechanisms must be embedded within the system itself to be effective.

---

## Stabilizing AI: Continuous Monitoring and Human Control

Stability mechanisms function much like parental supervision: continuous oversight ensures that unsafe behavior is detected and corrected early.

Monitoring tools can track AI behavior in real time, trigger alerts, and support periodic audits. However, the deeper challenge lies elsewhere: **how to preserve meaningful human control over AI decision-making**.

This concern is often discussed under the umbrella of *Human-in-the-Loop (HITL)* systems. While widely referenced, HITL requires substantial operational investment to be effective. Without clear authority boundaries and intervention protocols, human oversight risks becoming symbolic rather than functional.

---

## Optimizing AI: Metrics, Bias, and Iteration

AI systems require continuous evaluation. Accuracy, bias, efficiency, and robustness must be measured, compared, and improved iteratively.

Yet consensus on evaluation metrics is elusive. One possible path forward is to borrow from internet governance practices: multi-stakeholder governance models, deliberative processes, and design-based consensus-building.

Personally, I have explored the idea of **prediction markets** as a mechanism for collective expectation-setting around AI behavior—though this remains speculative.

---

## One Missing Layer: AI Product Insurance

Standards and verification alone are insufficient.

The original motivation behind *Trustable AI* was pragmatic: **when AI products cause harm, affected users must be compensated**. Certification exists not only to signal ethical intent, but to support liability allocation and economic accountability.

This framing differs significantly from the EU’s human-rights-driven Trustworthy AI discourse. The industries that emerge from these two approaches are fundamentally different.

While the dominant narratives at the time focused on Explainable AI, Responsible AI, and Beneficial AI, I believed Taiwan’s comparative advantage lay elsewhere—not in core AI infrastructure, but in the **trust delivery layer**: verification, testing, insurance, and deployment governance.

This is the final mile between AI systems and society—and an area where institutional design matters more than model performance.

---

## Further Reading

- Pomin Wu (2017), *Is Machine Learning Fair?*  
  https://www.bnext.com.tw/article/46864/ai-algorithmic-non-discrimination

- Pomin Wu (2017), *What Is Explainable AI and Why Does It Matter?*  
  https://medium.com/trustableai

- Roman Yampolskiy (2022), *On the Controllability of Artificial Intelligence*  
  https://www.researchgate.net/publication/360866412_On_the_Controllability_of_Artificial_Intelligence_An_Analysis_of_Limitations

- Central News Agency (Taiwan), *ITRI and the National Institute of Cyber Security Establish AI Evaluation Center*  
  https://www.cna.com.tw/news/ait/202307310125.aspx

- Wikipedia, *Human-in-the-loop*  
  https://en.wikipedia.org/wiki/Human-in-the-loop

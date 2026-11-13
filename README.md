# Infra Compass: Strategic Decision-Support Assistant (Anthropic Client Case)

A capstone project developed for **Foundations of AI in Business (FIIB)** designing **Infra Compass**—an evidence-grounded AI decision-support assistant built for Anthropic’s Chief Strategy Officer (CSO) and Enterprise Growth team.

## Business Problem & Context
Anthropic operates in a high-velocity frontier AI market shaped by heavy cloud-compute dependence (AWS and Google Cloud), intense API price/model rivalry, and evolving hardware export controls and AI governance standards. Because infrastructure, finance, and market intelligence data sit scattered across teams, strategy leaders lacked a single, standardized view of cloud-compute exposure.

## Structured 6-Stage Approach
1. **Problem Framing:** Defined SCQ parameters, scope boundaries, and human decision checkpoints so the assistant supports—never replaces—executive judgment.
2. **Evidence Base Construction:** Grounded the system in a **500-record Infrastructure Dataset** (compute utilization, GPU cluster allocation, hourly AWS vs. GCP cost rates, supplier concentration) alongside a **Capstone Evidence Register** (Stanford HAI compute reports, CNBC regulatory coverage, Tracxn competitor updates).
3. **Prototype Convergence:** Built four independent prototypes across the team and converged on a unified architecture combining strong governance/scope controls (Prototype C) with strict source verification (Prototype A) and structured trade-off comparisons (Prototype D).
4. **Adversarial Stress Testing:** Tested the assistant across **8 failure vectors**—including missing information, hallucination, human authority boundaries, out-of-scope tasks, privacy, conflicting data, instruction overrides, and overconfidence.
5. **Pilot Testing & Iteration:** Conducted independent user pilot testing; identified one speculative competitor launch prediction (`GPT-5` date) and resolved it in **Instruction Set v2** with strict grounding rules and concise-mode formatting.
6. **Risk & Control Framework:** Mapped 7 operational risks to concrete guardrails (approved-evidence restriction, dated evidence register, hard privacy boundaries, and executive escalation for capital/contract calls) and recommended a controlled **4-week CSO team pilot**.

## Repository File
* [Infra Compass Client Project Review & Pilot Testing Deck (.pdf)](./learning%20team%201%20anthropic%20chatbot%20ppt%20(1).pdf)

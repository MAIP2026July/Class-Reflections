# Reflection: Identifying AI Opportunities, Bounded Autonomy, and Human Fatigue Dynamics

**Session Date:** August 29, 2026
**Session Topic:** AI Opportunity Discovery, Sourcing Strategies (Build/Buy/Partner), UX for Probabilistic Systems, Human-in-the-Loop Fatigue, and Portfolio vs. Product Management

## Core Takeaways & Concepts

- **Don't Charge for the Word "AI":** If AI adds no value, it adds unnecessary overhead. Customers pay only for value (the double-bearing ceiling fan ad, when all fans already had it). Individuals and organizations get wiser, and brand damage follows.
- **Finish the Job and Leave:** Stickiness suits entertainment products, not workflow tools. The customer's goal is to complete the job and get out. Google's philosophy of no ads on its first page was cited.
- **Where AI Has High Opportunity:** Reducing friction, adding trust (AI can also subtract trust), reducing repeated effort, and reducing decision stress, which is among the most stressful activities (the satellite launch director example). Always ask for proof that AI is adding value.
- **ROI and Materiality:** Is the problem frequent and material enough to justify engineering and runtime cost? Sometimes a back-end database update is better than building a screen with access permissions. Feasibility depends on time, cost and answer quality *today*. The Moon/Mars gold analogy shows value that isn't feasible yet, but evolving tech may change that.
- **Pricing Economics:** Know your cost, what to charge, the value to customers, and what they will pay. Sometimes you fund learning if it is strategic.
- **Build vs. Buy vs. Partner:** Weigh vendor dependency (MySQL under Oracle's slower release cadence), data governance, and cost. Keep the moat capabilities owned. Standards and platforms (such as GTFS for transit data, ERP core with industry and geography packs) decide whether ecosystems scale.
- **The 4-Layer AI Product Stack:**
  - *Data Layer:* ingestion, embeddings, retrieval caches, ground truth.
  - *Model Layer:* classification, clustering, foundation SLMs/LLMs.
  - *API / Orchestration Layer:* decouples the app from the model so models can be swapped without rewriting business logic.
  - *UX Layer:* where confidence, uncertainty, and failure modes are communicated.
- **Designing UX for Uncertainty:** Deterministic UX assumes success or error. AI UX must show confidence, flag ungrounded inference, and offer fallbacks. A legal one-liner ("responses could be wrong") isn't enough because the PM must design for expectation calibration. Even answer length varies (short vs. a seven-page analysis).
- **PM Accountability for Economics:** The PM owns token cost, latency, and unit economics even when specialists supply numbers. Learn on the fly, gather quotes, and question them. People act in your name, like decisions in the President's name.
- **Don't Scale Before You've Tested:** Small samples (200 medical records) can't justify clinical claims. Novelty is mistaken for product-market fit, and repeat use vs. curiosity must be separated.
- **Fit to Real Segment (BPO example):** A team proposed scoring candidates by university rankings, dissertations, and papers, but the real target was BPO talent, who don't index on that. Match the model to the real talent pool.
- **PRDs and Strategy:** A one-page PRD misunderstands the effort needed. Strategy is a goal, not a decision. JTBD needs the stakeholder's progress, pain, anxiety, and uncertainty.
- **Prompts Are Product:** A prompt is an integral part of the product promise and customer experience. Smaller models (SLMs up to about 10B parameters) are an inexpensive basic option.
- **Product Owner vs. Portfolio Manager (Ramyatha's Sanofi case):** Clarify the role: a *purchase manager* procures tools for internal use, whereas an owner with P&L sells to others (including white-labeling). A portfolio manager must not jerk product managers week to week. Like the PM-to-engineering sprint contract, give a no-interference window (for example, three months between portfolio reviews). If you kill a product, reward the PM fairly, because it was the portfolio decision. Vendors are suppliers (Porter's forces).
- **The Psychology of HIL Fatigue:** Reviewers rubber-stamp confident AI. The fintech workaround: run human judgment and AI in parallel. If they align, auto-clear. If they diverge, the human justifies. Further HIL design choices:
  - Always-on, conditional, or never human review.
  - Escalation paths, time-outs (auto-progress after an hour), alerts (pager, WhatsApp), and re-routing.
  - Disclose stale or unreliable data to the decision-maker.
  - Record approvals, corrections, escalations, and evidence examined.
  - Weigh the reward for right vs. the penalty for wrong, and design responsibility (for example, a bonus withheld for 90 days after quitting if an incident traces to you).
  - Rajat added that humans are expected to match AI speed, which feeds fatigue. HIL can also be too costly in cost or time.
- **Exam Format Preview:** Two small cases, three sub-questions each, one page per sub-question (top to bottom, typed preferred, back side may be ignored). Questions may ask what type of AI problem it is (prediction, recommendation, generative).
- **Process Note:** Project topics are raised as GitHub issues in the instructions repo with team numbers (01, 02), first-come-first-served.

## Workplace Applicability & Contextual Translation

- **Eliminating Friction in Recruiter Workflows:** Recruiters abandon ATS tools with mandatory tagging, multi-screen navigation, and fragmented filtering. An AI screen that surfaces a high-confidence pool with outreach drafts lets a recruiter go from forty-five minutes to three.
- **Mitigating Screening Fatigue via Parallel Evaluation:** The recruiter records an independent quick score while the AI evaluates against the technical rubric. Mismatches are surfaced for review, preventing rubber-stamping and bias.
- **The Materiality Filter for Hiring Automations:** Don't spend sprints automating edge-case workflows that run twice a year (rare subsidiary-transfer onboarding). High-frequency pain (interview scheduling, immigration status verification) justifies AI triage.
- **The BPO / Recruitment Fit Disconnect:** Audit whether our filtering models reflect the actual talent pool, not an academic ideal.
- **Vendors and Portfolio Thinking:** Our HR tech stack mixes internal and vendor tools. Clarify who owns outcomes (procurement vs. P&L), and give owners stable planning windows rather than weekly changes.

# Class 5 Reflections

**Date:** 29 August 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Build vs Buy Rigor:** Building custom models in-house is rarely justified unless the problem space involves proprietary regulatory data, strict latency boundaries, or core domain differentiation. For most product layers, leveraging mature APIs is significantly cheaper and faster to market.
* **Total Cost of Ownership (TCO):** The purchase cost of an API or compute cluster is just the tip of the iceberg. Ongoing monitoring, prompt maintenance, evaluation harness updates, and vendor security compliance constitute the real operational cost.
* **Human-in-the-Loop (HITL) Review Fatigue:** Relying on human reviewers to catch rare AI errors quickly leads to cognitive exhaustion. Reviewers become desensitized and start approving outputs mechanically, creating a false sense of security.
* **Materiality Filtering:** The system should only route high-risk, ambiguous, or high-value decisions to human review, using deterministic rules to handle low-risk repetitive tasks.

---

### 2. What Resonated Most With Me
The deep dive into review fatigue was an eye-opener. It is very easy for PMs to write *"a human will review all flagged outputs before delivery"* into a PRD as a quick safety net. But as Professor Vinaya demonstrated, when a reviewer has to look at 200 outputs where 99% are fine, their attention drops sharply and they will inevitably miss the one critical hallucination.

This insight showed me that human oversight cannot be a lazy catch-all. If we want human review to be effective, our system must do the heavy lifting upfront—clustering similar outputs, highlighting exact diffs, and surfacing only genuine anomalies. This applies directly to our AI Twin, where asking the user to review every draft email creates as much work as writing the email from scratch.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* It would be very useful to study how leading enterprise software vendors calculate TCO across multi-year contracts when foundation model pricing drops every six months. A practical framework for negotiating SLA and deprecation terms with LLM vendors would be great.

---

### 4. Personal Action Item
Re-evaluate our team's AI Twin architecture to ensure we are not over-engineering custom pipelines where managed commercial APIs or lightweight open-source models would deliver 95% of the performance at a fraction of the maintenance burden.

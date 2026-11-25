# Class 9 Reflections

**Date:** 10 October 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Business Metrics vs Benchmark Scores:** A 3% improvement in an academic benchmark like MMLU or perplexity is meaningless to executive stakeholders. PMs must translate technical gains into business metrics: customer retention, reduced support turnaround time, and operational cost savings.
* **The "Guitar on the Motorcycle" Anti-Pattern:** Adding complex AI components to simple products just because the technology is trendy adds unnecessary cost, latency, and failure points without improving the user experience.
* **Managing Tail-Risk Vulnerabilities:** In probabilistic systems, average performance can be deceptive. A product that performs well 98% of the time can still create catastrophic legal, privacy, or financial risk in the remaining 2% if guardrails are absent.
* **Continuous Monitoring in the Wild:** Unlike traditional software where code stays static once compiled, AI products drift over time as user behavior changes and model providers update API behaviors silently.

---

### 2. What Resonated Most With Me
The visual of the "guitar on a motorcycle"—adding an unnecessary generative AI feature to a workflow that worked perfectly well with simple drop-down menus or keyword filters—was one of the funniest and most memorable lessons of the course. It captures the exact mistake so many companies are making right now in the rush to slap "AI" onto everything.

Professor Vinaya's point about bridging the language barrier between data scientists and business executives also hit home. Data scientists naturally want to discuss parameter sizes, loss curves, and benchmark leaderboards. But our job as product managers is to stand firmly on the business side and ask: *"Will this model update reduce our error rate in draft generation, and does it justify a 20% increase in our API bill?"* Being able to translate back and forth is what makes an AI PM indispensable.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* A brief session on drafting enterprise AI SLA agreements—specifically how to define uptime, accuracy thresholds, and latency guarantees when third-party cloud models are involved—would be an invaluable business asset.

---

### 4. Personal Action Item
Audit our AI Twin feature backlog and ruthlessly trim any proposed features that can be solved more reliably with deterministic logic or simple UI patterns rather than expensive generative API calls.

# Class 5 Reflections

**Date:** 29 August 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Build vs Buy vs Partner:** You rarely need to train or own the base model. Your true proprietary asset is the domain-specific judgment layer, data feedback loops, and integration into existing customer systems.
* **The Materiality Filter:** Not all model errors carry equal weight. A product manager must categorize errors by business impact and concentrate guardrails on high-severity failure modes.
* **Designing Real Human-in-the-Loop (HITL):** HITL cannot just be an operational band-aid or a marketing claim. If the review interface is clunky or causes fatigue, users will simply rubber-stamp outputs without looking.
* **Total Cost of Ownership (TCO):** Token fees are just the tip of the iceberg; evaluation pipelines, latency mitigation, retrieval infrastructure, customer support, and retraining represent the true long-term costs.

---

### 2. What Resonated Most With Me
Professor Vinaya's practical skepticism toward the hype that "new foundation models will wipe out all software overnight" was refreshing. Models are commodities; workflow integration and domain contextualization are defensible.

The concept of the **materiality filter** was especially relevant to our capstone discussions. In an enterprise assistant, getting a date format wrong is a nuisance; getting a financial balance or compliance classification wrong can trigger legal action. Designing differentiated validation pipelines based on error materiality is how you balance user experience with safety.

I also appreciated the emphasis on **review fatigue**. If an AI copilot flags 100 alerts a day and 80 are false positives, the human reviewer quickly tunes out. High precision on critical alerts beats high recall with noise every single time.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The build vs buy framework was very sharp. A mini-case study comparing the financial trade-offs of fine-tuning an open-source model (e.g., Llama) versus prompting an enterprise commercial model (e.g., Claude or GPT-4) across different query volumes would add tremendous practical value.

---

### 4. Personal Action Item
Map out the error taxonomy for our capstone project, clearly distinguishing between low-impact cosmetic errors and high-impact material errors, along with the automated checks required for each.

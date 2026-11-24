# Class 7 Reflections

**Date:** 12 September 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Value-Based Pricing vs Cost-Plus:** Pricing an AI product should be pegged to the measurable economic value created for the buyer, never simply to the cost of underlying tokens and compute.
* **AI Unit Economics & Margin Compression:** Unlike traditional SaaS where marginal serving costs approach zero, every generative AI query incurs variable compute costs. If query complexity scales faster than subscription fees, margins collapse.
* **AI Supply Chain Risk:** Relying heavily on external foundation model APIs introduces external dependencies—pricing changes, rate limits, latency spikes, or sudden policy shifts directly impact your product's SLA.
* **User Silence is Often Churn:** In AI products, a customer who stops complaining or submitting queries hasn't become satisfied; they have likely lost trust and silently moved on.

---

### 2. What Resonated Most With Me
Today's deep dive into **AI unit economics** was one of the most practical sessions of the semester. In traditional SaaS, product managers can afford to be somewhat casual about compute usage because serving an extra page or record costs fractions of a cent. With LLMs, uncontrolled context windows, repeated re-prompting, and heavy agent loops can turn a profitable customer into a loss-making account overnight.

The discussion on **supply chain vulnerability** was equally sobering. If an external API provider decides to adjust their content filtering or deprecate a specific model checkpoint, an enterprise product built on top can break without warning. This reinforced why caching, semantic routers, and fallbacks are essential product architecture requirements, not just technical preferences.

The insight that **silence signals churn** also hit home. When an AI tool produces poor results, users rarely file detailed bug tickets; they simply stop trusting the output and revert to their manual spreadsheet or old workflow.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* It would be fantastic to have a hands-on modeling spreadsheet during this class where we input token costs, latency SLA targets, and user query volumes to calculate gross margin break-even points under different pricing tiers (e.g., seat-based vs consumption-based vs outcome-based).

---

### 4. Personal Action Item
Build a rigorous cost-per-task model for our capstone deliverables, ensuring that our proposed business model remains financially viable even if token usage doubles under edge-case workloads.

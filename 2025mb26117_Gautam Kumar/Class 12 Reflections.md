# Class 12 Reflections

**Date:** 31 October 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Target Costing (Working Backwards):** Rather than traditional cost-plus pricing (calculating what it costs us to build and adding a margin), AI product managers must adopt the Japanese target costing philosophy: determine the customer's perceived value and willingness to pay first, subtract target profit margin, and work backwards to establish the maximum permissible build and inference cost.
* **Eliminating Contractual Ambiguity:** A product specification is effectively a contract with engineering or external vendors. Vague qualitative adjectives like "accurate", "user-friendly", or "reduced consultation time" create massive contractual risk and rework. Every requirement must be anchored to concrete, measurable numbers (e.g., "30% reduction in clinician consultation time", specific suppression rates for unsafe outputs).
* **Diagrams-as-Code & Workflow Swimlanes:** Workflows should be represented using diagrams-as-code (PlantUML or Mermaid) rather than static image exports. Swimlane diagrams must explicitly categorize each step into deterministic rules, probabilistic LLM inference, and human-in-the-loop oversight points, complete with token cost and latency estimates.
* **Agentic Loop Guardrails & Unit Economics:** With agentic AI and RAG systems, poor loop design can cause runaway API calls where tokens burn infinitely without reaching the goal. Systems must enforce strict maximum loop counts, fallback triggers, and transparent pricing policies when an agent fails to achieve its target.

---

### 2. What Resonated Most With Me
Today's session was one of the most interactive and practically grounding classes of the semester. Having our cohort review Team 002's project documentation live on screen gave all of us immediate clarity on what Professor Vinaya expects from an enterprise-grade AI submission.

The discussion on **unambiguous specification** hit home. Professor Vinaya's story about early software tools in the 1990s that scanned requirement docs specifically to flag subjective words like "beautiful UI" or "accurate results" was eye-opening. What is "user-friendly" or "accurate" to one engineer or vendor is completely different to a customer or legal auditor. As PMs, leaving things to the imagination of developers is an abdication of ownership. Putting numbers on the table—even initial estimates—forces alignment.

I was also deeply engaged during the conversation on **presentation timing and submission deadlines**. Coordinating the GitHub access across the cohort has given me a firsthand look at how easy it is for teams to get caught in "student syndrome" and defer deliverables until the final hours. Professor Vinaya's decision to institute a strict 24–48 hour GitHub freeze before evaluations was very sensible—you cannot evaluate a moving target when commits are landing every hour.

The deep dive into **outcome-based pricing versus input-based billing** also mirrored our team's AI Twin discussions. Customers do not care how many tokens or GPU seconds your model burned; they care about the business outcome achieved. If an AI hallucinates or loops, forcing the customer to pay for those wasted tokens destroys trust immediately. Finding the sweet spot where we take calculated outcome risk while capping downside with guardrails is the real art of AI product management.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The walkthrough of **PlantUML and the C4 Model** (system context and container diagrams) was incredibly useful. For many non-technical PMs in the class, seeing textual diagramming was a lightbulb moment. In future cohorts, having a 20-minute live workshop in earlier weeks where every team drafts a basic PlantUML swimlane with deterministic vs probabilistic tags would help teams avoid messy PDF flowcharts from day one.

---

### 4. Personal Action Item
Audit our AI Twin master deliverables and capstone documentation against today's guidelines:
1. Replace any remaining subjective phrases with concrete percentage targets and thresholds.
2. Ensure our PlantUML swimlanes clearly mark which agent interactions are deterministic guardrails versus probabilistic LLM completions.
3. Verify that our prompt logs and token cost projections are fully documented in our repository.

# Session 4 Reflection

**Date:** 22 August 2026  
**Topic:** AI Appropriateness, Tail Risk, Actionable Windows & Human-in-the-Loop  

The central question from today's session was moving from *"Can AI do this?"* to **"Should AI do this?"** Just because a problem *can* be solved using a model doesn't mean AI earns a place in the product. The starting point must always be the hypothesis of incremental value, balanced against the downside cost of an incorrect output.

**Key takeaways & thoughts:**

* **The 4-Step AI Appropriateness Ladder:** Always start with the simplest solution and only move up when necessary:
  1. *Deterministic Rules/Checklists*
  2. *Analytics & Search*
  3. *Predictive ML*
  4. *Generative or Agentic AI*  
  If a problem can be solved with simple business logic or structured rules, deploying an expensive, probabilistic LLM is just over-engineering.
* **Accuracy vs. The Actionable Window:** Accuracy alone doesn't create product value if the output arrives too late to act on. The agricultural advisory example (alerting a farmer about torrential rain after the crop is already ruined) proved that timing, latency, and operational context matter just as much as model precision.
* **Tail Risk Over Average Performance:** Evaluating an AI product purely on average accuracy can mask severe edge-case failures. In high-stakes domains, a 99% accuracy rate is meaningless if that 1% tail-risk failure causes catastrophic financial or operational damage. Guardrails, fallbacks, and escalation paths are core product features, not afterthoughts.
* **The "Rubber Stamp" Human-in-the-Loop:** Keeping a human in the loop is essential when accountability matters, but it brings its own design challenge: automation bias. If the workflow isn't designed properly, humans quickly fall into blindly approving whatever the AI recommends, defeating the entire purpose of oversight.
* **Adoption as a Product Design Problem:** High value doesn't automatically guarantee user adoption. If an AI feature alters an existing operational workflow, the friction, training, and switching costs become part of the product design challenge itself.

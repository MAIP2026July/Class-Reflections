# Class 8 Reflections

**Date:** 03 October 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **The Demo Trap:** A demo that works flawlessly with cherry-picked examples is easy to build in a weekend. An enterprise-grade AI product must perform consistently across noisy, adversarial, and poorly formatted real-world user inputs.
* **Stage-Gate Discipline:** Moving an AI project from proof-of-concept to production requires formal stage-gates based on objective regression tests, latency budgets, and safety benchmarks—not executive excitement over a slick presentation.
* **Model Agnostic Abstraction:** Building an abstraction layer between the application logic and specific LLM APIs ensures that the engineering team can switch backend providers without having to rewrite prompt pipelines or UI code.
* **Deterministic Fallback Mechanisms:** When probabilistic components fail or return unparseable structured outputs, the system must immediately fall back to rule-based defaults rather than crashing the user workflow.

---

### 2. What Resonated Most With Me
Professor Vinaya's contrast between "demo magic" and "production reliability" was spot on. In almost every AI meetup or demo day, you see impressive prototypes that produce stunning results on standard prompts. But the moment you test them with ambiguous instructions, unusual formatting, or edge cases, the system breaks down.

For our capstone project, this session reinforced the need for rigorous regression testing. Having an automated test suite that runs 50 realistic edge-case inputs against our AI Twin every time we update our system prompt is worth ten times more than adding another flashy feature. If our product is supposed to represent a user in business communications, even a 2% failure rate where the model sounds inappropriate or misunderstands context will destroy user trust permanently.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* It would be very helpful to review practical open-source evaluation tools (like promptfoo, Ragas, or Deepeval) with a short walkthrough on how PMs can review evaluation reports without needing deep coding expertise.

---

### 4. Personal Action Item
Create a dedicated "red team / edge case" test dataset of 25 tricky communication scenarios (e.g., conflicting calendar invites, urgent escalations with vague details) to stress-test our AI Twin persona logic.

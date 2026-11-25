# Class 10 Reflections

**Date:** 17 October 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Products as Promises:** Every product UI makes an implicit promise to the customer. When an AI product overpromises by claiming to be "fully autonomous" or "human-like," it sets an impossibly high standard where minor errors feel like catastrophic betrayals.
* **Graceful Degradation:** When an AI component encounters high latency, token limit exhaustion, or low confidence, the interface must gracefully scale down to a simpler, reliable alternative rather than showing a spinning wheel or a broken layout.
* **Managing Cognitive Load:** Giving users too many options to tweak (temperature sliders, model selectors, system prompt overrides) confuses non-technical users. The PM should hide internal complexity behind sensible, pre-tested defaults.
* **Communicating Confidence Transparently:** When the model is uncertain about a recommendation, the UI should explicitly signal that uncertainty to prompt the user to double-check the facts.

---

### 2. What Resonated Most With Me
Today's focus on expectation management and UI design was deeply relevant. When users try a new AI tool with sky-high expectations created by marketing hype, their first reaction to an imperfection is disappointment. But when the product is honest upfront about what it can and cannot do, users are far more forgiving and willing to work with the tool constructively.

For our AI Twin, this means our onboarding and micro-copy must be carefully crafted. Instead of promising that the Twin will *"handle your entire inbox autonomously,"* we should promise that it will *"draft well-researched responses for your review and flag your top three urgent priorities."* By setting clear expectations, the user feels in control, their cognitive load is reduced, and trust grows steadily over time.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* Looking at UI/UX design patterns from leading human-AI interaction guidelines (such as Microsoft's HAX toolkit or Google's PAIR guidelines) with practical before-and-after examples would be a great addition to this lecture.

---

### 4. Personal Action Item
Review all user-facing micro-copy and prompt placeholders across our AI Twin prototype to ensure we clearly communicate the boundary between automated suggestions and user sign-off.

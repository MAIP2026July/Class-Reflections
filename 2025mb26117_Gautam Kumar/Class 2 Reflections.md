# Class 2 Reflections

**Date:** 01 August 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Lifecycle Reality Check:** Launching a beta is not the finish line; it is barely the midpoint of the product journey. Real learning starts when users hit edge cases in production.
* **Evidence vs Product Intuition:** Strong PMs know when to rely on hard user data and when to trust qualitative intuition. When building brand-new AI paradigms, historical data is often sparse, so small experiments must precede big bets.
* **The Power of Deferring Decisions:** Not every technical choice needs to be locked in on day one. Keeping architectural options open until critical uncertainties clear up saves expensive rework.
* **Layering & Modularity:** Decoupling the user experience layer, application logic, and underlying model layer ensures that when a foundation model changes, the entire product doesn't collapse.

---

### 2. What Resonated Most With Me
The discussion around **spending someone else's money** was a great reality check. When you work inside large organizations, it is easy to treat cloud credits or developer hours as abstract resources. Professor Vinaya's emphasis on fiscal responsibility and traceability changes how you evaluate tradeoffs.

I also really liked the discussion on the **layering model**. In enterprise AI, foundation models get updated or deprecated constantly. If you tightly couple your business workflows to a specific model endpoint or prompt structure, maintenance becomes a nightmare. Designing an intermediate judgment and routing layer gives the product resilience.

Another highlight was the discussion on **influence without authority**. Since engineering, design, and legal teams don't report to the PM, building trust through transparent reasoning and shared artifacts is our primary currency.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The breakdown of product lifecycle stages was very clear. It would be helpful to see a sample template or rubric of what a real "gate review" looks like between alpha and beta in an AI-native company—specifically, what error threshold or user trust score must be hit before opening the doors wider.

---

### 4. Personal Action Item
For our team project, I will establish a simple decision log that captures not just what technical choices we made, but *why* we made them and what assumptions would trigger a revisit.

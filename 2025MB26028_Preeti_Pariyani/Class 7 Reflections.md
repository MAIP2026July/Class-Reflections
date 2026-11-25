# Class 7 Reflections

**Date:** 12 September 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Unit Economics and Margin Fragility:** In traditional SaaS, the marginal cost of serving an additional user is near zero. In AI products, every query incurs GPU inference costs. If pricing is not tied to value or usage boundaries, increased user adoption can quickly erode gross margins.
* **Predictable Billing vs Token Volatility:** Enterprise B2B customers despise unpredictable month-end bills. Passing raw token costs directly to enterprise finance teams leads to budget rejection; pricing must be packaged into predictable tiers with sensible usage quotas.
* **Supply Chain Fragility in GenAI:** Relying on a single third-party model vendor exposes the product to severe operational risks—including sudden rate limiting, model deprecation, and unexpected latency surges.
* **Combating Silent Churn:** When users quietly stop relying on an AI feature due to minor inaccuracies, they rarely file support tickets. Tracking behavioral drop-offs is vital to catch disengagement early.

---

### 2. What Resonated Most With Me
Today's deep dive into monetization and unit economics was a much-needed reality check. It is very easy during product design to focus purely on features and user delight while ignoring what happens when thousands of users start firing complex multi-step prompts. 

Professor Vinaya highlighted how many AI startups have raised capital with impressive top-line growth, only to discover that their gross margins are under 30% because of heavy third-party inference costs. For our AI Twin product, this means we cannot simply offer unlimited queries on a flat monthly fee without building strict token budgeting and caching mechanisms under the hood. Structuring tiers based on business value (e.g., number of high-stakes summaries generated) makes far more sense than billing by tokens.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* A hands-on financial modeling exercise where teams calculate expected gross margins under different model latency, caching rates, and fallback scenarios would be an incredible addition to this class.

---

### 4. Personal Action Item
Build a spreadsheet model for our AI Twin that calculates our per-user monthly inference cost across light, medium, and power-user scenarios, factoring in prompt caching and fallback logic.

# Reflection: Session 4

**22 August 2026 | Usha Talatala | 2025MB26177**


---

### The story that landed

* **AI Appropriateness & Least Complex Tools:** Always choose the simplest tool that gets the job done—starting with deterministic rules, then analytics/search, then predictive ML, before jumping to Generative AI or Agentic workflows. For Chase Offers+, deterministic rules or search indexers are often cheaper, faster, and more reliable for filtering valid merchant deals than running heavy LLM inference calls for every page load.
* **Actionable Time Windows:** Insights or alerts must be delivered within an actionable time frame. On the Chase Offers+ web platform, presenting a personalized cash-back deal after a customer has already completed a transaction is useless; the offer must render instantly at decision time.
* **Disruption and Reluctance Costs:** Customers don't resist change just to be difficult; they resist because of switching costs and disruption to their habitual workflows. Any UI redesign for Chase Offers+ must minimize cognitive friction so cardholders can activate offers in a single click without learning a new interface.
* **Tail Risks & 0-Harm Boundaries:** In financial apps, average success rates don't tell the whole story; tail risks matter. Showing an incorrect or expired offer terms modal could lead to customer disputes, regulatory fines, and reputational damage. Guardrails must handle worst-case failures gracefully.
* **Pre-AI vs. Post-AI Baselines:** Before claiming an AI model adds value to offer recommendations, we must measure performance against pre-AI baselines (e.g., static category-based offer sorting).

### Where I disagree

The professor advocated starting with the simplest deterministic rules before considering AI. However, in modern web personalizations at scale, static rule engines become unmaintainable when handling millions of cardholders with thousands of real-time merchant offers. Starting directly with lightweight predictive ML models is often cleaner than building complex `if-else` decision trees.

### What I will do

* **Enforce Pre-AI vs. Post-AI Benchmarks:** For any new smart offer sorting algorithm on the web app, my team will establish a clear baseline against simple rule-based sorting to prove real conversion lift.
* **Optimize Web Latency & Actionability:** I will work with back-end engineers to ensure offer recommendation payloads return within sub-100ms thresholds so web rendering is never delayed.
* **Design Fail-Safe Fallbacks:** I will implement deterministic fallback UI components in our micro-frontends so that if predictive offer services fail, users still see high-value default merchant offers without breaking page rendering.

### Open questions

1. How do we best structure user feedback loops on the web UI (e.g., "Hide this offer") to retrain recommendation models without degrading web performance?
2. How do we navigate the balance between personalized AI targeting and customer data privacy regulations (e.g., CCPA/GDPR) when tracking web browsing behavior?
# Session 7 Reflection

**Date:** 12 September 2026  
**Topic:** Proactive Systems, Value-Based Pricing, PFIR Model & Full-Lifecycle AI Risk  

This session brought everything together, demonstrating that pricing, customer support, data architecture, and AI strategy aren't isolated chapters—they are deeply interconnected parts of product management.

**Key takeaways & thoughts:**

* **Proactive Interventions over Reactive Support:** The electricity support case study highlighted a major design shift: instead of using AI to build a faster call center chatbot, use operational data and telemetry to detect outages proactively. The ideal customer experience is one where the customer never has to report a problem because the system already detected it and communicated a resolution timeline.
* **Designing for Uncertainty:** Proactive AI systems must gracefully handle incomplete information. If confidence is low, the UI should explicitly communicate uncertainty or remain silent rather than broadcasting an inaccurate, highly confident alert. A generic "AI may make mistakes" disclaimer is lazy product design; uncertainty must be handled natively in the user experience.
* **Value-Based Pricing Dynamics:** Pricing shouldn't start with cost-plus math. A practical baseline for value-based pricing is capturing **15–25% of the total economic value created** (with 20% being a solid default assumption). Additionally, even in B2B markets, willingness to pay depends heavily on the individual buyer's incentives, operational KPIs, and risk tolerance.
* **The "PFIR" Evaluation Model:** To structure product reasoning clearly, information must be parsed into *Facts/Features $\rightarrow$ Inferences $\rightarrow$ Recommendations*. Mixing raw features with unverified inferences leads to weak product strategy and poor execution.
* **Post-Launch Continuous Risk:** Launch isn't the finish line; it’s the start of an ongoing monitoring cycle. AI products carry dynamic post-launch risks—third-party model updates, API schema shifts, pricing changes, and data drift can instantly alter product behavior without warning. Managing vendor dependencies is a core product strategy responsibility, not just a procurement task.

# Reflection: Session 5

**29 August 2026 | Usha Talatala | 2025MB26177**

---

### The story that landed

* **Designing for AI Uncertainty & UX Transparency:** AI models are probabilistic and will occasionally output incorrect or confidence-varying results. The web user interface must be designed to communicate confidence, manage fallbacks, and handle errors transparently without breaking customer trust.
* **Human-in-the-Loop (HIL) & Fatigue:** Adding human oversight is necessary for high-risk decisions, but if the system constantly asks humans to approve low-risk items, human fatigue sets in and people auto-approve blindly. In Chase Offers+, merchant campaign approvals or offer mapping must balance automation with meaningful, staged human reviews.
* **Build vs. Buy vs. API Sourcing Strategy:** Sourcing AI logic via commercial APIs provides rapid time-to-market but introduces vendor lock-in, latency, and cost risks. Operating open-weight models on cloud infrastructure gives control but increases compute and maintenance overhead.
* **Prompt Engineering as Core UX Component:** Prompts are not one-off experiments; they are vital, version-controlled product artifacts that dictate application experience. Using the RCTC framework (Role, Context, Task, Constraints) ensures structured and reliable model outputs.
* **Platform vs. Feature Play:** Building modular, extensible micro-frontend architectures for web applications allows us to layer specialized merchant offer components without touching the core web platform.


### What I will do

* **Implement UI Confidence & Fallback States:** I will collaborate with UX designers to create clear visual patterns for AI-driven offer recommendations (e.g., "Recommended for you based on your dining history") and design silent fallbacks for low-confidence model outputs.
* **Version Control Prompts in Engineering Repos:** For any generative copy components (e.g., AI-generated deal summaries or merchant category descriptions), my engineering team will manage prompts as code with versioning and automated testing via RCTC structures.
* **Monitor Front-End Error Boundaries:** I will establish robust front-end error handling for external API dependencies so third-party latency or outages never disrupt the primary cardholder banking experience.

### Open questions

1. How can we measure "human fatigue" among internal compliance/operations teams reviewing merchant offer campaign creatives?
2. What strategy should web development teams use when deciding between client-side rendering of AI components versus server-side rendering (SSR) for optimized page load speeds?
# Reflection: Session 3

**18 August 2026 | Usha Talatala | 2025MB26177**

---

### The story that landed

* **Traceability & Responsibility Over Bureaucracy:** The professor emphasized having a traceable decision matrix because product managers operate on "someone else's money" and serve as custodians of trust. In the context of Chase Offers+, every UI decision—from shifting offer card layouts to implementing personalized recommendation carousels—must be traceable back to measurable evidence rather than executive gut feel.
* **Progress over Pure Features:** Focus should be placed on customer progress rather than blindly stacking features. For web development, this means optimizing the customer journey so users can discover, activate, and redeem relevant merchant offers effortlessly without friction.
* **Influence Without Authority:** Modern product leadership requires rallying cross-functional teams without rigid hierarchical authority. For web engineering, this means aligning design, backend API teams, and merchant integration partners behind shared UX performance and offer engagement goals.
* **Qualifying the "User":** Avoid generic terms like "user" or "customer". Within Chase Offers+, we must explicitly qualify whether we are building for a desktop credit card portal user, a mobile web shopper, an elderly cardholder needing high-contrast typography, or a merchant partner managing campaign creative.
* **Scrum as a "Labor Contract" for Stability:** Sprints act as a boundary to protect engineering teams from constant direction changes. In banking web apps where regulatory and business demands change rapidly, fixed 2-week sprints shield developers from continuous mid-sprint pivots while allowing dynamic course-correction between sprints.

### Where I disagree

While shorter sprint cycles (1–2 weeks) offer flexibility for web updates, in highly regulated financial environments like Chase, back-end API dependencies, security reviews, and multi-region deployment pipelines often make 2-week turnarounds for core offer mechanics difficult. Sometimes stability needs a slightly longer horizon to ensure zero customer-facing regression.

### What I will do

* **Eliminate Unqualified UI Copy:** I will ensure our web engineering team and designers stop using vague terms like "user preference" in PRDs and Jira tickets, replacing them with specific personas (e.g., "Frequent Travel Cardholder seeking dining offers").
* **Build Traceable UI Decision Logs:** I will institute a decision log linking front-end performance choices (like offer image lazy-loading or dynamic rendering) directly to conversion metrics and customer engagement evidence.
* **Buffer Engineering via Sprint Guardrails:** I will enforce strict sprint scope stability for my web developers so they aren't jerked around by dynamic stakeholder requests mid-sprint.

### Open questions

1. How can web engineering teams balance the need for rapid UI experimentation (A/B testing offer layouts) with stringent banking compliance and regulatory sign-offs?
2. What are the best practices for setting up fallback UI states when underlying AI recommendation APIs experience latency or silent failures during peak shopping events (e.g., Black Friday)?
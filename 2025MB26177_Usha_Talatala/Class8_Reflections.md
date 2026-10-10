# Reflection: Session 8

**3 October 2026 | Usha Talatala | 2025MB26177**

### The story that landed

* I learned that third-party AI models and external services exhibit **unpredictability and performance shifts over time**, requiring careful platform design.
* The distinction between **prototypes, MVPs, and production scaling** was very clear. Moving from an MVP to full production requires a completely different architectural mindset.
* The concept of **staged automation and Human-in-the-Loop (HITL)** highlighted that full automation should not be rushed. Confidence thresholds help safely manage high-risk workflows.
* Building a **pluggable architecture** is essential so that underlying vendors or components can be swapped without rewriting core business logic.
* The role of **decision gates and go/no-go criteria** is crucial for managing risk before advancing projects to the next stage.

### Where I disagree

Maintaining pluggable architecture and fallback systems for every external service adds substantial engineering overhead. In fast-paced product cycles, building full redundancy for every third-party component is not always practical.

### What I will do

* I will design **resilient, pluggable web portal architectures** with fallback mechanisms so web applications remain stable during third-party API latency or outages.
* I will advocate for **Human-in-the-Loop (HITL) workflows** when building high-risk operational tools, such as automated chargeback dispute reviews or risk scoring.
* I will implement **staged rollouts and pilot testing** for new merchant portal features before deploying updates across all merchant accounts.
* I will establish formal **decision gates** with clear criteria when transitioning web features from prototype to production.

### Open questions

1. What are the key metrics used to determine the right confidence threshold before shifting a workflow from Human-in-the-Loop to full automation?
2. How can web development teams manage the technical debt associated with maintaining pluggable fallbacks for third-party services?



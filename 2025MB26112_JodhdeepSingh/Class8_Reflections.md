# Reflection: Session 8

**3 October 2026 | Jodhdeep Singh | 2025MB26112**

### The story that landed

* **Third-party AI is unpredictable.** External models and services change over time, so products need monitoring and a plan for shifts in performance.
* **Prototype vs. MVP vs. production.** Each stage has different goals, and scaling to production needs a different architectural mindset.
* **Staged automation and human-in-the-loop.** Do not rush to full automation. Use confidence thresholds so humans handle the risky cases first.
* **Pluggable architecture.** Components and vendors should be swappable without rewriting core business logic.
* **Decision gates and go/no-go criteria.** Clear criteria at each stage control risk before more investment is made.

### Where I disagree

Pluggability and fallbacks for every external dependency add real engineering overhead. They should be reserved for critical components, not applied everywhere by default.

### What I will do

* Define **go/no-go criteria** before a project enters the next stage.
* Roll out new features through **pilots and staged releases**.
* Keep humans in the loop for **high-risk decisions** until the data justifies more automation.
* Isolate vendor-specific code behind **clean interfaces** for the most critical dependencies.

### Open questions

1. Which metrics determine the right confidence threshold for moving from human review to full automation?
2. How do teams manage the technical debt of maintaining fallbacks for third-party services?

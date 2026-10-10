# Reflection: Session 5

**29 August 2026 | Jodhdeep Singh | 2025MB26112**

### The story that landed

* **Designing for AI uncertainty.** Models are probabilistic, so interfaces should communicate confidence, handle errors openly and fall back gracefully.
* **Human-in-the-loop and fatigue.** Oversight is needed for high-risk decisions, but flooding reviewers with low-risk items leads to blind approvals.
* **Build vs. buy vs. API.** APIs give speed but bring lock-in, latency and cost risk. Self-hosted models give control but add maintenance load.
* **Prompts as product artifacts.** Prompts should be versioned and tested like code, and structured formats such as **RCTC (Role, Context, Task, Constraints)** make outputs more reliable.
* **Platform vs. feature.** A modular, extensible architecture lets new capabilities be layered on without disturbing the core.

### Where I disagree

Version-controlling and testing every prompt is good practice, but for early experiments it can slow learning. The rigor should scale with how critical the prompt is.

### What I will do

* Treat **prompts as versioned artifacts** with owners and test cases.
* Design **visible confidence and fallback states** in AI-driven features.
* Route only **meaningful, higher-risk items** to human review to reduce fatigue.
* Document the **build/buy/API trade-offs** before choosing a sourcing path.

### Open questions

1. How can "reviewer fatigue" be measured in practice?
2. When does it make sense to move from a commercial API to a self-hosted model?

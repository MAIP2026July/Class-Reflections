# Reflection: Session 4

**22 August 2026 | Jodhdeep Singh | 2025MB26112**

### The story that landed

* **AI appropriateness.** Use the simplest tool that solves the problem: rules first, then analytics and search, then predictive ML, and only then GenAI or agents.
* **Actionable time windows.** An insight delivered after the decision moment has no value, so latency and timing are part of product quality.
* **Disruption and reluctance costs.** Customers resist change because of switching costs, not stubbornness. Good design minimizes the relearning burden.
* **Tail risks and zero-harm boundaries.** Average performance can look fine while rare failures cause serious harm, so guardrails must handle worst cases.
* **Pre-AI vs. post-AI baselines.** Value must be shown against what existed before the AI, not assumed.

### Where I disagree

Starting with deterministic rules is sensible, but at large scale with many segments, rule sets can become unmaintainable. In some cases a simple predictive model is cleaner than a sprawling rules tree, provided a baseline is still measured.

### What I will do

* Set a **baseline before introducing any AI feature** and report lift against it.
* Check that outputs arrive **within the decision window**, not just that they are accurate.
* Define **fallback behavior** so a failed model degrades to a safe default.
* List the **worst-case failure** for each feature and design guardrails for it.

### Open questions

1. How should user feedback loops (e.g., "not relevant") be structured to improve models without hurting performance?
2. How do we balance personalization with privacy regulations when behavioral data is the input?

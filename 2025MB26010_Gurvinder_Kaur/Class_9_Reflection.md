# Reflection: The Economic Value of Models, Evaluation, and Feedback Loops

**Session Date:** October 10, 2026
**Session Topic:** Evaluation vs. Market Feedback, Economic Value of Classification Models, Risk Capacity, Experimentation, and Feedback Loops

## Core Takeaways & Concepts

- **Evaluation Is Yours, Feedback Is the Market's:** Joydev argued evaluation should be under your control while market response is feedback. The instructor agreed in part, but said it isn't pure feedback: the PM can influence outcomes by sensing new technologies, competitors, regulation changes, and standards-body work before they land.
- **Edge Cases and Catastrophe (Insurance):** Wildfire losses in Los Angeles led insurers to bankruptcy, and reinsurance paid only part. A 100-year flood or fire is rare, but when it hits it hits hard (the 2008 meltdown as context). Test edge cases, not just the happy path, and simulate. How much risk to accept or transfer is a management decision.
- **Accuracy Misleads, Recall and Economics Matter:** With imbalanced data (for example, two bad loans in 100), accuracy hides a model that misses half the bad cases. Recall shows how many true positives you catch. The instructor's loan example assigned profit or loss to each confusion-matrix cell (a 2.5% interest spread vs. a ₹1 lakh loss on a defaulted loan). The model supplies recall, the business supplies economic value, and you multiply them to decide whether the model is worth using.
- **Risk Capacity Matters:** How much risk you can bear depends on current exposures, collateral or guarantees, and whether defaults are correlated (cascade and contagion).
- **Irreversible One-Shot Decisions:** When an error means irreversible damage (a patient dies, game over), impact dominates probability, unlike repeatable settings where you can recover. The hijacked-plane policy example showed how a no-negotiation stance changes incentives, even with emotional costs.
- **Attributability and Smart Targeting:** A churn model that gives everyone a discount can lower profit. A customer's value includes network effects and social-media reach. Attributing a business result to your product is hard (a recommender may reduce a shock but get no credit).
- **Experimentation:**
  - Use test and control groups, A/B tests, and standard error.
  - Gautam described Bayesian methods that allow mid-experiment readouts, now used widely.
  - Awareness of being measured changes behavior (incentive credits bias feedback), so anonymize where possible.
  - You can't show wildly different UIs to similar users in usability testing.
- **Feedback Loops:** Feedback can run away and narrow the product toward one segment. Keep generic attractiveness and use add-ons, wrappers, or a personalized preferences filter. Decide which loops to keep and which to break. Always ask what you are optimizing and what you consciously ignore.
- **Third-Party Model Drift:** A third-party cloud LLM can change for better or worse without notice, so keep evaluation running.

## Workplace Applicability & Contextual Translation

- **Recall Over Accuracy in Screening:** Missing a strong candidate (false negative) costs placements. Evaluate screening models by recall at a reasonable review burden, and assign rough costs to a missed hire vs. a wasted interview.
- **Test vs. Control for Recruiting Tools:** When rolling out an AI sourcing assistant, compare recruiters using it with similar recruiters not using it, and track time-to-submittal and placement quality.
- **Feedback Loop Risk:** If the matching model learns only from hires approved by past managers, it narrows toward one profile. Add deliberate diversity checks and periodic loop reviews.

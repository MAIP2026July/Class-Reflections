# Reflection: Session 9

**10 October 2026 | Usha Talatala | 2025MB26177**

### The story that landed

* I understood the contrast between **deterministic systems and generative outputs**, particularly the need for specialized evaluation frameworks when outputs are non-deterministic.
* Evaluating models using an **Economic Payoff Matrix rather than pure accuracy** was a major insight. Mapping confusion matrices to actual financial profit, loss, and risk impact is vital.
* The focus on **tail risk management** demonstrated that overall averages can hide extreme edge cases that lead to catastrophic failures.
* The nuances of **A/B testing and controlled experiments** showed that external variables and concurrent system changes can distort test results.
* The danger of **uncontrolled feedback loops** explained how over-optimizing for specific noisy user groups can degrade the broader user experience.

### Where I disagree

While economic payoff matrices are effective for risk evaluation, quantifying exact financial costs for soft metrics like customer trust or brand reputation during a false positive error remains difficult in real-time web applications.

### What I will do

* I will evaluate web portal algorithms (such as fraud flags or offer recommendations) based on **net economic impact** (loss prevention vs. conversion friction) rather than pure statistical accuracy.
* I will establish specific **tail-risk review protocols** for web platform deployments to identify and mitigate high-impact edge cases.
* I will structure **rigorous A/B testing controls** for checkout UI updates, accounting for external factors like seasonal transaction volume.
* I will monitor personalization features on web portals to ensure we do not create **unbalanced feedback loops** that favor power users at the expense of general users.

### Open questions

1. How do you assign concrete monetary values to indirect consequences like user frustration or cart abandonment when building an Economic Payoff Matrix?
2. What statistical methods best isolate product changes during A/B testing on high-volume web portals subject to heavy external seasonality?
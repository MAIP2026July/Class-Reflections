# Session 9 Reflection

10 October 2026 | Seelam Raviteja | 2025MB26062

Accuracy is a comforting score and, for many product decisions, the wrong one. A model that is right 98 percent of the time can still be a bad business if the 2 percent is where the money, the trust, or the safety sits.

I want the evaluation to start from the payoff of each kind of mistake. A false alarm and a miss do not cost the same. In a fraud check, blocking a good payment annoys a customer and may lose a sale. Letting a bad payment through can lose the principal, the chargeback cost, and the relationship. In a clinical or credit setting the asymmetry is sharper. Mapping those outcomes into an economic payoff, rather than celebrating a single accuracy number, forces the threshold to serve the business. The hard part, which I do not want to smooth over, is that trust and reputation do not arrive as a clean rupee figure. I would still put a range on them, sourced from churn, complaints, and the cost of winning the customer back, and I would label the range as a judgement. Leaving them out because they are soft is how the matrix quietly optimizes for the easy costs.

Averages have the same blind spot we discussed earlier in the course, and this session made the measurement consequence clearer. Tail cases can be rare enough to barely move accuracy and still be the reason a launch should stop. I would split release criteria into two lists. One is a rate: this kind of error must stay under a level we can afford at volume. The other is absolute: one instance of this harm is enough to hold the release, because the damage does not average out. A fabricated claim in a customer-facing answer is closer to the second list than the first.

Experiments need the same suspicion of clean numbers. An A/B test on a live product shares the calendar with festivals, outages, campaigns, and other teams' releases. If those are not controlled or at least recorded, the winning variant may be a season wearing a product's clothes. I would rather run a smaller test with a stable window than a large one I cannot explain.

Feedback loops are the risk that arrives after a test looks successful. If the product learns mostly from the users who complain, click, or rate the most, it will tune itself to a loud minority and degrade the quieter majority. Personalization that chases that signal can raise a local metric and lower the experience of everyone else. The managerial response is to ask whose behavior is in the training signal, and what happens to the customers who never show up in it.

What I will carry into a later decision is a short test before any model review. What does a false positive cost, what does a false negative cost, which single failure is unacceptable at any rate, and which users are absent from the data that will retrain the system. If I cannot answer those, a higher accuracy score is not yet a reason to ship.

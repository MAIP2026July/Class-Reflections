# Session 9 Reflection

**Date:** 10 October 2026  
**Topic:** AI Product Metrics, Economic Cost of Errors, Tail Risk, Experimentation & Feedback Loops  

The biggest mindset shift from today’s session was realizing that **a technically accurate AI model is not necessarily a successful AI product.** Accuracy, precision, recall, and F1-score help us understand model performance, but product success depends on what those predictions actually mean economically and operationally. The real question isn't simply how often the model is correct, but what happens to the business and the customer when it is wrong.

**Key takeaways & thoughts:**

* **Not All Errors Have the Same Cost:** Looking at a confusion matrix from a business perspective changed how I think about false positives and false negatives. In a lending product, approving a borrower who eventually defaults creates a direct financial loss, while rejecting someone who would have repaid means losing a valid business opportunity and potentially damaging customer trust. The optimal model therefore isn't automatically the one with the highest accuracy; it is the one whose error profile best matches the consequences and objectives of the product.

* **Tail Risk Can Matter More Than Average Accuracy:** A model can perform extremely well on average and still expose the business to unacceptable risk. The wildfire and insurance discussion demonstrated how a relatively rare event can create losses large enough to overwhelm the benefits accumulated during normal operation. This connects strongly with the earlier discussion on AI appropriateness: when the consequence of failure is high, PMs need to understand worst-case scenarios and failure distributions rather than relying only on aggregate performance metrics.

* **Product Metrics Need to Connect Technical Performance to Business Value:** Model metrics are useful, but they should eventually connect to measurable outcomes such as revenue, loss avoided, conversion, operational efficiency, customer trust, or retention. A dashboard full of KPIs can actually make decision-making harder if nobody knows which metric the product is optimizing. The important part is choosing a small number of metrics that represent the current product objective and revisiting them as the product matures.

* **Good Numbers Can Hide Weak Underlying Signals:** Revenue growth alone does not necessarily mean that a product is becoming healthier. For example, revenue may continue to increase while new customer acquisition is already declining, creating a delayed problem that the headline metric hides. This reinforced the importance of identifying leading and lagging indicators rather than treating one successful business metric as proof that the overall product is healthy.

* **Experimentation Requires Causality, Not Just Before-and-After Comparison:** An improvement in a metric after launching a feature does not automatically prove that the feature caused it. A proper control group, adequate sample size, statistical significance, and awareness of external factors are necessary before attributing the change to the product intervention. For PMs, experimentation therefore isn't just about running an A/B test; it is about designing enough evidence to support a decision.

* **Feedback Loops Can Improve or Distort the Product:** Customer feedback is essential, but repeatedly optimizing around the loudest or most active customer segment can gradually turn a scalable product into a customized solution. This connects back to the layered-product principle from earlier sessions: maintain a common core product while allowing controlled configuration or extensions for specific segments. Feedback should influence the roadmap without allowing one group of users to redefine the entire product.

The broader lesson for me is that **AI product measurement should translate technical performance into the real cost and value of decisions.** A 95% or 99% accuracy number means very little without understanding what happens inside the remaining errors, who bears their consequences, and whether the product is actually improving the intended business outcome. As a PM, the objective isn't to maximize a model metric in isolation; it is to choose the right trade-off between opportunity, risk, customer impact, and long-term product value.

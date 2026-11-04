# Reflection: Session 9

10 October 2026 | Alamelu G | 2025MB26016

---

This class made me think differently about how we measure whether an AI product is actually successful. Until now, I have mostly associated AI model performance with things like accuracy, precision, recall and F1 score. But the discussion made me realise that these numbers alone do not tell us whether the product is creating value for the business or the customer.

**The point that stayed with me.** "One loss can wipe out the gains of multiple successful predictions." This was probably the most interesting part of the class for me. The faculty explained that average accuracy can sometimes hide the actual risk of a product. An AI model may perform well in most cases, but one serious mistake can have a much bigger financial or business impact than all the correct predictions combined.

The loan prediction example made this easier to understand. If a bank uses AI to decide whether to approve a loan, there are different outcomes. Giving a loan to someone who defaults results in a financial loss, but rejecting someone who could have repaid the loan also means losing a business opportunity. So both types of errors have a cost. I had not really looked at a confusion matrix from this economic perspective before. 

**Where I slightly disagree.** I understand why we should not depend only on accuracy, but I also think choosing the right metric can become complicated because different stakeholders may have different priorities. What is a good decision for a bank may not necessarily be a good decision for the customer. Similarly, the product company may want to reduce its errors, while the actual customer may be more concerned about avoiding a wrong rejection. So there is no single metric that can represent success for everyone.

**The tail risk discussion was important.** The example of the insurance companies facing huge losses because of wildfires showed how something that looks like a low-probability event can become a serious problem. We may be comfortable with the average performance of a model, but what happens when an extreme situation occurs? This made me realise that testing only the normal or expected scenarios is not enough. We also need to think about edge cases and what happens when things go completely wrong.

I also liked the point that simulated testing does not guarantee success in the real world. A model may perform very well during testing, but actual customer behaviour and real-world situations can be very different. As product managers, we should not just accept the average results given by the technical team without understanding the risks behind them.

**Another thing I noted was that metrics should evolve with the product.** The example of a company showing revenue growth while the number of new customer signups was actually declining was interesting. At first glance, the revenue numbers looked good, but the underlying business situation was different. This made me think that sometimes we keep measuring what was important at an earlier stage even when the product has changed.

The faculty also mentioned that we should not have too many KPIs just for the sake of tracking everything. We should know what we are optimising for and choose a small number of meaningful business metrics. I liked this because having a dashboard full of numbers does not necessarily mean we understand what is happening.

**The experimentation discussion also stood out.** I found the A/B testing example useful, especially the importance of having a control group. Just because customer satisfaction increases from 4.5 to 4.8 does not automatically mean that the product improvement caused it. We should look at the sample size, standard error and whether the difference is statistically significant before making claims.

Another interesting point was about feedback loops. Listening to users is important, but continuously making changes based on one particular group of users can make the product too customised for that segment. It may improve the experience for some customers while making it worse for others. The idea of keeping a common core product and offering additional customisation for specific segments seemed like a practical way to handle this.

**What I will take forward.** For our own AI product, I want to think beyond model accuracy when defining success. We should identify the cost of false positives and false negatives, understand who bears the risk, consider the impact on customer trust and connect the technical metrics to actual business outcomes. I also want to be more careful when interpreting feedback and experiment results instead of immediately assuming that every improvement is a positive result.

**Open question.** I am still thinking about how product managers decide the right trade-off between reducing errors and capturing business opportunities. Especially in areas like banking, insurance and healthcare, being too cautious can also mean losing opportunities or delaying decisions. So how do we decide what level of risk is acceptable without compromising customer trust or the long-term value of the product?

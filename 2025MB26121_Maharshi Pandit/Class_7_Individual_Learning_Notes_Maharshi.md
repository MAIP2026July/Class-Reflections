# Class 7 Individual Learning Notes

**Course:** Management of AI Products  
**Recording date:** 12 September 2026  
**Student:** Maharshi Pandit  
**BITS ID:** 2025mb26121

## My Learning and Reflection

My strongest learning from Class 7 is that a Product Manager should not remain distant from the real product or customer. The professor’s example of calling a bank during a cybersecurity incident made this clear. The customer-support representative could not understand the seriousness of the issue or provide a proper escalation path. Even if the bank had good technology, the complete product experience failed at the point where the customer needed help. I understood that the Product Manager should spend time handling tickets, calls or support emails after launch because these interactions reveal gaps that reports may not show.

The electricity-distribution case helped me connect many product-management concepts. The first idea was a call-centre solution or Artificial Intelligence voice bot. However, the better product question was: **Why should the customer have to call at all?** If a distribution company can detect abnormal consumption, identify a probable outage, dispatch the field team and inform affected customers proactively, the workflow becomes more valuable than simply automating complaint calls.

This example also showed the difference between planned and unplanned events. Planned-maintenance information is already known and should normally come from an approved database or rule. An unplanned outage may require anomaly detection, customer reports and human confirmation. I learned that every part of a product does not need Artificial Intelligence. A dependable product can combine verified data, rules, Machine Learning and human judgement.

The discussion on uncertain information was useful. A mobile application may know the caller’s registered property and current GPS location, but the complaint may refer to a different property. The product should ask a clarifying question rather than assume. Similarly, the interface should distinguish between a confirmed outage and a probable outage. If confidence is low, the system may request confirmation from customers, call-centre staff or field employees. If the information is completely unreliable, the product should avoid presenting it as fact.

I also understood the value of separating **facts, inferences and recommendations**. A planned shutdown is a fact when it exists in the approved system. A sudden fall in electricity consumption may support an inference that an outage has occurred. Sending a field employee is a recommendation based on evidence. If the facts are wrong, the recommendation may also be wrong. Therefore, the product should show the evidence chain and allow the human decision-maker to verify it.

The business side of the case was equally important. A distribution company may purchase electricity through forward contracts. If an outage prevents the company from distributing purchased power, the company may lose revenue while still paying for the supply. Early outage detection may therefore create operational and financial value, not only better customer service. The professor’s guidance that a supplier may capture roughly **15% to 25% of demonstrated business value**, with 20% as a practical classroom estimate, helped me understand value-based pricing. The exact price must still depend on the customer’s economics and evidence.

The case also showed why the Product Manager must remain inside the selected scope. Customer support, outage detection, energy pricing and capacity planning are related, but they are different products. Moving into an adjacent problem should be a conscious roadmap decision rather than uncontrolled feature expansion. A capability developed for electricity may later transfer to broadband or water utilities, but the first product should prove one clear workflow.

Another important learning was that launch is not the finish line for an Artificial Intelligence product. External model providers may change quality, availability or price. Real-world performance may differ from testing. The team needs alpha and beta testing, monitoring, quality thresholds, rollback and a safe manual process. The professor’s experience of being exhausted during a first product launch reminded me that the team must preserve enough energy for post-launch support and learning.

## How I Can Apply This Learning

For RiskReview AI, I should not build a detached writing assistant. The product should support the complete monthly risk-review workflow. Rules can identify missing owners, dates and mandatory fields. Artificial Intelligence can suggest unclear cause-event-impact structure or related risks. The interface should show the original entry, reason for the finding, evidence or confidence, and human options to accept, edit, reject, merge or defer.

The product must not automatically decide probability, impact, mitigation, escalation, acceptance or closure. I will define the fallback process, severe launch blockers, monitoring measures and what happens if the external Artificial Intelligence service changes or becomes unavailable.

## My Main Takeaway

My main takeaway is that a Product Manager must design and own the complete system: customer problem, data, uncertainty, human authority, business value, support and post-launch operation. Artificial Intelligence should remove avoidable customer effort, but it should never hide uncertainty or replace accountability.

---

**AI-use disclosure:** Microsoft Copilot was used to organise and improve the wording of these notes. The examples, interpretation and reflection are based on my understanding of the uploaded Class 7 recording.

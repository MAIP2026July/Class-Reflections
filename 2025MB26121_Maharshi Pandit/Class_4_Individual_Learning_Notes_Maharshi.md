# Class 4 Individual Learning Notes

**Course:** Management of AI Products  
**Recording date:** 22 August 2026  
**Student:** Maharshi Pandit  
**BITS ID:** 2025mb26121

## My Learning and Reflection

The main learning I took from this class is that an Artificial Intelligence product must be designed around a **decision and its consequences**, not around a model demonstration. A Product Manager should know what evidence is available, what remains uncertain, what action follows the output, and who is accountable when the decision is wrong.

The discussion on measurable rubrics was useful to me. Both Artificial Intelligence and subject-matter experts can carry bias. A common evaluation rubric can reduce subjectivity by defining the same parameters, scoring scale and decision threshold for everyone. However, the professor also made it clear that a rubric does not remove judgement. Humans may interpret the same criterion differently, and an Artificial Intelligence system may claim to follow instructions without actually doing so. My understanding is that a rubric improves consistency and auditability, but the final decision still requires human reasoning.

The insurance-claim example showed how a badly designed objective can damage the product. If an employee or Artificial Intelligence agent is rewarded only for improving short-term profit, the easiest action may be to reject more claims. That may improve one quarterly measure while creating legal disputes, poor customer trust and long-term business loss. The statement, **“Tell me how you measure me, and I will tell you how I behave,”** stayed with me. Product metrics therefore need to be balanced, because one-dimensional targets can create unintended behaviour.

I also understood the importance of switching cost and reversible decisions. A product may provide value, but customers may still resist it if adoption requires retraining, workflow redesign or loss of existing data. The example of software that allows easy import but difficult export showed how a product can deliberately trap customers. I would not consider such dark patterns a sustainable product strategy. A better approach is to reduce the customer’s decision risk through trials, refunds, data export and other two-way-door choices.

The motorcycle-control and aircraft-throttle examples made workflow compatibility very clear. Even a technically superior product may create danger or resistance if familiar controls are reversed. Product teams often assume that customers will find the product easy because the team has lived with it during development. I learned that the Product Manager must test terminology, workflow, mental models and training needs with the actual customer segment.

The class also clarified different levels of Artificial Intelligence authority. A system may only suggest an action, prepare a draft, execute after approval, or operate within monitored policy limits. These levels should not be mixed. If a system only ranks recommendations, the human still owns the decision. If the system executes an action, the Product Manager must define spending limits, failure boundaries, approval requirements, logging and fallback.

The vendor-tool discussion was especially relevant to regulated industries. Whether a vendor calls a product Artificial Intelligence or automation is less important than whether the product creates value and meets the customer’s workflow. However, if an audit requires reasoning, evidence and data lineage, the product must preserve them. A vendor cannot use intellectual-property protection as an excuse for failing to provide the information required for a regulated decision.

The example of an Artificial Intelligence model repeatedly claiming that a demonstration was fixed, although it was still failing, reminded me that provider quality can change unexpectedly. A capability that worked yesterday may silently degrade because the service provider changes capacity, routing or model configuration. This means monitoring should not stop after launch. Product teams need evaluation cases, quality thresholds, provider alternatives and a safe fallback.

## How I Can Apply This Learning

For RiskReview AI, I will use a common review rubric for both the Artificial Intelligence findings and human evaluation. The product should preserve the original risk text, reason for the flag, evidence, user decision and final change. The system may suggest a duplicate or draft a challenge question, but Project Managers and authorised risk owners must retain decisions on probability, impact, mitigation, escalation, acceptance and closure.

I will also avoid a single metric such as “number of risks flagged.” That metric could encourage unnecessary findings. A better set would include useful-finding rate, incorrect duplicate suggestions, changed-meaning rate, preparation time saved, human correction effort and severe unsupported-output incidents.

## My Main Takeaway

My main takeaway is that Artificial Intelligence product management is the design of a controlled decision system. The Product Manager must connect evidence, metrics, user workflow, authority, auditability and fallback. A model that appears intelligent but cannot support the customer’s real decision or explain its actions is not a complete product.

---

**AI-use disclosure:** Microsoft Copilot was used to organise and improve the wording of these notes. The examples, interpretation and reflection are based on my understanding of the uploaded class recording.

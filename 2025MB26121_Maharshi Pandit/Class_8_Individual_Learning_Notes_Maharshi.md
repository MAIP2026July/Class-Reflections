# Class 8 Individual Learning Notes

**Course:** Management of AI Products  
**Recording date:** 3 October 2026  
**Student:** Maharshi Pandit  
**BITS ID:** 2025mb26121

## My Learning and Reflection

The most important learning for me from Class 8 is that an Artificial Intelligence product must be designed for **change and uncertainty**, not only for a successful demonstration. The professor explained that hosted tools such as Claude, Codex and other coding assistants can suddenly perform better or worse even when the user has not intentionally changed the workflow. I understood that model randomness and provider-side instability are different risks. With a locally controlled model, the weights may remain fixed, while an external provider may change routing, compute, model versions or service behaviour without informing us.

The example of an agent behaving like a donkey that moves only one step after being pushed made this problem memorable. Sometimes an agent completes a long task correctly, while at another time the same tool stops after one step despite clear instructions. During development this creates delay and frustration, but in production the risk is larger because the team may not know which customer received an incomplete or poor-quality response. Therefore, monitoring should evaluate output quality by customer and use case, not only system uptime.

The discussion on repeatedly rejecting generated requirements was also useful. If the sixth response becomes correct after five rejections, it does not necessarily mean that the model has permanently learned. The system may only be eliminating alternatives within the current session. When the session restarts, the same behaviour may return because the underlying weights were not updated. This taught me to ask what type of memory exists: session context, saved preference, retrieval memory, fine-tuning or actual model learning.

The insurance-rating example showed why a hybrid solution is often better than forcing a Large Language Model to perform every task. Premium calculation requires deterministic and repeatable output, so a rules engine or approved rating engine should perform the calculation. Retrieval-Augmented Generation can retrieve relevant policy information, and a language model can explain the result in clear language. The product should combine rules, Application Programming Interfaces, retrieval, Artificial Intelligence and human judgement based on the nature of each task.

I also understood the difference between a prototype, pilot and Minimum Viable Product. A prototype should answer one uncertain question cheaply. A pilot allows a real customer to use the workflow in a controlled setting. A Minimum Viable Product should deliver enough value for the customer to use it, even if some steps remain manual. The professor’s dissertation-feedback example made this clear: a fully integrated tool is not valuable if the feedback does not match the university’s actual evaluation process, while a useful tool may still create value even if the user has to copy and paste the result manually.

The class also changed my understanding of Human-in-the-Loop. Manual work is acceptable during early validation, but it should be disclosed honestly. Hidden human labour may make a product appear more automated than it really is and may fail at scale. The team should use manual review to learn, define confidence thresholds and gradually automate safe cases. Low-confidence or high-risk cases should remain with an authorised human.

Another important learning was the need for decision gates. Before moving from concept to prototype, pilot or scale, the team should define what evidence is required and what decisions are possible: proceed, proceed with conditions, rework, modify or stop. Governance should be strong enough to protect the product but not so bureaucratic that it becomes the bottleneck. The criteria should be documented before the review so that the team is not surprised by changing expectations.

The professor’s feedback on project topics was directly relevant to RiskReview AI. Words such as “engineer,” “user” or “all industries” are too broad. The Product Manager should identify the exact person, organisation, workflow, time pressure and decision. A design engineer working for an automotive component supplier has a different need from a purchasing engineer or a vehicle Original Equipment Manufacturer. Narrowing the domain is not reducing ambition; it is preventing the team from trying to solve every problem at once.

## How I Can Apply This Learning

For RiskReview AI, I will define one industry segment, one primary user and one monthly risk-review workflow. The prototype should test whether rules and Artificial Intelligence can improve register quality without changing the intended meaning. Missing fields can be checked deterministically, semantic similarity can suggest related risks, and Generative Artificial Intelligence can draft challenge questions. Probability, impact, mitigation, escalation, acceptance and closure must remain human decisions.

I will also keep the external model replaceable, record the model and prompt version, define go/no-go criteria, disclose manual steps and maintain a safe fallback if the provider changes quality or becomes unavailable.

## My Main Takeaway

My main takeaway is that speed from Artificial Intelligence is useful only when the Product Manager preserves judgement and control. A fast prototype or impressive response does not prove product value. The Product Manager must define the customer, choose the right combination of rules and Artificial Intelligence, make components replaceable, test with real users and move forward only when evidence supports the next stage.

---

**AI-use disclosure:** Microsoft Copilot was used to organise and improve the wording of these notes. The examples, interpretation and reflection are based on my understanding of the uploaded Class 8 recording.

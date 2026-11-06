# Class 12 Individual Learning Notes

**Course:** Management of AI Products  
**Recording date:** 31 October 2026  
**Student:** Maharshi Pandit  
**BITS ID:** 2025mb26121

## My Learning and Reflection

The strongest learning for me from Class 12 is that a good product-management document should be written almost like a **contract for building the product**. If an engineering team or external vendor receives the document, the team should understand what to build without depending on hidden assumptions. Terms such as “accurate,” “user-friendly,” “high risk” and “reduced consultation time” sound acceptable, but each person may interpret them differently. The professor’s example was simple: saving half a second technically reduces time, but it may not be the improvement the Product Manager intended. A clearer requirement would say, for example, “reduce average consultation time by 30% from the measured baseline.”

The class made me understand why the workflow must be defined early. The first workflow may change after pilot feedback, but the team still needs a reference point. A swimlane diagram can show what the customer, Product Manager, system, Artificial Intelligence component and human reviewer do at every stage. It can also identify where the flow is deterministic, where the output is probabilistic, where hallucination is possible and where Human-in-the-Loop is required. I found the recommendation to use **PlantUML or Mermaid** useful because the diagram remains text-based, version-controlled and easy to update in GitHub.

The professor also distinguished a project plan from a product roadmap. The project plan explains the phases required to create the first version. The roadmap should show how Version 1, Version 2 and Version 3 may evolve. This corrected my earlier tendency to call every development phase a roadmap. The first version needs detailed timelines because the organisation cannot sell the product until something usable is available, while later versions can remain higher-level hypotheses.

Another important learning was to review the specification from an investment perspective. The professor asked us to imagine spending our own ₹1 crore to contract someone to build the product. If the document contains missing decisions, hard-coded assumptions or ambiguous success measures, that money is at risk. The suggestion to provide the document to an Artificial Intelligence tool and ask, “Can this be built without clarification?” is a practical self-review method. However, the team must judge and correct the Artificial Intelligence feedback rather than accept it mechanically.

The monetisation discussion connected customer value with product architecture. The Japanese target-costing approach starts with what the customer is willing to pay, subtracts the required margin and then determines the maximum cost-to-serve. This is stronger than building first and adding a profit margin later. The difference between **input-based and outcome-based pricing** was also clear. A provider may prefer payment for tokens, API calls or hours because the cost is easier to recover. The customer prefers to pay for a useful result. Outcome-based pricing can win more business, but it transfers more delivery risk to the product company.

The example from IT services helped me understand this trade-off. Time-and-material billing places less delivery risk on the provider, while fixed-price and gain-sharing models create greater responsibility for the result. The real-estate example went further: payment for a completed sale may be much higher than payment for a lead, but the provider must carry the lead-to-sale conversion risk. The Product Manager therefore needs to know what the customer is actually buying. A customer buying insurance is really buying a safety net, not the policy document itself.

I also learned that Artificial Intelligence economics can directly change architecture. An agent without a maximum loop may continue calling an API and consume tokens without completing the goal. A cheaper model may reduce cost but lower quality. A frontier model may improve quality but increase latency and inference cost. The Product Manager must find a workable balance among **quality, latency, cost and trust**. The Oracle examples showed that licensing based on connections or CPU cores can force architectural redesign. Finance is therefore not separate from technology; product economics can decide system structure.

## How I Can Apply This Learning

For RiskReview AI, I will define the automotive component programme workflow using a swimlane diagram. The diagram will show what the APQP coordinator, Project Manager, risk owner, deterministic rules, Artificial Intelligence review and human approval do. I will replace broad statements with measurable targets, such as preparation-time reduction, useful-finding rate, incorrect duplicate suggestions, changed-meaning incidents, cost per reviewed register and maximum human-review time.

I will also separate the detailed Version 1 delivery plan from the future roadmap. The pricing and cost model should consider the number of projects or registers, model calls, human review, support and configuration. RiskReview AI should not charge only for Artificial Intelligence activity; the commercial model should connect with the value of a more reliable and efficient launch-readiness review.

## My Main Takeaway

My main takeaway is that Product Management turns an idea into an unambiguous, measurable and commercially workable product. The workflow, requirements, metrics, architecture and pricing cannot be designed separately. If the Product Manager clearly defines the customer value and product economics, engineering and business decisions become easier to align.

---

**AI-use disclosure:** Microsoft Copilot was used to organise and improve the wording of these notes. The examples, interpretation and reflection are based on my understanding of the uploaded Class 12 recording.

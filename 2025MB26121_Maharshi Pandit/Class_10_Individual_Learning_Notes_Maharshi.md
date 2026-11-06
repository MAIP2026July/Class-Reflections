# Class 10 Individual Learning Notes

**Course:** Management of AI Products  
**Recording date:** 17 October 2026  
**Student:** Maharshi Pandit  
**BITS ID:** 2025mb26121

## My Learning and Reflection

My main learning from Class 10 is that scaling an Artificial Intelligence product is not simply adding more servers or handling more requests. It means scaling the **customer promise** while controlling quality, latency, cost, data freshness, operational complexity and risk. A product may work well for a few users during a demonstration and still become commercially unsustainable when usage grows.

The discussion about Artificial Intelligence cost made this practical. The professor referred to an example where Artificial Intelligence usage reportedly reduced from around **$1,000 per person per month to about $29**. Whether the exact amount applies everywhere is less important than the lesson: Artificial Intelligence costs are no longer too small to ignore. A Product Manager remains responsible for return on investment and should know when a frontier model is necessary, when a smaller model is sufficient, and when rules or cached results can complete the task more economically.

I understood that products and projects scale differently. In a project, the customer and billable effort are usually known. A product must recover development and operating costs across many customers who may not yet be known when the product is built. The purpose of a product is therefore reuse, repeatability and non-linear growth. If every new customer requires a separate custom build, the organisation may still be delivering services rather than a scalable product.

The examples of **WhatsApp, Gmail and Uber** helped me understand how user expectations change once a product becomes important. A free product may still receive strong criticism when it is unavailable because customers have built daily activities around it. Similarly, Uber’s promise is not that the application will display a searching animation; the promise is that a suitable cab will arrive within the expected time. Technical uptime is therefore not the same as fulfilment of the product promise.

The rear-view-camera example showed how expectations evolve. A feature may begin as a “wow” factor, become expected and later become a basic hygiene requirement. Response time follows the same pattern. Earlier, waiting several days for a letter was normal. Today, even a few minutes without a response can create anxiety. This means the acceptable quality-latency-cost trade-off is not permanent. The Product Manager must review it by customer segment, competitor level and time period.

I found the professor’s example about predictable processing useful. A process that sometimes completed in 14 seconds and sometimes took around one and a half minutes created uncertainty. The professor intentionally added cleanup work so that the process became slightly slower but more predictable. My understanding is that customers may prefer dependable completion within a known range over a faster average with occasional extreme delays. Product teams should therefore measure variability, not only average latency.

The class also explained why a larger model is not always better. A small language model may be appropriate for classification, routing or a simple decision, while a frontier model may be required for complex reasoning. A smaller model can first decide where the request should go. Caching, batching, shorter prompts, retrieval and selective routing can reduce cost, but each technique may affect privacy, freshness or quality. The Product Manager must define an acceptable operating range rather than allowing teams to move between extremes whenever someone complains about cost or speed.

The railway example made tiering and queues easy to understand. Vande Bharat, Rajdhani, express and passenger trains may use the same tracks but receive different priorities and service expectations. In the same way, an Artificial Intelligence product may need separate queues, usage limits and service levels for different customer tiers. However, one heavy user should not consume all shared capacity and leave other customers waiting. Service-level agreements should express customer and business promises, not only technical measurements.

Another important learning was that versioning is not only technical bookkeeping. Software, data, models, prompts, experiments and customer segments may all need versions. If a new model performs better for one segment and worse for another, the product may need routing or rollback by segment. Rollback is also not guaranteed when an external provider stops supporting the older model. Therefore, lineage, evaluation history, provider alternatives and replaceable components are part of product governance.

The professor also compared Artificial Intelligence product operation with a **marathon rather than a sprint**. A dramatic launch supported by team heroics is not a sustainable operating model. Some people work effectively in short, intense “commando” periods, while others provide steady “army-style” execution. A Product Manager should use different strengths appropriately and should not evaluate every person through one uniform measure.

## How I Can Apply This Learning

For RiskReview AI, I will define a clear promise: improve the readiness and quality of a specific industry’s monthly project-risk review without taking control of consequential risk decisions. The team should set acceptable ranges for finding quality, response time and cost per register. Rules should handle completeness checks, smaller models may support similarity or classification, and a stronger model should be used only where complex challenge-question generation justifies the cost.

The product should monitor useful-finding rate, changed-meaning incidents, provider cost, processing latency, human-review workload and severe unsupported outputs. Model, prompt, rule and dataset versions should be recorded so that the team can investigate changes and return to a safe workflow when required.

## My Main Takeaway

My main takeaway is that scaling means keeping the product promise dependable while usage, complexity and customer dependence increase. The Product Manager must define the acceptable trade-off between **quality, latency and cost**, communicate that range to every team, and ensure that growth does not destroy trust or profitability.

---

**AI-use disclosure:** Microsoft Copilot was used to organise and improve the wording of these notes. The examples, interpretation and reflection are based on my understanding of the uploaded Class 10 recording.

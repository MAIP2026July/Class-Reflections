Name - Gokulkrishnan N

Registered No - 2025MB26210

Management of AI products

**10th Session Topic:** Scaling AI Products, Inference Economics, and Operational Ownership.

**Management of AI Products – Class Reflection**

**1\. Class Overview** This session looked at what happens after an AI product succeeds. Growth brings its own problems: more users mean higher inference bills, tighter API limits, more varied data and much higher expectations of reliability. The class discussed why scaling an AI product means more than adding servers, how to keep unit costs under control through model routing and caching, and why monitoring and versioning are part of the product manager's job and not just an engineering concern.

**2\. Key Concepts and Discussions**

- **A Product Is a Promise, Not a System:** The Uber example showed that the app can be fully up and responsive while the customer still fails to get a ride because no driver accepts. Success has to be measured by whether the customer receives the outcome they were promised, not by server uptime. Scaling therefore means protecting that promise as usage grows.
- **From Experiment to Mission-Critical:** Users tolerate outages while a product is new and easy to replace. Once it becomes part of their daily workflow, the same outage becomes unacceptable. Expectations also decay over time: what feels like a "wow" feature today becomes a basic expectation tomorrow, much like rear-view cameras in cars. A PM has to keep resetting the quality, latency and cost bar instead of treating it as fixed.
- **Token Economics and Model Routing:** Sending every request to a frontier model looks impressive in a demo but destroys margins at scale. Routine queries can be routed to smaller, cheaper models, while complex reasoning is reserved for the larger ones. Caching repeated answers saves further cost, but must never leak one customer's data to another.
- **Priority Under Rate Limits:** The Indian Railways analogy explained multi-tenant scheduling well. Express and passenger trains share the same tracks but run on different priorities. In the same way, when an external API caps requests, paid or critical customers need a separate queue so heavy free-tier usage does not starve them.

**3\. Important Insights**

- **Scaling Is a Full-Stack Problem:** Growth exposes weaknesses across the whole Data → Model → API → UX chain. A model that performs well in one region or use case can fail in another because the data coverage or user behaviour is different. More infrastructure cannot fix stale or missing data.
- **Predictable Latency Can Beat Fast Latency:** Customers do not always want the fastest answer. In one example, users preferred a consistent processing time over a faster but unpredictable one. Latency targets should come from what the customer expects, not from a technical benchmark.
- **Monitoring Must Map to Business Signals:** In the electricity distribution example, a sudden spike or drop in a locality's consumption is not just a data anomaly. It is an operational event that needs action. A PM does not need to run the monitoring stack but must define which signals show that the customer promise is at risk.

**4\. Practical Learnings**

- **Version Everything, Not Just Code:** AI behaviour depends on data snapshots, prompts, model versions and routing rules, so all of these must be versioned together. If a new model improves overall accuracy but hurts one key customer segment, the team should be able to roll back for that segment, provided the vendor has not already retired the older model.
- **Staff for a Marathon:** An AI product is a long-distance run, not a sprint. Short-burst "commando" builders are ideal for rapid prototyping, while steady "regular army" builders keep monitoring and maintenance running. A PM needs both and should deploy each at the right stage of the lifecycle.

**5\. Conclusion -** This session changed how I think about scalability. It is not the ability to handle more traffic; it is the ability to keep delivering the same value as usage, dependency and cost grow. A product manager has to watch unit economics, external limits and customer-level signals from the start, and grow the investment in scale as real adoption appears, without over-building too early or reacting only after the product starts to fail.

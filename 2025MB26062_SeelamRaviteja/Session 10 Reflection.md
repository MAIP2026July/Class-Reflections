# Session 10 Reflection

17 October 2026 | Seelam Raviteja | 2025MB26062

I used to hear "scalability" as an engineering word: more servers, more traffic, a bigger bill. This session moved it into the product column. Scaling is whether the promise still holds when far more people, and far more of their work, depend on it.

The ride-hailing example is the one I keep. The app can be up, fast, and returning clean responses, and the customer still stands on the road because no driver accepted the trip. Uptime was fine. The product failed. That is why the class kept pushing reliability up to the level of the outcome. If the dashboard only shows server health, the team will report a good week while customers have a bad one. I would now write the reliability target in the customer's terms first, such as a ride confirmed within a few minutes, and let the infrastructure targets follow from it.

The same promise changes as the product succeeds. Downtime that nobody minds during a pilot becomes an incident once a business runs its day on the product. Nothing in the code changed. The dependence did. This is the part I underweighted. A product can drift from convenience to mission critical without a release, and the support model, the testing depth, and the contract still reflect the old status. I would review the promise when usage patterns change, not only when the roadmap does.

Cost is where AI scaling bites differently from ordinary software. Every extra request carries inference cost, so a product that customers love can lose more money as it grows. Sending every query to the most capable model is the easy default, and it is a pricing decision made by accident. Routing the routine work to a smaller model and keeping the expensive one for the hard or high-value cases is not a technical trick. It is how the margin survives. The point I want to hold is that quality, latency, and cost have to be set together as one target range by the product owner. If the team is not given that range, each person optimizes their own dimension. Someone cuts cost and quality quietly drops, or someone chases quality and the bill doubles.

Latency got the same treatment. Faster is not automatically better. Predictable often matters more. A result that always arrives within a known window lets a person plan around it. One that is sometimes instant and sometimes very slow trains people to stop trusting it. Shared capacity makes this worse. When a heavy, low-priority job runs on the same resources as a time-critical one, the critical work stalls even though nothing is wrong with it. Separate queues, or at least clear priority, is a product decision about which customer waits.

External dependencies scale too. A provider's rate limit is invisible at pilot volume and becomes our customer's problem at real volume. Queuing, prioritization, and different service levels for different customers have to be decided before the limit is hit, not during the outage.

The operating side closed the loop. Monitoring, versioning, and rollback sound like engineering hygiene, but the signals should map to the promise. An unusual drop in electricity consumption is not just an anomaly on a chart. It may be an outage that customers are about to call about. For AI the version is not only the code. It is the model, the prompt, the data, and the provider behind the API. If the product's behavior changes and I cannot say which of those changed, I cannot fix it or roll it back.

What I will do differently is avoid two mistakes at once: building for massive scale before anyone depends on the product, and waiting until it breaks. Scale the controls with the evidence of dependence, and keep checking the promise, the unit cost, and the outside limits as usage grows.

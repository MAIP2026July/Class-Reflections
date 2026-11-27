# Session 10 Reflection

| | |
|---|---|
| Date | 17 October 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | Scaling AI products: cost, promises, latency, versioning, rate limits and model routing |

## 1. Key concepts
The professor started with the cost of AI, which isn't small any more. He mentioned that Accenture cut AI spending per person from about $1,000 a month to around $29. Nobody has a clear rule yet for when to use the top models and when not to. He also reminded us that product pricing is based on value, not effort, because we can't charge one customer for all our costs.

Scaling isn't only more users or more requests. It also means the same user using the product more, workflows getting more complex as customers plug us into their own processes, and customers becoming dependent on us. He compared it to forgetting your phone at home and feeling uneasy all day.

What I noted most was this: user expectations harden faster than infrastructure can catch up. Once a feature becomes critical to someone's work, the promise changes, and disclaimers in the terms won't protect us. Courts look at it from the consumer's side.

He said teams talk about servers, but customers buy promises. He suggested making a customer promise matrix. With Uber, the promise is a cab in three minutes. If the app is fast but drivers don't accept, the promise is still broken. We also need to plan for degraded modes and maintenance windows.

Latency and cost are part of the user experience. What feels amazing today becomes basic tomorrow, and most people won't wait more than a minute. Progress indicators or splitting work into steps can help. The team should know the sweet spot between quality, latency and cost. He suggested sending simple requests to small models, with a tiny model deciding the route. He warned that demos can cost $20–40 each in API calls, which can quietly eat the margin.

On releases, we should version software, data, models and experiments (he mentioned semver). We need to know how fast we can roll back a model that does worse for one segment, even though the old version may no longer be available. Lineage and traceability matter a lot in regulated industries.

Rate limits and queues only appear at scale. Then we have to decide who gets the fast lane and who waits, and monitor each group. His example was the Vande Bharat and Deccan Queen running at different speeds on the same track.

Two more points from him:
- **Automation.** Don't over-automate MLOps before the product is even meeting expectations. But alerts on product promises are the PM's job and shouldn't be handed off.
- **Team rhythm.** Hold meetings early enough for people to act, and don't depend on heroics: commandos can't do sentry duty forever.

He also told us grading will follow a strict bell curve with averages around 70%, and repeated that reflections must be our own thoughts and not written with AI.

## 2. What changed in my thinking
"Teams talk about servers, customers buy promises" changed how I describe VendorPulse. The promise isn't "an ML model with a 70% hit rate". It's "your dock will be staffed when the truck arrives".

## 3. How I will apply it
- **Promise matrix:** I'll write one for receiving leads. Their forecast is ready before the shift starts, they get an alert at least 30 minutes before a high-risk arrival, and if the model is down they still see the vendor's usual window.
- **Model choice:** the LLM is used only for chat and reading emails, with a small model for simple questions. This should keep the cost within my estimate of $14 per store per month.
- **Rollback:** I'll version each model and keep the previous one ready.

## 4. Open questions
- How do we decide when a question needs a large model and when a small one is enough?
- How do we roll back if the provider has already retired the old model version?

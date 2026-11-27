# Session 12 Reflection

| | |
|---|---|
| Date | 31 October 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | Writing a buildable PRD, diagrams as code, value-based pricing, unit economics and cost/accuracy/latency trade-offs |

## 1. Key concepts
The professor asked us to write the PRD as if we were paying a vendor to build it with our own money. One test is to give the PRD to an AI, ask it to build the product, and see what questions it asks and what it hard-codes. Anything vague becomes a contract risk and wasted money.

He went after vague words like "user friendly", "fast" and "beautiful", because they mean different things to different people. His line was that beauty is in the eye of the beholder. If we say "less consultation time", we should say how much less.

He also said the plan should run up to the first version we can sell, not list future versions. The PRD should show where AI is uncertain and where a human steps in.

He showed us diagrams as code: PlantUML swimlanes with roles, colours and icons, and Mermaid diagrams. He also showed the C4 model, where a PM mostly needs the context and container views, plus the deployment view to understand running costs. Trust points and uncertain results should be marked in the workflow.

For submissions, he asked for a clear team name and roll numbers, files named by what they are (PRD, prototype, business plan), and the whole thing written like a request for VC funding. PDF or Word is easier for people to read.

The pricing discussion was the most useful part for me:
- **Price backwards** from what the customer can pay, not forwards from what it costs to build.
- **Outputs versus inputs.** Customers like paying for results, while vendors prefer charging for effort or usage. He compared it to time and materials, fixed price and gain-share in IT services. Paying for outcomes wins more business if you can manage the risk.
- **Know what the customer is really buying.** With insurance, people buy a safety net, not a policy.
- **Hybrid pricing:** a base subscription with some usage included, then pay for extra.
- **Don't be greedy with light users,** or they'll downgrade or leave.

He described cost, accuracy and latency as a triangle, and said he'd later add trust as a fourth corner. You can route requests between cheap and expensive models, but shorter prompts can hurt accuracy. He also showed how architecture and finance are linked. Years ago, Oracle charged per database connection, so his team redesigned everything to go through one module. Agent loops need a limit so they don't run forever.

Finally, unit economics: know your gross margin and your overhead per unit at different volumes, and be able to explain it to a VC in a minute. He also talked about platforms and bundling.

Logistics: upload to the repo, then a freeze before the presentations on 14 November, with one presentation and a resubmission afterwards. He warned that grading will be tough.

## 2. What changed in my thinking
"Customers pay for outputs, vendors charge for inputs" explained why pay-per-API-call often feels unfair to customers. It made me check whether my per-store price is tied to something the store actually values.

## 3. How I will apply it
I'll go through the VendorPulse PRD and replace vague words with numbers, like "arrival window within 45 minutes" and "forecast ready by 6 am". Then I'll give it to an AI to see what questions it comes back with. My pricing ($99 per store per month, against about $5,100 saved per store) is worked backwards from customer value, and I could test a gain-share option in the pilot. Using a cheap LLM for simple questions and a separate ML model for predictions also protects the margin.

## 4. Open questions
- Would grocery chains accept outcome-based pricing when labour savings are hard to attribute?
- How much detail can a PRD have before it starts tying the engineers' hands?

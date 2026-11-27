# Session 8 Reflection

| | |
|---|---|
| Date | 3 October 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | AI instability, determinism, prototypes and MVP briefs, decision gates, generalising a product |

## 1. Key concepts
The professor shared his experience that AI coding tools can behave very differently from one day to the next, even with the same model. He thinks the cause is mostly on the provider's side. A model you host yourself should stay stable unless the seed or temperature changes.

A classmate from insurance explained why some work has to be deterministic. In premium rating, the same inputs must always give the same answer, and the company must be able to explain the decision to a regulator. Rules and calculations fit there, and LLMs or RAG fit elsewhere. Putting everything into one big vector store doesn't work well, so a mix is better.

One point I could relate to: the PM becomes the bottleneck. AI produces so many suggestions that it's tempting to just say "go ahead" without reading them. The professor's example was an AI that quietly assumed there would always be exactly three banks, and failed when he tested it with one.

He talked about reuse and resilience. Instead of building something new for every bank, build one engine driven by configuration. Markets change, and the opportunity can disappear before we get there. Different stages also need different people: someone who does well in a big company can struggle in a startup.

He asked us to write prototype and MVP briefs:
- Do we need a prototype at all, and who is it for?
- What evidence should it give us?
- What is the go/no-go decision?

Faking things for testing or with synthetic data is fine, but never fake things in front of a customer. Don't automate too early, don't hide manual work behind the product, and don't keep adding features forever.

He said decision gates should be learning moments, not bureaucracy, and the amount of process should match the size of the company. He gave parametric insurance as an example of reimagining: the payout arrives as soon as the rain is detected, without the customer filing a claim. And he pushed us to think about a tool built for one company being made generic enough to sell to the world.

## 2. What changed in my thinking
The bottleneck point is true for me. When an AI tool gives me ten suggestions, I accept the ones that look reasonable. The "always three banks" example shows how one hidden assumption can break things later.

## 3. How I will apply it
VendorPulse gives the same prediction for the same inputs for a given model version, and the LLM only explains. Each chain is set up by configuration (stores, vendors, dock hours), not code. I'll write a short MVP brief with clear go/no-go conditions for the pilot, for example a minimum share of arrivals inside the window and fewer associate-hours spent waiting.

## 4. Open questions
- How do we test a model provider's stability before relying on it?
- How much governance does a one-person startup really need?

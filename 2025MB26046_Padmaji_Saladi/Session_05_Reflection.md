# Session 5 Reflection

| | |
|---|---|
| Date | 29 August 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | Where AI adds value, build/buy/API, the AI stack, and designing for uncertainty and human review |

## 1. Key concepts
The professor opened by saying customers want to finish their job and leave. Unless they're there for entertainment, nobody wants to hang around in our product.

We need evidence that AI adds value. It fits best in work that is data-heavy, frequent and painful. His example was adding a new company division, which happens once in three years. That doesn't need a screen, let alone AI. What makes sense also changes as prices and technology change.

One story stuck with me. A team debated something for two weeks when a quick AI prototype could have settled it in 48 hours. He said PMs should be willing to pay for learning.

On build, buy or API, he said APIs are fast to start with but risky, because the provider or a government can cut access. Running open-weight models still means paying for hardware. What matters is owning the capability the customer values, not the model itself. He asked us to look at Porter's Five Forces as they might be in 18 months, not just today. He also talked about platforms and standards, like core ERP with industry packs on top, GTFS and Node.js.

He said a one-page PRD is a misunderstanding. We have to justify the investment in the product and in each feature.

On UX, he asked us to design for uncertainty. Show where the system is confident and where it isn't, give evidence, and never let the screen sound more certain than the model is. Plan for the LLM being slow or down.

On human-in-the-loop, decide when a human is needed, tell them why the item was flagged, and give them the data so they don't have to search again. Watch for people who just click "yes" because they're tired. If a person disagrees with the AI, ask for a reason.

He also reminded us that the PM owns the cost per token and the latency. Trust takes years to build and one bad incident to lose, like someone following a map onto an unfinished bridge. Don't scale until people use the product repeatedly, not just out of curiosity. Prompts need versions too.

## 2. What changed in my thinking
"Don't let the screen sound more certain than the model is" changed how I see dashboards. A single predicted arrival time looks very sure of itself even when the model isn't. A time window with a confidence level is more honest.

## 3. How I will apply it
VendorPulse already shows an arrival window and a confidence level instead of one exact time, and every answer shows its evidence. If the model is unsure or the LLM is down, it falls back to the vendor's usual window. I use a hosted LLM only for language tasks and keep the prediction model in-house, since that's what the customer is paying for. I also need to check whether receiving leads are actually reading proposed changes or just approving them.

## 4. Open questions
- How do we tell whether a reviewer is really thinking or just approving everything?
- When does moving from an API to an open-weight model start to pay off?

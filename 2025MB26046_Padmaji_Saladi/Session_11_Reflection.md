# Session 11 Reflection

| | |
|---|---|
| Date | 24 October 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | Ethics, risk and responsible AI: bias, privacy, hallucination, controls, governance and launch gates |

## 1. Key concepts
This session was on ethics and responsible AI. The professor compared a model trained on limited data to a child who has only seen one neighbourhood: it is biased without knowing it. Being aware of bias is the first step. He said ethical, fair products last longer, and shortcuts get exposed sooner or later. His examples were real:
- the Apple Card offering a husband and wife different limits;
- a traffic camera reading a guitar on someone's back as a pillion rider without a helmet;
- an eKYC system rejecting someone with small eyes for "closing their eyes".

He said fairness has to be defined for our own product. A single "fairness check" tick box isn't enough. We should decide the thresholds before launch and follow the law and industry rules. If we can't guarantee something, like no age bias, we shouldn't claim it.

On privacy:
- **Collect only what's needed**, for a stated purpose, with consent, as the DPDP Act and GDPR require.
- **Children's data and health data** are especially sensitive.
- **Retention:** decide how long data is kept and how it is deleted.

He said many PMs don't even know what data their own teams collect. He wants a section in our assignment on what data we collect, why, and for how long.

On hallucination, grounding answers in source documents (RAG) helps, and so does limiting the choices or simply saying "I can't answer this" and passing it to a person. He mentioned AI inventing company policies that don't exist. Human reviewers should see only what they need to decide.

Even if a human isn't part of the main flow, we need a shadow review every so often to check quality. Users should be able to ask for a review. He showed how bad AI hurts people: a wrong ETA makes someone turn back when they could have arrived on time. Someone also pulled a cart full of phones down an empty street and made Google Maps show a traffic jam.

On controls, he said never make a missing control look as if it exists. Committees can recommend, but the PM is accountable. Reviewers shouldn't be treated as free labour, and the PM should do some reviews personally to understand the effort.

His line on governance stayed with me: governance has to grow faster than the number of AI agents you run, without turning into bureaucracy. Audits should be for learning, not punishment. We also need to be ready for cyber incidents and communicate clearly when they happen. No product is bug-free at launch, so think about use, misuse and abuse, and write a launch checklist for your own context: what you need to launch, and what stops a launch.

## 2. What changed in my thinking
The point about governance growing faster than the number of agents made me think. A small team adding agents quickly could lose control without noticing.

## 3. How I will apply it
The VendorPulse reliability score affects real businesses, so I'll check it for bias against small local vendors.
- **Store-caused delays:** a late arrival caused by the store, like a closed dock, shouldn't count against the vendor. Vendors should be able to dispute their score.
- **Data:** I'll collect only delivery and scheduling data, no driver personal details, with a set retention period.
- **Honest answers:** the copilot answers only from delivery records and should say "I don't know" rather than make up a reason.
- **Launch checklist:** it will include a fairness check on the score, and a check that the score isn't misused to punish vendors.

## 4. Open questions
- What fairness threshold makes sense when vendors differ so much in size?
- How do we run shadow reviews without adding work for receiving leads?

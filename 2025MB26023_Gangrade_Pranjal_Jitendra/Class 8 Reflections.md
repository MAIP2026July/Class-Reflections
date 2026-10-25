# Reflection: Session 8

3 October 2026 | Gangrade Pranjal Jitendra | 2025MB26023

---

The sentence that stayed with me was that the product manager becomes the bottleneck, and the natural human response is to say go ahead.

That is already my pattern. Cursor proposes a change, I am tired, I approve it faster than I would a colleague's pull request. The faculty's own example was smaller and worse. He asked a model to test three banks. Later it treated three as a permanent rule and failed a one bank test. He had said the number once, for a test, and it became an assumption he did not catch until cleanup.

Helm will do this to the Regional Delivery Manager. Twenty five briefings a week, each with a recommended action waiting for approval. If we design the flow so that approving is one click and rejecting needs a reason, we have already chosen the outcome. Session 4 worried me that people would stop thinking. Session 8 named the mechanism. Volume plus fatigue plus a cheap yes.

**What I cannot babysit.** During development you see a bad answer, roll back, lose time, recover. In production you do not know which customer got the incomplete one. We are building on Agentforce. The faculty split two kinds of instability that I had been treating as one. Model probability, if it is wrong five percent of the time, stays roughly there. Provider instability is different. The same harness, same model, same prompt, suddenly does one step and stops, or runs all night. He believes vendors change things behind the scenes, sometimes to push newer models. I cannot babysit every weekly review. If the platform drifts, the RDM will still see a ranked list that looks as confident as last week's.

**Where I disagree.** Keeping vendors pluggable is the right discipline and we already said we own the judgement layer, not the model. In our case the lock in is not the API format. It is the sharing model, field level security, and the fact that the data never leaves Salesforce. Switching is a data problem, not a connector problem. I will keep writing that down as a trade off rather than as flexibility we do not have.

**What I will change.** Every approval in the prototype currently looks the same. High impact actions should be slower to say yes to than to say no to. And I will run the weekly review myself for the first few cycles, not as a demo, as customer support. Session 7 already told me to do that. This session told me why: I am the person whose go ahead will start leaking into production.

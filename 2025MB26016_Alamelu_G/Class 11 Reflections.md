# Reflection: Session 11

24 October 2026 | Alamelu G | 2025MB26016

---

This class made me think about the responsibility that comes with building AI products. Until now, I had mostly looked at AI from the perspective of what it can do, how accurate it is and how it can improve a process. But this session made me realise that there is another side which is equally important: what happens when AI makes a wrong decision, creates an unfair outcome or exposes information that should not have been shared?

**The point that stayed with me.** Bias is not always intentional. I liked the example of the child who assumes that all security guards are Gurkhas simply because that is what the child has been exposed to. The child is not necessarily wrong intentionally, but the limited exposure has shaped the child's understanding. The same thing can happen with AI models. If the training data is incomplete or represents only a particular group of people, the model can develop similar assumptions.

This made me realise that even when we don't intentionally build something discriminatory, our data and existing business processes can introduce bias into the product. The examples around recruitment, loan approvals and facial recognition made this more practical. A model may look like it is making decisions objectively, but it could still be rejecting or disadvantaging certain groups.

**Where I slightly disagree.** I understand the point that there is no universal definition of fairness and that completely eliminating bias may not be possible. But I feel this should not become a reason to accept biased outcomes. Even if we cannot achieve perfect fairness, we should at least be able to identify who is being disadvantaged, understand why it is happening and take corrective action. The suggestion to follow industry regulations as a minimum and then try to do better made sense to me.

**The privacy discussion was something I found very relevant.** One point I noted was that we should not collect data just because it is available. There should be a clear reason for collecting every piece of information. The example of an AI-based recruitment product was interesting. If we don't actually need someone's age or gender to evaluate their suitability for a role, why collect it in the first place?

The idea of data minimisation seems simple, but I think it can be difficult in organisations because teams often want to collect more data for future analysis or personalisation. The faculty also discussed consent, explaining the purpose of data collection and deciding how long the information should be retained. This made me think that privacy should not be something we look at only during compliance reviews. It should be considered while designing the product itself.

I could also connect this to the customer data we work with in marketing systems. We collect and use customer information to create segments and personalise communication. Just because we have access to certain customer data does not automatically mean we should use all of it. There should be a clear purpose and appropriate consent.

**The hallucination discussion also stood out.** We discussed how generative AI can produce answers that sound very convincing even when the information is not actually correct. The examples of AI inventing company policies and even providing court cases that don't exist were quite concerning.

I liked the suggestion that a product should know when to answer, when to abstain and when to escalate to a human. Earlier, I would have considered an AI product that refuses to answer as a product limitation. But now I think giving an incorrect answer with confidence can be much worse than admitting that the system does not know.

The discussion around RAG was useful too. Grounding responses in reference documents can help reduce hallucinations. However, we still need to identify which decisions require human review and what should happen when the system cannot provide a reliable answer.

**The responsibility part was probably the biggest takeaway.** Fairness, accountability and transparency should not just be statements in a product document. Customers should have a way to request a review or escalate a decision. Even when human review is not part of the main workflow, there should be a separate process to periodically check the quality of AI decisions.

I also found the discussion about visible controls interesting. Sometimes a product may technically provide options to users, but if those options are hidden or not explained properly, they are not really useful. Customers should understand the choices available to them and the trade-offs involved.

Another important point was that having a governance committee does not mean the product manager can transfer accountability to that committee. Domain experts can provide recommendations, but ultimately the product manager still has to take responsibility for the decision.

**The launch decision discussion made sense to me.** We cannot wait for a product to become completely bug-free before launching it, but we also cannot ignore serious risks just to meet a deadline. The faculty discussed looking at the probability and severity of a risk, whether it can be detected and whether it can be reversed. Depending on the situation, we may choose a limited rollout, add human review or temporarily stop a particular functionality.

I liked the point that governance should not turn into unnecessary paperwork. It should help teams identify risks and make better decisions rather than becoming another approval bottleneck.

**What I will take forward.** For our own AI product, I want to think about the risks beyond just whether the model works correctly. We should identify possible misuse cases, understand what data we are collecting, define consent and retention requirements, check for potential bias and decide what happens when the AI gives an unreliable answer. I also want to include a proper risk and launch checklist instead of making generic statements about responsible AI.

**Open question.** I am still thinking about how much responsibility a product manager should take when the underlying AI model is provided by an external vendor. We may not know exactly how the model was trained or what biases it already contains. But the customer is still using our product and will hold us responsible for the outcome. So how do we establish enough confidence in something that we don't completely control?

# Session 12: They pay for output, we pay for input

31 October 2026 | Neetesh Jain | 2025MB26095

---

Customers will pay for the value they got out. Our cost is the tokens, the calls, the compute that went in. Those two are not the same thing, and the gap is our risk.

API pricing is input pricing. You ask a model a question, it burns tokens, it hallucinates or loops, you still pay. The faculty has done this himself, fallen in love with Claude, hated it, switched to Codex, switched back. Outcome pricing can charge more, because it sits next to the customer's gain, but then you carry conversion. A real estate lead that used to earn a few hundred rupees could earn a lakh if you take a share of the sale, and nothing if there is no sale.

I own the economic model and I had been pricing Helm like a services contract. Cost to run a review, plus a margin. That is time and material wearing product clothes. The RDM does not want a review. They want fewer late surprises. If we charge per conversation with Agentforce, we are billing the input. If usage goes up because they love it, inference cost shoots up and we stop loving our own product. Session 7 said if the product works the customer needs less of it. This is the twin. If they use it more, we lose on the cost side instead of the price side.

**Work backwards.** The Japanese target cost idea is older than this course and I have still been doing the forward version. Add up what it costs, add profit, hope the buyer agrees. If you are overpriced you panic. If you are underpriced you have left money on the table. Session 2 I wrote that nobody ever told me what anything earned. Session 7 I wrote that I had never read a client's annual report. This session is the method I kept agreeing with and not using. Start from willingness to pay. Subtract the margin we need. What is left is the maximum we may spend to serve one review. If Agentforce cannot fit inside that number, the architecture is wrong, not the sales story.

**Finance decides the shape of the system.** Oracle used to charge per connection, so they funnelled every query through one module. Later it was per CPU core, so nobody was allowed their own database. I have treated architecture as a technical preference. Here the bill wrote the diagram. Our per conversation cost will write ours. A multiplexer that sends easy cases to a cheap path and hard cases to a dear one only works if the extra tokens to rebuild context do not eat the saving. That is a product decision sitting in the economics note, not an engineering trick sitting in the spec.

**What I will put on one slide.** Unit economics, and which path through the workflow actually contributes margin. No action, ask for clarification, escalate. If escalation is the expensive path and also the valuable one, advertising it without a cap is how every new customer weakens the firm.

Name - Gokulkrishnan N

Registered No - 2025MB26210

Management of AI products

**11th Session Topic:** Responsible AI – Bias, Privacy, Hallucination, Accountability, and Risk-Based Launch Decisions.

**Management of AI Products – Class Reflection**

**1\. Class Overview** This session moved responsible AI from a set of slogans into concrete product decisions. The class discussed how bias enters models without anyone intending it, why data should be collected only when there is a clear purpose, how to design systems that admit when they do not know, and how to decide whether a product with known risks is ready to launch. The recurring message was that responsibility for the outcome stays with the product team, even when parts of the system come from vendors or committees.

**2\. Key Concepts and Discussions**

- **Bias Comes from Exposure, Not Intent:** The example of a young child forming assumptions about people from the limited set of people they see every day explained how models learn bias. A model trained on incomplete or historically skewed data repeats those patterns, which matters most in hiring, lending and facial recognition. Perfect fairness may not exist, but that is not an excuse to ignore measurable gaps between groups.
- **Organisations Are Trustees of Data, Not Owners:** Under India's DPDP Act and Europe's GDPR, a company holds user data on trust. Collecting attributes like age, gender or passport numbers "just in case" adds legal and security risk without adding value. The example of a job portal asking for a passport number on the very first application form showed how common this mistake is.
- **Designing for "I Don't Know":** Generative AI can invent company policies or court cases that sound completely believable. Grounding answers with RAG reduces this, but the system also needs a deliberate path to abstain, fetch better evidence or hand over to a human. A confident wrong answer is far more damaging than an honest refusal.
- **Data Poisoning Is a Real Threat:** The story of someone pulling a cart of 99 phones down an empty street, which made Google Maps show a traffic jam, showed how easily input data can be manipulated. AI products need sanity checks against deliberately misleading input.

**3\. Important Insights**

- **Transparency Must Show Up in the UX:** A disclaimer saying "AI can make mistakes" is not enough. If a decision affects someone, the product should explain the decision, show the controls available and offer a clear way to challenge it. A control hidden deep in settings provides almost no real protection.
- **Human Oversight Needs Real Ownership:** Placing a human in the loop does not make a system responsible by itself. The team must define which decisions need review, who owns the final call, and how a sample of AI decisions gets checked on a regular schedule, even when no human reviews every single one.
- **Governance Does Not Transfer Accountability:** Legal teams, domain experts and review committees can flag risks and suggest controls, but the product manager still owns the decision. Governance also has to keep pace with the number of AI agents being deployed. A slow committee that meets months later, or one run on unpaid extra effort, becomes paperwork instead of protection.
- **Vendor Models Are Still Our Responsibility:** When a third-party model misbehaves, the customer blames our product, not the vendor. Vendor evaluation, monitoring, version tracking and fallback paths are therefore part of the product's responsibility.

**4\. Practical Learnings**

- **Risk-Based Launch Triage:** Instead of waiting for zero risk or launching blindly, each open risk can be scored on four factors: **likelihood**, **severity**, **detectability** (would we even notice a silent failure?) and **reversibility** (can the damage be undone?). Based on the score, the right move may be a limited rollout, added human review, disabling one feature, or delaying the launch.
- **Data Minimisation Checklist:** For every data field, the PRD should answer three questions: why is it needed, what consent covers it, and when it will be deleted. Data that cannot be justified to a regulator should not be collected.

**5\. Conclusion -** This session showed that responsible AI is about designing for the cost of being wrong. Accuracy and business value still matter, but a mature AI product also has to answer who could be disadvantaged, what data is used and why, what happens when the system is unsure, and who is accountable when it fails. Building these answers into the product before launch turns governance into everyday product work instead of a last-minute compliance step.

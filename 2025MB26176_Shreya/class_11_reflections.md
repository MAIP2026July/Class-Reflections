## Class 11 -- Developing Responsible AI Through Ethics, Privacy and Governance (24 October 2026)

The session started with an introduction to the new lab, Prayogshala,
and some explanation of how we were expected to use it. Our professor
said that it would be more suitable for developing conventional machine
learning models than for agentic product development or embedding
generative AI into applications. The discussion then moved to ethics,
bias, privacy and responsible AI.

The professor's explanation of **Bias** was easy to relate to. He
described a child who has only ever seen Gurkha security guards and
consequently assumes that every security guard must be a Gurkha. The
child is not intentionally judging anyone unfairly; the conclusion comes
from having limited exposure. AI systems can develop similar patterns
when the datasets used to train them do not represent the wider
population.

I understood that bias does not always result from a deliberate choice.
It may be present in the data collected, the labels assigned to that
data, organisational policies or the workflows used to make decisions.
Identifying these possible sources is an important starting point for
reducing unfair outcomes.

When Gautam asked whether one accepted framework could be used to manage
every form of bias, our professor explained that no single framework is
sufficient in every situation. Organisations should follow relevant laws
and industry guidance while continuing to review and improve their
practices. This matters because guidelines can also contain outdated
assumptions or reflect existing biases.

The next topic was **Privacy and Responsible Data Collection**. The
professor's advice was to gather only information for which the
organisation can provide a clear justification if questioned by a
regulator. If a product does not need a customer's age, gender or even
name, there may be no reason to collect it. Data that is never collected
cannot later be used by an AI system to influence a decision.

He also stressed that organisations should explain why information is
being collected and obtain the appropriate consent. Health information
and children's data call for additional safeguards. India's DPDP
framework and GDPR impose responsibilities on organisations handling
personal information. The professor reiterated that customer data is
held in trust rather than owned by the organisation, and that requests
for deletion must be managed in line with the applicable requirements.

His phrase **"data is a drug"** was memorable. It described the tendency
of organisations and development teams to keep collecting more
information even when they cannot clearly explain why it is needed. I
realised that responsible product design also means having the
discipline to decide what not to collect.

We also explored practical methods for reducing **AI Hallucinations**:

-   **Ground Responses Through RAG:** Use relevant and dependable
    information sources to support the model's responses.
-   **Limit the Available Options:** Where a task requires controlled
    outputs, restrict the choices the model can make.
-   **Answer, Abstain or Escalate:** Design the system to answer when it
    has sufficient support, refrain from answering when it does not, or
    send the case to a human for review.

I found the final approach especially important because it challenges
the expectation that an AI system must always produce an answer.
Choosing not to answer can be the responsible decision. It can also
inform a fair pricing approach: a business may decide not to charge when
the system has not provided a useful result.

The discussion about **Governance** left me with two key principles:

-   Governance processes need to develop at a pace that keeps up with
    the growing number of AI agents being introduced.
-   Committees can review and advise, but the Product Owner remains
    responsible for the final outcome.

Our professor also cautioned against governance becoming a documentation
exercise with no practical effect. If participants cannot explain why a
review exists or what it protects, the process may become "governance
theatre". Reviewers should also be given enough time and recognition to
carry out their responsibilities properly. If reviews are treated as
unpaid extra work, there is a risk that people will approve submissions
without examining them carefully.

For **Risk Assessment**, I learned that probability and severity are not
the only factors to consider. We should also ask whether a problem can
be detected and whether its effects can be reversed. The professor
highlighted the need for an incident communication plan as well. His
example of telling people that they were safe if they had not received
an email by 7 a.m. showed how clear communication can prevent avoidable
anxiety and confusion.

**Application to Our Project:** We were asked to add a specific section
describing the information our product collects, the way consent is
obtained, the period for which data is retained and the regulatory
requirements relevant to the industry. We also had to prepare a
launch-gate checklist that separates essential launch conditions from
issues that would prevent release. The expectation was to make these
details relevant to our own product instead of relying on generic
statements about responsible AI.

**My Personal Reflection:** A small but useful point from the class was
the professor's repeated request that we avoid using the word *user*
without explaining which person or role we mean. I noticed how often I
write phrases such as "business users" in my own documents. It would be
clearer to identify whether I mean a finance executive, administrator,
customer-support representative or another specific stakeholder.

Overall, I learned that responsible AI involves much more than
preventing bias or meeting privacy requirements. It calls for careful
choices about data, transparency, error handling, accountability and
risk across the product life cycle. Governance should protect customers
and the organisation without becoming so burdensome that it obstructs
useful innovation.

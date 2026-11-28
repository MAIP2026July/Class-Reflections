## Class 5 -- Finding AI Opportunities and Designing Products for Uncertainty (29 August 2026)

The lecture had two broad parts. The first dealt with recognising
business problems where AI might offer value. The second considered how
to design products that account for the uncertainty associated with AI.

When looking for opportunities, we discussed signals such as operational
difficulties, lack of trust, repetitive work, decisions that require
considerable effort and processes that produce large amounts of data.
These signals can point towards possible opportunities, but they are not
proof that an AI solution is needed. The important question is: **What
evidence supports the opportunity?** Our professor stressed that teams
should not simply promise that AI will make a process better. They
should run experiments, measure the results and preserve the evidence. I
took away that validating assumptions is a core part of product
management.

The intranet example made the point particularly clear. A team wanted to
create a full interface for managing group, division and company
structures. When asked how often those structures changed, the response
was once every two or three years. The professor explained that a simple
back-end update could handle the requirement without the cost of
building a complete interface, testing it and managing access. This
showed me that a manual process does not automatically need to be
automated. If an activity happens rarely and has limited impact, the
effort of building a solution may not be justified. **The materiality of
the problem matters.**

The discussion about **Build vs. Buy vs. API/Subscribe** connected
closely with my professional experience. An external API can reduce
development time, but it can also make the product dependent on a
provider and limit control over the underlying technology. Using an
open-weight model on our own infrastructure may look like building, but
in practice it can resemble buying: even if the model itself is
available at no cost, hosting, operating and maintaining it still
require resources. Selecting between AI platforms, including
OpenAI-style and Anthropic-style APIs, is therefore a strategic choice
because it can affect future flexibility and the risk of vendor lock-in.

The second part focused on building AI products that can respond
appropriately when the system is uncertain. My main takeaways were:

-   **Choose Deliberately Whether to Reveal AI Involvement:** Making AI
    visible to customers should be a conscious product decision, not an
    automatic design convention.
-   **Be Clear When Confidence Is Low:** If the system is unsure, it
    should be able to communicate that uncertainty, request more
    information or explain that it cannot provide a dependable response.
-   **Design Fallbacks in Advance:** Alternative ways of completing a
    task and clear error messages should be part of the initial design,
    rather than being added only after something goes wrong.
-   **Do Not Present Uncertain Results as Certain:** An interface that
    makes doubtful information look definitive can lead customers to
    trust it too much. Once they encounter incorrect results, their
    confidence in the wider product may also decline.

One observation from the professor stayed with me. Conventional software
development has established methods for writing test cases and tracking
coverage. Comparable discipline is not always applied consistently to AI
systems. When developers or data scientists are asked to share test
cases for a generative AI feature, they may say that they tried a couple
of prompts. I understood that this level of informal experimentation is
not adequate for a product expected to behave reliably for real
customers.

The suggested prompt structure was also practical: **Role, Context, Task
and Constraints**. These elements help define what the AI is expected to
do and the limits it must respect. The professor also questioned why
chat interfaces do not commonly offer separate fields for these four
elements, which could help people give clearer instructions.

I also learned that a prompt included in a product is not simply an
instruction written once and forgotten. It affects how the product
behaves and is therefore part of the product experience and the promise
made to customers. Prompts should be maintained and version-controlled
with the same care as other product components.

**My Personal Reflection:** This class showed me that spotting an AI
opportunity and delivering a dependable AI solution are separate
challenges. The opportunity must be backed by evidence, and the product
must be designed to cope with uncertainty instead of assuming every
response will be correct. The discussions on provider dependence and
prompt versioning were especially relevant because they affect the
long-term maintenance of AI applications.

I also realised that reliability does not come simply from choosing a
powerful model. It depends on disciplined testing, suitable fallback
options, honest communication and ongoing checks of how the system
behaves.

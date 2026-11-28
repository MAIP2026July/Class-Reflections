## Class 12 -- Improving Product Documents, Technical Visualisation and Monetization (31 October 2026)

The class began with a live review of one team's project submission.
Although the comments were directed at that group, I found the feedback
relevant to our own work because the same standards can be applied
across projects.

The main message was that a **Product Requirements Document (PRD) should
be prepared with the seriousness of a contract given to an external
vendor**, particularly when the organisation is investing its own money.
Words such as "accurate", "user-friendly", "time reduction", "unsafe
output" and "high risk" are too open to interpretation. A vendor may
understand these expressions differently from the customer.

Our professor recommended turning broad expectations into measurable
requirements. For instance, rather than asking for processing time to be
reduced, we could set a target reduction of 30%. He also suggested
keeping target values in a separate column so they can be revised later
without rewriting the underlying requirement.

We were advised not to build unnecessary fixed assumptions into the
product. A system designed to work with only 12 medicines, for example,
may become difficult to extend when more medicines need to be added.
Workflows should also be documented clearly from the outset, even if
certain details are adjusted after the pilot.

The PRD should show precisely which stages of the workflow use AI. For
every AI-enabled activity, we should define the expected level of
reliability, running cost, method of communicating uncertainty and need
for human involvement. Simply stating that a product uses AI does not
explain how AI contributes to the solution or what responsibility it
has.

One suggestion I found particularly practical was to **give the PRD to
an AI system and ask whether it contains enough information to build the
proposed solution**. We should ask the system to list the questions it
would need answered before development could start. If the document
leaves several questions unresolved for the AI, a human vendor is likely
to face similar gaps. This can help us improve the document before
development begins.

The class also introduced **PlantUML and Mermaid**, tools that let us
create diagrams through text-based descriptions. We discussed swimlane
diagrams, in which each lane represents a participant or component, such
as a patient, doctor, system or AI. These diagrams make it easier to see
who performs each activity and where hand-offs take place.

I found text-based diagrams useful because they can be stored in Git,
reviewed and compared through version-control changes. We were also
introduced to the **C4 Model** for communicating software architecture.
Our professor explained that Product Managers generally need to
understand the system context and container views, rather than becoming
involved in every low-level technical detail.

Another recommendation was to prepare project material in Markdown so
that AI tools can process it easily, while also generating PDF versions
for people to read. This highlighted the value of making information
accessible in formats suited to both automated systems and human
readers.

The second half of the class focused on **Monetization and Product
Economics**. My main takeaways were:

-   **Target Costing:** The Japanese target-costing approach begins with
    the amount a customer is willing to pay. The desired profit is
    deducted from that price, and the balance becomes the maximum cost
    the organisation can afford for developing and delivering the
    product. This reverses the approach of calculating costs first and
    adding a margin afterwards.
-   **Customers Value Outcomes, While Providers Manage Inputs:**
    Customers generally pay for the result they receive, whereas
    providers incur expenses through resources and inputs. A customer
    may prefer outcome-based pricing, while a vendor may favour a Time
    and Material (T&M) arrangement. A provider that can manage the risks
    of delivering a defined outcome may be better positioned to win
    business.
-   **Include Inference Expenses in High-Usage Scenarios:** A product
    that succeeds may attract substantial usage, but more usage can also
    increase inference costs. Pricing should therefore be tested against
    heavy-use customers rather than being based only on average
    consumption.
-   **Offer Flexible Options to Retain Low-Usage Customers:** Customers
    with limited usage should not automatically be treated as
    relationships that are not worth retaining. A lower-cost plan or
    downgrade option may preserve the relationship instead of losing the
    customer altogether.
-   **Connect Architecture with Commercial Costs:** The professor used
    examples involving Oracle to show how licensing arrangements can
    shape technical architecture. In one situation, database requests
    were routed through a single module because the licence was charged
    per connection. In another, databases were consolidated because the
    licence cost depended on CPU cores. These examples showed why
    architects need to understand financial constraints as well as
    technical requirements.
-   **Understand Contribution Margin and Unit Economics:** Profitability
    should be considered at the level of individual workflow paths and
    customer groups. A Product Manager should be able to explain the
    product's unit economics clearly and briefly, including in a
    conversation with a potential investor.
-   **Recognise the Value of Platforms and Networks:** A platform can
    become more useful as more participants join its ecosystem. Its
    advantage may come from the value created by the network as a whole,
    not only from the core product.

**My Personal Connection:** The Oracle licensing discussion was familiar
to me. Through my experience with data platforms, I have seen how
licensing expenses and connection limits can influence decisions about
database access and integrations. In some situations, commercial
constraints have a greater impact on architecture than technical
preference. This helped me connect the professor's discussion of
economics with real technology environments.

**My Personal Reflection:** This class reinforced that Product
Management requires attention to documentation, technical design and
financial sustainability at the same time. A well-defined PRD reduces
ambiguity, diagrams help teams understand workflows, and pricing and
monetization choices determine whether the product can be sustained
commercially. A product must solve a customer problem, but its
architecture and delivery model must also make financial sense.

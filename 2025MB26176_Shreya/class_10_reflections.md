## Class 10 -- Scaling AI Products Without Breaking the Customer Promise (17 October 2026)

The class opened with a reminder about the assessment process. Our
professor explained that grading would follow a strict bell curve, with
an expected average of around 70%, and that late submissions would not
be accepted. The discussion then turned to scaling AI products. One
statement stood out to me: **if a team spends all its time discussing
servers and forgets the promise made to customers, it is overlooking an
important responsibility.**

Our professor explained that every product sets an expectation for its
customers. That expectation becomes especially important when the
product is part of their everyday routine. WhatsApp, for example, does
not charge users a subscription fee, yet people can become frustrated if
it is unavailable for even an hour. Customers judge the product against
the experience they have come to expect, not only against the formal
terms and conditions.

To manage this, the professor introduced a **Customer Promise Matrix**.
An organisation should define what it commits to delivering for each
customer segment and then measure whether it is meeting that commitment.
For example, Uber might create an expectation that a cab will arrive
within three minutes. Measuring server availability alone would not
establish whether that customer-facing promise is being fulfilled.

The main subject was the **Latency--Cost--Quality Trade-off**. Our
professor explained that deciding the acceptable balance among these
three dimensions is a Product Management responsibility. A Product
Manager might set a requirement that a response should arrive within 45
seconds, meet a minimum quality standard and stay within a defined cost
limit.

If those boundaries are not clear, different teams may optimise for
different outcomes. One person may choose a smaller model to improve
speed, while another may prefer a more expensive model to achieve higher
answer quality. I understood that the Product Manager must define
acceptable limits so that technical choices support the same product
objective.

I also found the example of choosing **predictability instead of maximum
speed** interesting. A product might take a few extra seconds to run a
final clean-up step so that response times are more consistent. This
reinforced the idea that the quickest possible response is not always
the best experience.

Other lessons from the session included:

-   **Version Every Component That Affects Behaviour:** Versioning
    should include application code, data, models, prompts and customer
    segments. Reverting an AI product can be difficult if an earlier
    model version has already been withdrawn by the provider.
-   **Prepare for Queues and Rate Limits:** These issues often appear as
    usage increases. Organisations may need service tiers, fair-use
    rules and monitoring by customer segment. The professor used Vande
    Bharat and passenger trains sharing railway tracks to explain how
    different service levels can be managed.
-   **Prevent Noisy-Neighbour Problems:** In a shared, multi-tenant
    environment, unusually high usage by one customer can affect the
    performance experienced by others. This risk should be considered in
    the system design.
-   **Control Model and Operating Expenses:** Smaller models should be
    selected when they can meet the required quality level. Model
    routing and caching can also help protect margins. Caching must be
    designed carefully, however, because reusing one customer's response
    for another could expose private information.
-   **Do Not Rely Only on Exceptional Effort:** Building and operating
    an AI product is an ongoing activity. Teams need people assigned to
    the right responsibilities instead of depending on a few individuals
    to handle every urgent issue. The professor used the contrast
    between "commandos" and "army" personnel to explain why different
    kinds of work need appropriately organised teams.

**My Personal Connection:** The discussion of rate limits reminded me of
a recent issue I had experienced. A system reached its connection limit
and rejected new sessions immediately instead of placing them in a
queue. This helped me see the difference between two experiences from
the customer's point of view: receiving an immediate failure or waiting
around 30 seconds for the service to become available. The technical
cause may be similar, but the product experience is very different.

**Application of the Class Exercise:** We were asked to identify tasks
that could be handled by smaller models and those that might need more
advanced frontier models. My understanding is that smaller models can
often manage structured activities such as classification, routing,
extracting fields and producing summaries in a fixed format. More
capable models may be needed for open-ended reasoning, multi-step
planning or customer-facing tasks with serious legal or financial
implications. Such use cases may also need appropriate human review.

**My Personal Reflection:** I understood that scaling is not simply a
matter of adding infrastructure or processing a larger number of
requests. It means continuing to provide the experience and reliability
customers expect as usage and operational complexity increase. Product
Managers must make deliberate choices about speed, quality and cost
rather than leaving each team to optimise one factor independently.
Successful scaling means keeping the customer promise intact as the
product grows.

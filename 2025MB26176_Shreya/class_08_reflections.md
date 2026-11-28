## Class 8 -- Moving from Prototype to Scale Through Evidence-Based Progress (3 October 2026)

This was our first class after the midterm examination. We began with a
subject I had come across in my own work but had not previously examined
in a structured way: **Provider Instability**.

Our professor explained two distinct forms of uncertainty. The first is
the usual probabilistic variation in an AI model's outputs. For example,
if a model produces an incorrect result about 5% of the time, we might
expect a similar error rate under comparable conditions. The second is
instability caused by the provider. A vendor may change something in the
background, causing the same prompt, application and test setup to
behave differently without any change on our side.

The professor described an example in which an AI agent was instructed
to keep working towards a goal but stopped after completing just one
step. He connected this behaviour to a Kannada saying about a donkey
taking only one step after each beating. The example was amusing, but it
highlighted a serious concern. During development, a team may notice a
problem and revert a change. In production, the situation is more
difficult because the team may not know which customers have already
received unreliable results.

Another concept that stood out was **Assumption Drift**. Our professor
described asking an AI system to test a process involving three banks.
The system silently interpreted the instruction as meaning that there
would always be exactly three banks. When the scenario was changed to
include only one bank, it failed.

This demonstrated how AI can introduce assumptions that were never
explicitly stated. Such assumptions can go unnoticed if Product Managers
review the outputs superficially and approve them without checking the
underlying logic. The professor also cautioned that a Product Manager
can become a bottleneck if every decision has to pass through them. When
work is under pressure, they may respond with a quick "fine, go ahead",
allowing flawed assumptions to enter the product.

The main subject of the session was the progression **Concept →
Prototype → MVP → Pilot → Scale**. The key principle was that a team
should demonstrate that it has met the objectives of one stage before
receiving the go-ahead to move to the next.

A prototype is mainly a learning tool. It helps test an idea and
demonstrate how a possible solution could work. An MVP, in contrast,
should be usable by actual customers so that their feedback can guide
the next steps. We also discussed different prototype types, including
concept, UI, data and workflow prototypes.

The discussion of **Wizard of Oz MVPs** was especially interesting. In
this method, a person may carry out work behind the scenes while the
customer believes it is being performed by an automated system. Our
professor drew an important distinction: human assistance can be part of
an early product, but concealing that involvement from customers is not
acceptable. Manual support can help validate demand and workflows,
provided the product is transparent about how the service is delivered.

Other practical lessons from the lecture were:

-   **Keep Provider Options Open:** AI products should be structured so
    that changing providers is manageable. Different providers may use
    different API formats and capabilities, so the architecture should
    avoid unnecessary dependence on one vendor.
-   **Set Evaluation Conditions in Advance:** A short prototype or MVP
    brief should state its purpose and success measures clearly. This
    reduces the risk of disagreement later about what the team was
    expected to demonstrate.
-   **Introduce Automation Gradually:** Where reliability is not yet
    established, manual alternatives should remain available. Automation
    can expand as the solution demonstrates that it performs
    consistently.
-   **Make Governance Useful and Proportionate:** The discussion
    included Jaydeep's point about excessive ISO/CMM documentation. I
    understood that governance should strengthen quality, accountability
    and consistency instead of becoming paperwork that adds little
    practical value.
-   **Create a Reusable Product Rather Than a One-Customer Solution:**
    Our professor challenged the idea that a provider should be stopped
    from selling the same solution to other organisations. He
    recommended building a common product foundation and handling
    customer-specific needs through configurations or separate add-ons.
    This makes it possible to serve a broader market rather than turning
    the work into a project for one customer.

**How I Intend to Use This at Work:** In our chatbot-related work, I
have already seen cases where the same prompt produces different
responses under different circumstances. This class showed me that
informal observation and a quick judgment that an answer "looks right"
are not enough. I want to maintain a small, consistent test suite and
rerun it whenever the underlying model or service provider changes.
Comparing the results should help us detect behavioural differences
systematically and gather evidence before approving a version for
production.

**My Personal Reflection:** I learned that AI product development should
advance through demonstrated learning, not assumptions or pressure to
release quickly. Every stage, from prototype through scale, should
provide enough evidence to justify the next investment. Flexibility,
transparency and disciplined testing are particularly important when a
product depends on external AI providers.

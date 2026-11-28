## Class 9 -- Choosing Metrics That Reflect Business Value and Trust (10 October 2026)

This class was about evaluating AI products and selecting measures that
reflect actual business performance. The exercise I remember most
clearly was a live Excel activity in which our professor built a loan
payoff matrix. It demonstrated why model accuracy by itself cannot tell
us whether a solution will be commercially successful.

The example involved a bank issuing a loan of ₹1 lakh at a 2.5% spread.
If the borrower defaulted, the bank would lose the full principal. By
changing the values assigned to the four possible outcomes in the
matrix, the professor showed that a model with accuracy above 90% could
still result in a financial loss. A model with lower accuracy could, in
some circumstances, produce a profit.

The reason was that different prediction errors have different financial
consequences. One bad loan could cancel out the earnings from around 40
successful loans. This helped me understand that an accuracy percentage
does not reveal whether a model is beneficial to the business. We need
to calculate the impact of both correct and incorrect decisions.

During the discussion, Jaydeep proposed recall as the suitable metric
for the example. The professor, however, avoided presenting precision or
recall as a universally correct answer. He asked us to assign a monetary
value to every outcome in the matrix, identify who gains and who bears
the loss, and evaluate the model using the economics of the business.

I found both perspectives useful, but as an MBA student I related
particularly well to the financial approach. Translating model outcomes
into monetary terms makes the assessment more practical and prevents us
from choosing a metric simply because it makes the model appear
successful. It also helps an organisation estimate how much it should
invest in improving performance.

Other important lessons were:

-   **Extreme Losses Can Outweigh Average Results:** The professor
    discussed how severe wildfires in California created substantial
    losses for insurance companies. The casino example made a similar
    point: probability calculations may assume that a game can continue
    indefinitely, but a real player or business can run out of money.
    Companies must assess whether they can withstand extreme outcomes,
    not just whether average results appear favourable.
-   **Revisit Metrics as the Product Changes:** Revenue may continue to
    rise even while new customer registrations fall. If a team tracks
    the same measures from launch without reviewing them, it may miss
    important changes in customer behaviour. The measures used should
    evolve with the product and its priorities.
-   **Who Bears the Cost of an Error Matters:** The party that faces the
    financial consequences of false positives or false negatives has a
    strong reason to focus on those errors. The banking example showed
    how fraud detection became a higher priority when regulations made
    banks responsible for the resulting losses.
-   **Metrics Can Create Unintended Incentives:** If testers are
    rewarded only for the number of defects they discover, they may be
    encouraged to delay reporting issues. This reminded me that a metric
    can lead to undesirable behaviour if its incentives are not
    considered.
-   **Be Careful When A/B Testing AI Products:** Such tests can be
    difficult to interpret because an external provider may be running
    its own experiments or changing model behaviour at the same time. A
    rise in customer satisfaction, for example from 4.5 to 4.8, should
    not automatically be treated as proof of improvement. Sample size
    and statistical significance must also be considered.

**A Point Where My View Differs Slightly:** Our professor suggested
limiting the number of metrics and beginning with three. I agree that
tracking too many measures can make decisions harder. However, I believe
that an AI product should include at least one explicit measure of
quality or safety among those key metrics. Otherwise, teams may focus
mainly on speed and cost while giving insufficient attention to
reliability and the impact of incorrect responses.

**How I Intend to Use This at Work:** For our finance chatbot, I want to
assess incorrect answers according to their real-world consequences.
Instead of sharing only an accuracy figure, I would like to understand
how a wrong response could affect a customer's time, finances or
decisions. This would make performance discussions more useful to
business stakeholders and help explain the need for investment in
quality improvements.

**My Personal Reflection:** This lecture changed the way I think about
measuring AI performance. A model may look impressive technically and
still fail to create business value. Product Managers need to connect
technical measures with commercial outcomes, understand the cost of
different errors and select metrics that encourage the right decisions.

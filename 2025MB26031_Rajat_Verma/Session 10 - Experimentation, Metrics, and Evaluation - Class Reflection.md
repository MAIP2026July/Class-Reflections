# Class Reflection – Session 10 of 16: Experimentation, Metrics, and Evaluation

Management of AI Products  
Faculty: Vinaya Sathyanarayana  
Rajat Verma  

## What the session covered

- **Why AI Metrics Differ:** Metrics that change decisions versus decorate dashboards
- **Core Classification Metrics:** Precision, recall and error cost in product terms
- **Business Lens on Evaluation:** Model quality meets trust, growth and ops burden
- **A/B Testing in AI Products:** Threshold and rollout logic you would approve
- **Feedback Loops:** Offline evidence, online proof, continuous correction
- **Metric Design Activity:** Which metric pair should drive the next move

## Key ideas and cases

### Ideas that stayed with me

- **Errors have owners:** Ask who pays for false positives and who pays for false negatives, then set the threshold.
- **Model metrics are not enough:** Better offline scores can hide worse user value, higher review burden or fragile online behaviour.
- **Feedback loops can trap you:** User feedback improves models, but can also reinforce bias if it only reflects what the model showed.

### Cases that made it concrete

- **Stripe Radar:** Precision vs recall is a business choice between lost sales and fraud loss.
- **PayPal fraud prevention:** Model quality is judged by loss avoided and customer friction together.
- **Booking.com experiments:** A culture of controlled tests turns opinions into evidence.
- **TikTok / Waze loops:** Feedback loops can sharpen the product or lock in a bias.

## How my thinking shifted

| Before this session | After this session |
| --- | --- |
| Accuracy is the headline metric | Error cost by type is the headline metric |
| Offline evaluation proves readiness | Online A/B evidence proves real impact |
| Dashboards should show everything | The front row shows the metric pair that drives decisions |

## Applying it to my work

- **Threshold memo for fraud:** Document the trade-off between false declines (lost GMV) and fraud loss for each merchant segment.
- **Pair model and business KPIs:** Report recall alongside approval rate and manual-review load.
- **Guard against loop bias:** Hold out a random sample from model-driven decisions to keep labels unbiased.

## Key takeaway

> Good AI evaluation protects the product by clarifying trade-offs before they become incidents.

## Question I am still exploring

How do we run A/B tests on risk models when a bad variant causes real financial loss?

# Class Reflection – Session 06 of 16: Data Fundamentals for Product Managers

Management of AI Products  
Faculty: Vinaya Sathyanarayana  
Rajat Verma  

## What the session covered

- **Data Supply Chain:** Signal quality and its product consequences
- **Signal Capture:** What gets measured, what gets missed
- **Label Logic:** Labels are product decisions, not clerical work
- **Pipeline Reality:** Ingestion, transformation, serving, feedback
- **Problem Translation:** From business ambiguity to an ML target
- **Fragility Map:** Leakage, bias, consent and hidden fragility

## Key ideas and cases

### Ideas that stayed with me

- **Data work is product work:** Collection, labels and pipelines shape user outcomes directly. The PM cannot delegate them away.
- **The target is a choice:** The prediction target must represent the real business outcome; a convenient proxy can optimise the wrong thing.
- **Instrument before you model:** Debating models before knowing signal quality is the most common and expensive mistake.

### Cases that made it concrete

- **Spotify / YouTube signals:** Skips and watch-time are richer signals than explicit ratings.
- **Google reCAPTCHA:** Labelling can be distributed into product use when the task is simple enough.
- **Stripe Radar pipelines:** Fraud value depends on fresh features served in milliseconds.
- **Apple Card controversy:** Hidden bias in data creates confident but unfair decisions.

## How my thinking shifted

| Before this session | After this session |
| --- | --- |
| Data quality is a data-team problem | Data quality is a PM accountability |
| Labels are routine background work | Labels encode product judgment and need expert design |
| More data is always better | Necessary, consented and representative data is better |

## Applying it to my work

- **Data requirements brief:** For each model, link the business question, event schema, label logic and consent basis.
- **Fix chargeback labels:** Make sure fraud labels reflect confirmed fraud, not every disputed transaction.
- **Review DPDP consent:** Check whether merchant and customer data used for models has a defensible consent basis.

## Key takeaway

> PM leverage grows when weak data assumptions are challenged early, before elegant downstream failure appears.

## Question I am still exploring

How can a PM judge label quality without becoming a data scientist?

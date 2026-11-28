# Class Reflection – Session 07 of 16: AI Product Lifecycle

Management of AI Products  
Faculty: Vinaya Sathyanarayana  
Rajat Verma  

## What the session covered

- **Lifecycle Control Tower:** Mapping the product from framing to scale
- **Discovery Gate:** Lock the right problem before optimising
- **Validation Gate:** Model readiness, thresholds, launch discipline
- **Launch Gate:** Integration, fallbacks, live workflow behaviour
- **Deliverables and Cadence:** CRISP-DM and agile as coordination systems
- **Resilience Under Change:** Drift, bottlenecks and recovery

## Key ideas and cases

### Ideas that stayed with me

- **Launch is the start:** Deployment begins accountable operation. Treating it as completion is the costliest lifecycle mistake.
- **Gates need evidence:** Each gate needs a defined error profile and an owner for the cost of mistakes.
- **Drift is predictable:** Seasonality and shocks are foreseeable; escalation triggers should be set before customers notice.

### Cases that made it concrete

- **Tesla Autopilot:** Feature evolution in stages, with expanding scope as evidence builds.
- **Klarna support assistant:** Rollout success depends on how the workflow absorbs the model.
- **Festival-season fraud drift:** Fraud patterns shift with peak traffic; models need seasonal monitoring.
- **Ride-hailing ETAs in weather:** External shocks degrade quality quickly without resilience plans.

## How my thinking shifted

| Before this session | After this session |
| --- | --- |
| The lifecycle is a sequence of milestones | The lifecycle is an operating system |
| Monitoring is an ops afterthought | Monitoring notes and drift reviews are core deliverables |
| Ship when accuracy is high enough | Ship when the error profile and its cost owner are agreed |

## Applying it to my work

- **Festive-season drift playbook:** Pre-set drift thresholds and escalation rules for Diwali and sale-season transaction spikes.
- **Formal launch gates:** Require an experiment brief and go/no-go criteria before any model reaches production.
- **Name an owner per model:** Make one person accountable for each live model's quality, not just its build.

## Key takeaway

> A mature lifecycle keeps evidence, response speed and ownership intact under change.

## Question I am still exploring

Who should own a model in production when product, data science and operations all touch it?

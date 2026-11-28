# Class Reflection – Session 11 of 16: Scaling AI Products

Management of AI Products  
Faculty: Vinaya Sathyanarayana  
Rajat Verma  

## What the session covered

- **Scale Architecture:** What breaks first when success arrives
- **Response-Time Economics:** Throughput, latency and cost
- **MLOps Basics:** Automation, monitoring and release confidence
- **Model Versioning:** Versioning, rollback and controlled rollout
- **API Scaling:** Queues, rate limits and reliability promises
- **Scaling GenAI Products:** Routing, caching and safety at volume

## Key ideas and cases

### Ideas that stayed with me

- **Scale is a product problem:** Service promise, unit economics, reliability and architecture have to be managed together.
- **Latency has a patience limit:** Beyond a point, users stop valuing quality gains if the response is too slow.
- **Promise only what you can hold:** Strong PMs shape the service promise before the system is forced to break it.

### Cases that made it concrete

- **ChatGPT demand spikes:** Launch success can overwhelm capacity and degrade experience.
- **Google Translate:** Low-latency expectations set the bar for model complexity.
- **Stripe-style APIs:** Reliability promises become part of the product contract.
- **Copilot routing & caching:** Route simple requests to cheaper models to protect margin.

## How my thinking shifted

| Before this session | After this session |
| --- | --- |
| Infrastructure is engineering's concern | Infrastructure limits are product decisions |
| Bigger models give better products | Right-sized models plus routing give better products |
| Releases are one-way doors | Versioning and rollback make releases reversible |

## Applying it to my work

- **Latency budget per flow:** Set end-to-end latency budgets for authorisation and risk scoring at peak TPS.
- **Tiered throughput:** Define rate limits and priority lanes for large merchants versus long-tail merchants.
- **Rollback drill:** Make sure every model release can be rolled back within minutes.

## Key takeaway

> Strong PMs shape what the system promises before the system is forced to break that promise.

## Question I am still exploring

How should SLAs differ between deterministic APIs and probabilistic AI services?

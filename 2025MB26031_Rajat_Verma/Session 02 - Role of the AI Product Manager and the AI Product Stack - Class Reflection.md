# Class Reflection – Session 02 of 16: Role of the AI Product Manager and the AI Product Stack

Management of AI Products  
Faculty: Vinaya Sathyanarayana  
Rajat Verma  

## What the session covered

- **Role of the AI PM:** Where ownership is direct, shared or influence-only
- **AI Product Stack Overview:** Data, model, API and UX as one operating system
- **Working Across Functions:** Translating between experts with different incentives
- **Decision-Making in the Stack:** Latency, cost, quality and scope trade-offs
- **Examples in Practice:** What users see versus the invisible layer that drives value
- **AI PM Deliverables:** The weekly artifacts that reduce ambiguity

## Key ideas and cases

### Ideas that stayed with me

- **Decision rights beat job titles:** An AI PM's leverage comes from knowing which decisions they own, which they share and which they can only influence.
- **Find the bottleneck layer:** Customer value is usually capped by one layer (data, model, API or UX). Fixing the others first wastes effort.
- **Translate, don't flatten:** Aligning legal, data science and engineering means keeping technical constraints intact while making them understandable.

### Cases that made it concrete

- **Stripe fraud stack:** Real-time scoring forces explicit trade-offs between latency, cost and catch rate.
- **Netflix ranking stack:** The visible UI is thin; most business value sits in invisible data and model layers.
- **Microsoft copilots:** Shipping needed product, design, engineering and legal to converge on one decision.
- **Airbnb search & trust:** Cross-functional loops connect ranking quality with host and guest trust.

## How my thinking shifted

| Before this session | After this session |
| --- | --- |
| The PM writes requirements and hands off | The PM makes dependencies and launch criteria explicit early |
| Quality is always the top priority | Quality, speed and cost must be traded off deliberately |
| Stack details belong to engineering | The PM must understand each layer well enough to find the bottleneck |

## Applying it to my work

- **Map our stack:** Draw the data, model, API and UX layers of our fraud/risk flows and mark the current bottleneck.
- **Write a decision-rights grid:** For each AI feature, state who owns, who is consulted and who only influences each decision.
- **Add launch criteria to PRDs:** Include latency budget, cost per call and acceptable error rate in every AI PRD.

## Key takeaway

> An AI PM creates leverage by making dependencies, trade-offs and launch criteria explicit earlier than anyone else.

## Question I am still exploring

How much technical depth does a PM need before they can credibly challenge a modelling choice?

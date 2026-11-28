# Class Reflection – Session 05 of 16: Designing AI Products - User and Model Thinking

Management of AI Products  
Faculty: Vinaya Sathyanarayana  
Rajat Verma  

## What the session covered

- **UX for AI Products:** When AI should be visible, invisible or reviewable
- **Designing for Uncertainty:** Confidence, fallback and expectation setting
- **Human-in-the-Loop Design:** Human review and staged automation
- **Prompt Design for GenAI:** Product behaviour through instructions and guardrails
- **Explainability and Trust:** Transparency and recourse that help users act
- **AI Design Deliverables:** Wireframes, prompt specs and fallback rules

## Key ideas and cases

### Ideas that stayed with me

- **Design the failure path:** Every AI surface needs a decided answer to: what happens when the model is wrong or unsure?
- **Human review has a cost:** Human-in-the-loop adds trust where judgment matters, and only adds delay where it does not.
- **Prompts are product specs:** Prompts and guardrails define product behaviour, so they deserve versioning and review like code.

### Cases that made it concrete

- **Perplexity answers:** Citations make AI output reviewable and build trust.
- **Copilot in-flow:** Invisible assistance works when it stays inside the user's flow.
- **Credit decision disclosures:** Explanations must help the customer act, not just satisfy compliance.
- **Support copilots:** Prompt libraries and fallback specs keep behaviour consistent at scale.

## How my thinking shifted

| Before this session | After this session |
| --- | --- |
| Good AI UX means hiding complexity | Good AI UX shows confidence and control where they matter |
| Explainability is a compliance checkbox | An explanation is useful only if it helps the user act |
| Prompting is an engineering detail | Prompt design is product design |

## Applying it to my work

- **Confidence-based flows:** Route low-confidence KYC or dispute decisions to human review with a clear status for the merchant.
- **Reason codes customers can act on:** Replace generic decline messages with explanations that suggest a next step.
- **Prompt spec for support bot:** Document tone, allowed actions, escalation triggers and forbidden claims.

## Key takeaway

> AI UX becomes credible only when the PM makes workflow, trust and failure recovery explicit.

## Question I am still exploring

How do we show uncertainty to users without making the product feel unreliable?

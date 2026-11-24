# Class 10 Reflections

**Date:** 17 October 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Products are Promises:** Every product is an explicit promise of predictability and value to the customer. Consistency and predictability matter far more to enterprise buyers than raw speed or novelty.
* **Graceful Degradation:** When an AI model fails, timeouts occur, or context limits are exceeded, the product must fail safely and visibly—never silently or with fabricated confidence.
* **The Moving Goalpost of User Expectations:** Novel features become baseline hygiene factors astonishingly quickly. What delighted users three months ago is taken for granted today.
* **Sustainable Adoption vs Short-Term Hype:** A successful launch with thousands of signups means nothing if users drop off after week two because the tool doesn't fit naturally into their daily routine.

---

### 2. What Resonated Most With Me
The concept of **graceful degradation** was the standout takeaway today. In critical enterprise applications, an explicit message stating *"I cannot verify this specific data point, please review the original source"* builds far more long-term credibility than an AI that confidently hallucinates an answer. Designing clear fallback states (reverting to keyword search, alerting a human analyst, or providing partial results) is a core PM responsibility.

The point about **rapidly hardening customer expectations** also felt very real. When generative AI first arrived, users were amazed by any coherent paragraph. Today, users expect precise, grounded, cited, and domain-accurate answers. As PMs, our roadmaps cannot simply plan to maintain the status quo; we have to build foundational architectures that can absorb new capabilities as baseline expectations rise.

I also liked the focus on **cross-functional team alignment**. Keeping engineering, design, compliance, and marketing aligned around the core product promise prevents scope creep and feature bloat.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The discussion on degraded states was excellent. Having a visual design walkthrough of 3–4 different degradation patterns across top SaaS tools (e.g., how Notion, GitHub Copilot, or Salesforce handle model dropouts and rate limits) would be a fantastic practical reference.

---

### 4. Personal Action Item
Ensure our project documentation includes an explicit "Failure Modes & Fallback Strategy" section detailing exactly how the system behaves when external APIs are unreachable or confidence scores fall below threshold.

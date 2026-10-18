# Reflection: Scale, Expectations, and Operating AI Products in Production

**Session Date:** October 17, 2026
**Session Topic:** Customer Expectations at Scale, Latency Design, Routing and Throttling, and Agent Governance

## Core Takeaways & Concepts

- **Scale and Unknown Customers:** You don't know your customers (or their count) when you build. At some point you can't service them, especially for SaaS. Even free products limit usage (the WhatsApp/Gmail question), assuming the product is good enough that people actually want it.
- **Customer Expectations Shift:** Run sensitivity analysis on what customers accept and what wows them, and remember it changes over time (a letter taking seven days was normal once). Alert customers in advance of downtime (a bank warned of a 1-3 a.m. SMS outage).
- **Latency Perception Design:** Users switch away while jobs run. Splitting work across screens can feel better than one long wait. A predictable time (for example 25 rising to 45 seconds) beats an erratic average.
- **Post-Release, Your Team Decides:** You won't make day-to-day decisions, so ensure team alignment and clear requirements, or you get defects and delayed releases. Plan alerts for peak periods (festival seasons).
- **Operating at Scale:**
  - Agent governance must scale faster than the number of agents.
  - Use model routing: the latest model where it performs, older ones elsewhere, which requires the ability to switch.
  - Throttle requests internally rather than being blocked for ten minutes by a provider.
  - Create priority lanes for VIP customers (express vs. passenger-train analogy) and measure on-time arrival by customer class, not overall.
  - Optimization techniques include caching, selective routing, and truncation. They carry privacy limits (you can't reuse one user's cached answer for another).
  - Know your unit economics at scale so overhead is covered by volume.

## Workplace Applicability & Contextual Translation

- **Priority Lanes in Recruiting Automation:** Urgent requisitions and top-tier clients deserve a faster queue for sourcing and screening jobs. Measure turnaround by client tier.
- **Model Routing:** Use cheaper or older models for bulk resume parsing and reserve premium models for nuanced summaries, with the ability to switch if a provider degrades.
- **Privacy at Scale:** Caching or reusing candidate data across recruiters and clients must respect consent boundaries.

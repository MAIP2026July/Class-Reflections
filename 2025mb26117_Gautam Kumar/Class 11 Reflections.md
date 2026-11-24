# Class 11 Reflections

**Date:** 24 October 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Ethics and Governance as Concrete Product Features:** Ethics cannot remain as vague mission statements on a slide. Responsible AI must be translated into explicit product requirements, automated guardrails, and audit logs.
* **Unintentional Bias in Data & Feedback Loops:** Bias rarely comes from malicious intent; it enters through historical training data, selective labeling, and self-reinforcing feedback loops that amplify majority patterns.
* **Data Minimization as a Risk Strategy:** The most secure piece of data is the data you never collected. Minimizing prompt telemetry and data retention significantly lowers enterprise liability.
* **Hallucination Mitigation Through Architecture:** Rather than hoping a model will stop hallucinating, PMs must enforce grounding through retrieval-augmented generation (RAG), strict schema validation, and source citation requirements.

---

### 2. What Resonated Most With Me
As the final classroom session before our capstone presentations, today's discussion on **accountability and governance** felt like the capstone of the entire course philosophy. Professor Vinaya's reminder that **we cannot outsource accountability to an algorithm** was powerful. When an enterprise product makes an error, the company and the PM own the consequences, not the LLM provider.

The discussion on **data minimization** was particularly pragmatic. In many teams, there is an instinct to hoard as much user conversation history and metadata as possible. But in an era of strict privacy regulations (GDPR, DPDP) and enterprise security audits, storing unneeded sensitive data is a liability waiting to happen.

I also valued the discussion on **transparent incident communication**. No software product is completely free of bugs or edge-case failures. When an AI system fails, acknowledging the issue promptly, explaining the root cause, and demonstrating the remediation steps taken is how you preserve customer trust for the long haul.

---

### 3. Constructive Thoughts & Course Reflection
* This course has been an exceptional journey that successfully balanced high-level strategic product thinking with rigorous, unvarnished realities of shipping AI into production. 
* If there is one suggestion for future cohorts, having an interactive mock "Executive Gate Review" or "Incident Response Simulation" in the final weeks would be an incredible capstone exercise to put all 11 weeks of learning into practice under real-time constraints.

---

### 4. Personal Action Item
Review our complete capstone submission package to ensure our governance, risk mitigation, audit logging, and ethical disclosure documentation are front and center alongside our product strategy and architecture.

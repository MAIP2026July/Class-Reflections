# Class 11 Reflections

**Date:** 24 October 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Responsible AI as a Core Architecture Requirement:** Safety, fairness, and compliance cannot be treated as post-launch compliance checklists. They must be designed into the data ingestion, prompt construction, and output validation layers from day one.
* **Data Minimization and Privacy Safeguards:** Collecting unnecessary user information increases legal liability and potential breach damage. An AI product should only ingest the specific context required to complete the task at hand.
* **Preventing Prompt Injection and Context Leakage:** In multi-tenant systems or autonomous agents, malicious inputs can manipulate the system into exposing system instructions or private data belonging to other users. Robust input sanitization is mandatory.
* **Auditability and Traceability:** Enterprise clients require full audit trails showing why an AI system made a specific recommendation, what data it accessed, and which prompt version was executed.

---

### 2. What Resonated Most With Me
Today's discussion on data minimization and prompt injection gave me a lot to think about regarding our AI Twin capstone. Because our product is designed to interact with a user's calendar, messages, and communication history, data privacy is not a secondary feature—it is the foundational prerequisite for anyone trusting our product.

Professor Vinaya's emphasis on auditability was also very impactful. If an enterprise executive uses an AI Twin to send a message or approve a workflow, there must be a transparent, tamper-proof log of exactly what context was provided to the model, what rules were applied, and when the user approved the action. Without that audit trail, no corporate legal team will ever clear our product for deployment. Building those guardrails early is much easier than trying to retrofit them into a complex codebase later.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* A quick walkthrough on how to structure a formal AI Data Protection and Security Whitepaper for enterprise procurement teams would be an extremely valuable business artifact for MBA students.

---

### 4. Personal Action Item
Document the data flow and anonymization policy for our AI Twin capstone, ensuring that sensitive personal identification information (PII) is scrubbed before any context is passed to external LLM endpoints.

# Class 12 Reflections

**Date:** 31 October 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Target Costing (Working Backwards from Customer Value):** In AI product development, traditional cost-plus pricing often fails. PMs must adopt the Japanese target costing methodology: determine the customer's willingness to pay based on delivered business value, subtract the required gross margin, and establish the maximum allowable build and inference cost per transaction.
* **Eliminating Contractual Ambiguity in PRDs:** A product requirements document is a binding contract between product management, engineering teams, and external vendors. Subjective phrases like "accurate summaries", "fast processing", or "user-friendly design" lead to misalignment, scope creep, and vendor disputes. Every requirement must be tied to unambiguous, verifiable metrics.
* **Diagrams-as-Code & Swimlane Architectures:** Moving away from static image flowcharts to diagrams-as-code (PlantUML or Mermaid) allows specifications to be version-controlled alongside code. Workflow swimlanes must explicitly identify which steps are deterministic rules, which are probabilistic AI completions, and where human intervention occurs.
* **Capping Agentic Loops:** Autonomous agent loops and RAG pipelines can easily fall into infinite retry loops, burning hundreds of dollars in API tokens in minutes. Enforcing hard loop caps, timeout boundaries, and fallback actions is essential for financial and operational stability.
* **Outcome-Based Pricing vs Input-Based Billing:** Customers should not be penalized for an AI's inefficiency. Pricing models must align with delivered customer outcomes rather than charging for consumed tokens or compute time.

---

### 2. What Resonated Most With Me
Today's live review of Team 002's documentation on screen made this session one of the most practical and high-impact classes of the entire term. Seeing real project deliverables critiqued in real time gave everyone immediate clarity on the difference between an academic assignment and a professional enterprise-grade submission.

Professor Vinaya's story about early software quality tools in the 1990s that flagged subjective words in requirements was fantastic. It made me realize how often we slip into comfortable, vague language in PRDs—writing things like "the response must be highly accurate" or "the interface must minimize user friction." To an engineer or third-party vendor, those phrases mean nothing and create massive delivery risk. Professor Vinaya's challenge to replace every adjective with a quantifiable threshold—such as "response generated within 1.8 seconds at p95" or "suppression rate above 99.5%"—is a standard I will carry into every future project.

The discussion on **outcome-based pricing versus token billing** was also directly relevant to our team's AI Twin deliberations. If an AI agent loops three times to summarize a complex email, the customer should not have their bill tripled because the model struggled. Customers pay for the solved problem, not our compute bill. If we cannot manage our internal prompt efficiency, that is our margin problem to solve through target costing, not a surcharge to pass onto the customer.

Lastly, the conversation around the **strict submission deadline freeze (24–48 hours before presentations)** was very sensible. Having coordinated closely with our team on our GitHub repository, I know how easy it is to keep tweaking files until the last minute. Establishing a clean freeze allows both the faculty and the students to focus on clear presentation delivery rather than tracking moving commits.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The live critique of Team 002 was so valuable that it would be wonderful in future courses to introduce peer-review clinics earlier in the semester (around week 6 or 7). Having teams review each other's draft swimlanes and metric specifications halfway through would elevate the quality of submissions across the entire cohort.

---

### 4. Personal Action Item
Conduct a thorough audit of our AI Twin project documentation and capstone files before the freeze:
1. Review all requirement sections to eliminate subjective adjectives and replace them with measurable acceptance criteria.
2. Ensure our system workflow diagram clearly distinguishes deterministic validation checks from probabilistic LLM inference calls.
3. Verify that our cost projections reflect target costing principles and enforce maximum retry caps on all autonomous agent routines.

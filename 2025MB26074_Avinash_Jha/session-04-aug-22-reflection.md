# Class Reflection: Session 04 — August 22, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: Value Creation, Gate 0 Social Legitimacy & The AI Appropriateness Ladder  

---

## 1. Core Theme & Executive Synthesis

Session 04 addressed a fundamental question: **When and where does AI actually create genuine product value?** The instructor cautioned against building "fashionable" AI features that add technological overhead without solving real user problems ("nuclear-powered pencil sharpeners"). Before evaluating technical feasibility, products must pass **Gate 0: Social Legitimacy, Consent, and Ethical Alignment**.

---

## 2. Key Concepts & Frameworks Dissected

* **Gate 0 — Social Legitimacy**: Earning societal trust, user consent, and regulatory alignment before testing technical fit. Products targeting vulnerable groups (minors, impaired users) or relying on hidden labor/surveillance fail Gate 0 regardless of profitability.
* **The AI Appropriateness Ladder**: Always default to the simplest, least complex technology that gets the job done:
  1. *Level 1 — Deterministic Rules*: `if-then-else` logic for static, unambiguous tasks.
  2. *Level 2 — Search & Analytics*: Knowledge retrieval and rule-based indexing.
  3. *Level 3 — Predictive ML*: Classification, regression, and demand forecasting based on historical patterns.
  4. *Level 4 — Generative & Agentic AI*: Unstructured generation, autonomous reasoning, and copilot workflows.
* **Tail Risk & Actionable Windows**:
  * *Tail Risks*: Low-probability, high-consequence failures (e.g., incorrect medical/pesticide advice) require strict human-in-the-loop guardrails.
  * *Actionable Window*: Insights delivered outside the user's operational decision window (e.g., weather alerts delivered 1 minute before a storm) hold zero economic value.
* **Pre-AI vs. Post-AI Baselines**: Proving incremental AI value requires establishing clear pre-AI performance baselines (cost, latency, accuracy) to measure post-AI lift.

---

## 3. Personal Reflection & Practical Application

The case study of **Kesan Sai** (multilingual agricultural advisory) illustrated the life-and-death consequences of model outputs. Recommending an incorrect pesticide or delayed harvesting window due to hallucination causes catastrophic financial harm to smallholder farmers. 

This reinforced that **average accuracy metrics (e.g., 95% overall accuracy) mask dangerous tail risks**. In high-stakes applications, product managers must design fallback guardrails—escalating low-confidence predictions to domain specialists or restricting the model to deterministic lookup tables.

---

## 4. Critical Evaluation & Friction Points

* **Automating Desirable Human Workflows**: Automating tasks that users actually enjoy (such as personal branch visits or social interactions) reduces overall customer satisfaction. PMs must distinguish between tedious friction points and valued human touchpoints.
* **Model Over-Engineering**: Engineering teams often default to complex foundational models when simple SQL queries or rule-based logic would deliver faster, cheaper, and fully explainable outcomes.

---

## 5. Action Items for Capstone PRD

1. **Gate 0 Verification**: Screen my Capstone project for data consent, privacy compliance, and vulnerable population impact.
2. **Baseline Definition**: Define explicit pre-AI vs. post-AI performance metrics ($P_{50}, P_{95}$ latency and cost per inference) in the PRD framework.

# Class Reflection: Session 07 — September 12, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: Midterm Exam Strategy, Utility Customer Support Case Study & Prompt Engineering  

---

## 1. Core Theme & Executive Synthesis

The final session prior to the Midterm exam synthesized key course themes through an interactive case study involving **electricity distribution companies (DISCOMs)**. The instructor emphasized shifting from theoretical "what to do" answers to **practical, context-driven execution ("I, as the PM, will do X")**. The session also covered **prompt engineering frameworks (RCTC)** and addressed the psychological friction of **human reviewer fatigue in Human-in-the-Loop (HIL) systems**.

---

## 2. Key Concepts & Frameworks Dissected

* **DISCOM Case Analysis — Proactive vs. Reactive Support**:
  * *Reactive*: Waiting for irate customers to call during a power outage overburdens call centers and generates negative sentiment.
  * *Proactive / Systemic Thinking*: Integrating telemetry from smart meters and feeder stations to detect outages automatically, broadcast proactive SMS/app alerts with estimated restoration times ($ETAs$), and route field technicians before calls occur.
* **Outcome-Based Unit Economics & Shared Savings**: Pricing AI customer support solutions for utilities should avoid per-seat or raw API token models (which penalize efficiency). Instead, utilize **pay-as-you-use or gain-share models** tied to reduced call volume and operational cost savings.
* **Prompt Engineering Framework (RCTC)**:
  * **R**ole: Define the AI persona (e.g., "You are an expert utility support triage assistant").
  * **C**ontext: Provide domain rules, operational boundaries, and account status.
  * **T**ask: Specify the exact output requirement (e.g., classify query and generate $ETA$).
  * **C**onstraints: Enforce guardrails (e.g., "Do not promise restoration times under 30 minutes without field log confirmation").
* **Managing Human Fatigue in HIL Systems**: When human reviewers repeatedly approve $99\%$ of AI recommendations without changes, fatigue sets in, turning human oversight into a rubber stamp. Systems must randomize reviews or present contrasting cases to maintain active human judgment.

---

## 3. Personal Reflection & Practical Application

The DISCOM case study provided a masterclass in **systems thinking**. My initial instinct was to design a faster AI voice bot to answer customer calls. However, as the discussion evolved, I realized that **the best customer support experience is eliminating the need for a call entirely**. Proactive outage detection and automated broadcast updates solve the root problem, leaving call centers free to handle complex edge cases.

In my workplace, this reinforces the principle that **AI should not merely digitize existing friction—it should eliminate it**.

---

## 4. Critical Evaluation & Friction Points

* **Exam Strategy Mandate**: Answers must be written from the perspective of an accountable decision-maker ("I will..."), avoiding generic advice ("The company should..."). Every sub-question must adhere strictly to the 1-page limit, delivering dense, contextualized solutions.
* **Launch is the Midpoint**: Launching General Availability (GA) is not the finish line; it is the midpoint of the product lifecycle. Post-launch operations must continuously monitor model drift, data drift, and latency degradation.

---

## 5. Action Items for Capstone PRD & Exam Prep

1. **Adopt RCTC Prompt Design**: Standardize prompt templates in the Capstone PRD using the Role-Context-Task-Constraint framework.
2. **Midterm Execution Posture**: Review all 7 session topics through the lens of context-driven case execution, ensuring answers frame explicit trade-offs and concise justifications.

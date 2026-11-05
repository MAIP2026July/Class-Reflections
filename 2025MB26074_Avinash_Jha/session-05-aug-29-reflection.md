# Class Reflection: Session 05 — August 29, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: High-Value AI Opportunities, Build vs. Buy, Midterm Strategy & The AI Stack  

---

## 1. Core Theme & Executive Synthesis

Session 05 provided strategic guidance on identifying high-value AI opportunities and making disciplined **Build vs. Buy vs. Partner vs. API** decisions. The instructor emphasized scientific rigor and evidence over technological hype: customers pay for solved problems, not for the word "AI." Additionally, the instructor outlined the **4-Layer AI Product Stack** and provided key guidelines for the upcoming case-based Midterm exam.

---

## 2. Key Concepts & Frameworks Dissected

* **The 4-Layer AI Product Stack**:
  1. *Data Layer*: Data collection pipelines, labeling/annotation quality, and data freshness.
  2. *Model Layer*: Machine learning algorithms (classification, time-series, GenAI) chosen for specific task performance.
  3. *API Layer*: Decoupling the front-end experience from the underlying model to prevent vendor lock-in and enable seamless model swaps.
  4. *User Experience (UX) Layer*: Designing interfaces for probabilistic outputs, uncertainty disclaimers, confidence scoring, and system error fallbacks.
* **Sourcing Strategy (Build vs. Buy vs. Partner vs. API)**:
  * *Build*: Reserve in-house model development exclusively for core competitive moats and proprietary IP.
  * *API / Subscription*: Leverage commodity APIs for standard capabilities (OCR, speech-to-text, general LLMs) to reduce capital expenditure and time-to-market.
* **Midterm Exam Mandate**:
  * Case-based, context-driven evaluation (2 cases, 3 sub-questions each).
  * **Strict 1-page maximum per sub-question** (top to bottom on a single page). Conciseness, direct execution, and contextual application are mandatory; filler text is penalized.

---

## 3. Personal Reflection & Practical Application

The **4-Layer AI Product Stack** provided a clear mental model for evaluating system architecture. In my own workplace, we previously coupled UI logic directly to specific model endpoints. When a superior model variant became available, updating the application required major code refactoring. 

Decoupling through a dedicated **API layer** allows the product team to swap underlying models ($M_1 \rightarrow M_2$) seamlessly as inference costs drop and model accuracy improves.

---

## 4. Critical Evaluation & Friction Points

* **Unit Economics & Token Costs**: Generative AI applications introduce variable inference costs that scale directly with usage. Without analyzing cost-per-token and $P_{95}$ latency upfront, products that achieve viral user growth can face financial collapse due to negative unit economics.
* **The "Build" Trap**: Product teams frequently suffer from Not-Invented-Here (NIH) syndrome, attempting to train proprietary models from scratch when commercially available APIs deliver superior performance at a fraction of the cost.

---

## 5. Action Items for Capstone PRD

1. **Architecture Decoupling**: Ensure the Capstone PRD specifies a distinct API layer between the UX and model endpoints.
2. **Unit Economics Framework**: Estimate inference cost per user interaction and model $P_{95}$ latency constraints.

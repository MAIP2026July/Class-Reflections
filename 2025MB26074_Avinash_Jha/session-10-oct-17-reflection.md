# Class Reflection: Session 10 — October 17, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: Scaling AI Products, Cost of Inference, MLOps & Semantic Versioning  

---

## 1. Core Theme & Executive Synthesis

Session 10 focused on the operational realities of scaling AI products from initial prototype to General Availability (GA). The core message was clear: **uncontrolled product growth can destroy unit economics if inference costs are not actively managed**. Product managers must balance model latency, output quality, infrastructure costs, and customer trust. Achieving sustainable scale requires rigorous MLOps practices, token optimization, and customer-centric latency metrics.

---

## 2. Key Concepts & Frameworks Dissected

* **Cost of Inference & Unit Economics (The Accenture Case)**:
  * Scaling user adoption without token cost controls leads to margin collapse. The instructor cited Accenture’s enterprise initiative, which reduced per-user AI costs from $\$1,000/\text{month}$ down to $\$29/\text{month}$ through aggressive optimization.
* **Token Optimization Architecture**:
  * **Model Routing / Multiplexing**: Directing simple queries ($80\%$ volume) to lightweight Small Language Models (SLMs, $< 10\text{B}$ parameters) and routing complex multi-step reasoning ($20\%$ volume) to expensive Frontier LLMs.
  * **Prompt Caching & Truncation**: Caching repetitive system context and trimming payload sizes to minimize input token billing.
* **Customer Promise Metrics vs. Infrastructure Metrics**:
  * Infrastructure metrics ($CPU/GPU$ utilization, raw API uptime) do not reflect user value.
  * PMs must manage **Customer Promise Metrics**: $P_{50}, P_{95}, P_{99}$ latency, time-to-first-token ($TTFT$), and task completion fidelity within the user's actionable time window.
* **MLOps & Semantic Versioning (SemVer) for AI**:
  * Adapting SemVer ($\text{Major}.\text{Minor}.\text{Patch}$) to AI products:
    * *Major*: Fundamental architecture or base model replacement ($e.g., \text{GPT-3.5} \rightarrow \text{GPT-4}$).
    * *Minor*: System prompt revisions, RAG pipeline updates, or fine-tuning weight updates.
    * *Patch*: Bug fixes, guardrail updates, or formatting adjustments.

---

## 3. Personal Reflection & Practical Application

Understanding **Model Routing** as a cost-governance mechanism was highly actionable. In product design, the default temptation is to send every prompt to the most powerful frontier model available. However, implementing a lightweight "router model" at the API layer allows the system to satisfy $80\%$ of routine requests at a fraction of the cost, preserving budget for high-value reasoning tasks.

This insight will directly shape how we budget and architect LLM features in our enterprise product stacks.

---

## 4. Critical Evaluation & Friction Points

* **Actionable Time Windows**: Delivering predictions outside the user's operational decision window renders the output useless, regardless of model accuracy ($e.g.,$ weather/traffic alerts delivered minutes too late).
* **Silent Performance Drops**: Scaling API usage often triggers silent rate-limiting, throttling, or degraded response quality from cloud vendors during peak hours, necessitating failover routing across multiple LLM providers.

---

## 5. Action Items for Capstone PRD

1. **Incorporate Token Optimization Strategy**: Specify model routing logic (SLM vs. Frontier LLM) and caching rules in the Capstone PRD architecture section.
2. **Define Latency SLAs**: Establish explicit $P_{95}$ latency SLAs for all interactive user touchpoints in the PRD.

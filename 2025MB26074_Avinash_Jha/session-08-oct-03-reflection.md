# Class Reflection: Session 08 — October 03, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: Midterm Exam Retrospective, PFIR Framework & Human-in-the-Loop Gating  

---

## 1. Core Theme & Executive Synthesis

This session bridged the Midterm exam retrospective with advanced operational frameworks for managing probabilistic outputs. The core theme centered on **architecting trust in AI systems**: moving away from vague, ungrounded LLM outputs toward structured retrieval architectures, explicit output classification via the **PFIR Framework**, and rigorous **Human-in-the-Loop (HIL) gating**. The instructor reinforced that product managers are the ultimate trustees of capital and user trust, fully accountable for mitigating technical and regulatory risks.

---

## 2. Key Concepts & Frameworks Dissected

* **PFIR Framework for Hallucination & Output Taxonomy**:
  * **P / F (Facts & Features)**: Deterministic data points (e.g., insurance claim rules, product specs, exact pricing) retrieved directly from databases or RAG pipelines. Hallucination risk must be kept at zero.
  * **I (Inferences)**: Logical derivations synthesized from structured or unstructured data. Requires clear data lineage and confidence attribution.
  * **R (Recommendations)**: Probabilistic advice (e.g., underwriting approvals, medical triage recommendations). Requires explicit guardrails, confidence scoring, or mandatory human review.
* **Model Convergence & Iterative Tuning**:
  * Base SLM/LLM models hosted locally (e.g., via Ollama or RunPod GPU instances) rarely produce production-grade results on the first attempt.
  * Achieving output stability requires 5 to 6 iterative refinement loops—tuning hyper-parameters (temperature, top-p, seed) and system prompt constraints.
* **Human-in-the-Loop (HIL) Gating & Staged Autonomy**:
  * Autonomy should be granted dynamically based on confidence thresholds and financial/legal liability.
  * Low-risk or high-confidence predictions run autonomously; high-risk or low-confidence edge cases trigger mandatory human escalation with audit logs.

---

## 3. Personal Reflection & Practical Application

The **PFIR Framework** fundamentally changes how I view LLM outputs. Previously, I viewed generative AI responses as uniform text blobs. Deconstructing outputs into *Facts, Features, Inferences, and Recommendations* provides a precise blueprint for UX design and error handling. For instance, Facts should be rendered with direct source citations, while Recommendations must display confidence badges and explicit disclaimers.

In my workplace, applying PFIR allows us to set hard deterministic boundary rules around regulatory data while leveraging probabilistic generation only for drafting narrative summaries.

---

## 4. Critical Evaluation & Friction Points

* **Exam Strategy Realignment**: Theoretical "what to do" answers fail in case evaluations. Execution requires an accountable posture ("I, as the PM, will do X") supported by explicit trade-off analyses (e.g., trading inference latency for higher precision).
* **Vendor Dependency & Model Drift**: Relying on external API models (OpenAI, Anthropic) introduces hidden operational risk. When vendors silently update model weights, product performance can degrade without code changes, making pluggable architecture designs essential.

---

## 5. Action Items for Capstone PRD

1. **Implement PFIR Taxonomy**: Map all LLM outputs in the Capstone PRD to the PFIR structure, defining explicit grounding protocols for Facts vs. Recommendations.
2. **Design HIL Escalation Rules**: Define exact confidence score thresholds ($e.g., < 0.85$) that trigger human reviewer escalation in the target PRD workflow.

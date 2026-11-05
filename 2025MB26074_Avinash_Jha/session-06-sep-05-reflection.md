# Class Reflection: Session 06 — September 5, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: Re-imagining Workflows (Art of the Possible), Sentiment Analysis & Data Governance  

---

## 1. Core Theme & Executive Synthesis

Session 06 challenged students to master **"the art of the possible"**—re-imagining core business workflows by removing historical constraints rather than merely digitizing legacy manual processes. The technical focus shifted to **sentiment analysis and opinion mining**, moving beyond primitive positive/negative labels to extract structured **quintuples**. The session concluded with an urgent directive on data governance, consent, and the **DPDP (Digital Personal Data Protection) Act**.

---

## 2. Key Concepts & Frameworks Dissected

* **Re-imagining Black-Box Workflows**: True transformation leaps from caterpillar speed to butterfly flight ($1000\times$ improvement). Product managers must question legacy assumptions (e.g., why exams occur on set days or why loans require manual branch reviews) and re-architect workflows using AI capabilities.
* **The Opinion Quintuple**: A structured framework for extracting actionable intelligence from unstructured feedback:
  $$G = (o, f, s, h, t)$$
  * $o$: Target Object (e.g., iPhone).
  * $f$: Specific Feature (e.g., battery life, camera in low light).
  * $s$: Sentiment orientation and strength (e.g., negative, neutral, highly positive).
  * $h$: Opinion Holder (e.g., user vs. parent).
  * $t$: Time of opinion posting (pre- or post-update).
* **Data Governance & DPDP Compliance**: Organizations do not own user data; they act as **custodians and trustees**. Under DPDP and GDPR, products must support explicit consent, purpose limitation, and the "right to be forgotten."
* **Heisenberg Principle of Measurement in Product Management**: The act of measuring a system (e.g., logging granular user telemetry or prompt metrics) alters system behavior, increases latency, and introduces security attack surfaces.

---

## 3. Personal Reflection & Practical Application

The distinction between **surface-level sentiment analysis and feature-level quintuple mining** was eye-opening. A generic positive score across user reviews provides zero guidance to engineering. However, extracting that *voice quality* is rated highly while *low-light camera performance* is heavily criticized gives the product manager precise, actionable requirements for the next feature sprint.

Furthermore, the discussion on **DPDP compliance** highlighted a major industry risk. Many product teams collect extensive telemetry without explicit consent mechanisms. In my own organization, we must audit our data pipelines to enforce automated data expiration and user deletion workflows.

---

## 4. Critical Evaluation & Friction Points

* **Opinion Spam & Sarcasm**: Sentiment models frequently misinterpret sarcasm, implicit comparisons, and fake reviews. Relying solely on automated sentiment dashboards without qualitative spot-checks risks misguiding product strategy.
* **Consent Fatigue**: Over-indexing on consent popups disrupts the user experience. PMs must design frictionless consent workflows that preserve privacy without creating user fatigue.

---

## 5. Action Items for Capstone PRD

1. **Quintuple Feature Extraction**: Incorporate structured feature-sentiment extraction into user feedback analytics for the Capstone concept.
2. **Data Governance Protocol**: Include a DPDP consent and data retention specification in the PRD appendix.

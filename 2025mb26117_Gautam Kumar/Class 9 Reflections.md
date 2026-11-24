# Class 9 Reflections

**Date:** 10 October 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Business Metrics vs Model Benchmarks:** A 98% benchmark score means nothing if the remaining 2% errors destroy customer trust. Never let an engineering model metric substitute for a real business KPI.
* **The Trap of Averages:** Averages conceal the catastrophic outliers. In enterprise AI, you must evaluate performance at the 99th percentile and inspect edge cases systematically.
* **Who Pays for the Errors?** In consumer software, a minor bug is a mild inconvenience. In enterprise workflows, if an AI generates incorrect calculations or misleading compliance guidance, the customer pays the price.
* **The "Guitar on the Motorcycle":** Users will inevitably take your product and use it in ways you never intended or imagined. Product design must account for unexpected behavior without breaking catastrophically.

---

### 2. What Resonated Most With Me
The professor's story about the **guitar on the motorcycle** was a great piece of product wisdom. In software, we often design around an idealized "happy path". But in reality, real users will paste confidential data into open text boxes, upload corrupted PDFs, or ask questions that violate every design assumption we made. Building resilient guardrails and graceful failure states is essential.

The discussion on **who bears the cost of model error** was deeply thought-provoking. If an AI recruiting tool filters out qualified candidates or an AI underwriting tool misprices risk, the software vendor rarely suffers immediately; the end customer bears the damage. This ethical asymmetry requires PMs to implement robust verification layers.

I also took note of the point about **continuous post-launch monitoring**. Unlike deterministic software which behaves identically unless code changes, AI systems degrade due to data drift, user behavioral shifts, and prompt changes. Monitoring must be ongoing.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The focus on edge-case testing was great. It would be wonderful to spend some time discussing red-teaming methodologies—specifically how product managers can systematically stress-test their own AI applications before releasing them to customer pilots.

---

### 4. Personal Action Item
Stress-test our capstone system with adversarial and boundary test cases, specifically documenting how the system responds when fed conflicting, incomplete, or ambiguous inputs.

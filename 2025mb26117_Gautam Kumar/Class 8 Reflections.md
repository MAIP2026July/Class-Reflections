# Class 8 Reflections

**Date:** 03 October 2026  
**Name:** Gautam Kumar  
**BITS ID:** 2025MB26117  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Reliability Trumps Demo Magic:** Anyone can build a demo that looks miraculous on a curated script. Building a product that functions reliably across thousands of noisy, unstructured real-world inputs is where product management actually happens.
* **Stage-Gate Discipline:** Products must "earn the right" to progress to the next phase through empirical proof gates, rather than moving forward simply because an arbitrary deadline arrived.
* **Model Agnosticism & Swappability:** Software architecture must be designed so that swapping an underlying model or embedding vendor requires minimal code adjustment rather than a wholesale rebuild.
* **Gradual Automation:** Start with AI as an assistant or suggester, let users validate accuracy, and only automate actions once confidence thresholds are proven over time.

---

### 2. What Resonated Most With Me
The contrast between **an impressive demo and production reliability** was spot on. In the generative AI space, Twitter and LinkedIn are flooded with five-minute prototype videos that fall apart the moment you feed them messy data. As product managers, our credibility depends on designing for the messy, unglamorous 90% of real-world usage.

The concept of **earning the right to advance** through stage gates resonated with our team's capstone journey. Defining objective validation gates (e.g., factual accuracy >95%, zero data leakage, sub-2-second latency on 90th percentile) keeps the team honest and prevents premature scaling.

I also appreciated the advice on **gradual automation**. Giving users the steering wheel initially and progressively automating tasks as trust builds is the most reliable way to achieve sustainable adoption in enterprise settings.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* The stage-gate discussion was very thorough. It would be valuable to see real-world examples of automated evaluation suites (evals) that PMs can run in continuous integration to catch regressions before releasing updated prompts or models to customers.

---

### 4. Personal Action Item
Define explicit, measurable exit criteria for our project's prototype gate, including a golden evaluation test dataset of at least 30 diverse test cases to verify prompt and workflow stability.

# Class 2 Reflections

**Date:** 01 August 2026  
**Name:** Preeti Pariyani  
**BITS ID:** 2025MB26028  
**Course:** MBA ZG583 — Management of AI Products  

---

### 1. Key Learnings & Takeaways
* **Beta is Only the Starting Line:** Releasing a beta version or working prototype accounts for barely half the total product effort. The real work begins when handling messy edge cases, non-linear user inputs, and unexpected failure modes in production.
* **Deferring Architecture Decisions Wisely:** Prematurely locking down an infrastructure stack before understanding actual user traffic and latency tolerance creates costly technical debt. PMs should keep architecture modular and delay heavy vendor commitments until operational constraints are clear.
* **Layered System Design:** Separating the user experience layer from the underlying AI model allows the team to swap or upgrade models without breaking the front-end user workflow.
* **Feedback Loops as Product Assets:** Designing intuitive mechanisms for users to correct or thumbs-down AI outputs is critical—not just for troubleshooting, but for continuously curating high-value evaluation datasets.

---

### 2. What Resonated Most With Me
Today's discussion on avoiding premature architecture lock-in was particularly timely for our team as we brainstorm our AI Twin capstone. It is tempting to pick an end-to-end proprietary framework right away because it looks polished in tutorials, but Professor Vinaya's warning about vendor lock-in and unexpected pricing spikes made me rethink that approach.

I also appreciated the conversation around "beta syndrome." Too often in corporate projects, teams celebrate the prototype launch as if the job is done, only to get blindsided by production issues—like API rate limits, slow response times, and inconsistent formatting. Thinking through how users will actually recover when the AI gives a wrong or awkward answer needs to be designed on day one, not treated as a post-launch bug fix.

---

### 3. Constructive Thoughts & What Could Be Explored Further
* While deferring architecture decisions is sound advice, teams often face pressure from leadership to commit to specific vendor budgets early on. A short template or decision matrix on how to present "flexible, staged architecture" to finance stakeholders would be a great practical addition to this module.

---

### 4. Personal Action Item
Work with my teammates on the AI Twin project to map out at least three distinct error-recovery pathways in our user journey so that if an LLM call fails or times out, the user is never left staring at a blank screen or a generic error code.

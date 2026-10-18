**Name** - Achal Tiwari

**Registered No** - 2025MB26002

# **Management of AI products**

**10th Session Topic:** Operating AI Products at Scale: Expectations, Latency, Routing, Throttling and Agent Governance.

# **Management of AI Products - Class Reflection**

**1. Class Overview** This session moved to running AI products once demand grows. We discussed how customer expectations shift, rationing capacity even in free products, designing for perceived latency, planning for peak periods, routing between models, throttling, priority lanes, and why governance has to grow faster than the number of agents.

# **2. Key Concepts and Discussions**

- **Even Free Products Ration:** WhatsApp and Gmail have limits, and those limits assume people want more of a good product.
- **Expectations Shift:** What customers put up with and what pleases them keeps changing. People once accepted that a letter took a week to arrive. Customers should be warned before planned downtime, like the bank that announced a late-night SMS outage in advance.
- **Perceived Latency:** A predictable wait feels better than an erratic one, and breaking a task into visible steps makes it feel shorter.
- **Routing and Throttling:** Use the newest model where it performs, an older one elsewhere, and keep the ability to switch. Throttle requests yourself before a provider blocks you.
- **Priority Lanes:** In the express and passenger train example, on-time performance is measured by class of service.
- **Caching With Limits:** Caching and truncation cut cost, but one user's cached answer cannot be served to another.
- **Agent Governance:** Governance must grow faster than the number of agents.

# **3. Important Insights**

- **Rationing Is a Design Decision:** Decide how to ration before demand decides it for you.
- **Peaks Need Planning:** After release the team makes the daily calls, so alerts and plans for peak periods have to be in place early.
- **Where I Differ:** Priority lanes for VIP customers suit a bank or a railway. In a study app for school students I am uncomfortable with them. A free student the night before an exam needs help as much as a paying one, so I would rather slow everyone slightly and protect safety responses for all.

# **4. Practical Learnings**

- **Sparks as a Throttle:** Infi gives each student a free daily allowance of Sparks that refills on a rolling 24-hour basis, with paid packs on top. We designed it as a pricing and habit tool, but it also caps how much model capacity one student can use in a day. I want to review it against cost per action and peak load as well as revenue.
- **Routing on Infi:** Routine chat could run on a lighter model and homework solutions on a stronger one.
- **Exam-Eve Peaks:** Our festival season is the night before board exams. Before the board exam season I will plan load alerts, a routing fallback and a clear message to students if things slow down.
- **Progress States:** Our early voice design used visible states for listening, thinking and speaking. Long homework answers need the same.

**5. Conclusion -** I had not thought of Sparks as a capacity tool before this class. My open question is where throttling to control cost turns into rationing help that a student actually needs, and how to tell a student about a limit without it feeling like being cut off in the middle of a doubt.

---

*AI use: draft written with Claude (Opus 5.5); facts and work examples checked by me. Model, prompt and sources are in AI-Use-Disclosure.md.*

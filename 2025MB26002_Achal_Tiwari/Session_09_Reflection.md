**Name** - Achal Tiwari

**Registered No** - 2025MB26002

# **Management of AI products**

**9th Session Topic:** Judging AI by the Economics of Its Errors: Payoff Matrices, Tail Risk, Experiments and Feedback Loops.

# **Management of AI Products - Class Reflection**

**1. Class Overview** This session was about evaluating AI products by what their mistakes cost. At its centre was a loan example that turned a confusion matrix into money. We also discussed tail risk, how metrics should change as a product matures, A/B testing and its pitfalls, feedback loops, and drift in third-party models.

# **2. Key Concepts and Discussions**

- **Evaluation vs Market Feedback:** A classmate argued that evaluation is in our control and the market's reaction is only feedback. The professor partly agreed and added that a PM can see shifts coming by watching technology, competitors and regulation.
- **Accuracy Misleads:** With imbalanced data, such as two bad loans in a hundred, a model can look very accurate while missing half the bad loans.
- **Economic Payoff Matrix:** Each cell of the confusion matrix gets a business value. The model supplies the error rates and the business supplies the value of each outcome.
- **Tail Risk:** Averages hide rare, severe events, so edge cases need testing and simulation. Safeguards should match the stakes.
- **Experimentation:** We went over A/B tests with test and control groups, and how standard error tells you whether a difference is real. Outside events and other changes running at the same time can distort results, and people who know they are being measured behave differently.
- **Feedback Loops:** Unchecked loops can pull a product towards a vocal or very active minority.
- **Third-Party Drift:** A cloud model can get better or worse without notice, so evaluation has to keep running after launch.

# **3. Important Insights**

- **One Default Cancels Many Good Loans:** A good loan earns a small spread and a default loses a large amount, so one bad loan can wipe out the profit from dozens of good ones.
- **What Are We Ignoring:** The professor asked us to always say what we are optimising and what we are choosing to ignore.
- **Where I Differ:** The payoff matrix works when every cell can be priced. For a child's safety I do not think we should put a rupee value on the worst cell. Some outcomes should be fixed limits that no profit calculation can trade away.

# **4. Practical Learnings**

- **Infi's Distress Check:** When a student writes something that may signal distress or self-harm, Infi has to switch to a careful response with helpline numbers. These messages are rare, so accuracy means almost nothing. A false alarm costs an awkward moment and a miss costs far more, so the threshold has to lean towards catching every real case. I want to write this payoff table with our AI lead before any tuning.
- **Voice vs Text Test:** For Infi's planned voice versus text test with older students, I will record exam dates and app releases during the test window.
- **Segments Over Averages:** The most active students will probably spend a lot of time in the fun modes. If we tune Infi on them alone it could drift away from quieter students who come for doubts, so engagement should be read by segment.

**5. Conclusion -** This session gave me a better way to argue about safety thresholds, with numbers where numbers make sense and fixed limits where they do not. My open question: distress messages are rare, so how do we collect enough real examples to measure how many we miss, without anyone reading children's private chats?

---

*AI use: draft written with Claude (Opus 5.5); facts and work examples checked by me. Model, prompt and sources are in AI-Use-Disclosure.md.*

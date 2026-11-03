# Class Reflection — 10 October 2026

The discussion about metrics made me think about how easily we can feel confident when a dashboard shows good numbers. In software development, a build can be successful and most validation tests can pass. But that does not automatically mean the customer will have a good experience. One failure that happens only in a particular condition may be more serious than many minor issues that are easy to reproduce.

I connected this with the professor's point about averages and tail risks. If a device boots correctly most of the time but fails during an important restart, the average success rate alone will not tell the complete story. Similarly, in AI products, accuracy alone does not show the cost of a wrong decision. A false alarm and a missed critical problem may have very different consequences.

The class also made me think about measurements after a release. Sometimes our attention naturally moves to the next development task once something is delivered. But actual usage and field feedback can reveal what our test environment did not cover. The metrics should change as the product matures, instead of remaining the same simply because we have always reported them.

I want to apply this by looking beyond overall pass percentages in software reviews. I should pay more attention to repeated failures, difficult operating conditions, customer impact and the cost of errors. The question I want to ask more often is: **Are we measuring what matters to the customer, or only what is easy for us to measure?**

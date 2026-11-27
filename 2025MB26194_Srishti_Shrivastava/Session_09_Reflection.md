# Class 9 Reflection

**Date:** 10 October 2026  
**Topic:** Business metrics, payoff matrices, tail risk and A B testing

The loan example was the clearest reminder that accuracy can be misleading. If one bad loan loses as much money as many good loans earn, a model can look accurate and still create a financial loss. The cost of each kind of error matters more than a single headline percentage.

I found the payoff matrix useful because it keeps the business decision visible. Precision, recall and F1 score are helpful, but they do not tell us what a wrong decision actually costs. The product manager still has to define the impact of a false positive, a false negative, delay and manual review.

The discussion of tail risk also made sense. Average performance can hide the rare cases that cause the biggest damage. Those cases need deliberate testing instead of waiting for them to appear after launch. Similarly, a small improvement in an A B test should not be celebrated without checking sample size and uncertainty.

For Wayfinder AI, a rare fabricated safety instruction could matter more than hundreds of correct routine answers. We therefore need to measure unsupported answers, incorrect citations, abstentions and escalations, not just overall answer accuracy or response speed.

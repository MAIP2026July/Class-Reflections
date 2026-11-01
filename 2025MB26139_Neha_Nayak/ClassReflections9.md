# Management of AI Products: Class 9

This session looked at how AI products should be measured and evaluated from a management point of view, not just a technical one. It covered why metrics shape trust, margins and workflow, and why model-level scores can mislead. It also covered how to design experiments, learn from feedback, and choose a small set of metrics that reflect real business value and risk.

## Core Concepts
- **Economic-value metrics over mathematical accuracy**: Precision, recall and accuracy don’t capture the unequal payoffs between outcomes. Build a payoff matrix with the profit, loss and opportunity cost of each prediction type, because one bad decision can wipe out the gains from many good ones.
- **Tail risk and survivability**: Averages hide edge cases, and edge cases can shut down a product or company. Product managers must look at worst-case scenarios, simulate them, and decide how much risk to carry versus transfer (for example through insurance or reinsurance).
- **Experimentation and feedback loops**: A/B testing needs hypotheses, control groups, significance checks and awareness of bias. With third-party LLMs that change underneath you, experiments are never fully controlled. Feedback can improve a product but can also over-tune it to one segment, so it needs governance.
- **Managerial lens on error types and metric design**: Ask who pays for false positives and false negatives, and how incentives and measurement systems drive behavior. Keep metrics few and simple (about three to start), tie them to a balanced scorecard, and evolve them as the product matures.

## Reflection and Insights
**A product is a promise of value.** Marketing only makes the promise. Reputation comes from the value users actually receive, so AI metrics should test whether the promise holds.
**Separate what you control from what you can only sense.** Evaluation quality is in your hands. Competitors, regulation and macroeconomics aren’t, but they can be anticipated, for example by comparing today’s competitive analysis with a projected one 18 months out.
**Optimizing the wrong metric is a hidden risk.** Revenue can look healthy while new-customer acquisition quietly declines. If your metrics haven’t changed as the product matured, you may be blind to an emerging trend or a disruptor attacking from another dimension, such as small, fast models replacing ever-larger ones.
**Probability assumes you survive long enough to play.** A model that is right on average is useless if a single catastrophic loss ends the game, so one-shot, irreversible decisions need far more caution than repeatable ones.
**Metrics are a managerial accountability.** The product manager owns metric design even when others draft it, because the metrics shape team behavior. Rewarding the wrong measure (such as raw bug counts) produces the wrong behavior.
**Societal and emotional impact count.** AI errors affect real people, and liability for them (vendor versus deployer) is often unclear. Stakeholders also decide differently under emotional stress, which a product must account for.
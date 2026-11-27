# Session 9 Reflection

| | |
|---|---|
| Date | 10 October 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | Innovation and competitive change, tail risk, economic value metrics, A/B testing and metric design |

## 1. Key concepts
The professor said every product starts as a hypothesis and is a promise of value. A straight copy of an existing product has very little chance. There has to be something new that gives us an edge, and our reputation depends on the value people actually get, not what we promise.

He used DeepSeek as an example of how fast things change: it wiped out a huge amount of market value almost overnight. He asked us to do Porter's analysis for now and for 18 months ahead, even if we get the future wrong.

Then he talked about averages hiding risk. A classmate in Los Angeles described how the wildfires pushed insurers out of business. The professor's coin-toss example made the same point: on average you break even, but you can run out of money long before the average works out.

The most useful part for me was economic value metrics. Instead of only accuracy, precision and recall, put a profit or loss in each cell of the confusion matrix. In his loan example, one bad loan wiped out the profit of about 40 good ones, so accuracy alone was misleading. He said business numbers are harder to game than precision and recall. A classmate added that we also need to know how much loss we can survive, and whether losses can spread.

He asked who pays for false positives and false negatives, because that decides who cares about fixing them. For example, a bank manager who will be promoted before a loan goes bad has little reason to worry.

On metric design, he said it is the PM's job. Dashboards change how teams behave and can reward the wrong thing, like testers holding back defects. He suggested a small, balanced set of about three metrics, not thirty. Metrics reflect goals but aren't the goals.

On A/B testing, he stressed control groups, standard error, sample size and significance before claiming anything. With AI it's harder, because the model, the people and the segments all keep changing, and people behave differently when they know they're being measured. A classmate mentioned Bayesian testing, which allows checking results midway. He also warned about feedback loops that make the product overfit to whoever complains the most.

## 2. What changed in my thinking
The loan example changed how I'll present my results. I was going to lead with "70% of arrivals within 45 minutes". But a wrong prediction that leaves the dock empty for a big delivery costs much more than one that makes an associate wait 20 minutes.

## 3. How I will apply it
For VendorPulse I'll weigh each type of error by its cost:
- **Missed early arrival:** the dock is empty, the vendor scans their own pallets, and shrink goes up.
- **Missed no-show:** an associate's time is wasted waiting.
- **False alarm:** only a small amount of extra staffing.

The dashboard will track three things: arrivals inside the window, associate-hours lost waiting, and receiving variances or shrink. In the pilot I'll compare pilot stores with similar stores that aren't using it, and check significance before claiming improvement.

## 4. Open questions
- How do we run a fair pilot when stores differ so much in vendors and volume?
- How big does a pilot need to be before a 5% improvement means anything?

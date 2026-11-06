# Class 9 Individual Learning Notes

**Course:** Management of AI Products  
**Recording date:** 10 October 2026  
**Student:** Maharshi Pandit  
**BITS ID:** 2025mb26121

## My Learning and Reflection

The strongest learning for me from Class 9 is that **model accuracy is not the same as product value**. A Product Manager must translate every correct and incorrect Artificial Intelligence decision into business value, customer impact, operational effort and risk. Precision, recall and accuracy are useful, but they cannot decide the product trade-off on their own.

The bank-loan example made this very clear. The professor assumed a loan of ₹1,00,000, a deposit cost of 7% and a lending rate of 9.5%. The bank earns only about ₹2,500 from one good loan, but may lose nearly ₹1,00,000 when a wrongly approved borrower defaults. Therefore, one bad loan can wipe out the profit from around forty good loans. A model may show 90% or even 98% accuracy and still make a poor business decision if the costly error falls in the wrong cell of the confusion matrix.

I understood that the Product Manager should create an **economic payoff matrix** for all four outcomes. A correctly approved good borrower creates limited profit. A wrongly approved bad borrower may create a major loss. A wrongly rejected good borrower creates an opportunity cost. A correctly rejected bad borrower avoids a loss. This is more useful than arguing mechanically that precision or recall is always the correct measure. The right trade-off depends on the use case, the value of each decision and who carries the consequence.

The motorcycle-and-guitar example showed another side of error impact. The system apparently treated a guitar strapped behind the rider as a pillion passenger without a helmet and issued a notice. In that case, the error became unusual news, but the same type of mistake could lead to customer harassment, legal claims or loss of public trust. The technology provider, government agency and affected person may each view the error differently. This reminded me to ask who gains, who pays and who remains accountable for every error type.

The discussion on tail risk was also important. Average performance can look acceptable while one rare event destroys the product or organisation. The California wildfire and 2008 financial-crisis examples showed that correlated failures and extreme events can overwhelm normal assumptions. The casino example made survivability simple: probability may assume that the player can continue indefinitely, but a real business can run out of money before the long-run average is achieved. Product evaluation should therefore include worst credible cases, cascade effects and whether the organisation can absorb the loss.

I also learned that metrics must evolve with the product. Total revenue may continue rising because existing customers buy more while new-customer acquisition is falling. If the team continues reporting only revenue growth, the dashboard hides an emerging weakness. The Product Manager should regularly review whether current metrics still represent the product’s real health.

The class also showed how metrics can create unintended behaviour. If testers are rewarded only for the number of defects reported, they may wait for defects to reach testing instead of helping prevent them earlier. If employees record a standard eight hours regardless of actual effort, the data cannot support reliable planning. A balanced set of a few measures is better than one misleading Key Performance Indicator or a dashboard with thirty measures that nobody can optimise.

The discussion on A/B testing reminded me not to celebrate small improvements without evidence. A customer-satisfaction score increasing from 4.5 to 4.8 may be real or may be random variation. Sample size, standard error, control group and statistical significance matter. Artificial Intelligence experiments are even more difficult because an external provider such as OpenAI or Anthropic may be changing the underlying service while the product team is running its own experiment.

Finally, I understood that feedback loops can improve a product but can also over-customise it for one segment. The team may treat one sample as the full population and gradually make the core product unsuitable for others. A better design may preserve a stable core and use a configurable layer or personalisation wrapper for specific segments.

## How I Can Apply This Learning

For RiskReview AI, I will not evaluate success only through duplicate-detection precision or the number of risks flagged. I will measure useful findings, incorrect duplicate suggestions, changed-meaning incidents, missed weak risks, preparation time saved, human correction effort and severe unsupported outputs. A fabricated project fact or changed risk meaning should be a launch blocker even if average usefulness is high.

I will also create an economic and operational payoff view for each finding type, define who bears the cost, and use a small balanced set of metrics that changes between prototype, pilot and wider deployment.

## My Main Takeaway

My main takeaway is that Artificial Intelligence metrics become useful only when they are translated into managerial consequences. The Product Manager must look beyond average accuracy and ask: **Who gains, who pays, what is the worst credible failure, and can the product survive it?**

---

**AI-use disclosure:** Microsoft Copilot was used to organise and improve the wording of these notes. The examples, interpretation and reflection are based on my understanding of the uploaded Class 9 recording.

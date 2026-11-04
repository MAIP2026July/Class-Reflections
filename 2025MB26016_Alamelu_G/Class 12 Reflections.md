# Reflection: Session 12

31 October 2026 | Alamelu G | 2025MB26016

---

This class made me look at AI products from a more business and financial perspective. We have discussed building products, understanding customers, managing risks and scaling AI in the previous sessions. This time, the focus was more on how the product actually makes money and whether the business model is sustainable. I realised that having a good product does not automatically mean it will be a successful business.

**The point that stayed with me.** "Start with the value to the customer and work backwards."

The discussion around target costing was interesting. Usually, I think we first calculate how much it costs to build something and then add a profit margin to decide the selling price. But the faculty explained the opposite approach. First understand how much the customer is willing to pay based on the value they receive, decide the margin we want and then work backwards to figure out how much we can spend on building and running the product.

This made a lot of sense because we may build something technically excellent, but if the final price is too high compared to the value customers see, the product may struggle commercially. So the product manager has to think about profitability even before the product is fully developed.

**The input vs output pricing discussion was probably my favourite.** The faculty explained that customers are interested in the output and value they receive, whereas the product company is more concerned about the input costs. For example, when we use an AI API, we pay based on tokens or API calls, but the customer is not interested in how many tokens were consumed. They want the actual result.

The example of charging for marketing leads versus charging for successful sales was interesting. A company may currently charge for every lead generated, but the customer is actually interested in converting those leads into sales. Moving to outcome-based pricing could create more value for the customer, but it also means the product company takes on more risk because the final conversion is not completely under its control.

This made me think about how important it is to understand what the customer is actually buying rather than just looking at what our product delivers technically.

**Where I slightly disagree.** Outcome-based pricing sounds attractive, but I think it can become difficult when the final outcome depends on factors outside the product. For example, if an AI product generates a good lead but the sales team does not follow up properly, should the product company still be held responsible for not achieving a sale? There has to be a clear understanding of what the product can control and what it cannot. Otherwise, even a good pricing model can create disagreements between the customer and the product company.

**The workflow and documentation discussion also connected with the previous classes.** The faculty reviewed some of the project submissions and pointed out that words like "accurate", "user-friendly" and "reduction in consultation time" are too vague. We need to put actual numbers wherever possible. Saying that consultation time should reduce is not enough. We should define whether we expect a 10% or 30% reduction.

I found this particularly useful because requirements can be interpreted differently by different people. What is accurate for one person may not be accurate for another. If these expectations are not defined properly, the development team or vendor may build something completely different from what we expected.

**The swimlane diagram example was useful.** I had not given much thought to how workflows should be represented, but the faculty demonstrated how PlantUML and Mermaid can be used to create diagrams through text. What I liked about swimlane diagrams is that they clearly show what each stakeholder does and what the system does.

For an AI product, we can also identify which steps are deterministic, which steps use AI and where human intervention is required. This makes it easier to understand where uncertainty exists and where fallback mechanisms are needed.

The C4 model was another interesting concept. I understood that product managers don't necessarily need to go into every technical detail or code-level architecture, but they should understand the overall system, its components and how they interact. This is enough to have meaningful discussions with the technical team and understand the product's architecture and costs.

**The cost of serving customers was another important learning.** We discussed how inference costs can increase when customers start using the product more frequently. A product may look profitable initially, but if every additional customer increases the cost significantly, the business model may not work at scale.

I also found the discussion on contribution margin interesting. Not every customer segment or workflow contributes equally to profitability. Some customers may use more resources and generate lower margins, while others may be more profitable. So we should understand which customer segments are actually contributing to the business rather than simply celebrating an increase in the number of customers.

I also liked the point about downselling instead of always trying to upsell. Sometimes offering a smaller plan to a customer may help retain them rather than losing them completely. I usually associate business growth with selling more, but retaining customers through the right pricing can also be a sensible strategy.

**One more thing I noted was platform economics.** The example of WhatsApp made it easier to understand why some platforms are difficult to replace. Their value increases as more people join because the connections between users also increase. So a new product entering an existing ecosystem may find it difficult to compete even if its features are good.

This also made me think about whether AI should always be a standalone product or whether it makes more sense to embed it into an existing product as a premium feature. The right approach depends on the customer, the market and how the product creates value.

**What I will take forward.** For our own product, I want to spend more time understanding the actual value customers receive and how we can convert that into a sustainable pricing model. We should calculate development costs, inference costs, operational expenses and expected revenue instead of just assuming that more customers will automatically mean more profit. I also want to make our workflows and requirements more specific so that the development team has fewer assumptions to make.

**Open question.** I am still thinking about how to price AI products when usage and inference costs are unpredictable. A customer may pay a fixed subscription but suddenly start using the product much more than expected. A usage-based model may protect the company's margins, but customers may not like unpredictable bills. So how do we create a pricing model that is fair to customers while still allowing the product company to remain profitable?

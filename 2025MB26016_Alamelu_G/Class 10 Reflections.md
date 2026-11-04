# Reflection: Session 10

17 October 2026 | Alamelu G | 2025MB26016

---

This class made me think about what happens when an AI product actually becomes successful and more people start using it. Until now, I had mostly looked at building the product, solving the problem and making sure it works. But scaling it introduces a completely different set of challenges. More users and more usage can be good, but if the product cannot handle the demand or the cost becomes too high, the same success can become a problem.

**The point that stayed with me.** "Every product is a promise." I think this was one of the most important points from the class. Customers don't really care how many servers or how much infrastructure we have. They care about whether the product delivers what it promised. The Uber example made this very clear. Even if the app is working perfectly, if there are no drivers accepting the ride, the actual customer promise is not fulfilled.

I also liked the discussion about how a product becomes mission critical over time. Initially, customers may be okay with occasional downtime because they have other options. But once they start depending on the product for their daily work, even a short disruption can create a lot of frustration. This means that as product managers, we have to understand how much customers depend on our product and what happens when it is unavailable.

**The cost side of AI was something I found very relevant.** We discussed how using AI is becoming necessary, but the cost of using it cannot be ignored anymore. A product may have a great demonstration and attract customers, but if every customer request costs too much to process, the business model may not be sustainable.

The discussion around using smaller language models versus larger frontier models was interesting. I initially thought that using a more powerful model would generally give better results. But not every request needs the most powerful model. A simple query can be handled by a smaller model, while more complex tasks may need a larger one. This could help control costs without compromising too much on quality.

**Where I slightly disagree.** I agree that we need to balance quality, speed and cost, but I don't think there is one fixed sweet spot that can work for every customer. Some customers may prefer a quicker response even if it is slightly less detailed, while others may be willing to wait longer for a more accurate result. The faculty also shared an example where customers preferred predictable processing time over simply getting the fastest response. That made me realise that we should understand customer expectations before making these trade-offs.

**The scalability discussion was more than just handling traffic.** I found it interesting that scaling also includes data growth, model performance, workflow complexity and organisational dependency. For example, an AI product designed for one particular use case may not perform well when customers start using it for something slightly different. Similarly, stale data or data missing for a particular geography can affect the product even when the underlying model is working correctly.

The discussion around API rate limits and queues was also useful. Initially, a product may work perfectly with a small number of users, but once usage increases, external providers may start restricting the number of requests. Then we have to decide which customers get priority, whether requests should be queued and what service guarantees we can provide to different customer segments.

**Another important learning was operational ownership.** The faculty discussed monitoring, alerting, deployment repeatability and versioning. I had generally thought of these as technical or engineering responsibilities, but the class made me realise that the product manager cannot completely separate themselves from these areas.

The example of the electricity distribution company was useful here. If power consumption in a particular locality suddenly drops or increases unexpectedly, the system should detect it and generate an alert. The product manager should understand these business signals rather than simply waiting for someone to share a technical report.

I also noted the importance of versioning and traceability. It is not just about keeping track of software versions. We also need to track changes in data, models and experiments so that if something goes wrong, we understand what changed and whether we can roll back. This seems especially important for AI products because model updates can affect different customer segments differently.

**What I will take forward.** When thinking about an AI product now, I want to consider not just whether it works but whether it can continue working when usage increases. I should look at the actual cost per request, response time, model selection, customer expectations and what happens when an external API reaches its limits. I also want to remember that technical monitoring should always connect back to the customer promise. Having good infrastructure is useful only when it helps us deliver that promise consistently.

**Open question.** I am still thinking about how product managers decide how much to invest in scalability before the product has a large customer base. Building everything upfront can increase costs unnecessarily, but waiting until the product starts growing may create problems for existing customers. Finding the right balance between preparing for growth and not over-investing too early seems like an important judgement a product manager has to make.

# Class Reflection — 17 October 2026

Before this session, I mostly associated scaling with handling more users, more requests or more computing load. The professor's discussion gave me a broader way to look at it: when customers depend on a product, we are responsible for keeping the promise that made them use it in the first place.

This connects with embedded software products. For an engineering team, releasing a BSP or a tool may look like a technical milestone. For a customer who uses it in an industrial system, the expectation is different. They care about reliable operation, predictable behaviour, support and what happens when something fails. A product that performs well in a demo but becomes unreliable under real usage has not really scaled successfully.

I also found the quality, latency and cost trade-off interesting. In AI products, using the biggest model for every request might improve some answers but may not be economical. For example, a small local model could be worth exploring for basic log categorisation or a limited offline assistance task, while a more capable model may be justified for complex troubleshooting across multiple documents. Even then, privacy, response time and the need for human review matter.

My takeaway is that the product manager needs to explain these trade-offs clearly to the team, rather than simply asking for the fastest or most accurate solution. I would like to become more disciplined about defining what reliability, response time and cost are acceptable for a particular customer use case. **Scaling the technology is useful only if the customer promise scales with it.**

Session 9 Reflection: Managing AI Beyond Model Performance

One of my strongest takeaways from this session was that the most powerful AI model is not necessarily the best choice for a product. As someone from a software development background, I naturally tend to look at technical capability and performance first. This session made me think more broadly about the trade-offs between accuracy, latency, cost, reliability, and user experience.

The discussion around using smaller and larger models was particularly relevant to me. A larger model may produce better results for a complex task, but using it for every request can increase response time and operating cost. In some situations, a smaller model may be sufficient, while more complex requests can be routed to a larger model.

I could relate this to my experience managing enterprise software solutions. We often have multiple ways of solving the same problem technically, but the most sophisticated solution is not always the most practical one. The right solution is the one that meets the business need reliably while keeping performance, cost, maintainability, and customer experience balanced.

Another point that stayed with me was the discussion around predictability and user experience. Users may sometimes accept a slightly slower response if they know what is happening and the behaviour is predictable. Inconsistent performance, on the other hand, can quickly create frustration and reduce trust. The session illustrated this through examples of managing processing time and communicating delays to users.

This made me think differently about AI performance. Earlier, I might have focused mainly on reducing response time. I now realize that consistency and expectation management can be just as important as absolute speed. From a product perspective, it may sometimes be better to provide a predictable experience than to optimize only for the fastest possible response.

The discussion on versioning and rollback was another area I could connect directly with my technical background. In conventional software development, version control and rollback are familiar concepts. What I found interesting was that AI products add another level of complexity. We may need to manage versions not only of the software, but also of models, data, and potentially different experiences for different customer segments.

A newer model may perform better overall but perform worse for a particular segment or use case. This means that upgrading should not automatically mean replacing the previous model everywhere. The Product Manager needs sufficient monitoring to detect degradation and the ability to switch, reroute, or roll back when required.

This was an important learning for me because, in enterprise systems, I have always considered rollback mainly as a technical release-management capability. Session 9 helped me see it as a product-management capability for managing risk and protecting customer trust.

The discussion on AI agents reinforced this further. As AI systems become more autonomous and involve multiple agents, the session emphasized that governance and controls need to scale along with that complexity. Monitoring, alerts, release discipline, and clearly defined controls become increasingly important.

From my managerial perspective, this means that adopting more AI does not automatically reduce management responsibility. In fact, it may increase the need for clear ownership, monitoring, escalation paths, and controls.

My Key Reflection

Session 9 helped me move beyond looking at AI primarily through the lens of model capability. A technically impressive model does not automatically create a good product. The real challenge is deciding how to balance capability with cost, latency, reliability, user expectations, and risk.

I also realized that Product Managers need to think about failure before it happens. If a new model performs poorly after deployment, we should already know how quickly we can detect it, who needs to respond, and whether we can safely revert or reroute the affected users.

My biggest takeaway is:

For an AI product, choosing the model is only one decision. The bigger responsibility is designing the product so that it remains reliable, economical, observable, and recoverable when the AI does not behave as expected.

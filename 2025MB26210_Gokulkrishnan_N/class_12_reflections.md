Name - Gokulkrishnan N

Registered No - 2025MB26210

Management of AI products

**12th Session Topic:** AI Product Economics – Target Costing, Outcome Pricing, Unit Economics, and Platform Strategy.

**Management of AI Products – Class Reflection**

**1\. Class Overview** This session connected product design to commercial survival. A product can solve a real problem and gain users yet still fail as a business if every interaction costs more than it earns. The class covered working backwards from customer value to set a cost limit, the gap between what AI costs us and what customers actually pay for, and how architecture choices protect or destroy margins. The session also reviewed project PRDs, focusing on vague requirements and on using diagrams to make workflows clear.

**2\. Key Concepts and Discussions**

- **Target Costing Instead of Cost-Plus:** Borrowed from Japanese manufacturing, target costing starts with the value the customer receives and what they are willing to pay. The required margin is then subtracted to find the maximum cost the product can afford to build and run. This makes profitability a design constraint from day one, instead of a number calculated after development.
- **Input Costs vs. Output Value:** AI providers charge us for tokens, API calls and compute, but customers do not care about any of these. They pay for outcomes: a qualified lead, a resolved claim, a faster decision. Customers especially resent paying for wasted effort, such as an agent looping endlessly or producing an unusable answer.
- **Architecture Follows Economics:** Pricing models shape system design. In the past, per-connection and per-CPU database licensing pushed teams to build connection pooling layers. Today, an agentic AI loop with no step limit or model routing can drain margins overnight. Cost controls must be part of the architecture, not an afterthought.
- **Ecosystems Compete, Not Features:** Competition increasingly happens between ecosystems (for example, the Microsoft stack against MERN or LAMP) rather than between standalone tools. Platforms like WhatsApp become hard to replace because their value grows with every new user. A standalone AI tool with no integration into an existing platform faces very expensive customer acquisition.

**3\. Important Insights**

- **Outcome-Based Pricing Shifts Risk to the Vendor:** Charging per sale instead of per lead aligns price with value, but the final sale depends on factors outside the product, such as whether the customer's sales team follows up. Outcome pricing works only when the outcome can be clearly defined, measured and influenced by the product. Otherwise it creates disputes about who caused the result.
- **Contribution Margin Over Customer Count:** In AI, every extra interaction carries a real cost, so more customers do not automatically mean more profit. Contribution margin shows which segments, tiers or workflows actually make money after variable costs. This extends the previous session's scaling theme: a product must scale economically, not just technically.
- **Downselling Can Protect Retention:** Moving a low-usage customer to a smaller plan can keep them longer than forcing an upgrade that leads them to cancel. Pricing should match the value each customer receives, not maximise short-term revenue.

**4\. Practical Learnings**

- **Quantify Every Requirement:** Words like "accurate", "user-friendly" or "reduced consultation time" leave room for different interpretations between the PM, engineers and vendors. A PRD should state measurable targets, such as a 30% reduction in consultation time, so success can be checked objectively.
- **Diagramming as Code:** Swimlane diagrams written as text in PlantUML or Mermaid can be version-controlled in Git. They clearly separate deterministic steps, AI-driven steps and human checkpoints, which shows exactly where fallback and escalation are needed. The **C4 model** gives a PM enough architectural understanding of systems, components and data flows to discuss latency, cost and dependency trade-offs without going down to code level.

**5\. Conclusion -** This session made it clear that economics has to shape an AI product from the beginning. Customer value sets what we can charge, while architecture, model choice and usage patterns set what it costs to deliver. A product manager has to balance both sides: define measurable outcomes, design cost controls into the system, and choose a pricing model that stays fair to customers as usage grows while still keeping the business profitable.

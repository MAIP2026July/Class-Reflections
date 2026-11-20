# **Session 8 Reflection**

**Date:** 3 October 2026\
**Topic:** AI Reliability, RAG, Prototyping, Progressive Automation & Product Governance

This session made me look at AI product development from a slightly different perspective. As someone with a software development background, I am used to working with systems where the same inputs generally produce predictable results. With AI, however, getting the expected output once does not necessarily mean the system will behave consistently in production. Building a working demo is one thing; building something reliable enough for real users is a much bigger responsibility.

The discussion around AI reliability was particularly relevant. Model behaviour can change even when there are no changes in the application code. Updates from the AI provider, changes in model behaviour and the probabilistic nature of AI can all affect the output. This made me realise why production monitoring, fallback mechanisms and continuous validation are essential for AI-based applications.

I also found the discussion on RAG useful. It reinforced the idea that AI should be used where it genuinely adds value. RAG is helpful when an application needs to retrieve information from a large knowledge base and use that information to generate relevant responses. However, calculations, validations and business rules should continue to use deterministic logic wherever consistency is important. In practice, a good solution may combine APIs, traditional programming, business rules, retrieval and LLMs instead of depending on a single model for everything.

Another interesting point was vendor flexibility. Depending entirely on one AI provider can create risks if its pricing, availability, latency or model behaviour changes. At the same time, switching between providers is not always straightforward because different models can produce different results even with identical prompts. So, flexibility needs to be considered during architecture design, while also understanding the additional complexity it can introduce.

The Prototype, Pilot and Scale approach was another important learning for me. Earlier, I mostly viewed a prototype as an early version of the final application. Now I understand that each stage should have a different purpose. A prototype checks whether an idea is technically possible, a pilot tests it with real users and actual working conditions, and scaling should happen only when there is enough evidence that the solution works reliably.

I particularly liked the idea of learning before automating. Automating an entire process from the beginning may hide important exceptions and edge cases. Keeping some steps manual initially allows teams to understand how the workflow actually operates. Human intervention, overrides and fallback options should be part of the design, with automation increasing gradually as the system becomes more reliable.

Finally, the session helped me understand governance as a way to make better decisions rather than simply adding approval processes. Each development stage should have clear objectives and evidence-based decision criteria. Sometimes the right decision may be to rework an idea or stop it altogether instead of continuing to invest in something that is not delivering the expected results.

My biggest takeaway from this session is that AI product development is about reducing uncertainty step by step. The objective should not be to automate everything as quickly as possible, but to build confidence in the system before increasing its responsibilities. A product becomes successful not just when it works, but when it continues to work reliably under real-world conditions.

# Session 8 Reflection

**Date: 3 October 2026**  
**Topic: AI Reliability, RAG, Prototyping, Progressive Automation & Product Governance**

This session made me realise that getting an AI solution to work during development is very different from making it reliable in a real-world environment. AI systems can behave differently over time, even when nothing has changed from our side. This helped me understand why continuous monitoring is important after an AI product is deployed.

The discussion on **RAG** was also useful. My understanding is that we should not use AI for every part of a product just because we can. RAG works well when we need to retrieve information from a large knowledge base, but for calculations, validations or processes where the result needs to be consistent every time, APIs or rule-based logic may be more suitable. A good AI product can therefore use a combination of AI and traditional systems.

I also got better clarity on **prototype, pilot and scaling**. A prototype helps us check whether an idea can work, while a pilot helps us understand how it performs with real users and actual business conditions. A successful demo alone does not mean that the product is ready to scale.

The idea of **“learn before we automate”** stood out to me the most. Instead of automating the entire process immediately, keeping humans involved initially can help us identify errors, edge cases and situations we may not have considered. As confidence in the system improves, automation can gradually increase. Having manual overrides and fallback options is also important when the AI does not behave as expected.

The governance discussion also helped me understand that each stage of AI product development should have a clear purpose. We should know what we are trying to prove before moving to the next stage rather than continuously adding features.

Overall, my biggest learning from this session was that building an AI product is about **gradually reducing uncertainty through testing, learning and validation**, rather than trying to achieve complete automation from the beginning.

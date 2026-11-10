
Reflection: Session 8


This session made me realise that building an AI product is not just about selecting a good model and getting the expected output during development. Even if something works well during testing, its behaviour may change in production. The discussion around model and provider-side instability helped me understand why continuous monitoring is important.
Another useful learning for me was around RAG and deterministic vs probabilistic outputs. Not every problem needs an LLM. For tasks where the output must be accurate and consistent every time, a normal API, calculation or rule-based solution may work better. RAG is useful when we need to retrieve information from a large knowledge base, but the overall product can be a combination of AI and traditional systems.
I also got better clarity on prototype, pilot and MVP. A prototype mainly helps us understand whether an idea can work, while a pilot helps us see how the solution behaves with actual users. A successful demo does not necessarily mean that the product is ready to scale.
The point I liked the most was “learn before we automate.” Instead of automating everything from the beginning, keeping some manual intervention initially can help us understand where the AI is making mistakes. Having manual overrides and fallback options also seems important, especially when the AI is uncertain.
The governance discussion also made sense to me. Before starting each stage, we should be clear about what we are trying to prove and what success looks like. For our own project, I think this will help us start small, validate the important assumptions first, and then gradually move towards wider automation and scaling.

#Class Reflection — 22 August 2026

My biggest reflection from this session was a simple question: Just because AI can be used, should we use it?

In my technical work, new technologies naturally attract attention. Edge AI, NPU acceleration, LLMs and other AI capabilities create many possibilities. But this class made me think that the starting point should not be the technology. It should be whether AI creates incremental value for the user compared with a simpler solution.

I can relate this to industrial embedded products. Suppose a customer wants equipment-health monitoring. We could immediately think about anomaly-detection AI. But if two deterministic thresholds can reliably solve 95% of the actual problem, adding an AI model may increase development effort, validation effort and support complexity without creating enough additional value.

The discussion on downside and Human-in-the-Loop was equally important. If an AI recommendation is wrong, I need to ask who carries the impact. For a low-risk recommendation, some error may be acceptable. For a safety-related or business-critical action, the same error percentage may be unacceptable.

So my takeaway is to use a simple sequence before proposing AI:
What job is the user trying to complete? → What value does AI add? → What happens when AI is wrong? → Where should a human retain control?

That is a more responsible way for me to think about AI products than starting with “Which model should we use?”

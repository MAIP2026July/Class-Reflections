**Name** - Achal Tiwari

**Registered No** - 2025MB26002

# **Management of AI products**

**8th Session Topic:** Building With Unstable AI: Provider Volatility, Rules vs LLMs, and Gates From Prototype to Scale.

# **Management of AI Products - Class Reflection**

**1. Class Overview** The first class after the midterm looked at what it takes to build on AI that keeps changing underneath you. We discussed the difference between a model's own error and instability on the provider's side, grounding and RAG, when a rule beats an LLM, the PM as a bottleneck when reviewing agent output, staged automation, and the gates between prototype, pilot and scale.

# **2. Key Concepts and Discussions**

- **Model Error vs Provider Instability:** With seed and temperature fixed, a model's error should stay in a narrow band. The professor described coding tools that ran long chains of work one day and stopped after one step the next, and he could not tell whether the model or the harness had changed.
- **Grounding and RAG:** Grounding depends on the base model, the system prompt, examples and memory. One big vector store does not hold up at scale, and deterministic queries like arithmetic or lookups should go to rules or APIs.
- **Rules Where Output Must Be Exact:** An insurance premium calculator has to return an identical premium every time it gets identical inputs, which rules out an LLM for that step.
- **Learn Before We Automate:** Start with transparent human review, use confidence thresholds to route uncertain cases, and widen automation as evidence builds.
- **Prototype, Pilot, Scale:** A prototype shows feasibility, a pilot tests value inside a real workflow, and scale tests whether the economics and failure handling survive volume. Decide what success looks like before the pilot begins.
- **Pluggable Architecture:** It should be possible to swap the model or a provider without rewriting business rules.

# **3. Important Insights**

- **The PM as Bottleneck:** Agents need repeated nudging, and people flooded with AI proposals start approving them without checking. Small wrong assumptions get in this way, like the tool that decided every output must contain three banks.
- **Be Honest About What Is Manual:** Partial automation is fine if the core is right, as long as you say what is still done by hand.
- **Where I Differ:** Writing success criteria before a pilot is the easy part. The harder part is agreeing in advance who can say stop, because once a team has spent months on something nobody wants to end it. A go/no-go gate needs a named decision-maker as well as a threshold.

# **4. Practical Learnings**

- **Our Provider Shock:** Infi's architecture documents named a specific Gemini Live model, and Google shut it down on 1 June 2026. We had to revisit the migration target, the cost model and the voice plan without releasing anything ourselves. I will keep a provider watch list and review it every month.
- **Sparks Stays Deterministic:** Sparks balances, debits and purchases must come from fixed logic. The model can talk about Sparks, but it should never decide the number.
- **Pilot Criteria:** We wrote down Infi's activation and Day-7 retention targets early. Next I want every pilot to name the person who can stop it.

**5. Conclusion -** After this class I see provider changes as a normal part of running an AI product. My open question is how to notice when a provider quietly changes a model in production, since we cannot check every answer. A small fixed test set run every day may be enough, but someone on a small team has to own it.

---

*AI use: draft written with Claude (Opus 5.5); facts and work examples checked by me. Model, prompt and sources are in AI-Use-Disclosure.md.*

# Reflection: Session 4

22 August 2026 | Joydev Pain | 2025MB26105

---

*"Do not default to a foundation model. Start at the lowest rung that solves the job: deterministic rules, then retrieval, then predictive models, and only then generative or agentic systems."*

In enterprise architecture, this is the definitive divide between a fragile AI gimmick and a defensible, governed product. Too many modern AI initiatives treat the foundation model as a universal computing engine, forcing LLMs to calculate burn rates, evaluate dates, or enforce hard SLA thresholds through fragile prompt engineering. 

We applied this hierarchy directly to our platform capabilities: deterministic boundaries—contractual dates, regulatory thresholds, financial limits, and severity counters—were extracted entirely from the generative layer and codified as deterministic validation rules. Offloading those constraints shrank the LLM's task to what it genuinely excels at: synthesizing unstructured narrative commentary across dozens of operational reports and highlighting anomalies that structured metrics miss. A product becomes defensible when you can justify why lower-rung methods fail before invoking a probabilistic model.

**The automation complacency trap: When efficiency eliminates oversight.** The core value proposition of an AI assistant is to reduce manual review overhead. Yet the acute risk this creates is automation complacency: when domain experts begin passively rubber-stamping AI recommendations, the systemic failure risk rebounds entirely onto the product owner. If an underwriter or delivery director blindly trusts a low-risk score on an account that is quietly deteriorating, a shallow human review is replaced with *zero review*.

The faculty’s architectural pattern—dual-track parallel evaluation where agreement passes silently and divergence demands human justification—is elegant, but difficult to justify across 100% of volume when the primary business case is cost elimination. A viable design adaptation for enterprise environments is **stochastic blind calibration**: routing a randomized 10% sample through blind review (where the human evaluates the case without seeing the AI's ranking). This provides an empirical baseline to measure human drift against model drift, proving far more effective than passive UI disclaimers.

**Cognitive apprenticeship: The hidden cost of eliminating mundane work.** During the class debate on automating triage, discussion divided between "saving an hour of developer time" and "downsizing operations." Both miss a critical failure mode: routine, repetitive analysis is often how human practitioners build tacit domain intuition. 

A junior analyst or engineer who manually wades through dozens of status reports or raw logs is absorbing subtle nuances, operational friction, and organizational subtext. If an AI delivers an executive-ready ranked briefing, they receive the conclusion without the context. Over time, the AI product risks eroding the very institutional domain expertise required to govern and correct the model when edge cases emerge. Routine work cannot be classified as pure operational waste without accounting for the loss of cognitive training wheels.

**Adoption, data contamination, and Goodhart’s Law.** Resistance to enterprise AI adoption is not irrational stubbornness; it is an intelligent response to perceived risk and switching costs. In enterprise systems, the positioning risk is severe: if teams perceive an AI system as an automated surveillance mechanism auditing their reporting integrity, they adapt rationally. They sanitize written narratives, withhold candid risk assessments, and feed the system benign corporate jargon. The high-fidelity textual signal the model depends on evaporates.

This dynamic is anchored in Goodhart's Law: *"Tell me how you measure me, and I will tell you how I behave."* If you measure operations managers on the speed of "AI flags resolved," they will optimize for clearing flags rather than remediating operational risk. Designing an AI product requires engineering the behavioral incentives surrounding the model just as rigorously as the model itself.

# Session 8 Reflection

3 October 2026 | Seelam Raviteja | 2025MB26062

The operating risk I had treated as a research topic is an ordinary management problem: the same instructions can behave differently tomorrow, and in production you may never see which customer received the weak answer.

During a build, that unpredictability is frustrating and usually reversible. After launch it is a service incident without a clear start time. The cause might be the model's own variation, or a provider change behind an API the team did not ship. For a number that must be the same every time, such as an insurance premium or a fee, a rule is often the better product. Generative output earns its place where variation is acceptable and a person can still check the result. I would write that choice down before anyone debates model quality.

"Learn before we automate" is the control that matches this risk. Automating a process the team does not understand makes the wrong action faster and wider. A human checkpoint looks inefficient in a spreadsheet. It is also how the team sees the exceptions. Staged automation, with a confidence threshold and a person on the uncertain cases, is a way to buy that learning. Full automation can come later, when the evidence says the residual errors are cheaper than the review. I would not set the threshold by taste. I would set it by the cost of a miss and the cost of a false alarm, and revisit it when the mix of cases changes.

The path from idea to scale needs gates for the same reason. A prototype shows that a path exists. A pilot shows that a real workflow will tolerate it. Scale shows that the economics and the failure handling survive volume. Skipping a gate because the demo went well is how a one-office success becomes an expensive rollout. The success criteria should be written before the pilot, so a disappointing result is allowed to stop the work. Moving the goal after the data arrives is a way to protect the project from the truth.

Pluggable architecture is the grown-up version of vendor risk. If the model, the messaging provider, or the scoring service can be swapped without rewriting the business rules, an outage or a price change is a substitution rather than a rewrite. The trade-off is real. Abstractions and fallbacks cost engineering time, and a young product can die under that overhead. I would make the core path replaceable, and I would not build a spare for every minor dependency on day one.

The last shift is about my own role. When generation is cheap, the scarce resource is the decision. A product manager who waves every suggestion through becomes the place where small wrong assumptions enter, such as a tool quietly deciding that a design must always include three options. Checking early is cheaper than unwinding a confident mistake after the team has built on it. Speed without that pause is not efficiency. It is unreviewed work at a higher rate.

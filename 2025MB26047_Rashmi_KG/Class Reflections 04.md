Class Reflection 4: Making Reversible Decisions and Giving AI the Right Level of Autonomy

Course: Management of AI Products
 Session: 4

My Reflection

This session made me think about product management from a perspective I had not consciously considered before: a good decision is not only about choosing the right option, but also about understanding what happens if the decision turns out to be wrong.

In my professional experience, considerable attention naturally goes into making the correct technical or delivery decision. We evaluate requirements, dependencies, risks, implementation effort and timelines before proceeding. What I had thought about less explicitly was the importance of designing decisions for reversibility.

The discussion around making decisions more like a“two-way door” was therefore particularly meaningful to me. The session explained that when customers are trying something new, reducing switching costs through easy exit, refunds or data portability can make experimentation less risky.

This changed the way I look at risk.

Earlier, my instinct would have been to reduce risk mainly by performing more analysis before making the decision. I now see another possibility:

Instead of trying only to increase certainty before making a decision, I can sometimes reduce risk by making the decision easier to reverse.

For me, this is a powerful idea, particularly in AI product management where waiting for complete certainty may not be realistic.

Proving That AI Actually Adds Value

Another part of the session that strongly resonated with me was the emphasis on measuring the value created by AI.

The class highlighted the importance of comparing the situation before AI and after AI, because without a baseline it becomes difficult to demonstrate whether AI has genuinely created additional value. It also emphasized that the benefit may differ across customer segments.

This is especially relevant to me because, with the current attention around AI, it is easy to interpret the presence of an AI capability as innovation by itself. The class made me question that assumption.

If I introduce AI into a workflow, I should be able to answer:

What was the performance before AI?
What changed after introducing AI?
Which users actually benefited?
What new cost or complexity did AI introduce?
Did the quality of the decision improve?
Was time saved?
Were errors reduced?
Did the customer receive enough incremental value to justify changing the existing workflow?

This is a mindset I would like to adopt consciously.

For example, if AI is introduced into one of the enterprise processes I work with, I would not consider the implementation successful simply because a model or Copilot capability was integrated successfully. I would want to know whether it shortened a task, improved quality, reduced manual intervention, increased consistency, or enabled something that was previously difficult to achieve.

AI should have to earn its place in the product.

A Metric Can Improve One Outcome and Damage Another

One of the more thought-provoking discussions for me was around KPIs and incentives. The session pointed out that people naturally adapt their behavior to how they are measured, and that management decisions can therefore produce unintended side effects.

I could relate to this immediately.

In software environments, we frequently use metrics such as delivery timelines, defect counts, productivity measures, incident volumes or SLA adherence. These metrics are useful, but this session reminded me that optimizing one dimension can unintentionally damage another.

For example, if a team is measured predominantly on completing work quickly, it may discourage sufficient exploration or long-term architectural thinking. If success is measured only by the number of issues closed, the team may optimize closure rather than solving underlying problems. Similarly, if an AI product is measured only by automation rate, the organization could inadvertently encourage automation of decisions that would be safer or more effective with human intervention.

This led me to an important personal realization:

Whenever I define a KPI, I should also ask what undesirable behavior that KPI could accidentally encourage.

That is a question I have not always asked explicitly.

I now see metrics less as passive measurements and more as mechanisms that influence behavior.

How Much Authority Should We Give AI?

The discussion that I found most relevant to AI product management was around the progression from a Copilot-style system to increasingly autonomous agents.

The session distinguished between AI that provides a suggestion, AI that drafts an action, AI that executes after human approval, and AI that can execute independently within defined policies or limits. It also raised practical considerations such as API usage, token budgets, spending limits and boundaries on what the AI should be allowed to do.

This helped me recognize that the key AI product question is not simply:

“Can AI perform this task?”

A much more important question is:

“How much authority should AI be given to perform this task?”

For me, the answer should depend primarily on the consequence of being wrong and the reversibility of the action.

If AI generates a draft that a person reviews before sending, an incorrect output may be easily recoverable. If AI independently performs an irreversible financial, customer or production action, the same level of model performance may no longer be acceptable.

This is particularly meaningful in my software-development context. An AI system recommending a code change is fundamentally different from an agent autonomously deploying that code into production. Both may involve similar underlying intelligence, but the product risks are completely different.

Human Oversight Is Part of the Product Design

This also changed how I think about human involvement in AI systems.

Previously, I could have interpreted human review mainly as an additional safeguard added when confidence in AI was insufficient. After this session, I see human oversight as a deliberate product-design decision.

When designing an AI-enabled workflow, I would now explicitly decide whether the AI should:

Suggest an action;
Prepare or draft the action;
Execute only after approval;
Execute independently within predefined limits; or
Execute autonomously and surface only exceptions.

The appropriate level should depend on business risk, confidence, consequences and whether an incorrect action can be reversed.

This feels far more practical to me than treating AI autonomy simply as a measure of technological maturity.

How I Would Apply This Learning

I see several direct applications to my work.

First, when introducing a new technology or AI capability, I would explicitly establish a pre-implementation baseline. If the objective is faster processing, better quality or reduced manual effort, I should measure the existing process before introducing AI.

Second, I would classify significant product decisions according to their reversibility. Where possible, I would prefer pilots, controlled rollouts, configuration switches or clear rollback mechanisms before making an irreversible commitment.

Third, when defining KPIs for a product or team, I would examine both the intended outcome and the behavior the metric might unintentionally encourage.

Finally, for AI-enabled functionality, I would explicitly document decision and action boundaries. I would want the team to know not only what the AI can technically do, but what it is authorized to do without human intervention.

Where I Would Apply It with Caution

One point I would qualify is the preference for reversible decisions.

Not every important decision can remain reversible forever. Maintaining alternatives has a cost. Supporting multiple technologies, keeping parallel processes operational or postponing a commitment can increase complexity and prevent the organization from realizing the full benefit of a chosen direction.

Therefore, I would use reversibility mainly when uncertainty is high and the cost of preserving the option is reasonable. Once sufficient evidence exists, commitment may become the better decision.

I would apply the same caution to human oversight. More human involvement does not automatically make an AI system safer. Excessive approvals can introduce delays, review fatigue and a tendency to approve recommendations without meaningful consideration. The objective should therefore not be to maximize human intervention, but to place human judgment where it genuinely reduces meaningful risk.

My Key Takeaway

My strongest takeaway from this session is that AI product management is fundamentally about designing decision boundaries, not simply designing intelligent features.

The product manager has to determine what the AI may recommend, what it may decide, what it may act upon, when a human must intervene, and what happens when either the human or the AI gets the decision wrong.

The session also made me much more conscious that AI value needs to be demonstrated against a meaningful baseline and that KPIs themselves can change human behavior.

The question I would carry forward from this session is:

“If this decision turns out to be wrong, how easily can I detect it, reverse it, and limit the impact?”

For me, this is an especially important question for AI products because greater technical capability should not automatically translate into greater autonomy. The level of autonomy should be earned through evidence, bounded by risk, and supported by a clear recovery path.

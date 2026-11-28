**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 1 Topic:** AI Product Foundations and Why AI Became Commercially Viable

# Management of AI Products: Class Reflection

## 1. Class Overview

The first session set up the vocabulary for the rest of the course. Most of the time went on one question: what makes a product AI-powered, and what is just ordinary software with an AI label on it. The second half looked at why this became practical in the last few years and not ten years ago.

## 2. Key Concepts and Discussions

- **Traditional software vs AI products:** traditional software follows rules someone wrote down, so the same input gives the same output. An AI product learns a pattern from data, so its output is a best guess that can shift as the data changes.
- **Rule-based vs learning systems:** rules are easy to explain and check, but they fail on cases nobody thought of. Learning systems cope with messy cases, but they can be wrong with full confidence and are harder to explain.
- **The removal test:** take the AI out and see if the product still does its job. If it works about the same, it was never really an AI product.
- **Types of AI products:** prediction (demand forecasting), recommendation (the Netflix kind), generation (chatbots and copilots), and hybrids of these. The useful way to sort them is by the job the user wants done, not by the technique underneath.
- **Why now:** a lot more digital data, cheaper cloud computing, better models, and access through APIs, so a small team can use AI without training a model itself.

## 3. Important Insights

- **Most real products are a mix:** a food delivery app predicts arrival times, ranks restaurants, and also runs plain fixed rules for things like payments. Calling the whole product one type is too tidy.
- **Uncertainty becomes the PM's problem:** an AI output is probabilistic, so you cannot promise a fixed result. You have to decide how often it can be wrong, what the user sees when it is, and who pays for the mistake. This is the biggest break from managing normal software.
- **India changes the design:** languages, price sensitivity and how much people trust an app matter as much as the model does.

## 4. Practical Learnings

I can use the removal test straight away on apps I already use. Google Maps would fall apart without its prediction, while a "smart" feature that only sorts a list by date is just normal software. When someone pitches an AI feature, I will ask three things: what is it predicting or generating, what data does it learn from, and what happens when it gets it wrong.

## 5. Conclusion

I came in thinking of AI as one thing that a product either has or doesn't. After this class it seems more useful to ask what role it plays and how much error the product can tolerate. I'm still unsure where the line sits for something like a lightly personalised "recommended for you" row.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 2 Topic:** The AI Product Manager and the AI Product Stack

# Management of AI Products: Class Reflection

## 1. Class Overview

This class was about what an AI product manager is actually responsible for. The short answer was the outcome and the quality of decisions, not the model code itself.

## 2. Key Concepts and Discussions

- **The stack:** data, model, API or application layer, and the user experience on top. A user judges the product by whichever layer is weakest, even if they can't name it.
- **The PM as translator:** the PM talks to data scientists, engineers, designers and legal, and has to ask each of them a different question.
- **Trade-offs:** quality, speed, cost and scope pull against each other. It helps to write down which one wins when they clash.

## 3. Important Insights

- **Netflix and Google Maps:** what you see is small, a row of titles or an arrival time, sitting on top of a lot of prediction and ranking you never see.
- **Late decisions turn political:** decisions pushed to launch week tend to be settled by opinion and not by evidence.

## 4. Practical Learnings

I broke down a few apps on my phone into the four layers. For a music app, listening history is the data, a ranking model sits on top, the app logic follows, and the home screen is the UX. It made it easier to guess where a bad recommendation probably starts. Next time an app feels off, I'll check the layers one at a time instead of just saying the AI is bad.

## 5. Conclusion

It was a relief that the PM doesn't have to be the strongest technical person in the room. What I'm unsure about is how deep to go when the model is a black box supplied by a vendor.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 3 Topic:** AI Product Strategy and Opportunity Identification I

# Management of AI Products: Class Reflection

## 1. Class Overview

We moved from what AI is to where it is worth using. The main point was that an opportunity is a workflow that gets clearly better, not a model that looks impressive.

## 2. Key Concepts and Discussions

- **Value and feasibility:** an idea can be valuable but hard to build, or easy to build but worth little. You pick the one with the best risk-adjusted payoff.
- **Build, buy or API:** build what gives you an edge, and borrow commodity capability when speed matters more.
- **Feature or platform:** start as a feature, and only think about becoming a platform once demand keeps repeating.
- **Jobs-to-be-done:** start from the progress the user is trying to make, not from the technology.

## 3. Important Insights

- **Ticket routing beats a novelty chatbot:** it is frequent, painful and easy to measure, so you can tell whether it worked.
- **The HDFC exercise:** we compared support, fraud, sales and knowledge retrieval, and it became obvious that you fund one and say no to the others.

## 4. Practical Learnings

Suppose a college club has three AI ideas: an FAQ bot, an automatic poster maker and an attendance tracker. Scoring each on how often the problem comes up, how much it hurts and how easy it is to measure would show the first pilot. I suspect all three would end up as API or buy decisions, not build.

## 5. Conclusion

Saying no turned out to be part of strategy. That was harder to accept than I expected.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 4 Topic:** AI Product Strategy and Opportunity Identification II

# Management of AI Products: Class Reflection

## 1. Class Overview

This session dealt with what comes after the first trial: product-market fit, platforms, how recommendations work, and what makes an AI product hard to copy.

## 2. Key Concepts and Discussions

- **AI product-market fit:** an important job, repeated success, trust, repeat use, and economics that hold up. A viral launch proves nothing on its own.
- **ChatGPT as a platform:** it can be reused for almost anything, but governance gets harder and reliability in a specific workflow can be weaker.
- **Recommendation logic:** retrieve candidates, set the objective, filter and rank, then test. What you choose to optimize matters a lot.
- **Defensibility:** workflow fit, data, distribution, trust, integration and how fast you learn. Having access to a good model is not enough.

## 3. Important Insights

- **Optimizing for clicks can hurt trust:** engagement can grow while satisfaction falls, and the dashboard will only show the first.
- **Same model, different outcome:** given two products on the same model, the one with better workflow fit and feedback loops wins.

## 4. Practical Learnings

When I look at a new app, the first-week download count now seems like the wrong thing to be impressed by. I would want week-eight usage and how often people have to correct its output.

## 5. Conclusion

Novelty gets people to try something and only repeated value keeps them. I'll remember that the next time a launch looks great after two weeks.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 5 Topic:** Designing AI Products for Uncertainty

# Management of AI Products: Class Reflection

## 1. Class Overview

Normal UX assumes the system is right. This class looked at designing for a system that might be wrong, and still helping people act on it.

## 2. Key Concepts and Discussions

- **Interaction modes:** visible assistant, inline suggestion, background automation and invisible optimizer. Each has different risks.
- **Handling uncertainty:** show enough confidence, offer a fallback, let users correct the output, and send risky cases to a human.
- **Human-in-the-loop vs on-the-loop:** the choice depends on how serious and how reversible the consequences are.
- **Prompt design is product design:** instructions, context, examples, boundaries and a fallback all shape what the user experiences.

## 3. Important Insights

- **Perplexity's sources:** showing where an answer came from builds trust in a way that fluent writing does not.
- **Explain in proportion to the stakes:** too much explanation adds friction and too little kills confidence.

## 4. Practical Learnings

Take an email assistant that drafts replies. For a casual note to a friend, an inline suggestion is fine. For a message with legal or financial weight, a person should read it before it goes out. It is the same tool but a different loop, because the stakes are different.

## 5. Conclusion

This was the session where design felt most concrete to me. I had never thought of a confirmation screen as a safety feature before.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 6 Topic:** Data Fundamentals for Product Managers

# Management of AI Products: Class Reflection

## 1. Class Overview

The message was that saying "we have data" means very little. What matters is whether the right signal exists, arrives on time, is fair, and can actually be used.

## 2. Key Concepts and Discussions

- **The data supply chain:** collect, ingest, transform, label, serve, observe, and feed back.
- **Sources:** behavioral logs, transaction data and explicit feedback each have their own gaps.
- **Labels are product decisions:** a proxy label is cheaper, but it can end up optimizing the wrong goal.
- **Translation:** business objective, decision, prediction target, features, threshold, then evaluation.
- **Risks:** missing data, biased samples, leakage and consent.

## 3. Important Insights

- **BigBasket forecasting:** the goal is having stock on the shelf, not a good offline accuracy score. A failure in one region can come from stale data or poor coverage.
- **Accurate on the wrong target:** a model can score well and still help nobody.

## 4. Practical Learnings

I tried the translation chain on a simple problem: a canteen that wastes food. Objective: less waste. Decision: how many meals to prepare each morning. Prediction target: meals needed tomorrow. Features: weekday, weather, exam dates. Evaluation: waste and sell-outs together, not forecast error alone.

## 5. Conclusion

Labels as a product decision was new to me. I now want to check what an "engagement score" is really standing in for whenever I see one.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 7 Topic:** The AI Product Lifecycle

# Management of AI Products: Class Reflection

## 1. Class Overview

Shipping is not the finish line. It is the point where you become accountable for how the product runs. We followed the loop from discovery through validation, launch, monitoring and change.

## 2. Key Concepts and Discussions

- **Three gates:** discovery asks if this is the right problem, validation asks if it is good enough for this use, and launch asks if the workflow, monitoring, fallback and owners are ready.
- **Limits of offline validation:** it cannot prove that users or the business are better off.
- **Thresholds:** where you set the threshold decides who carries the cost of errors.
- **Fallback, override, rollback:** each one needs a clear trigger and an owner.
- **Drift:** the world changes after launch, so monitoring has to cover users, the model, the system and risk.

## 3. Important Insights

- **Agree escalation triggers before launch:** once something breaks, it is too late to argue about what counts as a failure.
- **A dashboard needs an action:** every signal should come with a threshold, an owner and a next step.

## 4. Practical Learnings

A simple post-launch checklist could work for any small project, including our capstone: who watches which number, what value means we pause, and what the fallback is.

## 5. Conclusion

This changed how I think about "done". For an AI product, launch is closer to the halfway point.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 8 Topic:** Revision and Integration of Sessions 1 to 7

# Management of AI Products: Class Reflection

## 1. Class Overview

The last session before the mid-sem pulled everything together. The goal was not to recall frameworks but to make a PM recommendation under time pressure.

## 2. Key Concepts and Discussions

- **The course in order:** classify the AI, find the opportunity, decide on stack and sourcing, design for trust, check the data, then run and monitor.
- **Answering a case:** define the problem, take a position early, use one framework, give an example, name the downside, and say what evidence would change the decision.
- **Make a decision:** a weak answer describes AI, a strong one recommends build, pilot, delay, redesign or API.

## 3. Important Insights

- **One framework done well:** listing every framework is worse than using one properly.
- **The same order works for any case:** from Swiggy to HDFC, the sequence holds.

## 4. Practical Learnings

I tried the sequence on a practice case: should a university add an AI assistant for admissions queries? Following the order gave me a one-page answer, pilot it, keep a human fallback, and track unresolved queries, faster than I expected.

## 5. Conclusion

Revision showed me that the sessions build on each other. Strategy without data or lifecycle thinking falls apart, and putting them together is the real skill.

---

**Name:** Rugved Khanwalkar

**BITS ID:** 2025MB26040

# Management of AI Products

**Session 9 Topic:** AI Product Development Cycle: Prototypes and MVPs

# Management of AI Products: Class Reflection

## 1. Class Overview

This session was about how an AI product actually gets built, and how much you should build before you learn something. The main distinction was between a prototype, which tests an idea, and an MVP, which tests whether real users get real value.

## 2. Key Concepts and Discussions

- **Stages of development:** problem framing, data and feasibility checks, prototype, MVP, launch and then iteration. The stages overlap, and you often go back a step.
- **Types of prototypes:** paper sketches and wireframes for the experience, clickable mockups for the flow, and a quick notebook or demo for checking that the model can do the task at all.
- **Prototype vs MVP:** a prototype answers whether something could work. An MVP is released to real users to see if it does work, so it needs a real workflow around it.
- **Types of MVP:** a Wizard of Oz MVP, where a person quietly does the AI's job behind the screen, a concierge MVP, a single-feature MVP, and staged automation, where the human share shrinks as confidence grows.

## 3. Important Insights

- **The AI illusion is a legitimate method:** faking the model with a person is a cheap way to learn whether anyone wants the output, before paying for data and training.
- **Smallest does not mean sloppy:** an AI MVP still needs a fallback and a way to catch bad outputs, since users judge it on its worst answers.
- **What you want to learn decides the type:** testing demand and testing model quality are different questions and need different MVPs.

## 4. Practical Learnings

For a study-notes summarizer idea, I would not start by training anything. I would take notes from a few classmates, summarize them by hand, and see whether they actually use the summaries and what they correct. If they do, then it is worth checking whether a model can match that quality.

## 5. Conclusion

I had assumed an MVP meant a smaller version of the final product. It is closer to the cheapest way of finding out whether the product is worth building. I'm still a bit unsure how to decide when a manual MVP has taught enough to move to automation.

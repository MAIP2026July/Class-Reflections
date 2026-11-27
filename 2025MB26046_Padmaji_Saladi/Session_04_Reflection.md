# Session 4 Reflection

| | |
|---|---|
| Date | 22 August 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | When is AI appropriate? Legitimacy, value, adoption and the AI opportunity thesis |

## 1. Key concepts
This class was about when AI should be used at all. The first gate is social legitimacy, before any technical check. Should this product exist? Does it add real value? Who gets hurt if the answer is wrong? Some questions a system simply shouldn't answer.

His example was a nuclear-powered pencil sharpener. You could build one, but should you? Cost, safety and common sense all say no.

He suggested using the simplest tool that works: rules first, then search and analytics, then machine learning, then generative AI, and agents only when a controlled sequence of steps really improves the result. AI can suggest, draft, act with approval, or act within limits. Anything with money or social impact at stake needs an approval step. He also warned about tail risk, using Bhopal as the example of a very rare event with a huge impact.

The idea I liked most was the actionable window. Telling someone it will rain one minute before it rains is useless. A city worker needed to know that morning to carry an umbrella, and a farmer needed two days' notice to arrange a harvest.

On adoption, he said people aren't always early adopters or laggards. It depends on the product. Switching cost and disruption to the current workflow are why people resist change. He also mentioned dark patterns, like hiding the unsubscribe button, which some countries have banned.

He warned against automating everything. Sometimes the time we "save" is time people enjoy, like chatting with someone about a recipe. Tata Nano didn't fail on engineering; it failed on positioning. Incentives matter for AI agents too: if an agent is told to maximise profit, it might start rejecting every insurance claim. He asked us to always keep before-AI and after-AI baselines, and to back the AI opportunity with evidence. Silent drops in model quality are more dangerous than obvious failures.

## 2. What changed in my thinking
The actionable window made me rethink my own project. A delay prediction only helps if the receiving lead sees it early enough to move people. If it's accurate but too late, it's useless.

## 3. How I will apply it
In VendorPulse, the ML model makes the predictions and the LLM only explains them and reads vendor messages, which follows the "simplest tool" idea. The copilot drafts schedule changes, but the receiving lead approves them. I'll measure accuracy and also how early a risk shows up before the truck arrives. The agreed delivery window will be my before-AI baseline.

## 4. Open questions
- How do we catch a silent quality drop in a hosted model before users lose trust?
- How do we measure switching cost for a team that currently runs on spreadsheets and phone calls?

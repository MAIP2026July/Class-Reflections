# Class 5 Reflections

## 1. Zero-shot vs. Few-shot Prompting

-   **Zero-shot:** Provide only the problem statement.
-   **Few-shot:** Provide the problem statement along with examples.
-   Providing examples can help the model produce better results.

## 2. Uncertainty in AI Outputs

AI outputs can be probabilistic. The user experience (UX) must handle
uncertainty appropriately.

### Confidence tiers

  Confidence level   Suggested handling
  ------------------ -----------------------------------
  High               Automate
  Medium             Provide clarity or request review
  Low                Human intervention or fallback

**Key point:** Confidence is not the same as truth.

## 3. AI Product Management: What to Consider

Think about the combination of:

**Model output + Uncertainty + UX + Human oversight**

### Designing uncertainty into the UX

1.  Show confidence.
2.  Provide alternatives.
3.  Ask clarifying questions.
4.  Escalate to a human.
5.  Allow correction.

## 4. Human in the Loop (HITL)

A human participates in the AI decision-making process when human
judgement is valuable or when risk requires oversight.

**Core idea:** AI + Human

### Three common HITL patterns

1.  **Human approval**
    -   AI makes a recommendation.
    -   A human approves it.
2.  **Human review**
    -   Used for uncertain cases.
    -   High-confidence cases: AI handles them automatically.
    -   Low-confidence cases: a human reviews them.
    -   This is called **confidence-based escalation**.
3.  **Human correction**
    -   A human corrects the AI.
    -   The correction may later become feedback or training data.

## 5. Basic Prompt Structure

**Role + Task + Context + Constraints + Output Format**

## 6. Prompt Engineering Basics

1.  Clear instruction.
2.  Context.
3.  Constraints.
4.  Output format.
5.  Examples.

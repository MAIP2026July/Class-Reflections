# Class Reflection (Lecture 3): Frameworks, Limits, and Fast-Changing Products in AI Management

## 1. Practical Application & Execution

I work as an AI product manager in an environment where model outputs, data, and technical abilities keep changing. In this kind of work, product management frameworks cannot stay as textbook ideas. They need to be used in daily work. When used well, they bring order to a situation that could otherwise become chaotic. They also help the PM connect uncertain research with disciplined execution.

### Using the Decision Traceability Matrix as a "Custodial Decision Gate"

In this lecture, the Traceability Matrix was presented not as extra paperwork but as a **Custodial Decision Gate**. A product manager is not a king who decides everything alone. A PM is a custodian of money, time, trust, and people, entrusted by board members, executive sponsors, and engineering teams. Every decision to prioritize, deprioritize, or ignore a feature must be written down and justified.

When I write an AI Product Requirement Document (PRD) and set release gates, I can use this idea by keeping a living matrix that tracks three things:

- **Data Source and Evidence:** Record the evidence that justifies each feature, such as domain research, stakeholder interviews, or regulatory requirements. Describe user personas precisely (their role, working conditions, and accessibility needs) instead of using vague user labels.
- **Model Evaluation and Defects:** Record test feedback, baseline evaluation metrics, and failures. This shows what went wrong so we do not repeat the same mistakes during model fine-tuning or prompt changes.
- **Feature Trade-offs and Quality Function Deployment (QFD):** Link what customers want (the "whats") to the technical solutions (the "hows"). For example, we must balance model accuracy against speed and token cost. Must-have requirements get done before nice-to-have improvements.

The matrix should also record our strategic stance on outside changes, including why we chose to react to a competitor's move or chose *not* to react. Adding this matrix to the PRD release gates creates a clear audit trail. It protects product decisions when stakeholders push back, removes confusion between teams, and keeps the PM from becoming the main source of confusion.

### Treating Scrum Sprints as "Bounded Risk Contracts"

Using agile methods in AI engineering means changing how we think about software development. The instructor described a Scrum Sprint as a **stability contract** between the product manager and the engineering team. In fast-moving AI work, market changes and unexpected model behavior tempt a PM to change direction mid-sprint. But constant pivots hurt team morale, kill momentum, and reduce trust.

To apply this, I will plan AI development in fixed-length sprints that act as bounded risk contracts:

- **Fixed Two-Week Sprints:** A fixed two-week sprint gives the engineering team a period of full stability. Requirements and research direction stay locked. This limits the financial and operational risk of R&D experiments and shields engineers from daily outside pressure.
- **Sprint Length Based on the Type of Work:** Stable core platform work can use longer sprints (three to four weeks). Fast-changing AI work, where model APIs change quickly or performance moves unpredictably, needs shorter sprints so we can recheck our assumptions often without breaking the stability contract.
- **Sprint Cancellation Option:** If a key technical assumption fails mid-sprint because of a model failure or a major shift, I keep the authority to formally end the sprint. This resets the agreement cleanly. The PM takes responsibility for the change, and the engineering team is released from wasted effort without blame.

These frameworks bring order to our internal development cycles, but their success depends on outside organizational, technical, and business limits.

---

## 2. Limits and Boundaries ("Where it Fails")

Using product management frameworks without checking their limits leads to failure. From what I have seen in enterprise workflows and technology lifecycles, textbook frameworks often assume predictable inputs, stable markets, and straight-line execution. When these tools are forced onto unpredictable AI work, without thinking about technical limits, project size, or market speed, they stop helping and become obstacles.

### Where the Amazon PR/FAQ Framework Breaks Down in AI Projects

A clear example is the **Amazon PR/FAQ (Press Release / Frequently Asked Questions) Framework**. It was taught in class as a way of "working backwards" from the customer outcome. Before engineering begins, the team writes a press release announcing a finished, successful product.

In our class discussion, Amazon practitioner Shruti Chaturvedi explained that Amazon mainly uses the PR/FAQ for long-running, multi-billion-dollar programs with a stable end goal, such as Subscribe & Save. For short, fast-changing projects, the upfront PR/FAQ is skipped or heavily adjusted, because the assumptions in the document change too quickly.

In fast-paced AI product development, a fixed PR/FAQ breaks down for four reasons:

- **Probabilistic Outputs vs. a Fixed Vision:** The PR/FAQ assumes we can clearly picture and guarantee the final product ability in advance. But AI abilities are based on probability. If the press release promises highly accurate automated reasoning, but testing shows accuracy stops improving or the model hallucinates in edge cases, the document becomes misleading.
- **Fast Model and Infrastructure Changes:** Foundation models, open-source architectures, and hardware (for example, a move from general GPUs to specialized inference LPUs) change weekly. A fixed vision written months earlier stops a company from swapping models or components when something better appears.
- **User Fatigue and Changing Interfaces:** In fast AI development, the way users interact with the product keeps changing as workflows mature. Locking early interaction designs into a press release causes problems when live user testing demands quick changes. Users get tired when what was promised no longer matches the real product.
- **Slower Projects and Lost Stakeholder Trust:** When short AI projects must follow a fixed PR/FAQ, teams waste development time trying to make uncertain research results match an outdated vision. When the final product differs from the press release, executives lose trust in product forecasts, and the project slows down because the documents keep falling out of sync.

Seeing where upfront frameworks fail pushes us to question some basic assumptions of traditional product management.

---

## 3. Alternative / Contrarian Perspective

During technology disruption and fast market change, an AI product manager must question established PM rules. Traditional product management principles often give strict, general rules designed for mature software markets. But following standard theory too rigidly during early AI shifts can threaten a product's market chances, data strategy, and long-term finances.

### The Strategic Enterprise Anchor Model: Rethinking Products vs. Projects

A core idea in traditional product management, also discussed in this lecture, is a strict separation between "Products" (built for many unknown users on a shared system) and "Projects" (custom work for a single client). The usual advice is to protect the core codebase, avoid heavy customization, and walk away from single-client work to avoid falling into consulting traps.

I challenge this strict split with **The Strategic Enterprise Anchor Model**. In early-stage enterprise AI, money is tight, inference costs are high, and timing is aggressive. Under these conditions, deliberately building a heavily customized solution for one client first is often the most workable way to build a strong platform.

Instead of avoiding single-client customization, an early-stage AI product manager should use an enterprise anchor client for three reasons:

- **Access to Valuable Domain Data:** AI models need real-world context, edge cases, and expert knowledge to create real value. Working closely with one anchor enterprise gives the team rare access to private workflows and real operational data. This cannot be recreated in isolation or built from public benchmarks.
- **Real-World Testing of Unpredictable Workflows:** Probability-based model behavior cannot be fully tested in an isolated sandbox. A custom integration for one client acts as a live testing ground. The team can try human-in-the-loop checks, error handling, and token costs inside real business operations.
- **Funding R&D Through Layered Architecture:** Heavily customized enterprise projects bring in money that does not dilute ownership, and this money can fund risky core R&D. The PM can manage the customization cleanly with a three-layer software design:
  1. **Base layer:** The Protected Core AI Platform, a reusable multi-tenant engine that holds the core IP.
  2. **Middle layer:** The Industry / Domain Framework, which standardizes common workflows for a sector.
  3. **Top layer:** Client-Specific Customization, fully paid for by the anchor client.

With this separation, the single client's funding supports the basic infrastructure while the core IP stays protected. Once the anchor client's workflow is stable and proven, the PM can turn it into a general domain framework, spread the R&D costs across later enterprise clients, and grow the custom engine into a multi-tenant platform. Walking away too early from deep single-client work means missing important chances to gather data, test in real operations, and get funded platform development.

This leads to my final conclusion about how an AI product manager must handle a constantly moving target.

---

## 4. Personal Takeaway & Synthesis

Studying operational frameworks, their limits, and contrarian market strategies has changed how I see the leadership of AI projects.

Managing an AI product is like steering a guided missile toward a fast-moving target. Customer expectations, foundation model abilities, and aggressive competitors are all changing at the same time. In this environment, I must give up rigid, fixed roadmaps and focus on continuous risk management. I should treat frameworks as real-time navigation dials, not fixed autopilot routines. In the end, my main role as an AI product manager is to make these course corrections well, balancing stability for the engineering team against the strategic need to out-innovate the market.

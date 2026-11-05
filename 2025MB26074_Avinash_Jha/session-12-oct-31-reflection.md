# Class Reflection: Session 12 — October 31, 2026
**Course**: Management of AI Products (MBA ZG583)  
**Instructor**: Prof. Vinaya Sathyanarayana  
**Topic**: AI Product Monetization, Unit Economics, Target Costing & Platform Economics  

---

## 1. Core Theme & Executive Synthesis

The final core lecture session addressed **AI Product Monetization, Business Models, and Unit Economics**. The instructor emphasized that a technologically superior model means nothing if the underlying business model cannot deliver sustainable gross margins. AI product managers must master **Target Costing** (working backward from customer willingness-to-pay), align output-based value pricing with input-based token costs, and leverage platform economics to build defensible competitive moats.

---

## 2. Key Concepts & Frameworks Dissected

* **Target Costing (Japanese Backward Approach)**:
  * *Traditional Forward Approach*: $\text{Cost of Build} + \text{Desired Margin} = \text{Price}$ (risks pricing the product out of the market).
  * *Target Costing (Backward Approach)*: $\text{Customer Willingness-to-Pay (Value)} - \text{Target Profit Margin} = \text{Maximum Allowable Cost to Serve}$.
  * PMs must engineer the AI stack ($SLMs, \text{caching}, \text{RAG}$) to meet the allowable cost-to-serve ceiling.
* **Value-Based vs. Input-Based Pricing Misalignment**:
  * *Customers* desire **Output/Value-Based Pricing** ($e.g.,$ per resolved ticket, per loan processed, per report generated).
  * *Vendors* incur **Input-Based Costs** ($e.g.,$ per token, per API call, per GPU hour).
  * *PM Responsibility*: Bridge this structural gap by designing tiered subscriptions, usage-based thresholds, or outcome-aligned pricing models that protect gross margins against heavy power users.
* **Platform & Ecosystem Economics (Metcalfe’s Law)**:
  * Metcalfe’s Law ($Value \propto n^2$): Standalone AI features easily get commoditized or swallowed by platform giants.
  * Long-term defensibility requires building an ecosystem—embedding AI into user workflows, establishing network effects, and creating high switching costs.
* **Capstone PRD & VC Pitch Preparation**:
  * Structuring the final Capstone PRD as a Markdown repository contract and preparing a concise, high-impact 10-minute presentation pitch focused on unit economics, market differentiation, and risk management.

---

## 3. Personal Reflection & Practical Application

The distinction between **Input-Based Costs and Output-Based Pricing** represents the single biggest financial risk in AI product management. If an AI product promises flat-rate output pricing while bearing unbounded input token costs, power users will quickly drive gross margins negative.

Applying **Target Costing** forces us as PMs to design architectural constraints early—caching frequent queries, enforcing context window limits, and utilizing SLMs—so that our cost-to-serve remains well below the customer's perceived value threshold.

---

## 4. Critical Evaluation & Friction Points

* **The Heavy-User Trap**: Flat-rate SaaS pricing models fail in generative AI. Uncapped usage by heavy users creates negative-margin customer cohorts, making sensitivity analysis and tier-based caps essential.
* **Markdown Standard for AI Evaluation**: Technical PRDs should be authored in native Markdown (`.md`) rather than static PDFs to allow seamless ingestion, automated specification checks, and unambiguous version control across git repositories.

---

## 5. Action Items for Capstone PRD & Pitch

1. **Finalize PRD Markdown Submission**: Ensure all Capstone PRD sections (Product Strategy, Architecture, Unit Economics, Risk Assessment) are committed as clean Markdown (`.md`) files in the team GitHub repository.
2. **Refine VC Pitch Deck**: Structure the 10-minute presentation around the target market opportunity, unit economics, platform defensibility, and risk mitigation safeguards.

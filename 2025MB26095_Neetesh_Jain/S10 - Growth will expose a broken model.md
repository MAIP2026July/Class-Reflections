# Session 10: Growth will expose a broken model

17 October 2026 | Neetesh Jain | 2025MB26095

---

If the economic model is not thought through, growth will expose it fully. That is the sentence I needed in session 7 and did not have a method for.

A demo that spends twenty to forty dollars in API calls looks wonderful, and then every trial by a customer repeats that bill. Teams pull to extremes. Latency is high, so someone switches to a small model. Quality drops, so someone switches to a frontier model. Nobody named the sweet spot, so the product oscillates at the edges and the margin disappears. That briefing is the product manager's job. Min and max for quality, latency, and cost. Outside the window, come and talk. Inside it, decide.

I have a cost per review in the model. I do not have a window. I have a point estimate, which is the same habit as my padded single number estimates from session 3. A point is something people can violate without noticing. A range is a rule.

**Predictability over speed.** The faculty added extra seconds to processing so the next unit of work would arrive on a known beat, rather than a garbage collector hitting in the middle and making the wait random. Customers preferred that to a faster but jumpy system. I would have optimised for speed. I have spent ten years treating latency as a defect. For a weekly review that runs once, a briefing that always takes four minutes is better than one that takes forty seconds most weeks and four minutes when the portfolio is messy, because the messy week is the week they cannot wait. I will price and design for a predictable duration, not a minimum one.

**Same track, different queues.** Generative products survive by routing, caching, and tiering, not by always using the best model. Like trains on one track: some complete in two hours, some in six. At low volume none of this matters. At success you hit rate limits, then you build queues, then you invent a fast lane for VIP customers, and the plumbing becomes the product. We have one RDM in the MVP, so none of this is visible. I still need a sentence in the economics note for what happens at forty managers sharing one org: who waits, who does not, and whether a noisy neighbour in another region can starve ours. Session 5's lock in worry was about the vendor. This is lock in to our own success.

**What I will add.** A sweet spot table. Quality not below X. Duration between A and B. Cost per review between C and D. And a line that says if growth makes C greater than the value per review, we stop scaling and redesign, rather than celebrating usage.

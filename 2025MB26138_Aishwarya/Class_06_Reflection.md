**Class 6 Reflection**

5 September 2026 - Reimagining workflows, translating problems to AI, sentiment analysis

The PRD-in-the-stakeholder's-own-words point is one I should have been doing already - "I as a ride giver want..." instead of generic system-speak - since half the requirement docs I write get re-translated by someone else before an engineer reads them anyway.

Treating the business process as a black box and asking which inputs can now be dropped or added is a cleaner way to scope an AI feature than where I usually start, which is closer to "what can the model do." The warning that bad modelling just gets optimised beautifully in the wrong direction is worth keeping in view.

The sentiment-analysis walkthrough (object, feature, sentiment, holder, time) made the point that plain positive/negative scoring misses the actual signal - the mother upset she wasn't told before a purchase isn't something a sentiment score alone would ever surface, and that's the part a PM actually needs.
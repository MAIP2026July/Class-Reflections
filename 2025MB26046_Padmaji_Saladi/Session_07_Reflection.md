# Session 7 Reflection

| | |
|---|---|
| Date | 12 September 2026 |
| Name | V V S S N Padmaji Saladi |
| BITS ID | 2025MB26046 |
| Course | MBA ZG583 – Management of AI Products |
| Topic | Reimagining a DISCOM's customer support, value-based pricing, the FIR framework, product lifecycle |

## 1. Key concepts
The professor started with exam advice. Answer in the context of the case and avoid general statements that could apply to anything. He marks how well we connect our reasoning, so two different answers can both score well. He also said PMs should spend some time doing customer support after launch, because poor support damages so many companies.

Most of the class was a discussion on customer support for an electricity distribution company (a DISCOM, like BESCOM). We started with ideas like a voice bot for outage calls. By the end, the better idea was to use monitoring data to know about an outage before anyone calls, tell customers through an app, and send the nearest field engineer to the right transformer.

Pricing came up a lot. Nobody pays extra for a DISCOM's call-centre tool, so the price has to come from the value it gives the DISCOM, and we take a share of that value. Charging less than the value means leaving money on the table. Willingness to pay depends on the people running the company and what they care about. Charging per call-centre seat can backfire: fewer outages mean fewer calls, and the DISCOM cuts seats.

He shared his own framework, FIR: Facts, Inferences and Recommendations.
- **Facts** come from databases and tools, so hallucination there can be almost zero.
- **Inferences** come from patterns in data, like many complaints from one area.
- **Recommendations** carry the most uncertainty.

He said hallucination isn't yes or no but comes in shades. If the system is completely unsure, it shouldn't show the answer.

Other points I noted:
- **Land and expand.** The same DISCOM might also want power-purchase forecasting.
- **Life after launch.** We need records of data consent, use and deletion, and customers may ask for software escrow.
- **AI dependencies change.** A provider can slow down, change, or release something that makes your product unnecessary.
- **Data quality.** Record the exact transformer, not "near the bank".

He also asked us not to use AI for our reflections. I've noted how these were prepared in my AI-Use-Disclosure file.

## 2. What changed in my thinking
FIR gave me words for something I had felt but couldn't explain. A fact from the database and a recommendation from a model shouldn't look the same on the screen.

## 3. How I will apply it
In VendorPulse I'll keep the three layers separate and visible:
- **Facts:** a vendor's past deliveries, and whether there's an ASN today (there isn't for NEX vendors).
- **Inferences:** the predicted arrival window and the risk of a late arrival or reschedule.
- **Recommendations:** for example, "move one associate to the dock at 2 pm". The receiving lead always has to confirm these.

On pricing, I'll compare my per-store price with the value it creates, not just with my costs.

## 4. Open questions
- How do we show uncertainty on a small handheld screen without confusing people?
- When should the product refuse to answer instead of showing a weak inference?

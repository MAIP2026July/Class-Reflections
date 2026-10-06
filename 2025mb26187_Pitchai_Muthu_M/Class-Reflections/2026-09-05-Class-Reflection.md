#Class Reflection — 5 September 2026

One important thought for me from this class was that a confident system and a correct system are not always the same thing.

As engineers, we normally try to remove errors. With AI products, uncertainty cannot always be removed completely, so the product also has to decide what to do when it is unsure.

I can connect this with tools used in embedded-software workflows. Suppose an automated tool detects a board configuration, selects an image and proceeds with flashing. If it has incomplete information but still behaves as though it is 100% certain, a user may flash the wrong image or lose trust in the tool. A better product would recognize uncertainty, show what it knows, and ask the user to confirm when necessary.

This changed my view of UX. Earlier I normally thought of UX mainly as screens, menus and ease of use. For an AI product, UX also includes how confidence, errors and limitations are communicated.

There is also a balance here. If we ask a human to approve every action, then we may lose the benefit of automation. If we automate everything, risk increases. The right design may be high-confidence automation with human review only for uncertain or high-impact cases.

My takeaway is that fallback behaviour should be designed from the beginning, not added after failures happen.
# Class 10 Reflection

**Date:** 17 October 2026  
**Topic:** Scaling AI products across quality, latency, cost and reliability

The part I found most useful was the shift from monitoring infrastructure to monitoring the promise made to the customer. Servers can look healthy while the customer still waits too long or receives an unusable answer. The real question is whether the product delivered what it promised, when the user needed it.

AI makes this harder because quality, speed and cost pull in different directions. A stronger model may improve difficult answers but respond more slowly and cost more. A smaller model may be fast and affordable but fail on complex cases. Saying “make it faster” or “use the best model” is therefore not a complete product requirement.

The versioning discussion also stood out. When behaviour changes, the team should know which model, prompt, source set and policy produced the output. Without that record, it becomes difficult to understand why an answer changed or whether a fix actually worked.

For Wayfinder AI, the promise should be simple: provide a timely answer supported by approved content, or clearly abstain and escalate. Scaling is successful only if that promise survives when the number of sites, documents and questions grows.

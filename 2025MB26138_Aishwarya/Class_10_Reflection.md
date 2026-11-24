**Class 10 Reflection**

17 October 2026 - Scaling AI products

"User expectations harden faster than infrastructure can catch up" is the line I kept turning over, because it's exactly the trap on a mission-critical system - once a feature is relied on daily, the SLA people expect stops being written anywhere, it's just assumed.

Teams talk about servers when they should talk about promises - if the commitment is "a cab in three minutes," that's the thing to monitor, not CPU. I think our own support metrics have the same gap: we track ticket volume and response time, not whether the thing the client actually needed working was working.

The quality/latency/cost trade-off as a range to hand the team, rather than a single "make it faster" instruction, is a small but useful change to how I'd brief an engineering ask going forward.
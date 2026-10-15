---
id: PR-002
title: Partial Victory and the 2:1 threshold
status: confirmed
printing: third-2026
rules: ["§10.2 table p.29", "Player Aid B (official flow chart, 2026), Partial Victory node and footnote 5"]
tags: [peace-resolution, partial-victory, land-units]
source: "Paradox Player Aid B v1.3 (2026): 'Either player has twice as many Land Units Deployed as their Enemy'"
contributors: []
---

# Partial Victory and the 2:1 threshold

## Setup
Player A and Player B are both human PRs, at war. Neither has been eliminated. Counting **Deployed Land Units** at Peace Resolution:

| | A's units | B's units | Result |
|---|---|---|---|
| Scenario 1 | 9 | 4 | Partial Victory for A |
| Scenario 2 | 5 | 4 | No Partial Victory |
| Scenario 3 | 8 | 4 | **Partial Victory for A** (exactly 2:1 is enough) |

## The question
At what point does a player reach Partial Victory against a human Enemy?

## Resolution
- The rulebook table (p.29) says a human Enemy is beaten when your Deployed Land Units "**outnumber** the Deployed Land Units of their Enemy 2:1".
- The official flow chart words it differently: "**Either player has twice as many Land Units Deployed as their Enemy**." Twice as many means exactly double is enough.
- **Scenario 1 (9 vs 4):** more than double. **Partial Victory.**
- **Scenario 2 (5 vs 4):** nowhere near double. **No Partial Victory.** If nobody occupies any Provinces it is an Automatic White Peace; otherwise Inconclusive.
- **Scenario 3 (8 vs 4):** exactly double. **Partial Victory.** This was the one case where the rulebook's "outnumber 2:1" was ambiguous; the chart's "twice as many" settles it.
- The chart says **"either player"**: whichever side has the 2× advantage is the Victor.
- Land Units on **Distant Continents where the enemy PR has no Town** do not count (chart footnote 5).
- Against an **NPR or Bot**, it is different: your Deployed Land Units must outnumber the enemy's Deployed Land Units **and** the total number of a particular icon in the NPR's Areas (the rulebook table, p.29; see [Q5](../../docs/open-questions.md)).

## Status notes
Upgraded from "disputed" to confirmed using the publisher's own flow chart. An earlier version of this case listed Scenario 3 as unresolved.

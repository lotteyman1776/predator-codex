# vRogue v3.1 (Video Roulette / RNG)

## Mission
vRogue is built to survive randomness, not “predict” it.
The goal is disciplined, repeatable play that:
1) keeps spins flowing with controlled exposure,
2) builds rolling memory,
3) applies pressure only when criteria are met,
4) protects profit automatically.

---

## Core Rules (Always On)
- **Cold Mode is mandatory** until engagement criteria are met.
- **Never overcommit** to a narrow cluster (fixes the [17,29] trap).
- **Profit-only scaling**: reserve funds are never used for aggressive sizing.
- **Exposure cap**: total units at risk per spin must have a hard ceiling.
- **50% drawdown = Recovery Mode** (slow down, don’t panic-bet).

---

## Inputs
Track these every spin:
- Spin result (number)
- Session bankroll (current)
- Buy-in reference ($100 default)
- Unit size (table minimum)

---

## Dual Memory Engine (Concept)
### Short Memory (Reactive)
- Last **12–18** spins
- Used to detect fast repeat density and short streak behavior

### Long Memory (Stabilizing)
- Last **60–120** spins
- Used to prevent tunnel vision and confirm real density vs noise

Track both:
- number repeats
- zone/sector repeats (defined by layout rules)
- streak behavior: color / parity / high-low (secondary signal only)

---

## Cold Mode (Keep-Spinning Mode)
**When no cluster is confirmed:**
- Place the minimum allowed bet to keep the machine spinning.
- Prefer a simple even-money bet:
  - Red/Black, Even/Odd, or High/Low

**Cold Mode Goals**
- Build memory without bleeding
- Avoid emotional betting
- Maintain discipline

---

## Engagement Criteria (When You’re Allowed to Attack)
A cluster may be engaged only when it meets BOTH:

### A) Short Memory trigger
- At least **2 hits inside the candidate set** within the last **12 spins**

### B) Long Memory confirmation
- At least **3 hits inside the candidate set** within the last **30 spins**

If criteria are not met → remain in Cold Mode.

---

## Cluster Definition Rules (Anti-Overcommit)
The system must never lock onto a cluster that is too narrow.

### Minimum cluster width
- A valid cluster must be at least **5–8 numbers wide**
  (exact width depends on your unit limits and table minimums)

### Why this exists
Overcommitting to a 2-number “micro cluster” can cause long stagnation losses
even when the player is “technically correct” about prior hits.

---

## Stagnation Timer (Escape Rule)
Once a cluster is engaged, start a stagnation timer.

If the cluster produces **no hit within 10 spins**, do the following in order:
1) **De-escalate** (reduce total units)
2) **Widen** the set OR return to Cold Mode
3) **Never chase by narrowing further**

This is the primary correction for the sniper stagnation flaw.

---

## Sizing Doctrine (Simple)
- Base unit = table minimum
- Start conservative
- Scale only with **session profit**
- Never risk reserve funds for “kill shots”

### Hard Exposure Cap (Required)
Set a max total units exposed per spin.
Example:
- Cold Mode: 1 unit total
- Engagement: 2–6 units total (depending on bankroll)
- Never exceed your cap even if you “feel it coming”

---

## Profit Lock (Mandatory)
When profit reaches defined thresholds, remove a portion from risk.

Example structure (adjust later):
- +10 units profit → lock 25%
- +20 units profit → lock 50%
- +30 units profit → lock 70%
Locked profit cannot be re-risked in the same session.

---

## 50% Drawdown Recovery Mode
If bankroll drops to **50% of buy-in reference**:
- Return to Cold Mode only
- Reduce exposure to minimum
- Require stronger engagement criteria before attacking again
- Goal becomes survival and stabilization, not “winning it back fast”

---

## End Condition
Session ends when one occurs:
- Profit target hit and locked
- War chest depleted (after rebuys per protocol)
- Execution integrity breaks (confusion, fatigue, misreads)

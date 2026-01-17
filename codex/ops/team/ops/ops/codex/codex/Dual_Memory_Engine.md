# Dual Memory Engine (DME)

Dual Memory Engine prevents Predator from being fooled by short-term noise.
It uses two time horizons at once:

- **Short Memory** = fast reaction
- **Long Memory** = stability and anti-tunnel-vision

DME is mandatory for vRogue and recommended for LiveEdge.

---

## Memory Windows (Defaults)
### Short Memory (SM)
- last **12–18 spins**
Purpose:
- detect fresh repeat density
- detect short streak behavior
- trigger engagement opportunities

### Long Memory (LM)
- last **60–120 spins**
Purpose:
- confirm real density vs random coincidence
- prevent overcommit to narrow micro clusters
- detect persistent zones/sets

---

## What DME Tracks
DME tracks outcomes in 3 layers:

### Layer 1: Number Repeats
- exact number repeats inside SM and LM

### Layer 2: Zone / Set Density
Numbers grouped into a defined set (example: 8-number cluster set).
Track how many hits occur inside the set.

### Layer 3: Trend Signals (Secondary)
Even-money behavior only:
- Red/Black
- Even/Odd
- High/Low

Trends never override bankroll protection rules.

---

## Engagement Logic (DME Gate)
A candidate set can be engaged only when:

### Short Memory Trigger
- at least **2 hits** in the set within the last **12 spins**

### Long Memory Confirmation
- at least **3 hits** in the set within the last **30 spins**

If not met → remain in Cold Mode.

---

## Anti-Overcommit Rule (DME Safety)
DME forbids engagement if:
- the set is too narrow (less than 5 numbers)
- the set is “micro-sniped” down to 2 numbers
- long memory does not support the density

This is the primary defense against stagnation traps.

---

## Stagnation Recognition
Stagnation is defined as:
- engaged set produces **no hit for 10 spins**

When stagnation occurs:
1) reduce exposure
2) widen set OR return to Cold Mode
3) never narrow further

If stagnation repeats twice in one session:
- force switch to Recovery Mode or Profit Protection

---

## Practical Use (No Math Overload)
DME is not complicated in live play.

You only need to answer:
1) “Did this set hit at least twice recently?”
2) “Did it also hit multiple times across the last 30 spins?”
3) “Is the set wide enough to avoid tunnel vision?”
4) “Are we within exposure limits and bankroll rules?”

If yes → engage.
If no → Cold Mode.

---

## DME Success Criteria
A DME-successful session is one where:
- engagement was criteria-based
- overcommit never happened
- stagnation was handled correctly
- bankroll rules were respected

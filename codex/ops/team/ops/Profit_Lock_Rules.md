# Profit Lock Rules (Predator)

Profit Lock exists to prevent the most common roulette failure:
**winning early, then bleeding it back through overconfidence or chasing.**

Locked profit is removed from risk for the remainder of the session.

---

## Definitions
- **Buy-In Reference:** $100 (default session starting point)
- **Current Bankroll:** what you have right now
- **Session Profit:** Current Bankroll - Buy-In Reference
- **Locked Profit:** portion of profit that cannot be re-risked

---

## Profit Lock Thresholds (Default)
These can be adjusted later, but the system requires a simple structure.

### Tier 1 Lock
When Session Profit reaches **+10 units**
- Lock **25%** of profit

### Tier 2 Lock
When Session Profit reaches **+20 units**
- Lock **50%** of profit

### Tier 3 Lock
When Session Profit reaches **+30 units**
- Lock **70%** of profit

### Tier 4 Lock (Hard Secure)
When Session Profit reaches **+40 units**
- Lock **85%** of profit
- Session may optionally end here if conditions are unstable

---

## Lock Enforcement Rules
- Locked profit cannot be used to size up bets.
- Only **unlocked profit** may be used for scaling.
- Reserve funds are never used for scaling.

---

## Scaling Permission (Profit-Only)
Scaling is allowed only if BOTH are true:
- You are above Buy-In Reference
- You are not violating exposure caps

If profit drops back below a lock threshold:
- Do NOT “unlock” previously locked profit.
- Scaling reduces automatically.

---

## Behavioral Triggers (Automatic Lock / Stop)
If any of these occur, lock immediately and/or end session:
- urge to chase
- confusion in communication
- fatigue spike
- repeated stagnation timer failures
- “I feel like it’s due” thinking

---

## Practical Execution (Simple)
In real play, Profit Lock is executed by:
- physically separating chips/cash (live)
- mentally subtracting locked amount from usable bankroll (video)

Locked = protected. Protected = untouchable.

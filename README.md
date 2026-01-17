# Predator Codex

**Single source of truth** for the Predator roulette system.

This repository exists to keep the Predator protocols structured, recoverable, and executable in real casino conditions.

---

## Non-Negotiable Rules
- **Two systems, kept separate:**
  - **vRogue** = Video Roulette / RNG
  - **LiveEdge** = Live Dealer / Physical wheel
  No cross-contamination of logic unless explicitly validated.
- **Evidence-based changes only.** No “feels like it works.” If it’s not proven true/false, it’s not doctrine.
- **Execution > theory.** Everything must be simple enough to run under pressure without confusion.
- **Documentation must be complete enough to rebuild the system from scratch.**

---

## Repo Structure
- `codex/` — full strategy definitions and doctrine
- `ops/` — execution checklists, stop-loss & recovery, profit lock rules
- `team/` — roles, responsibilities, and communication protocol
- `logs/` — (optional) session logs and test results
- `diagrams/` — (optional) visuals / flowcharts

---

## Quick Start
If you’re starting a session:
1. Identify mode: **vRogue** or **LiveEdge**
2. Use the **Session Checklist**
3. Run **Cold Mode** until engagement criteria are met
4. Enforce:
   - exposure caps
   - overcommit prevention
   - 50% drawdown recovery
   - profit lock

---

## Glossary (short)
- **Cold Mode**: minimum-risk spins to build memory when no edge criteria exist
- **Cluster**: repeat density inside a defined number set / zone
- **Stagnation Timer**: rule that forces de-escalation when a target set stops producing
- **Profit Lock**: rules that remove winnings from risk during the session

---

## Status
This codex is active and evolving under controlled testing.

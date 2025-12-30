# P016: Conservative-then-Upgrade Architecture

**Domain:** System design  
**Leverage:** L4  
**Validated:** 1 project (TDR-100)

## Description
Start with conservative approach sufficient for current needs, but explicitly design upgrade path. Let real-world data drive progression.

## Evidence
| Project | Conservative | Upgrade Path | Trigger |
|---------|--------------|--------------|---------|
| TDR-100 | 120V DC Phase 1 | 400V DC Phase 2 | If 100m altitude needed |

## Template
```
Phase N (Conservative):
  - Solution: [conservative choice]
  - Rationale: [why sufficient]
  - Data to collect: [metrics for upgrade decision]

Phase N+1 (Upgrade - if needed):
  - Solution: [upgraded choice]
  - Trigger: [specific criteria]
```

## Anti-Pattern
Optimizing prematurely; selecting "best" solution before validating need

# P013: Research Subagent Validates Design Decisions

**Domain:** Agent system  
**Leverage:** L6  
**Validated:** 2 projects (BB-01, TDR-100)

## Description
Spawn @researcher before committing to novel technical approaches. External validation reduces risk and reveals implementation details.

## Evidence
| Project | Research Query | Key Finding |
|---------|----------------|-------------|
| BB-01 LOMAH | ADXL345 impact detection | Built-in tap detection validated |
| TDR-100 Drone | Tethered drone voltage | Industry uses 400-800V; 120V valid |

## Spawn Triggers
- constraint_type == "structural"
- Novel sensor or component
- Unfamiliar domain
- High-stakes decision

## Anti-Pattern
Committing to design based only on internal knowledge

# P015: Quadratic Leverage in Physical Systems

**Domain:** Electrical, Thermal, Mechanical  
**Leverage:** L10  
**Validated:** 1 project (TDR-100)

## Description
Look for variables with quadratic (or higher order) relationships to constraint. Small changes yield disproportionately large improvements.

## Evidence
| System | Relationship | Result |
|--------|--------------|--------|
| TDR-100 I2R | P_loss = I²R | 2.5x voltage increase = 6.25x loss reduction |

## Common Quadratic Relationships
- I²R heating in conductors
- Kinetic energy (½mv²)
- Aerodynamic drag (∝ v²)
- Centrifugal force (∝ ω²r)

## Mechanism
1. Identify constraint equation
2. Find variables with exponents > 1
3. Focus design on high-leverage variables
4. Small improvements yield quadratic returns

## Anti-Pattern
Treating all variables as linear; missing quadratic leverage

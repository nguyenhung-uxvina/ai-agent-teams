# P011: Variable Decoupling as Constraint Bypass

**Domain:** Sensing systems, Power systems  
**Leverage:** L7  
**Validated:** 2 projects (BB-01, TDR-100)

## Description
When signal and noise share same medium, find alternate path that physically separates them.

## Evidence
| Project | Observation | Outcome |
|---------|-------------|---------|
| BB-01 LOMAH | Contact sensing through steel | Bypasses airborne noise |
| TDR-100 Drone | Voltage decouples power from I²R | 6.25x loss reduction |

## Mechanism
1. Identify medium where signal and noise propagate together
2. Find alternate medium that carries signal but not noise
3. Redesign to use alternate medium
4. Noise becomes irrelevant rather than filtered

## Anti-Pattern
Trying to filter noise from signal in shared medium (diminishing returns)

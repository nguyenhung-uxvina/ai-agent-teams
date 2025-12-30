# P014: Built-in Features Beat Custom Implementation

**Domain:** Embedded systems  
**Leverage:** L10  
**Validated:** 2 projects (BB-01, TDR-100)

## Description
Before implementing custom logic, check if component has built-in features for use case. Manufacturer features are more robust and tested.

## Evidence
| Project | Component | Built-in Feature Used |
|---------|-----------|----------------------|
| BB-01 LOMAH | ADXL345 | Tap detection registers with thresholds |
| TDR-100 Drone | Vicor DCM3623 | OCP, OTP, soft-start protections |

## Checklist
- [ ] Read FULL datasheet, not just quick start
- [ ] Check application notes
- [ ] Search manufacturer forums
- [ ] Look for eval board example code

## Anti-Pattern
Reimplementing in firmware what silicon already does

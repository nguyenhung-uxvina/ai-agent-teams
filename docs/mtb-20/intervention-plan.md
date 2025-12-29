# MTB-20 Naval Target Production Scaling
## Intervention Plan

**Generated**: 2025-12-29  
**Framework**: D-M-I-R Analysis with MCP Integration  
**Status**: Ready for Implementation

---

## Executive Summary

| Aspect | Decision |
|--------|----------|
| **Binding Constraint** | Knowledge - Tacit autoclave process held by Technician B |
| **Recommended Solution** | Knowledge-First Digital Capture |
| **Weighted Score** | 4.55 / 5.00 |
| **Implementation Timeline** | 4 phases, 21 months |
| **Immediate Action** | Video record ONE complete autoclave cycle THIS WEEK |

---

## System Overview

```
┌─────────────────────────────────────────────────────────────────────┐
│                    MTB-20 PRODUCTION SYSTEM                         │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│  CURRENT STATE                        TARGET STATE                  │
│  ─────────────                        ────────────                  │
│  ┌──────────────┐                    ┌──────────────┐              │
│  │ 2 units/mo   │   ════════════►    │ 20 units/mo  │              │
│  └──────────────┘                    └──────────────┘              │
│                                                                     │
│  BOTTLENECK IDENTIFIED:                                            │
│  ┌────────────────────────────────────────────┐                    │
│  │         TECHNICIAN B (SPOF)                │                    │
│  │                                            │                    │
│  │  ┌─────────────────────────────────────┐  │                    │
│  │  │     TACIT KNOWLEDGE                 │  │                    │
│  │  │     ─────────────────               │  │                    │
│  │  │  • Autoclave temperature profiles   │  │                    │
│  │  │  • Layup sequences                  │  │                    │
│  │  │  • Pressure curves                  │  │                    │
│  │  │  • Defect detection                 │  │                    │
│  │  │                                     │  │                    │
│  │  │  STATUS: UNDOCUMENTED ⚠️            │  │                    │
│  │  └─────────────────────────────────────┘  │                    │
│  │                                            │                    │
│  │  IF UNAVAILABLE: 100% PRODUCTION STOP     │                    │
│  └────────────────────────────────────────────┘                    │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Binding Constraint Analysis

### Evidence from Airtable Data

| Source | Finding | Impact |
|--------|---------|--------|
| Team Table | Technician B: "CRITICAL - Only person who can run autoclave cycle" | Single Point of Failure |
| Team Table | Availability: "Partial" | Cannot scale with one person |
| Requirements | "Composite hull fabrication process documentation" - Status: Active | Knowledge gap confirmed |
| Project | Gap: 2 → 20 units/month (18 unit shortfall) | 10x scaling required |

### System Archetypes Detected

**Primary: Limits to Growth**
```
     More Orders
          │
          ▼
    ┌─────────────┐        ┌─────────────┐
    │ Production  │───────►│ Demand on   │
    │ Pressure    │        │ Tech B      │
    └─────────────┘        └──────┬──────┘
                                  │
                                  ▼
                          ┌─────────────┐
                          │ Tech B      │
                          │ Capacity    │◄── LIMIT
                          │ Reached     │
                          └─────────────┘
```

**Secondary: Shifting Burden**
```
    Symptomatic Solution          Fundamental Solution
    ────────────────────          ────────────────────
    "Push Tech B harder"    vs    "Document knowledge,
    (overtime, stress)             train backups"
           │                              │
           ▼                              ▼
    Short-term relief              Long-term capability
    but burnout risk               but upfront investment
```

---

## Concept Evaluation Matrix

### Concepts Evaluated

| ID | Concept | Description |
|----|---------|-------------|
| A | **Knowledge-First Digital Capture** | AI-assisted capture of Technician B's expertise using video, sensors, interviews |
| B | Defense Foundry Partnership | Partner with external composite fabricator for surge capacity |
| C | Design-for-Manufacturing Redesign | Redesign hull for simplified process (no specialized skill needed) |

### Weighted Evaluation

| Criterion | Weight | A (Knowledge) | B (Partnership) | C (Redesign) |
|-----------|--------|---------------|-----------------|--------------|
| Addresses Root Cause | 0.35 | 5 | 2 | 5 |
| Time to Impact | 0.25 | 4 | 3 | 1 |
| Investment Required | 0.20 | 4 | 2 | 1 |
| Risk Reduction | 0.20 | 5 | 4 | 5 |

### Weighted Scores

| Concept | Score | Recommendation |
|---------|-------|----------------|
| **A: Knowledge-First** | **4.55** | ✓ SELECTED |
| C: Redesign | 3.20 | Future MTB-30 consideration |
| B: Partnership | 2.60 | Evaluate after 6 months |

**Rationale**: Concept A scores highest because:
1. DIRECTLY addresses the binding constraint (tacit knowledge)
2. Fastest time to impact (3 months to documented process)
3. Is a PREREQUISITE for any other scaling approach
4. Research validates AI-driven knowledge capture works in A&D manufacturing (iBase-t)

---

## Implementation Roadmap

### Phase Overview

```
Month  1   2   3   4   5   6   7   8   9  ...  21
       ├───┼───────────┼───────────────┼────────┤
       │ 0 │  PHASE 1  │   PHASE 2     │PHASE 3 │
       │   │ Capture   │   Training    │ Scale  │
       │   │           │               │        │
       │   │           │               │        │
       ▼   ▼           ▼               ▼        ▼
      Vid  Full AI    Backup       20 units/
      Rec  Docs       Fab          month
```

### Phase 0: Micro-Win (This Week)

| Issue | Task | Timeline | Owner | Success Metric |
|-------|------|----------|-------|----------------|
| [#2](https://github.com/nguyenhung-uxvina/ai-agent-teams/issues/2) | Video record ONE complete autoclave cycle | This week | Production Manager | Raw video captured and stored |

**Why Critical**: Provides immediate baseline if Technician B becomes unavailable. Zero capital investment, immediate risk reduction.

**Leverage Point**: L06-Information (make tacit knowledge visible)

### Phase 1: Quick-Win (3 Months)

| Issue | Task | Timeline | Owner | Investment |
|-------|------|----------|-------|------------|
| [#3](https://github.com/nguyenhung-uxvina/ai-agent-teams/issues/3) | Implement AI-assisted knowledge capture system | 3 months | Engineering Lead | $50K-100K |

**Components**:
- Video documentation of autoclave process (all variations)
- Sensor data logging during production cycles
- Structured knowledge interviews with Technician B
- AI-assisted process documentation generation
- Training material development

**Deliverable**: Complete process documentation validated by Technician B

**Leverage Points**: L06-Information + L07-Reinforcing Loops

### Phase 2: Lock-In (6 Months)

| Issue | Task | Timeline | Owner | Success Metric |
|-------|------|----------|-------|----------------|
| [#4](https://github.com/nguyenhung-uxvina/ai-agent-teams/issues/4) | Train backup fabricator using documented process | Month 4-9 | Production Manager | Second qualified operator |

**Deliverable**: Second person capable of producing quality hulls independently

**Leverage Point**: L10-Structure (add redundancy, eliminate SPOF)

### Phase 3: Goal (12+ Months)

| Issue | Task | Timeline | Owner | Investment |
|-------|------|----------|-------|------------|
| [#5](https://github.com/nguyenhung-uxvina/ai-agent-teams/issues/5) | Enable second production line for 20 units/month | Month 10-21 | Program Manager | $200K-500K |

**Deliverable**: Sustained 20 units/month for 3 consecutive months

**Leverage Point**: L11-Buffers (build physical capacity)

---

## Leverage Points Applied

| Level | Name | Intervention | Phase | Impact |
|-------|------|--------------|-------|--------|
| L06 | Information | Make tacit knowledge visible through documentation | 0, 1 | High |
| L07 | Reinforcing Loops | Knowledge → training → more trainers loop | 1, 2 | High |
| L10 | Structure | Add redundancy - backup fabricator eliminates SPOF | 2 | Critical |
| L11 | Buffers | Build physical capacity buffer for 20 units/month | 3 | Medium |

---

## Risk Register

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| Technician B unavailable before capture | Medium | **Critical** | Phase 0 micro-win provides immediate baseline |
| Knowledge capture incomplete | Low | High | Multiple capture methods (video + sensor + interview) |
| Trained backup fails qualification | Low | Medium | Use validated documentation, supervised practice |
| Capital investment delayed | Medium | Medium | Phase 0-2 proceed without major capital |
| Defect rate increases at scale | Medium | High | Design-for-manufacturing review (Concept C later) |

---

## Research Sources

Industry research validated knowledge capture approach:

| Source | Key Finding | Application |
|--------|-------------|-------------|
| [McKinsey](https://www.mckinsey.com/industries/aerospace-and-defense/our-insights) | "Utilization-based approach for step-change output" | Data-driven capacity analysis |
| [iBase-t](https://www.ibaset.com/how-ai-is-solving-knowledge-transfer-challenges) | "AI-driven automation fills gap left by retiring employees" | Core of Concept A approach |
| [Karve International](https://www.karveinternational.com/insights/the-defense-foundry-model) | Defense Foundry Model for partnership scaling | Concept B backup option |
| [NAMF](https://www.namf.com/military-fabrication/) | "Components must be producible at scale" | Future MTB-30 consideration |

---

## Success Criteria

### Phase Gates

| Phase | Gate Criteria | Status |
|-------|---------------|--------|
| Phase 0 | Raw video of complete autoclave cycle stored | Pending |
| Phase 1 | Documentation validated by Technician B | Pending |
| Phase 2 | Second operator produces quality hull independently | Pending |
| Phase 3 | 20 units/month for 3 consecutive months | Pending |

### Final Acceptance

- [ ] Production rate: 20 units/month sustained
- [ ] Workforce: ≥2 qualified fabricators
- [ ] Documentation: Complete and validated
- [ ] Quality: Defect rate ≤ prototype baseline
- [ ] Timeline: Navy contract deadline met

---

## Airtable Records

| Record Type | ID | Purpose |
|-------------|-----|---------|
| Project | recuf98yXNEoRB4rt | MTB-20 master record |
| Lesson 1 | rec0N03r1u3psrpx0 | MCP Integration Enables Data-Driven DMIR |
| Lesson 2 | rec7PkWlbhx4mzAwq | Knowledge Constraints Precede Physical |
| Lesson 3 | recjfsugiRSAbVPMe | Micro-Wins Reduce Catastrophic Risk |

---

## Immediate Actions

1. **THIS WEEK**: Video record complete autoclave cycle ([Issue #2](https://github.com/nguyenhung-uxvina/ai-agent-teams/issues/2))
2. **Month 1**: Evaluate AI knowledge capture tools ([Issue #3](https://github.com/nguyenhung-uxvina/ai-agent-teams/issues/3))
3. **Month 1**: Begin structured interviews with Technician B

---

## Hybrid Strategy Note

After Phase 1 completion (~3 months), evaluate:
- **If timeline is tight**: Activate Concept B (Defense Foundry Partnership) for surge capacity
- **For MTB-30**: Apply Concept C (Design-for-Manufacturing Redesign) lessons learned

---

*Generated by D-M-I-R Agent Chain with MCP Integration*  
*🤖 [Claude Code](https://claude.com/claude-code)*

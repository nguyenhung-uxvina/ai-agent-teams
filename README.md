# AI Agent Teams

D-M-I-R Analysis Framework with MCP Integration

## Projects

### TDR-100 Tethered Drone Reconnaissance
- **Status**: Active
- **Binding Constraint**: Thermal (I²R heating in tether/ground station)
- **Recommended Solution**: Medium-Voltage Balanced (120V DC)
- **VDI 2225 Score**: 3.10 / 4.00
- **Timeline**: 3 phases, 12 weeks
- **Documentation**: [Intervention Plan](docs/tethered-drone/intervention-plan.md)
- **Issues**: [#6](../../issues/6) [#7](../../issues/7) [#8](../../issues/8) [#9](../../issues/9) [#10](../../issues/10) [#11](../../issues/11) [#12](../../issues/12) [#13](../../issues/13)

### MTB-20 Naval Target Production
- **Status**: Active  
- **Binding Constraint**: Knowledge (Technician B single point of failure)
- **Recommended Solution**: Knowledge-First Digital Capture
- **Weighted Score**: 4.55 / 5.00
- **Timeline**: 4 phases, 21 months
- **Documentation**: [Intervention Plan](docs/mtb-20/intervention-plan.md)
- **Issues**: [#2](../../issues/2) [#3](../../issues/3) [#4](../../issues/4) [#5](../../issues/5)

## Framework

```
@diagnostician → @modeler → @interventionist → @reflector
      │              ↑
      │         [@researcher]
      ▼              │
  [Airtable]    [Brave Search]
                     │
                     ▼
                  [GitHub]
```

### Agent Roles

| Agent | Role | MCP Integration |
|-------|------|-----------------|
| @diagnostician | Stock-flow analysis, constraint identification | Airtable (read) |
| @researcher | Industry benchmarks, similar solutions | Brave Search |
| @modeler | Concept design, VDI 2225 evaluation | - |
| @interventionist | Leverage points, implementation roadmap | GitHub (write) |
| @reflector | Lessons learned, pattern capture | Airtable (write) |

## MCP Integrations

| Server | Purpose | Operations |
|--------|---------|------------|
| **Airtable** | Project data, requirements, test results | list_records, create_record, update_records |
| **GitHub** | Issue tracking, documentation | create_issue, create_or_update_file |
| **Brave Search** | Industry research, benchmarks | brave_web_search |

## Documentation

- [TDR-100 Intervention Plan](docs/tethered-drone/intervention-plan.md) - Tethered drone 120V architecture
- [MTB-20 Intervention Plan](docs/mtb-20/intervention-plan.md) - Naval target knowledge capture

---
🤖 Generated with [Claude Code](https://claude.com/claude-code)

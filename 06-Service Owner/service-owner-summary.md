# Service Owner Analysis summary
´´´ 
IT Capacity Requirements - Service Owner Model

System          Current IT │ Service Owner Addition │ New Total
────────────────────────────────────────────────────────────────
Ascendo         ▓           │ ████████████████████   │ 3.0 hrs
                0.16 hrs    │ +2.8 hrs               │

Flexite         ████        │ ████████████           │ 4.9 hrs
                2.5 hrs     │ +2.4 hrs               │

Idus            ████        │ ████████████████       │ 5.5 hrs
                2.5 hrs     │ +3.0 hrs               │

Agda/Visma      ▓           │ ████████               │ 2.16 hrs
                0.16 hrs    │ +2.0 hrs               │
────────────────────────────────────────────────────────────────
TOTAL           5.32 hrs    │ +10.2 hrs              │ 15.56 hrs/month
                (64 hrs/yr) │ (+122 hrs/yr)          │ (187 hrs/yr)

Current IT: 4% FTE  →  Service Owner IT: 12% FTE  →  Additional: 8% FTE
´´´´

## Summary Overview

| System | Current Business Owner Time | Current IT Time | Total System Management | User Count |
|--------|---------------------------|-----------------|------------------------|------------|
| **Ascendo** | 3.2 hrs/week (12.8 hrs/month) | 0.16 hrs/month | 12.96 hrs/month | 93 |
| **Flexite** | 1.05 hrs/week (4.2 hrs/month) | 2.5 hrs/month | 6.7 hrs/month | Not specified |
| **Idus** | 1.4 hrs/week (5.6 hrs/month) | 2.5 hrs/month | 8.1 hrs/month | 30 |
| **Agda/Visma** | 1.14 hrs/week (4.56 hrs/month) | 0.16 hrs/month | 4.64 hrs/month | 400-450 |
| **TOTAL** | **6.79 hrs/week (27.16 hrs/month)** | **5.32 hrs/month** | **32.48 hrs/month** | ~573-593 |

### Business vs Technical Time Split

| System | Business Time | Technical Time | Business % | Technical % |
|--------|--------------|----------------|------------|-------------|
| **Ascendo** | 10.0 hrs | 2.8 hrs | 78% | 22% |
| **Flexite** | 1.8 hrs | 2.4 hrs | 43% | 57% |
| **Idus** | 2.56 hrs | 3.0 hrs | 46% | 54% |
| **Agda/Visma** | 2.56 hrs | 2.0 hrs | 56% | 44% |

## Portfolio-Wide Recommendations Summary

### Tasks to Transfer to IT

| System | Task | Hours/Month | Rationale |
|--------|------|-------------|-----------|
| **ASCENDO** | **TOTAL: 2.8 hrs/month** | | |
| | User account management | 1.2 hrs | Pure technical task - creating/removing accounts, permission changes |
| | Technical support | 0.8 hrs | Login issues, error messages - requires IT troubleshooting |
| | Technical troubleshooting | 0.4 hrs | System errors - technical diagnosis needed |
| | Technical vendor coordination | 0.4 hrs | IT already handles rare technical incidents |
| | | | |
| **FLEXITE** | **TOTAL: 2.4 hrs/month** | | |
| | User account creation/removal | 1.2 hrs | Pure technical task - system execution |
| | Password resets | 0.6 hrs | Technical task - authentication management |
| | Permission changes | 0.2 hrs | Technical execution (business approves) |
| | Technical change requests | 0.4 hrs | Requires technical knowledge, vendor coordination |
| | | | |
| **IDUS** | **TOTAL: 3.0 hrs/month** | | |
| | User account creation/removal | 2.0 hrs | Pure technical task - system execution |
| | Technical support | 1.0 hrs | Login issues, error messages, system errors |
| | Password management | 0 hrs* | **CRITICAL: Implement individual passwords (currently shared!)** |
| | | | |
| **AGDA/VISMA** | **TOTAL: 2.0 hrs/month** | | |
| | User account creation/removal | 1.2 hrs | Pure technical task - system execution |
| | Password resets | 0.4 hrs | Technical task (self-service portal already exists) |
| | Technical support | 0.4 hrs | Login issues, error messages - IT troubleshooting |
| | Technical vendor coordination | 0.08 hrs | ~1 hr/year for system errors |

*Idus password management shows 0 hrs currently because all users share one password - this MUST be fixed immediately as a security violation.

---

### Tasks to Keep with Business

| System | Task | Hours/Month | Rationale |
|--------|------|-------------|-----------|
| **ASCENDO** | **TOTAL: 10.0 hrs/month** | | |
| | Reports & data exports | 4.0 hrs | Requires financial/accounting context and business analysis |
| | User training | 2.0 hrs | Process knowledge essential - invoice approval workflows |
| | Business support | 0.4 hrs | "How do I..." questions requiring process knowledge |
| | Business vendor coordination | 3.6 hrs | Business context needed for feature requests, process questions |
| | | | |
| **FLEXITE** | **TOTAL: 1.8 hrs/month** | | |
| | Reports & data exports | 1.0 hrs | Safety incident analysis - requires safety expertise |
| | Business support | 0.8 hrs | "How do I report incident" - process questions |
| | Permission approval decisions | 0 hrs* | Safety compliance requirements - business must approve access levels |
| | | | |
| **IDUS** | **TOTAL: 2.56 hrs/month** | | |
| | Business support | 1.36 hrs | Maintenance workflow and process questions |
| | Business configuration | 0.4 hrs | Maintenance approval workflows - requires domain expertise |
| | Reports & exports | 0.28 hrs | Maintenance data analysis |
| | User training | 0.52 hrs | Maintenance process knowledge |
| | | | |
| **AGDA/VISMA** | **TOTAL: 2.56 hrs/month** | | |
| | User training | 2.0 hrs | HR/payroll process knowledge essential, labor law compliance |
| | Business support | 0.4 hrs | Payroll, time reporting questions |
| | Business configuration | 0.4 hrs | Workflows, approval rules - HR compliance requirements |
| | Business vendor coordination | 0.08 hrs | Feature requests |

*Flexite permission approvals tracked as 0 hrs but critical business input - Safety team must approve who gets access based on safety/compliance needs.

### Total Transfer Opportunity to IT

| System | Current Business Time | Transfer to IT | Remain with Business | Reduction % |
|--------|---------------------|----------------|---------------------|-------------|
| **Ascendo** | 12.8 hrs/month | 2.8 hrs | 10.0 hrs | 22% |
| **Idus** | 5.56 hrs/month | 3.0 hrs | 2.56 hrs | 54% |
| **Flexite** | 4.2 hrs/month | 2.4 hrs | 1.8 hrs | 57% |
| **Agda/Visma** | 4.56 hrs/month | 2.0 hrs | 2.56 hrs | 44% |
| **TOTAL** | **27.12 hrs/month** | **10.2 hrs/month** | **16.92 hrs/month** | **38%** |

### IT Capacity Requirements

| System | Current IT | Service Owner Addition | New IT Total |
|--------|-----------|----------------------|--------------|
| **Ascendo** | 0.16 hrs/month | +2.8 hrs | 3.0 hrs/month |
| **Flexite** | 2.5 hrs/month | +2.4 hrs | 4.9 hrs/month |
| **Idus** | 2.5 hrs/month | +3.0 hrs | 5.5 hrs/month |
| **Agda/Visma** | 0.16 hrs/month | +2.0 hrs | 2.16 hrs/month |
| **TOTAL** | **5.32 hrs/month** | **+10.2 hrs/month** | **15.56 hrs/month** |

**Staffing Translation:**
- Current IT time: 5.32 hrs/month (64 hrs/year) = 4% FTE
- Service Owner IT time: 15.56 hrs/month (187 hrs/year) = 12% FTE
- **Additional IT capacity needed: ~8% FTE (122 hours/year) or 2 hours 18 minutes per week**

### Peak Capacity Planning

| Period | Normal Month | Peak Week (Flexite) | Notes |
|--------|-------------|---------------------|-------|
| Total IT hours | 15.56 hrs/month | 16.6 hrs/month | Flexite summer temp prep (1 week/year) |
| FTE equivalent | 10% | 10% | Minimal peak impact |

**Note:** Flexite peak is 2.5 hrs/week for one week per year (sommarvikarier preparation), adding approximately 1 hour to one month's total, resulting in minimal overall monthly impact.

---

## Consolidated Comparison: Current vs Recommended State

### Business Team Capacity Freed Up

| Team | System | Current Time | New Time | **Hours Freed** | **Value Return** |
|------|--------|-------------|----------|-----------------|------------------|
| **Ekonomi** | Ascendo | 12.8 hrs/month | 10.0 hrs/month | 2.8 hrs/month | Financial process work |
| **Safety** | Flexite | 4.2 hrs/month | 1.8 hrs/month | 2.4 hrs/month | Safety compliance & training |
| **Purchasing/Maintenance** | Idus | 5.56 hrs/month | 2.56 hrs/month | 3.0 hrs/month | Maintenance planning |
| **HR** | Agda/Visma | 4.56 hrs/month | 2.56 hrs/month | 2.0 hrs/month | HR/payroll processes |
| **TOTAL** | All systems | **27.12 hrs/month** | **16.92 hrs/month** | **10.2 hrs/month** | **122 hrs/year** |

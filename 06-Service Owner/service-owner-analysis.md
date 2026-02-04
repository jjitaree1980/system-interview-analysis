# IT Support Time Analysis - By Activity

## Total IT Investment: **5.32 hours/month** (1.33 hours/week)

---

## Time Breakdown by Activity

| Activity Category | Ascendo | Idus | Flexite | Agda/Visma | **Monthly Total** | **% of Total** | **Annual Hours** |
|-------------------|---------|------|---------|------------|-------------------|----------------|------------------|
| **User access/login issues** | 0.16 | 0.20 | 0.30 | 0.16 | **0.82 hrs** | 15% | 9.84 hrs |
| **Technical troubleshooting** | - | 0.10 | 0.20 | - | **0.30 hrs** | 6% | 3.60 hrs |
| **Infrastructure support** (backups, updates, monitoring) | - | 1.10 | 1.10 | - | **2.20 hrs** | 41% | 26.40 hrs |
| **Integration troubleshooting** (Idus↔SAP only) | - | 1.00 | - | - | **1.00 hr** | 19% | 12.00 hrs |
| **Vendor coordination** (occasional) | 0.16* | 0.10 | 0.90 | - | **1.00 hr** | 19% | 12.00 hrs |
| **TOTAL per system** | **0.16** | **2.50** | **2.50** | **0.16** | **5.32 hrs** | **100%** | **63.84 hrs** |

**Notes:**
- *Ascendo vendor issues occur 1-2 times per 2 years at 3-4 hours each = ~0.16 hrs/month average*
- *Flexite major updates/patches require 1-2 days (8-16 hours) but occur every 2-3 years = ~0.22-0.44 hrs/month average (included in infrastructure support)*

---

## Integration Status Clarification

| Integration Path | Status | IT Support Required |
|------------------|--------|---------------------|
| **Idus ↔ SAP** | ❌ Broken/unreliable | 1.0 hr/month troubleshooting |
| **Ascendo → SAP** | ✅ Perfect (email/PDF import) | ~0.16 hr/month (rare vendor issues) |

---

## Key Insights from Activity Breakdown

### 🎯 Top 3 Time Consumers

1. **Infrastructure Support (41%)** - 2.2 hrs/month maintaining on-premise Idus/Flexite servers
2. **Integration Troubleshooting (19%)** - 1.0 hr/month fixing Idus-SAP integration failures  
3. **User Access Issues (15%)** - 0.82 hrs/month across all systems

### 💡 What This Reveals

**Ascendo's "Near-Zero" Support Model:**
- Only requires IT intervention 1-2 times per 2 years for vendor coordination
- When issues occur, they're resolved at vendor level (3-4 hour investment per incident)
- Perfect integration means zero ongoing troubleshooting
- **Annual cost: ~2 hours/year**

**Idus's Support Burden:**
- Consumes **47% of all IT time** despite being just 1 of 4 systems
- Integration troubleshooting alone = 40% of Idus support time
- Infrastructure + Integration = 84% of Idus-related IT work
- **Annual cost: ~30 hours/year**

**Flexite's Infrastructure Overhead:**
- Routine maintenance is modest, but major updates are intensive
- Update patches occur every 2-3 years requiring 1-2 days of IT effort per event
- Amortized cost: ~3-5 hours/year for major updates + ongoing monthly maintenance
- **Annual cost: ~30 hours/year total**

**Infrastructure Multiplier:**
- On-premise systems (Idus + Flexite): 5.0 hrs/month combined
- Cloud systems (Ascendo + Agda/Visma): 0.32 hrs/month combined
- **Cloud systems require 93% less IT support**

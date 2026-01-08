# Flexite System Assessment - Pain Points

**System:** Flexite (Incident Management)  
**Assessment Date:** 2026-01-08  
**Super User:** Jan-Eric

---

## Critical Pain Points

### 1. No Government System Integration (e-tjänster)

**Severity:** High  
**Frequency:** Always (12 times per month)  
**Impact:** Manual double-entry of incident data

**Description:**
Jan-Eric must manually log into e-tjänster (government agencies website) to enter incident data that already exists in Flexite. This affects approximately 12 government reports per month.

**Current Workaround:**
Manual login and data entry into government portal

**Business Impact:**
- Time waste from duplicate data entry
- Increased error risk from manual transcription
- Delayed government reporting
- Administrative burden on safety team

**Annual Waste Estimate:**
[Time per report] × 12 monthly reports × 12 months × [hourly rate] = [To be calculated]

---

### 2. Manual Dashboard and Analytics Creation

**Severity:** High  
**Frequency:** Often (per reporting cycle)  
**Impact:** 30-45 minutes of manual data processing per cycle

**Description:**
Management dashboards and analysis reports require manual export from Flexite, pasting into Excel source files, and formula creation. LTA (Lost Time Accident) reports are completely manual.

**Current Workaround:**
Manual data extraction and Excel manipulation

**Business Impact:**
- 30-45 minutes per reporting cycle wasted
- Delayed insights into safety trends
- Limited real-time visibility for management
- Potential for data manipulation errors

**Annual Waste Estimate:**
30-45 minutes × [reporting frequency] × [hourly rate] = [To be calculated]

---

### 3. No Cross-System Integration (Idus, HR, Insurance)

**Severity:** Medium  
**Frequency:** Always  
**Impact:** Siloed incident data prevents workflow automation

**Description:**
Flexite has no integration with Idus (facilities/maintenance), Agda/Visma (HR), or insurance systems. Maintenance-related incidents cannot trigger work orders automatically, and accident data cannot flow to payroll or insurance claims.

**Current Workaround:**
Manual communication and data sharing between systems

**Business Impact:**
- Missed opportunities for automated workflows
- Duplicate data entry across systems
- Incomplete incident visibility across departments
- Delayed response to maintenance-related safety issues

**Annual Waste Estimate:**
Difficult to quantify without workflow analysis - potential for significant efficiency gains

---

## Medium-Level Pain Points

### 4. Multi-Team Coordination Complexity

**Severity:** Medium  
**Frequency:** Often (varies by incident type)  
**Impact:** Preventive action plans require extensive cross-department coordination

**Description:**
Incident analysis and preventive action planning involve multiple teams, creating coordination complexity. This is a business process challenge rather than a system limitation.

**Current Workaround:**
Manual coordination through meetings and follow-ups

**Business Impact:**
- Time-intensive preventive action development
- Potential delays in implementing safety improvements
- Communication overhead across departments

**Note:** This is inherent to thorough safety management rather than a system flaw.

---

### 5. Reporting Culture Concerns

**Severity:** Low-Medium  
**Frequency:** Sometimes  
**Impact:** Potential underreporting due to fear of consequences

**Description:**
Some employees may avoid reporting incidents in Flexite due to fear of complaints or warnings, though Jan-Eric has been addressing this through education and policy changes since joining in 2023.

**Current Workaround:**
Education campaigns and policy adjustments to encourage reporting

**Business Impact:**
- Risk of hidden safety issues
- Incomplete incident data for trend analysis
- Potential regulatory compliance gaps

**Note:** Being actively addressed; system achieves 100% compliance rate for reported incidents.

---

## Summary of Annual Waste

| Pain Point | Annual Time Waste | Estimated Cost | Priority |
|:-----------|:-----------------|:---------------|:---------|
| Government reporting manual entry | [TBC] hours | [TBC] SEK | High |
| Manual dashboard creation | [TBC] hours | [TBC] SEK | High |
| Cross-system data re-entry | [TBC] hours | [TBC] SEK | Medium |
| **Total Estimated Waste** | **[TBC] hours** | **[TBC] SEK** | |

---

## Recommendations

**Immediate Actions:**
1. Quantify exact time spent on manual government reporting and dashboard creation
2. Research e-tjänster API or integration capabilities
3. Evaluate Flexite vendor's roadmap for automated reporting features

**Short-term Improvements:**
1. Implement government system integration to eliminate manual double-entry
2. Add automated dashboard and analysis reporting capabilities
3. Create standardized templates to reduce dashboard creation time

**Long-term Strategy:**
1. Integrate Flexite with Idus for maintenance-related incident workflows
2. Connect to Agda/Visma for personnel data and accident reporting to payroll
3. Explore insurance system integration for claims automation

---

**Document Status:** Draft  
**Next Action:** Calculate specific annual waste figures with Jan-Eric

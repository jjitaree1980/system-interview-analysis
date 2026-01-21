# IT Systems Portfolio - Risk Assessment

**Assessment Date:** January 2026
**Version:** v1.0
**Status:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo 🔄 (Pending)

---

## 📋 Table of Contents

**Executive Summary**
- [Critical Risk Alert](#-critical-risk-alert-investment-decision-risk)
- [Risk Dashboard](#risk-dashboard)
- [Top 5 Risks Requiring Immediate Attention](#top-5-risks-requiring-immediate-attention)

**Risk Analysis**
- [Risk Categories Overview](#risk-categories-overview)
- [Critical Risks (High Likelihood + High Impact)](#critical-risks-high-likelihood--high-impact)
- [Significant Risks (Medium Priority)](#significant-risks-medium-priority)
- [Moderate Risks (Lower Priority)](#moderate-risks-lower-priority)
- [Cross-System Risks](#cross-system-risks)

**Risk Management**
- [Risk Mitigation Strategy](#risk-mitigation-strategy)
- [Risk Monitoring Plan](#risk-monitoring-plan)
- [Contingency Planning](#contingency-planning)

---

## 🚨 CRITICAL RISK ALERT: Investment Decision Risk

### Highest Impact Risk in Portfolio

| Risk | Impact | Likelihood | Financial Exposure | Status |
|------|--------|------------|-------------------|---------|
| **Wrong Idus Investment Decision** | 🔴 **CRITICAL** | 🟡 Medium | **800,000+ SEK** | 🔴 **ACTIVE** |

**Risk Description:**
Committing 800K+ SEK to Idus investment based on single-source unvalidated assessment with identified bias indicators could result in wrong strategic decision for 5-10 years.

**Why This is the #1 Risk:**
- 🔴 **Single largest financial exposure** (800K+ SEK investment at stake)
- 🔴 **97% of waste estimate unvalidated** (4.73M SEK claim based on assumptions)
- 🔴 **Single source data** (one super user interview only)
- 🔴 **Potential bias indicators** (super user prefers existing system)
- 🔴 **No market comparison** (compared to 2016 Maximo, not modern alternatives)
- 🔴 **5-10 year impact** (wrong decision compounds over time)

**Mitigation Status:** ⚠️ **URGENT - Validation study required before investment**

**Recommended Action:**
Invest 100K SEK in validation study to protect against 800K SEK wrong decision (8:1 risk reduction ratio)

---

## Risk Dashboard

### Portfolio Risk Summary

| Category | Critical Risks | Significant Risks | Moderate Risks | Total Risks |
|----------|----------------|-------------------|----------------|-------------|
| **Strategic/Financial** | 1 | 1 | 2 | 4 |
| **Operational** | 3 | 3 | 2 | 8 |
| **Technical** | 2 | 2 | 2 | 6 |
| **Compliance** | 0 | 1 | 1 | 2 |
| **People/Knowledge** | 1 | 2 | 1 | 4 |
| **Data Quality** | 2 | 0 | 1 | 3 |
| **TOTAL** | **9** | **9** | **9** | **27** |

### Risk Distribution by System

| System | Critical | Significant | Moderate | Total | Assessment Confidence |
|--------|----------|-------------|----------|-------|---------------------|
| **Idus** | 5 | 5 | 5 | 15 | 🔴 Low (single source) |
| **Agda/Visma** | 1 | 2 | 1 | 4 | 🟢 High (validated) |
| **Flexite** | 2 | 2 | 2 | 6 | 🟢 High |
| **Cross-System** | 1 | 0 | 1 | 2 | 🟡 Medium |

**Key Insight:** Idus dominates risk landscape (56% of all identified risks), but **assessment confidence is LOW** due to single-source data.

### Risk Heat Map

```
                    HIGH IMPACT
                         │
    Critical Threats     │     Top Priority
    (Immediate Action)   │     (Strategic Focus)
                         │
         9 risks         │        9 risks
                         │
    ─────────────────────┼─────────────────────
                         │
    Monitor & Manage     │     Low Priority
                         │     (Track Only)
                         │
         9 risks         │        0 risks
                         │
                    LOW IMPACT

           LOW ────────────────────── HIGH
               LIKELIHOOD
```

---

## Top 5 Risks Requiring Immediate Attention

### 1. 🔴 Wrong Idus Investment Decision

| Attribute | Value |
|-----------|-------|
| **Category** | Strategic/Financial Risk |
| **System(s)** | Idus |
| **Likelihood** | 🟡 Medium (50%) |
| **Impact** | 🔴 Critical (800K+ SEK exposure) |
| **Risk Score** | **CRITICAL** |
| **Current Status** | ⚠️ Active - Requires immediate mitigation |
| **Financial Exposure** | 800,000+ SEK wrong investment + opportunity cost |

**Description:**
Committing major investment to Idus (800K+ SEK) based on unvalidated single-source assessment could result in suboptimal 5-year strategic decision. Modern CMMS alternatives not evaluated, actual waste not validated, and potential bias indicators present in assessment.

**Potential Consequences:**
- 800K SEK invested in wrong solution
- Opportunity cost of better alternatives missed
- Continued waste not addressed effectively
- Technical debt accumulation continues
- 5-10 year impact from wrong strategic choice
- Competitive disadvantage vs. modern platforms

**Mitigation Strategy:**
✅ **IMMEDIATE:** Invest 100K SEK in validation study (3-4 months)
- Time-tracking study validates actual waste (not estimates)
- Multi-user interviews beyond single super user
- Modern CMMS market evaluation (Planon, Ultimo, Fiix, eMaint)
- 5-year TCO comparison (Idus vs. alternatives)
- Data-driven decision gate before 800K commitment

**Owner:** IT Leadership / Management

**Timeline:** Month 1 (approve study) → Months 1-4 (execute) → Month 4-5 (decision gate)

**Success Metric:** Data-driven investment decision made with 100K study protecting 800K decision (8:1 ROI)

---

### 2. 🔴 Technical Debt Accumulation (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | Technical Risk |
| **System(s)** | Idus |
| **Likelihood** | 🔴 High (Already occurring) |
| **Impact** | 🔴 High (Cascading failures) |
| **Risk Score** | **CRITICAL** |
| **Current Status** | 🔴 Active - Already materializing |
| **Annual Cost** | 1,552,000 SEK (broken SAP integration) |

**Description:**
Delayed version upgrade has created cascading problems (broken SAP integration unfixable without upgrade). Further delays compound technical debt, making future upgrades increasingly difficult and expensive.

**Warning Signs:**
- Version upgrade significantly delayed
- SAP integration broken and unfixable
- Gap between current and latest version widening
- Multiple manual workarounds in place
- User confidence in data only "somewhat"

**Potential Consequences:**
- More integrations break over time
- Increasing upgrade difficulty and cost
- Loss of access to newer features
- Potential vendor support end-of-life
- Security vulnerabilities in outdated versions
- Forced emergency upgrade at worst time

**Mitigation Strategy:**
- **IF keeping Idus:** Execute version upgrade within 6 months
- **IF replacing:** Include in replacement timeline
- Establish regular upgrade schedule (annual or bi-annual)
- Monitor vendor support lifecycle
- Budget for ongoing system maintenance

**Owner:** IT Operations + Idus Super User

**Dependencies:** Contingent on Idus validation study decision (invest vs. replace)

---

### 3. 🔴 Key Person Dependencies (Idus + Flexite)

| Attribute | Value |
|-----------|-------|
| **Category** | People/Knowledge Risk |
| **System(s)** | Idus (Tom), Flexite (Jan-Eric) |
| **Likelihood** | 🟡 Medium |
| **Impact** | 🔴 High (Operational disruption) |
| **Risk Score** | **CRITICAL** |
| **Current Status** | ⚠️ Active - No backup capacity |

**Description:**
**Idus:** Single super user handles system administration, integrations, reporting (2+ days per report), and user support for 30 users managing 1,800 tickets/month.

**Flexite:** Single Health & Safety Manager (8 years system experience) manages compliance-critical safety system for Arbetsmiljöverket requirements.

**Potential Consequences:**
- **If Idus super user unavailable:**
  - No management reports generated
  - System administration gaps
  - Integration troubleshooting failures
  - User support unavailable
  - Knowledge loss
  - 1,800 monthly tickets at risk

- **If Flexite super user unavailable:**
  - Compliance reporting disruption (144 government reports/year)
  - Safety incident management compromised
  - Arbetsmiljöverket legal compliance risk
  - 120-140 monthly incidents unprocessed

**Mitigation Strategy:**
**Immediate Actions:**
1. Train additional super users for both systems
2. Document system administration procedures
3. Cross-train backup personnel
4. Create knowledge transfer program
5. Establish vendor support relationships

**Agda/Visma Comparison (Lower Risk):**
- Two-person team (Helena + new hire)
- Backup capacity exists
- Still recommend backup capability assessment

**Owner:** HR + IT + System Super Users

**Timeline:** Initiate Month 1, Complete Month 3

---

### 4. 🔴 Data Quality Deterioration (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | Data Quality Risk |
| **System(s)** | Idus |
| **Likelihood** | 🟡 Medium-High |
| **Impact** | 🔴 High |
| **Risk Score** | **CRITICAL** |
| **Current Status** | 🔴 Already compromised |
| **Annual Cost** | 102,500 SEK (manual verification + error costs) |

**Description:**
Super user only "somewhat confident" in data accuracy due to poor data hygiene and incomplete data structure from historical migration. Data quality will deteriorate further without intervention through user errors, incomplete entries, and lack of governance.

**Warning Signs:**
- Poor data hygiene practices
- Inadequate data structure design
- Historical data quality issues from Maximo migration
- No data governance framework
- User confidence only "somewhat"
- Affects reporting accuracy and reliability

**Potential Consequences:**
- Unreliable data for maintenance planning
- Poor decision-making from inaccurate information
- Compliance and audit risks
- Reduced user trust in system
- Increased manual verification overhead (102.5K SEK/year)
- Foundation for analytics undermined

**Mitigation Strategy:**
**Required regardless of Idus decision (invest or replace):**
1. Execute comprehensive data cleansing project (150K SEK investment)
2. Establish data governance framework
3. Implement data quality monitoring
4. Train users on proper data entry standards
5. Assign data ownership and accountability
6. Regular data audits

**Owner:** Idus Super User + IT Data Governance

**Timeline:** Months 1-4 (parallel to validation study)

---

### 5. 🔴 System Unavailability Risk (Idus + Flexite)

| Attribute | Value |
|-----------|-------|
| **Category** | Operational Risk |
| **System(s)** | Idus (9/10 critical), Flexite (9/10 critical) |
| **Likelihood** | 🟡 Medium |
| **Impact** | 🔴 Critical (Operations halt) |
| **Risk Score** | **CRITICAL** |
| **Current Status** | ⚠️ Potential risk |

**Description:**
**Idus (9/10 criticality):** Handles ~1,800 tickets/month. User states unavailability would severely disrupt operations: "UH would have problem on the WO and PM plan management, it's hard to track and maintain the asset which is important to the production line."

**Flexite (9/10 criticality):** Essential for Arbetsmiljöverket compliance. 100% employee adoption means safety incident management dependent on system availability.

**Potential Consequences:**
- **Idus:** Complete loss of work order management, PM planning/tracking, asset history access, production line maintenance severely impacted, potential equipment failures, manual paper processes inadequate for 1,800/month volume

- **Flexite:** Safety compliance disruption, incident management failure, Arbetsmiljöverket legal risk, 120-140 monthly incidents untracked

**Mitigation Strategy:**
1. Develop business continuity plans with manual backup procedures
2. Implement redundant super user training
3. Regular system backups and disaster recovery testing
4. For Idus: Cloud migration evaluation (if keeping system)
5. Document critical workflows for manual execution
6. Establish vendor SLA monitoring

**Owner:** IT Operations + Business Continuity Planning

---

## Risk Categories Overview

### Strategic/Financial Risks (4 risks)

| Risk | System | Likelihood | Impact | Score | Status |
|------|--------|------------|--------|-------|--------|
| Wrong Idus investment decision | Idus | 🟡 Medium | 🔴 Critical | **CRITICAL** | ⚠️ Active |
| Budget visibility blind spot | Idus | 🔴 High | 🟡 Medium | **SIGNIFICANT** | 🔴 Occurring |
| Vendor lock-in without upgrades | Idus | 🟡 Medium | 🟡 Medium | **MODERATE** | 🟡 Developing |
| Competitive disadvantage | Idus | 🟡 Medium | 🟡 Low-Med | **MODERATE** | 🟡 Developing |

**Total Financial Exposure:** 800K+ SEK (Idus wrong decision) + 226K SEK/year (budget overruns)

---

### Operational Risks (8 risks)

| Risk | System | Likelihood | Impact | Score | Status |
|------|--------|------------|--------|-------|--------|
| System unavailability | Idus, Flexite | 🟡 Medium | 🔴 Critical | **CRITICAL** | ⚠️ Active |
| Integration fragility | Idus | 🟡 Medium | 🔴 Med-High | **SIGNIFICANT** | 🔴 Occurring |
| User adoption erosion | Idus | 🟡 Medium | 🟡 Medium | **SIGNIFICANT** | 🔴 Occurring |
| Shift leader Excel gatekeeping waste | Idus, Flexite | 🔴 High | 🟡 Medium | **SIGNIFICANT** | 🔴 Occurring |
| Self-service underutilization | Agda/Visma | 🔴 High | 🟡 Medium | **SIGNIFICANT** | 🔴 Occurring |
| Manual government reporting burden | Flexite | 🔴 High | 🟡 Medium | **SIGNIFICANT** | 🔴 Occurring |
| Parallel system proliferation | Idus | 🟡 Low-Med | 🟡 Low-Med | **MODERATE** | 🔴 Occurring |
| Incomplete work logging | Idus | 🟡 Medium | 🟡 Medium | **MODERATE** | 🔴 Occurring |

**Annual Operational Waste:** 150K SEK (validated: Agda + Flexite) + 4.73M SEK (unvalidated: Idus)

---

### Technical Risks (6 risks)

| Risk | System | Likelihood | Impact | Score | Status |
|------|--------|------------|--------|-------|--------|
| Technical debt accumulation | Idus | 🔴 High | 🔴 High | **CRITICAL** | 🔴 Occurring |
| Integration failures | Idus (SAP) | 🔴 High | 🔴 High | **CRITICAL** | 🔴 Occurring |
| System integration isolation | Flexite | 🔴 High | 🟡 Medium | **SIGNIFICANT** | 🔴 Occurring |
| System performance degradation | Idus | 🟡 Medium | 🟡 Medium | **MODERATE** | 🔴 Occurring |
| Manual process reliance | All systems | 🔴 High | 🟡 Low-Med | **MODERATE** | 🔴 Occurring |
| Legacy infrastructure dependency | Idus | 🟡 Medium | 🟡 Low-Med | **MODERATE** | 🟡 Developing |

**Primary Technical Issue:** Broken SAP integration costing 1.55M SEK/year (unvalidated estimate)

---

### Compliance Risks (2 risks)

| Risk | System | Likelihood | Impact | Score | Status |
|------|--------|------------|--------|-------|--------|
| Flexite compliance disruption | Flexite | 🟡 Low-Med | 🔴 High | **SIGNIFICANT** | 🟡 Potential |
| Regulatory compliance gaps | Idus | 🟡 Low-Med | 🟡 Medium | **MODERATE** | 🟡 Potential |

**Compliance Context:**
- **Flexite:** Arbetsmiljöverket (Swedish Work Environment Authority) legal requirements
- **Agda/Visma:** Payroll regulations and tax compliance (10/10 critical, zero failures)
- **Idus:** Maintenance documentation for regulatory investigations

---

### People/Knowledge Risks (4 risks)

| Risk | System | Likelihood | Impact | Score | Status |
|------|--------|------------|--------|-------|--------|
| Key person dependency | Idus, Flexite | 🟡 Medium | 🔴 High | **CRITICAL** | ⚠️ Active |
| Loss of institutional knowledge | Idus | 🟡 Medium | 🟡 Medium | **SIGNIFICANT** | 🟡 Growing |
| Insufficient backup capacity | Agda/Visma | 🟡 Low-Med | 🟡 Medium | **SIGNIFICANT** | 🟡 Potential |
| User training gaps | Idus, Agda | 🟡 Medium | 🟡 Low-Med | **MODERATE** | 🔴 Occurring |

**Single Points of Failure:**
- Idus: 1 super user (Tom) for 30 users, 1,800 tickets/month
- Flexite: 1 super user (Jan-Eric) for compliance-critical safety system
- Agda/Visma: 2-person team (lower risk, but backup capability needs assessment)

---

### Data Quality Risks (3 risks)

| Risk | System | Likelihood | Impact | Score | Status |
|------|--------|------------|--------|-------|--------|
| Data quality deterioration | Idus | 🟡 Med-High | 🔴 High | **CRITICAL** | 🔴 Compromised |
| Poor data hygiene/structure | Idus | 🔴 High | 🔴 High | **CRITICAL** | 🔴 Occurring |
| Data export adjustments | Flexite | 🟡 Medium | 🟡 Low-Med | **MODERATE** | 🔴 Occurring |

**Data Confidence Levels:**
- 🔴 Idus: LOW (poor hygiene/structure, "somewhat confident")
- 🟢 Agda/Visma: HIGH (validated, reliable)
- 🟢 Flexite: HIGH (note: users adjust exports for workflows)

---

## Critical Risks (High Likelihood + High Impact)

### RISK 1: Wrong Idus Investment Decision
*[Detailed above in Top 5 - #1]*

---

### RISK 2: Technical Debt Accumulation (Idus)
*[Detailed above in Top 5 - #2]*

---

### RISK 3: Key Person Dependencies
*[Detailed above in Top 5 - #3]*

---

### RISK 4: Data Quality Deterioration (Idus)
*[Detailed above in Top 5 - #4]*

---

### RISK 5: System Unavailability Risk
*[Detailed above in Top 5 - #5]*

---

### RISK 6: Integration Failures (Idus - SAP)

| Attribute | Value |
|-----------|-------|
| **Category** | Technical Risk |
| **System(s)** | Idus |
| **Likelihood** | 🔴 High (Already failed) |
| **Impact** | 🔴 High |
| **Risk Score** | **CRITICAL** |
| **Current Status** | 🔴 Active failure |
| **Annual Cost** | 1,552,000 SEK (unvalidated estimate) |

**Description:**
SAP inventory integration broken and unfixable without version upgrade. Forces manual verification of spare parts availability for ~10,800 work orders per year, creating massive coordination overhead and potential delays.

**Current Workarounds:**
- Manual verification: 10 min/ticket estimate = 1,800 hours/year
- Custom warehouse search program (IT-developed)
- Barcode scanner system (separate from Idus)
- Manual coordination between technicians and warehouse

**Potential Consequences:**
- Continued manual coordination waste (1.55M SEK/year if estimate accurate)
- Delayed maintenance execution
- Increased errors from manual processes
- Further integration failures may occur
- Reduced operational efficiency

**Mitigation Strategy:**
- **IF keeping Idus:** Execute version upgrade to restore SAP integration
- **IF replacing:** Select CMMS with reliable SAP integration capability
- Regular integration monitoring and testing
- Establish vendor support for integration issues
- Document integration architecture

**Dependencies:** Idus validation study decision gate

---

### RISK 7: Poor Data Hygiene & Structure (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | Data Quality Risk |
| **System(s)** | Idus |
| **Likelihood** | 🔴 High (Confirmed existing) |
| **Impact** | 🔴 High |
| **Risk Score** | **CRITICAL** |
| **Current Status** | 🔴 Active issue |

**Description:**
System has poor data hygiene practices and inadequate data structure design. Affects all reporting, analytics, and decision-making capabilities. Super user only "somewhat confident" in data accuracy.

**Warning Signs:**
- Data structure issues identified in assessment
- Inconsistent data cleaning procedures
- Historical migration problems from Maximo
- Reporting accuracy concerns
- Manual verification required for critical decisions

**Potential Consequences:**
- Unreliable foundation for any analytics or BI tools
- Poor data migrates to any replacement system if not cleaned
- Decision-making based on questionable information
- Waste estimates themselves may be inaccurate due to data issues
- Compliance and audit trail reliability concerns

**Mitigation Strategy:**
**REQUIRED REGARDLESS OF IDUS DECISION:**
1. Comprehensive data audit and assessment (included in validation study)
2. Data cleansing project (150K SEK estimated)
3. Establish data governance framework
4. Standardized data entry procedures
5. Data quality monitoring implementation
6. User training on data standards

**Critical:** Clean data essential whether upgrading Idus OR migrating to new system

---

### RISK 8: System Integration Isolation (Flexite)

| Attribute | Value |
|-----------|-------|
| **Category** | Technical Risk |
| **System(s)** | Flexite |
| **Likelihood** | 🔴 High (By design - zero integrations) |
| **Impact** | 🟡 Medium |
| **Risk Score** | **CRITICAL** |
| **Current Status** | 🔴 Active limitation |
| **Annual Cost** | 60-90K SEK (government reporting + dashboards) |

**Description:**
Flexite operates in complete isolation with ZERO integrations to any other business system (Idus, Agda/Visma, government e-tjänster). While core functionality is excellent (100% adoption), isolation creates manual burden and missed opportunities.

**Current Impact:**
- 144 manual government reports per year (double-entry to e-tjänster)
- Manual dashboard creation (30-45 min per cycle)
- No connection to Idus for maintenance-related incidents
- Separate system training and management overhead

**Potential Consequences:**
- Continued manual government reporting waste (60-75K SEK/year)
- Duplicate data entry between systems
- Incomplete visibility across safety and maintenance
- Manual coordination overhead
- Missed opportunities for automated workflows

**Mitigation Strategy:**
**Priority investments:**
1. Government system (e-tjänster) integration - 70-100K SEK (Priority #2 overall)
2. Automated dashboard implementation - 30-50K SEK
3. Future: Evaluate Flexite-Idus integration (depends on Idus decision)

**Status:** Ready to plan (Month 1-2), implement (Months 3-6)

---

### RISK 9: Shift Leader Excel Gatekeeping Waste

| Attribute | Value |
|-----------|-------|
| **Category** | Operational Risk (Cross-System) |
| **System(s)** | Idus + Flexite |
| **Likelihood** | 🔴 High (Confirmed occurring) |
| **Impact** | 🟡 Medium |
| **Risk Score** | **CRITICAL** |
| **Current Status** | 🔴 Active - Costs unquantified |
| **Estimated Cost** | 50-100K+ SEK/year (unmeasured) |

**Description:**
**CRITICAL DISCOVERY:** Both Idus and Flexite have hidden multi-layer workflow where shift leaders maintain Excel tracking sheets, analyze data, and decide what enters formal systems. This creates:

**Idus Process (5 steps):**
1. Shift leaders maintain Excel tracking sheets
2. Analyze to determine Idus need
3. Create Excel "Felanmälan" reports
4. Super user manually reviews
5. Super user decides work order vs. quick fix
- **Result:** Triple data entry (Excel → Felanmälan → Idus)

**Flexite Process (4 steps):**
1. Shift leaders maintain Excel tracking sheets
2. Analyze to determine Flexite need
3. Enter selected incidents in Flexite
4. Super user manually analyzes for preventive plans
- **Result:** Double data entry (Excel → Flexite)

**Hidden Costs (Currently Unquantified):**
- Shift leader Excel maintenance time
- Shift leader analysis and decision time
- Double/triple data entry waste
- Information delays (data sits in Excel before system entry)
- Potential information loss (not everything in Excel enters systems)
- Data integrity risks from manual transfers
- Inconsistent filtering criteria across shift leaders

**Strategic Question:**
**Should shift leaders be gatekeepers, or should systems enable direct entry?**

**Why Flexite Succeeds Despite Complexity:**
- Same gatekeeping workflow as Idus
- BUT achieves 100% compliance
- Demonstrates clear system design + strong support can overcome complexity

**Why Idus Struggles:**
- Same gatekeeping workflow as Flexite
- BUT experiences system bypass
- Suggests usability or support structure issues

**Mitigation Strategy:**
1. **Immediate:** Quantify shift leader Excel time (include in Idus validation study)
2. Map complete workflow for both systems
3. Assess information loss and delays
4. Compare: Why does Flexite succeed where Idus struggles?
5. Determine: Is gatekeeping necessary or process design failure?
6. **Solutions:** Simplify entry, strengthen support, redesign workflow, or provide mobile tools

**Priority:** HIGH - Include in Idus validation study (Months 1-3)

---

## Significant Risks (Medium Priority)

### RISK 10: Budget Visibility Blind Spot (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | Strategic/Financial Risk |
| **System(s)** | Idus |
| **Likelihood** | 🔴 High (Confirmed) |
| **Impact** | 🟡 Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🔴 Occurring |
| **Annual Cost** | 226,400 SEK (budget overruns + manual tracking) |

**Description:**
No ability to track maintenance costs against budget in real-time. Super user explicitly states "we do not know if we reach to the budget." Creates risk of budget overruns without awareness until too late.

**Potential Consequences:**
- Budget overruns discovered too late (200K SEK/year estimate)
- Reactive cost management instead of proactive
- No early warning system
- Difficulty justifying budget requests
- Manual tracking overhead (26.4K SEK/year)

**Mitigation Strategy:**
- **IF keeping Idus:** Purchase reporting module with budget tracking
- **IF replacing:** Select CMMS with built-in budget visibility
- Interim: Establish manual budget review cadence
- Create cost alerts and thresholds

---

### RISK 11: User Adoption Erosion (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | Operational Risk |
| **System(s)** | Idus |
| **Likelihood** | 🟡 Medium |
| **Impact** | 🟡 Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🔴 Partially occurring |
| **Annual Cost** | 139,040 SEK (system bypass waste) |

**Description:**
Blue-collar workers and production team already bypassing system for phone/email due to system complexity and usability issues. Poor performance and difficult workflows could drive more users to abandon system, creating incomplete data.

**Warning Signs:**
- System bypass behavior confirmed
- Slow performance frustrating users
- Quick fixes not logged (490K SEK/year additional waste)
- Users prefer phone/email over system

**Mitigation Strategy:**
- Address performance (cloud migration evaluation)
- Simplify interfaces for occasional users
- Implement mobile platform for field access
- Create quick-logging mechanisms
- Targeted training programs
- Monitor adoption metrics

**Compare to Flexite:** 100% adoption achieved despite complexity - suggests usability design matters

---

### RISK 12: Self-Service Underutilization (Agda/Visma)

| Attribute | Value |
|-----------|-------|
| **Category** | Operational Risk |
| **System(s)** | Agda/Visma |
| **Likelihood** | 🔴 High (Confirmed 20% adoption) |
| **Impact** | 🟡 Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🔴 Occurring |
| **Annual Cost** | 42-83K SEK (manual entry waste) |

**Description:**
Only ~20% of employees use self-service portal for leave requests. Most still submit paper forms, creating manual data entry burden for HR team (2-4 hours/week waste).

**Root Causes:**
- Digital literacy gaps
- Computer discomfort among some users
- Insufficient training on self-service features
- Resistance to change

**Potential Consequences:**
- Continued manual HR workload (42-83K SEK/year)
- Underutilization of purchased features
- Lower ROI on Agda/Visma investment
- Employee dissatisfaction with paper processes

**Mitigation Strategy:**
**Priority #1 action (ready to execute):**
1. Launch self-service adoption campaign (20-30K SEK)
2. Digital literacy training program (10-20K SEK)
3. User-friendly guides and materials (5-10K SEK)
4. Celebrate early adopters
5. Monitor adoption improvement

**Expected Outcome:** 20% → 80%+ adoption, 42-83K SEK/year savings

---

### RISK 13: Manual Government Reporting Burden (Flexite)

| Attribute | Value |
|-----------|-------|
| **Category** | Operational Risk |
| **System(s)** | Flexite |
| **Likelihood** | 🔴 High (Occurring) |
| **Impact** | 🟡 Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🔴 Active |
| **Annual Cost** | 60-75K SEK (144 reports/year) |

**Description:**
Super user manually logs into government website (e-tjänster) to enter incident data that already exists in Flexite. 144 reports per year represent pure manual double-entry waste with no legitimate business justification.

**Potential Consequences:**
- Continued manual reporting waste (60-75K SEK/year)
- Risk of transcription errors
- Delayed compliance reporting
- Super user time diverted from preventive safety work

**Mitigation Strategy:**
**Priority #2 action (ready to plan):**
1. Research e-tjänster API capabilities (Months 1-2)
2. Engage Flexite vendor on integration roadmap
3. Design and implement integration (Months 3-6)
4. Eliminate 144 manual reports
5. Investment: 70-100K SEK

**Expected Outcome:** 144 reports/year → 0, 60-75K SEK/year savings, 13-18 month payback

---

### RISK 14: Loss of Institutional Knowledge (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | People/Knowledge Risk |
| **System(s)** | Idus |
| **Likelihood** | 🟡 Medium |
| **Impact** | 🟡 Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🟡 Growing risk |

**Description:**
Incomplete data cleansing from Maximo migration means institutional knowledge about data interpretation and system quirks resides with key individuals (super user). Loss of these individuals means loss of context for historical data.

**Potential Consequences:**
- Inability to interpret historical data correctly
- Lost context for equipment history
- Difficulty troubleshooting recurring issues
- Reduced value of asset database
- New users unable to leverage full capabilities

**Mitigation Strategy:**
1. Document data interpretation guidelines
2. Create comprehensive system user guide
3. Cross-train multiple users
4. Execute data cleansing (reduces interpretation needs)
5. Capture tribal knowledge before lost

---

### RISK 15: Insufficient Backup Capacity (Agda/Visma)

| Attribute | Value |
|-----------|-------|
| **Category** | People/Knowledge Risk |
| **System(s)** | Agda/Visma |
| **Likelihood** | 🟡 Low-Medium |
| **Impact** | 🟡 Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🟡 Requires assessment |

**Description:**
While HR department has two people working with system (Helena + new hire), depth of secondary user's expertise unclear. Given 10/10 criticality and payroll regulatory obligations, backup capability requires validation.

**Note:** Lower risk than Idus/Flexite single-person dependencies, but still requires attention for business continuity.

**Potential Consequences:**
- Payroll disruption during primary user absence
- Compliance risks if backup insufficient
- Delayed payroll processing (high employee impact)
- Regulatory violations if errors occur

**Mitigation Strategy:**
1. Assess backup user's current capability level
2. Complete knowledge transfer program
3. Document all critical payroll workflows
4. Test backup capability (process full payroll cycle)
5. Establish escalation to vendor support if needed

---

### RISK 16: Compliance Disruption (Flexite)

| Attribute | Value |
|-----------|-------|
| **Category** | Compliance Risk |
| **System(s)** | Flexite |
| **Likelihood** | 🟡 Low-Medium |
| **Impact** | 🔴 High |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🟡 Potential risk |

**Description:**
Flexite is essential for Arbetsmiljöverket (Swedish Work Environment Authority) compliance. System unavailability or failure could result in legal compliance violations and regulatory penalties.

**Regulatory Context:**
- Legal requirement to report workplace incidents
- 144 government reports required annually
- 100% employee adoption demonstrates criticality
- 9/10 criticality rating

**Potential Consequences:**
- Arbetsmiljöverket compliance violations
- Regulatory fines and penalties
- Legal liability for unreported incidents
- Reputation damage
- Inability to track safety performance

**Mitigation Strategy:**
1. Maintain strong vendor relationship
2. Business continuity plan with manual reporting backup
3. Regular system health monitoring
4. Prioritize government integration (eliminates manual reporting risk)
5. Document compliance reporting procedures

**Current Status:** System healthy, 100% adoption, good vendor support

---

### RISK 17: Integration Complexity Growth (Idus)

| Attribute | Value |
|-----------|-------|
| **Category** | Technical Risk |
| **System(s)** | Idus |
| **Likelihood** | 🟡 Medium |
| **Impact** | 🟡 Medium-High |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🔴 Already occurring |

**Description:**
SAP integration already broken. No procurement integration exists. As Idus gaps persist, integration fragility may worsen, forcing more manual coordination and increasing operational complexity.

**Current State:**
- SAP integration: BROKEN (cannot fix without upgrade)
- Procurement system: NO INTEGRATION (manual warehouse visits)
- Stopptider (downtime): SEPARATE SYSTEM
- Warehouse search: CUSTOM WORKAROUND
- Barcode scanner: PARALLEL SYSTEM

**Potential Consequences:**
- Further integration failures
- Increased manual workaround development
- System fragmentation continues
- Higher IT maintenance burden (49.5K SEK/year current)
- Data scattered across multiple systems

**Mitigation Strategy:**
- **IF keeping Idus:** Version upgrade + integration restoration plan
- **IF replacing:** Select CMMS with strong integration capabilities
- Establish integration architecture governance
- Monitor integration health regularly

---

### RISK 18: Manual Dashboard Creation (Flexite)

| Attribute | Value |
|-----------|-------|
| **Category** | Operational Risk |
| **System(s)** | Flexite |
| **Likelihood** | 🔴 High (Occurring) |
| **Impact** | 🟡 Low-Medium |
| **Risk Score** | **SIGNIFICANT** |
| **Current Status** | 🔴 Active |
| **Annual Cost** | 15K SEK (30-45 min/cycle) |

**Description:**
Management dashboards and LTA reports created manually by exporting Flexite data and processing in Excel every reporting cycle (30-45 minutes per cycle).

**Potential Consequences:**
- Continued manual effort waste (15K SEK/year)
- Delayed visibility into safety trends
- Potential data manipulation errors
- Slower decision-making on safety issues

**Mitigation Strategy:**
**Part of Priority #2 Flexite investment:**
1. Implement automated dashboard solution (30-50K SEK)
2. Real-time safety trend visibility
3. Standardized reporting formats
4. Investment included in government integration project

**Expected Outcome:** 30-45 min/cycle → Automated, 15K SEK/year savings, 2-4 year payback

---

## Moderate Risks (Lower Priority)

### Strategic/Financial

**RISK 19: Vendor Lock-In Without Upgrades (Idus)**
- Likelihood: Medium | Impact: Medium
- Falling behind on upgrades increases dependency, reduces future flexibility
- May reach end-of-support, forcing expensive emergency actions

**RISK 20: Competitive Disadvantage (Idus)**
- Likelihood: Medium | Impact: Low-Medium
- Industry moving to mobile-first, cloud-based, analytics-driven platforms
- Current Idus lacks modern capabilities

### Operational

**RISK 21: Parallel System Proliferation (Idus)**
- Likelihood: Low-Medium | Impact: Low-Medium
- Multiple parallel systems already exist (Stopptider, warehouse search, barcode)
- System fragmentation increasing (49.5K SEK/year maintenance)

**RISK 22: Incomplete Work Logging (Idus)**
- Likelihood: Medium | Impact: Medium
- Quick fixes (~5 min) not logged, creating incomplete records
- Missed recurring issue patterns (490K SEK/year waste)

### Technical

**RISK 23: System Performance Degradation (Idus)**
- Likelihood: Medium | Impact: Medium
- Slow system performance reduces productivity (627K SEK/year estimate)
- Local infrastructure vs. cloud limitation

**RISK 24: Manual Process Reliance (All Systems)**
- Likelihood: High | Impact: Low-Medium
- Heavy reliance on manual processes across all systems
- Creates fragility and scaling limitations

### Compliance

**RISK 25: Regulatory Compliance Gaps (Idus)**
- Likelihood: Low-Medium | Impact: Medium
- Incomplete logging creates potential audit risks
- Quick fixes not documented for investigations

### People/Knowledge

**RISK 26: User Training Gaps (Idus, Agda/Visma)**
- Likelihood: Medium | Impact: Low-Medium
- Insufficient training contributing to adoption challenges
- Digital literacy gaps in some user populations

### Data Quality

**RISK 27: Data Export Adjustments (Flexite)**
- Likelihood: Medium | Impact: Low-Medium
- Users export and adjust data for company workflows
- May indicate system limitations or legitimate business requirements
- Requires investigation to determine root cause

---

## Cross-System Risks

### 🔴 Investment Decision Risk Portfolio

| Risk | Financial Exposure | Mitigation Investment | ROI |
|------|-------------------|---------------------|-----|
| Wrong Idus decision | 800K+ SEK | 100K SEK validation | 8:1 protection |
| Unvalidated waste estimates | 4.73M SEK/year | 100K SEK validation | Data-driven decisions |
| Missed modern alternatives | Opportunity cost | 100K SEK market eval | Informed choice |

**Portfolio Risk:** Highest financial exposure in entire assessment. Immediate mitigation required.

---

### 🟡 Single Point of Failure Pattern

| System | Super User | Criticality | Backup | Risk Level |
|--------|-----------|-------------|--------|------------|
| Idus | Tom | 9/10 | ❌ None | 🔴 High |
| Flexite | Jan-Eric | 9/10 | ❌ None | 🔴 High |
| Agda/Visma | Helena | 10/10 | ⚠️ Assess | 🟡 Medium |

**Pattern Risk:** Key person dependencies across multiple critical systems. Cross-training program needed.

---

## Risk Mitigation Strategy

### Immediate Actions (Month 1) - EXECUTE NOW

| Action | Risk Mitigated | Investment | Impact |
|--------|---------------|------------|--------|
| **Approve Idus validation study** | Wrong investment decision | 100K SEK | Protects 800K decision |
| **Launch Agda self-service campaign** | Underutilization waste | 30-70K SEK | 42-83K SEK/year savings |
| **Initiate cross-training program** | Key person dependencies | 20-30K SEK | Business continuity |
| **Begin backup procedure documentation** | Knowledge loss | 10K SEK | Risk reduction |

**Total Month 1 Investment:** 160-210K SEK
**Risk Reduction:** 800K SEK exposure + operational continuity

---

### Short-Term (Months 1-4) - VALIDATION & PLANNING

**Idus Validation Study (Parallel Activities):**
- [ ] Time-tracking validation (actual vs. estimated waste)
- [ ] Multi-user interviews (beyond single super user)
- [ ] Modern CMMS market evaluation (3-5 vendors)
- [ ] Data quality audit (cleansing requirements)
- [ ] Shift leader Excel workflow investigation
- [ ] 5-year TCO comparison (Idus vs. alternatives)

**Agda/Visma Improvements (Ongoing):**
- [ ] Execute self-service training program
- [ ] Digital literacy support deployment
- [ ] Monitor adoption metrics
- [ ] Fix shift calculation validation

**Flexite Planning:**
- [ ] Research e-tjänster API capabilities
- [ ] Engage vendor on integration roadmap
- [ ] Design dashboard automation requirements

**Ascendo:**
- [ ] Complete assessment interview
- [ ] Integrate findings into risk portfolio

---

### Decision Gate (Month 4-5) - CRITICAL POINT

**🎯 Idus Investment Decision Based on Validation Results**

**Decision Criteria:**
- [ ] Validation study results reviewed
- [ ] 5-year TCO comparison completed
- [ ] Modern alternatives evaluated
- [ ] Management decision made

**Possible Outcomes:**
- **Path A:** Invest in Idus (800K SEK) - Execute upgrade + modules
- **Path B:** Replace with modern CMMS - Begin implementation
- **Path C:** Hybrid - Targeted improvements + future replacement

**Risk Mitigation Impact:**
- Wrong decision risk: **ELIMINATED** (data-driven choice made)
- Technical debt risk: **ADDRESSED** (upgrade or replacement planned)
- Integration risk: **PLANNED** (SAP restoration or new system)

---

### Medium-Term (Months 5-12) - IMPLEMENTATION

**Based on Decision Gate Outcomes:**

**Agda/Visma:**
- [ ] Monitor self-service adoption improvements
- [ ] Achieve 80%+ adoption target
- [ ] Document lessons learned

**Flexite:**
- [ ] Implement government integration (144 reports eliminated)
- [ ] Deploy automated dashboards
- [ ] Investigate shift leader workflow optimization

**Idus (Path Dependent):**
- [ ] Execute approved investment path
- [ ] Implement data quality improvements
- [ ] Restore integrations or migrate systems
- [ ] Address key person dependency

---

### Long-Term (Months 12-24) - OPTIMIZATION

- [ ] Post-implementation review for all systems
- [ ] Validate actual risk reduction vs. projections
- [ ] Update risk register based on new information
- [ ] Plan next wave of risk mitigation
- [ ] Establish continuous risk monitoring

---

## Risk Monitoring Plan

### Monthly Risk Monitoring

**Critical Risks (Monthly Review):**
1. **Idus validation study progress** - Track milestones, identify blockers
2. **Key person availability** - Monitor absences, backup readiness
3. **System availability** - Track downtime incidents, uptime %
4. **Integration health** - Monitor SAP status, escalate failures

**Dashboard Metrics:**
- Validation study completion % (target: on track)
- System uptime % (target: 99%+)
- Key person single points of failure (target: eliminate)
- Backup capacity assessment status

---

### Quarterly Risk Assessment

**Review Quarterly:**
- Threat landscape changes
- Risk likelihood and impact updates
- New emerging risks
- Mitigation effectiveness
- Budget impact from risks

**Reporting:**
- Executive summary to management
- Risk heat map updates
- Mitigation progress tracking
- Budget impact analysis

---

### Annual Risk Portfolio Review

- Comprehensive risk register update
- Validate risk scoring methodology
- Benchmark against industry standards
- Update mitigation strategies
- Multi-year risk trend analysis

---

## Contingency Planning

### If Idus System Becomes Unavailable

**Immediate Actions:**
1. Activate manual paper-based work order process
2. Emergency vendor support engagement
3. Daily coordination meetings for 1,800 monthly tickets
4. Priority-based maintenance only (emergency + critical)
5. Communication plan to all stakeholders

**Backup Procedures:**
- Manual work order forms (pre-printed templates)
- Spreadsheet tracking (temporary)
- Daily super user coordination meetings
- Production line priority assessments

---

### If Flexite System Becomes Unavailable

**Immediate Actions:**
1. Activate manual incident reporting forms
2. Emergency vendor support engagement
3. Manual government reporting backup (e-tjänster direct entry)
4. Safety coordinator daily briefings
5. Arbetsmiljöverket compliance notification if extended

**Backup Procedures:**
- Paper incident report forms
- Manual log maintenance
- Direct government portal entry
- Weekly safety meeting escalations

---

### If Super User Becomes Unavailable

**Idus:**
1. Activate backup super user (requires training first - RISK!)
2. Vendor support for critical issues
3. Defer non-critical reporting
4. Simplified user support (basic issues only)
5. Elena handles user account maintenance only

**Flexite:**
1. Activate backup H&S team member (requires training - RISK!)
2. Vendor support for compliance reporting
3. Manual government reporting continues (must maintain 144/year)
4. Preventive analysis deferred

**Agda/Visma:**
1. Activate backup HR team member (new hire)
2. Vendor support for payroll issues
3. Focus on critical payroll processing
4. Defer non-critical HR functions

---

### If Idus Validation Study Fails to Provide Clear Answer

**Fallback Plan:**
1. Extend validation period (additional 2 months)
2. Engage external CMMS consultant for objective assessment
3. Request additional budget for comprehensive proof-of-concept
4. If still unclear: Default to maintaining status quo with targeted improvements
5. Schedule re-evaluation in 12 months with better data

---

### If Budget Overrun Detected (Idus)

**Immediate Actions:**
1. Spending freeze for non-critical work orders
2. Management escalation and review
3. Root cause analysis (why budget exceeded)
4. Corrective action plan development
5. Enhanced budget monitoring (weekly reviews)

**Prevention:** Implement reporting module or interim manual tracking

---

## Key Insights & Recommendations

### 🎯 Strategic Risk Insights

**1. Investment Decision Risk Dominates Portfolio**
- Single largest financial exposure (800K+ SEK)
- 97% of waste estimate unvalidated
- Wrong decision has 5-10 year impact
- **Action:** Invest 100K SEK in validation study to protect 800K decision

**2. Risk Concentration in Idus (56% of all risks)**
- But risk assessment itself has LOW CONFIDENCE (single source data)
- Many Idus risks contingent on unvalidated waste estimates
- Validation study will clarify actual risk landscape

**3. Cross-System Pattern: Single Points of Failure**
- Idus (Tom), Flexite (Jan-Eric): No backup capacity
- Agda/Visma (Helena): Backup exists but needs assessment
- **Action:** Immediate cross-training and documentation program

**4. Data Quality as Foundation Risk**
- Poor Idus data undermines all analytics and decision-making
- Clean data required whether upgrading OR replacing
- **Action:** Data cleansing project regardless of Idus decision

**5. Hidden Costs Create Unquantified Risks**
- Shift leader Excel gatekeeping (50-100K+ SEK/year estimated)
- Information delays and potential data loss
- Inconsistent filtering criteria
- **Action:** Investigate and quantify as part of validation study

---

### ✅ Recommended Risk Mitigation Priorities

**CRITICAL PRIORITY (Week 1):**
1. ✅ Approve Idus validation study (100K SEK) - Protects 800K decision
2. ✅ Launch Agda/Visma self-service campaign (30-70K SEK) - Mitigates 42-83K/year waste
3. ✅ Initiate cross-training program - Reduces single points of failure
4. ✅ Begin backup procedure documentation - Business continuity

**HIGH PRIORITY (Months 1-4):**
5. Execute Idus validation study comprehensively
6. Complete Agda/Visma training rollout
7. Plan Flexite government integration
8. Assess Agda/Visma backup capacity depth
9. Initiate data quality improvement program

**MEDIUM PRIORITY (Months 5-12):**
10. Execute Idus decision (based on validation results)
11. Implement Flexite integrations
12. Address identified compliance gaps
13. Optimize user adoption across all systems
14. Establish continuous risk monitoring

---

### ⚠️ Critical Success Factors for Risk Management

**DO:**
✅ Prioritize validation before major commitments
✅ Address single points of failure urgently
✅ Execute quick wins while studying complex risks
✅ Maintain high data quality standards
✅ Monitor risks continuously with clear metrics

**DON'T:**
❌ Commit 800K+ SEK without validation study
❌ Accept unquantified costs (shift leader Excel)
❌ Ignore people risks (key person dependencies)
❌ Defer data quality improvements
❌ Let unvalidated large numbers drive decisions

---

## Document Version Control

**Version:** 1.0
**Last Updated:** January 2026
**Next Review:** After Idus validation study (Month 4-5) and quarterly risk assessment

**Change Log:**
- v1.0 - Initial comprehensive risk assessment
- Pending: v1.1 after Idus validation study results
- Pending: v1.2 after Ascendo assessment integration
- Pending: v2.0 after risk mitigation execution (Month 12)

---

**📌 Quick Reference: Top 3 Actions**

1. **⚠️ URGENT:** Approve Idus validation study (100K SEK to protect 800K decision)
2. **✅ EXECUTE:** Launch Agda/Visma self-service campaign (immediate ROI, validated)
3. **🔴 CRITICAL:** Initiate cross-training program (eliminate single points of failure)

**🚨 Remember:** The highest risk is not system failure - it's making a major investment decision (800K+ SEK) based on unvalidated single-source assessment. Invest in validation first.

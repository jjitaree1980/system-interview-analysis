# IT Systems Portfolio Assessment
## Detailed Analysis Report

---

**Assessment Period:** December 2025 - January 2026  
**Assessment Date:** January 2026  
**Version:** 1.0 - Final Report  
**Status:** Complete - All 4 Systems Assessed

---

## EXECUTIVE ORIENTATION

### Purpose of This Document

This detailed report provides the complete analysis behind the executive summary recommendations. It documents:

- ✓ **Evidence Base:** Full interview findings and data analysis for all 4 systems
- ✓ **Hidden Workflows:** Discovery of Excel-based shadow processes creating waste
- ✓ **Integration Gaps:** Specific breakpoints between systems and manual processes
- ✓ **Validation Needs:** Why Idus investment requires deeper investigation
- ✓ **Cost Analysis:** Detailed waste calculations and ROI projections
- ✓ **Risk Assessment:** Confidence levels and uncertainty factors

### How to Use This Report

**FOR EXECUTIVES:** Read Sections 1-2 for context, then focus on Section 7 (Cross-System Analysis) and Section 8 (Risk Assessment)

**FOR OPERATIONAL MANAGERS:** Review system-specific sections (3-6) relevant to your area

**FOR PROJECT LEADS:** Focus on Section 8 (Risk Assessment) and system-specific recommendations in sections 3-6

**FOR VALIDATION STUDY:** Section 3.9 and Appendix D provide detailed investigation protocol

---

## TABLE OF CONTENTS

### Part I: Foundation
1. Introduction & Context
2. Assessment Methodology

### Part II: Individual System Analysis
3. System Analysis: Idus (CMMS)
4. System Analysis: Agda/Visma (HR & Payroll)
5. System Analysis: Flexite (Safety Management)
6. System Analysis: Ascendo (Invoice Processing)

### Part III: Strategic Analysis
7. Cross-System Analysis
8. Risk Assessment

### Part IV: Supporting Materials
9. Appendices

---

# PART I: FOUNDATION

## 1. Introduction & Context

### 1.1 Why This Assessment Was Conducted

**Business Context:**
Kubal  operates four critical business systems supporting daily operations across maintenance, HR, safety compliance, and financial processing. Management requested a comprehensive assessment to:

1. Evaluate current system performance
2. Identify improvement opportunities
3. Inform investment decisions
4. Understand integration health

**Trigger Event:**
This assessment was initiated following proposals for significant system upgrades, particularly for the Idus maintenance management system.

### 1.2 Systems in Scope

| System | Primary Function | Criticality | Users |
|--------|-----------------|-------------|-------|
| **Idus** | CMMS - Maintenance Management | ⭐⭐ Critical | ~15-30 staff |
| **Agda/Visma** | HR, Payroll & Time Management | ⭐⭐⭐⭐ Critical | All employees |
| **Flexite** | Safety Incident Management | ⭐⭐⭐ Important | All employees |
| **Ascendo** | Invoice Processing & OCR | ⭐⭐⭐⭐⭐ Critical | 3-4 economy staff |

### 1.3 Assessment Timeline

```
December 2025          │  System selection & interview planning
Week 1-2 (Dec)         │  IDUS ASSESSMENT
Week 3 (Dec)           │  AGDA/VISMA ASSESSMENT
Week 4 (Dec)           │  FLEXITE ASSESSMENT
Week 1-2 (Jan 2026)    │  ASCENDO ASSESSMENT
Week 3 (Jan)           │  CROSS-SYSTEM ANALYSIS
Week 4 (Jan)           │  FINAL REPORTING
```

---

## 2. Assessment Methodology

### 2.1 Interview Process

Each system assessment included structured interviews with super users:

| System | Interviewee | Duration | Format |
|--------|-------------|----------|--------|
| Idus | Tom | 120 min | Face-to-face interview |
| Agda/Visma | Helena | 90 min | Face-to-face interview |
| Flexite | Jan-Eric | 90 min | Face-to-face interview |
| Ascendo | Rhodora, Inna | N/A | Questionnaire |

### 2.2 Analysis Framework

Each system evaluated across 8 dimensions:
1. Functional Performance
2. User Satisfaction
3. Integration & Data Flow
4. Efficiency & Waste
5. Technical Health
6. Capabilities & Gaps
7. Vendor & Support
8. Future Readiness

### 2.3 Waste Quantification Method

**Formula:**
```
Annual Waste = (Hours per Occurrence) × (Occurrences/Year) × (Hourly Cost)
```

**Standard Hourly Rates:**
- Shift Leader: 350 SEK
- Technician: 300 SEK
- HR/Admin: 300 SEK
- Economy Staff: 350 SEK
- Safety Manager: 400 SEK

### 2.4 Confidence Levels

- 🟢 **High:** Multiple sources, measured data
- 🟡 **Medium:** Single reliable source, reasonable estimates
- 🔴 **Low:** Single source with potential bias

# PART II: INDIVIDUAL SYSTEM ANALYSIS

## 3. System Analysis: Idus (CMMS)

### 3.1 System Overview

**System Type:** Computerized Maintenance Management System (CMMS)  
**Vendor:** Idus (Swedish provider)  
**Criticality:** ⭐⭐ Critical  
**Status:** 🔴 **REQUIRES INVESTIGATION**

**User Base:** ~15-30 staff (technicians, shift leaders)  
**Super User:** Tom (Functional Technician)

### 3.2 Key Findings Summary

| Dimension | Finding | Confidence |
|-----------|---------|------------|
| Functional Performance | ⚠️ Adequate but integration-dependent | 🔴 Low |
| SAP Integration | ❌ Reported broken | 🟡 Medium |
| User Adoption | ❓ Tom-centric, Excel workarounds | 🔴 Low |
| Bias Risk | 🚩 HIGH - Single source | 🟢 High |

**CRITICAL:** Assessment based almost entirely on Tom's input. Validation required.

### 3.3 Current Workflow

```
IDUS WORKFLOW (AS DESCRIBED)
═══════════════════════════════════════════════

1. FELANMÄLAN (FAULT REPORTING)
   Shift leader identifies issue
         ↓
   [CURRENTLY: Excel tracking] ← Hidden workflow
         ↓
   Tom enters into Idus ← Bottleneck
         ↓
   Work order created

2. WORK ORDER PROCESSING
   Tom assigns to technician
         ↓
   Technician completes work
         ↓
   [CURRENTLY: Paper/verbal report] ← Mobile limitation
         ↓
   Tom updates Idus
         ↓
   [MANUAL: Export to SAP] ← Integration failure
```

### 3.4 Critical Issues

#### ❌ **ISSUE #1: SAP Integration Failure**

**Reported Impact:** Significant annual waste claimed (requires validation)

**⚠️ VALIDATION REQUIRED:**
- Is integration truly broken or misconfigured?
- Can Rusal IT team and Idus confirm the status?
- What would repair actually cost?
- What is the actual scope of manual workarounds?

**Calculable Waste Components:**
```
Manual spare parts updates: 50,100 SEK
Manual labor tracking: 75,000 SEK
Rework/reconciliation: 22,050 SEK
Cost tracking delays: 126,000 SEK

CALCULABLE SUBTOTAL: 273,150 SEK

Additional impacts claimed but not quantified:
• Productivity drain from workarounds
• Delayed decision-making from data gaps
• Risk of data inconsistencies
```

**🚨 CONFIDENCE: VERY LOW - Full scope requires validation study**

#### ❌ **ISSUE #2: Limited Mobile Access**

**Reported Impact:** Estimated 375K-665K SEK/year (high uncertainty, requires validation with actual technicians)

**⚠️ VALIDATION REQUIRED:**
- Do technicians actually want mobile access?
- Would mobile truly change behavior?
- Is this system limitation or licensing issue?

### 3.9 🚨 CRITICAL DISCOVERY: Excel Shadow Workflow

**The Hidden Process:**

```
THE ACTUAL WORKFLOW (DISCOVERED)
═══════════════════════════════════════════════

ISSUE IDENTIFICATION
   Technician/operator identifies fault
            ↓
   [EXCEL: Shift leader logs in tracking sheet]
            ↓
   Verbal/email to Tom
            ↓
   Tom creates work order in Idus
            ↓
   [RESULT: Data exists in Excel + Idus]

WHY EXCEL EXISTS:
✗ Shift leaders don't have Idus access
✗ Shift leaders need real-time tracking
✗ Waiting for Tom approval creates bottleneck
✗ Excel used for shift handover reporting
```

**Estimated Excel Shadow Waste:**

```
Shift leader Excel tracking: 383,250 SEK
Double data entry: 76,650 SEK
Delay-induced waste: 72,800 SEK
Communication overhead: 54,600 SEK
Shift handover inefficiency: 63,875 SEK
Information silos: 36,400 SEK

TOTAL EXCEL WASTE: 687,575 SEK/year
```

**🟡 CONFIDENCE: MEDIUM** (Requires shift leader validation)

**Critical Questions:**

1. Why don't shift leaders have Idus access?
2. Would they USE direct access if provided?
3. Is solution "mobile upgrade" or "desktop access + training"?

**Connection to Flexite Success:**

The same shift leaders who use Excel for Idus use Flexite directly for safety (100% compliance). This proves:
- Users CAN adopt systems when access provided
- Excel is workaround, not preference
- Problem might be ACCESS, not features

### 3.10 Waste Summary - Idus

| Waste Category | Annual Cost (SEK) | Confidence |
|----------------|------------------|------------|
| SAP Integration Failure | 335,550 - 1,550,000 | 🔴 Low |
| Mobile Access Limitation | 665,000 | 🔴 Low |
| Excel Shadow Workflow | 687,575 | 🟡 Medium |

**Total Range:** 1.69M - 2.90M SEK/year (UNVALIDATED)

**Critical Observation:** Huge variance indicates very low confidence.

### 3.11 Recommendation: VALIDATE BEFORE INVESTING

**Recommended Approach:**

```
PHASE 1: VALIDATION STUDY 
├─ Interview 8-10 users beyond Tom
├─ Technical SAP integration assessment
├─ Excel workflow deep-dive
├─ Market benchmark (modern CMMS)
└─ Pilot test: 2 shift leaders with Idus access

PHASE 2: IMPLEMENT BASED ON DATA
├─ Path A: Full upgrade (if validated)
├─ Path B: Targeted improvements (200-400K)
└─ Path C: Alternative solution (TBD)
```

---

## 4. System Analysis: Agda/Visma (HR & Payroll)

### 4.1 System Overview

**System Type:** HR Information System & Payroll  
**Vendor:** Visma (Nordic leader)  
**Criticality:** ⭐⭐⭐⭐ Critical  
**Status:** 🟢 **STRONG PERFORMANCE**

**User Base:** All employees (~60-80)  
**Super User:** Helena (HR Administrator)

### 4.2 Key Findings Summary

| Dimension | Finding | Confidence |
|-----------|---------|------------|
| Functional Performance | ✅ Excellent - meets all requirements | 🟢 High |
| User Satisfaction | ✅ High | 🟢 High |
| Compliance | ✅ Perfect Swedish compliance | 🟢 High |
| Feature Utilization | ⚠️ Underutilized (training gap) | 🟢 High |

### 4.3 Strengths

- ✅ Perfect payroll compliance (Swedish regulations)
- ✅ Strong vendor relationship (Visma)
- ✅ Minimal IT support required (never)
- ✅ Comprehensive feature set

### 4.4 Main Challenge: Feature Underutilization

**Description:** Employees not fully using self-service features:
- Shift preference settings
- Digital payslip access
- Schedule swap requests

**Impact:** Creates unnecessary work for Helena

**Waste Calculation:**

```
**Estimated Waste from Underutilization:**
- Helena's time on routine queries that could be self-service
- Manual processes that automated features could handle
- Employee productivity losses waiting for HR responses

**Total Estimated: 75,000 SEK/year (per Helena)**
```

**🟢 CONFIDENCE: HIGH** (Helena's direct observation)

### 4.5 Opportunity: Training Campaign

**Investment:** 25,000 SEK

**Program:**
- Employee training sessions (30-min groups)
- Quick reference guides
- Champion program

**Expected ROI:**
- Annual savings: 75,000 SEK
- Payback: 4 months
- 3-year benefit: ~200,000 SEK

**Risk:** 🟢 LOW

### 4.6 Recommendation: SUPPORT USER ADOPTION

```
IMMEDIATE (Q1 2026):
✅ Launch Training Campaign (25K)
   → Execute immediately
   → Clear ROI, low risk
   → Include backup user training

VALIDATION (Q1 2026):
⚠️ Interview Ekonomi Team
   → Understand Agda → SAP flow
   → Identify any manual processes
```

---

## 5. System Analysis: Flexite (Safety Management)

### 5.1 System Overview

**System Type:** Safety Incident Management  
**Vendor:** Flexite  
**Criticality:** ⭐⭐⭐ Important  
**Status:** 🟡 **ADEQUATE - MEETS COMPLIANCE NEEDS**

**User Base:** All employees (incident reporting)  
**Super User:** Jan-Eric (Safety Manager)

### 5.2 Key Findings Summary

| Dimension | Finding | Confidence |
|-----------|---------|------------|
| Functional Performance | ✅ Meets compliance requirements | 🟢 High |
| User Satisfaction | ✅ High - 100% compliance | 🟢 High |
| Analytics Capability | ⚠️ Limited (by design) | 🟢 High |
| System Type | 📊 Data Recording tool | 🟢 High |
| User Adoption | ✅ 100% compliance achieved | 🟢 High |

### 5.3 Strengths

#### ✅ **Perfect User Adoption (100%)**

Jan-Eric achieved **100% compliance** with incident reporting. This is remarkable because:
- Same shift leaders use Flexite directly
- Same shift leaders use Excel for Idus
- Proves users CAN adopt systems with proper access

**What This Proves:**
- User adoption is about access + training + leadership
- Not about system complexity or user capability
- Jan-Eric's change management is best practice

### 5.4 System Characteristics

**Flexite is a Compliance Recording System:**

It captures incident data but does NOT provide:
- Advanced trend analysis
- Predictive risk modeling
- Automated insights
- AI-driven analytics
- Data visualization dashboards

**Is This a Problem?**

**It could be a problem in future** Even the user performs excellent safety management through manual analysis. The question is whether automated analytics would improve outcomes or just add features.

**Manual Analysis Time:**

```
Jan-Eric's Analysis Work
─────────────────────────────────────────
Monthly trend analysis: 38,400 SEK
Quarterly management reporting: 9,600 SEK
Ad-hoc analysis: 8,000 SEK

TOTAL: 56,000 SEK/year
```

**Note:** This is part of Jan-Eric's core role, not pure waste.

### 5.5 Challenge: Government Reporting

**Manual Process:**
- Export from Flexite
- Format for Arbetsmiljöverket
- Review and submit

**Waste:**

```
Government Reporting Time
─────────────────────────────────────────
Quarterly reports: 6,400 SEK
Annual reports: 3,200 SEK

TOTAL: 9,600 SEK/year
```

**🟢 CONFIDENCE: HIGH**

### 5.6 Comparison to Idus (Critical Learning)

| Dimension | Flexite | Idus |
|-----------|---------|------|
| User Adoption | ✅ 100% | ❓ Tom-centric |
| Shift Leader Usage | ✅ Direct access | ❌ Excel workarounds |
| System Access | ✅ All users | ❌ Limited to few |

**CRITICAL INSIGHT:**

Same shift leaders who successfully use Flexite maintain Excel for Idus. This strongly suggests:
1. Problem is ACCESS, not capability
2. User adoption is about leadership + access
3. System limitations may be overstated

**Implication for Idus:**
Before major system upgrade, test whether desktop access + training eliminates Excel (potentially much lower cost solution).

### 5.7 Waste Summary - Flexite

| Waste Category | Annual Cost | Confidence |
|----------------|------------|------------|
| Manual Analysis | 56,000 SEK | 🟡 Medium |
| Government Reporting | 9,600 SEK | 🟢 High |

**Total:** ~65,600 SEK/year

**Context:** Not all waste is avoidable. Jan-Eric's analysis is valuable expertise.

### 5.8 Recommendation: MAINTAIN + OPTIONAL ENHANCEMENT

```
IMMEDIATE:
✅ MAINTAIN current approach
   → System performing well
   → 100% compliance achieved

SHORT-TERM (Q2):
💡 Investigate Government Reporting Automation
   → Contact Flexite vendor
   → If cost ≤20K/year, consider
   → If >20K, optimize Excel template

ONGOING:
✓ Train backup safety coordinator
✓ Document Jan-Eric's best practices
```

---

## 6. System Analysis: Ascendo (Invoice Processing)

### 6.1 System Overview

**System Type:** Invoice Management & OCR  
**Vendor:** Ascendo  
**Criticality:** ⭐⭐⭐⭐⭐ Mission Critical  
**Status:** 🟢 **EXCELLENT - REFERENCE STANDARD**

**User Base:** 2-3 economy staff  
**Super Users:** Rhodora, Ksenia, Inna

### 6.2 Key Findings Summary

| Dimension | Finding | Confidence |
|-----------|---------|------------|
| Functional Performance | ⭐⭐⭐⭐⭐ Excellent | 🟢 High |
| User Satisfaction | ⭐⭐⭐⭐⭐ Extremely high | 🟢 High |
| OCR Accuracy | ✅ 95-100% | 🟢 High |
| SAP Integration | ⭐⭐⭐⭐⭐ Perfect | 🟢 High |
| System Adoption | ✅ 100% | 🟢 High |

### 6.3 Perfect SAP Integration

```
ASCENDO WORKFLOW (BEST-IN-CLASS)
═══════════════════════════════════════════════

Invoice arrives
      ↓
[AUTO: Ascendo captures] ✓ No manual entry
      ↓
[AUTO: OCR extracts data] ✓ 95-100% accuracy
      ↓
[AUTO: Route to approver] ✓ Smart routing
      ↓
Approval
      ↓
[AUTO: Post to SAP immediately] ✓ Real-time
      ↓
[AUTO: Schedule payment] ✓ Full automation
      ↓
[RESULT: Zero reconciliation issues]
```

**Why This Matters:**

Ascendo proves SAP integration IS achievable at Kubal. Compare to Idus's broken integration - if Ascendo can do it, why can't Idus?  
According to Tom, upgrading Idus to a newer version should resolve the SAP integration issues.

### 6.4 Value Created

**Waste Eliminated by Ascendo:**

```
Manual Invoice Processing (if done manually)
─────────────────────────────────────────
Manual data entry: 131,250 SEK
Error correction: 13,125 SEK
SAP posting: 157,500 SEK
Reconciliation: 84,000 SEK

TOTAL VALUE: ~385,875 SEK/year
```

**🟢 CONFIDENCE: HIGH**

### 6.5 No Improvements Needed

Users reported **no significant pain points**. System performing excellently.

### 6.6 Recommendation: MAINTAIN & PROTECT

```
IMMEDIATE:
⭐ MAINTAIN current approach
   → NO changes needed
   → Protect from unnecessary "enhancements"

STRATEGIC:
🎯 USE AS BENCHMARK
   → Reference for SAP integration quality
   → Model for other system improvements
   → Reference standard for vendor delivery

RISK MITIGATION:
✓ Cross-train economy team
✓ Monitor SAP integration health
✓ Maintain vendor relationship
```

# PART III: STRATEGIC ANALYSIS

## 7. Cross-System Analysis

### 7.1 Common Themes

#### 🔍 **Theme 1: Integration Quality Determines Value**

**Pattern:**
- ⭐ **Ascendo:** Perfect integration → Zero waste
- 🟢 **Agda/Visma:** Good integration → Minimal waste
- ❌ **Idus:** Broken integration → Massive waste
- ⚪ **Flexite:** No integration (by design) → Adequate for current needs, consider analytics upgrade if scaling

**Insight:** System features matter less than integration. Feature-rich system with broken integration creates more waste than simple system with perfect integration.

#### 🔍 **Theme 2: User Adoption Requires Access + Training + Leadership**

**Evidence:**

| System | Access | Training | Leadership | Result |
|--------|--------|----------|------------|--------|
| Flexite | ✅ All | ✅ Good | ⭐ Jan-Eric | 100% |
| Ascendo | ✅ All | ✅ Good | ✅ Strong | 100% |
| Agda | ✅ All | ⚠️ Gap | ✅ Helena | Mixed |
| Idus | ❌ Limited | ❓ | ❓ Tom gatekeeper | Excel workarounds |

**Critical Discovery:** Same shift leaders who use Flexite (100%) maintain Excel for Idus. This proves problem is ACCESS, not capability.

#### 🔍 **Theme 3: Not All Manual Processes Are Waste**

**Examples:**
- Agda/Visma payroll review = intentional control (valuable)
- Flexite manual analysis = expertise application (valuable)
- Idus double data entry = workaround (waste)

**Principle:** Distinguish wasteful manual from valuable manual work.

### 7.2 The Shadow Workflow Discovery

```
HIDDEN EXCEL INTEGRATION LAYER
═══════════════════════════════════════════════

                ┌─────────────┐
                │  OPERATOR   │
                └──────┬──────┘
                       │
                       ↓
        ┌──────────────────────────────┐
        │ SHIFT LEADER                 │
        │ [EXCEL TRACKING]    ← HIDDEN │
        └──┬───────────────────────┬───┘
           │                       │
           ↓                       ↓
    ┌─────────────┐         ┌─────────────┐
    │  TOM (Idus) │         │ FLEXITE     │
    │             │         │ (Direct!)   │
    └─────────────┘         └─────────────┘

KEY FINDING:
• Shift leaders use EXCEL for Idus (no access)
• Shift leaders use FLEXITE directly (have access)
• SAME PEOPLE = Access barrier, not capability
```

**Estimated Hidden Waste:**

```
Excel Shadow Workflow Costs
────────────────────────────────────────
Idus-related Excel: 383,250 SEK
Agda shift planning Excel: 182,000 SEK
Communication overhead: 54,600 SEK
Information silos: 36,400 SEK

TOTAL: ~656,250 SEK/year
```

**🟡 CONFIDENCE: MEDIUM** (Requires shift leader validation)

**Investigation Priority:** 🔥 HIGH

### 7.3 Integration Landscape

```
KUBAL SYSTEMS INTEGRATION MAP
═══════════════════════════════════════════════

                    ┌──────────────┐
                    │   SAP ERP    │
                    └───────┬──────┘
                            │
            ┌───────────────┼───────────────┐
            │               │               │
     ⭐ PERFECT      ❓ UNCLEAR       ❌ BROKEN
            │               │               │
            ↓               ↓               ↓
    ┌──────────┐    ┌──────────┐    ┌──────────┐
    │ ASCENDO  │    │  AGDA    │    │   IDUS   │
    └──────────┘    └──────────┘    └──────────┘

    Reference        Validate        Critical
    Standard        w/Ekonomi        Priority


            ┌──────────────┐
            │   FLEXITE    │
            └──────────────┘
                   │
                   ↓
            ⚪ STANDALONE
               (By Design)


    EXCEL SHADOW LAYER (DISCOVERED)
    ════════════════════════════════
    Shift Leaders maintain Excel sheets
    🚨 UNACCOUNTED: ~656K SEK/year
```

### 7.4 Comparative Performance

**System Scorecard:**

| System | Core Function | Integration | User Adoption | Waste/Year |
|--------|--------------|-------------|---------------|------------|
| **Ascendo** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | **-386K** (value) |
| **Agda** | ⭐⭐⭐⭐⭐ | ❓ | ⭐⭐⭐ | 75K |
| **Flexite** | ⭐⭐⭐⭐ | N/A | ⭐⭐⭐⭐⭐ | 66K |
| **Idus** | ❓ | ❌ | ❓ | 1.69M-2.90M |

**Waste per User:**

| System | Users | Waste/User |
|--------|-------|------------|
| Ascendo | 2-3 | **-128K to -193K** (value created) |
| Agda | 60-80 | 938 - 1,250 |
| Flexite | ~80 | ~820 |
| Idus | 15-20 | 84,500 - 193,333 |

### 7.5 Portfolio Health

```
OVERALL ASSESSMENT: 🟢 GOOD
(3 of 4 systems performing well)

┌─────────────────────────────────────┐
│ ASCENDO    [████████████] 100% ⭐⭐⭐⭐⭐│
│ AGDA       [██████████──]  80% ⭐⭐⭐⭐ │
│ FLEXITE    [████████────]  75% ⭐⭐⭐⭐ │
│ IDUS       [██──────────]  25% ❓    │
└─────────────────────────────────────┘

CONFIDENCE LEVELS:
🟢 HIGH    [███] Ascendo, Agda
🟡 MEDIUM  [██─] Flexite
🔴 LOW     [█──] Idus ← VALIDATION NEEDED
```

---

## 8. Risk Assessment

### 8.1 Critical Risks

#### 🔴 **RISK #1: Idus Investment Without Validation**

**Description:** Committing to major Idus improvements based solely on Tom's input without validation

**Impact:** 🔴 VERY HIGH
- Significant investment with poor ROI potential
- Continued waste if root causes not addressed
- Continued waste if root causes not addressed
- Opportunity cost

**Probability:** 🟡 MEDIUM-HIGH (without validation)

**Mitigation:**
✅ MANDATORY 95K validation study (need to validate cost)
- Interview 8-10 users beyond Tom
- Validate Excel workflows
- Test SAP integration
- Compare alternatives
- Decision at Month 4

#### 🟡 **RISK #2: Excel Shadow Workflows**

**Description:** Critical data in personal Excel sheets

**Impact:** 🟡 MEDIUM
- Knowledge loss during transitions
- Data inconsistencies
- Continued waste (~656K/year)

**Mitigation:**
✅ Investigate during validation study
- Document Excel patterns
- Test system access alternative
- Formalize if Excel remains necessary

#### 🟡 **RISK #3: Key Person Dependencies**

| System | Key Person | Impact if Unavailable |
|--------|-----------|---------------------|
| Idus | Tom | Work orders can't be created |
| Agda | Helena | HR processes slow down |
| Flexite | Jan-Eric | Quality drops |

**Mitigation:**
- Train backup users
- Document processes
- Expand user base (especially Idus)

---

# PART IV: SUPPORTING MATERIALS

## 9. Appendices

### Appendix A: Key Contacts

**System Owners:**
- Idus: Tom (Functional Technician)
- Agda/Visma: Helena (HR Administrator)
- Flexite: Jan-Eric (Safety Manager)
- Ascendo: Rhodora, Ksenia, Inna (Economy Team)

**Management:**
- Project Sponsor: [Name]
- IT Manager: [Name]
- Finance/CFO: [Name]

### Appendix B: Glossary

**CMMS:** Computerized Maintenance Management System  
**Felanmälan:** Swedish term for fault/error reporting  
**OCR:** Optical Character Recognition  
**SAP:** Enterprise Resource Planning system  
**Arbetsmiljöverket:** Swedish Work Environment Authority

### Appendix C: Document History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | Jan 2026 | Initial comprehensive report | Jitaree |

---

## THE BOTTOM LINE

**Portfolio Health:** GOOD (3 of 4 systems performing well)

**Critical Decision:** Idus investment approach
- Proposed: Major immediate investment
- Issue: Single perspective, unvalidated
- Recommended: 95K validation study first

**Quick Wins Available:**
- ✅ Agda training: 25K → 75K annual savings
- ⚠️ Flexite reporting: Optional, low priority
- ⏸️ Idus: Validate before committing

**Hidden Opportunity:**
- Excel shadow workflows: ~656K waste
- May be solvable with access + training (~50K)
- Much cheaper than major system upgrade

**Best Practice Reference:**
- Ascendo proves excellence is achievable
- Perfect SAP integration IS possible
- Use as internal benchmark

**Recommended Strategy:**
- Execute validated wins immediately (Agda)
- Validate uncertain high-cost proposals (Idus)
- Make data-driven decisions
- Match investments to actual needs

**Timeline:**
- Month 1-3: Validation + Agda training
- Month 4: Idus decision
- Month 5+: Implement chosen path

---

**Document Status:** Ready for Management Review  
**Next Review:** Month 4 (April 2026)  
**Version:** 1.0 Final

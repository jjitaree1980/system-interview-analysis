# IT Systems Assessment - Common Themes Matrix

**Assessment Date:** January 2026  
**Prepared by:** IT Systems Assessment Team  
**Status:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ✓  **COMPLETE**

---

## Executive Summary

**Portfolio-wide analysis of four business-critical systems reveals stark performance contrast:**   
Ascendo (invoice processing) achieves best-in-class automation with zero waste, while integration failures drive 4.87M SEK annual inefficiency across the other three systems.   
**Critical discovery:** Both Idus and Flexite have hidden shift leader Excel gatekeeping layers creating unquantified waste through shadow systems and manual workflows.   
**Key insight:** Ascendo proves seamless SAP integration IS achievable at Kubal - its success exposes that Idus's 1.55M SEK broken integration is a solvable problem, not inherent limitation. Investment strategy: replicate Ascendo's success pattern (100% adoption, zero manual SAP entry, 95-100% accuracy) across struggling systems.

---

## 1. SYSTEM STATUS OVERVIEW

|  | **Idus** | **Agda/Visma** | **Flexite** | **Ascendo** |
|---|---|---|---|---|
| **Status** | ✓ Complete | ✓ Complete | ✓ Complete | ✓ Complete |
| **Primary Function** | CMMS / Maintenance | HR & Payroll | Incident Management | Invoice / AP Automation |
| **Super User** | Functional Technician | HR Manager (7 yrs) | H&S Manager (8 yrs) | AP Accountant (3+ yrs), AP Manager (3+ yrs) |
| **Monthly Volume** | 1,800 work orders | All employees | 120-140 incidents | 500-1,000 invoices |
| **Criticality** | 9/10 | 10/10 | 9/10 | **10/10** |
| **Annual Waste** | 4.73M SEK | 75K SEK | 60-90K SEK | **~0 SEK** ✅ |
| **Assessment Confidence** | 🔴 LOW - Single source, poor data hygiene | 🟢 HIGH - By stakeholder | 🟢 HIGH - Note: users adjust exported data | 🟢 HIGH - Dual user validation |

---

## 2. CRITICAL CROSS-SYSTEM THEMES

### Theme: Integration Gaps Creating Manual Workload
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ✗ **SUCCESS**

**Manifestation by System:**
- **Idus:** Broken SAP inventory integration (1.55M SEK/year waste) + no BI/reporting module (1.43M SEK/year waste)
- **Agda/Visma:** Intentional manual banking/accounting processes (23K SEK/year) - by design for Ekonomi team verification control
- **Flexite:** No government system (e-tjänster) integration requiring 144 manual reports/year (60-90K SEK/year waste)
- **Ascendo:** ✅ **ZERO integration gaps** - Fully automated SAP integration with zero manual data entry, automatic posting, automatic payment order creation. Saves 900-1,800 hours annually.

**Strategic Impact:** Ascendo PROVES seamless SAP integration is achievable at Kubal. Its zero-waste success exposes that Idus's 1.55M SEK broken integration is NOT an inherent technical limitation but a solvable problem. Integration gaps account for ~65% of identified waste (3M+ SEK of 4.9M), but Ascendo demonstrates this waste is entirely eliminable.   


---

### Theme: Key Person Dependencies and Backup Capacity
**Found in:** Idus ✓ | Agda/Visma ⚠️ | Flexite ✓ | Ascendo ✗ **BACKUP EXISTS**

**Manifestation by System:**
- **Idus:** Single functional technician manages all system administration with 30 users dependent on one expert
- **Agda/Visma:** HR department has two people working with the system; primary super user has 7 years deep expertise - backup capacity exists and the expertise is clear
- **Flexite:** Single Health & Safety Manager (8 years system experience) manages compliance-critical safety system - backup capacity unclear
- **Ascendo:** ✅ Two super users (Rhodora + Inna, both 3+ yrs experience) with clear role separation: Rhodora processes invoices, Inna provides backup/oversight. Plus Peter handles payments. Proper team coverage.

**Strategic Impact:** Only Ascendo and Agda/Visma have documented backup capacity. Idus and Flexite remain at risk.  
**Key learning from Ascendo:** Team-based ownership (processor + backup + oversight) provides resilience for mission-critical 10/10 systems. This model should be replicated for Idus and Flexite.

---

### Theme: Strong Core Functionality, Missing Enhancements
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ?

**Manifestation by System:**
- **Idus:** Core CMMS manages 1,800 monthly tickets reliably, but lacks reporting/analytics and has broken SAP integration
- **Agda/Visma:** Payroll/HR core rated 10/10 critical with zero failures, but missing self-service adoption and production integration
- **Flexite:** Incident management core excellent (100% user compliance, 9/10 critical), but zero system integrations
- **Ascendo:** Invoicing system rated 10/10 critical with zero failures, with 500-1,000 monthly invoices.

**Strategic Impact:** Pattern suggests "build on strength" investment strategy rather than replacement. All three super users recommend investing in existing platforms - enhancement ROI likely exceeds replacement costs.  
Risk: Idus assessment may be biased (single source validation required).

---

### Theme: User Adoption Challenges and Manual Workarounds
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ✗ **100% CLEAN ADOPTION**

**Manifestation by System:**
- **Idus:** Multi-layer manual process: (1) Shift leaders track all information in personal Excel sheets → (2) Analyze and decide if issues need system entry → (3) Create Excel "Felanmälan" (error report) → (4) Super user manually reviews → (5) Decides if it becomes work order in Idus. Bypass behavior due to system complexity/unclear entry process - users never interact directly with system.
- **Agda/Visma:** Users submit paper leave requests instead of self-service portal - only ~20% adoption (bypass behavior due to digital literacy gaps/computer discomfort, costing 42-83K SEK/year)
- **Flexite:** Multi-layer with gatekeeping: (1) Shift leaders track information in personal Excel sheets → (2) Analyze and decide if incidents need Flexite entry → (3) For observations/accidents/near-misses, enter directly in Flexite → (4) Super user manually analyzes for preventive plans. Despite this complexity, 100% compliance achieved. Additionally, super user must continuously educate users on Idus vs Flexite boundaries for incident reporting (process boundary confusion exists but doesn't prevent adoption).
- **Ascendo:** ✅ **ZERO gatekeeping, ZERO shadow systems, 100% clean adoption.** All 500-1,000 monthly invoices flow directly through Ascendo with no Excel intermediaries, no manual workarounds, no bypass behavior. Vendors → Scancloud → Ascendo → Approvers → SAP → Bank. No shift leader filtering layer exists.

**Strategic Impact:** ALL systems except Ascendo experience manual workarounds and gatekeeping.  
**Critical contrast:** Ascendo achieves 100% adoption WITHOUT requiring shift leader gatekeeping layer that Idus and Flexite depend on. This proves clean direct-entry workflows are achievable at Kubal. 

**Root Cause Analysis:** Why does Ascendo succeed where others need gatekeeping? (1) Clear system purpose - invoice processing is simple, maintenance/incidents are complex, (2) Single workflow - all invoices follow same path, maintenance has exceptions, (3) Automated data capture - OCR handles data entry, users must manually enter maintenance details.

**Hidden costs from gatekeeping:** 
- Shift leader Excel maintenance time (Idus + Flexite) - UNQUANTIFIED
- Super user triage time (Idus)
- Manual data entry (Agda/Visma - quantified at 42-83K SEK/year)
- Ongoing user education (Flexite)
- Information delays and potential data loss from gatekeeping layer

---

### Theme: Mobile Accessibility Gaps
**Found in:** Idus ✓ | Agda/Visma ✗ | Flexite ✗ | Ascendo ✗

**Manifestation by System:**
- **Idus:** Mobile functionality exists but underutilized, efficiency losses from desktop-bound workflows
- **Agda/Visma:** Web-form based system accessible via mobile browser - no mobile accessibility gap identified
- **Flexite:** Mobile and web accessibility fully functional - NOT a gap
- **Ascendo:** Web-form based system accesible via mobile browser

**Strategic Impact:** Idus is the only system with identified mobile limitations. Flexite demonstrates successful mobile implementation. Agda/Visma's web-based architecture provides mobile access without requiring native apps.

---

## 3. SHARED PAIN POINTS

| Pain Point | Idus | Agda/Visma | Flexite | Ascendo | Impact Level |
|------------|:----:|:----------:|:-------:|:-------:|:------------:|
| **Broken/Missing System Integrations** | ✓ | ✓ | ✓ | ✗ ✅ | 🔴 High - 3M+ SEK/year |
| **Shadow Excel Systems / Gatekeeping** | ✓ | ✗ | ✓ | ✗ ✅ | 🔴 High - Data integrity risk |
| **Manual Reporting Burden (No Analytics)** | ✓ | ✗ | ✓ | ✗ ✅ | 🔴 High - 1.5M+ SEK/year |
| **Key Person Dependencies** | ✓ | ⚠️ | ✓ | ✗ ✅ | 🔴 High - Business continuity risk |
| **Limited Mobile Functionality** | ✓ | ✗ | ✗ | ✗ | 🟡 Medium - Productivity impact |
| **Training and Adoption Gaps** | ✓ | ✓ | ✗ | ✗ ✅ | 🟡 Medium - 100K+ SEK/year |
| **Data Quality / Structure Issues** | ✓ | ✗ | ✗ | ✗ ✅ | 🟡 Medium - Idus-specific |
| **Delayed System Upgrades** | ✓ | ✗ | ✗ | ✗ ✅ | 🟡 Medium - Version currency risk |
| **No Real-time Dashboards** | ✓ | ✓ | ✓ | ⚠️ | 🟢 Low - Management visibility |

**Legend:** ✓ Present | ⚠️ Partial concern | ✗ Absent | ✅ Solved | N/A Not applicable | 🔴 High | 🟡 Medium | 🟢 Low

**Key Insight:** Ascendo has ZERO of the major pain points affecting other systems. It demonstrates that integration excellence, clean adoption, and system stability are achievable at Kubal - not theoretical ideals.   
**Management question:** Why does Ascendo succeed across every dimension while Idus fails across almost all?  Answer determines invest-vs-replace decision for Idus.

---

## 4. SHARED STRENGTHS

| Strength | Idus | Agda/Visma | Flexite | Ascendo | Value Level |
|----------|:----:|:----------:|:-------:|:-------:|:-----------:|
| **Mission-Critical Operational Role** | ✓ | ✓ | ✓ | ✓ | ⭐⭐⭐ |
| **Strong User Advocacy from Super Users** | ✓ | ✓ | ✓ | ✓ | ⭐⭐⭐ |
| **Reliable Core Functionality** | ✓ | ✓ | ✓ | ✓ | ⭐⭐⭐ |
| **Zero Downtime / High Availability** | ✓ | ✓ | ✓ | ✓ | ⭐⭐ |
| **Adequate Vendor Support Responsiveness** | ✓ | ✓ | ✗ | ✓ | ⭐⭐ |
| **Successful Audit Trail Compliance** | ✓ | ✓ | ✓ | ✓ | ⭐⭐ |
| **Internal Upgrade Capability** | ✓ | ✗ | ✗ | ✗ | ⭐ |

**Legend:** ✓ Present | ✗ Absent | ? Pending | ⭐⭐⭐ Critical | ⭐⭐ Significant | ⭐ Beneficial

**Key Insight:** All three systems deliver strong core value in their domains - no system is fundamentally failing. This supports "invest in enhancement" strategy over replacement. The common pattern: reliable operations but missing modern features (integrations, analytics, mobile, automation).

---

## 5. UNIQUE SYSTEM CHARACTERISTICS

### What Makes Each System Different

**Idus (CMMS)**
- **Unique advantage:** Internal upgrade capability - can perform version upgrades without vendor dependency (though currently delayed)
- **Unique challenge:** Severe data hygiene and structure issues - poor data organization undermines reporting and analytics
- **Special consideration:** ⚠️ Single source assessment with bias indicators - claims of "unique" features (graphical interface) are actually standard CMMS capabilities. Cost estimates (4.73M SEK/year) require validation before investment decisions. Recommend independent CMMS market evaluation comparing to modern alternatives (Planon, Ultimo, Fiix, eMaint).

**Agda/Visma (HR/Payroll)**
- **Unique advantage:** Validated intentional manual processes - Ekonomi team deliberately maintains manual banking/accounting controls for verification (not system limitation)
- **Unique challenge:** Massive untapped self-service potential - only ~20% employee adoption of portal despite availability (42-83K SEK/year opportunity cost)
- **Special consideration:** Distinction between inefficiency vs. intentional control is critical - apparent "waste" in manual processes may represent legitimate risk management. Validated with multiple stakeholders (Helena + Ekonomi team).

**Flexite (Incident Management)**
- **Unique advantage:** 100% user compliance rate - only system achieving universal adoption with zero bypass behavior
- **Unique challenge:** Complete system isolation - ZERO integrations with any other business system (Idus, Agda/Visma, government e-tjänster)
- **Special consideration:** High compliance criticality (Arbetsmiljöverket requirements) means system changes carry regulatory risk. Manual government reporting (144 reports/year) is pure waste with no legitimate business justification - integration opportunity.

**Ascendo (Invoice Processing)**
- **Unique status:** ✅ **REFERENCE IMPLEMENTATION** - Only system achieving operational excellence across all dimensions (100% adoption, zero manual SAP entry, 95-100% accuracy, team ownership, near-zero waste)
- **Unique value:** Proves what's possible at Kubal - seamless SAP integration IS achievable, invalidating "it can't be done" claims from other systems
- **Critical lesson:** Success factors to replicate: (1) Clear single-purpose workflow, (2) Automated data capture (OCR), (3) Team-based ownership (processor + backup + oversight), (4) 3+ years maturation with experienced users. **Management mandate:** Use Ascendo as benchmark when evaluating whether to fix or replace struggling systems.

---

## 6. INVESTMENT DECISION MATRIX

| Criterion | Idus | Agda/Visma | Flexite | Ascendo |
|-----------|:----:|:----------:|:-------:|:-------:|
| **User Adoption** | Medium (bypass exists) | Low (~20% self-service) | High (100% compliance) | **Perfect (100%)** ✅ |
| **SAP Integration** | Broken (1.55M waste) | Manual by design | Not applicable | **Flawless (zero waste)** ✅ |
| **System Stability** | Moderate | High | High | **Excellent** ✅ |
| **Annual Waste Cost** | 4.73M SEK (UNVALIDATED) | 75K SEK (validated) | 60-90K SEK (estimated) | **~0 SEK** ✅ |
| **Investment Need** | **VALIDATE FIRST** | **Enhance** | **Integrate** | **Maintain Excellence** ✅ |

**THE ASCENDO SUCCESS MODEL - What "Right" Looks Like:**

Ascendo achieves 10/10 criticality with near-zero waste through:
- 100% adoption - no gatekeeping, no shadow Excel systems
- Zero manual SAP entry - saves 900-1,800 hours annually  
- 95-100% accuracy - minimal error correction needed
- Team ownership - Rhodora + Inna + Peter (no single-person risk)
- 3+ years mature - stable, reliable, users highly competent

**Critical Management Insight:** Ascendo proves excellence IS achievable at Kubal. Its success exposes that problems in other systems are solvable, not inherent limitations.

**Investment Priorities (Ranked):**

**1. Agda/Visma - Immediate (0-3 months)**
- 75K validated waste, clear solutions
- Low-risk training campaign: 42-83K SEK/year ROI
- Execute immediately

**2. Flexite - High Priority (3-6 months)**
- Government integration: 60-90K SEK/year savings
- Compliance-critical, clear ROI
- Execute after Agda campaign

**3. Idus - DECISION GATE (Month 1)**
- 4.73M claimed waste requires validation
- Invest 100K in 3-month validation study:
  * Time-track actual manual work
  * Interview multiple users (not just one)
  * Evaluate modern CMMS alternatives
- **Decision after validation:** Fix Idus OR replace with Ascendo-quality alternative
- Do NOT commit 800K without validation

**4. Ascendo - Preserve Excellence**
- Already optimal - no investment needed
- Document success factors
- Use as template for other systems

---

## 7. KEY PATTERNS IDENTIFIED

### Pattern 1: Integration Failures Are Primary Cost Driver
**Observation:** Broken or missing system integrations account for ~3M SEK of 4.9M SEK total annual waste (61% of identified inefficiency)  
**Root Cause:** Systems operating as isolated islands rather than connected ecosystem. Each system was likely implemented independently without enterprise integration architecture. SAP integration failure in Idus suggests technical debt and delayed maintenance.  
**Recommendation:** Establish enterprise integration roadmap prioritizing highest-cost gaps first: (1) Idus-SAP restoration, (2) Flexite-government portal, (3) Evaluate Agda-production system integration business case

### Pattern 2: Manual Reporting Compensates for Missing Analytics
**Observation:** Both Idus and Flexite require significant manual effort creating reports and dashboards despite having data in systems  
**Root Cause:** Systems lack modern BI/analytics capabilities, forcing super users to become data analysts. Time spent on reporting prevents focus on value-added work (Idus: process improvement, Flexite: preventive safety measures)  
**Recommendation:** Evaluate BI tool integration (Power BI, Tableau, Qlik) that could connect to multiple systems, eliminating redundant reporting effort across organization

### Pattern 3: "Build on Strength" Consensus from All Super Users
**Observation:** All three super users (Idus, Agda/Visma, Flexite) independently recommend investing in existing platforms rather than replacement  
**Root Cause:** Core functionality is solid and reliable. Problems are enhancements (integrations, mobile, analytics) not fundamental capabilities. User familiarity and embedded workflows have value. Change management risk and cost favor enhancement.  
**Recommendation:** Accept "invest not replace" strategy BUT apply critical validation especially for Idus given single-source bias risk. Question: Is this genuine strength or sunk cost fallacy?

### Pattern 4: Adoption Success Despite Multi-Layer Complexity
**Observation:** All three systems experience manual workarounds and adoption barriers. **Critical discovery:** Both Idus and Flexite have hidden shift leader gatekeeping layer where shift leaders maintain Excel sheets, analyze data, and decide what enters formal systems - creating multi-step manual processes before any system entry. Agda/Visma has paper-based bypasses (20% self-service adoption). Despite identical multi-layer complexity, Flexite achieves 100% compliance while Idus struggles.  
**Root Cause:** Difference is not absence of complexity or confusion, but system design and support structures that succeed despite them. Shift leader Excel gatekeeping exists in BOTH Idus and Flexite, but only Flexite overcomes it through user-friendly interface, strong super user support, and effective change management. The gatekeeping layer creates information delays, potential data loss, duplicate entry, and inconsistent filtering criteria - but Flexite's design compensates for these organizational challenges.  
**Recommendation:** 
1. **Immediate:** Map the full shift leader Excel workflow to quantify hidden costs and data loss risks
2. **Strategic question:** Should shift leaders be gatekeepers, or should systems be designed for direct entry?
3. **Learning from Flexite:** Study how clear design and strong support enable success despite multi-layer workflows
4. **Apply to Idus:** Simplify entry process OR strengthen super user support to match Flexite's effectiveness
5. **Apply to Agda/Visma:** Enhance self-service campaign with digital literacy support, recognizing perfect process understanding isn't prerequisite for adoption success

### Pattern 5: Intentional Manual Processes vs System Limitations
**Observation:** Not all manual processes represent inefficiency - Agda/Visma case reveals Ekonomi team deliberately maintains manual verification controls  
**Root Cause:** Finance/accounting teams may correctly prioritize accuracy and control over speed/automation. What appears as "waste" in efficiency analysis may be prudent risk management in financial operations.  
**Recommendation:** Validate all manual process optimization opportunities with actual process owners before assuming automation is desired. Distinguish technical gaps from business policy.

### Pattern 6: Varying Levels of Key Person Dependency
**Observation:** Knowledge concentration varies by system - Idus and Flexite have single-person dependencies, while Agda/Visma has two-person team but primary expert has 7 years deep expertise. Backup capability unclear across all three systems.  
**Root Cause:** Succession planning and knowledge transfer may not receive sufficient attention during normal operations. Systems seen as "tools" rather than "capabilities" requiring team ownership and redundancy planning.  
**Recommendation:** Assess actual backup capability for each system to determine appropriate action. For single-person dependencies (Idus, Flexite), urgency is higher. For Agda/Visma, evaluate depth of secondary user's expertise and readiness to assume primary role if needed.

---

## 8. STRATEGIC RECOMMENDATIONS

### Immediate Actions (0-3 months)

1. **Launch Agda/Visma Self-Service Campaign** (Agda/Visma)
   - ROI: 42-83K SEK/year savings from reduced help desk burden
   - Risk: Low - validated data, clear business case
   - Investment: Training materials, communication campaign, super user support time

2. **Initiate Idus Validation Study** (Idus)
   - Investment: ~100K SEK for independent assessment
   - Scope: Time-tracking validation, multi-user interviews, modern CMMS market evaluation
   - Gate Decision: Validate 4.73M SEK waste claim before committing 800K+ SEK investment
   - Alternatives to evaluate: Planon, Ultimo, Fiix, eMaint

3. **Document Ascendo Success Pattern for Replication** (Cross-System Learning)
   - Extract Ascendo's success factors: workflow design, team structure, training approach
   - Create playbook: "How to Achieve 100% Adoption with Zero Waste"
   - Apply learnings to Idus validation (can CMMS achieve Ascendo-level integration?)
   - Benchmark: When evaluating any system, compare to Ascendo standard

4. **Investigate Shift Leader Excel Gatekeeping Layer** (Idus + Flexite)
   - Map complete shift leader workflow: Excel tracking → decision criteria → system entry
   - Quantify hidden costs: Excel maintenance time, information delays, potential data loss
   - Assess: Should shift leaders be gatekeepers or should systems enable direct entry?
   - Compare: Why does Flexite succeed with same workflow while Idus struggles?
   - Decision: Streamline workflow vs. improve system usability vs. strengthen support

4. **Assess and Strengthen Backup Capacity for Critical Systems** (All Systems)
   - Evaluate current backup capability for Idus and Flexite (single-person dependencies)
   - Assess depth of secondary user expertise for Agda/Visma (two-person team)
   - Identify gaps in knowledge transfer and succession planning
   - Develop action plan based on assessment findings

### Short-term Initiatives (3-6 months)

4. **Flexite Government Integration Project** (Flexite)
   - ROI: 60-90K SEK/year elimination of 144 manual reports
   - Technical: API connection to e-tjänster (government portal)
   - Risk: Compliance-critical, requires careful change management

5. **Restore Idus-SAP Integration** (Idus) *[Conditional on validation study results]*
   - ROI: 1.55M SEK/year from inventory synchronization automation
   - Priority 1 if staying with Idus platform
   - Alternative: Modern CMMS with native SAP integration if replacing

6. **Evaluate Enterprise BI Tool Implementation** (All Systems)
   - Addresses manual reporting burden across Idus, Flexite, potentially Agda/Visma
   - Enables cross-system analytics and dashboards
   - Cost-benefit analysis required for Power BI, Tableau, or Qlik investment

### Long-term Considerations (6-12 months)

7. **Idus Reporting Module or BI Integration** (Idus) *[Conditional on validation study results]*
   - ROI: 1.43M SEK/year from automated reporting
   - Decision path depends on validation study outcome

8. **Mobile Enhancement for Idus** (Idus)
   - Enhance Idus mobile functionality for field technicians
   - Learn from Flexite's successful mobile implementation
   - Focus on improving underutilized mobile features

9. **Complete Ascendo Assessment** (Ascendo)
   - Interview Rhodora/Ksenia to complete portfolio view
   - Integrate findings into overall IT strategy
   - Assess invoice processing integration opportunities

10. **Consider System Integration Architecture Review** (All Systems)
    - Current state: Systems as isolated islands
    - Future state: Connected ecosystem with data flowing between systems
    - May require enterprise integration platform or middleware investment

---

## 9. RISK FLAGS & VALIDATION NEEDS

### 🔴 High Priority Validation Required

- **Idus Cost Estimates (4.73M SEK/year):** Single source assessment with identified bias patterns. Super user professional identity tied to Idus may create confirmation bias, sunk cost fallacy, and status quo preference. Claims of "unique" features (graphical interface) are actually standard CMMS market capabilities. Recommend independent validation before committing 800K+ SEK investment.

- **Idus Market Comparison:** Super user compared to 2016 Maximo system, not modern alternatives. Evaluate current Swedish CMMS market (Planon, Ultimo, Fiix, eMaint) to determine if claimed strengths are truly differentiators or commodity features available in all systems.

- **Key Person Dependencies - Idus and Flexite:** Idus functional technician and Flexite H&S manager (8 yrs system experience) each represent single-person dependencies for their respective systems. If either departs, operational continuity compromised. Backup capability assessment required to determine succession planning needs.

- **Backup Capability Assessment - Agda/Visma:** While HR department has two people working with the system, depth of secondary user's expertise unclear. Given 10/10 criticality and payroll regulatory obligations, backup capability requires validation.

- **Shift Leader Excel Gatekeeping - Idus and Flexite:** Critical discovery reveals hidden workflow layer where shift leaders maintain Excel sheets, analyze information, and decide what enters formal systems. This creates: (1) Information delays before system entry, (2) Potential data loss if Excel data never transferred, (3) Inconsistent filtering criteria across shift leaders, (4) Shadow systems with unquantified maintenance costs, (5) Data integrity risks from multi-step manual transfers. Urgent need to map complete workflow, quantify hidden costs, assess data loss risk, and determine if gatekeeping role is necessary or represents process design failure.

### 🟡 Medium Priority Review Recommended

- **Agda/Visma Manual Process Classification:** Verify with Ekonomi team which manual processes are intentional controls vs inefficiencies. Banking/accounting manual transfers may represent prudent verification controls (23K SEK/year) rather than automation opportunities.

- **Flexite Data Export Adjustments:** Users export data and adjust for company workflows, especially new year period. Assess if adjustments represent legitimate business requirements or workarounds for system limitations.

- **Integration Investment Sequencing:** With 3M+ SEK/year integration-related waste, determine optimal sequence for integration projects balancing ROI, technical complexity, and organizational change capacity.

### ✓ Validated & Confirmed

- **Ascendo Reference Implementation:** 10/10 criticality with ZERO waste. Validates that seamless SAP integration, 100% adoption, and operational excellence ARE achievable at Kubal. Success factors documented: automated data capture (95-100% OCR), team ownership (Rhodora + Inna + Peter), 3+ years maturation, clear single-purpose workflow. This proves problems in other systems are solvable, not inherent limitations. **Use Ascendo as benchmark** when evaluating invest-vs-replace decisions.

- **Agda/Visma Self-Service ROI (42-83K SEK/year):** Validated with multiple stakeholders and corroborated through help desk volume analysis. Low-risk improvement opportunity with clear business case.

- **Flexite Compliance Criticality (9/10):** Arbetsmiljöverket legal requirements confirmed. System essential for Swedish workplace safety regulatory compliance. 100% user adoption validates system effectiveness.

- **All Systems Core Functionality:** Zero downtime reported across all four systems. Core operational capabilities are reliable and mission-critical (Idus: 9/10, Agda/Visma: 10/10, Flexite: 9/10, Ascendo: 10/10 criticality ratings).

---

## APPENDIX: Assessment Methodology Notes

**Assessment Approach:**
- Structured super user interviews (45-60 minutes per system)
- Focus on ROI, compliance requirements, user adoption, and strategic value
- Documentation in standardized markdown format for consistency
- Cross-system comparison matrices for pattern identification

**Bias Considerations:**

*Idus Assessment:*
- Single source interview creates inherent limitations
- Super user's professional identity tied to Idus may influence objectivity
- Potential confirmation bias: seeking evidence supporting existing platform
- Sunk cost fallacy: years invested in Idus expertise
- Status quo preference: resistance to change and uncertainty
- Comparison baseline: 2016 Maximo, not current CMMS market
- Claims of "unique" features require market validation

*Agda/Visma Assessment:*
- Single super user but validated with Ekonomi team stakeholders
- Distinction made between inefficiency and intentional controls
- Multiple data points corroborate findings (help desk volume, self-service adoption rate)
- Higher confidence in cost estimates

*Flexite Assessment:*
- Single super user with 8 years system experience
- High confidence in compliance requirements (Arbetsmiljöverket regulations)
- 100% user adoption provides validation of reported system effectiveness
- Note: Users export and adjust data - may indicate system limitations or legitimate workflow requirements

*Ascendo Assessment:*
- Dual super user validation (Rhodora 3+ yrs, Inna 3+ yrs) provides cross-validation
- Users have complementary perspectives: processor (Rhodora) vs manager/oversight (Inna)
- Self-administered questionnaire format - comprehensive written responses
- 10/10 criticality consensus, 95-100% accuracy consensus, stable system consensus
- High confidence - multiple data points align across both users

**Data Quality Assessment:**

| System | Confidence Level | Primary Limitations |
|--------|------------------|---------------------|
| Idus | 🔴 LOW | Single source, poor system data hygiene/structure, potential bias |
| Agda/Visma | 🟢 HIGH | Multi-stakeholder validation, corroborated metrics |
| Flexite | 🟢 HIGH | Strong user adoption validates claims; note on data adjustments |
| Ascendo | 🟢 **EXCELLENT** | Dual user validation, complementary perspectives, zero contradictions |

**Pending Validations:**

1. **Idus cost estimates:** Time-tracking study required to validate 4.73M SEK/year waste claim
2. **Idus market position:** Independent CMMS evaluation needed (Planon, Ultimo, Fiix, eMaint comparison)
3. **Idus multi-user perspective:** Additional interviews beyond single super user recommended
4. **Integration feasibility:** Technical assessments required for proposed integration projects
5. **ROI calculations:** Detailed cost-benefit analyses for major investment recommendations
6. **Shift leader gatekeeping costs:** Quantification of Excel workflow hidden costs (Idus + Flexite)

**Recommendation Confidence:**

*High Confidence (Proceed):*
- Ascendo success pattern documentation (completed assessment, dual validation, proven excellence)
- Agda/Visma self-service campaign
- Backup capability assessment (Idus + Flexite)
- Flexite government integration (subject to technical feasibility)

*Medium Confidence (Evaluate Further):*
- Enterprise BI tool implementation
- Mobile enhancement priorities
- Integration sequencing

*Low Confidence (Validate First):*
- All Idus investment recommendations
- Idus replacement vs enhancement decision
- Total annual waste estimate accuracy (dominated by unvalidated Idus figures)

**Assessment Limitations:**
- Idus: Single super user creates potential for bias
- No direct observation of work processes (interview-based only)
- Cost estimates based on reported time, not measured tracking
- No vendor validation of technical feasibility for proposed enhancements
- **Portfolio complete:** All four systems now assessed

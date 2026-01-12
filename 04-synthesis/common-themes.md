# IT Systems Assessment - Common Themes Matrix

**Assessment Date:** January 2026  
**Prepared by:** IT Systems Assessment Team  
**Status:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo 🔄 (In Process)

---

## Executive Summary

Cross-system analysis of four business-critical systems at Kubal reveals integration failures as the dominant cost driver (61% of identified waste), with combined annual inefficiency of 4.87M SEK across three assessed systems. All three super users independently recommend enhancing existing platforms rather than replacement, suggesting core functionality is solid but missing modern capabilities (integrations, analytics, mobile). Critical finding: Idus assessment (representing 97% of total waste estimate) requires independent validation due to single-source data and identified bias patterns before committing to major investments. Agda/Visma and Flexite assessments show high confidence with validated stakeholder input and clear improvement pathways.

---

## 1. SYSTEM STATUS OVERVIEW

|  | **Idus** | **Agda/Visma** | **Flexite** | **Ascendo** |
|---|---|---|---|---|
| **Status** | ✓ Complete | ✓ Complete | ✓ Complete | 🔄 In Process |
| **Primary Function** | CMMS / Maintenance | HR & Payroll | Incident Management | Invoice Processing |
| **Super User** | Functional Technician | HR Manager (7 yrs) | H&S Manager (8 yrs) | Pending |
| **Monthly Volume** | 1,800 work orders | All employees | 120-140 incidents | Unknown |
| **Criticality** | 9/10 | 10/10 | 9/10 | Pending |
| **Annual Waste** | 4.73M SEK | 75K SEK | 60-90K SEK | Pending |
| **Assessment Confidence** | 🔴 LOW - Single source, poor data hygiene | 🟢 HIGH - Validated with Ekonomi team | 🟢 HIGH - Note: users adjust exported data | Pending |

---

## 2. CRITICAL CROSS-SYSTEM THEMES

### Theme: Integration Gaps Creating Manual Workload
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ?

**Manifestation by System:**
- **Idus:** Broken SAP inventory integration (1.55M SEK/year waste) + no BI/reporting module (1.43M SEK/year waste)
- **Agda/Visma:** Intentional manual banking/accounting processes (23K SEK/year) - by design for Ekonomi team verification control
- **Flexite:** No government system (e-tjänster) integration requiring 144 manual reports/year (60-90K SEK/year waste)
- **Ascendo:** [Pending assessment]

**Strategic Impact:** Integration gaps are THE dominant cost driver across all systems, accounting for ~65% of identified annual waste (3M+ SEK of 4.9M total). However, Agda/Visma reveals not all manual processes are inefficiencies - some represent intentional risk management controls. Validation required to distinguish technical gaps from business controls.

---

### Theme: Key Person Dependencies and Backup Capacity
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ?

**Manifestation by System:**
- **Idus:** Single functional technician manages all system administration with 30 users dependent on one expert
- **Agda/Visma:** HR department has two people working with the system; primary super user has 7 years deep expertise - backup capacity exists and the expertise is clear
- **Flexite:** Single Health & Safety Manager (8 years system experience) manages compliance-critical safety system - backup capacity unclear
- **Ascendo:** [Pending - assess if Rhodora/Ksenia provide redundancy or if knowledge is concentrated]

**Strategic Impact:** Knowledge concentration varies by system. Idus and Flexite have single-person dependencies which create operational continuity risk if those individuals depart. Agda/Visma has staffing redundancy with two people, though the depth of backup capability requires assessment. For compliance-critical systems (Flexite - Arbetsmiljöverket, Agda/Visma - payroll regulations), succession planning and knowledge transfer are especially important regardless of staffing levels. Recommended action: evaluate actual backup capability and knowledge transfer readiness for business continuity planning (Idus and Flexite).

---

### Theme: Strong Core Functionality, Missing Enhancements
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ?

**Manifestation by System:**
- **Idus:** Core CMMS manages 1,800 monthly tickets reliably, but lacks reporting/analytics and has broken SAP integration
- **Agda/Visma:** Payroll/HR core rated 10/10 critical with zero failures, but missing self-service adoption and production integration
- **Flexite:** Incident management core excellent (100% user compliance, 9/10 critical), but zero system integrations
- **Ascendo:** [Pending]

**Strategic Impact:** Pattern suggests "build on strength" investment strategy rather than replacement. All three super users recommend investing in existing platforms - enhancement ROI likely exceeds replacement costs. Risk: Idus assessment may be biased (single source validation required).

---

### Theme: User Adoption Challenges and Manual Workarounds
**Found in:** Idus ✓ | Agda/Visma ✓ | Flexite ✓ | Ascendo ?

**Manifestation by System:**
- **Idus:** Users submit Excel "Fel anmälan" instead of direct system entry → Super user manually triages → Decides work order or quick fix (bypass behavior due to system complexity/unclear entry process)
- **Agda/Visma:** Users submit paper leave requests instead of self-service portal - only ~20% adoption (bypass behavior due to digital literacy gaps/computer discomfort, costing 42-83K SEK/year)
- **Flexite:** 100% compliance rate achieved BUT super user must continuously educate users on Idus vs Flexite boundaries for incident reporting (process boundary confusion exists but doesn't prevent adoption)
- **Ascendo:** [Pending]

**Strategic Impact:** ALL THREE systems experience manual workarounds and adoption challenges, revealing organizational capability gaps in digital adoption, process clarity, and training effectiveness that span the entire system portfolio. Critical insight: Flexite achieves 100% compliance DESPITE boundary confusion, demonstrating that clear system design and effective change management can overcome adoption barriers. The difference is not whether challenges exist, but whether systems and support structures are designed to succeed despite them. Hidden costs include super user triage time (Idus), manual data entry (Agda/Visma - quantified at 42-83K SEK/year), and ongoing user education (Flexite).

---

### Theme: Mobile Accessibility Gaps
**Found in:** Idus ✓ | Agda/Visma ✗ | Flexite ✗ | Ascendo ?

**Manifestation by System:**
- **Idus:** Mobile functionality exists but underutilized, efficiency losses from desktop-bound workflows
- **Agda/Visma:** Web-form based system accessible via mobile browser - no mobile accessibility gap identified
- **Flexite:** Mobile and web accessibility fully functional - NOT a gap
- **Ascendo:** [Pending]

**Strategic Impact:** Idus is the only system with identified mobile limitations. Flexite demonstrates successful mobile implementation. Agda/Visma's web-based architecture provides mobile access without requiring native apps.

---

## 3. SHARED PAIN POINTS

| Pain Point | Idus | Agda/Visma | Flexite | Ascendo | Impact Level |
|------------|:----:|:----------:|:-------:|:-------:|:------------:|
| **Broken/Missing System Integrations** | ✓ | ✓ | ✓ | ? | 🔴 High - 3M+ SEK/year |
| **Manual Reporting Burden (No Analytics)** | ✓ | ✗ | ✓ | ? | 🔴 High - 1.5M+ SEK/year |
| **Key Person Dependencies** | ✓ | ⚠️ | ✓ | ? | 🔴 High - Business continuity risk |
| **Limited Mobile Functionality** | ✓ | ✗ | ✗ | ? | 🟡 Medium - Productivity impact |
| **Training and Adoption Gaps** | ✓ | ✓ | ✗ | ? | 🟡 Medium - 100K+ SEK/year |
| **Data Quality / Structure Issues** | ✓ | ✗ | ✗ | ? | 🟡 Medium - Idus-specific |
| **Delayed System Upgrades** | ✓ | ✗ | ✗ | ? | 🟡 Medium - Version currency risk |
| **No Real-time Dashboards** | ✓ | ✓ | ✓ | ? | 🟢 Low - Management visibility |

**Legend:** ✓ Present | ⚠️ Partial concern | ✗ Absent | ? Pending | 🔴 High | 🟡 Medium | 🟢 Low

**Key Insight:** Integration failures dominate the pain point landscape, representing 60%+ of total identified waste. Manual reporting follows as secondary issue, primarily affecting Idus and Flexite. Key person dependencies vary - Idus and Flexite have single-person risk, while Agda/Visma has staffing redundancy but needs backup capability assessment.

---

## 4. SHARED STRENGTHS

| Strength | Idus | Agda/Visma | Flexite | Ascendo | Value Level |
|----------|:----:|:----------:|:-------:|:-------:|:-----------:|
| **Mission-Critical Operational Role** | ✓ | ✓ | ✓ | ? | ⭐⭐⭐ |
| **Strong User Advocacy from Super Users** | ✓ | ✓ | ✓ | ? | ⭐⭐⭐ |
| **Reliable Core Functionality** | ✓ | ✓ | ✓ | ? | ⭐⭐⭐ |
| **Zero Downtime / High Availability** | ✓ | ✓ | ✓ | ? | ⭐⭐ |
| **Adequate Vendor Support Responsiveness** | ✓ | ✓ | ✗ | ? | ⭐⭐ |
| **Successful Audit Trail Compliance** | ✓ | ✓ | ✓ | ? | ⭐⭐ |
| **Internal Upgrade Capability** | ✓ | ✗ | ✗ | ? | ⭐ |

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
- **Unique advantage:** [Pending assessment]
- **Unique challenge:** [Pending assessment]
- **Special consideration:** [Pending assessment]

---

## 6. INVESTMENT DECISION MATRIX

| Criterion | Idus | Agda/Visma | Flexite | Ascendo |
|-----------|:----:|:----------:|:-------:|:-------:|
| **User Adoption** | Medium (bypass exists) | Low (~20% self-service) | High (100% compliance) | ? |
| **ROI Potential** | Very High (if validated) | High (validated) | Medium-High | ? |
| **Compliance Risk** | Medium | High (payroll critical) | Very High (Arbetsmiljöverket) | ? |
| **Annual Waste Cost** | 4.73M SEK (UNVALIDATED) | 75K SEK (validated) | 60-90K SEK (estimated) | ? |
| **Investment Priority** | **Validate First** | **1 - Immediate** | **2 - High** | ? |

**Priority Ranking Explained:**

**Priority 1 - Agda/Visma (Immediate Action)**
- Validated 75K SEK/year waste with clear solutions
- Low-risk self-service campaign: 42-83K SEK/year savings potential
- Can proceed immediately with training initiatives
- Strong stakeholder support and validated data

**Priority 2 - Flexite (High Priority)**
- Government system integration: eliminate 144 manual reports/year
- Compliance-critical with Arbetsmiljöverket requirements
- High confidence assessment data
- Clear ROI on integration investment

**Priority HOLD - Idus (Validation Required)**
- Single source assessment with identified bias patterns
- 4.73M SEK/year waste estimate requires independent validation
- DECISION GATE: Invest 100K SEK in validation study (3-4 months)
  - Time-tracking study of actual manual processes
  - Multi-user interviews beyond single super user
  - Modern CMMS market evaluation (Planon, Ultimo, Fiix, eMaint)
  - Only after validation → commit to 800K+ SEK investment OR replacement path

**Pending - Ascendo**
- Interview with Rhodora/Ksenia required
- Assessment completion before prioritization

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

### Pattern 4: Adoption Success Despite Organizational Challenges
**Observation:** All three systems experience manual workarounds and adoption barriers (Idus: Excel bypasses, Agda/Visma: 20% self-service, Flexite: boundary confusion requiring education), yet Flexite achieves 100% compliance while others struggle  
**Root Cause:** Difference is not absence of challenges but system design and support structures that succeed despite them. Flexite combines user-friendly interface, strong support, and effective change management to overcome organizational capability gaps (digital literacy, process clarity, training effectiveness) that affect all systems.  
**Recommendation:** Study Flexite's success factors - not elimination of confusion but management of it through clear design and continuous education. Apply learnings: improve Idus entry process clarity, enhance Agda/Visma self-service campaign with digital literacy support, recognize that perfect process understanding isn't prerequisite for adoption success.

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

3. **Assess and Strengthen Backup Capacity for Critical Systems** (All Systems)
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

### 🟡 Medium Priority Review Recommended

- **Agda/Visma Manual Process Classification:** Verify with Ekonomi team which manual processes are intentional controls vs inefficiencies. Banking/accounting manual transfers may represent prudent verification controls (23K SEK/year) rather than automation opportunities.

- **Flexite Data Export Adjustments:** Users export data and adjust for company workflows, especially new year period. Assess if adjustments represent legitimate business requirements or workarounds for system limitations.

- **Integration Investment Sequencing:** With 3M+ SEK/year integration-related waste, determine optimal sequence for integration projects balancing ROI, technical complexity, and organizational change capacity.

### ✓ Validated & Confirmed

- **Agda/Visma Self-Service ROI (42-83K SEK/year):** Validated with Helena and corroborated through help desk volume analysis. Low-risk improvement opportunity with clear business case.

- **Flexite Compliance Criticality (9/10):** Arbetsmiljöverket legal requirements confirmed. System essential for Swedish workplace safety regulatory compliance. 100% user adoption validates system effectiveness.

- **All Systems Core Functionality:** Zero downtime reported across all three systems. Core operational capabilities are reliable and mission-critical (Idus: 9/10, Agda/Visma: 10/10, Flexite: 9/10 criticality ratings).

### ⚠️ Pending Assessment Completion

- **Ascendo System Portfolio:** Cannot complete comprehensive IT strategy recommendations until Ascendo invoice processing assessment completed with Rhodora/Ksenia. May reveal additional integration opportunities or portfolio rationalization possibilities.

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

**Data Quality Assessment:**

| System | Confidence Level | Primary Limitations |
|--------|------------------|---------------------|
| Idus | 🔴 LOW | Single source, poor system data hygiene/structure, potential bias |
| Agda/Visma | 🟢 HIGH | Multi-stakeholder validation, corroborated metrics |
| Flexite | 🟢 HIGH | Strong user adoption validates claims; note on data adjustments |
| Ascendo | ⚪ PENDING | Assessment not yet completed |

**Pending Validations:**

1. **Idus cost estimates:** Time-tracking study required to validate 4.73M SEK/year waste claim
2. **Idus market position:** Independent CMMS evaluation needed (Planon, Ultimo, Fiix, eMaint comparison)
3. **Idus multi-user perspective:** Additional interviews beyond single super user recommended
4. **Integration feasibility:** Technical assessments required for proposed integration projects
5. **ROI calculations:** Detailed cost-benefit analyses for major investment recommendations
6. **Ascendo system assessment:** Complete portfolio view requires fourth system evaluation

**Recommendation Confidence:**

*High Confidence (Proceed):*
- Agda/Visma self-service campaign
- Backup procedure documentation
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
- Single super user per system creates potential for bias
- No direct observation of actual work processes (interview-based only)
- Cost estimates based on reported time allocations, not measured tracking
- No vendor validation of technical feasibility for proposed enhancements
- Incomplete portfolio view pending Ascendo assessment

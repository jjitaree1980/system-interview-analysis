# System Comparison Matrix

**Assessment Date:** December 2025  
**Version:** v1.0

---

## 📋 Table of Contents

**Quick Reference**
- [System Status Cards](#system-status-cards)
- [Investment Priority Ranking](#investment-priority-ranking)
- [Annual Waste Summary](#annual-waste-summary)

**Key Analysis**
- [Executive Summary Table](#executive-summary-table)
- [Side-by-Side Comparison](#side-by-side-comparison)
  - [Problem Type Classification](#problem-type-classification)
  - [Top Priority by System](#top-priority-by-system)
  - [Integration Health Status](#integration-health-status)
  - [Vendor Support Quality](#vendor-support-quality)
  - [User Adoption Challenges](#user-adoption-challenges---manual-workarounds)
- [Critical Findings by System](#critical-findings-by-system)

**Detailed Sections**
- [Idus Assessment Considerations](#idus-assessment-considerations)
- [Management Implications](#management-implications)
- [Next Steps](#next-steps)

---

## 🚨 CRITICAL ALERT: Data Reliability Issues

### Idus Assessment - Validation Required

**⚠️ WARNING:** Idus data comes from single source interview with limited perspective. Cost estimates require validation before investment decisions.

**Data Concerns:**
- Single stakeholder perspective only
- Comparing to legacy system (2016), not modern alternatives
- Claims standard CMMS features as "unique strengths"
- 4.7M SEK waste estimate **UNVALIDATED**
- Poor data hygiene and structure in current system

**Action Required:** Complete validation study before committing 800K+ SEK investment.

[Full assessment considerations →](#idus-assessment-considerations)

---

## System Status Cards

### 🔧 Idus - CMMS Maintenance Management
```
Status:        ✅ Assessment Complete (⚠️ REQUIRES VALIDATION)
Criticality:   9/10 (single source perspective)
Interview:     Super user (Functional Technician) - SINGLE SOURCE
Annual Waste:  4,730,590 SEK (REQUIRES VALIDATION)
Data Quality:  🔴 LOW - Poor data hygiene and structure in system
Decision:      VALIDATION STUDY REQUIRED
```

**🎯 Priority Actions:**
1. Validate cost assumptions (time-tracking study)
2. Evaluate modern CMMS alternatives (Planon, Ultimo, Fiix, eMaint)
3. Additional user interviews needed
4. Assess data structure and cleaning requirements

---

### 👥 Agda/Visma - HR & Payroll
```
Status:        ✅ Assessment Complete
Criticality:   10/10
Interview:     Super user (7 yrs experience) - SINGLE SOURCE
Annual Waste:  75,000 SEK (Helena's assessment)
Data Quality:  🟢 HIGH - Experienced super user, well-documented processes
Decision:      INVEST IN EXISTING PLATFORM
```

**🎯 Priority Actions:**
1. Launch self-service adoption campaign (42-83K SEK/year savings)
2. Training initiative for unused features

**📝 Note on Manual Controls:** Helena reports that manual banking/accounting transfers are intentional per Ekonomi team requirements for payment validation. This has not been independently verified with Ekonomi team but aligns with typical finance control practices.

---

### ⚠️ Flexite - Incident Management
```
Status:        ✅ Assessment Complete
Criticality:   9/10
Interview:     Super user (Health & Safety Manager, 8 yrs system experience)
Annual Waste:  60,000-90,000 SEK (estimated)
Data Quality:  🟢 HIGH - Note: Users export/adjust data for company workflows
Decision:      INVEST IN EXISTING PLATFORM
```

**🎯 Priority Actions:**
1. Government system integration (eliminate 144 manual reports/year)
2. Automated dashboard implementation

**📝 Data Note:** Users may adjust exported data to align with company working modes (especially during new year period)

---

### 📄 Ascendo - Invoice Processing
```
Status:        ✅ Assessment Complete (VALIDATED)
Criticality:   10/10 (Both users)
Interview:     Two super users (AP Accountant, AP Manager, 3+ yrs experience)
Annual Waste:  MINIMAL - Best-in-class system performance
Data Quality:  🟢 HIGH - Two sources, corroborating assessments
Decision:      MAINTAIN CURRENT STATE (Excellent performance)
```

**🎯 Priority Actions:**
1. Monitor minor pain points over 1-2 months (quantify if needed)
2. Evaluate vendor enhancement packages only if ROI-positive
3. Interview Peter (payment processor) to complete workflow assessment

**✅ SUCCESS STORY:** Zero manual SAP data entry, 95-100% OCR accuracy, 100% adoption, saves 900-1,800 hours annually. Both users report "fully meets needs."

---

## Investment Priority Ranking

| Priority | System | Investment Type | Annual Savings Potential | Confidence Level | Budget Estimate |
|----------|--------|----------------|-------------------------|------------------|-----------------|
| **#1** | **Agda/Visma** | Training & adoption | 42,000-83,000 SEK | 🟢 High | Low |
| **#2** | **Flexite** | Integration (government) | 60,000-90,000 SEK | 🟢 High | Medium |
| **#3** | **Idus** | Validation study FIRST | 4,730,590 SEK (if accurate) | 🔴 Requires validation | 100K SEK study |
| **#4** | **Ascendo** | Monitor & maintain | Minimal optimization only | 🟢 High | Very Low |

**Investment Philosophy:**
- **High confidence, low cost → Proceed immediately** (Agda, Flexite)
- **Low confidence, high cost → Validate first** (Idus)
- **Best-in-class performance → Maintain stability** (Ascendo)

**Portfolio Pattern Insight:**
Two systems performing excellently (Agda/Visma, Ascendo), one needs integration (Flexite), one requires validation before any investment (Idus). This suggests organizational capability to implement systems well when properly scoped and integrated.

---

## Annual Waste Summary

### Total Identified Waste
**4,865,000-4,895,000 SEK/year** across four systems

**⚠️ CAVEAT:** 97% of waste is from Idus (4.7M SEK) - **UNVALIDATED ESTIMATES**

### Waste Breakdown by System

| System | Annual Waste | % of Total | Data Quality | Validation Status |
|--------|--------------|------------|--------------|-------------------|
| Idus | 4,730,590 SEK | 97% | 🔴 Low | **REQUIRES VALIDATION** |
| Agda/Visma | 75,000 SEK | 1.5% | 🟢 High | Single source (Helena - experienced, credible) |
| Flexite | 75,000 SEK | 1.5% | 🟢 High | Single source (well-documented compliance focus) |
| Ascendo | MINIMAL | <0.1% | 🟢 High | ✅ Two sources corroborating |

**Portfolio Insight:** Three systems (Agda/Visma, Flexite, Ascendo) combined waste is ~150K SEK (3% of total). One system (Idus) represents 97% of waste IF estimates accurate. This extreme concentration suggests Idus validation study should be top priority for investment decisions.

**Success Story:** Ascendo demonstrates zero-waste target is achievable. With 100% adoption, zero manual SAP entry, and 900-1,800 hours saved annually, Ascendo proves excellence is possible at Kubal and should be the benchmark for other systems.

### Waste Categories - Idus Detail

| Category | Annual Cost | % of Idus Total | Data Source |
|----------|------------|-----------------|-------------|
| Broken SAP integration | 1,552,000 SEK | 33% | Interview estimate (10 min/ticket) |
| No mobile platform | 981,000 SEK | 21% | Interview estimate (5-10% productivity loss) |
| No reporting module | 176,000 SEK | 4% | Interview estimate (8 hrs/week manual work) |
| Performance issues | 627,590 SEK | 13% | Interview estimate (5 trips/week × 10 min) |
| System unavailability | 544,000 SEK | 12% | Historical data (10 downtime hrs/year) |
| Missing automation | 850,000 SEK | 18% | Interview estimate (various inefficiencies) |

**🚨 54% of Idus waste (2.5M SEK) comes from SAP + Mobile categories based on unvalidated assumptions**

**⚠️ ADDITIONAL UNQUANTIFIED WASTE:** Both Idus and Flexite have **shift leader Excel maintenance time** that is NOT included in above figures:
- Shift leaders maintain parallel Excel tracking systems before data enters formal systems
- Time spent on Excel sheets (tracking, analysis, decision-making, "Felanmälan" creation) not measured
- Double/triple data entry waste (Excel → "Felanmälan" → Idus OR Excel → Flexite) not fully captured
- **Estimated impact if quantified:** Could add 50-100K+ SEK annually across both systems
- **Investigation required** to determine actual cost

---

## Executive Summary Table

| System | Primary Purpose | Criticality | User Satisfaction | Annual Waste | Decision |
|--------|----------------|-------------|-------------------|--------------|----------|
| **Idus** | CMMS maintenance | 9/10 | High (power users) | **4.7M SEK** ⚠️ | **Validate first** |
| **Agda/Visma** | HR and payroll | 10/10 | High + advocacy | 75K SEK ✓ | Invest now |
| **Flexite** | Incident management | 9/10 | Excellent (100% adoption) | 60-90K SEK ✓ | Invest now |
| **Ascendo** | Invoice processing | 10/10 | Excellent (both users) | MINIMAL ✓ | Maintain (best-in-class) |

**Legend:**
- ⚠️ = Requires validation (poor data structure/single source with concerns)
- ✓ = Credible single-source or multiple sources
- 🔴 = Low confidence (data quality issues, unvalidated assumptions)
- 🟢 = High confidence (experienced source, credible assessment)

**Data Quality Notes:**
- Idus: Poor data hygiene and structure in system; single source interview
- Agda/Visma: Single source (Helena) with 7 years experience; Helena reports manual controls are per Ekonomi team requirements (not independently verified)
- Flexite: High confidence; users may adjust exported data for company workflows
- Ascendo: High confidence; two sources corroborating, best-in-class performance

**Four-System Portfolio Assessment:**
- **Two excellence cases** (Agda/Visma, Ascendo): 10/10 criticality, credible assessments, minimal waste
- **One integration opportunity** (Flexite): 9/10 criticality, strong core, needs connections
- **One validation required** (Idus): 9/10 criticality, unvalidated 4.7M SEK waste claim

---

## Side-by-Side Comparison

### Problem Type Classification

| System | Problem Type | Root Cause | Solution Approach |
|--------|-------------|------------|-------------------|
| **Idus** | Technical failures | Broken integration, missing modules | Fix OR replace (needs evaluation) |
| **Agda/Visma** | Organizational gaps | Unused features, lack of training | Change management + training |
| **Flexite** | Integration isolation | Strong core, missing connections | Integration + automation |
| **Ascendo** | No significant problems | Excellent implementation | Monitor & maintain excellence |

**Pattern Recognition:** Only one system (Idus) has technical failures. Two systems (Agda/Visma, Ascendo) need minor organizational improvements. One system (Flexite) needs integration work. This suggests Kubal has strong system implementation capability when integration is done well.

### Top Priority by System

| System | #1 Priority | Impact | Difficulty | Timeline |
|--------|------------|--------|------------|----------|
| **Idus** | Evaluate alternatives vs. investment | High IF accurate | Medium | 3-4 months |
| **Agda/Visma** | Self-service adoption campaign | Medium (credible estimate) | Low | 1-2 months |
| **Flexite** | Government integration | Medium | Medium | 3-6 months |
| **Ascendo** | Monitor minor pain points | Very Low | Very Low | Ongoing |

**Strategic Takeaway:** Three systems have clear, actionable priorities. One (Ascendo) simply needs stability maintenance. This allows focused resource allocation on systems with actual improvement needs.

### Integration Health Status

| System | SAP | External Systems | Email | Overall Status |
|--------|-----|-----------------|-------|----------------|
| **Idus** | ❌ BROKEN | - | ✅ | 🔴 Critical failure |
| **Agda/Visma** | ✅ Functional | ⚠️ Manual controls | ✅ | 🟢 Healthy |
| **Flexite** | - | ❌ None | ✅ | 🟡 Isolated but stable |
| **Ascendo** | ✅ SEAMLESS | ✅ Vendor data | ✅ | 🟢 Reference implementation |

**Critical Learning:** Ascendo proves seamless SAP integration is achievable at Kubal. Zero manual data entry, automatic posting, automatic payment order creation. This should be the benchmark standard for evaluating other system integrations.

**Integration Hierarchy:** Ascendo (seamless) > Agda/Visma (functional with controls) > Flexite (isolated but stable) > Idus (broken critical integration)

### Vendor Support Quality

| System | Responsiveness | Partnership Quality | Concerning Issues |
|--------|---------------|---------------------|-------------------|
| **Idus** | Adequate | Standard | SAP issue unresolved |
| **Agda/Visma** | Excellent | Strong partnership | None identified |
| **Flexite** | Good | Collaborative | None identified |
| **Ascendo** | Good | Stable relationship | Rare IT issues only |

**Vendor Pattern:** Three of four systems report good-to-excellent vendor relationships. Only Idus shows concerning vendor performance (unresolved SAP integration). This suggests the Idus vendor problem may be systemic rather than isolated.

### User Adoption Challenges - Manual Workarounds

| System | Manual Workaround Pattern | Root Cause | Hidden Cost Impact |
|--------|--------------------------|------------|-------------------|
| **Idus** | **Shift leaders** maintain Excel tracking sheets → Analyze to determine Idus need → Create Excel "Felanmälan" → **Super user** manually reviews → Decides work order or quick fix | System complexity / Multi-layer manual process / Unclear entry criteria | Shift leader Excel maintenance time + Super user triage time + Delayed work orders + **Double/triple data entry** |
| **Agda/Visma** | Users submit paper leave requests instead of self-service portal | Digital literacy gaps / computer discomfort | Manual data entry (41-83K SEK/year already calculated) |
| **Flexite** | **Shift leaders** maintain Excel tracking sheets → Analyze to determine Flexite need → Enter in Flexite → **Manual analysis** for preventive plans | Unclear system boundaries / Manual analysis requirement | Shift leader Excel maintenance time + Manual preventive analysis time + **Double data entry** |
| **Ascendo** | **No manual workarounds** - 100% digital adoption | Clear workflow design / Seamless SAP integration / Excellent OCR accuracy (95-100%) | **None** - System eliminates manual processes entirely |

**🚨 CRITICAL DISCOVERY:** Both Idus and Flexite have an **unquantified Excel pre-processing layer** where shift leaders maintain parallel tracking systems before deciding what enters the formal systems. This represents significant hidden waste:
- **Shift leader time maintaining Excel sheets** (not previously quantified)
- **Double/triple data entry** (Excel → "Felanmälan" → Idus OR Excel → Flexite)
- **Manual analysis and triage time** at multiple steps
- **Delayed incident response** due to multi-step manual processes

**Ascendo Success Model:** Zero workarounds achieved through: (1) Seamless SAP integration eliminating manual data entry, (2) 95-100% OCR accuracy minimizing corrections, (3) Clear approval routing removing process confusion, (4) 100% user adoption proving system meets real workflow needs. This demonstrates the target state possible at Kubal.

**Cross-System Pattern:** Three of four systems experience manual bypasses. The Idus and Flexite workflows are particularly concerning because shift leaders maintain **shadow Excel systems** as primary data collection tools, with formal systems used only after manual analysis and filtering. Ascendo and Agda/Visma (for core payroll) show full digital adoption is achievable.

**Strategic Implication:** Hidden costs include shift leader Excel time (Idus, Flexite - unquantified), super user triage time (Idus), and manual data entry (Agda/Visma - 41-83K SEK/year). Ascendo proves these costs can be eliminated through proper system design and integration. These adoption barriers represent organizational capability gaps that span systems, but Ascendo demonstrates excellence is achievable.

---

## Critical Findings by System

### Idus - Key Takeaways

**🔴 CRITICAL ISSUES**
1. Broken SAP integration → 1.55M SEK/year (estimate)
2. No mobile platform → 981K SEK/year (estimate)
3. Poor data hygiene and structure in system
4. Single-source interview data requiring validation

**🟢 STRENGTHS**
- Reliable work order management (1,800/month)
- Strong preventive maintenance framework
- High satisfaction among power users

**⚠️ DATA CONCERNS**
- Limited to single stakeholder perspective
- Cost estimates based on unvalidated assumptions
- Data structure and cleaning issues affecting reporting
- Modern CMMS comparison needed

**💰 ESTIMATED FIX COST:** 800K+ SEK (Idus investment path)

**🎯 RECOMMENDATION:** Do NOT commit investment before validation study

**📝 USER ADOPTION NOTE:** Multi-layer manual process creates significant hidden waste:
1. **Shift leaders maintain Excel tracking sheets** for all operational issues (time not quantified)
2. **Shift leaders analyze Excel data** to determine what needs Idus entry (decision time not quantified)
3. **Shift leaders create Excel "Felanmälan"** reports for selected items (formatting time not quantified)
4. **Super user manually reviews** each "Felanmälan" (triage time not quantified)
5. **Super user decides** work order vs. quick fix (decision time not quantified)

This **5-step manual process with triple data entry** (Excel tracking → Excel Felanmälan → Idus work order) adds substantial unquantified costs in shift leader time, super user time, and delayed work order processing. The 176,000 SEK manual reporting cost may significantly underestimate actual waste.

---

### Agda/Visma - Key Takeaways

**🟢 STRENGTHS**
- 10/10 criticality - irreplaceable
- Excellent core payroll performance
- Strong vendor partnership
- Validated cost estimates

**🟡 IMPROVEMENT AREAS**
1. Paper leave requests (42-83K SEK/year)
2. Unused employee self-service features
3. Missing production system integration

**✅ VALIDATED DATA**
- Helena (7 years experience) provides credible, well-informed assessment
- Manual controls reported as intentional per Ekonomi team requirements (Helena's understanding - not independently verified)
- Cost estimates based on observable processes
- High confidence in recommendations despite single-source data

**💰 WASTE COST:** 75K SEK/year (Helena's assessment)

**🎯 RECOMMENDATION:** Proceed with self-service adoption campaign immediately

**📝 USER ADOPTION NOTE:** Paper leave requests continue due to digital literacy gaps and computer discomfort among some users. This waste is already quantified in the 41-83K SEK/year calculation above.

**📝 DATA QUALITY NOTE:** Assessment based on Helena (super user, 7 years experience) only. Her report that manual banking/accounting transfers are intentional Ekonomi team requirements has not been independently verified but aligns with typical finance control practices. Consider brief confirmation with Ekonomi team to validate this understanding.

---

### Flexite - Key Takeaways

**🟢 STRENGTHS**
- 100% employee adoption rate
- Easy-to-use interface
- Excellent incident capture (120-140/month)
- Critical for safety compliance

**🟡 GAPS**
1. Manual government reporting (144 reports/year)
2. No automated dashboards (30-45 min/cycle)
3. Zero system integrations

**📊 USAGE DATA**
- 120-140 monthly incident reports
- 100% compliance rate
- Critical for Arbetsmiljöverket compliance

**💰 ESTIMATED WASTE:** 60-90K SEK/year

**🎯 RECOMMENDATION:** Invest in government integration and dashboard automation

**📝 USER ADOPTION NOTE:** Multi-step manual process identified:
1. **Shift leaders maintain Excel tracking sheets** for observations, accidents, near-misses (time not quantified)
2. **Shift leaders analyze Excel data** to determine what needs Flexite entry (decision time not quantified)  
3. **Shift leaders enter selected incidents in Flexite** (achieves 100% compliance for formal incidents)
4. **Super user manually analyzes** incident data for preventive planning (time partially captured in dashboard creation cost)

This **4-step process with double data entry** (Excel tracking → Flexite) adds unquantified shift leader Excel maintenance time. The 60-90K SEK waste estimate captures government reporting and dashboard work but may not fully account for shift leader Excel time investment.

**📝 USER ADOPTION NOTE:** Super user team educates users on Idus/Flexite boundaries - which incidents should be logged where. Despite this process boundary confusion, Flexite achieves 100% compliance, demonstrating that clear system design and effective change management can overcome adoption barriers.

---

### Ascendo - Key Takeaways

**🟢 STRENGTHS - BEST-IN-CLASS PERFORMANCE**
- 10/10 criticality (both users) - absolutely essential
- Zero manual SAP data entry achieved
- 95-100% OCR accuracy on invoice scanning
- 100% user adoption (500-1,000 invoices/month)
- Seamless SAP integration (reference implementation)
- Saves 900-1,800 hours annually vs manual processing

**✅ SUCCESS METRICS**
- Automatic payment order creation in SAP
- Full approval workflow automation
- Duplicate detection working effectively
- Complete audit trail and status tracking
- Zero manual workarounds or bypasses
- Both users report "fully meets our needs"

**🟡 MINOR OPTIMIZATION OPPORTUNITIES**
1. Approval reminder automation (not yet configured)
2. Requisitioner notification automation (small time savings)
3. Vendor matching logic refinement (edge case improvements)
4. UI column width adjustments (cosmetic only)

**✅ VALIDATED ASSESSMENT**
- Two independent sources (AP Accountant + AP Manager)
- 3+ years system experience each
- Corroborating assessments on all major points
- Only disagreement: "invest more" vs "keep as is" (both positive)

**💰 WASTE COST:** MINIMAL - All pain points are enhancements, not fixes

**🎯 RECOMMENDATION:** Maintain current excellence. Only invest in enhancements if clear ROI demonstrated (<2 year payback required)

**📝 USER ADOPTION NOTE:** No manual workarounds exist. 100% digital adoption achieved through seamless SAP integration, excellent OCR accuracy, and clear approval workflow. Ascendo demonstrates the target state: zero shadow systems, zero manual data entry, zero process confusion. This is the benchmark other Kubal systems should aspire to.

**🏆 STRATEGIC SIGNIFICANCE:** Ascendo proves that seamless SAP integration IS achievable at Kubal. This invalidates any argument that broken integrations (like Idus-SAP) are unavoidable. Ascendo should be the reference implementation for all future system integration evaluations.

---

## Idus Assessment Considerations

### Assessment Limitations

**1. Single Source Perspective**
- Data collected from one super user interview
- Limited to functional technician viewpoint
- → Need additional perspectives (regular technicians, occasional users, production team)

**2. Comparison Reference**
- System compared against legacy Maximo (replaced ~2016)
- NOT compared to modern CMMS alternatives
- → Makes current system appear more competitive than market reality

**3. Data Quality Issues in System**
- Poor data hygiene practices
- Inadequate data structure design
- Inconsistent data cleaning procedures
- → Affects reporting accuracy and analysis reliability

**4. Feature Perception vs. Market Reality**
- Claims as "unique strengths": graphical interface, BOM hierarchy, asset database
- **Reality:** These are standard features in modern CMMS systems
- → Inflates perceived competitive advantage

### Cost Estimation Uncertainty

**High Uncertainty Areas:**
| Estimate | Assumption | Risk Level | Reason |
|----------|-----------|------------|--------|
| 10 min/ticket for SAP verification | Interview estimate, not time-tracked | 🔴 High | No empirical data |
| 5-10% productivity loss from no mobile | Subjective percentage estimate | 🔴 High | Difficult to measure |
| 5 control room trips/week | Frequency assumption | 🟡 Medium | May vary by season/role |
| 8 hours/week manual reporting | Time estimate, not measured | 🟡 Medium | Need validation |

**Potential Overestimation Impact:** If actual times are 50% of estimates, waste drops from 4.7M to 2.35M SEK

### Market Reality Check

**Claimed Idus Advantages → Market Reality:**
- "Graphical interface" → Standard in all modern CMMS
- "BOM hierarchy structure" → Standard in all industrial CMMS
- "Comprehensive asset database" → Core feature, not differentiator
- "Better than old Maximo" → Not relevant comparison (Maximo replaced 2016)

**Modern CMMS Alternatives to Evaluate:**
- Planon (Swedish presence, cloud-native)
- Ultimo (Strong EU presence)
- Fiix (Modern cloud platform)
- eMaint (Fluke Reliability, global support)

### Validation Requirements

**Before Investment Decision:**
1. **Time-tracking study** (2-4 weeks)
   - Actual manual verification times
   - Real control room trip frequency
   - Measured reporting hours

2. **Additional interviews** (3-5 users)
   - Regular technicians perspective
   - Occasional users feedback
   - Production team impact assessment

3. **Data quality audit** (1-2 weeks)
   - Current data structure assessment
   - Data cleaning requirements
   - Impact on reporting capabilities

4. **Market evaluation** (2-3 months)
   - 3-5 modern CMMS alternatives
   - Real workflow demonstrations
   - 5-year TCO comparison

**Budget for Validation:** ~100K SEK
**Timeline:** 3-4 months
**ROI Protection:** Prevents potential 800K+ SEK wrong decision

---

## Management Implications

### Data Quality Assessment

| System | Assessment Reliability | Reason | Investment Confidence |
|--------|----------------------|--------|---------------------|
| **Idus** | 🔴 Low | Single source + poor data structure/hygiene | Requires validation |
| **Agda/Visma** | 🟢 High | Experienced super user (7 yrs) + credible assessment | Can proceed with reasonable confidence |
| **Flexite** | 🟢 High | Compliance-focused + well-documented | Can proceed |
| **Ascendo** | 🟢 Very High | Two sources corroborating + measurable results | Maintain excellence |

**Note on Agda/Visma:** Assessment from single source (Helena, 7 years experience). Her report that manual banking/accounting transfers are intentional per Ekonomi team requirements has not been independently verified but aligns with typical finance control practices. Brief Ekonomi team confirmation would increase confidence to "very high."

**Note on Flexite:** Users may export and adjust data slightly to align with company working modes (especially during new year period), but overall data quality and assessment confidence remain high.

**⚠️ UNQUANTIFIED COST ALERT:** Both Idus and Flexite assessments discovered significant **shift leader Excel maintenance time** that was NOT quantified in original waste calculations:
- **Shift leaders maintain parallel Excel tracking systems** before data enters formal systems
- **Time spent on Excel sheets** (tracking, analysis, decision-making) is not measured
- **Double/triple data entry waste** (Excel → Felanmälan → Idus OR Excel → Flexite) not fully captured
- **Estimated impact:** Could add 50-100K+ SEK annually across both systems if measured

This suggests actual waste for both systems may be **higher than reported figures**.

**Asymmetric Confidence Impact:**
- Agda/Visma 75K SEK → High confidence in Helena's credible assessment, can act with reasonable confidence
- Flexite 60-90K SEK → High confidence, compliance-documented, reasonable to proceed
- Ascendo MINIMAL → Very high confidence, two sources + measurable performance data
- Idus 4.7M SEK → Low confidence, **MUST validate before committing**
- Agda/Visma 75K SEK → High confidence, can act immediately
- Flexite 60-90K SEK → High confidence, reasonable to proceed, **but may underestimate shift leader time**
- Idus 4.7M SEK → Low confidence, **MUST validate before committing**, **plus unquantified shift leader time**

### Investment Decision Framework

**Two Viable Paths for Idus:**

**Path A: Accept Recommendation (Higher Risk)**
- Commit 800K+ SEK to Idus investment immediately
- **Risk:** Overestimated costs, alternatives not evaluated, single perspective
- **Timeline:** Faster (6-12 months)
- **Cost:** 800K+ SEK commitment

**Path B: Validate First (Lower Risk) ← RECOMMENDED**
- Invest 100K SEK in 3-4 month evaluation first
- Validate assumptions, compare alternatives, multi-user input
- **Risk:** Protected against 800K SEK wrong decision
- **Timeline:** Slower (12-18 months total)
- **Cost:** 100K SEK study + informed decision

**Decision Gate Outcomes:**
- Proceed with Idus investment if validation confirms estimates
- Replace with modern CMMS if alternatives offer better 5-year value
- Hybrid approach if partial investment justified

### Scenario Analysis

**Scenario 1: All Estimates Accurate (4.865M SEK/year total)**
- Idus dominates (97% of waste) → Urgent action required
- Agda/Visma & Flexite relatively minor
- **Implication:** Idus investment becomes critical IF validated

**Scenario 2: Idus Overestimated 50% (2.5M SEK/year total)**
- Idus still significant (94%) but more manageable
- Validates cautious evaluation approach
- **Implication:** Balanced investment across all systems

**Scenario 3: Modern Alternatives Better Value**
- Cloud CMMS may include Idus gaps as standard features
- Lower TCO, better support, automatic updates
- **Implication:** Replacement more cost-effective than investment

### Resource Allocation Strategy

**Risk-Adjusted Priority Order:**

**Immediate Actions (Month 1):**
1. ✅ Agda/Visma self-service campaign (42-83K savings, high confidence, low risk)
2. 📋 Flexite government integration planning (compliance-critical)
3. 🔍 Approve Idus validation study (100K SEK investment)

**Short-term (Months 1-4):**
4. 🔍 Execute Idus market evaluation (alternatives comparison)
5. 🛠️ Flexite dashboard automation (30-45 min/cycle savings)
6. ✅ **Ascendo assessment COMPLETE** - Added to four-system portfolio view

**Decision Gate (Month 4-5):**
7. 🎯 Idus investment decision (based on validation results)

**Medium-term (Months 5-12):**
8. Execute approved Idus investment path
9. Implement Flexite government integration
10. Continue Agda/Visma optimization

**Critical Success Factor:**
🚨 **Do NOT commit 800K+ SEK to Idus before validation study**

---

## Next Steps

### Month 1 - Immediate Actions

**✅ High Confidence, Low Risk**
- [ ] Launch Agda/Visma self-service adoption campaign
- [ ] Begin Agda/Visma training initiative for unused features
- [ ] Approve 100K SEK budget for Idus validation study

**📋 Planning & Preparation**
- [ ] Initiate Flexite government integration research (e-tjänster API)
- [ ] Schedule Ascendo interview (invoice processing super users)

### Months 1-4 - Validation Phase

**🔍 Idus Validation Study**
- [ ] Time-tracking study (actual vs. estimated manual process times)
- [ ] **Quantify shift leader Excel maintenance time:** Track time spent maintaining Excel sheets, analyzing data, and creating "Felanmälan" reports
- [ ] **Map complete workflow:** Excel tracking → Analysis → "Felanmälan" creation → Super user review → Work order decision
- [ ] Additional user interviews (3-5 technicians, occasional users, production team, **shift leaders**)
- [ ] Document real workflow patterns and pain points
- [ ] **Calculate triple data entry waste:** Excel → "Felanmälan" → Idus work order

**🔍 Idus Market Evaluation**
- [ ] Research 3-5 modern CMMS alternatives (Planon, Ultimo, Fiix, eMaint)
- [ ] Request vendor demonstrations with real Kubal workflows
- [ ] Complete 5-year TCO analysis (Idus investment vs. alternatives)
- [ ] Assess Idus vendor roadmap and product investment

**🛠️ Flexite Progress**
- [ ] Engage Flexite vendor on government integration roadmap
- [ ] Calculate ROI for 144 annual report automation
- [ ] Begin automated dashboard requirement documentation
- [ ] **Quantify shift leader Excel maintenance time:** Track time spent maintaining Excel sheets and analyzing data before Flexite entry
- [ ] **Interview shift leaders:** Understand workflow and decision criteria for Flexite vs. Idus incident classification
- [ ] **Calculate double data entry waste:** Excel tracking → Flexite entry
- [ ] **Assess manual preventive analysis time:** Super user time analyzing incidents for preventive plans

**✅ Complete Portfolio**
- [x] **Complete Ascendo assessment** - ✅ COMPLETE
- [ ] Update comparison matrix with full four-system perspective - ✅ COMPLETE
- [ ] Update comparison matrix with four-system perspective
- [ ] **🚨 CROSS-SYSTEM INVESTIGATION: Shift Leader Excel Workflows**
  - [ ] Identify all shift leader Excel tracking sheets (Idus-related, Flexite-related, others)
  - [ ] Quantify total shift leader time maintaining parallel Excel systems
  - [ ] Assess why Excel is preferred over direct system entry
  - [ ] Calculate combined waste from double/triple data entry across systems
  - [ ] Evaluate if this pattern exists in other areas (Agda/Visma, Ascendo, etc.)

### Month 4-5 - CRITICAL DECISION GATE

**🎯 Idus Investment Decision**

Based on validation study and market evaluation, choose path:

- **Path A:** Commit to Idus investment (SAP, reporting, mobile) if:
  - Validation confirms 4.7M SEK waste estimate
  - Alternatives don't offer better 5-year value
  - Idus vendor shows strong roadmap

- **Path B:** Proceed with modern CMMS replacement if:
  - Alternatives show better TCO
  - Cloud features address Idus gaps as standard
  - Better integration and support ecosystem

- **Path C:** Hybrid approach if:
  - Some Idus investments justified short-term
  - Plan longer-term replacement (2-3 years)
  - Staged migration strategy makes sense

### Months 5-12 - Implementation Phase

**Based on Decision Gate Outcome:**
- [ ] Execute approved Idus path (investment OR replacement OR hybrid)
- [ ] Implement Flexite government system integration
- [ ] Continue Agda/Visma optimization (production integration evaluation)
- [ ] Evaluate Flexite-Idus integration (depends on Idus decision)

### Months 12-24 - Optimization Phase

- [ ] Develop integrated investment roadmap
- [ ] Monitor actual waste reduction from improvements
- [ ] Post-implementation review (validate ROI calculations)
- [ ] Update strategic priorities based on lessons learned

---

## Assessment Status

**✅ Completed Assessments:**
- **Idus** - Super user (Functional Technician) - ⚠️ Single source, validation required
- **Agda/Visma** - Super user (7 years experience) - ✓ Single source, credible assessment
- **Flexite** - Super user (Health & Safety Manager, 8 years system experience) - ✓ High confidence
- **Ascendo** - Two super users (AP Accountant, AP Manager, 3+ years experience) - ✓ Corroborating assessments

**📊 Complete Portfolio Status:**
- **4 of 4 systems assessed (100%)**
- **3 of 4 assessments high confidence (75%)**
- **2 of 4 systems performing excellently (50%)** - Agda/Visma, Ascendo
- **1 of 4 requires validation before action (25%)** - Idus
- **1 of 4 needs integration investment (25%)** - Flexite

**Portfolio Health Summary:**
- **Excellence tier:** Agda/Visma, Ascendo (minimal waste, high performance)
- **Integration tier:** Flexite (strong core, needs connections)
- **Investigation tier:** Idus (validation study required before any investment)

---

## Document Version Control

**Version:** 2.0  
**Last Updated:** January 2026  
**Next Review:** After Idus validation study (Month 4-5)

**Change Log:**
- v1.0 - Initial comprehensive assessment with Idus, Agda/Visma, Flexite (December 2025)
- **v2.0 - COMPLETE PORTFOLIO: Added Ascendo assessment - All four systems now assessed (January 2026)**
- Pending: v3.0 after Idus validation study results

---

**📌 Four-System Portfolio Summary:**

**Excellence Tier (Maintain):**
- ✅ **Ascendo** - Best-in-class performance, zero waste, reference implementation
- ✅ **Agda/Visma** - Training needed (credible assessment, 75K SEK opportunity)

**Integration Tier (Invest):**
- 🔧 **Flexite** - Government integration needed (compliance-critical, 60-90K SEK savings)

**Investigation Tier (Validate First):**
- ⚠️ **Idus** - Validation study required (4.7M SEK claim unvalidated, 800K+ SEK investment at risk)

**🚨 Portfolio Risk:** 97% of identified waste concentrated in ONE system (Idus) with LOW data confidence. Do not commit 800K+ SEK investment without validation study. Three other systems performing well.

**🏆 Success Benchmark:** Ascendo proves seamless SAP integration is achievable at Kubal - use as reference for all system integration evaluations.

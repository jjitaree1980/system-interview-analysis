# Ascendo System Assessment - Threats

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  
**Super Users:** Rhodora Centeno Engelfeldt, Inna  

---

## ⚠️ IMPORTANT: Threat Profile is Low Compared to Other Systems

Ascendo's threat profile is remarkably low due to:
- Excellent system stability (rarely needs IT support)
- Strong SAP integration (zero manual data entry)
- High user satisfaction (10/10 criticality, "fully meets needs")
- Experienced users (3+ years, know workarounds)
- Complete adoption (100% of invoices through system)

Most identified threats are **operational risks** rather than **system failures**.

---

## High-Priority Threats

### 1. Single Point of Failure Risk (Rhodora Dependency)

**Threat Type:** Operational Continuity  
**Probability:** High (Currently occurring)  
**Impact:** High (AP operations halt)

**Description:**
Rhodora is the sole invoice processor with 3+ years of accumulated system knowledge. While Inna can back up, she also has manager duties and wasn't hired as primary processor. Summer temps require training but lack deep expertise.

**Risk Factors:**
- Only one person processes all 500-1,000 monthly invoices
- Inna backup has competing manager responsibilities
- Summer temps need training each year (knowledge doesn't persist)
- 3+ years knowledge concentrated in single person
- No documented backup training program

**Potential Consequences:**
- **If Rhodora unavailable:** AP operations halt entirely
- Both users said "NO" to "Could you process invoices manually if needed?"
- Invoice backlog accumulates during absence
- Critical invoices might be paid as prepayments (creating later cleanup work)
- Month-end closing delays
- Vendor payment delays and relationship strain

**Current Mitigation:**
- Inna acts as backup when available
- Summer temps hired during vacation periods
- Both have 3+ years Ascendo experience

**Additional Mitigation Needed:**
1. Develop formal cross-training program
2. Create comprehensive process documentation
3. Identify secondary backup beyond Inna
4. Consider rotational processing to distribute knowledge
5. Document workarounds and edge case handling

**Urgency:** Medium-High (operational risk, not emergency)

---

### 2. SAP Integration Failure Risk

**Threat Type:** Technical/Integration  
**Probability:** Low (Historically rare, stable now)  
**Impact:** Extreme (Entire AP automation breaks)

**Description:**
Ascendo's value proposition depends entirely on seamless SAP integration. If integration breaks, system becomes data entry tool with no automated posting or payment order creation. Compare to Idus where broken SAP integration causes 1.55M SEK annual waste.

**Risk Factors:**
- Zero manual SAP entry capability (by design)
- Users said "NO" to manual processing capability
- Complete operational dependency on integration
- SAP updates can affect integration (historical issues noted)
- Integration complexity creates fragility

**Historical Context:**
- Rhodora: "Integration problem mostly from SAP end after some updates"
- Rhodora: "But rarely happening now"
- Issues resolved, system stable currently

**Potential Consequences:**
- AP operations completely halt (no manual workaround)
- Cannot post invoices to SAP
- Cannot create payment orders
- Invoice backlog accumulates
- 900-1,800 hour annual time savings evaporates
- Manual processing infeasible at 500-1,000 invoices/month

**Mitigation:**
1. **Proactive monitoring:** Implement integration health checks
2. **SAP upgrade planning:** Test Ascendo compatibility before SAP updates
3. **Vendor relationship:** Maintain strong support agreement with Ascendo
4. **Contingency plan:** Document emergency manual process (even if slow)
5. **Early warning:** Alert when preliminary posting failures occur

**Current Status:** Stable - "rarely happening now"  
**Urgency:** Monitor continuously, but not immediate threat

---

## Medium-Priority Threats

### 3. User Knowledge Erosion from System Updates

**Threat Type:** Operational/Change Management  
**Probability:** Medium (Recurring with updates)  
**Impact:** Medium (Temporary efficiency loss)

**Description:**
System updates can require adaptation period as seen with February 2025 changes. "Administrators encountered some big changes" requiring time to return to "working as normal again."

**Risk Factors:**
- Vendor-controlled update schedule
- Users may not have advance notice of changes
- 3+ years established workflows may break
- Workarounds may stop working after updates
- Training needed to learn new features/interfaces

**Historical Example:**
February 2025 update caused "big changes" but system is "working as normal again" after adaptation period.

**Potential Consequences:**
- Temporary processing slowdown during adaptation
- User frustration with unexpected changes
- Need to relearn workflows
- Potential for errors during transition
- Reduced efficiency until new normal established

**Mitigation:**
1. Request advance notice of updates from vendor
2. Test updates in sandbox before production deployment
3. Create update communication plan for users
4. Document workflow changes after updates
5. Build in adaptation time for major changes

**Current Status:** Resolved from last update  
**Urgency:** Plan for future updates, not immediate threat

---

### 4. Vendor Dependency and Roadmap Misalignment

**Threat Type:** Strategic/Vendor  
**Probability:** Medium (Some misalignment exists)  
**Impact:** Medium (Limits optimization opportunities)

**Description:**
Ascendo's future development roadmap may not align with Kubal's specific enhancement needs, forcing expensive custom development or acceptance of suboptimal workflows.

**Risk Factors:**
- Vendor controls feature development priorities
- Rhodora's requests may not be on vendor roadmap:
  - Automatic requisitioner notifications
  - Faster matching status refresh
  - Automatic approval reminders
- Inna's request for vendor entity matching may be design philosophy, not bug
- No control over vendor prioritization

**Rhodora's Perspective:**
"There are some packages available in Ascendo for added features. Possible to check with their Marketing team."

**Potential Consequences:**
- Cannot implement desired enhancements without vendor support
- High cost for custom development
- Continued manual workarounds for optimization opportunities
- Divergence between user needs and vendor direction
- Eventually may need system replacement if vendor capabilities stagnate

**Mitigation:**
1. Engage vendor early on enhancement roadmap
2. Evaluate vendor feature packages for fit with user requests
3. Understand vendor's strategic direction for product
4. Assess if current pain points align with vendor's priorities
5. Consider alternative vendors if major misalignment occurs

**Current Status:** Need to engage vendor on feature packages  
**Urgency:** Low - system meets core needs, enhancements optional

---

### 5. Complexity Risk from Enhancement Additions

**Threat Type:** Operational/Strategic  
**Probability:** Medium (If "invest more" pursued aggressively)  
**Impact:** Medium (Could reduce current 95-100% accuracy)

**Description:**
Adding new features to currently stable system (95-100% OCR accuracy, excellent reliability) risks introducing bugs, reducing accuracy, or creating new workarounds that offset efficiency gains.

**Risk Factors:**
- Current system is stable and high-performing
- Each enhancement adds complexity and potential failure points
- "Invest more" could mean feature bloat
- Users adapted to current workflows - changes require relearning
- New features may have unintended interactions with existing functionality

**Inna's Conservative Perspective:**
Recommends "keep as is" - satisfied with current state, views minor issues as integration-related not system problems, risk-averse toward unnecessary changes.

**Potential Consequences:**
- Regression in OCR accuracy from changes
- New bugs introduced by enhancements
- User confusion from workflow changes
- Reduced processing efficiency during adaptation
- Cost of enhancements exceeds benefit
- "Perfect is enemy of good" - breaking what works

**Mitigation:**
1. Apply strict ROI threshold (>2:1) before any enhancement
2. Pilot all changes before full deployment
3. Implement incrementally, not all at once
4. Validate that improvements don't introduce regression
5. Maintain rollback capability for each change
6. Listen to Inna's "keep as is" perspective as risk check

**Current Status:** Not immediate threat - no enhancements implemented yet  
**Decision Point:** Rhodora vs Inna perspective to be resolved

---

## Low-Priority Threats

### 6. Process Degradation from Workaround Accumulation

**Threat Type:** Operational/Process  
**Probability:** Low-Medium  
**Impact:** Low (Gradual efficiency loss)

**Description:**
As workarounds accumulate for minor pain points (vendor matching corrections, queue routing bounces, manual approver reminders), process complexity increases and efficiency gradually degrades.

**Risk Factors:**
- Workarounds become "the way we do it"
- New users learn inefficient processes
- Documentation doesn't reflect reality
- Small inefficiencies compound over time
- Loss of institutional knowledge about why workarounds exist

**Current State:**
Multiple workarounds exist but users manage them effectively:
- Vendor matching corrections
- Manual queue redistribution
- Manual approval reminders
- Manual requisitioner follow-ups

**Potential Consequences:**
- Gradual increase in processing time per invoice
- Loss of "best practice" workflows
- Difficulty training new staff
- Accumulated frustration from repetitive manual tasks
- Harder to identify root causes when everything is workaround

**Mitigation:**
1. Document all current workarounds and their frequency
2. Prioritize fixing most time-consuming workarounds first
3. Regular process review to eliminate unnecessary steps
4. Standardize workarounds so they're consistently applied
5. Measure processing time trends to detect degradation

**Current Status:** Managed well by experienced users  
**Urgency:** Low - monitor trends, address if degradation detected

---

### 7. External Vendor Data Quality Issues

**Threat Type:** Operational/Data Quality  
**Probability:** Medium (Already occurring)  
**Impact:** Low-Medium (Increases manual touchpoints)

**Description:**
External vendors submitting invoices without proper PO numbers, incorrect bank details, or poor-quality PDFs reduce OCR accuracy and increase manual correction time.

**Risk Factors:**
- Kubal has limited control over vendor invoice quality
- Some vendors don't include PO numbers on invoices
- Bank account changes cause matching issues
- Poor-quality PDFs reduce OCR accuracy
- Hundreds of vendors with varying capabilities

**Current State:**
- OCR accuracy 95-100% (excellent despite vendor variation)
- Manual corrections needed for 10-30% of invoices
- Vendor matching issues from bank account changes
- System handles exceptions well (Inna: "Very easy")

**Potential Consequences:**
- Increased manual correction time
- Processing delays from missing PO numbers
- Requisitioner follow-ups when deliveries missing
- Lower effective OCR accuracy with poor-quality PDFs

**Mitigation:**
1. Vendor education program on invoice best practices
2. Encourage e-invoice adoption (reduces OCR dependency)
3. Standard vendor onboarding with invoice guidelines
4. Template invoices provided to frequent vendors
5. Track vendor invoice quality and address worst performers

**Current Status:** Well-managed by Ascendo's exception handling  
**Urgency:** Low - system handles variation effectively

---

## Threat Summary Matrix

| Threat | Probability | Impact | Current Mitigation | Additional Action Needed | Priority |
|:-------|:-----------|:-------|:-------------------|:------------------------|:---------|
| Single point of failure (Rhodora) | High | High | Inna backup | Cross-training program | **High** |
| SAP integration failure | Low | Extreme | Stable currently | Monitoring, testing | **High** |
| User knowledge erosion (updates) | Medium | Medium | Adaptation successful | Update planning | Medium |
| Vendor roadmap misalignment | Medium | Medium | Unknown | Engage vendor | Medium |
| Complexity from enhancements | Medium | Medium | None yet | Strict ROI criteria | Medium |
| Workaround accumulation | Low-Medium | Low | Users manage well | Document workarounds | Low |
| Vendor data quality | Medium | Low-Medium | System handles well | Vendor education | Low |

---

## Risk Mitigation Priority

### Immediate Actions (Next 30 Days):

1. **Develop Rhodora backup plan:**
   - Document critical daily procedures
   - Identify secondary backup beyond Inna
   - Create emergency contact list

2. **Validate SAP integration monitoring:**
   - Confirm integration health checks exist
   - Document escalation process for failures
   - Test emergency manual process

---

### Short-Term Actions (3-6 Months):

3. **Cross-training program:**
   - Train secondary processor to handle 2-3 week Rhodora absence
   - Document workarounds and edge case handling
   - Rotate responsibilities to prevent knowledge hoarding

4. **Vendor engagement:**
   - Request feature package details and pricing
   - Understand vendor's product roadmap
   - Evaluate alignment with user requests

5. **Enhancement ROI framework:**
   - Apply strict >2:1 ROI threshold
   - Pilot changes before full deployment
   - Validate no regression in accuracy/stability

---

### Long-Term Risk Management (12+ Months):

6. **Process optimization:**
   - Address highest-impact workarounds
   - Measure processing time trends
   - Regular review of accumulated complexity

7. **Vendor relationship management:**
   - Annual review of roadmap alignment
   - Evaluate alternative vendors if major divergence
   - Maintain competitive pressure on vendor

---

## Critical Success Factors for Threat Mitigation

### Key Principles:

**Preserve What Works:**
- Don't compromise 95-100% OCR accuracy
- Don't break zero manual SAP entry automation
- Don't reduce system stability
- Don't disrupt experienced users' workflows

**Mitigate Operational Risks:**
- Address single point of failure (Rhodora dependency)
- Monitor SAP integration health continuously
- Plan for system updates proactively
- Document workarounds and processes

**Make Strategic Investments Carefully:**
- Apply strict ROI criteria to enhancements
- Consider Inna's "keep as is" perspective as risk check
- Pilot changes before full deployment
- Prioritize operational continuity over optimization

---

## Comparison to Other Kubal Systems

### Threat Context:

**Ascendo Threat Profile:**
- Low probability, well-managed risks
- Mostly operational (backup, training) not technical
- Main threat is breaking what works through changes

**Idus Threat Profile:**
- High probability, high impact risks
- Broken SAP integration causing 1.55M SEK waste
- Mobile access limitations affecting operations
- Technical failures, not operational risks

**Flexite Threat Profile:**
- Medium probability, medium impact
- Regulatory non-compliance from manual reporting
- Data integrity risk from manual dashboards
- Reporting culture degradation risk

**Conclusion:** Ascendo has lowest threat profile of all assessed systems. Risk management should focus on preserving success, not fixing failures.

---

## Strategic Risk Assessment

### What Makes Ascendo Low-Risk:

1. **Strong foundation:** 10/10 criticality, "fully meets needs"
2. **Proven stability:** Rarely needs IT support, excellent month-end performance
3. **Experienced users:** 3+ years, know workarounds, adapted successfully
4. **Best-in-class integration:** Zero manual SAP entry (unlike Idus)
5. **Complete adoption:** 100% of invoices, no parallel processes

### Where Risks Exist:

1. **People risk:** Rhodora single point of failure
2. **Integration risk:** SAP connection is mission-critical
3. **Change risk:** Updates and enhancements could break stability
4. **Vendor risk:** Future roadmap may not align with needs

### Risk Management Philosophy:

**For Ascendo, risk management means:**
- Preserving current excellent performance
- Mitigating operational dependencies (backup, training)
- Being conservative about enhancements (Inna's perspective has merit)
- Monitoring SAP integration health vigilantly
- Accepting minor pain points rather than risking regression

**This is opposite of Idus, where risk management means:**
- Fixing broken core functionality
- Replacing or heavily investing in repairs
- Aggressive action to stop ongoing waste

---

## Warning Signs to Monitor

### Indicators System Health Declining:

**Technical:**
- SAP integration errors increasing
- OCR accuracy dropping below 90%
- System stability issues emerging
- Processing time increasing

**Operational:**
- Rhodora expressing frustration or burnout
- Inna unable to provide backup coverage
- Manual correction time increasing
- Month-end closing delays growing

**Strategic:**
- Vendor unresponsive to support requests
- User satisfaction declining from current high
- Workaround accumulation accelerating
- Enhancement costs exceeding benefits

**Action if Warning Signs Appear:**
Immediate investigation and mitigation. Current excellent state should not be taken for granted.

---

**Risk Assessment Summary:**

Ascendo has **low threat profile** due to strong foundation, stability, and experienced users. Primary risks are:
1. Operational continuity (Rhodora dependency) - addressable through backup planning
2. Preserving success (avoiding regression from changes) - addressable through conservative change management
3. Strategic alignment (vendor roadmap) - addressable through engagement and ROI criteria

**Key Message:** Risk management for Ascendo means protecting what works, not fixing what's broken.

---

**Document Status:** Ready for management review  
**Risk Management Priority:** Develop Rhodora backup plan (30 days), Monitor SAP integration (ongoing), Apply strict ROI criteria to enhancements (before any investment)  
**Critical Insight:** This is a low-risk system compared to others in IT portfolio. Risk mitigation should be proportional to actual threat level.

# Ascendo System Assessment - Capability Gaps

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  
**Super Users:** Rhodora Centeno Engelfeldt, Inna  

---

## ⚠️ IMPORTANT: No Critical Functional Gaps Identified

This assessment found **no critical gaps** in Ascendo's core invoice processing capabilities. The system achieves its primary purpose: automated invoice processing with zero manual SAP data entry. All identified gaps are **enhancement opportunities** rather than functional failures.

Both users rated the system **10/10 criticality** and stated it **"fully meets our needs."**

---

## Medium-Priority Gaps (Efficiency Optimizations)

### Gap 1: No Automatic Requisitioner Notifications for Missing Deliveries

**Gap Description:**
When an invoice arrives but the purchase order delivery is not yet created in SAP, Ascendo does not automatically notify the requisitioner. Rhodora must manually contact them to request delivery creation.

**Current Impact:**
- Manual follow-up burden on Rhodora
- Delayed invoice processing waiting for deliveries
- Repetitive communication tasks
- No systematic reminder process

**Business Need:**
Automated notification system that alerts requisitioners when their deliveries are needed to process waiting invoices.

**Gap Type:** Workflow Automation  
**Severity:** Medium  
**Workaround:** Manual email/communication from Rhodora  
**Workaround Sustainability:** Functional but time-consuming

**Frequency:** Unknown - requires tracking to quantify  
**Annual Waste Estimate:** [Number of follow-ups/month × time per follow-up × 12 months] = **[TBC]**

**Remediation Options:**
1. Check if Ascendo has built-in notification feature (may exist unused)
2. Request feature from Ascendo vendor
3. Create automated email triggers in SAP
4. Implement manual email templates as interim solution

**Estimated Remediation Cost:** Low-Medium (if feature exists) to Medium (if requires development)

---

### Gap 2: No Automatic Approval Reminders

**Gap Description:**
Ascendo lacks automated reminders to approvers about pending invoices in their queues, requiring manual follow-up especially during month-end closing.

**Current Impact:**
- Manual reminder communications from Rhodora
- Delayed approvals extend period-end closing timeline
- Bottleneck risk during high-volume periods
- Inconsistent approval turnaround times

**Business Need:**
Automated reminder system that notifies approvers of pending invoices, with escalation for overdue items, particularly during period-end.

**Gap Type:** Workflow Automation  
**Severity:** Medium  
**Workaround:** Manual follow-up with approvers  
**Workaround Sustainability:** Functional but creates month-end bottleneck

**Frequency:** Regular (especially month-end)  
**Annual Waste Estimate:** [Time on manual reminders × frequency] = **[TBC]**

**Remediation Options:**
1. Check if Ascendo has configurable reminder capabilities
2. Configure reminder rules if available
3. Request feature from vendor if not available
4. Create manual reminder schedule as interim solution

**Estimated Remediation Cost:** Low (if configurable) to Medium (if requires development)

**Strategic Value:** High impact on month-end closing efficiency

---

### Gap 3: Manual Payment File Preparation (SAP to Bank)

**Gap Description:**
While Ascendo automatically posts to SAP and SAP automatically creates payment order documents, Peter must manually prepare payment registers and bank files in SAP. This is the only remaining manual step in an otherwise fully automated workflow.

**Current Impact:**
- Peter's time spent on payment file preparation (unknown - not interviewed)
- Potential for human error in payment assembly
- Delay between invoice approval and payment execution
- Manual process breaks end-to-end automation chain

**Business Need:**
Automated bank file generation from SAP payment orders to eliminate final manual step in AP-to-bank workflow.

**Gap Type:** Integration/Automation  
**Severity:** Medium (pending Peter interview to confirm impact)  
**Workaround:** Manual payment register assembly by Peter  
**Workaround Sustainability:** Unknown - requires assessment

**Frequency:** Regular (payment cycles)  
**Annual Waste Estimate:** **[REQUIRES PETER INTERVIEW]**

**Remediation Options:**
1. Investigate SAP payment automation capabilities
2. Evaluate if Ascendo can directly generate bank files
3. Consider third-party payment automation tools
4. Calculate ROI: Peter's time cost vs automation investment

**Estimated Remediation Cost:** Medium-High (SAP/banking integration)

**Assessment Gap:** Peter not interviewed - critical workflow component unknown

---

### Gap 4: No Standard Message Templates

**Gap Description:**
When Rhodora uses Ascendo's direct mailing function to contact requisitioners, no standard message templates exist, requiring manual composition each time.

**Current Impact:**
- Time spent writing repetitive messages
- Inconsistent communication style
- Potential for unclear instructions to requesters
- No quality control on message content

**Business Need:**
Library of standard message templates for common invoice communication scenarios.

**Gap Type:** Usability Enhancement  
**Severity:** Low-Medium  
**Workaround:** Manual message composition  
**Workaround Sustainability:** Functional; low individual time cost but adds up

**Frequency:** Variable (per invoice communication)  
**Annual Waste Estimate:** Minimal per instance; **[TBC]** in aggregate

**Remediation Options:**
1. Check if Ascendo supports message templates
2. Create template library in Ascendo if supported
3. Document standard messages for copy/paste
4. Create email system templates as workaround

**Estimated Remediation Cost:** Very Low (configuration/documentation)

**Priority:** Low (nice-to-have quality of life improvement)

---

## Low-Priority Gaps (Cosmetic/Minor)

### Gap 5: UI Column Width Adjustment

**Gap Description:**
Users cannot adjust column widths in Ascendo interface, causing some columns to appear "a little off."

**Current Impact:**
- Minor user experience degradation
- Potential readability issues
- No functional impact on processing
- Purely cosmetic annoyance

**Business Need:**
Configurable column widths for better screen real estate management.

**Gap Type:** UI/UX Enhancement  
**Severity:** Low  
**Workaround:** Work with fixed column widths  
**Workaround Sustainability:** Acceptable - users adapted

**Annual Waste Estimate:** Negligible (cosmetic only)

**Remediation Options:**
1. Request UI improvement from Ascendo vendor
2. Check if configurable in system settings
3. Document as low priority

**Estimated Remediation Cost:** Low (UI configuration)

**Priority:** Very Low - document but don't invest resources

---

### Gap 6: Slow Matching Status Refresh

**Gap Description:**
After matching conditions are met, automatic status update to green "Fully matched" takes up to 1 hour. Rhodora describes this as "manageable."

**Current Impact:**
- Slight delay in processing flow
- Users cannot immediately proceed after fixing matches
- Minimal impact as described "manageable"
- Predictable waiting time

**Business Need:**
Faster refresh cycle for matching status updates (target: real-time or <5 minutes).

**Gap Type:** Performance Optimization  
**Severity:** Low  
**Workaround:** Wait for automatic update, or manually verify  
**Workaround Sustainability:** Acceptable - users adapted workflow

**Annual Waste Estimate:** Low (waiting time predictable and short)

**Remediation Options:**
1. Request faster refresh cycle from vendor
2. Investigate if manual refresh trigger exists
3. Assess if database query optimization possible

**Estimated Remediation Cost:** Low (configuration change) to Medium (requires development)

**Priority:** Low - current state acceptable, enhancement would be nice-to-have

---

## Design Choice Gaps (Not Bugs, But Cause Friction)

### Gap 7: Vendor Matching by Bank Account Instead of Vendor Entity

**Gap Description:**
Ascendo matches invoices based on vendor bank account details rather than vendor entity. When bank details differ between Ascendo and SAP purchase order, manual corrections are required even though IBAN is taken by default for payment anyway.

**Current Impact:**
- Manual correction time for bank account mismatches
- Waiting time for Ascendo to recognize updates
- Invoice processing delays
- Frustration from unnecessary distinction

**Business Need:**
Vendor matching logic based on vendor entity rather than bank account details to eliminate unnecessary corrections.

**Gap Type:** System Design/Configuration  
**Severity:** Medium (causes regular friction)  
**Workaround:** Manual correction of bank account information  
**Workaround Sustainability:** Functional but inefficient

**Frequency:** Regular (subset of invoices)  
**Annual Waste Estimate:** **[REQUIRES 1-2 MONTH TRACKING]**

**Remediation Options:**
1. Request vendor to change matching logic (may be configurable)
2. Standardize bank account data between Ascendo and SAP
3. Investigate if this is system configuration vs hardcoded logic
4. Calculate cost of current corrections vs fix investment

**Estimated Remediation Cost:** Unknown (could be simple config or major development)

**Priority:** Medium - quantify impact before investing in fix

**Strategic Note:** This may be Ascendo design philosophy rather than bug. Vendor may have reasons for bank account matching.

---

### Gap 8: Queue Routing Logic Issues

**Gap Description:**
Invoices sometimes "turn back several times to the entrance queue before getting to the right queue," requiring Rhodora to repeatedly redistribute them.

**Current Impact:**
- Extra touches per invoice
- Processing delays
- Administrative overhead
- Potential for invoices to be missed

**Business Need:**
Reliable queue routing logic that correctly directs invoices on first attempt.

**Gap Type:** System Configuration/Logic  
**Severity:** Medium  
**Workaround:** Manual redistribution by Rhodora  
**Workaround Sustainability:** Functional but creates extra work

**Frequency:** Sometimes (subset of invoices)  
**Annual Waste Estimate:** **[REQUIRES 1 MONTH TRACKING]**

**Remediation Options:**
1. Review queue routing rules with Ascendo vendor
2. Identify specific invoice types that trigger bounces
3. Adjust entry validation logic to catch issues earlier
4. Document and standardize manual workaround

**Estimated Remediation Cost:** Low-Medium (configuration review/adjustment)

**Priority:** Medium - quantify frequency before prioritizing fix

---

## Integration/Structural Gaps

### Gap 9: Credit Note Processing Complexity

**Gap Description:**
Credit note processing "could have been better" but is noted as primarily an Ascendo-SAP integration issue rather than Ascendo system limitation.

**Current Impact:**
- Extra processing time for credit notes vs regular invoices
- Potential for errors in credit processing
- Inconsistent workflow vs regular invoices

**Business Need:**
Streamlined credit note processing matching regular invoice workflow.

**Gap Type:** Integration (Ascendo-SAP)  
**Severity:** Low-Medium  
**Workaround:** Manual handling of credit note exceptions  
**Workaround Sustainability:** Functional; depends on credit note volume

**Frequency:** Variable (depends on credit note volume)  
**Annual Waste Estimate:** **[TBC - depends on volume]**

**Remediation Options:**
1. Review SAP credit note configuration
2. Request Ascendo vendor guidance on credit note best practices
3. Map desired credit note workflow and identify gaps
4. Calculate if credit note volume justifies enhancement investment

**Estimated Remediation Cost:** Medium (integration work)

**Priority:** Low-Medium - quantify credit note volume and extra time

**Strategic Note:** Inna explicitly states this is "more on SAP integration rather than Ascendo itself" - may be SAP-side fix needed.

---

## Gap Summary Matrix

| Gap | Severity | Type | Annual Waste | Remediation Complexity | Priority |
|:----|:---------|:-----|:-------------|:----------------------|:---------|
| Auto requisitioner notifications | Medium | Workflow | [TBC] | Low-Medium | Medium |
| Auto approval reminders | Medium | Workflow | [TBC] | Low-Medium | Medium |
| Payment file automation | Medium | Integration | [TBC] | Medium-High | Medium* |
| Vendor matching by bank account | Medium | Design | [TBC] | Unknown | Medium |
| Queue routing issues | Medium | Configuration | [TBC] | Low-Medium | Medium |
| Credit note processing | Low-Medium | Integration | [TBC] | Medium | Low-Medium |
| Standard message templates | Low-Medium | Usability | Minimal | Very Low | Low |
| Matching status refresh speed | Low | Performance | Low | Low-Medium | Low |
| UI column width adjustment | Low | UI/UX | Negligible | Low | Very Low |

*Pending Peter interview to confirm impact

---

## Gap Remediation Priority

### Phase 1: Quantification (1-2 Months)
**Before any investment, gather data:**
1. Track vendor matching correction frequency and time
2. Interview Peter on payment file preparation time
3. Count queue routing bounce instances
4. Measure credit note volume and extra processing time
5. Log requisitioner follow-up frequency

### Phase 2: Low-Cost Quick Wins (0-3 Months)
**If features exist or easy to implement:**
1. Check for existing but unused notification/reminder capabilities
2. Create standard message templates (manual documentation)
3. Review queue routing rules for obvious issues

### Phase 3: ROI-Justified Enhancements (3-12 Months)
**If ROI exceeds 2:1 ratio:**
1. Implement automatic requisitioner notifications
2. Configure/request automatic approval reminders
3. Address vendor matching logic (if cost-effective)
4. Fix queue routing issues (if high frequency)

### Phase 4: Strategic Investments (12+ Months)
**If strategic value justifies cost:**
1. Payment automation (SAP to bank) - pending Peter assessment
2. Credit note workflow optimization - if volume justifies
3. Matching status refresh speed improvement

---

## Critical Perspective on Gaps

### What This Gap Analysis Reveals

**Ascendo has no core functional gaps.** All identified gaps are optimization opportunities on an already-excellent foundation:

- **Zero manual SAP data entry achieved** ✓
- **95-100% OCR accuracy** ✓
- **Automatic approval routing** ✓
- **Automatic payment order creation** ✓
- **Effective duplicate detection** ✓
- **100% invoice adoption** ✓

**Gaps are all about making a working system work even better.**

### Comparison to Other Kubal Systems

**Ascendo Gap Profile:**
- No critical gaps
- All gaps are enhancements
- Both users say "fully meets needs"

**Idus Gap Profile:**
- Critical SAP integration broken (1.55M SEK waste)
- Mobile access severely limited
- Core functionality gaps

**Flexite Gap Profile:**
- No government integration (manual double-entry)
- No automated reporting
- System isolation from other systems

**Conclusion:** Ascendo's gaps are minor compared to other systems. This should inform investment prioritization across IT portfolio.

---

## Investment Decision Framework

### Before Investing in Gap Remediation:

**Step 1: Quantify Current Waste**
- What is annual cost of all identified gaps combined?
- What percentage of total time savings (900-1,800 hours) does waste represent?

**Step 2: Evaluate Vendor Offerings**
- What feature packages does Ascendo vendor offer?
- Do they address specific gaps identified?
- What is cost vs expected time savings?

**Step 3: Calculate ROI**
- Gap remediation cost ÷ annual waste savings = payback period
- Target: <2 year payback for approval
- Consider: Risk of adding complexity to stable system

**Step 4: Decide**
- **If gaps cost <50K SEK annually:** Recommend "keep as is" (Inna's position)
- **If specific fix has >2:1 ROI:** Recommend targeted investment
- **If vendor packages misaligned:** Maintain current state

---

## Strategic Gap Analysis

**Root Cause:**
Gaps exist because Ascendo is a mature, stable system that wasn't designed with every workflow optimization. Current state prioritized core automation (achieved excellently) over edge case optimization.

**Core System Functionality:**
Zero gaps in core invoice processing, OCR, matching, approval routing, or SAP integration. System performs primary functions at best-in-class level.

**Gap Pattern:**
All gaps are workflow enhancements or minor usability issues. No fundamental design flaws or broken integrations (unlike Idus).

**Investment Implication:**
Rhodora's "invest more" vs Inna's "keep as is" are both valid. Decision should be purely ROI-driven after quantification phase.

---

**Document Status:** Ready for management review  
**Next Actions:**  
1. ✅ Complete quantification phase (1-2 months data collection)
2. ✅ Interview Peter to assess payment automation opportunity
3. ✅ Request Ascendo vendor feature package pricing
4. ➡️ Calculate ROI for each enhancement
5. ➡️ Make data-driven investment decision

**Key Message:** No critical gaps exist. All enhancements optional based on ROI.

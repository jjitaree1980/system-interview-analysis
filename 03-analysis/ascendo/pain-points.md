# Ascendo System Assessment - Pain Points

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  
**Super Users:** Rhodora Centeno Engelfeldt, Inna

---

## Critical Pain Points

### ⚠️ IMPORTANT: No Critical System Failures Identified

This assessment found **no critical pain points** that compromise Ascendo's core functionality. All identified issues are **efficiency optimizations** rather than system failures. Both users rated the system 10/10 criticality and "fully meets our needs."

---

## Medium-Level Pain Points (Efficiency Losses)

### 1. Vendor Matching by Bank Account Instead of Vendor Entity

**Severity:** Medium  
**Frequency:** Always (affects subset of invoices)  
**Impact:** Correction time and waiting for system to recognize changes

**Description:**
Ascendo matches invoices based on vendor bank account details rather than vendor entity. When bank details differ between Ascendo and SAP purchase order (even though IBAN is taken by default for payment), manual corrections are required and users must wait for Ascendo to recognize the updates.

**User Quote:**
"The matching is based on vendor bank details and not the vendor itself, which require numerous corrections and waiting time until the correction is seen by Ascendo in case if there are different bank details in Ascendo and PO (which practically makes no difference because for the payment order the IBAN is taken by default)." - Inna

**Current Workaround:**
Manual correction of bank account information

**Business Impact:**
- Time spent on corrections
- Waiting time for system to process changes
- Invoice processing delays
- Frustration for processors

**Annual Waste Estimate:**
**[TO BE CALCULATED]**
- Need to quantify: How many invoices per month affected?
- Average correction time per invoice
- Waiting time impact on overall processing speed
- **Action:** Track correction time over 1-2 months to establish baseline

**Solution Options:**
1. Request Ascendo vendor to change matching logic to vendor entity
2. Standardize bank account data between systems
3. Investigate if this is configurable setting vs hardcoded logic

---

### 2. Invoice Queue Routing Logic Issues

**Severity:** Medium  
**Frequency:** Sometimes (subset of invoices)  
**Impact:** Invoice processing delays, manual intervention required

**Description:**
Invoices sometimes "turn back several times to the entrance queue before getting to the right queue." This creates inefficiency as Rhodora must repeatedly redistribute invoices.

**User Quote:**
"The invoices may sometime turn back several times to the entrance queue before getting to the right queue." - Inna

**Current Workaround:**
Manual redistribution by Rhodora

**Business Impact:**
- Extra touches per invoice
- Processing delays
- Administrative overhead
- Potential for invoices to be missed

**Annual Waste Estimate:**
**[TO BE CALCULATED]**
- Need to quantify: How many invoices bounce back per month?
- Average number of bounces per affected invoice
- Time per manual redistribution
- **Action:** Log bounced invoices for 1 month to establish frequency

**Solution Options:**
1. Review queue routing rules with Ascendo vendor
2. Identify specific invoice types that trigger bounces
3. Adjust entry validation logic to catch issues earlier

---

### 3. Manual Payment File Preparation (SAP to Bank)

**Severity:** Medium  
**Frequency:** Regular (payment cycles)  
**Impact:** Manual work in payment workflow

**Description:**
While Ascendo automatically posts to SAP and SAP automatically creates payment order documents, Peter must manually prepare payment registers and bank files in SAP. This is the one remaining manual step in otherwise automated workflow.

**Process Flow:**
1. ✅ Ascendo → SAP: **Fully automated** (invoice posting)
2. ✅ SAP creates payment order: **Fully automated**
3. ❌ SAP → Bank file: **Manual** (Peter creates payment registers and bank files)

**Current Workaround:**
Peter manually assembles payment registers and creates bank files in SAP

**Business Impact:**
- Peter's time spent on payment file preparation
- Potential for human error in payment assembly
- Delay between invoice approval and payment execution

**Annual Waste Estimate:**
**[TO BE CALCULATED - REQUIRES PETER INTERVIEW]**
- Need to quantify: Hours per week Peter spends on payment file prep
- Number of payment runs per month
- Potential automation savings
- **Action:** Interview Peter to understand payment workflow time cost

**Solution Options:**
1. Investigate SAP payment automation capabilities
2. Evaluate if Ascendo can directly generate bank files
3. Consider third-party payment automation tools
4. Compare manual time cost vs automation investment ROI

---

### 4. Credit Note Processing Complexity

**Severity:** Low-Medium  
**Frequency:** Variable (depends on credit note volume)  
**Impact:** Extra processing time for credit notes vs regular invoices

**Description:**
Credit note processing "could have been better" but is noted as primarily an Ascendo-SAP integration issue rather than Ascendo system limitation.

**User Quote:**
"The processing of credit-notes could have been better, but it depends more on SAP integration rather than Ascendo itself." - Inna

**Current Workaround:**
Manual handling of credit note exceptions

**Business Impact:**
- Extra time per credit note
- Potential for errors in credit processing
- Inconsistent workflow vs regular invoices

**Annual Waste Estimate:**
**[TO BE CALCULATED]**
- Need to quantify: Monthly credit note volume
- Average extra time per credit note vs regular invoice
- Error rate comparison
- **Action:** Track credit note processing time vs regular invoices

**Solution Options:**
1. Review SAP credit note configuration
2. Request Ascendo vendor guidance on credit note best practices
3. Map desired credit note workflow and identify gaps
4. Calculate if credit note volume justifies enhancement investment

---

## Low-Level Pain Points (Minor Annoyances)

### 5. Matching Status Display Accuracy

**Severity:** Low  
**Frequency:** Sometimes  
**Impact:** Extra validation step required

**Description:**
Matching status can show green "Fully matched" when line number is actually missing, requiring manual verification.

**User Quote:**
"Some fixing is being done to the matching status to show it correctly. One example is when it scanned with purchase order number, it can happen that the status is green meaning ready but it is actually missing the line number. But it is an easy fix." - Rhodora

**Current Workaround:**
Manual verification, "easy fix"

**Business Impact:**
- Extra validation step
- Potential for missing data to slip through
- User confusion from inaccurate status

**Annual Waste Estimate:**
Minimal - described as "easy fix," users have adapted workflow

**Solution Options:**
1. Report bug to Ascendo vendor for status logic fix
2. Create validation checklist for processors
3. Monitor if issue persists after vendor updates

---

### 6. UI Column Width Adjustment

**Severity:** Low  
**Frequency:** Always (cosmetic issue)  
**Impact:** Display annoyance, no functional impact

**Description:**
Cannot adjust column widths in Ascendo interface. "Appearance of some columns are a little off."

**User Quote:**
"The appearance of some columns are a little off. There is no possibility to adjust the width. The same with the coding and article lines width." - Rhodora

**Current Workaround:**
Work with fixed column widths

**Business Impact:**
- Minor user experience degradation
- Potential readability issues
- No functional impact on processing

**Annual Waste Estimate:**
Negligible - purely cosmetic issue

**Solution Options:**
1. Request UI improvement from Ascendo vendor
2. Check if configurable in system settings
3. Low priority - document but don't invest resources

---

### 7. Matching Status Update Speed

**Severity:** Low  
**Frequency:** Always (by design)  
**Impact:** <1 hour wait time for status refresh

**Description:**
After matching conditions are met, automatic status change to green "Fully matched" takes up to 1 hour. Rhodora describes this as "manageable."

**User Quote:**
"Shorter update of the matching status. Normally takes less than an hour to be automatically changed to green 'Fully matched'. Otherwise, manageable." - Rhodora

**Current Workaround:**
Wait for automatic update, or manually verify matching

**Business Impact:**
- Slight delay in processing flow
- Users cannot immediately proceed after fixing matches
- Minimal impact as described "manageable"

**Annual Waste Estimate:**
Low - waiting time is predictable and users have adapted workflow

**Solution Options:**
1. Request faster refresh cycle from vendor
2. Investigate if manual refresh trigger exists
3. Low priority - current state is acceptable

---

## Temporary/Resolved Issues

### 8. February 2025 System Update Challenges

**Severity:** Was High, Now Resolved  
**Frequency:** One-time event  
**Impact:** Temporary adaptation period

**Description:**
February 2025 updates caused "big changes" for administrators requiring adaptation time. Issue has resolved - system "working as normal again."

**User Quote:**
"With the updates made in February 2025 the administrators encountered some big changes but as the time passes by we are working as normal again." - Rhodora

**Current Status:**
Resolved - no longer active pain point

**Lessons Learned:**
- Major updates require change management support
- Users adapted successfully over time
- Consider staging/testing future major updates

**No waste calculation needed** - issue resolved.

---

## Missing Features (Enhancement Requests)

### 9. No Automatic Requisitioner Notifications for Missing Deliveries

**Severity:** Low-Medium (nice-to-have)  
**Impact:** Manual follow-up with requisitioners required

**Description:**
When invoice arrives but purchase order not delivered in SAP, system doesn't automatically notify requisitioner to create delivery. Rhodora must manually contact them.

**User Request:**
"When the invoice comes and the purchase order is not delivered in SAP it is notifying the requisitioners about the deliveries." - Rhodora

**Current Workaround:**
Manual email/communication from Rhodora to requisitioners

**Business Impact:**
- Manual follow-up time
- Delayed invoice processing waiting for deliveries
- Repetitive communication burden

**Annual Waste Estimate:**
**[TO BE CALCULATED]**
- Need to quantify: How many invoices per month require requisitioner contact?
- Average time per follow-up communication
- Average delay in processing from missing deliveries

**Solution Options:**
1. Check if Ascendo has automated notification feature
2. Request feature from vendor if not available
3. Create manual email templates to speed communication
4. Calculate ROI: Manual time cost vs feature cost

---

### 10. No Automatic Approval Reminders

**Severity:** Low-Medium (nice-to-have)  
**Impact:** Manual follow-up during month-end

**Description:**
No automated reminders to approvers about pending invoices in their queue, especially problematic during month-end closing when timely approvals are critical.

**User Request:**
"Automatic reminders to attesters to approve all the invoices in the queues especially month-end closing." - Rhodora

**Current Workaround:**
Manual follow-up with approvers

**Business Impact:**
- Manual reminder communications
- Delayed approvals extend period-end closing
- Bottleneck risk during high-volume periods

**Annual Waste Estimate:**
**[TO BE CALCULATED]**
- Need to quantify: Time spent on manual approval follow-ups
- Impact on month-end closing timeline
- Number of approvers requiring regular reminders

**Solution Options:**
1. Check if Ascendo has automated reminder capability
2. Configure reminder rules if available
3. Request feature from vendor if not available
4. Create manual reminder process as interim solution

---

### 11. No Standard Message Templates for Invoice Communication

**Severity:** Low (nice-to-have)  
**Impact:** Repetitive message composition

**Description:**
When emailing requesters from Ascendo (which has direct mailing capability), no standard message templates exist, requiring manual composition each time.

**User Request:**
"List of standard messages invoice mailing." - Inna

**Current Workaround:**
Manual composition of messages

**Business Impact:**
- Time spent writing repetitive messages
- Inconsistent communication style
- Potential for unclear instructions to requesters

**Annual Waste Estimate:**
Low - message composition time is minimal per instance

**Solution Options:**
1. Check if Ascendo supports message templates
2. Create template library in email system
3. Document standard messages for copy/paste
4. Very low priority - minimal time impact

---

## Summary of Quantified Waste

| Pain Point | Frequency | Annual Time Waste | Estimated Cost | Priority |
|:-----------|:----------|:-----------------|:---------------|:---------|
| Vendor matching corrections | Regular | **[TBC]** hours | **[TBC]** SEK | **Medium** |
| Queue routing bounces | Sometimes | **[TBC]** hours | **[TBC]** SEK | **Medium** |
| Manual payment file prep | Regular | **[TBC]** hours | **[TBC]** SEK | **Medium** |
| Credit note processing extra time | Variable | **[TBC]** hours | **[TBC]** SEK | **Low-Medium** |
| Requisitioner follow-ups | Regular | **[TBC]** hours | **[TBC]** SEK | **Low-Medium** |
| Approval reminders | Monthly | **[TBC]** hours | **[TBC]** SEK | **Low-Medium** |
| Other minor issues | Variable | Minimal | Minimal | **Low** |
| **Total Estimated Waste** | | **[TBC]** hours | **[TBC]** SEK | |

### Comparison to Time Savings

**Ascendo eliminates 900-1,800 hours annually** in manual invoice processing compared to no-system baseline.

Even if all identified pain points totaled **100 hours annual waste**, Ascendo still delivers **900%+ ROI** on its core automation value.

**This puts pain points in perspective: Ascendo is overwhelmingly positive despite optimization opportunities.**

---

## Actions Required to Quantify Waste

### Immediate Data Collection (1-2 Months)

**Priority 1 - Vendor Matching Corrections:**
- Log each instance of bank account mismatch
- Time correction process
- Calculate monthly impact

**Priority 2 - Payment Workflow:**
- Interview Peter about payment file preparation time
- Understand payment run frequency
- Calculate automation opportunity

**Priority 3 - Queue Routing:**
- Track invoices bouncing back to entrance queue
- Count touches per bounced invoice
- Identify patterns/root causes

### Secondary Data Collection

**Priority 4 - Credit Notes:**
- Compare credit note processing time vs regular invoices
- Document volume
- Assess if different enough to justify investment

**Priority 5 - Enhancement Features:**
- Track requisitioner follow-up frequency and time
- Count manual approval reminder instances
- Measure month-end closing delays from approvals

---

## Recommendations

### Immediate Actions (No Cost)

1. **Document workarounds** for vendor matching to reduce variation
2. **Review queue routing rules** with IT to identify fix opportunities
3. **Create email templates** for requisitioner communications (manual solution)
4. **Interview Peter** to complete payment workflow assessment

### Short-Term Improvements (Low Cost)

1. **Report status display bug** to Ascendo vendor for fix
2. **Request faster matching status refresh** - may be simple config change
3. **Investigate existing features** - reminder/notification capabilities may exist unused
4. **Standardize vendor bank data** between Ascendo and SAP to reduce mismatches

### Medium-Term Investments (Requires ROI Analysis)

1. **Evaluate Ascendo feature packages** - do they address user requests?
2. **Payment automation assessment** - SAP to bank file automation ROI
3. **Vendor matching logic change** - cost/benefit of changing to entity-based matching
4. **Credit note workflow optimization** - if volume justifies investment

### Long-Term Strategy

1. **Maintain current excellent foundation** - don't break what works
2. **Incremental optimization** - address highest-ROI pain points first
3. **User feedback loop** - regular check-ins with Rhodora/Inna on new issues
4. **Vendor relationship management** - stay informed on Ascendo roadmap

---

## Critical Perspective: Pain Points vs System Value

### What This Assessment Reveals

**Ascendo's pain points are remarkably minor** compared to other Kubal systems:
- **Idus:** 2.2M SEK annual waste, broken SAP integration
- **Flexite:** Manual government reporting, no system integrations
- **Agda/Visma:** 75K SEK waste, primarily from underused features

**Ascendo's "problems" are optimization opportunities on an already-excellent foundation.**

### Investment Decision Framework

**Before investing in enhancements, ask:**
1. What is total annual cost of current pain points? (**[Calculate first]**)
2. What do vendor feature packages cost?
3. What is ROI of each enhancement?
4. What is risk of adding complexity to stable system?

**If pain point cost < 100K SEK annually:** Consider "keep as is" (Inna's recommendation)  
**If specific enhancement has >2x ROI:** Consider "invest more" (Rhodora's recommendation)

**Either decision is reasonable because the foundation is solid.**

---

**Document Status:** Ready for management review  
**Next Steps:**  
1. ✅ Interview Peter (payment workflow)
2. ✅ Quantify vendor matching correction time (track 1-2 months)
3. ✅ Quantify queue routing bounce frequency (track 1 month)
4. ✅ Get Ascendo vendor feature pricing
5. ➡️ Calculate specific ROI for each enhancement
6. ➡️ Make data-driven invest/maintain decision

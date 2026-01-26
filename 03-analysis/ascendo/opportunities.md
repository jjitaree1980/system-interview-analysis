# Ascendo System Assessment - Opportunities

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  
**Super Users:** Rhodora Centeno Engelfeldt, Inna  

---

## High-Value Opportunities

### 1. Automatic Requisitioner Notifications for Missing Deliveries

**Opportunity:**
Implement automated notification system that alerts requisitioners when their purchase order deliveries are needed to process waiting invoices.

**Current State:**
Rhodora manually contacts requisitioners when invoices arrive but deliveries not created in SAP. Manual email/communication required for follow-up.

**Potential Impact:**
- Eliminate manual follow-up burden on Rhodora
- Reduce invoice processing delays from missing deliveries
- Proactive problem identification (requisitioners notified before asking)
- Standardized communication process
- Improved requisitioner responsiveness

**Implementation Path:**
1. Check if Ascendo has built-in notification feature (may exist unused)
2. If available, configure notification rules and triggers
3. If not available, request feature from Ascendo vendor
4. As interim: Create manual email templates to standardize communication

**Estimated ROI:**
**[TO BE CALCULATED]**
- Track: Monthly frequency of requisitioner follow-ups
- Track: Average time per follow-up communication
- Track: Average delay in processing from missing deliveries
- Formula: [Follow-ups/month × time/follow-up × 12 months × hourly rate] = Annual savings

**Priority:** Medium-High (Rhodora specifically requested this feature)

**User Quote:**
"When the invoice comes and the purchase order is not delivered in SAP it is notifying the requisitioners about the deliveries." - Rhodora's feature request

---

### 2. Automatic Approval Reminders (Especially Month-End)

**Opportunity:**
Implement automated reminder system that notifies approvers of pending invoices in their queues, with escalation for overdue items, particularly during period-end closing.

**Current State:**
Manual approval follow-up required, creating bottleneck during month-end when timely approvals are critical for closing timeline.

**Potential Impact:**
- Eliminate manual reminder communications from Rhodora
- Reduce approval delays and month-end bottlenecks
- Improve approval turnaround consistency
- Free up Rhodora's time for value-added processing
- Faster period-end closing

**Implementation Path:**
1. Check if Ascendo has configurable reminder capabilities
2. If available, configure reminder schedule and escalation rules
3. If not available, request feature from vendor
4. Pilot during one month-end cycle before full deployment

**Estimated ROI:**
**[TO BE CALCULATED]**
- Track: Time spent on manual approval reminders
- Track: Approval delays during month-end vs normal periods
- Track: Impact on period-end closing timeline
- Formula: [Reminder time × frequency + closing delay cost] = Annual savings

**Priority:** High (significant month-end impact)

**User Quote:**
"Automatic reminders to attesters to approve all the invoices in the queues especially month-end closing." - Rhodora's feature request

**Strategic Value:** Directly addresses month-end efficiency challenge

---

### 3. Vendor Matching Logic Optimization (Entity vs Bank Account)

**Opportunity:**
Change Ascendo's vendor matching logic from bank account-based to vendor entity-based to eliminate unnecessary correction time when bank details differ between systems.

**Current State:**
Ascendo matches by vendor bank account. When bank details differ between Ascendo and SAP PO (even though IBAN taken by default anyway), manual corrections required with waiting time for system to recognize updates.

**Potential Impact:**
- Eliminate correction time for bank account mismatches
- Remove unnecessary waiting time for system updates
- Reduce processing delays
- Decrease Rhodora's frustration with meaningless distinctions
- Improve overall processing efficiency

**Implementation Path:**
1. Quantify current correction frequency and time cost (1-2 months tracking)
2. Request Ascendo vendor to investigate if matching logic configurable
3. If vendor change required, calculate ROI: correction cost vs vendor development cost
4. If not feasible, explore data standardization between Ascendo and SAP as alternative

**Estimated ROI:**
**[REQUIRES TRACKING DATA]**
- Track: Number of bank account mismatch corrections per month
- Track: Average time per correction
- Track: Average waiting time impact
- Formula: [Corrections/month × (correction time + waiting time) × 12 × hourly rate] vs Vendor fix cost

**Priority:** Medium (pending quantification)

**User Quote:**
"The matching is based on vendor bank details and not the vendor itself, which require numerous corrections and waiting time." - Inna

**Strategic Note:** This may be Ascendo design philosophy. Vendor may have valid reasons for current approach. Investigate before assuming change is possible.

---

## Medium-Value Opportunities

### 4. Queue Routing Logic Improvement

**Opportunity:**
Optimize Ascendo's queue routing rules to prevent invoices from bouncing back to entrance queue multiple times before reaching correct processing queue.

**Current State:**
Some invoices "turn back several times to the entrance queue" requiring Rhodora to repeatedly redistribute them manually.

**Potential Impact:**
- Reduce extra touches per invoice
- Eliminate processing delays from routing issues
- Decrease manual redistribution burden
- Reduce risk of invoices being missed
- Improve first-time-right routing percentage

**Implementation Path:**
1. Track bounced invoices for 1 month to establish frequency and patterns
2. Identify specific invoice types or characteristics triggering bounces
3. Review queue routing rules with Ascendo vendor
4. Adjust entry validation logic to catch issues earlier
5. Test routing changes before full deployment

**Estimated ROI:**
**[REQUIRES 1 MONTH TRACKING]**
- Track: Number of invoices bouncing back per month
- Track: Average number of bounces per affected invoice
- Track: Time per manual redistribution
- Formula: [Bounced invoices × bounces per invoice × redistribution time × 12] = Annual savings

**Priority:** Medium (pending frequency quantification)

**Complexity:** Low-Medium (likely configuration review/adjustment)

---

### 5. Payment Automation (SAP to Bank)

**Opportunity:**
Automate bank file generation from SAP payment orders to eliminate Peter's manual payment register assembly and bank file preparation.

**Current State:**
Peter manually prepares payment registers and bank files in SAP. This is the only remaining manual step in otherwise fully automated workflow from invoice receipt to payment execution.

**Potential Impact:**
- Complete end-to-end automation (invoice to bank)
- Eliminate Peter's manual payment file preparation time
- Reduce potential for human error in payment assembly
- Faster payment execution turnaround
- Enable true straight-through processing

**Implementation Path:**
1. **CRITICAL FIRST STEP:** Interview Peter to quantify current manual effort
2. Investigate SAP payment automation capabilities
3. Evaluate if Ascendo can directly generate bank files
4. Consider third-party payment automation tools
5. Calculate ROI: Peter's time cost vs automation investment

**Estimated ROI:**
**[REQUIRES PETER INTERVIEW]**
- Unknown: Hours per week Peter spends on payment file preparation
- Unknown: Number of payment runs per month
- Unknown: Error rate in manual payment assembly
- **Cannot calculate ROI without Peter's input**

**Priority:** Medium (pending Peter interview to confirm impact)

**Complexity:** Medium-High (SAP/banking integration work)

**Assessment Gap:** Peter not interviewed - critical data missing

---

### 6. Standard Message Templates Library

**Opportunity:**
Create library of standard message templates for common invoice communication scenarios when using Ascendo's direct mailing function.

**Current State:**
No standard templates exist. Rhodora manually composes messages each time she contacts requisitioners about invoice issues.

**Potential Impact:**
- Reduce time spent writing repetitive messages
- Improve communication consistency and clarity
- Ensure quality control on message content
- Reduce potential for unclear instructions
- Faster communication turnaround

**Implementation Path:**
1. Check if Ascendo supports message templates feature
2. If supported, create template library in system
3. If not supported, document standard messages for copy/paste
4. Create email system templates as workaround
5. Very low implementation cost (configuration or documentation)

**Estimated ROI:**
**Low per instance, potential accumulation**
- Message composition time minimal individually
- Frequency depends on invoice communication volume
- Quick win if feature already exists unused

**Priority:** Low-Medium (nice-to-have quality of life improvement)

**Complexity:** Very Low (configuration or documentation exercise)

**User Quote:**
"List of standard messages invoice mailing." - Inna's feature request

---

## Low-Value Opportunities (Minor Optimizations)

### 7. Faster Matching Status Refresh

**Opportunity:**
Reduce matching status update time from current <1 hour to real-time or <5 minutes for faster processing flow.

**Current State:**
After matching conditions met, automatic status change to green "Fully matched" takes up to 1 hour. Rhodora describes as "manageable."

**Potential Impact:**
- Slight reduction in processing flow delays
- Immediate confirmation of matching corrections
- Improved user experience (no waiting)
- Marginal efficiency gain

**Implementation Path:**
1. Request faster refresh cycle from Ascendo vendor
2. Investigate if manual refresh trigger exists
3. Assess if database query optimization possible
4. Low priority given current state is acceptable

**Estimated ROI:**
Low - waiting time is predictable, short, and users adapted workflow around it.

**Priority:** Low (enhancement vs necessity)

**Complexity:** Low (configuration) to Medium (if requires development)

**User Quote:**
"Shorter update of the matching status. Normally takes less than an hour... Otherwise, manageable." - Rhodora

**Assessment:** Since Rhodora says "manageable," this is nice-to-have rather than necessity.

---

### 8. Credit Note Workflow Streamlining

**Opportunity:**
Optimize credit note processing to match regular invoice workflow efficiency.

**Current State:**
Credit note processing "could have been better" but noted as primarily Ascendo-SAP integration issue rather than Ascendo limitation.

**Potential Impact:**
- Reduce extra processing time for credit notes
- Decrease potential for credit note errors
- Standardize workflow across all invoice types
- Depends heavily on credit note volume

**Implementation Path:**
1. Quantify monthly credit note volume
2. Compare credit note processing time vs regular invoices
3. Review SAP credit note configuration (Inna says it's SAP-side issue)
4. Request Ascendo vendor guidance on best practices
5. Calculate if volume justifies optimization investment

**Estimated ROI:**
**[DEPENDS ON CREDIT NOTE VOLUME]**
- Need data: Monthly credit note volume
- Need data: Extra time per credit note vs regular invoice
- Formula: [Credit notes/month × extra time × 12] vs Optimization cost

**Priority:** Low-Medium (depends on volume)

**Complexity:** Medium (integration work)

**User Quote:**
"The processing of credit-notes could have been better, but it depends more on SAP integration rather than Ascendo itself." - Inna

**Strategic Note:** Inna explicitly identifies this as SAP integration issue, not Ascendo system issue. May require SAP-side fix rather than Ascendo enhancement.

---

### 9. UI Column Width Adjustment

**Opportunity:**
Enable users to adjust column widths in Ascendo interface for better screen real estate management.

**Current State:**
Cannot adjust column widths. Some columns appear "a little off" according to Rhodora.

**Potential Impact:**
- Improved user experience (cosmetic)
- Better readability
- No functional processing impact
- Minor quality of life improvement

**Implementation Path:**
1. Request UI improvement from Ascendo vendor
2. Check if configurable in system settings
3. Very low priority investment

**Estimated ROI:**
Negligible - purely cosmetic issue with no measurable efficiency impact.

**Priority:** Very Low (document but don't invest resources)

**Complexity:** Low (UI configuration)

---

## Strategic Opportunity Assessment

### Quick Wins (0-3 Months):

**If Features Already Exist:**
1. Check for unused approval reminder capabilities
2. Check for unused requisitioner notification features
3. Create standard message templates (manual documentation)

**Low-Cost Implementations:**
1. Review queue routing rules for obvious fixes
2. Document and standardize existing workarounds

---

### Medium-Term Investments (3-12 Months):

**If ROI Exceeds 2:1 Ratio:**
1. Implement automatic requisitioner notifications
2. Configure/request automatic approval reminders
3. Optimize vendor matching logic (if cost-effective)
4. Fix queue routing issues (if high frequency confirmed)

**Dependent on Quantification:**
1. Payment automation (pending Peter assessment)
2. Credit note optimization (pending volume analysis)

---

### Long-Term Strategy (12+ Months):

**Only if Strategic Value Justifies:**
1. Advanced SAP-to-bank payment automation
2. Comprehensive credit note workflow redesign
3. Integration with additional systems (if future needs emerge)

---

## Investment Prioritization Framework

### Highest ROI Potential:
1. **Approval reminders** - Month-end impact, high frequency
2. **Requisitioner notifications** - Reduces delays, user-requested
3. **Vendor matching optimization** - Regular friction, "numerous corrections"

### Highest Strategic Value:
1. **Payment automation** - Completes end-to-end automation vision
2. **Approval reminders** - Supports period-end efficiency
3. **Queue routing optimization** - Improves first-time-right processing

### Lowest Complexity:
1. **Standard message templates** - Documentation or configuration only
2. **Queue routing review** - Configuration adjustment
3. **Check for existing unused features** - Discovery, no development

### Lowest Priority:
1. UI column width adjustment (cosmetic)
2. Faster matching status refresh (current state acceptable)
3. Credit note optimization (depends on low-frequency volume)

---

## Critical Success Factors for Opportunity Implementation

### Before Investing in Any Opportunity:

**Step 1: Quantify Current Waste**
- Track specific pain point frequency and time cost
- Calculate annual waste in hours and SEK
- Determine if waste justifies investment

**Step 2: Validate Technical Feasibility**
- Check if features already exist unused
- Confirm vendor can deliver requested enhancements
- Assess integration complexity and risk

**Step 3: Calculate ROI**
- Enhancement cost ÷ annual waste savings = Payback period
- Target: <2 years payback for approval
- Consider: Risk of adding complexity to stable system

**Step 4: Pilot and Validate**
- Test enhancements before full deployment
- Validate that improvements don't introduce regression
- Confirm actual time savings match projections

---

## Rhodora vs Inna Investment Perspectives

### Rhodora's "Invest More" Position:
**Focus:** Optimization features that reduce daily friction
- Requisitioner notifications ✓
- Faster matching status ✓
- Approval reminders ✓
- Aware of Ascendo vendor feature packages ✓

**Mindset:** Proactive enhancement, continuous improvement

---

### Inna's "Keep As Is" Position:
**Focus:** Maintain stable, proven system
- Current functionality meets needs ✓
- Minor issues are integration-related, not Ascendo ✓
- Risk-averse toward unnecessary changes ✓
- Satisfied with aggregate performance ✓

**Mindset:** Conservative, stability-focused

---

### Reconciliation Strategy:

**Both perspectives are valid.** Decision should be data-driven:

1. **Quantify opportunities:** Calculate actual annual waste from pain points
2. **Evaluate vendor offerings:** What feature packages address user requests?
3. **Calculate ROI:** Do enhancements exceed 2:1 return threshold?
4. **Assess risk:** Will changes compromise current 95-100% accuracy and stability?

**If pain points total <50K SEK annually:** Inna's "keep as is" justified  
**If specific fix has >2:1 ROI:** Rhodora's "invest more" justified  
**If vendor packages misaligned:** Maintain current stable state

---

## Comparison to Other Kubal Systems

### Opportunity Context:

**Ascendo Opportunities:**
- All enhancement-focused (workflow optimization)
- No critical fixes needed
- Building on excellent foundation
- Optional based on ROI

**Idus Opportunities:**
- Must fix broken SAP integration (1.55M SEK waste)
- Must address mobile access limitations
- Critical remediation, not enhancement

**Flexite Opportunities:**
- Must add government integration (eliminates manual reporting)
- Must implement automated dashboards
- Mix of critical fixes and enhancements

**Conclusion:** Ascendo is in enviable position - choosing between optimization options rather than fixing broken functionality.

---

## Key Insight on Opportunities

**Ascendo's opportunities are a "luxury problem."**

The system:
- ✅ Achieves zero manual SAP data entry
- ✅ Delivers 95-100% OCR accuracy
- ✅ Saves 900-1,800 hours annually
- ✅ Operates stably with minimal IT support
- ✅ Fully satisfies both experienced users

**All identified opportunities are incremental optimizations on proven success.**

This contrasts sharply with other systems requiring fundamental fixes. Investment decisions should reflect this difference - Ascendo enhancements are optional efficiency gains, not urgent remediation.

---

**Document Status:** Ready for management review  
**Next Steps:**  
1. ✅ Quantify top 3 opportunity ROI (tracking period required)
2. ✅ Interview Peter for payment automation assessment
3. ✅ Request Ascendo vendor feature package details and pricing
4. ➡️ Calculate specific ROI for each enhancement
5. ➡️ Make data-driven invest/maintain decision

**Key Message:** All opportunities are enhancements, not fixes. Prioritize based on ROI, not urgency.

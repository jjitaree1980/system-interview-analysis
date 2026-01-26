# Ascendo System Assessment - Key Themes

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  
**Super Users:** Rhodora Centeno Engelfeldt (AP Accountant), Inna (AP Manager/Supervisor)  
**System Criticality:** 10/10 (Both users)

---

## Theme 1: Mission-Critical System with No Manual Alternative

**Summary:**
Ascendo is absolutely essential to Kubal's finance operations. Both users rated it 10/10 criticality and stated that manual invoice processing is not feasible at current volumes (500-1,000 invoices/month).

**Evidence:**
- "We are completely dependent of Ascendo for proper booking of accounts payables" (Rhodora)
- "There is no other process of approval and booking of invoices" (Inna)
- "For Kubal size company it's not the question between manual invoice processing or invoice processing solution because manual processing is out of question" (Inna)
- Both users answered "NO" to "Could you process invoices manually if needed?"
- 100% of invoices processed through Ascendo
- 0% manual processing outside system

**Impact:**
System downtime would halt all AP operations. Only critical invoices could be paid as prepayments, with invoice processing backlog accumulating until system recovery.

---

## Theme 2: Exceptional Integration Success with SAP

**Summary:**
Ascendo achieves the ideal state of AP automation: zero manual data entry to SAP. Data flows automatically from invoice receipt through approval to posting and payment order creation.

**Evidence:**
- **Zero manual SAP data entry** - fully automatic posting
- Preliminary posting after first approval, final posting after last approval
- Payment orders automatically created in SAP upon posting
- Both users confirmed: "Data flows automatically from Ascendo to SAP, posts automatically, I don't touch it"
- 95-100% OCR accuracy reduces manual corrections needed
- PO matching rated "Excellent" (Inna) or "Good" (Rhodora)

**Impact:**
This represents best-in-class integration. Compare to Idus where broken SAP integration creates 1.55M SEK annual waste. Ascendo proves seamless integration is achievable at Kubal.

**Time Savings:**
- Manual data entry would take ~10 minutes per invoice (Inna's estimate)
- Ascendo overview takes <1 minute
- **Savings: 9 minutes per invoice**
- **Monthly: 75-150 hours saved** (at 500-1,000 invoices)
- **Annual: 900-1,800 hours eliminated**

---

## Theme 3: High Performance with Minimal Operational Friction

**Summary:**
Ascendo demonstrates excellent operational metrics with 95-100% OCR accuracy, sub-1-minute processing time, and high system stability requiring minimal IT support.

**Evidence:**
- OCR accuracy: 95% (Rhodora) to "close to 100%" (Inna)
- Processing time: <1 minute in optimal conditions (Inna)
- Manual corrections: "Rarely" (<10% of invoices) to "Sometimes" (10-30%)
- Correction time: 1-5 minutes per invoice when needed
- System stability: "Very stable - Rarely have problems" (both users)
- Month-end performance: "Excellent - No slowdown" (both users)
- IT support: "Rarely (a few times per year)" (both users)

**Impact:**
Low friction in daily operations allows small team (Rhodora + Inna backup + Peter for payments) to process high invoice volumes efficiently without system bottlenecks.

---

## Theme 4: Mature System with Complete Workflow Automation

**Summary:**
After 3+ years of use, Ascendo is fully embedded into Kubal's AP workflow with complete adoption, experienced users, and automated end-to-end processes from receipt to payment.

**Evidence:**
- 3+ years user experience (both users identify as "super users")
- 100% invoice adoption through system
- Complete workflow coverage:
  - PDF receipt and OCR extraction ✓
  - PO matching ✓
  - Approval routing with saved chains ✓
  - SAP posting (preliminary and final) ✓
  - Payment order creation ✓
  - Duplicate detection ✓
  - Status tracking ✓
- Approval process embedded in Ascendo (SAP lacks approval module)
- Direct mailing to requesters from Ascendo
- Multiple queue management for different invoice types

**Impact:**
No parallel manual processes exist. System represents single source of truth for AP operations with complete audit trail and compliance support.

---

## Theme 5: Minor Pain Points are Optimization Opportunities, Not Fundamental Flaws

**Summary:**
Identified frustrations are efficiency enhancements rather than system failures. Users can work around issues, and most stem from data quality or integration design choices rather than Ascendo malfunction.

**Evidence:**
- **Vendor matching by bank account** (vs vendor entity): Causes correction delays but workaround exists
- **Queue routing logic**: Invoices sometimes bounce back to entrance queue - annoying but manageable
- **UI limitations**: Cannot adjust column widths - cosmetic issue
- **Credit note processing**: "Could be better" but noted as SAP integration issue, not Ascendo
- **Matching status display**: Green status when line number missing - "easy fix"
- **February 2025 update issues**: Temporary challenge, "working as normal again"

**Impact:**
Pain points cause minor efficiency losses but don't compromise core functionality. All users' feature requests are enhancements, not fixes. Both users responded "Yes, fully meets our needs" when asked if Ascendo meets current requirements.

---

## Theme 6: Divergent Investment Perspectives Reflect Different Roles

**Summary:**
Rhodora (processor) recommends "invest more" while Inna (manager) recommends "keep as is." This disagreement is healthy and role-appropriate rather than indicating dissatisfaction.

**Evidence:**

**Rhodora's "Invest More" Position:**
- Processor experiences daily friction points
- Aware of Ascendo vendor's additional feature packages
- Wants proactive enhancements:
  - Automatic requisitioner notifications for missing deliveries
  - Faster matching status updates (<1 hour)
  - Automatic approval reminders for month-end

**Inna's "Keep As Is" Position:**
- Manager sees aggregate performance, not edge cases
- Views minor issues as integration-related, not Ascendo's fault
- Satisfied with current capability meeting business needs
- Risk-averse toward unnecessary changes to stable system

**Impact:**
Both perspectives are valid. Decision should be based on ROI of specific feature packages vs risk of unnecessary complexity to working system.

---

## Strategic Implications

### System Strengths to Preserve

**Core Functionality:**
- Zero manual SAP data entry (fully automated)
- 95-100% OCR accuracy
- <1 minute processing time
- Seamless approval routing
- Automatic payment order creation
- Effective duplicate detection

**Operational Excellence:**
- 100% system adoption
- High user expertise (3+ years)
- Minimal IT support needs
- Excellent month-end performance
- Strong audit trail and compliance

### Investment Considerations

**Rhodora's Enhancement Requests:**
1. **Requisitioner notification system** - Proactive delivery reminders
2. **Faster matching status refresh** - Current <1 hour is "manageable" but could be quicker
3. **Automatic approval reminders** - Especially valuable at month-end

**Inna's Optimization Requests:**
1. **Vendor matching by entity** (vs bank account) - Would eliminate correction time
2. **Standard message templates** - Speed up invoice communication

**Cost-Benefit Analysis Needed:**
- What do Ascendo's feature packages cost?
- Do they address specific user requests?
- ROI calculation: Feature cost vs time saved
- Risk assessment: Complexity added vs efficiency gained

### Comparison to Other Kubal Systems

**Ascendo as Reference Implementation:**
- **vs Idus:** Seamless SAP integration (Idus broken = 1.55M SEK waste)
- **vs Agda/Visma:** Similar high performance, minimal waste
- **vs Flexite:** Both 100% adoption, but Flexite has manual government reporting

**Key Lesson:**
Ascendo proves that seamless system integration and high user satisfaction are achievable at Kubal. Other systems should be evaluated against this standard.

### Risk of No Action

**If "Keep As Is" (Inna's recommendation):**
- ✅ Maintain stable, proven system
- ✅ Avoid unnecessary complexity
- ❌ Forgo potential efficiency improvements
- ❌ Miss vendor-supported enhancements

**If "Invest More" (Rhodora's recommendation):**
- ✅ Optimize daily processor experience
- ✅ Reduce month-end approval bottlenecks
- ✅ Eliminate vendor matching correction time
- ❌ Risk introducing bugs or complexity
- ❌ Cost of feature packages (unknown)

### Strategic Questions

**Before deciding on investment:**
1. What is annual cost of current manual corrections and workarounds?
2. What do Ascendo's add-on packages cost and include?
3. Do vendor features map to user requests or introduce unneeded complexity?
4. What is Peter's perspective on payment workflow? (Not interviewed - gap in assessment)
5. Could vendor matching logic be fixed without major feature purchase?

---

## Conclusion: A System That Works

Ascendo represents successful enterprise software implementation at Kubal. It is mission-critical, fully adopted, highly performing, and seamlessly integrated with SAP. Minor pain points are optimization opportunities rather than fundamental problems.

**Key Success Factors:**
1. Complete automation (zero manual SAP entry)
2. Excellent OCR accuracy (95-100%)
3. Experienced, trained users (3+ years)
4. Customization to Kubal's specific workflow
5. Stable, reliable performance

**Investment Decision:**
The "invest more vs keep as is" question is a luxury problem. Both options are reasonable because the foundation is solid. Decision should be driven by specific ROI analysis of vendor feature packages against quantified time waste from current workarounds.

**This is the standard other Kubal systems should meet.**

---

**Document Status:** Ready for management review  
**Next Steps:**  
1. Interview Peter to complete payment workflow assessment
2. Quantify time cost of vendor matching corrections
3. Get Ascendo vendor feature package pricing
4. Calculate ROI for enhancement investments
5. Make invest/maintain decision based on data

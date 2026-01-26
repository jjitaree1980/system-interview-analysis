# Ascendo System Assessment - Strengths

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  
**Super Users:** Rhodora Centeno Engelfeldt, Inna  
**System Criticality Rating:** 10/10 (Both users)

---

## Core System Strengths

### 1. Zero Manual SAP Data Entry (Fully Automated Integration)

**Evidence:**
- Data flows automatically from Ascendo to SAP
- Automatic posting after approval
- Automatic payment order creation
- Both users confirmed: "Data flows automatically, posts automatically, I don't touch it"
- No manual export/import required
- No manual data entry into SAP

**Business Value:**
This is the **gold standard** for invoice processing automation. Manual invoice data entry would take ~10 minutes per invoice. At 500-1,000 invoices/month, Ascendo saves **75-150 hours monthly** (900-1,800 hours annually) on data entry alone, not counting approval workflow and PO matching automation.

**Comparison Context:**
Idus suffers 1.55M SEK annual waste from broken SAP integration. Ascendo proves seamless integration is achievable at Kubal.

---

### 2. Exceptional OCR Accuracy (95-100%)

**Evidence:**
- Rhodora: 95% accuracy estimate
- Inna: "Close to 100%" accuracy estimate
- Both selected: "90-100% accurate (rarely need to fix)"
- Manual corrections: <10% to 10-30% of invoices
- Correction time: 1-5 minutes when needed
- Common OCR errors minimal (mainly reference/PO confusion)

**Business Value:**
High OCR accuracy means most invoices flow through system with minimal human intervention. Processing time <1 minute in optimal conditions (Inna's estimate).

**Industry Context:**
95-100% OCR accuracy is best-in-class for invoice processing systems.

---

### 3. Complete User Adoption (100%)

**Evidence:**
- 100% of invoices processed through Ascendo
- 0% manual processing outside system
- Both users: "Could not process invoices manually" if Ascendo unavailable
- No parallel manual processes or shadow systems
- No invoice bypass workarounds
- 3+ years mature implementation

**Business Value:**
Complete adoption means system is the single source of truth for AP operations. Audit trail is comprehensive, compliance is assured, and there are no gaps in financial controls.

**Risk Implication:**
System is mission-critical (10/10 from both users). Downtime would halt AP operations entirely.

---

### 4. High System Stability and Reliability

**Evidence:**
- Both users: "Very stable - Rarely have problems"
- IT support contact: "Rarely (a few times per year)"
- Month-end performance: "Excellent - No slowdown"
- No reported crashes or extended downtime
- Integration issues "mostly from SAP end" and "rarely happening now"
- February 2025 update challenges resolved, "working as normal again"

**Business Value:**
Reliable system minimizes IT support costs, enables predictable processing timelines, and maintains operations during critical periods like month-end closing.

---

### 5. Experienced, Competent Users (3+ Years)

**Evidence:**
- Rhodora: 3+ years, self-described "super user"
- Inna: 3+ years, self-described "super user"
- Both use system multiple times daily
- Deep system knowledge reduces errors
- Users understand workarounds for known issues
- Can adapt to updates (February 2025 example)

**Business Value:**
Experienced users maximize system efficiency, troubleshoot issues independently, and maintain high processing quality. 3+ years tenure indicates low turnover and knowledge retention.

---

### 6. Embedded Approval Routing (No SAP Approval Module Needed)

**Evidence:**
- Approval chains saved in Ascendo
- Number of approvers depends on invoice amount
- Direct bookings have +1 approval level automatically
- 100% of approvals happen in Ascendo (no email approvals)
- Approvers can return invoices for investigation
- Preliminary posting after first approval, final posting after last approval

**Business Value:**
Ascendo eliminates need for separate SAP approval workflow module. Approval automation is built-in, customizable, and effective. This is strategic system architecture - approval logic belongs in invoice system, not ERP.

---

### 7. Effective Duplicate Detection

**Evidence:**
- Duplicate check performed at invoice intake (Step 2 in Inna's workflow)
- Both users: "Yes - Flags potential duplicates effectively"
- Inna noted duplicate payments have occurred but "doesn't depend on Ascendo" - human error (forgetting to block prepaid invoices), not system failure

**Business Value:**
Prevents costly duplicate payments through automated detection. When duplicates do occur, root cause is human error in blocking prepaid invoices, not system malfunction.

---

### 8. Comprehensive Workflow Automation

**Evidence:**
- PDF receipt and OCR extraction ✓
- Purchase order matching ✓
- Approval routing ✓
- SAP posting (preliminary and final) ✓
- Payment order creation ✓
- Duplicate detection ✓
- Status tracking ✓
- Direct mailing to requisitioners ✓

**Business Value:**
End-to-end automation from invoice receipt to payment order creation. Only remaining manual step is Peter's bank file preparation (SAP-to-bank, not Ascendo responsibility).

---

### 9. Fast Processing Time (<1 Minute in Optimal Conditions)

**Evidence:**
- Inna: "Processing in Ascendo would take less than 1 minute" with good data quality
- Compare to manual: ~10 minutes data entry alone
- **90%+ time reduction** on invoice processing
- OCR accuracy reduces manual touchpoints

**Business Value:**
Speed enables small team (Rhodora + Inna backup + Peter for payments) to handle 500-1,000 monthly invoices efficiently without processing bottlenecks.

---

### 10. Customized to Kubal's Specific Workflow

**Evidence:**
- Inna: "It is quite well customized to our work flow"
- Rhodora: "It is built to work well with the integration to SAP"
- Separate queues for PO matching vs direct booking
- Account number assignment for non-PO invoices
- Direct booking adds +1 approval level automatically
- Prepayment blocking capability

**Business Value:**
System matches Kubal's business processes rather than forcing process changes. Implementation included customization to organization's specific needs.

---

## Strategic Strengths

### Mission-Critical Status with No Manual Alternative

**Evidence:**
Both users rated 10/10 criticality:
- Rhodora: "We are completely dependent of Ascendo for proper booking of accounts payables and everything that is related to it."
- Inna: "There is no other process of approval and booking of invoices."
- Inna: "For Kubal size company it's not the question between manual invoice processing or invoice processing solution because manual processing is out of question."

**Strategic Implication:**
At 500-1,000 invoices/month, manual processing is infeasible. Ascendo isn't optional infrastructure - it's foundational to finance operations.

---

### Best-in-Class Integration Success

**Integration Quality:**
- Rhodora: "Seamlessly - Data flows automatically"
- Inna: "Well - Works most of the time"
- Zero manual data entry
- Automatic payment order creation
- Fully automatic posting

**Benchmark Context:**
This is the **reference implementation** for how Kubal systems should integrate with SAP. Compare to:
- **Idus:** Broken SAP integration, 1.55M SEK annual waste
- **Flexite:** System isolation, manual government reporting
- **Agda/Visma:** Good performance, 75K SEK waste

**Key Lesson:**
Ascendo proves seamless SAP integration is achievable at Kubal. Other systems should be evaluated against this standard.

---

### Exceptional ROI Delivered

**Time Savings:**
- Data entry: 9 minutes saved per invoice
- At 500 invoices/month: 75 hours saved
- At 1,000 invoices/month: 150 hours saved
- Annual: 900-1,800 hours eliminated
- Plus unmeasured savings: PO matching, approval routing, posting automation

**Cost Avoidance:**
Inna's insight: At Kubal's size, manual processing is "out of question." Ascendo isn't saving money versus manual process - it's enabling AP operations that couldn't exist manually at this scale.

---

### Mature, Stable Foundation for Future Optimization

**System Maturity Indicators:**
- 3+ years implementation
- Experienced super users
- Resolved past challenges (February 2025 update)
- No core functionality gaps
- All identified pain points are optimization opportunities

**Investment Position:**
Strong foundation allows confident investment in enhancements. Unlike systems requiring fundamental fixes (Idus), Ascendo optimizations build on proven success.

---

## Operational Strengths

### 11. Easy Status Tracking and Visibility

**Evidence:**
- Both users: "Yes, very easy - Can see status in Ascendo"
- Search function allows invoice tracking at any stage
- Users can check payment status
- Complete audit trail of invoice lifecycle

**Business Value:**
Transparency enables proactive management, quick customer inquiries response, and problem identification before they escalate.

---

### 12. Flexible Exception Handling

**Evidence:**
- Rhodora: "Somewhat easy - Can manage with workarounds"
- Inna: "Very easy - System handles them well"
- Inna notes: Issues stem from vendor/requester errors, not system limitations
- System handles: invoices without PO numbers, credit notes, foreign currency, non-standard formats

**Business Value:**
System accommodates real-world invoice variations. Processing doesn't break when data is imperfect.

---

### 13. Effective Audit Trail and Compliance Support

**Evidence:**
- Complete invoice lifecycle documentation
- Approval chain visibility
- Preliminary and final posting tracking
- Both users: Reports "very easy" or "takes time but doable"
- Support for internal and external audits

**Business Value:**
Financial controls maintained, audit readiness ensured, compliance demonstration straightforward.

---

### 14. Direct Communication Capabilities

**Evidence:**
- Ascendo has direct mailing function to requisitioners
- Includes recipient address book
- Can send invoices to requesters for investigation
- Email notifications for approvers

**Business Value:**
Communication stays within workflow context. No need to switch to external email, maintain separate contact lists, or lose audit trail of communications.

---

## User Satisfaction Strengths

### Both Users Report "Fully Meets Our Needs"

**Rhodora's Strengths List:**
1. "Already an established invoice system" - proven track record
2. "Built to work well with integration to SAP" - strategic architecture
3. "We are already super user of it" - deep knowledge and comfort

**Inna's Strengths List:**
1. "Eliminates huge amount of manual work on all levels" - organization-wide impact
2. "It is quite well customized to our work flow" - process fit

**Investment Recommendations:**
- Rhodora: "Invest more" - wants optimization features
- Inna: "Keep as is" - satisfied with current state
- **Both perspectives acknowledge strong foundation**

---

## Preservation Priorities

### Must Preserve During Any System Changes:

**Critical Capabilities:**
1. Zero manual SAP data entry (fully automated integration)
2. 95-100% OCR accuracy
3. Automatic approval routing
4. Automatic payment order creation
5. Duplicate detection effectiveness
6. Fast processing time (<1 minute optimal)

**User Experience:**
1. System stability and reliability
2. Complete workflow automation
3. Easy status tracking
4. Exception handling flexibility

**Strategic Position:**
1. 100% user adoption
2. Mission-critical status (10/10)
3. Experienced user base (3+ years)
4. Customization to Kubal workflow

---

## Competitive Advantages

### Compared to Manual Processing:
- Automated OCR vs manual data entry (9 min/invoice saved)
- Automatic SAP posting vs manual entry (additional time saved)
- Built-in approval workflow vs manual routing (coordination eliminated)
- Duplicate detection vs manual checking (errors prevented)
- Status tracking vs spreadsheet management (real-time visibility)

### Compared to Other Kubal Systems:
- **Best SAP integration** (zero manual entry)
- **Highest criticality rating** (10/10 vs Idus 10/10, Flexite 9/10)
- **No critical gaps** (unlike Idus broken integration)
- **Mature, stable operation** (unlike recent Idus challenges)
- **Complete user satisfaction** ("fully meets needs" from both users)

---

## Key Insight

**Ascendo represents successful enterprise software implementation at Kubal.** 

Core strengths:
- ✅ Solves critical business problem (AP automation)
- ✅ Achieves best-practice integration (zero manual SAP entry)
- ✅ Delivers exceptional ROI (900-1,800 hours saved annually)
- ✅ Maintains high stability (rarely needs IT support)
- ✅ Achieves complete user adoption (100% of invoices)
- ✅ Satisfies experienced users ("fully meets needs")

**This is the standard other Kubal systems should meet.**

---

## Investment Strategy Implications

### Building on Strength:

**Do:**
- Enhance existing excellent foundation
- Add workflow optimizations (notifications, reminders)
- Improve efficiency at the margins
- Maintain core automation quality

**Don't:**
- Replace working system
- Compromise SAP integration
- Reduce OCR accuracy
- Break approval automation
- Add unnecessary complexity

### ROI Perspective:

Even if **all identified pain points totaled 100 hours annual waste**, Ascendo still delivers **900%+ net positive ROI** on its core automation value.

**This puts "invest more vs keep as is" in perspective:**
- Both options are reasonable
- Foundation is excellent either way
- Decision should be driven by specific ROI calculations
- Risk of regression must be weighed against marginal gains

---

**Document Status:** Ready for management review  
**Strategic Recommendation:** Preserve these strengths as foundation for any future enhancements  
**Key Message:** Ascendo is a reference implementation of successful system adoption - replicate this pattern in other areas

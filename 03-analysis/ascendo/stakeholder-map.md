# Ascendo System Assessment - Stakeholder Map

**System:** Ascendo (Invoice Processing & AP Automation)  
**Assessment Date:** January 19, 2026  

---

## Primary Stakeholders

### Rhodora Centeno Engelfeldt - AP Accountant / System Owner

**Role:** Main Ascendo processor and system owner  
**Tenure:** 3+ years with Ascendo  
**Usage Frequency:** Multiple times per day  
**System Criticality Rating:** 10/10

**Responsibilities:**
- Process all incoming invoices (500-1,000/month)
- Match invoices to purchase orders
- Handle direct cost bookings (non-PO invoices)
- Perform data corrections after OCR
- Route invoices for approval
- Post invoices to SAP
- Manage queue distribution
- Handle vendor communications
- Resolve matching issues
- System administration and user support

**Pain Points:**
- Vendor matching by bank account causes correction delays
- UI limitations (cannot adjust column widths)
- Matching status sometimes inaccurate
- Queue routing causes some invoices to bounce back
- February 2025 update required adaptation

**System Satisfaction:** High (10/10 criticality, "fully meets needs")  
**Influence Level:** Critical (single point of failure for AP operations)  
**Investment Recommendation:** "Invest more" - wants additional feature packages

**Key Quote:**
"We are completely dependent of Ascendo for proper booking of accounts payables and everything that is related to it."

---

### Inna - AP Manager/Supervisor

**Role:** AP oversight and backup processor  
**Tenure:** 3+ years with Ascendo  
**Usage Frequency:** Multiple times per day  
**System Criticality Rating:** 10/10

**Responsibilities:**
- Review already-processed invoices for detailed information
- Set framework for invoice processing during period closing
- Act as Rhodora's replacement when unavailable
- Provide managerial oversight of AP function
- Handle complex investigations
- System backup and support

**Pain Points:**
- Invoices bounce back to entrance queue multiple times
- Vendor matching by bank account vs vendor entity
- Credit note processing could be better (SAP integration issue)

**System Satisfaction:** High (10/10 criticality, "fully meets needs")  
**Influence Level:** High (manager authority, backup processor)  
**Investment Recommendation:** "Keep as is" - satisfied with current functionality

**Key Quote:**
"For Kubal size company it's not the question between manual invoice processing or invoice processing solution because manual processing is out of question."

---

### Peter - Payment Processor

**Role:** Payment execution and bank file preparation  
**Tenure:** Unknown (not interviewed)  
**Usage Frequency:** Regular (payment cycles)  
**System Interaction:** Downstream SAP user

**Responsibilities:**
- Create payment files in SAP
- Manage payment registers
- Prepare bank files
- Handle prepayments
- Execute payment runs
- Monitor payment status

**Pain Points:**
- Unknown (not interviewed - assessment gap)

**System Value:**
Receives automatic payment order documents from Ascendo/SAP integration

**Influence Level:** Medium (executes on Ascendo outputs)  
**Assessment Gap:** Peter's workflow time cost not quantified

---

## Secondary Stakeholders

### Invoice Approvers - Department Managers & Budget Owners

**Role:** Approve invoices within authorization limits  
**Population:** Multiple departments across organization  
**Usage Frequency:** Daily to weekly (varies by department)  
**Access Method:** Ascendo approval interface

**Responsibilities:**
- Review and approve invoices in their queues
- Return invoices for investigation if needed
- Respond to approval requests promptly
- Ensure budget compliance

**Pain Points:**
- No automatic reminders for pending approvals (especially month-end)
- No visibility into approval bottlenecks

**System Value:**
Embedded approval routing eliminates need for separate SAP approval module

**Influence Level:** Medium (approval bottlenecks delay processing)  
**User Behavior:** Generally responsive to approval requests

---

### Requisitioners - Purchase Order Creators

**Role:** Create purchase orders and deliveries in SAP  
**Usage Frequency:** Indirect (triggered by Ascendo needs)

**Responsibilities:**
- Create purchase orders in SAP
- Make deliveries when goods/services received
- Respond when invoices arrive before delivery created
- Provide PO information when requested

**Pain Points:**
- Manual follow-up when deliveries missing
- No automatic notification from Ascendo about missing deliveries

**System Impact:**
Delayed deliveries cause invoice processing delays and manual follow-up burden on Rhodora

**Influence Level:** Medium (data quality affects processing time)

---

### Vendors - External Suppliers

**Role:** Submit invoices for payment  
**Population:** Hundreds of suppliers  
**Interaction Method:** E-invoice or PDF via Scancloud

**Responsibilities:**
- Send invoices electronically (e-invoice encouraged)
- Include correct PO numbers
- Provide accurate bank account information
- Update vendor data when changed

**Pain Points:**
- Some don't include PO numbers on invoices
- Bank account changes cause matching issues

**System Impact:**
Vendor data quality directly affects OCR accuracy and matching success

**Influence Level:** Low (external, limited control)

---

### Economy/Finance Team - Financial Management

**Role:** Oversee AP operations and financial compliance  
**Usage Frequency:** Monthly reporting and oversight

**Responsibilities:**
- Monitor AP aging and payment status
- Pull reports for audits and compliance
- Review financial controls
- Oversee month-end closing
- Manage cash flow

**System Value:**
Automated posting and audit trails support financial controls and reporting

**Influence Level:** High (budget and investment decisions)

---

### IT Department - Technical Support

**Engagement Level:** Minimal  
**Responsibilities:** System access and technical issues  
**Support Frequency:** Rarely (few times per year for both users)

**Current State:**
- Very low support requirements
- Ascendo-SAP integration runs reliably
- Excellent performance = minimal IT burden

**Influence Level:** Low (system requires minimal support)

---

### SAP System - Critical Integration Partner

**Role:** Downstream system receiving Ascendo data  
**Interaction:** Fully automated data flow

**Integration Points:**
- Purchase order data (from SAP to Ascendo)
- Invoice posting (from Ascendo to SAP)
- Payment order creation (automatic in SAP)
- Preliminary and final posting

**Integration Quality:** Excellent (zero manual data entry)  
**Influence Level:** Critical (broken integration would halt operations)

**Note:** Compare to Idus where broken SAP integration causes 1.55M SEK annual waste

---

## Stakeholder Influence & Impact Matrix

| Stakeholder | System Usage | Decision Power | Change Impact | Priority |
|:------------|:-------------|:---------------|:--------------|:---------|
| Rhodora | Daily/Critical | High | Extreme | Critical |
| Inna | Daily | High | High | Critical |
| Peter | Downstream | Low | Medium | High |
| Approvers | Regular | Low | High | High |
| Requisitioners | Indirect | Low | Medium | Medium |
| Vendors | External | Low | Medium | Medium |
| Economy Team | Oversight | High | Medium | High |
| IT Department | Minimal | Low | Low | Low |
| SAP Integration | Automated | N/A | Critical | Critical |

---

## Stakeholder Communication Strategy

**For System Changes:**

**Must Engage:**
- **Rhodora:** System owner, daily processor, must approve all changes
- **Inna:** Manager oversight, backup processor, strategic perspective
- **Approvers:** Any workflow changes affect their experience
- **Economy Team:** ROI justification and strategic alignment

**Should Interview:**
- **Peter:** Payment workflow gap in assessment - need his perspective
- **Key Approvers:** Month-end bottleneck analysis

**Should Inform:**
- **IT Department:** Technical requirements for enhancements
- **Requisitioners:** If automatic notification feature implemented

**May Coordinate:**
- **Vendors:** If changes affect invoice submission process
- **SAP Team:** If integration modifications required

---

## Key Stakeholder Insights

### Rhodora as Critical Single Point of Failure

**Risk Profile:**
- Only person who processes all invoices
- Inna backup has other manager duties
- Summer temps require training
- 3+ years accumulated system knowledge
- If Rhodora unavailable: AP operations halt

**Mitigation Needed:**
- Cross-training plan
- Process documentation
- Backup processor enhancement

### Divergent Investment Perspectives

**Rhodora (Processor View):**
- Experiences daily friction points
- Wants optimization features
- Recommends "invest more"
- Focus: Reduce manual touchpoints

**Inna (Manager View):**
- Sees aggregate performance
- Satisfied with current state
- Recommends "keep as is"
- Focus: Maintain stability

**Reconciliation:**
Both perspectives valid; decision should be ROI-driven based on quantified pain point costs vs feature package pricing.

### Approver Engagement Critical

**Month-End Bottleneck:**
- Manual approval reminders needed
- Affects period-end closing timeline
- No system visibility into approval delays
- Automatic reminders would improve throughput

### Peter Assessment Gap

**Unknown Variables:**
- How much time spent on payment file preparation?
- Could SAP-to-bank automation add value?
- Is manual payment assembly causing delays?
- What's ROI potential for payment automation?

**Action:** Interview Peter to complete workflow assessment

---

## Stakeholder Dependencies

**Critical Path:**
Vendor → Scancloud → Ascendo → Rhodora → PO/Delivery (Requisitioner) → Approvers → SAP → Peter → Bank

**Bottleneck Points:**
1. Requisitioner delays creating deliveries
2. Approver delays (especially month-end)
3. Peter's manual payment file preparation

**System Strengths:**
- Ascendo → SAP: Fully automated (zero manual entry)
- OCR: 95-100% accuracy reduces Rhodora touchpoints
- Approval routing: Embedded workflow eliminates SAP module need

---

## Change Management Considerations

### High-Risk Changes (Avoid)
- Altering core OCR or matching logic (could reduce 95-100% accuracy)
- Changing approval routing workflow (could break automation)
- Modifying SAP integration (zero manual entry is key strength)
- UI redesign (users adapted to current interface)

### Medium-Risk Changes (Manage Carefully)
- Adding vendor matching by entity vs bank account (test thoroughly)
- Queue routing logic modifications (ensure no regression)
- New feature packages (avoid unnecessary complexity)

### Low-Risk Changes (Safe to Implement)
- Automatic requisitioner notifications (adds, doesn't replace)
- Automatic approval reminders (adds, doesn't replace)
- Standard message templates (cosmetic enhancement)
- Faster matching status refresh (performance improvement)

---

## Success Metrics by Stakeholder

**Rhodora Success:**
- Reduced correction time for vendor matching
- Fewer invoices bouncing to entrance queue
- Faster requisitioner response to delivery requests
- UI improvements for daily usability

**Inna Success:**
- Maintained system stability
- No regression in core functionality
- Improved period-end closing efficiency
- Enhanced reporting for oversight

**Approvers Success:**
- Clearer approval queue visibility
- Automatic reminders reduce manual follow-up
- Faster overall approval cycle

**Economy Team Success:**
- ROI demonstrated for any investments
- Period-end closing timeline improved
- Audit trail and compliance maintained
- Financial controls strengthened

**Management Success:**
- 900-1,800 hours annual savings maintained
- Zero manual SAP entry preserved
- Investment decisions backed by data
- No disruption to critical operations

---

**Document Status:** Ready for management review  
**Critical Action:** Interview Peter to complete stakeholder assessment  
**Stakeholder Validation:** Rhodora and Inna primary contacts for all system changes

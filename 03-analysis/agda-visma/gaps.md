# Gaps Analysis - Agda PS

## Overview

**System:** Agda PS (Payroll System)
**Analysis Date:** December 2025
**Source:** Interview with Helena (Super User, 7 years experience)

This document identifies missing functionality, integration gaps, and capability limitations that could improve system value or operational efficiency.

---

## 1. Banking System Integration

**Category:** Integration
**Priority:** Medium (Revised from High)
**Impact:** Medium - Manual process is intentional risk mitigation

### Gap Description
No direct integration between Agda PS and banking system. Payroll data must be manually exported and uploaded by Ekonomi team.

### Current Workaround
- Helena manually generates data report
- Report sent to Ekonomi team via email or shared folder
- Ekonomi team manually uploads to banking system

### Business Context - Intentional Manual Control
**Important:** The Ekonomi team's preference for manual transfers reflects a risk-mitigation approach, ensuring full validation control over sensitive payroll and HR data before system entry. This manual step provides:
- Final validation checkpoint before salary payments
- Control over timing of bank transfers
- Opportunity to catch errors before funds are transferred
- Clear accountability and audit trail

### Business Impact
**Costs:**
- Manual work in each payroll cycle (~1-2 hours)
- Requires coordination between HR and Ekonomi teams
- Time spent on data validation

**Benefits of Current Approach:**
- Full validation control over sensitive financial data
- Risk mitigation before irreversible bank transfers
- Clear handoff point with accountability
- Flexibility in transfer timing

### Recommended Solution
**Option 1: Maintain Current Process (Low Risk)**
- Continue manual process given stakeholder preference
- Document validation procedures
- Streamline handoff process if needed

**Option 2: Semi-Automated Integration (Balanced)**
- Implement integration with approval/validation gate
- Data flows automatically but requires Ekonomi team approval before transmission
- Maintains control while reducing manual data generation
- Ekonomi team retains validation checkpoint

**Option 3: Full Automation (Higher Risk)**
- Direct integration without manual intervention
- Would require strong confidence in data accuracy
- May not align with Ekonomi team's risk management approach

### Recommendation
Consult with Ekonomi team before pursuing automation. If they value the manual validation step for risk management, consider Option 2 (semi-automated with approval gate) rather than full automation. The current manual process may be the appropriate solution for this organization's risk tolerance.

### Estimated Benefit (If Automated)
- Time savings: 1-2 hours per payroll cycle
- Reduced coordination overhead
- **Must be weighed against:** Loss of validation control, increased automation risk

### Note for Future Assessment
Interview Ekonomi team to understand:
- Their specific validation requirements
- Risk concerns with direct integration
- Whether semi-automated approach would be acceptable
- True cost/benefit of current manual process

---

## 2. Accounting System Integration

**Category:** Integration
**Priority:** Low to Medium (Revised)
**Impact:** Medium - Similar risk considerations as banking

### Gap Description
No direct integration between Agda PS and accounting system. Payroll data must be manually exported and entered by Ekonomi team.

### Current Workaround
- Manual data generation similar to banking
- Ekonomi team processes data in accounting system
- Manual reconciliation between systems

### Business Context
Similar to banking integration, the Ekonomi team likely values manual control over accounting entries for:
- Data validation before financial impact
- Control over accounting period timing
- Reconciliation and verification
- Clear audit trail

### Business Impact
**Costs:**
- Manual work for Ekonomi team (~1-2 hours per cycle)
- Potential for data inconsistencies
- Manual reconciliation required

**Benefits of Current Approach:**
- Validation control over financial data
- Flexibility in timing of entries
- Manual reconciliation opportunity

### Recommended Solution
**Before pursuing integration:**
- Interview Ekonomi team about their process preferences
- Understand if manual control is valued here as well
- Assess if accounting has different risk profile than banking

**If integration is desired:**
- Semi-automated approach with approval gates
- Maintain validation checkpoints
- Align with Ekonomi team workflow preferences

### Estimated Benefit (If Automated)
- Time savings for Ekonomi team
- Improved data consistency
- **Must be weighed against:** Validation control, risk management needs

---

## 3. Onboarding Module

**Category:** Feature / Functionality
**Priority:** Medium
**Impact:** Medium - Would add new capability

### Gap Description
No onboarding module within Agda PS. New employee setup and onboarding processes are handled outside the system.

### Current Workaround
- Manual onboarding processes
- New employee data entered into Agda PS separately
- No standardized digital onboarding workflow

### Business Impact
- Manual setup for new employees
- Inconsistent onboarding experiences
- No centralized tracking of onboarding completion
- Potential for missed steps or incomplete data

### Recommended Solution
Evaluate and implement Visma's onboarding module or integrate with existing onboarding tools

### Estimated Benefit
- Standardized onboarding process
- Reduced manual setup time
- Better tracking and compliance
- Improved new hire experience
- Complete employee lifecycle in one system

### User Feedback
Helena specifically requested this feature as enhancement

---

## 4. Automated Pension Reporting

**Category:** Process Automation
**Priority:** Low
**Impact:** Low - Small volume, infrequent

### Gap Description
Pension data to government agencies (myndigheter) requires manual generation and submission rather than automated reporting.

### Current Workaround
- Helena manually generates pension data
- Data sent to government agencies via their portals
- Manual process similar to other data transfers

### Business Impact
- Small amount of manual work
- Helena notes it "takes not too much time"
- Potential for reporting errors
- Less efficient than automated compliance reporting

### Recommended Solution
Investigate if Visma offers automated pension reporting similar to other compliance automation

### Estimated Benefit
- Minimal time savings (low volume)
- Improved reporting accuracy
- Consistency with other automated compliance features

---

## 5. Self-Service Adoption Enablement

**Category:** User Experience / Change Management
**Priority:** Low to Medium
**Impact:** Medium - Could reduce HR workload

### Gap Description
While self-service functionality exists, some employees don't use it. There's a gap in change management, training, or user enablement that prevents full adoption.

### Current Situation
- Self-service features are available
- Some employees still submit paper leave requests
- System usability is not the issue
- Gap is in user adoption, not functionality

### Business Impact
- HR team must manually input some leave requests
- Underutilization of purchased features
- Reduced system ROI
- Inconsistent processes

### Recommended Solution
Not a system gap per se, but a change management gap that affects system value:
- Better user training
- Computer literacy support
- Communication of self-service benefits
- Mandatory self-service for new hires

### Estimated Benefit
- 2-4 hours per week saved for HR team
- Better data completeness
- Full value realization of self-service features

---

## 6. Data Entry Validation Rules

**Category:** Data Quality / User Experience
**Priority:** Low
**Impact:** Low - Infrequent issue

### Gap Description
Limited validation rules at data entry point allow incomplete or incorrect time data to be entered, requiring later correction.

### Current Situation
- Employees can submit incomplete time data
- Errors discovered during payroll processing
- Helena must follow up and correct data

### Business Impact
- Processing delays when incomplete data discovered
- Manual follow-up required
- Risk of errors if incomplete data not caught

### Recommended Solution
Implement stronger validation rules and user guidance at data entry point:
- Required field validation
- Format checking
- Real-time feedback to users
- Automated reminders for missing entries

### Estimated Benefit
- Reduced data quality issues
- Fewer processing interruptions
- Less manual follow-up needed

---

## 7. Shift Calculation Configuration

**Category:** Configuration / Temporary Gap
**Priority:** High (Short-term)
**Impact:** Medium - Current operational issue

### Gap Description
Shift time calculations for new shift pattern (October 2025) not yet validated or automated, requiring manual review.

### Current Situation
- New shift schedule implemented October 2025
- System calculates time but Helena must verify accuracy
- Manual review added to otherwise automated process

### Business Impact
- Additional time in each payroll cycle
- Risk of calculation errors
- Temporary reduction in processing efficiency

### Recommended Solution
Work with Visma to configure and validate shift calculation rules for new schedule

### Estimated Benefit
- Eliminate manual review (1-2 hours per cycle)
- Restore full automation
- Return to "very easy" payroll process

### Note
This is a temporary configuration gap related to recent organizational change, not a permanent system limitation

---

## Gaps Summary

### High Priority Gaps

1. **Shift Calculation Configuration** - Current operational issue (temporary)

### Medium Priority Gaps

2. **Banking System Integration** - Revised priority; requires Ekonomi team consultation on risk management approach
3. **Accounting System Integration** - Depends on Ekonomi team process preferences
4. **Onboarding Module** - User-requested feature enhancement
5. **Self-Service Adoption Enablement** - Change management, not system gap

### Low Priority Gaps

6. **Automated Pension Reporting** - Low volume, minimal impact
7. **Data Entry Validation Rules** - Infrequent issue

---

## Gap Categories

### Integration Gaps (Require Stakeholder Consultation)
- Banking system (Medium priority - **intentional manual control for risk management**)
- Accounting system (Low to Medium priority - **similar risk considerations**)

### Feature Gaps
- Onboarding module (Medium priority)
- Automated pension reporting (Low priority)

### Configuration Gaps
- Shift calculation validation (High priority, temporary)

### Data Quality / UX Gaps
- Data entry validation rules (Low priority)
- Self-service adoption (Medium priority, change management)

---

## Overall Assessment

The identified gaps are primarily in two areas:

1. **System Integration:** Missing connections to banking and accounting systems create manual workarounds, **however, these manual processes are intentionally maintained by Ekonomi team for risk management and validation control**
2. **Feature Enhancement:** Onboarding module would add value but is not critical to current operations

Importantly, there are **no gaps in core payroll functionality**. The system handles its primary mission (payroll processing and compliance) very well. 

### Key Insight on Integration Gaps
What initially appeared as integration gaps may actually be **intentional risk management controls**. The Ekonomi team's preference for manual validation of sensitive payroll and financial data before system entry represents a deliberate business decision rather than a technical limitation. Any automation initiatives must respect and potentially incorporate these validation requirements.

---

## Prioritization Rationale

**High Priority:**
- Shift calculation is current operational issue requiring immediate attention

**Medium Priority:**
- Banking/accounting integration **must be evaluated with Ekonomi team** - if they prefer manual control for risk management, these may not be true "gaps" but appropriate controls
- Onboarding module adds new capability, specifically requested by user
- Self-service adoption could reduce HR workload significantly

**Low Priority:**
- Pension reporting has minimal impact (low volume, Helena notes it's quick)
- Data validation is infrequent issue with manageable workarounds

---

## Critical Next Step

**Interview Ekonomi team** to understand:
- Their validation requirements and risk management approach
- Whether they view manual processes as necessary controls or inefficiencies
- Their perspective on semi-automated vs. fully automated integration
- True cost/burden of current manual processes on their workflow
- Appetite for automation with appropriate validation gates

This information is essential before prioritizing integration initiatives, as what appears to be a gap from one perspective may be an intentional control from another.

---

**Document Status:** Draft
**Last Updated:** December 2025
**Next Review:** After Ekonomi team interview - critical for validating integration gap assessment

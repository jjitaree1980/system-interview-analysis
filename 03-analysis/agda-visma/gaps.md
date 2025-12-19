# Gaps Analysis - Agda PS

## Overview

**System:** Agda PS (Payroll System)
**Analysis Date:** December 2025
**Source:** Interview with Helena (Super User, 7 years experience)

This document identifies missing functionality, integration gaps, and capability limitations that could improve system value or operational efficiency.

---

## 1. Banking System Integration

**Category:** Integration
**Priority:** High
**Impact:** High - Affects time-sensitive payroll process

### Gap Description
No direct integration between Agda PS and banking system. Payroll data must be manually exported and uploaded by Ekonomi team.

### Current Workaround
- Helena manually generates data report
- Report sent to Ekonomi team via email or shared folder
- Ekonomi team manually uploads to banking system

### Business Impact
- Manual work in each payroll cycle
- Requires coordination between HR and Ekonomi teams
- Risk of data transfer errors affecting salary payments
- Processing delays if coordination issues occur

### Recommended Solution
Implement direct integration to automate payroll-to-bank data transfer

### Estimated Benefit
- Time savings: 1-2 hours per payroll cycle
- Error reduction: Eliminates manual transfer errors
- Reduced coordination overhead

---

## 2. Accounting System Integration

**Category:** Integration
**Priority:** Medium
**Impact:** Medium - Less time-critical than banking

### Gap Description
No direct integration between Agda PS and accounting system. Payroll data must be manually exported and entered by Ekonomi team.

### Current Workaround
- Manual data generation similar to banking
- Ekonomi team processes data in accounting system
- Manual reconciliation between systems

### Business Impact
- Manual work for Ekonomi team
- Potential for data inconsistencies
- Delayed financial reporting
- Manual reconciliation required

### Recommended Solution
Implement accounting system integration after banking integration is complete

### Estimated Benefit
- Time savings for Ekonomi team
- Improved data consistency
- Faster month-end closing

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

1. **Banking System Integration** - Most impactful, affects time-sensitive process
2. **Shift Calculation Configuration** - Current operational issue (temporary)

### Medium Priority Gaps

3. **Accounting System Integration** - Important but less urgent than banking
4. **Onboarding Module** - User-requested feature enhancement
5. **Self-Service Adoption Enablement** - Change management, not system gap

### Low Priority Gaps

6. **Automated Pension Reporting** - Low volume, minimal impact
7. **Data Entry Validation Rules** - Infrequent issue

---

## Gap Categories

### Integration Gaps
- Banking system (High priority)
- Accounting system (Medium priority)

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

1. **System Integration:** Missing connections to banking and accounting systems create manual workarounds
2. **Feature Enhancement:** Onboarding module would add value but is not critical to current operations

Importantly, there are **no gaps in core payroll functionality**. The system handles its primary mission (payroll processing and compliance) very well. All identified gaps are optimization opportunities rather than critical missing capabilities.

---

## Prioritization Rationale

**High Priority:**
- Banking integration affects time-sensitive, high-risk process (salary payments)
- Shift calculation is current operational issue requiring immediate attention

**Medium Priority:**
- Accounting integration improves efficiency but less time-critical
- Onboarding module adds new capability, specifically requested by user
- Self-service adoption could reduce HR workload significantly

**Low Priority:**
- Pension reporting has minimal impact (low volume, Helena notes it's quick)
- Data validation is infrequent issue with manageable workarounds

---

**Document Status:** Draft
**Last Updated:** December 2025
**Next Review:** After Ekonomi team interview and validation of integration requirements

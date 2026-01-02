# Pain Points - Agda PS

## Overview

**System:** Agda PS (Payroll System)
**Analysis Date:** December 2025
**Source:** Interview with Helena (Super User, 7 years experience)

---

## 1. Manual Shift Time Calculation Review

**Category:** Process / Configuration
**Severity:** Medium
**Frequency:** Every payroll cycle (since October 2025)
**Impact on Business:** Adds time to payroll processing, requires manual validation

### Description
Recent organizational change to shift working times (started October 2025) requires Helena to manually review whether time calculations for the new shift are correct before processing payroll.

### Why This Is a Problem
- Adds manual review step to previously smooth payroll process
- Increases processing time
- Risk of calculation errors if review is missed
- Only current pain point in otherwise "very easy" payroll workflow

### Current Workaround
Manual review and validation for each payroll cycle

### User Quote
> "Currently she need to manual review if the time calculation for this new shift is correct."

### Recommended Solution
- Work with Visma support to configure and validate shift calculation rules
- Test thoroughly with sample data
- Remove manual review once calculations are confirmed accurate

**Priority:** High (addresses current operational pain point)

---

## 2. Manual Banking Data Transfer

**Category:** Integration / Process
**Severity:** Medium
**Frequency:** Every payroll cycle
**Impact on Business:** Manual work, coordination overhead, potential for errors

### Description
Payroll data must be manually generated and sent to the Ekonomi team, who then manually upload it to the banking system.

### Why This Is a Problem
- Manual process in time-sensitive payroll workflow
- Requires coordination between HR and Ekonomi team
- Risk of data transfer errors affecting salary payments
- Adds steps to payroll processing

### Current Workaround
Helena generates data report, sends to Ekonomi team who uploads to bank system

### User Quote
> "Banking: No, manual generate data report then send to Ekonomi team to upload to bank system"

### Recommended Solution
- Implement direct integration between Agda PS and banking system
- Automate data transfer to eliminate manual steps
- Reduce coordination dependency

**Priority:** Medium (time-sensitive, affects critical payroll function)  
**Note:** The Economy team's preference for manual transfers reflects a risk-mitigation approach, ensuring full validation control over sensitive payroll and HR data before system entry.

---

## 3. Manual Accounting Data Transfer

**Category:** Integration / Process
**Severity:** Low to Medium
**Frequency:** Every payroll cycle
**Impact on Business:** Manual work, less time-critical than banking

### Description
Similar to banking, accounting data must be manually generated and transferred to the Ekonomi team for entry into the accounting system.

### Why This Is a Problem
- Adds manual work to payroll cycle
- Potential for data inconsistencies
- Duplicated effort between systems
- Less time-critical than banking but still inefficient

### Current Workaround
Manual data generation and transfer, same process as banking

### User Quote
> "Accounting: No, doing the same way as Banking"

### Recommended Solution
- Implement accounting system integration after banking integration
- Automate data flow to accounting system

**Priority:** Medium (lower urgency than banking, but similar impact)  
**Note:** The Economy team's preference for manual transfers reflects a risk-mitigation approach, ensuring full validation control over sensitive payroll and HR data before system entry.

---

## 4. Paper Leave Requests from Some Employees

**Category:** User Adoption / Change Management
**Severity:** Low
**Frequency:** Ongoing
**Impact on Business:** Manual data entry required, reduces system ROI

### Description
Some employees still submit leave requests on paper instead of using the self-service portal, despite the functionality being available.

### Why This Is a Problem
- HR must manually input leave requests
- Underutilizes purchased self-service features
- Reduces efficiency gains from system
- Potential for data entry errors
- Inconsistent processes across employees

### Current Workaround
HR team manually inputs leave requests from paper submissions

### User Quote
> "Some user still request the leave by paper as it was like that before they start the system and they used to it."

### Root Cause
- Old habits from pre-system processes
- Some users not comfortable with computers
- Lack of change management or training

### Recommended Solution
- Targeted training for users still submitting paper requests
- Computer literacy support for struggling users
- Communicate benefits of self-service
- Consider making self-service mandatory for new hires

**Priority:** Low (manageable impact, more of an optimization opportunity)

---

## 5. Incomplete Time Data

**Category:** Data Quality
**Severity:** Low
**Frequency:** Sometimes
**Impact on Business:** Blocks processing until corrected

### Description
Occasionally, incomplete or incorrect In/Out time data prevents Helena from continuing to the next processing step until the data is fixed.

### Why This Is a Problem
- Delays payroll processing
- Requires follow-up with employees
- Manual data correction needed
- Interrupts workflow

### Current Workaround
Helena follows up to get complete data, enters corrections manually

### User Quote
> "By the incomplete or garbage In/Out data, sometimes she could not continue the next process or the next step could not be start until the data is fixed."

### Root Cause
- User error in time logging
- Lack of validation at data entry point
- Limited employee training on time logging

### Recommended Solution
- Implement data validation rules at entry point
- Provide better user guidance during time logging
- Automated reminders for incomplete entries
- Additional employee training

**Priority:** Low (infrequent, minimal impact)

---

## 6. Manual Pension Data Generation

**Category:** Process
**Severity:** Low
**Frequency:** Regular
**Impact on Business:** Small amount of manual work

### Description
Pension data must be manually generated and sent to myndigheter (government agencies).

### Why This Is a Problem
- Adds manual step to regular processes
- Potential for errors in reporting
- Not integrated with other automated compliance reporting

### Current Workaround
Manual data generation and submission

### User Quote
> "Yes, the manually generate data for payroll to Ekonomi team, Pension data to myndigheter. It takes not too much time but it's manually"

### Recommended Solution
- Investigate automated pension reporting capabilities
- Low priority due to small volume and infrequent occurrence

**Priority:** Low (Helena notes it doesn't take too much time)

---

## 7. Manual Pension Age Updates

**Category:** Data Maintenance
**Severity:** Very Low
**Frequency:** Occasional
**Impact on Business:** Minimal

### Description
Some changes in pension ages require manual review and updates in the system.

### Why This Is a Problem
- Manual data maintenance required
- Potential for missed updates

### Current Workaround
Helena reviews and updates manually as needed

### User Quote
> "Some of change in Pension ages also need to review and change manually, but not much data records."

### Recommended Solution
- Continue current approach (low volume doesn't justify automation)
- Document process for knowledge transfer

**Priority:** Very Low (limited volume, manageable)

---

## Pain Points Summary

### By Priority

**High Priority (Immediate Action):**
1. Manual shift time calculation review
2. Manual banking data transfer

**Medium Priority (Plan for Improvement):**
3. Manual accounting data transfer

**Low Priority (Monitor/Optimize):**
4. Paper leave requests from some employees
5. Incomplete time data
6. Manual pension data generation
7. Manual pension age updates

### By Category

**Integration Issues:**
- Manual banking data transfer
- Manual accounting data transfer

**Process/Configuration:**
- Manual shift time calculation review
- Manual pension data generation
- Manual pension age updates

**User Adoption:**
- Paper leave requests
- Incomplete time data

---

## Overall Assessment

The pain points identified are relatively minor compared to the system's strengths. The most significant issues are:

1. Integration gaps requiring manual data transfers
2. Temporary configuration issue with shift calculations
3. Incomplete user adoption of self-service features

None of these pain points are critical system failures, and all have clear paths to resolution. The system's core payroll functionality is working very well.

---

**Document Status:** Draft
**Last Updated:** December 2025
**Next Review:** After Ekonomi team interview to validate integration pain points

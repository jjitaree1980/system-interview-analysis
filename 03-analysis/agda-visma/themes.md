# Thematic Analysis - Agda PS

## Analysis Overview

**System:** Agda PS (Payroll System)
**Analysis Date:** December 2025
**Total Interviews Analyzed:** 1 (Helena - Super User, 7 years experience)

---

## Identified Themes

### Theme 1: System Stability & Mission-Critical Reliability

**Strength:** Very Strong
**Severity:** High (Positive)
**Category:** Technical / Business Critical

#### What This Theme Is About
Agda PS demonstrates exceptional stability and reliability in handling the company's most critical business function - payroll processing. The system has maintained consistent uptime without major incidents, supporting on-time salary payments.

#### Why This Matters
Payroll is rated 10/10 in criticality. Any system failure during payroll week would result in employees not receiving salaries on time, creating significant business and legal risks. The system's proven stability provides confidence in business continuity.

#### Evidence from Interview

**Interview Helena - Super User:**
> "It would be worst as the employee would not get salary in time. Since she working on the system, it never have that kind of problem."

> "Rating 10/10 because we need to pay the salary in time."

> "Never" [contacts internal IT for Agda PS issues]

> "Rarely, the system quite stable and not much technical issue." [contacts Visma support]

#### Related Observations
- No major system issues in 2.5 years of operation
- Technical problems are rare (new hardware compatibility, occasional upgrades)
- When issues occur, Visma resolves them within 1 business day maximum
- Payroll processing window of 1.5 weeks is always adequate

#### Implications & Recommendations
- **For Design:** System architecture and vendor support model are working well - maintain current approach
- **For Requirements:** No urgent technical stability improvements needed
- **For Priorities:** Focus on optimization rather than replacement; stability is a key strength to preserve

---

### Theme 2: Comprehensive Swedish Regulatory Compliance

**Strength:** Very Strong
**Severity:** High (Positive)
**Category:** Technical / Compliance

#### What This Theme Is About
Agda PS fully handles all Swedish payroll compliance requirements with automatic updates for regulatory changes. The system manages complex statutory reporting to multiple government agencies without manual intervention.

#### Why This Matters
Compliance with Swedish tax and social insurance regulations is mandatory and complex. Manual compliance management would require significant expertise and create risks of errors, penalties, and legal issues. Automated compliance handling is a critical system value.

#### Evidence from Interview

**Interview Helena - Super User:**
> "System is fully handle data compliance to Swedish system: Skatteverket, Social fees, pensions, försäkringskasson, kollektiv fackavgifter"

> "Yes, always updated. For the special customization if it required then it would take short time for support team."

#### Related Observations
- System handles Skatteverket reporting
- Manages Försäkringskassan requirements
- Calculates and reports social fees, pensions, and collective agreement fees
- Regulatory updates are applied automatically by Visma
- Custom compliance requirements can be implemented quickly

#### Implications & Recommendations
- **For Design:** Compliance automation is a core strength - any future system must maintain this capability
- **For Requirements:** Swedish regulatory compliance must remain fully automated
- **For Priorities:** This is a key reason to continue with Agda PS rather than explore alternatives

---

### Theme 3: Manual Data Transfer Workarounds

**Strength:** Moderate
**Severity:** Medium (Negative)
**Category:** Integration / Process

#### What This Theme Is About
Despite time tracking integration, Agda PS requires manual data generation and transfer for banking and accounting systems. This creates manual work in each payroll cycle and potential for human error.

#### Why This Matters
Manual data transfers add time to the payroll process, create potential for data entry errors, and require coordination between HR and Ekonomi teams. While not currently causing major problems, automation would improve efficiency and reduce risk.

#### Evidence from Interview

**Interview Helena - Super User:**
> "Banking: No, manual generate data report then send to Ekonomi team to upload to bank system"

> "Accounting: No, doing the same way as Banking"

> "Yes, the manually generate data for payroll to Ekonomi team, Pension data to myndigheter. It takes not too much time but it's manually"

#### Related Observations
- Time tracking system is successfully integrated
- Banking requires manual data export to Ekonomi team
- Accounting follows same manual process as banking
- Pension data to government agencies is manually generated
- Helena notes these processes don't take excessive time but could be automated

#### Implications & Recommendations
- **For Design:** Explore integration capabilities with banking and accounting systems
- **For Requirements:** Prioritize banking integration over accounting (payroll is more time-sensitive)
- **For Priorities:** Medium priority - system works but automation would improve efficiency

---

### Theme 4: Incomplete User Adoption of Self-Service

**Strength:** Weak
**Severity:** Low (Negative)
**Category:** User Experience / Change Management

#### What This Theme Is About
Some employees continue using paper-based processes for leave requests instead of the self-service system, creating manual work for HR. This stems from old habits and resistance to change rather than system usability issues.

#### Why This Matters
Paper leave requests create unnecessary manual data entry for HR and reduce the time-saving benefits of the system. However, this is a change management issue rather than a technical problem, and the impact is relatively minor.

#### Evidence from Interview

**Interview Helena - Super User:**
> "Some user still request the leave by paper as it was like that before they start the system and they used to it."

> "As they are minimal usage group, they do quite ok and did not much complain about the system. Just few but it was because they are not use to the computer."

#### Related Observations
- Employees are "minimal usage group" with few system complaints
- Issues are primarily due to computer literacy, not system problems
- HR must manually input leave requests from some employees
- Occasionally incomplete time data requires follow-up
- Self-service functionality exists and works, but adoption is incomplete

#### Implications & Recommendations
- **For Design:** System functionality is adequate; focus on user training and change management
- **For Requirements:** No new features needed for this issue
- **For Priorities:** Low priority - address through training rather than system changes

---

### Theme 5: Current Temporary Challenge - Shift Time Calculation

**Strength:** Moderate
**Severity:** Medium (Negative, Temporary)
**Category:** Process / Configuration

#### What This Theme Is About
Recent organizational change to shift working times (October 2025) requires manual review of time calculations. This is a temporary configuration issue related to a specific business change, not a systemic problem.

#### Why This Matters
Manual review adds time to payroll processing and creates risk of calculation errors. However, this appears to be a configuration or validation issue during a transition period rather than a fundamental system limitation.

#### Evidence from Interview

**Interview Helena - Super User:**
> "The company organization just change the shift working time and it was start in October 2025. Currently she need to manual review if the time calculation for this new shift is correct."

#### Related Observations
- This is the only regular pain point mentioned in payroll processing
- Issue is recent (October 2025) and tied to organizational change
- Otherwise payroll process is described as "very easy" with "accurate" data
- System normally saves Helena significant time

#### Implications & Recommendations
- **For Design:** Work with Visma support to validate shift calculation configuration
- **For Requirements:** May need custom configuration or validation rules for new shift patterns
- **For Priorities:** High priority to resolve, but likely temporary issue

---

### Theme 6: High-Quality Vendor Support

**Strength:** Very Strong
**Severity:** High (Positive)
**Category:** Support / Maintenance

#### What This Theme Is About
Visma provides excellent technical support with rapid response times and effective issue resolution. The system requires minimal support intervention, and when issues arise, they are resolved quickly.

#### Why This Matters
For a mission-critical system, vendor support quality is essential. Fast resolution times minimize business disruption and provide confidence that issues will be handled promptly. The combination of system stability and strong support creates low operational risk.

#### Evidence from Interview

**Interview Helena - Super User:**
> "We do not get the issue on payroll yet, but for another tech issue then they are using max 1 business day to resolve it. So the quality of their support is quite excellent."

> "Rarely, the system quite stable and not much technical issue."

#### Related Observations
- Maximum 1 business day resolution time for technical issues
- Support team can implement custom requirements quickly
- No payroll-critical issues have occurred
- Helena never needs to contact internal IT for Agda PS
- Support is described as "quite excellent"

#### Implications & Recommendations
- **For Design:** Vendor relationship and support model are working well - maintain
- **For Requirements:** Continue current support arrangement
- **For Priorities:** This is a key strength supporting the recommendation to continue with Agda PS

---

## Theme Overview Summary

### By Severity (Impact Level)

**High Severity (Positive):**
- System Stability & Mission-Critical Reliability - Proven track record supporting business continuity
- Comprehensive Swedish Regulatory Compliance - Automated handling of complex requirements
- High-Quality Vendor Support - Rapid resolution and strong partnership

**Medium Severity (Negative):**
- Manual Data Transfer Workarounds - Integration gaps create manual work
- Shift Time Calculation Challenge - Temporary configuration issue requiring attention

**Low Severity (Negative):**
- Incomplete User Adoption of Self-Service - Change management issue, not system problem

### By Category

**Technical Themes:**
- System Stability & Mission-Critical Reliability
- Comprehensive Swedish Regulatory Compliance
- High-Quality Vendor Support

**Process Themes:**
- Manual Data Transfer Workarounds
- Shift Time Calculation Challenge

**User Experience / Training Themes:**
- Incomplete User Adoption of Self-Service

---

## Theme Relationships

### Primary Theme Cluster: System Excellence

**Includes themes:** System Stability, Regulatory Compliance, Vendor Support

**Connection:** These three themes together demonstrate that Agda PS excels at its core mission - reliable, compliant payroll processing with strong vendor backing.

**Combined impact:** This cluster explains Helena's strong recommendation to "definitely invest more" in Agda PS rather than explore alternatives. The system's strengths in mission-critical areas outweigh the identified gaps.

### Secondary Theme Cluster: Operational Efficiency Opportunities

**Includes themes:** Manual Data Transfer Workarounds, Shift Time Calculation, User Adoption

**Connection:** These themes represent opportunities to improve efficiency and reduce manual work, but none are critical blockers to system success.

**Combined impact:** These issues can be addressed through configuration, integration work, and training without requiring system replacement.

---

## Key Insights

### Strongest Patterns

1. **System delivers exceptionally well on core payroll requirements:** Stability, accuracy, compliance, and support are all rated very highly. The system successfully handles the most critical business function.

2. **Integration gaps create manageable workarounds:** Manual data transfers to banking and accounting add work but are not causing major problems. These represent optimization opportunities rather than critical failures.

3. **User experience is positive despite minimal engagement:** Employees use the system minimally but successfully. Issues stem from change management and computer literacy rather than system usability problems.

### Unexpected Findings

- Despite being a minimal user group, employees have very few complaints about the system
- No payroll-critical issues in 2.5+ years is exceptional for such a complex system
- The only current pain point (shift calculations) is tied to a recent organizational change, not a systemic issue

### User Sentiment

**Overall Sentiment:** Highly Positive

**Helena (Super User, 7 years experience):**
- **System Criticality:** 10/10
- **Recommendation:** "Definitely invest more" (continue with Agda PS)
- **Support Quality:** "Quite excellent"
- **Payroll Process:** "Very easy" with "accurate" data
- **Time Savings:** System "save a lot of times"

### Critical Themes Requiring Immediate Attention

1. **Shift Time Calculation Review:** High priority to resolve manual review requirement, likely through configuration or validation with Visma support

2. **Banking Integration:** Medium priority to reduce manual data transfer and potential for errors in time-sensitive payroll-to-bank process

---

## Recommendations Based on Themes

### Technical Recommendations

1. Work with Visma to configure and validate shift time calculations for new schedule implemented in October 2025
2. Explore integration options with banking system to automate payroll data transfer
3. Investigate accounting system integration as secondary priority

### Process Recommendations

1. Continue with two-person staffing model for business continuity (currently being implemented)
2. Document manual data transfer workflows to ensure consistency and reduce errors
3. Establish validation checkpoints for manual processes until automation is implemented

### Training/Support Recommendations

1. Conduct targeted training for employees still using paper leave requests
2. Focus change management on demonstrating self-service benefits rather than system features
3. Provide computer literacy support for users struggling with digital tools

### Strategic Recommendations

1. **Continue investment in Agda PS** - System strengths in stability, compliance, and support justify continued use
2. **Focus on optimization, not replacement** - Address integration gaps and configuration issues rather than exploring new systems
3. **Prioritize banking integration** - Highest ROI for reducing manual work in time-sensitive processes
4. **Add onboarding module** - Requested feature would enhance system value without disrupting core functions

---

## Themes to Validate

**Theme: User satisfaction with self-service features**
- **Why this needs validation:** Only one minimal user group perspective captured; would benefit from direct employee feedback
- **How to validate:** Survey or interview employees who use time logging and self-service features

**Theme: Impact of manual data transfers**
- **Why this needs validation:** Helena reports these don't take too much time, but Ekonomi team perspective would provide fuller picture
- **How to validate:** Interview Ekonomi team members who receive manual data exports

---

**Document Status:** Final
**Last Updated:** December 2025
**Interview Source:** Helena (Super User, 7 years Agda PS experience)

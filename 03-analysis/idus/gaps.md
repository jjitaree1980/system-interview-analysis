# Gap Analysis - Idus

## Analysis Overview

**System:** Idus (Maintenance Management System)  
**Analysis Date:** 2024-12-12  
**Analyst:** JJA  
**Total Interviewees:** 1 (Super User)


## Functional Gaps

### Gap 1: No Reporting and Analytics Module

**Current State:** No reporting/analytics module purchased; all reports created manually in Excel  
**Desired State:** Built-in reporting capabilities with real-time analytics and budget tracking  
**Impact:** High  
**Priority:** P1  
**Frequency:** Mentioned by 1 of 1 interviewees

#### Business Impact
Consumes 2+ business days per regular report and 1 hour per investigative report. Prevents real-time visibility into maintenance costs, equipment performance, and budget consumption. No ability to track if spending is within budget limits, preventing proactive cost management.

#### Current Workarounds
- Manual data export to Excel
- Creating custom reports requiring 2+ business days
- Maintaining separate Excel files for planning data and recurring records
- Manual budget tracking in spreadsheets

#### User Evidence
> "No, as Kubal do not purchase report or analytic module, so Tom has too export data and generate his own report in excel... To make a report it use around 2 business days and around 1 hour for the investigate report."

> "Feature for cost following up by the budget. No we do not know if we reach to the budget."

#### Recommended Solution
Purchase Idus reporting/analytics module with real-time budget tracking, equipment performance dashboards, and automated report generation.  
Alternative: integrate with external BI tool (Excel, Power BI, Tableau).

---

### Gap 2: No Mobile Platform Access

**Current State:** Mobile platform module not purchased  
**Desired State:** Mobile access for field technicians to view work orders, asset information, and update status on-site  
**Impact:** High  
**Priority:** P1  
**Frequency:** Mentioned by 1 of 1 interviewees

#### Business Impact
Field technicians cannot access system information at point of work, requiring trips back to control room or reliance on memory. Reduces maintenance efficiency and increases time to complete work orders.

#### Current Workarounds
- Technicians return to control room to check information
- Print work orders and asset information before going to field
- Rely on memory for equipment specifications and history

#### User Evidence
> "The Idus Kubal use right now, we do not purchase for mobile platform."

#### Recommended Solution
Purchase mobile platform module enabling field access to work orders, asset information, maintenance history, and real-time status updates.

---

### Gap 3: No Quick-Logging for Minor Repairs

**Current State:** No mechanism for quickly logging minor maintenance fixes (~5 minutes)  
**Desired State:** Simplified logging process for quick fixes that captures work without full WO creation  
**Impact:** Medium  
**Priority:** P2  
**Frequency:** Mentioned by 1 of 1 interviewees

#### Business Impact
Quick fixes go unlogged, creating incomplete maintenance records. Lost visibility into recurring minor issues that could indicate larger problems. Compliance risk from undocumented work.

#### Current Workarounds
- Quick fixes handled informally without system documentation
- Recurring 5-minute jobs monitored through reports rather than WO entries
- Incomplete maintenance history for assets

#### User Evidence
> "Not all maintenance work is logged in Idus, in case that job is just 5 minutes fix, they do not create any WO in system."

#### Recommended Solution
Create simplified quick-log feature allowing technicians to capture work in 30 seconds or less without full WO process. Include asset ID, issue type, and time spent.

---

### Gap 4: Limited BOM Customization

**Current State:** BOM structure has fixed columns  
**Desired State:** Customizable BOM with additional columns for specific information  
**Impact:** Low  
**Priority:** P3  
**Frequency:** Mentioned by 1 of 1 interviewees

#### Business Impact
Cannot capture all relevant information in BOM structure, requiring additional documentation outside system.

#### Current Workarounds
- Maintaining supplemental documentation outside Idus
- Using notes fields for information that should have dedicated columns

#### User Evidence
> "Customization of the BOM information to have more columns for few informations"

#### Recommended Solution
Add BOM customization capability allowing users to add custom fields relevant to their specific maintenance needs.

---

### Gap 5: No Outsource Service Management

**Current State:** No automated feature for managing regular checkups with outsourced services  
**Desired State:** Automated scheduling and reminder system for outsourced maintenance services  
**Impact:** Low  
**Priority:** P3  
**Frequency:** Mentioned by 1 of 1 interviewees

#### Business Impact
Manual tracking of outsource service schedules increases risk of missing regular checkups.

#### Current Workarounds
- Using basic Idus reminder function to generate manual notes
- Manual calendar tracking

#### User Evidence
> "A feature they can setup the regular checkup to the outsource, by now they applied the function reminder in Idus to generate the note for them."

#### Recommended Solution
Implement outsource service management feature with automated scheduling, reminders, and vendor contact integration.

---

## Integration Gaps

### Gap 1: Broken SAP Inventory Integration

**Systems Involved:** Idus ↔ SAP Inventory  
**Impact:** High  
**Priority:** P1

#### The Problem
Integration between Idus and SAP inventory system is broken. Integration code cannot be fixed until Idus version is upgraded. Inventory stock levels in Idus are unreliable, making it impossible to trust data for work order planning.

#### Who's Affected
Technicians, Super User, Warehouse Staff, Maintenance Planning

#### Business Consequences
Technicians cannot effectively plan work orders due to unreliable parts availability information. Forces manual verification of all parts, significantly delaying maintenance execution. Increases coordination burden on warehouse staff.

#### Manual Process Required
- IT developed custom warehouse search program to check SAP directly
- Technicians manually coordinate with warehouse before work
- Manual verification of parts availability for each WO
- IT implemented barcode scanner workaround for spare part requests

---

### Gap 2: No Procurement Module Integration

**Systems Involved:** Idus ↔ Procurement System  
**Impact:** Medium  
**Priority:** P2

#### The Problem
Idus does not integrate with procurement module. When spare parts are needed, technicians must physically visit warehouse, and warehouse staff must manually create orders.

#### Who's Affected
Technicians, Warehouse Staff, Procurement Team

#### Business Consequences
Inefficient procurement process creates delays in obtaining parts. Increased workload on warehouse staff. No automated procurement workflow based on inventory levels or maintenance schedules.

#### Manual Process Required
- Technicians physically visit warehouse for part requests
- Warehouse staff manually place orders on behalf of technicians
- No automated reorder points or procurement triggers

---

## Data Gaps

### Missing Data Quality: Clean and Accurate Asset Data

**Who Needs It:** All users  
**Impact:** High  
**Frequency:** Continuous issue

#### Why It's Needed
Reliable asset data is foundation for all maintenance planning and decision-making. Data quality issues undermine trust in system and affect operational effectiveness.

#### Current Workaround
Users work with existing data quality issues and manually verify critical information. Cross-reference with other systems when accuracy is critical.

#### Impact of Gap
User only "somewhat confident" in data accuracy. Potential errors in maintenance decisions. Reduced trust in system leads to increased manual verification and workarounds.

---

### Missing Module: Summarized Maintenance History by Asset

**Who Needs It:** Management, Super User, Maintenance Planning  
**Impact:** Medium  
**Frequency:** Often (for analysis and reporting)

#### Why It's Needed
Comprehensive maintenance history reports by asset support equipment lifecycle analysis, predictive maintenance planning, and budget forecasting.

#### Current Workaround
Manual data compilation from multiple sources. Limited historical analysis capability.

#### Impact of Gap
Cannot generate comprehensive maintenance history summaries. Limited ability to analyze equipment performance trends over time.

---

## Reporting Gaps

### Report Needed: Real-Time Budget Tracking

**Current State:** No budget tracking capability in system  
**Impact:** High  
**Priority:** P1  
**Requested By:** Management, Super User

#### Business Need
Need real-time visibility into maintenance spending against budget to enable proactive cost management and prevent budget overruns.

#### Required Data Elements
- Actual maintenance costs by period
- Budget allocation by category
- Variance analysis
- Spending trends
- Forecast to year-end

#### Current Alternative
Manual Excel tracking requiring significant time investment. No real-time visibility.

#### Frequency Needed
Daily for operational decisions; Monthly for management reporting

---

### Report Needed: Equipment Performance and Maintenance Cost Analysis

**Current State:** No equipment performance reporting module  
**Impact:** High  
**Priority:** P1  
**Requested By:** Management, Maintenance Planning

#### Business Need
Need to analyze which equipment has highest maintenance costs, most frequent failures, and longest downtime to support capital planning and maintenance strategy decisions.

#### Required Data Elements
- Maintenance cost by asset
- Failure frequency by asset
- Downtime duration and impact
- Mean time between failures (MTBF)
- Mean time to repair (MTTR)
- Total cost of ownership by asset

#### Current Alternative
Manual data export and Excel analysis taking 2+ business days

#### Frequency Needed
Monthly for management review; On-demand for specific analysis

---

### Report Needed: Maintenance Planning and Workload Analysis

**Current State:** Limited planning visibility  
**Impact:** Medium  
**Priority:** P2  
**Requested By:** Maintenance Planning, Super User

#### Business Need
Need visibility into maintenance workload, technician capacity, and PM schedule adherence to optimize resource allocation.

#### Required Data Elements
- Planned vs actual PM completion
- Work order backlog by priority
- Technician workload and capacity
- Schedule adherence metrics
- Resource utilization

#### Current Alternative
Manual tracking in Excel spreadsheets maintained separately

#### Frequency Needed
Weekly for operational planning

---

## Usability Gaps

### Gap: Asset Search Difficulty for Non-Technical Users

**Impact:** Medium  
**Affected Users:** Blue-collar workers, Production team (~40-50% of potential users)

#### The Problem
Blue-collar workers and production team members struggle to locate assets in Idus, finding phone/email easier than system navigation. Creates system bypass behavior and incomplete data capture.

#### User Frustration Level
Medium - Users prefer alternative methods (phone/email) over system, indicating significant usability barrier

#### Time Wasted
Estimated 5-10 minutes per incident when users call/email instead of using system; accumulates to significant time loss across organization

#### Suggested Improvement
Simplified asset search with multiple search methods (equipment name, location, visual navigation, barcode scan). Targeted training for blue-collar workers. Potential mobile app with simpler interface.

---

### Gap: Slow System Performance

**Impact:** Medium  
**Affected Users:** All users (~30 users)

#### The Problem
System runs slowly due to local/on-premises infrastructure, affecting daily productivity and user experience.

#### User Frustration Level
Medium - Continuous issue affecting all daily interactions

#### Time Wasted
Small delays accumulate throughout day; estimated 10-15% productivity loss from slow response times

#### Suggested Improvement
Cloud migration to improve performance; technical assessment to identify optimization opportunities; infrastructure upgrade.

---

## Gap Summary

### By Category

**Functional Gaps:**
- High: 2 (Reporting/analytics, Mobile platform)
- Medium: 1 (Quick-logging)
- Low: 2 (BOM customization, Outsource management)

**Integration Gaps:**
- High: 1 (SAP inventory)
- Medium: 1 (Procurement)

**Data Gaps:**
- High: 1 (Data quality)
- Medium: 1 (Maintenance history module)

**Reporting Gaps:**
- High: 2 (Budget tracking, Equipment performance)
- Medium: 1 (Planning/workload analysis)

**Usability Gaps:**
- Medium: 2 (Asset search, Performance)

### Overall Statistics

**Total Gaps Identified:** 14  
**Critical/P1 Gaps:** 6  
**High Priority/P2 Gaps:** 3  
**Medium Priority/P3 Gaps:** 2  
**Low Priority Gaps:** 3

---

## Priority Gaps (Immediate Action Required)

1. **Broken SAP Inventory Integration** - Integration - Cannot plan work orders without reliable parts data; requires version upgrade
2. **No Reporting/Analytics Module** - Reporting - 2+ days per report; no budget visibility; prevents data-driven decisions
3. **No Mobile Platform** - Functional - Field technicians cannot access information at point of work
4. **Data Quality Issues** - Data - Foundation issue affecting trust and decision-making across all users
5. **Real-Time Budget Tracking** - Reporting - No visibility into spending vs budget; prevents proactive cost management
6. **Equipment Performance Reporting** - Reporting - Cannot analyze maintenance costs and equipment reliability for strategic decisions

---

## Key Insights

**Common Patterns:**
- Multiple gaps stem from modules not purchased during initial implementation (reporting, mobile, procurement, history)
- Technical debt from delayed version upgrade creating cascading problems
- Usability gaps particularly affect non-technical user groups

**Root Causes:**
- Budget-constrained initial implementation missing critical modules
- Delayed version upgrade preventing integration fixes
- Incomplete data cleansing during Maximo migration
- Local/on-premises infrastructure limiting performance
- Insufficient consideration of non-technical user needs

**Impact on Workflows:**
- Manual workarounds consuming significant time (2+ days for reporting)
- System bypass behavior creating incomplete records
- Delayed maintenance execution due to parts coordination issues
- Limited data-driven decision-making capability

**Competitive Disadvantage:**
- Lack of real-time reporting puts organization behind industry standards
- No mobile access reduces field technician efficiency
- Manual processes increase labor costs vs automated competitors

---

## Recommended Actions

### Immediate (0-3 months)
1. **Execute version upgrade** to restore SAP integration (prerequisite: data cleansing)
2. **Purchase reporting/analytics module** for immediate ROI through time savings
3. **Conduct data cleansing project** to improve data quality and enable upgrade

### Short-term (3-6 months)
1. **Purchase mobile platform module** to enable field technician efficiency
2. **Implement quick-logging mechanism** to capture informal maintenance work
3. **Develop targeted training** for blue-collar workers and production team

### Medium-term (6-12 months)
1. **Evaluate cloud migration** for performance improvement
2. **Assess procurement module integration** to reduce manual coordination
3. **Purchase maintenance history reporting module** for better analytics
4. **Implement outsource service management** feature

---

**Document Status:** Draft  
**Last Updated:** 2024-12-12 by JJA  
**Next Steps:** Validate gaps with additional user interviews; prioritize based on ROI analysis *If necessary*

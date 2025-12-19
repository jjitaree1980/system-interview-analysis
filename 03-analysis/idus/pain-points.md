# Pain Points Analysis - Idus

## Analysis Overview

**System:** Idus (Maintenance Management System)  
**Analysis Date:** 2025-12-12  
**Analyst:** JJA  
**Total Interviewees:** 1 (Super User)

---

## Critical Pain Points (High Impact, High Frequency)

### 1. Broken SAP Inventory Integration

**Impact:** High  
**Frequency:** Always (continuous issue)  
**Affected Roles:** Technicians, Super User, Warehouse Staff  
**Business Impact:** Technicians cannot trust inventory data for work order planning; requires manual warehouse coordination; delays maintenance execution

#### Description
SAP inventory integration has been broken since Kubal did not upgrade Idus version. Integration code is broken and cannot be fixed without upgrading to current version. This makes inventory stock unreliable and forces technicians to manually verify parts availability, significantly impacting work planning efficiency.

#### What Users Are Saying
> "It was with the inventory in SAP that can check and reliable the inventory from SAP. But since Kubal do not upgrade the version and some integrate code is broke -- no one from Idus can fix it until we upgrade the version. So now we can not truely trust the inventory in stock which lead to it's hard for the technician to plan their WO."

#### Current Workarounds
- IT developed custom warehouse search program to check SAP inventory directly
- Manual coordination between technicians and warehouse staff
- IT implemented barcode scanner system using Idus data for spare part requests

#### Potential Solutions
1. **Execute Version Upgrade:** Upgrade Idus to current version to enable integration fix (prerequisite: data cleansing)
2. **Temporary API Bridge:** Develop interim integration solution while planning upgrade
3. **Enhanced Workaround:** Improve custom warehouse search tool with real-time sync capability

---

### 2. No Reporting and Analytics Module

**Impact:** High  
**Frequency:** Often (regular reporting needs)  
**Affected Roles:** Super User, Management  
**Business Impact:** 2+ business days consumed per report; 1 hour per investigative report; no real-time visibility into maintenance costs, equipment performance, or budget consumption

#### Description
Kubal did not purchase the reporting or analytics module for Idus. This forces manual data export and Excel-based report creation for all management and analysis reporting. No ability to track costs against budget within the system, preventing proactive budget management.

#### What Users Are Saying
> "No, as Kubal do not purchase report or analytic module, so Tom has too export data and generate his own report in excel -- also control some extra of his plan or recuring record in the excel. To make a report it use around 2 business days and around 1 hour for the investigate report."

> "Feature for cost following up by the budget. No we do not know if we reach to the budget. By now they are create manually report in excel to get that data and it takes time."

#### Current Workarounds
- Manual data export to Excel
- Maintaining planning data and recurring records in separate Excel files
- Creating custom reports requiring 2+ business days

#### Potential Solutions
1. **Purchase Analytics Module:** Immediate ROI through time savings (2+ days/month)
2. **Business Intelligence Integration:** Connect Idus to external BI tool (Power BI, Tableau)
3. **Custom Reporting Dashboard:** Develop internal reporting layer on top of Idus database

---

### 3. Data Quality and Accuracy Issues

**Impact:** High  
**Frequency:** Often (ongoing data reliability concerns)  
**Affected Roles:** All users  
**Business Impact:** Reduced confidence in system data; potential errors in decision-making; incomplete maintenance records

#### Description
Data was not properly cleansed during migration from Maximo to Idus, resulting in ongoing data quality issues. User is only "somewhat confident" in data accuracy, which undermines trust in the system and affects data-driven decision-making.

#### What Users Are Saying
> "Somewhat confident, Idus do not manipulate the data but it was because of some of data was not cleansing before Kubal migrated from Maximo to Idus. So it seems user error."

#### Current Workarounds
- Users work with existing data quality issues
- Manual verification of critical data
- Cross-referencing with other systems

#### Potential Solutions
1. **Data Cleansing Project:** Conduct comprehensive data audit and cleanup (identified as prerequisite for version upgrade)
2. **Data Governance Framework:** Establish ongoing data quality standards and validation processes
3. **User Training:** Train users on proper data entry to prevent future quality issues

---

## Significant Pain Points (Medium Impact or Frequency)

### 4. Slow System Performance

**Impact:** Medium  
**Frequency:** Always (continuous issue)  
**Affected Roles:** All users

#### Description
System runs slowly due to local/on-premises infrastructure. Performance issues affect daily productivity and user experience across all functions.

#### User Evidence
- "It quite slow but it could be because we are working with the local, it might be faster if it upgrade to cloud"
- Daily operations impacted by slow response times

#### Recommended Actions
- Evaluate cloud migration for performance improvement
- Conduct technical performance assessment
- Compare with cloud deployment benchmarks

---

### 5. No Procurement Module Integration

**Impact:** Medium  
**Frequency:** Always (whenever spare parts needed)  
**Affected Roles:** Technicians, Warehouse Staff

#### Description
Idus does not integrate with procurement module. When spare parts are needed, technicians must physically visit warehouse, and warehouse staff manually place orders on their behalf, creating inefficient processes.

#### User Evidence
- "Idus also do not integrate to the procurement module, so in case there are needed for spare part, they need to go to warehouse then warehouse will fix the order for them"
- Manual coordination creates delays in maintenance execution

#### Recommended Actions
- Evaluate procurement module integration or purchase
- Assess cost-benefit of automated procurement workflows
- Consider integration with existing procurement systems

---

### 6. Incomplete User Adoption and System Bypass

**Impact:** Medium  
**Frequency:** Often (regular occurrence)  
**Affected Roles:** Blue-collar workers, Production team

#### Description
Significant portions of organization bypass Idus for phone/email reporting. Blue-collar workers struggle to find assets in system. Quick fixes (~5 minutes) are not logged. Not all maintenance work captured in system, creating incomplete records and potential compliance risks.

#### User Evidence
- "It's mix, some they can use it but some of blue collar -- sometimes they could not find out the asset in Idus, so it's easy for them to call or email. Sometimes Production team not submit the ticket in Idus but call or email instead"
- "Not all maintenance work is logged in Idus, in case that job is just 5 minutes fix, they do not create any WO in system"

#### Recommended Actions
- Develop targeted training for blue-collar workers and production teams
- Improve asset search and discovery features
- Create quick-logging mechanism for minor repairs
- Conduct usability testing with representative users

---

### 7. No Mobile Platform Access

**Impact:** Medium  
**Frequency:** Always (continuous limitation)  
**Affected Roles:** Field technicians

#### Description
Mobile platform module not purchased, limiting accessibility for field technicians who need information at point of work. Reduces efficiency for maintenance activities outside control room.

#### User Evidence
- "The Idus Kubal use right now, we do not purchase for mobile platform"
- Field technicians cannot access system information on-site

#### Recommended Actions
- Purchase mobile platform module
- Evaluate mobile-first design for field operations
- Assess field technician workflow requirements

---

## Minor Pain Points (Low Impact, Infrequent)

- **Limited BOM Customization:** Need more columns for specific information in BOM structure | Impact: Low
- **No Outsource Service Management:** No automated feature for regular checkup schedules with outsourced services; currently using manual reminder workaround | Impact: Low
- **No Budget Tracking Feature:** Cannot track maintenance costs against budget in real-time within system | Impact: Low (covered under reporting pain point)
- **Module for Maintenance History Not Purchased:** Cannot generate summarized maintenance history reports by asset | Impact: Low

---

## Pain Points by Category

### Technical Issues
- Broken SAP Inventory Integration
- Data Quality and Accuracy Issues
- Slow System Performance

### Data & Reporting
- No Reporting and Analytics Module
- Module for Maintenance History Not Purchased
- No Budget Tracking Feature

### Integration & System Connections
- Broken SAP Inventory Integration
- No Procurement Module Integration

### Usability & User Experience
- Incomplete User Adoption and System Bypass
- No Mobile Platform Access
- Limited BOM Customization

### Process & Workflow
- No Outsource Service Management
- Incomplete User Adoption and System Bypass

---

## Summary Overview

**Total Pain Points Identified:** 11

**By Severity:**
- Critical (High Impact + High Frequency): 3
- Significant (Medium Impact or Frequency): 4
- Minor (Low Impact or Frequency): 4

**By Category:**
- Technical: 3
- Data/Reporting: 3
- Integration: 2
- Usability: 3
- Process: 2

**Top 3 Priority Areas:**
1. Version Upgrade (enables SAP integration fix and unlocks other improvements)
2. Analytics/Reporting Module Purchase (immediate ROI through time savings)
3. Data Quality and Governance (foundational for reliable system usage)

---

## Key Insights

**Common Patterns:**
- Multiple pain points stem from modules not purchased (reporting, mobile, procurement, history reports) - suggests budget-constrained initial implementation
- Technical debt from delayed version upgrade creating cascading problems
- Strong core capabilities (asset management) but weak peripheral functionality

**Root Causes:**
- Delayed version upgrade preventing integration fixes and feature access
- Incomplete module purchasing during initial implementation
- Inadequate data cleansing during Maximo to Idus migration
- Local/on-premises infrastructure limiting performance

**Quick Wins:**
- Purchase reporting/analytics module (clear ROI: 2+ days/month time savings)
- Develop targeted training for low-adoption user groups
- Improve asset search functionality for easier discovery

---

## Recommended Next Steps

1. **Execute Version Upgrade (URGENT):** Restore SAP inventory integration; prerequisite for other improvements. Requires data cleansing first.

2. **Purchase Reporting/Analytics Module (HIGH PRIORITY):** Immediate ROI through elimination of 2+ day manual reporting cycles; enables real-time budget tracking and performance visibility.

3. **Conduct Data Cleansing Project:** Address migration legacy issues; establish data governance framework; prerequisite for successful version upgrade.

4. **Purchase Mobile Platform Module (HIGH PRIORITY):** Enable field technician efficiency and real-time access to equipment information.

5. **Evaluate Cloud or Web-based Migration:** Assess performance improvement potential, cost-benefit, and implementation timeline.

6. **Develop User Training Program:** Target blue-collar workers and production teams to improve adoption and reduce system bypass.

---

**Document Status:** Draft  
**Last Updated:** 2025-12-12 by JJA  
**Next Steps:** Validate pain points with additional user interviews (technicians, blue-collar workers, production team) *If necessary*

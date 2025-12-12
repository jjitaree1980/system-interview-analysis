# Interview Notes

## Interview Details
 
**System:** Idus  
**Date:** 2025-12-10  
**Time:** 13:00-14:15 | **Duration:** 75 minutes  
**Location:** In-person  
**Interviewer(s):** JJA  
**Note-taker:** JJA


## Interviewee Profile

**Name:** Tom Löfgren  
**Role:** Teknik Ingenjör  
**Department:** UH  
**Experience:** ca 4 years with company  
**Usage Frequency:** Daily


## Pre-Interview Context

Idus Maintenance System helps you plan, follow up and improve maintenance together idus, providing a complete enterprise-wide solution for managing all aspects of maintenance operations.

- Kubal still user old version of v.8.9.1
- Current version of Idus is v.10
- Currenly we did not purchase report & analytic tool


# Interview Discussion

## 1. General Overview & Current Usage

### Q: What is your role, and how long have you been the super user for Idus?

**A:** 
- Tom serves as the functional technician and is also responsible for integration with Idus
- Primary routine involves analyzing fault reports (FA) from users and making initial decisions on whether they should be converted into work orders (WO) in Idus
- Generates maintenance reports, including all management and analysis reports
- Maintains user accounts in Idus together with Elena

### Q: What is Idus used for in our maintenance operation? Who uses it?

**A:** 
- Used for tracking work orders (WO), preventive maintenance (PM) planning, and asset management
- Primary users include operators and UH technicians

### Q: How many maintenance requests does the system handle per month? How many assets are tracked?

**A:**
- Approximately 1,800 tickets per month, including both fault reports (FA) and preventive maintenance (PM) tasks
- All capital assets in Kubal are tracked in Idus

**Notes:**
- System currently has approximately 30 active users


## 2. Technical & Functional Aspects

### Q: Does Idus help reduce equipment downtime or prevent failures?

**A:** Yes, significantly. Downtime reduction is achieved through preventive maintenance plans set up in Idus

### Q: What types of maintenance does Idus handle?

**A:** Idus primarily handles reactive and preventive maintenance
- Predictive maintenance features are not currently utilized in Idus
- UH performs manual condition monitoring through PM plans

### Q: How well is preventive maintenance being tracked and executed?

**A:** PM planning is quite effective, with most PM schedules being followed.  
Some PM tasks are occasionally skipped depending on Production department priorities

### Q: On a scale of 1-10, how critical is this system to maintenance operations? Why?

**A:** Rating: 9/10. UH relies on Idus to control their work and manage planning activities

### Q: What would happen if Idus was unavailable for a week?

**A:** UH would face significant challenges managing work orders and PM plans. Tracking and maintaining critical production line assets would become difficult

**Notes:**
- Integration issues exist with the inventory system in SAP, resulting in inaccurate stock data
- This inaccuracy makes it difficult to run automatic planning or generate comprehensive reports
- Several reports regarding planning and inventory are currently managed through Excel and an in-house warehouse search application (customized by IT)
- Uncertain if Idus has predictive maintenance features; current Kubal assets are not equipped for predictive maintenance
- Some specialized equipment (e.g., snif) has dedicated tools for failure prediction and downtime forecasting


## 3. User Experience & Workflows

### Q: How frequently do you use Idus?

**A:** Daily

### Q: What is the typical maintenance workflow in Idus?

**A:** 
- Process begins with a fault report (FA)
- Tom reviews the FA together with the shift leader to determine if it should become a work order (WO) in Idus
- If approved, a WO is generated and assigned to a technician
- Technician checks spare part availability with the warehouse, completes the work, and submits a report
- PM workflow follows a similar process

### Q: Do people actually use Idus to submit maintenance requests, or do they call/email?

**A:** It's a mixed approach.
- Some users can use the system effectively
- Blue-collar workers sometimes cannot locate assets in Idus, making it easier for them to call or email instead
- Production team occasionally bypasses Idus and uses phone or email for requests

### Q: Is all maintenance work logged in Idus vs. handled informally?

**A:** Not all maintenance work is logged in Idus.
- Quick fixes (approximately 5 minutes) typically don't generate a WO in the system
- Technicians monitor their maintenance plans and adjust accordingly

### Q: What about recurring requests that are 5-minute jobs?

**A:** These are monitored through reports rather than individual WO entries.

### Q: What do maintenance technicians appreciate most about Idus?

**A:** 
- Graphical interface that makes it easy to navigate object locations
- Spare parts list connected to asset structure (BOM hierarchy)

### Q: How complete is the asset/equipment database in Idus?

**A:** All valuable assets are registered in Idus with comprehensive information including:
  - Specifications
  - Location
  - Maintenance history
  - Spare parts list
  - Asset manuals

### Q: Can technicians easily access equipment history and documentation?

**A:** Technicians can access failure history for assets/objects. Equipment manuals and specifications are available in the system.

### Q: How often do you engate IT support for Idus issues?

**A:** Rarely.

**Notes:**
- Checking spare parts in SAP can be complex due to the layout
- UH also uses an in-house application called "Stopptider" to enter downtime data (unclear if this is due to Idus lacking this feature or if the custom solution better fits legacy requirements)
- Kubal's current Idus implementation does not include the mobile platform module
- Unable to generate summarized maintenance history reports by asset, as Kubal has not purchased that module

## 4. Pain Points & Challenges

### Q: How is the performance of the system?

**A:** System performance is quite slow. This may be due to the local/on-premises installation; performance might improve with a cloud-based upgrade.

### Q: Does Idus integrate with other systems?

**A:** 
- **SAP Inventory Integration:**
  - Previously integrated with inventory in SAP for checking and validating stock levels
  - Integration has been broken since Kubal did not upgrade to the latest version
  - Idus support cannot fix the integration issues until the version is upgraded
  - Current inventory data cannot be fully trusted, making it difficult for technicians to plan their work orders
  - UH has requested IT to customize a warehouse search program to easily check inventory stock in SAP

- **Procurement Module:**
  - No integration with procurement module
  - When spare parts are needed, technicians must go to the warehouse, and warehouse staff place orders on their behalf

### Q: Can you generate reports on equipment performance and maintenance costs?

**A:** No, Kubal has not purchased the reporting or analytics module.
- Tom must export data and generate custom reports in Excel
- Also maintains additional planning data and recurring records in Excel
- Report generation takes approximately 2 business days
- Investigative reports take approximately 1 hour each

**Notes:**
- No manual data transfers to other systems are required
- IT has utilized Idus data for the warehouse barcode scanner system, making it easier for technicians to request spare parts using WO numbers

**Key Pain Points Identified:**

1. **Slow System Performance**
   - Severity: Medium
   - Frequency: Always
   - Impact: Reduced productivity and slower user experience during daily operations; affects efficiency of maintenance workflows
   - Current workaround: Users tolerate the slow performance; cloud-based upgrade has been identified as potential solution

2. **Broken SAP Inventory Integration**
   - Severity: High
   - Frequency: Always
   - Impact: Inventory data cannot be fully trusted, making it difficult for technicians to plan work orders effectively; unable to rely on accurate stock levels for maintenance planning
   - Current workaround: IT has customized a warehouse search program to allow direct checking of inventory stock in SAP; integration cannot be fixed until Idus version is upgraded

3. **No Procurement Module Integration**
   - Severity: Medium
   - Frequency: Always (whenever spare parts are needed)
   - Impact: Inefficient process requiring technicians to physically visit warehouse for spare part requests; warehouse staff must manually place orders on their behalf
   - Current workaround: Manual coordination between technicians and warehouse staff; IT has implemented barcode scanner system using Idus data to streamline spare part requests by WO number

4. **Limited Reporting and Analytics Capabilities**
   - Severity: High
   - Frequency: Often
   - Impact: Report generation is time-intensive (approximately 2 business days per report, 1 hour for investigative reports); inability to generate equipment performance and maintenance cost reports directly from system; requires manual data export and analysis
   - Current workaround: Tom manually exports data and creates custom reports in Excel; maintains additional planning data and recurring records separately in Excel

---

## 5. Data Management & Reporting

### Q: How confident are you in the accuracy of data in Idus?

**A:** Somewhat confident, Idus do not manipulate the data but it was because of some of data was not cleansing before Kubal migrated from Maximo to Idus. So it seems user error.

**Notes:**
- 
- 

---

### 6. Future State & Wishlist

**Q:** [Question asked]

**A:** [Response]

**Requested Features:**
- 
- 

---

## Key Insights

### 💬 Notable Quotes

> "[Quote 1 - context]"

> "[Quote 2 - context]"

> "[Quote 3 - context]"

### 🎯 Main Themes

- [ ] **[Theme 1]:** [Brief description]
- [ ] **[Theme 2]:** [Brief description]
- [ ] **[Theme 3]:** [Brief description]
- [ ] **[Theme 4]:** [Brief description]

### ✅ What's Working Well

- 
- 
- 

### ❌ What Needs Improvement

- 
- 
- 

---

## Follow-up Actions

**🔍 Item 1:** [Description]  
→ Owner: [Name] | Due: [Date] | Status: [Not Started / In Progress / Complete]

**🔍 Item 2:** [Description]  
→ Owner: [Name] | Due: [Date] | Status: [Not Started / In Progress / Complete]

**🔍 Item 3:** [Description]  
→ Owner: [Name] | Due: [Date] | Status: [Not Started / In Progress / Complete]

---

## Interviewer Observations

*Non-verbal cues, engagement level, tone, notable impressions*

**Engagement Level:** [High / Medium / Low]

**Overall Tone:** [Enthusiastic / Frustrated / Neutral / etc.]

**Key Observations:**
- 
- 
- 

---

## Additional Notes

*Any other relevant information, context, or connections to other interviews*

- 
- 

---

## Document Control

**Notes completed by:** [Name] on [YYYY-MM-DD]  
**Reviewed by:** [Name] on [YYYY-MM-DD]  
**Status:** [Draft / Final / Archived]

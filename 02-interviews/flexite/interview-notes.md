# Interview Notes

## Interview Details

**System:** Flexite  
**Date:** 2026-01-08  
**Time:** [13:00 - 13:50] | **Duration:** [50 minutes]  
**Location:** [In-person]  
**Interviewer(s):** JJA  
**Note-taker:** JJA

---

## Interviewee Profile

**Name:** Jan-Eric Berglund  
**Role:** Säkerhet & skydd ledare    
**Department:** Säkerhet & skydd  
**Experience:** [3 years with company] | [5 yr+ using system]  
**Usage Frequency:** Daily

---

## Pre-Interview Context

**Primary Purpose:**  
Swedish incident and deviation management system for workplace incidents, near-misses, safety observations, quality deviations, and improvement suggestions.  

Core Functions:  

- Incident registration and tracking
- Root cause analysis and CAPA tracking
- Risk assessment and classification
- Investigation management and reporting

Swedish Compliance Context:

- Arbetsmiljöverket compliance
- Systematic work environment management (SAM)
- Collective agreement reporting requirements

Key Integration Points:

- Government system (Arbetsmiljösverkety, försäkringkassan, landstyrelsen, mm.)
- HR systems (personnel/org structure)
- SAP (equipment, cost centers, departments)
- Idus CMMS (maintenance incidents)

---

# Interview Discussion

## 1. General Overview & Current Usage

### Q: How long have you been the super user for Flexite?  
**A:**  
- At Kubal for approximately 3 years (since 2023)
- Started working with Flexite in 2017


### Q: What's your role in relation to health and safety management?  
**A:**  
- Multiple responsibilities, but primarily manages and controls safety policies to ensure alignment with company standards and Swedish law
- Serves as government contact for incident reporting



### Q: What types of incidents does Flexite handle?  
**A:**  
- Accidents, near-misses, property damage, unsafe conditions
- Safety risk observations



### Q: How many incident reports does the company typically receive per month through Flexite?  
**A:**  
- Monthly reports: 120-140 incidents
- Total for 2025: 1,572 reports
- Government agency reports: approximately 12 cases per month in 2025



### Q: What would happen if Flexite was unavailable for a week? How would incidents be reported?  
**A:**  
- Production process would continue
- Safety compliance control and alignment would be difficult, even with manual management
- Backup system exists for the platform



### Q: On a scale of 1-10, how critical is this system for health and safety compliance?  
**A:**  
**Rating:** 9 / 10  
**Reasoning:**
- Critical for controlling company alignment with Swedish safety compliance law
- System maintains information that enables creation of preventive procedures, which significantly reduces incidents



### Q: Does Flexite help us meet legal reporting requirements for workplace incidents?  
**A:**  
- Yes, fully
- Meets government agency requirements for 24-hour reporting and documentation



### Q: Who benefits most from Flexite?  
**A:**  
- Ultimately benefits all employees through improved safety procedures



## 2. Technical & Functional Aspects

### Q: Does Flexite integrate with any other systems?  
**A:**  
- Only email notifications; no other system integrations

**Notes:**
- **JJA Observation:** Jan-Eric must manually log into e-tjänster (government agencies website) to enter incident report data
- No integration with:
  - Government reporting systems (e-tjänster)
  - Facilities system (Idus)
  - HR systems
  - Insurance systems for accident claims or salary reporting



### Q: Does Flexite send automatic notifications to responsible persons when assigned actions?  
**A:**  
- Yes, automatic notifications are sent



### Q: How well does the system track preventive actions versus just reactive responses?  
**A:**  
- Quite good for tracking preventive actions using system data
- Data enables proactive prevention rather than only reactive responses



### Q: Does Flexite maintain adequate audit trails for investigations?  
**A:**  
- Yes, adequate audit trails are maintained



### Q: Are you able to demonstrate compliance to auditors or inspectors using Flexite data?  
**A:**  
- Yes, easily
- Data is readily accessible for compliance demonstrations



## 3. User Experience & Workflows

### Q: How frequently do you use Flexite?  
**A:**  
- Daily



### Q: Who can report incidents in Flexite?  
**A:**  
- All employees have access to report incidents



### Q: Do people actually use Flexite to report incidents, or do they still call/email you?  
**A:**  
- Mostly use Flexite
- Even when employees call him, they are still required to report in Flexite



### Q: What percentage of incidents would you estimate are properly reported through the system?  
**A:**  
- Estimated reporting rate: 100%



### Q: Are there incidents that should be reported in Flexite but aren't?  
**A:**  
- Possibly, yes

**Notes:**
- Since joining Kubal in 2023, Jan-Eric suspects some employees avoid logging incidents in Flexite due to fear of hidden consequences (complaints or warnings)
- He and his team address this through:
  - Providing more information and education to employees
  - Changing company rules to make employees more comfortable reporting incidents



### Q: What do people like most about Flexite for incident reporting?  
**A:**  
- Maintains audit trails
- Easy to use and not overly complex



### Q: How easy is it for an employee to report an incident?  
**A:**  
- Ease rating: Easy
- Access methods: Mobile app and web form



### Q: Do responsible persons/teams respond promptly to incidents assigned to them?  
**A:**  
- Usually respond promptly
- Jan-Eric can view pending tasks and send reminders to managers about outstanding items



### Q: Can you easily track whether corrective actions have been completed?  
**A:**  
- Yes, easily tracked through the system



## 4. Pain Points & Challenges

### Q: What are the top 3 frustrations users have with Flexite?  
**A:**  
- No frustrations with the system itself
- Frustrations exist with the business process: incident analysis requires significant effort and involves multiple teams for preventive action planning

**Notes:**
- Frustration #1: High workload - extensive analysis required for each incident
- Frustration #2: Cross-team coordination - preventive action plans require involvement from multiple teams
- Frustration #3: [None identified with the system itself]



### Q: How often do you engage IT support for Flexite issues?  
**A:**  
- Never, unless system access issues occur (which is rare)
- Most common issues: System accessibility (rare occurrence)



### Q: Are there issues with mobile access for incident reporting?  
**A:**  
- No issues currently
- New mobile function request in progress based on user needs



### Q: Is the system performance acceptable? (Speed, responsiveness)  
**A:**  
- Excellent performance
- No speed or responsiveness concerns



**Key Pain Points Identified:**

1. **Incident Analysis Workload**
   - Severity: Medium
   - Frequency: Always (for every incident)
   - Impact: Time-consuming analysis process required for each incident
   - Current workaround: None - inherent to thorough safety management

2. **Multi-team Coordination Required**
   - Severity: Medium
   - Frequency: Often (depending on incident type)
   - Impact: Preventive action plans require coordination across multiple departments
   - Current workaround: None - necessary for comprehensive safety improvements

3. **[No System-Related Pain Points]**
   - Severity: N/A
   - Frequency: N/A
   - Impact: No technical frustrations identified with Flexite platform
   - Current workaround: N/A



## 5. Data Management & Reporting

### Q: Can you analyze incident trends and patterns effectively?  
**A:**  
- Yes, with effort
- Analysis requires manual data extraction and processing

**Notes:**
- Manual process: Exports reports from Flexite and pastes data into dashboard source file to create graphs and management dashboards
- Time required: Approximately 30-45 minutes per reporting cycle
- LTA (Lost Time Accident) reports created manually using Excel formulas with Flexite source data
- No automated dashboard or direct reporting functionality


  
## 6. Future State & Wishlist

### Q: Is Flexite meeting current health and safety reporting needs?  
**A:**  
- Yes, fully meeting current needs



### Q: What features are missing that would improve incident management?  
**A:**  
- Jan-Eric's opinion: No missing features identified

**Notes:**
- Top missing features:
  1. Automated analysis reports and dashboards
  2. Customizable management reports
  3. Direct export to government reporting formats

**JJA Observation:**
- Analysis reports may not fulfill Jan-Eric's requirements or may not exist in current system
- This gap necessitates manual data extraction and report creation

**Requested Features:**
- Automated analysis reports matching management requirements
- Integrated dashboard functionality to eliminate manual data processing
- Direct government reporting integration (e-tjänster)



### Q: Would you recommend: invest more, maintain current investment, or explore alternatives?  
**A:**  
- **Recommendation:** Invest more

**Reasoning:**
- Analysis reports matching management needs would add significant value
- Jan-Eric would welcome additional reporting features if they prove useful

**JJA Observation:**
- Management and government reports currently created manually (30-45 minutes per cycle)
- Investment in automated reporting would reduce administrative burden and improve data accuracy
- Potential ROI from eliminating repetitive manual data processing



### Q: Any other thoughts about Flexite you'd like to share?  
**A:**  
- System is easy to use
- Meets core incident management needs effectively
- User adoption is strong across the organization




## Key Insights

### ✅ What's Working Well

**Core System Performance & Reliability**
- Excellent system performance with no speed or responsiveness concerns
- Minimal IT support requirements (only rare system access issues)
- High system availability and reliability
- Easy to use interface for both administrators and end users

**User Adoption & Compliance**
- 100% incident reporting rate through the system
- Strong user adoption - employees primarily use Flexite rather than calling/emailing
- All employees have access to report incidents
- Daily usage by safety administrator demonstrates system value
- Mobile app and web form accessibility support field reporting

**Safety Management Effectiveness**
- Critical system rating: 9/10 for health and safety compliance
- Fully meets Swedish legal reporting requirements (Arbetsmiljöverket)
- Maintains adequate audit trails for investigations
- Easy demonstration of compliance to auditors and inspectors
- Effective tracking of preventive actions using system data
- Data enables creation of preventive procedures that reduce incidents
- Automated notifications to responsible persons work reliably
- Easy tracking of corrective action completion

**Reporting Volume & Management**
- Handles high volume effectively: 120-140 monthly reports (1,572 in 2025)
- Successfully manages approximately 12 government agency reports per month
- Responsible persons usually respond promptly to assigned incidents

---

### ❌ What Needs Improvement

**Critical Integration Gaps**
- **No government system integration**: Jan-Eric must manually log into e-tjänster website to enter incident data for government reporting
- **No facilities system integration**: No connection to Idus for maintenance-related incidents
- **No HR system integration**: Missing personnel data synchronization with Agda/Visma
- **No insurance system integration**: Manual processes for accident claims and salary reporting
- **Only email notifications**: No deeper system-to-system data exchange

**Manual Reporting & Data Processing**
- **Time-consuming dashboard creation**: 30-45 minutes required to manually export data from Flexite and paste into management dashboard source files
- **Manual LTA reporting**: Lost Time Accident reports created manually using Excel formulas with Flexite source data
- **No automated analysis reports**: Lack of built-in dashboards matching management requirements
- **No customizable management reports**: Forces manual data extraction and manipulation

**Business Process Challenges** *(Not system limitations)*
- **Multi-team coordination complexity**: Preventive action plans require involvement across multiple departments
- **High incident analysis workload**: Extensive analysis required for each incident
- **Reporting culture concerns**: Some employees may avoid reporting due to fear of consequences (complaints/warnings) - being addressed through education and policy changes

**Estimated Annual Waste from Manual Processes**
- Dashboard creation: ~30-45 minutes per cycle × frequency = [calculate based on reporting frequency]
- Government reporting manual entry: [time per report] × 12 monthly reports
- LTA report creation: [time per report] × frequency
- **Total estimated waste**: [To be calculated based on specific time investments and hourly rates]

---

### 🎯 Priority Improvement Areas

**High Priority:**
1. **Government system integration (e-tjänster)** - Eliminate manual double-entry for compliance reporting
2. **Automated dashboard and analysis reports** - Reduce 30-45 minute manual reporting cycles
3. **System integrations** - Connect to Idus, Agda/Visma, and insurance systems for seamless data flow

**Medium Priority:**  
4. **Enhanced reporting capabilities** - Built-in customizable reports matching management needs  
5. **Direct export functionality** - Streamline data extraction for external analysis  

**Cultural (Non-Technical):**  
6. **Continue reporting culture improvement** - Ongoing education to eliminate fear-based reporting barriers  


## Interviewer Observations
*Non-verbal cues, engagement level, tone, notable impressions*

**Engagement Level:** [High]  
**Overall Tone:** [Neutral]  


## Document Control
**Notes completed by:** JJA on 2026-01-08    
**Status:** [Draft ]

# Stakeholder Analysis - Idus

## Analysis Overview

**System:** Idus (Maintenance Management System)  
**Analysis Date:** 2024-12-12  
**Analyst:** JJA  
**Total Stakeholder Groups:** 6


## Stakeholder Groups

### Group 1: Super User / Functional Technician

**Number of Users:** 1-2 people  
**Usage Frequency:** Daily  
**System Dependency:** High  
**Influence Level:** High  
**Overall Sentiment:** Mixed (Positive about core features, frustrated with limitations)

#### Primary Use Cases
System administration, integration management, user support, maintenance reporting, and work order triage. Acts as gatekeeper between fault reports and work order creation.

**Key Tasks:**
1. Analyze fault reports (FA) and determine if they should become work orders (WO)
2. Generate maintenance reports for management and analysis (2+ days per report)
3. Maintain user accounts together with Elena
4. Manage system integrations and troubleshoot issues
5. Coordinate with shift leaders on work order decisions

**Time Spent in System:**
Multiple hours daily across all functions

#### Key Concerns & Pain Points
- **Broken SAP Integration:** Cannot trust inventory data for work planning; integration cannot be fixed without version upgrade
- **Manual Reporting Burden:** Spending 2+ business days creating reports manually in Excel
- **No Budget Tracking:** Cannot see if maintenance spending is within budget limits
- **Data Quality Issues:** Data not cleansed during Maximo migration; only "somewhat confident" in accuracy

#### What They Value
- Graphical interface for easy navigation
- Complete asset database with specifications, history, and documentation
- Internal upgrade capability (can manage upgrades without external dependency)
- BOM hierarchy connecting spare parts to assets

#### What They Need from Redesign
1. Version upgrade to restore SAP integration
2. Reporting/analytics module to eliminate manual Excel work
3. Data cleansing before upgrade
4. Budget tracking capability
5. Automated reporting capabilities

#### Influence on Project
High influence - serves as primary system expert, liaison to users, and recommends strategic direction. Explicitly recommends investing in existing system over replacement.

#### Engagement Strategy
Continue regular interviews; involve in data cleansing planning; engage in version upgrade decisions; validate proposed solutions

---

### Group 2: Maintenance Technicians

**Number of Users:** ~20 people (UH technicians)  
**Usage Frequency:** Daily  
**System Dependency:** High  
**Influence Level:** Medium  
**Overall Sentiment:** Positive about core features, frustrated with performance and integration issues

#### Primary Use Cases
Execute work orders, check spare parts availability, access equipment history and documentation, update work status, report completion.

**Key Tasks:**
1. Receive and execute assigned work orders
2. Check spare parts availability with warehouse
3. Access equipment history and failure records
4. Review equipment manuals and specifications
5. Update work order status and completion

**Time Spent in System:**
2-4 hours daily

#### Key Concerns & Pain Points
- **Unreliable Inventory Data:** Cannot trust spare parts availability; must manually verify with warehouse
- **No Mobile Access:** Cannot access information in field; must return to control room
- **Slow Performance:** System runs slowly affecting daily productivity
- **Complex SAP Interface:** Checking spare parts in SAP is complex

#### What They Value
- Graphical interface for locating equipment
- BOM hierarchy showing spare parts for each asset
- Access to equipment history and failure records
- Equipment manuals and specifications available in system

#### What They Need from Redesign
1. Reliable inventory integration for work planning
2. Mobile platform for field access
3. Improved system performance
4. Simplified spare parts checking process

#### Influence on Project
Medium influence - primary end users whose efficiency directly impacts maintenance effectiveness. User satisfaction critical for adoption.

#### Engagement Strategy
Conduct focused interviews; observe actual workflows; involve in usability testing; gather feedback on mobile platform requirements

---

### Group 3: Blue-Collar Workers / Operators

**Number of Users:** ~10 people  
**Usage Frequency:** Occasional (when issues arise)  
**System Dependency:** Low  
**Influence Level:** Low  
**Overall Sentiment:** Negative (Prefer alternative methods)

#### Primary Use Cases
Submit maintenance requests when equipment issues arise.

**Key Tasks:**
1. Submit fault reports for equipment issues
2. Report equipment malfunctions or abnormalities

**Time Spent in System:**
Minutes per week, when needed

#### Key Concerns & Pain Points
- **Cannot Find Assets:** Struggle to locate equipment in system; easier to call or email
- **System Not Intuitive:** Prefer phone/email over system navigation
- **Training Gaps:** May not be adequately trained on system usage

#### What They Value
- Simple, direct communication channels
- Quick resolution of issues
- Minimal system complexity

#### What They Need from Redesign
1. Simplified asset search and discovery
2. Easier interface for submitting requests
3. Targeted training for their role
4. Alternative to

 calling/emailing (QR codes, simple forms)

#### Influence on Project
Low influence but important for complete data capture and compliance. System bypass creates incomplete maintenance records.

#### Engagement Strategy
Conduct interviews to understand specific barriers; observe actual request submission behavior; involve in usability testing for simplified interfaces

---

### Group 4: Production Team

**Number of Users:** Unknown  
**Usage Frequency:** Occasional to Weekly  
**System Dependency:** Medium  
**Influence Level:** Medium  
**Overall Sentiment:** Neutral to Negative (Sometimes bypass system)

#### Primary Use Cases
Submit maintenance requests affecting production equipment; coordinate maintenance timing with production schedules.

**Key Tasks:**
1. Submit requests for production equipment issues
2. Coordinate PM scheduling with production plans
3. Provide input on maintenance timing and priorities

**Time Spent in System:**
Variable, depending on production issues

#### Key Concerns & Pain Points
- **Sometimes Bypass System:** Occasionally call or email instead of submitting tickets
- **PM Schedule Conflicts:** Some PMs skipped based on production priorities
- **System Not Always Convenient:** May not fit into fast-paced production environment

#### What They Value
- Quick response to production-critical issues
- Flexibility in PM scheduling
- Minimal disruption to production

#### What They Need from Redesign
1. Faster, easier request submission
2. Better visibility into maintenance schedules
3. Mobile or quick-access request methods
4. Production-aware scheduling features

#### Influence on Project
Medium influence - their cooperation critical for PM execution and production-maintenance coordination. Production priorities can override maintenance schedules.

#### Engagement Strategy
Interview production coordinators; understand production-maintenance workflow; address system bypass reasons; involve in PM scheduling improvements

---

### Group 5: Warehouse Staff

**Number of Users:** ~5 people  
**Usage Frequency:** Daily  
**System Dependency:** Medium  
**Influence Level:** Low  
**Overall Sentiment:** Neutral (Working with workarounds)

#### Primary Use Cases
Fulfill spare parts requests, manage inventory coordination with maintenance, process procurement orders.

**Key Tasks:**
1. Respond to spare parts requests from technicians
2. Verify parts availability in SAP
3. Place procurement orders for needed parts
4. Use barcode scanner system (IT custom integration with Idus data)

**Time Spent in System:**
1-2 hours daily (combined with SAP and custom tools)

#### Key Concerns & Pain Points
- **Manual Coordination:** Technicians must physically visit warehouse for parts
- **No Procurement Integration:** Must manually create procurement orders
- **Working Across Multiple Systems:** Idus, SAP, custom warehouse search program, barcode scanner

#### What They Value
- Barcode scanner system developed by IT
- Custom warehouse search program for SAP inventory
- Work order number-based part requests

#### What They Need from Redesign
1. Procurement module integration for automated ordering
2. Better integration between Idus and SAP
3. Consolidated system eliminating need for multiple tools
4. Ability to see maintenance priorities for parts allocation

#### Influence on Project
Low influence but critical operational role. Efficiency improvements would reduce coordination burden and speed maintenance execution.

#### Engagement Strategy
Interview about parts coordination workflow; understand custom tool usage; assess procurement integration opportunities

---

### Group 6: Management

**Number of Users:** 3-5 people  
**Usage Frequency:** Monthly (reviewing reports)  
**System Dependency:** Medium  
**Influence Level:** High  
**Overall Sentiment:** Neutral (Limited visibility)

#### Primary Use Cases
Review maintenance performance, analyze costs, make budget decisions, evaluate equipment performance and replacement needs.

**Key Tasks:**
1. Review monthly maintenance reports
2. Monitor maintenance spending vs budget
3. Evaluate equipment performance and lifecycle
4. Make capital planning decisions
5. Assess maintenance strategy effectiveness

**Time Spent in System:**
Minimal direct usage; rely on reports from Super User

#### Key Concerns & Pain Points
- **No Real-Time Visibility:** Must wait 2+ days for reports
- **No Budget Tracking:** Cannot see spending vs budget in real-time
- **Limited Analytics:** Cannot analyze equipment performance and cost trends
- **Manual Reporting Delays:** Slow access to decision-making information

#### What They Value
- Equipment reliability and uptime
- Cost control and budget adherence
- Data for capital planning decisions
- Maintenance strategy effectiveness

#### What They Need from Redesign
1. Real-time budget tracking and reporting
2. Equipment performance analytics and dashboards
3. Automated report generation
4. Cost analysis by asset, category, and time period
5. Predictive insights for capital planning

#### Influence on Project
High influence - budget approval authority and strategic decision-making power. ROI analysis critical for gaining support for module purchases and upgrades.

#### Engagement Strategy
Present business case with clear ROI; demonstrate how analytics would improve decision-making; show time savings from automated reporting; involve in requirements for management dashboards

---

## Stakeholder Mapping

### By Dependency on System

**High Dependency (Critical to their role):**
- Super User: System administration, reporting, and user support entirely dependent on Idus
- Maintenance Technicians: Daily work execution requires constant system access

**Medium Dependency (Important but not critical):**
- Warehouse Staff: Important for coordination but have alternative systems
- Production Team: Need it for requests but can work around
- Management: Need data but don't directly use system

**Low Dependency (Optional or occasional use):**
- Blue-Collar Workers: Can complete work through alternative channels (phone/email)

### By Influence on Project

**High Influence (Major decision makers):**
- Super User (Tom): System expert with strategic recommendation authority
- Management: Budget approval and strategic direction

**Medium Influence (Input valued):**
- Maintenance Technicians: Primary end users whose efficiency drives value
- Production Team: Production priorities can override maintenance schedules

**Low Influence (Minimal input):**
- Blue-Collar Workers: Limited voice but adoption important
- Warehouse Staff: Operational role without strategic input

### By Sentiment Toward System

**Positive Sentiment (Satisfied with core features):**
- Super User: Values graphical interface, asset database, BOM hierarchy
- Maintenance Technicians: Appreciate core asset management features

**Neutral Sentiment:**
- Management: Limited direct interaction; focused on results
- Warehouse Staff: Working with system through workarounds
- Production Team: System works but not always convenient

**Negative Sentiment (Frustrated users):**
- None explicitly negative toward system itself

**Mixed Sentiment (Positive about some aspects, frustrated with others):**
- Super User: Loves core features but frustrated with limitations
- Maintenance Technicians: Value asset management but frustrated with performance and integration issues
- Blue-Collar Workers: System not meeting their needs; prefer alternatives

---

## Stakeholder Matrix

### Prioritization Grid

**High Dependency + High Influence = TOP PRIORITY**
- Super User: Critical system knowledge, recommends strategic direction, daily heavy usage

**High Dependency + Medium Influence = CRITICAL USERS**
- Maintenance Technicians: Primary end users whose productivity drives system value

**Medium Dependency + High Influence = KEY INFLUENCERS**
- Management: Budget authority and strategic approval; need compelling ROI case

**Medium Dependency + Medium Influence = KEEP INFORMED**
- Production Team: Coordination important; production priorities matter
- Warehouse Staff: Operational efficiency impacts maintenance execution

**Low Dependency + Low Influence = MONITOR**
- Blue-Collar Workers: System bypass concerning but limited strategic impact

---

## Key Stakeholder Insights

### Common Needs Across Groups
1. **Better Integration and Data Reliability:** Shared by Super User, Technicians, Warehouse Staff
   - Impact if addressed: Eliminates manual verification; enables efficient work planning; restores trust in system

2. **Improved Performance:** Shared by Super User, Technicians
   - Impact if addressed: Improved productivity; better user experience; reduced frustration

3. **Simplified Access and Usage:** Shared by Blue-Collar Workers, Production Team, Technicians (for mobile)
   - Impact if addressed: Increased adoption; complete data capture; reduced system bypass

### Conflicting Needs Between Groups

**Production Team vs Maintenance Planning:**
- **Production wants:** Flexibility to skip or reschedule PMs based on production priorities
- **Maintenance wants:** Consistent PM execution according to schedule
- **Conflict:** Production priorities sometimes override preventive maintenance schedules
- **Resolution approach:** Develop production-aware scheduling with clear prioritization framework; visibility into deferred PM impacts

**Blue-Collar Workers vs System Complexity:**
- **Blue-Collar Workers want:** Simpler, faster methods (phone/email)
- **Organization wants:** Complete data capture in system
- **Conflict:** System complexity drives bypass behavior
- **Resolution approach:** Create simplified submission interface; QR codes for equipment; targeted training; accept multiple submission methods while capturing in system

### Power Dynamics
Management holds budget authority but relies on Super User's technical expertise and recommendation. Super User has significant influence due to system knowledge and strategic recommendation to invest vs replace. Technicians' adoption critical for operational success but limited decision-making power.

### Change Champions
- **Super User (Tom):** Already recommends investing in system; can champion upgrade and improvements; train other users
- **Experienced Technicians:** Those who value graphical interface and BOM hierarchy can advocate for system to peers
- **Shift Leaders:** Coordinate with Tom on work orders; can influence technician adoption and usage

### Resistance Risks
- **Blue-Collar Workers:** May resist increased system usage if usability not addressed; comfortable with phone/email
- **Production Team:** May resist stricter PM adherence if impacts production flexibility
- **Management:** May resist module purchase costs without clear ROI demonstration

---

## Engagement Requirements by Group

### Super User - High Priority
**Engagement Level Required:** High  
**Frequency:** Weekly check-ins during upgrade planning; bi-weekly during normal operations  
**Communication Channels:** Direct meetings, email, system demonstrations  
**Decision Rights:** Technical approach, data cleansing process, upgrade timing  
**Success Criteria:** Time savings from automated reporting; restored SAP integration; improved data quality

### Maintenance Technicians - Critical Users
**Engagement Level Required:** High  
**Frequency:** Monthly during planning; weekly during implementation  
**Communication Channels:** Group meetings, workflow observations, usability testing  
**Decision Rights:** Mobile platform requirements, workflow design input  
**Success Criteria:** Reduced time to access information; reliable inventory data; mobile field access

### Management - Key Influencers
**Engagement Level Required:** Medium  
**Frequency:** Monthly updates; milestone reviews  
**Communication Channels:** Executive presentations, ROI reports, dashboards  
**Decision Rights:** Budget approval, strategic direction, priority decisions  
**Success Criteria:** Real-time budget visibility; reduced reporting time; better decision support

### Production Team - Keep Informed
**Engagement Level Required:** Medium  
**Frequency:** Quarterly updates; as needed for PM coordination  
**Communication Channels:** Department meetings, coordination sessions  
**Decision Rights:** PM scheduling input, production priority escalation  
**Success Criteria:** Minimal production disruption; clear communication on maintenance plans

### Warehouse Staff - Keep Informed
**Engagement Level Required:** Low to Medium  
**Frequency:** Monthly updates  
**Communication Channels:** Department meetings, process training  
**Decision Rights:** Parts fulfillment process input  
**Success Criteria:** Reduced manual coordination; clearer parts priorities

### Blue-Collar Workers - Monitor
**Engagement Level Required:** Low  
**Frequency:** Training sessions as needed; quarterly check-ins  
**Communication Channels:** Training, simplified instructions, helpdesk  
**Decision Rights:** Feedback on submission interface  
**Success Criteria:** Increased system usage; reduced phone/email requests

---

## Influence Map

### Decision Makers
- **Management:** Final budget approval for module purchases and upgrades
- **Super User:** Technical approach, upgrade planning, data cleansing methodology
- **IT Leadership:** Infrastructure decisions (cloud migration), integration approaches

### Key Influencers
- **Super User (Tom):** Shapes technical requirements and strategic recommendation
- **Shift Leaders:** Influence work order priorities and technician workflows
- **Production Management:** Influences PM scheduling and maintenance priorities

### Subject Matter Experts
- **Super User (Tom):** Idus functionality, data structure, integration issues
- **Experienced Technicians:** Field workflows, asset information needs, mobile requirements
- **Warehouse Manager:** Parts coordination, inventory management, procurement needs

### End User Representatives
- **Lead Technician:** Represents technician workflows and needs
- **Super User:** Represents all user groups; interfaces with everyone

---

## Stakeholder Engagement Plan

### Phase 1: Discovery & Research (Current Phase)
**Who to involve:**
- Super User: Primary interviews; detailed system knowledge - Why: Strategic recommendation and technical insights
- Technicians: Workflow observations; pain point identification - Why: Primary end users
- Management: High-level requirements; ROI expectations - Why: Budget authority

### Phase 2: Analysis & Requirements
**Who to involve:**
- Super User: Data cleansing planning; upgrade requirements
- Technicians: Mobile platform requirements; workflow improvements
- Management: Budget tracking and reporting requirements
- Production Team: PM scheduling requirements

### Phase 3: Solution Planning
**Who to involve:**
- Super User: Module selection; upgrade approach
- IT: Cloud migration assessment; integration planning
- Management: ROI analysis review; budget approval
- Technicians: Mobile platform evaluation

### Phase 4: Implementation
**Who to involve:**
- Super User: Data cleansing execution; upgrade coordination
- IT: Technical implementation; cloud migration
- Technicians: UAT for mobile platform; workflow validation
- All Groups: Training and communication

### Phase 5: Post-Implementation
**Who to involve:**
- Super User: Monitor adoption; troubleshoot issues
- All Groups: Feedback collection; continuous improvement
- Management: ROI measurement; performance review

---

## Communication Strategy

### Key Messages by Stakeholder Group

**To Super User:**
- Your recommendation to invest is being followed
- Data cleansing will improve foundation before upgrade
- Reporting module will save you 2+ days per month
- Your expertise critical to success

**To Maintenance Technicians:**
- Mobile platform coming to improve field efficiency
- SAP integration will be restored for reliable parts data
- Performance improvements through cloud migration
- Your feedback shaping solution

**To Management:**
- Clear ROI: 2+ days/month time savings from reporting module
- Version upgrade enables SAP integration fix
- Mobile platform improves technician productivity
- Real-time budget tracking enables proactive cost management

**To Production Team:**
- Improvements will minimize disruption to production
- Better coordination tools for PM scheduling
- Your priorities will be considered in system design

**To Warehouse Staff:**
- Procurement integration will reduce manual coordination
- Improved inventory reliability benefits everyone
- Your workflow expertise valued in design

**To Blue-Collar Workers:**
- Simpler ways to submit requests coming
- Training and support available
- Your feedback matters for usability improvements

### Communication Frequency

**Weekly Updates:**
- Super User during active implementation phases
- Project core team

**Monthly Reviews:**
- Management (ROI progress, milestone updates)
- Technician representatives (progress, feedback)

**Quarterly Updates:**
- All stakeholder groups (overall progress, upcoming changes)
- Blue-collar workers and production team

**Milestone Communications:**
- All groups informed of major milestones (version upgrade, module launch, cloud migration)
- Success stories and benefits realization

---

## Risk Management

### High-Risk Stakeholders

**Super User (Tom):**
- **Risk:** Single point of failure; if unavailable during upgrade, project significantly impacted
- **Mitigation:** Document knowledge; establish backup super user; engage Elena as co-administrator
- **Contingency:** Delay upgrade if Tom unavailable; ensure vendor support available

**Management:**
- **Risk:** Budget approval denied if ROI not compelling
- **Mitigation:** Develop detailed ROI analysis; demonstrate time savings; benchmark against industry
- **Contingency:** Phased approach starting with highest ROI items (reporting module); defer lower priority modules

**Maintenance Technicians:**
- **Risk:** Poor adoption of mobile platform if doesn't meet field needs
- **Mitigation:** Involve in requirements and testing; pilot program before full rollout
- **Contingency:** Iterate based on feedback; provide adequate training and support

### Political Sensitivities
- Production vs Maintenance priorities: Balance production flexibility with PM adherence
- IT custom solutions: Acknowledge value of workarounds while proposing better long-term solutions
- Budget constraints: Recognize past budget limitations while making case for investment

---

## Summary Statistics

**Total Stakeholders Mapped:** 6 groups  
**Total User Count:** ~40 users  
**Daily Active Users:** ~25 users

**By Dependency:**
- High: 2 groups (~22 users)
- Medium: 3 groups (~15 users)
- Low: 1 group (~10 users)

**By Influence:**
- High: 2 groups
- Medium: 2 groups
- Low: 2 groups

**By Sentiment:**
- Positive: 0 groups (fully satisfied)
- Neutral: 3 groups (~20 users)
- Negative: 0 groups (entirely dissatisfied)
- Mixed: 3 groups (~22 users) - positive about core features, frustrated with limitations

---

## Action Items

### Immediate Actions
1. Schedule follow-up interviews with technicians to validate pain points and mobile requirements
2. Present ROI analysis to management for reporting module and version upgrade
3. Engage IT on cloud migration feasibility assessment
4. Schedule interviews with blue-collar workers and production team to understand system bypass reasons

### Ongoing Actions
1. Weekly check-ins with Super User during planning phases
2. Monthly stakeholder updates on progress
3. Gather ongoing feedback from technicians on proposed solutions

### Validation Needed
- Confirm management budget availability for module purchases
- Validate mobile platform requirements with field technicians
- Assess Production Team's PM scheduling flexibility needs
- Understand blue-collar worker training and support needs

---

**Document Status:** Draft  
**Last Updated:** 2024-12-12 by JJA  
**Next Review:** After additional stakeholder interviews completed

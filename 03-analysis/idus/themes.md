# Thematic Analysis - Idus

## Analysis Overview

**System:** Idus (Maintenance Management System)  
**Analysis Date:** 2024-12-12  
**Analyst:** JJA  
**Total Interviews Analyzed:** 1 (Tom - Super User)

---

## Identified Themes

### Theme 1: Critical Dependency on Inadequate System

**Frequency:** Mentioned by 1 of 1 interviewees (100%)  
**Severity:** High  
**Category:** Technical / Process

#### What This Theme Is About
Idus is essential to operations (9/10 criticality, ~1,800 tickets/month) but has major limitations: broken SAP integration, no reporting module, slow performance, and missing features. The organization heavily depends on a system that doesn't fully meet its needs.

#### Why This Matters
System unavailability would severely disrupt operations, creating high operational risk. Problems stem from delayed version upgrades and unpurchased modules, yet the system cannot be easily replaced due to operational dependency.

#### Evidence from Interviews

**Interview: Tom - Super User/Functional Technician:**
> "Rating is 9/10 as UH use it to control their work and planning."

**Interview: Tom - Super User/Functional Technician:**
> "It was with the inventory in SAP that can check and reliable the inventory from SAP. But since Kubal do not upgrade the version and some integrate code is broke -- no one from Idus can fix it until we upgrade the version. So now we can not truely trust the inventory in stock which lead to it's hard for the technician to plan their WO."

**Interview: Tom - Super User/Functional Technician:**
> "No, as Kubal do not purchase report or analytic module, so Tom has too export data and generate his own report in excel... To make a report it use around 2 business days and around 1 hour for the investigate report."

**Interview: Tom - Super User/Functional Technician:**
> "No." [When asked if Idus is meeting current maintenance management needs]

#### Related Observations
- SAP inventory integration broken due to version not upgraded - cannot be fixed until upgrade
- No procurement module integration - manual warehouse coordination required
- Reporting/analytics module not purchased - 2+ days manual Excel work per report
- Mobile platform not purchased - limits field technician access
- Summarized maintenance history module not purchased
- System performance slow due to local/on-premises infrastructure
- Data quality issues from incomplete Maximo migration cleansing
- User only "somewhat confident" in data accuracy

#### Connection to Other Themes
Directly connects to Theme 3 (Investment Strategy) - these deficiencies drive recommendation to invest. Contrasts with Theme 2 (Asset Management Strength) - despite strong core, peripheral capabilities are inadequate.

#### Implications & Recommendations
- **For Design:** Future systems must have comprehensive module coverage and robust integration reliability
- **For Requirements:** Real-time reporting, mobile access, and reliable integrations are non-negotiable requirements
- **For Priorities:** Version upgrade urgent to restore SAP integration; ROI analysis for purchasing missing modules; data cleansing prerequisite for upgrade

---

### Theme 2: Strong Asset Management Core with Adoption Barriers

**Frequency:** Mentioned by 1 of 1 interviewees (100%)  
**Severity:** Medium (barriers) / Positive (core strength)  
**Category:** UX / Technical / People/Training

#### What This Theme Is About
Idus has comprehensive asset management capabilities with valued features (graphical interface, BOM hierarchy, complete documentation), yet faces incomplete adoption as users bypass the system for phone/email, quick fixes go unlogged, and parallel systems exist for certain functions.

#### Why This Matters
Strong core capabilities justify investing in existing system, but adoption barriers create incomplete data capture and compliance risks. Paradox of powerful features with fragmented usage suggests training gaps and usability issues for certain user groups.

#### Evidence from Interviews

**Interview: Tom - Super User/Functional Technician:**
> "All value assets is in Idus with information of specification/location/maintenance history/spare part list/asset manual"

**Interview: Tom - Super User/Functional Technician:**
> "Graphic interface that make it easy to navigate the location of objects. Spare part list which connect to asset structure (BOM hierachy)"

**Interview: Tom - Super User/Functional Technician:**
> "It's mix, some they can use it but some of blue collar -- sometimes they could not find out the asset in Idus, so it's easy for them to call or email. Sometimes Production team not submit the ticket in Idus but call or email instead."

**Interview: Tom - Super User/Functional Technician:**
> "Not all maintenance work is logged in Idus, in case that job is just 5 minutes fix, they do not create any WO in system."

#### Related Observations
- All valuable assets comprehensively tracked with full documentation
- Graphical navigation highly appreciated by technicians
- Easy access to equipment history and specifications
- Blue-collar workers struggle to find assets - prefer phone/email
- Production team occasionally bypasses system
- Quick fixes (~5 minutes) handled informally
- Parallel "Stopptider" application for downtime tracking
- Custom IT solutions: warehouse search program, barcode scanner integration

#### Connection to Other Themes
Supports Theme 3 (Investment Strategy) - strong core features justify evolution over replacement. Related to Theme 1 (System Inadequacy) - adoption barriers stem partly from performance and usability issues.

#### Implications & Recommendations
- **For Design:** Preserve graphical interface and BOM hierarchy; improve asset search for all skill levels; mobile-first design for field workers
- **For Requirements:** Quick-logging mechanism for minor repairs; intuitive asset discovery; consolidated functionality to eliminate parallel systems
- **For Priorities:** Targeted training for blue-collar workers and production teams; evaluate integrating "Stopptider" functionality; usability testing with representative users

---

### Theme 3: Strategic Investment Path Over Replacement

**Frequency:** Mentioned by 1 of 1 interviewees (100%)  
**Severity:** N/A (Strategic Theme)  
**Category:** Process / Technical

#### What This Theme Is About
Despite significant limitations, super user explicitly recommends investing in and upgrading existing Idus rather than exploring alternatives, based on ease of internal upgrade management, user familiarity, strong core features, and minimal training requirements. Clear prerequisites identified: data cleansing, process reorganization, and HQ coordination.

#### Why This Matters
Strategic direction has major budget and project planning implications. Recommendation reflects practical considerations of change management costs, operational risk, and satisfaction with core capabilities. Phased approach needed to address technical debt before maximizing system value.

#### Evidence from Interviews

**Interview: Tom - Super User/Functional Technician:**
> "To invest more could be easy for Kubal to manage it. The upgrade can do it by our self. The problem is about data cleasning and some reorganize or reprocess which could be done before upgrade it. Also need to sit with HQ to recheck the organization structure for the maintenance asset. Another points is Idus has feature for the graphic layout which is easy to use and also take not much time to do another extra training."

#### Related Observations
- Upgrades can be performed internally by Kubal
- Prerequisites: data cleansing, process reorganization, HQ coordination on org structure
- Graphical layout feature highly valued
- Minimal additional training time required
- User familiarity reduces change management effort
- Investment would include purchasing missing modules

#### Connection to Other Themes
Informed by Theme 2 (Asset Management Strength) - core capabilities worth preserving. Addresses Theme 1 (System Inadequacy) - investment path to resolve deficiencies through upgrade and module purchases.

#### Implications & Recommendations
- **For Design:** Focus on enhancement and evolution rather than replacement; maintain valued features during upgrade
- **For Requirements:** Phased roadmap: (1) Data cleansing, (2) Process reorganization, (3) Version upgrade, (4) Module purchases (reporting, mobile, analytics)
- **For Priorities:** ROI analysis comparing upgrade vs replacement; coordinate with HQ on organizational structure; establish data governance framework; evaluate cloud migration for performance

---

## Theme Overview Summary

### By Severity (Impact Level)

**High Severity:**
- Theme 1: Critical Dependency on Inadequate System - Operational risk; broken integrations; significant manual overhead

**Medium Severity:**
- Theme 2: Strong Asset Management Core with Adoption Barriers - Incomplete data capture; compliance risks; training gaps

**Strategic:**
- Theme 3: Strategic Investment Path Over Replacement - Clear direction with phased implementation requirements

### By Category

**Technical Themes:**
- Theme 1: Critical Dependency on Inadequate System
- Theme 2: Strong Asset Management Core with Adoption Barriers
- Theme 3: Strategic Investment Path Over Replacement

**User Experience Themes:**
- Theme 2: Strong Asset Management Core with Adoption Barriers

**Process Themes:**
- Theme 1: Critical Dependency on Inadequate System
- Theme 3: Strategic Investment Path Over Replacement

**People/Training Themes:**
- Theme 2: Strong Asset Management Core with Adoption Barriers

**Data/Reporting Themes:**
- Theme 1: Critical Dependency on Inadequate System

---

## Theme Relationships

### Primary Theme Cluster: System Evolution Strategy

**Connection:** All three themes work together to paint complete picture - Theme 1 identifies what's broken, Theme 2 identifies what's working, Theme 3 synthesizes into strategic direction.

**Combined Impact:** Organization should pursue targeted investment in existing system rather than replacement, addressing specific deficiencies (integrations, modules, performance) while preserving valued core capabilities (asset management, graphical interface). Prerequisites must be completed first (data cleansing, process reorganization, version upgrade) before maximizing value through module purchases.

---

## Key Insights

### Strongest Patterns
1. **Module Underinvestment:** Multiple pain points stem from modules not purchased (reporting, mobile, analytics, history reports) - suggests budget-constrained implementation
2. **Technical Debt Cascade:** Delayed version upgrade created cascading problems (broken integrations, unsupported features) - demonstrates compounding cost of deferred maintenance
3. **Strong Core with Weak Periphery:** Asset management foundation solid and valued, but surrounding functionality inadequate - targeted investment strategy indicated

### Unexpected Findings
- Super user recommends investing in existing system despite significant limitations
- Data quality issues traced to historical migration rather than current operations
- IT team developed multiple custom solutions showing both capability and system gaps
- Unclear if "Stopptider" parallel system exists due to missing Idus features or user preference

### User Sentiment

**Overall Sentiment:** Mixed - Positive about core features, frustrated with limitations

**By User Group:**
- **Super User (Tom):** Pragmatic - recognizes problems but values strengths; recommends investment over replacement
- **Technicians:** Positive about graphical interface and BOM; frustrated with SAP integration and performance
- **Blue-Collar Workers/Production:** Lower adoption; prefer phone/email (usability or training gaps)

### Critical Themes Requiring Immediate Attention
1. **Broken SAP Integration:** Cannot be fixed without version upgrade - triggers urgent upgrade decision
2. **Manual Reporting Overhead:** 2+ business days per report - ROI analysis for analytics module warranted
3. **Operational Risk:** High dependency on inadequate system requires mitigation strategy during improvements

---

## Recommendations Based on Themes

### Technical Recommendations
1. **URGENT:** Execute version upgrade to restore SAP inventory integration
2. Conduct data cleansing project before upgrade
3. Evaluate cloud migration for performance improvement
4. Coordinate with HQ on organizational structure review

### Investment Recommendations
1. **High Priority:** Purchase reporting/analytics module (ROI: 2+ days/month savings)
2. **High Priority:** Purchase mobile platform module
3. **Medium Priority:** Purchase summarized maintenance history module
4. **Evaluate:** Procurement module integration, budget tracking feature

### Process Recommendations
1. Phased roadmap: Data cleansing → Process reorganization → Version upgrade → Module purchases
2. Establish data governance framework
3. Create formal process for logging all maintenance work
4. Implement change management program for upgrade

### Training/Support Recommendations
1. Develop targeted training for blue-collar workers and production teams
2. Create user guides focused on asset search and navigation
3. Establish super user network beyond Tom

---

## 🔴 Themes to Validate

**Theme 2 (Adoption Barriers):** Validate with blue-collar workers and production team - How: Conduct interviews with non-technical users; observe actual usage patterns

**Performance Issues:** Determine if purely infrastructure-related or includes database optimization - How: Technical performance assessment; cloud deployment benchmarks

**"Stopptider" System:** Unclear if due to missing Idus functionality or legacy preference - How: Interview users; feature comparison; assess integration feasibility

**Module Purchasing Rationale:** Why critical modules not purchased initially - How: Review implementation decisions with IT leadership and procurement

---

**Document Status:** Draft  
**Last Updated:** 2024-12-12 by Jitaree  
**Next Review Date:** [After additional interviews]  
**Notes:** Based on single super user interview. Additional interviews with technicians, blue-collar workers, and production team recommended to validate themes.

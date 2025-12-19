# Thematic Analysis - Idus

## Analysis Overview

**System:** Idus (Maintenance Management System)  
**Analysis Date:** 2025-12-12  
**Analyst:** JJA  
**Total Interviews Analyzed:** 1 (Tom - Super User)

---

## Identified Themes

### Theme 1: Critical Dependency on Inadequate System

**Frequency:** 1 of 1 interviewees (100%)  
**Severity:** High  
**Category:** Technical / Process

#### Description
Idus is essential to operations (9/10 criticality, ~1,800 tickets/month) but has major limitations: broken SAP integration, no reporting module, slow performance, and missing features. System unavailability would severely disrupt operations. Problems stem from delayed upgrades and unpurchased modules, creating high operational risk.

#### Key Evidence
- "Rating is 9/10 as UH use it to control their work and planning"
- SAP integration broken since version not upgraded - inventory data unreliable, making work planning difficult
- No reporting module - Tom spends 2+ business days creating manual Excel reports
- System not meeting current maintenance management needs

#### Key Issues
- SAP inventory integration broken (cannot be fixed without version upgrade)
- No procurement module (requires manual warehouse coordination)
- No reporting/analytics module (2+ days manual work per report)
- No mobile platform (limits field technician access)
- Slow performance (local/on-premises infrastructure)
- Data quality issues from incomplete Maximo migration

#### Recommendations
- **URGENT:** Execute version upgrade to restore SAP integration
- Conduct data cleansing before upgrade
- Purchase reporting/analytics module (ROI: 2+ days/month savings)
- Purchase mobile platform module
- Evaluate cloud migration for performance

---

### Theme 2: Strong Asset Management Core with Adoption Barriers

**Frequency:** 1 of 1 interviewees (100%)  
**Severity:** Medium  
**Category:** UX / Technical / People/Training

#### Description
Idus has strong asset management capabilities (graphical interface, BOM hierarchy, complete documentation) that technicians value, but faces incomplete adoption. Users bypass the system for phone/email, quick fixes go unlogged, and parallel systems exist. This creates incomplete data capture and compliance risks.

#### Key Evidence
- "All value assets is in Idus with information of specification/location/maintenance history/spare part list/asset manual"
- "Graphic interface that make it easy to navigate the location of objects"
- Blue-collar workers struggle to find assets in Idus - prefer phone/email
- Production team sometimes bypasses system
- Quick fixes (~5 minutes) not logged in system

#### Key Issues
- Blue-collar workers and production team have low adoption
- Not all maintenance work logged (informal quick fixes)
- Parallel "Stopptider" application for downtime tracking
- Custom IT workarounds (warehouse search program, barcode scanner)

#### Recommendations
- Preserve graphical interface and BOM hierarchy during upgrades
- Improve asset search for all skill levels
- Develop targeted training for blue-collar workers and production teams
- Create quick-logging mechanism for minor repairs
- Evaluate integrating "Stopptider" functionality into Idus

---

### Theme 3: Strategic Investment Path Over Replacement

**Frequency:** 1 of 1 interviewees (100%)  
**Severity:** N/A (Strategic)  
**Category:** Process / Technical

#### Description
Despite limitations, super user recommends investing in existing Idus rather than replacing it. Rationale: upgrades manageable internally, user familiarity, strong core features, minimal training needed. Prerequisites required: data cleansing, process reorganization, HQ coordination.

#### Key Evidence
- "To invest more could be easy for Kubal to manage it. The upgrade can do it by our self"
- Need data cleansing and process reorganization before upgrade
- Need to coordinate with HQ on maintenance asset organizational structure
- "Idus has feature for the graphic layout which is easy to use and also take not much time to do another extra training"

#### Strategic Approach
**Phased roadmap:**
1. Data cleansing
2. Process reorganization
3. Version upgrade
4. Module purchases (reporting, mobile, analytics)

#### Recommendations
- Focus on enhancement rather than replacement
- Conduct ROI analysis comparing upgrade vs replacement
- Coordinate with HQ on organizational structure
- Establish data governance framework
- Maintain valued features during upgrade

---

## Summary

### Key Patterns
1. **Module Underinvestment** - Pain points stem from unpurchased modules (reporting, mobile, analytics)
2. **Technical Debt** - Delayed version upgrade created cascading problems (broken integrations)
3. **Strong Core, Weak Periphery** - Solid asset management but inadequate surrounding functionality

### User Sentiment
- **Super User:** Pragmatic - recognizes problems but recommends investment over replacement
- **Technicians:** Positive about interface/BOM; frustrated with SAP integration and performance
- **Blue-Collar/Production:** Low adoption; prefer phone/email

### Critical Actions Required
1. **URGENT:** Version upgrade to restore SAP integration
2. **High Priority:** Purchase reporting/analytics module (2+ days/month time savings)
3. **High Priority:** Purchase mobile platform module
4. Data cleansing and process reorganization before upgrade

---

## Themes to Validate (Additional Interviews Needed)

- **Adoption Barriers:** Interview blue-collar workers and production team about specific usage challenges
- **Performance Issues:** Technical assessment to determine if infrastructure or database-related
- **"Stopptider" System:** Understand if due to missing Idus features or user preference
- **Module Purchasing:** Why critical modules not purchased initially

---

**Document Status:** Draft  
**Last Updated:** 2025-12-12 by JJA  
**Next Review:** After additional interviews  
**Note:** Based on single super user interview. Additional interviews needed to validate themes across user groups.

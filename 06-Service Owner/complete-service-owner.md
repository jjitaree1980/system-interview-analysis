# Complete IT Service Owner Burden Analysis
## Core Tasks + Hidden Burdens + Technical Onboarding

---

## Executive Summary - Total IT Burden

### Visual Comparison: What You See vs What You Get

```
WHAT IT LOOKS LIKE (Original Estimate):
Current IT  │ + Service Owner Core Tasks  │ = New Total
5.32 hrs    │ +10.2 hrs                   │ 15.52 hrs/month (10.1% FTE)
████        │ ████████████████            │

WHAT IT ACTUALLY IS - YEAR 1 (Complete Picture with Setup):
Current IT  │ + Core │ + Training │ + Docs │ + Setup │ + Hidden Burdens      │ = REAL Total
5.32 hrs    │ +10.2  │ +13.0      │ +1.1   │ +8.3    │ +32.8                 │ 70.7 hrs/month (46.1% FTE)
████        │ ██████ │ ████████   │ ██     │ ████████│ ██████████████████████│

WHAT IT ACTUALLY IS - YEAR 2+ (Steady State):
Current IT  │ + Core │ + Training │ + Docs │ + Hidden Burdens          │ = REAL Total
5.32 hrs    │ +10.2  │ +13.0      │ +0.3   │ +32.8                     │ 61.6 hrs/month (40.2% FTE)
████        │ ██████ │ ████████   │ ▓      │ ██████████████████████████│

Setup work: 100 hours one-time (process dev, ticketing, metrics, knowledge transfer) 
            = 8.3 hrs/month average in Year 1 only
The hidden burdens are 3.2X larger than the visible core tasks!
```

### Complete IT Burden Breakdown

| Component | Year 1 (hrs/month) | Year 2+ (hrs/month) | Hours/Year (Y1) | Hours/Year (Y2+) | FTE % (Y1) | FTE % (Y2+) | % of Total (Y2+) |
|-----------|-------------------|---------------------|-----------------|------------------|------------|-------------|------------------|
| **Core Service Owner tasks** | 10.2 hrs | 10.2 hrs | 122 hrs | 122 hrs | 6.6% | 6.6% | 17% |
| **Technical onboarding training** | 13.0 hrs | 13.0 hrs | 156 hrs | 156 hrs | 8.5% | 8.5% | 21% |
| **Documentation** | **1.1 hrs** | **0.3 hrs** | **13 hrs** | **4 hrs** | **0.7%** | **0.2%** | **<1%** |
| **Hidden operational burdens** | 32.8 hrs | 32.8 hrs | 394 hrs | 394 hrs | 21.4% | 21.4% | 53% |
| **Setup work (one-time)** | **8.3 hrs*** | **0 hrs** | **100 hrs** | **0 hrs** | **5.4%** | **0%** | **-** |
| | | | | | | | |
| **TOTAL YEAR 1** | **65.4 hrs/month** | - | **785 hrs/year** | - | **42.7% FTE** | - | - |
| **TOTAL YEAR 2+** | - | **56.3 hrs/month** | - | **676 hrs/year** | - | **36.7% FTE** | 100% |

## Key Differences Between Year 1 and Year 2+

| Metric | Year 1 | Year 2+ | Difference |
|--------|--------|---------|------------|
| **Documentation** | 13 hrs/year (0.7% FTE) | 4 hrs/year (0.2% FTE) | -9 hrs (-0.5% FTE) |
| **Setup work** | 100 hrs/year (5.4% FTE) | 0 hrs/year (0% FTE) | -100 hrs (-5.4% FTE) |
| **Total burden** | 785 hrs/year (42.7% FTE) | 676 hrs/year (36.7% FTE) | -109 hrs (-6.0% FTE) |

***Setup work breakdown (Year 1 only):**
- Process development: 32 hours
- Ticketing system configuration: 20 hours  
- Metrics & reporting setup: 18 hours
- Knowledge transfer: 30 hours
- **Total: 100 hours ÷ 12 months = 8.3 hrs/month average**

**For IT:**
- **Year 1:** 65.4 hrs/month = **16.4 hrs/week = 196 minutes/day**
- **Year 2+:** 56.3 hrs/month = **14.0 hrs/week = 168 minutes/day**
- **Peak months (Mar-May) :** 91 hrs/month = **22.8 hrs/week = 274 minutes/day**

**FTE calculation basis:** 1 FTE = 40 hrs/week × 46 working weeks = 1,840 hours/year

---

## CRITICAL FINDING

**The Service Owner role is NOT 10.2 hrs/month (6.6% FTE)**

**The Service Owner role is:**
- **Year 1: 65.4 hrs/month (42.7% FTE)** - includes setup work
- **Year 2+: 56.3 hrs/month (36.7% FTE)** - steady state

**Hidden burdens + setup are 4.0X larger than the visible core tasks in Year 1!**
**Hidden burdens are 3.2X larger than the visible core tasks in Year 2+!**

---

## Part 1: Core Service Owner Tasks (From GitHub Summary)

### 1A. Current State vs Service Owner State - COMPLETE PICTURE

```
IT CAPACITY REQUIREMENTS - YEAR 1 (WITH DOCUMENTATION CREATION)

Component                Current IT │ Service Owner Core │ + Training │ + Docs  │ + Hidden │ TOTAL YEAR 1
──────────────────────────────────────────────────────────────────────────────────────────────────────────
System-Specific Work:
  Ascendo                ▓           │ ████████           │            │         │          │ 3.0 hrs
                         0.16 hrs    │ +2.8 hrs           │            │         │          │
  
  Flexite                ████        │ ████████           │            │         │          │ 4.9 hrs
                         2.5 hrs     │ +2.4 hrs           │            │         │          │
  
  Idus                   ████        │ ████████████       │            │         │          │ 5.5 hrs
                         2.5 hrs     │ +3.0 hrs           │            │         │          │
  
  Agda/Visma             ▓           │ ████████           │            │         │          │ 2.16 hrs
                         0.16 hrs    │ +2.0 hrs           │            │         │          │
                         ────────────────────────────────────────────────────────────────────────────────
  Subtotal Systems       5.32 hrs    │ +10.2 hrs          │            │         │          │ 15.52 hrs

Cross-System Work:
  Technical Onboarding   -           │ -                  │ ██████████████████████ │         │ 13.0 hrs
  (110 new employees/yr) -           │ -                  │ +13.0 hrs              │         │
  
  Documentation          -           │ -                  │            │ ██      │          │ 1.1 hrs
  (creation - Year 1)    -           │ -                  │            │ +1.1 hrs│          │
  
  Hidden Burdens         -           │ -                  │            │         │ ████████████████████████████████████████ │ 32.8 hrs
  (see breakdown below)  -           │ -                  │            │         │ +32.8 hrs                                │
  
  Setup Work             -           │ -                  │            │         │ ████████████                             │ 8.3 hrs*
  (process, ticketing)   -           │ -                  │            │         │ +8.3 hrs*                                │
──────────────────────────────────────────────────────────────────────────────────────────────────────────
TOTAL YEAR 1             5.32 hrs    │ +10.2 hrs          │ +13.0 hrs  │ +1.1 hrs│ +41.1 hrs│ 70.7 hrs/month
                         (64 hrs/yr) │ (+122 hrs/yr)      │ (+156 hrs) │ (+13 hrs)│ (+494 hrs)│ (849 hrs/yr)

*Setup work: 100 hours one-time spread over 12 months = 8.3 hrs/month average


IT CAPACITY REQUIREMENTS - YEAR 2+ (STEADY STATE)

Component                Current IT │ Service Owner Core │ + Training │ + Docs  │ + Hidden │ TOTAL YEAR 2+
──────────────────────────────────────────────────────────────────────────────────────────────────────────
System-Specific Work:
  Ascendo                ▓           │ ████████           │            │         │          │ 3.0 hrs
                         0.16 hrs    │ +2.8 hrs           │            │         │          │
  
  Flexite                ████        │ ████████           │            │         │          │ 4.9 hrs
                         2.5 hrs     │ +2.4 hrs           │            │         │          │
  
  Idus                   ████        │ ████████████       │            │         │          │ 5.5 hrs
                         2.5 hrs     │ +3.0 hrs           │            │         │          │
  
  Agda/Visma             ▓           │ ████████           │            │         │          │ 2.16 hrs
                         0.16 hrs    │ +2.0 hrs           │            │         │          │
                         ────────────────────────────────────────────────────────────────────────────────
  Subtotal Systems       5.32 hrs    │ +10.2 hrs          │            │         │          │ 15.52 hrs

Cross-System Work:
  Technical Onboarding   -           │ -                  │ ██████████████████████ │         │ 13.0 hrs
  (110 new employees/yr) -           │ -                  │ +13.0 hrs              │         │
  
  Documentation          -           │ -                  │            │ ▓       │          │ 0.3 hrs
  (maintenance)          -           │ -                  │            │ +0.3 hrs│          │
  
  Hidden Burdens         -           │ -                  │            │         │ ████████████████████████████████████████ │ 32.8 hrs
  (see breakdown below)  -           │ -                  │            │         │ +32.8 hrs                                │
──────────────────────────────────────────────────────────────────────────────────────────────────────────
TOTAL YEAR 2+            5.32 hrs    │ +10.2 hrs          │ +13.0 hrs  │ +0.3 hrs│ +32.8 hrs│ 61.6 hrs/month
                         (64 hrs/yr) │ (+122 hrs/yr)      │ (+156 hrs) │ (+4 hrs)│ (+394 hrs)│ (740 hrs/yr)


FTE Breakdown:
  Current IT:            3.5% FTE    │                    │            │         │          │
  + Core Service Owner:              │ +6.6% FTE          │            │         │          │
  + Training:                        │                    │ +8.5% FTE  │         │          │
  + Documentation:                   │                    │            │ +0.7%** │          │
  + Hidden Burdens:                  │                    │            │         │ +21.4%   │
  + Setup (Y1 only):                 │                    │            │         │ +5.4%*** │
                         ──────────────────────────────────────────────────────────────────────────────
  YEAR 1 TOTAL:          3.5% FTE →  10.1% FTE      →     18.6% FTE → 19.3% FTE → 46.1% FTE
  YEAR 2+ TOTAL:         3.5% FTE →  10.1% FTE      →     18.6% FTE → 18.8% FTE → 40.2% FTE

**Year 1: 0.7% FTE for documentation creation (13 hrs)
***Year 1 only: 5.4% FTE for setup work (100 hrs one-time)
```

**CRITICAL INSIGHT: The visible 10.2 hrs/month is only 14% of total Year 1 work, 17% of Year 2+ work!**

---

### Hidden Burdens Breakdown (32.8 hrs/month):

```
Hidden Operational Work               Hours/Month │ Visual Scale
──────────────────────────────────────────────────────────────────
Business Coordination                  6.0 hrs     │ ████████████████████
Escalation Handling                    5.3 hrs     │ █████████████████
Security & Compliance                  5.0 hrs     │ ████████████████
Request Management Overhead            3.7 hrs     │ ████████████
Metrics & Reporting                    2.7 hrs     │ ████████
Ticketing System Management            2.5 hrs     │ ███████
Service Owner Governance               2.2 hrs     │ ███████
System Upgrades & Changes              2.0 hrs     │ ██████
Process Development & Refinement       1.7 hrs     │ █████
Continuous Improvement                 1.7 hrs     │ █████
──────────────────────────────────────────────────────────────────
TOTAL HIDDEN BURDENS                   32.8 hrs    │ (58% of total work!)
```

**Key Insights:**
- **Top 3 hidden burdens** = 16.3 hrs/month (26% of total Service Owner work)
- **Communication work** (Coordination + Request Mgmt + Governance) = 11.9 hrs/month (19%)
- **Compliance work** (Security + Reporting + Governance) = 9.9 hrs/month (16%)

---

## EXPANDED CHART - Year 2+ with All Hidden Burdens Detailed

```
IT CAPACITY - YEAR 2+ STEADY STATE (EVERY HIDDEN BURDEN SHOWN)

Component                     Current IT │ + Core │ + Train │ + Docs │ Hours/Month │ TOTAL
────────────────────────────────────────────────────────────────────────────────────────────
SYSTEM-SPECIFIC WORK:
  Ascendo                     ▓          │ ██████ │         │        │ 3.0 hrs     │
                              0.16       │ +2.8   │         │        │             │
  Flexite                     ████       │ ██████ │         │        │ 4.9 hrs     │
                              2.5        │ +2.4   │         │        │             │
  Idus                        ████       │ ██████████      │        │ 5.5 hrs     │
                              2.5        │ +3.0   │         │        │             │
  Agda/Visma                  ▓          │ ██████ │         │        │ 2.16 hrs    │
                              0.16       │ +2.0   │         │        │             │
                              ─────────────────────────────────────────────────────────────
  Subtotal                    5.32       │ +10.2  │         │        │ 15.52 hrs   │

CROSS-SYSTEM WORK:
  Technical Onboarding        -          │        │ ██████████████████ │ 13.0 hrs    │
  (30-45 min × 250 users/yr)  -          │        │ +13.0  │        │             │
  
  Documentation Maintenance   -          │        │        │ ▓      │ 0.3 hrs     │
                              -          │        │        │ +0.3   │             │

HIDDEN BURDENS (DETAILED):
  1. Business Coordination    -          │        │        │ ████████████ │ 6.0 hrs     │
     (Meetings with Rhodora,  -          │        │        │ +6.0   │             │
      Sofia, Tom, Helena)

  2. Escalation Handling      -          │        │        │ ██████████   │ 5.3 hrs     │
     (Complex issues, RCA)    -          │        │        │ +5.3   │             │

  3. Security & Compliance    -          │        │        │ ██████████   │ 5.0 hrs     │
     (Quarterly reviews,GDPR) -          │        │        │ +5.0   │             │

  4. Request Management       -          │        │        │ ███████      │ 3.7 hrs     │
     (Email, tickets, comm.)  -          │        │        │ +3.7   │             │

  5. Metrics & Reporting      -          │        │        │ █████        │ 2.7 hrs     │
     (SLA tracking, reports)  -          │        │        │ +2.7   │             │

  6. Ticketing System Mgmt    -          │        │        │ █████        │ 2.5 hrs     │
     (Queue mgmt, routing)    -          │        │        │ +2.5   │             │

  7. Service Owner Governance -          │        │        │ ████         │ 2.2 hrs     │
     (Formal meetings, exec)  -          │        │        │ +2.2   │             │

  8. System Upgrades          -          │        │        │ ████         │ 2.0 hrs     │
     (User communication)     -          │        │        │ +2.0   │             │

  9. Process Refinement       -          │        │        │ ███          │ 1.7 hrs     │
     (Ongoing improvement)    -          │        │        │ +1.7   │             │

 10. Continuous Improvement   -          │        │        │ ███          │ 1.7 hrs     │
     (Automation projects)    -          │        │        │ +1.7   │             │
                              ─────────────────────────────────────────────────────────────
  Subtotal Hidden             -          │        │        │ +32.8  │ 32.8 hrs    │
────────────────────────────────────────────────────────────────────────────────────────────
GRAND TOTAL YEAR 2+           5.32       │ +10.2  │ +13.0  │ +33.1  │ 61.6 hrs/month
                              (64/yr)    │(122/yr)│(156/yr)│(397/yr)│ (740 hrs/year)
                              3.5% FTE   │ +6.6%  │ +8.5%  │ +21.6% │ 40.2% FTE
```

**BREAKDOWN BY CATEGORY:**

| Category | Hours/Month | % of Total | What's Included |
|----------|-------------|------------|-----------------|
| **System-specific core tasks** | 10.2 hrs | 17% | User accounts, passwords, technical support, vendor |
| **Technical onboarding** | 13.0 hrs | 21% | Training 110 new employees/year (30-45 min each) |
| **Documentation** | 0.3 hrs | <1% | Annual maintenance of technical guides |
| **Communication overhead** | 11.9 hrs | 19% | Coordination (6.0) + Requests (3.7) + Governance (2.2) |
| **Compliance & reporting** | 9.9 hrs | 16% | Security (5.0) + Reporting (2.7) + Governance (2.2) |
| **Complex problem solving** | 5.3 hrs | 9% | Escalations, root cause analysis |
| **System management** | 4.5 hrs | 7% | Ticketing (2.5) + Upgrades (2.0) |
| **Process improvement** | 3.4 hrs | 6% | Refinement (1.7) + Automation (1.7) |
| **Infrastructure (existing)** | 2.7 hrs | 4% | Idus/Flexite current work (part of 5.32 base) |
| **TOTAL** | **61.6 hrs** | **100%** | |

---

---

### 1B. Core Tasks Breakdown by System

#### ASCENDO: 2.8 hrs/month

| Task | Hours/Month | Rationale |
|------|-------------|-----------|
| User account management | 1.2 hrs | Create/remove accounts, permission changes |
| Technical support | 0.8 hrs | Login issues, error messages |
| Technical troubleshooting | 0.4 hrs | System errors, technical diagnosis |
| Technical vendor coordination | 0.4 hrs | IT handles rare technical incidents |
| **TOTAL** | **2.8 hrs** | Pure technical tasks |

---

#### FLEXITE: 2.4 hrs/month

| Task | Hours/Month | Rationale |
|------|-------------|-----------|
| User account creation/removal | 1.2 hrs | System execution |
| Password resets | 0.6 hrs | Authentication management |
| Permission changes | 0.2 hrs | Technical execution (business approves) |
| Technical change requests | 0.4 hrs | Technical knowledge, vendor coordination |
| **TOTAL** | **2.4 hrs** | Pure technical tasks |

---

#### IDUS: 3.0 hrs/month

| Task | Hours/Month | Rationale |
|------|-------------|-----------|
| User account creation/removal | 2.0 hrs | System execution |
| Technical support | 1.0 hrs | Login issues, error messages, system errors |
| Password management | 0 hrs* | **CRITICAL: Must implement individual passwords!** |
| **TOTAL** | **3.0 hrs** | Pure technical tasks |

*Currently all 30 users share one password - major security violation requiring immediate fix

---

#### AGDA/VISMA: 2.0 hrs/month

| Task | Hours/Month | Rationale |
|------|-------------|-----------|
| User account creation/removal | 1.2 hrs | System execution |
| Password resets | 0.4 hrs | Self-service portal exists |
| Technical support | 0.4 hrs | Login issues, error messages |
| Technical vendor coordination | 0.08 hrs | ~1 hr/year for system errors |
| **TOTAL** | **2.0 hrs** | Pure technical tasks |

---

### 1C. Core Tasks Summary

**Total Core Service Owner Tasks: 10.2 hrs/month (122 hrs/year) = 6.6% FTE**

This represents the **visible, documented tasks** that transfer from business to IT:
- User account creation/removal
- Password resets
- Permission changes (technical execution)
- Technical support
- Technical vendor coordination

**BUT THIS IS ONLY 19% OF THE ACTUAL WORK!**

---

## Part 2: Technical Onboarding Training

### 2A. Training Volume (Based on Kubal 2025 Data)

**New employees in 2025:** 110 people (including sommarvikarier)
**Peak months:** March, April, May

#### New Users Per System Per Year

| System | New Users/Year | Monthly Average | Peak Month |
|--------|---------------|-----------------|------------|
| **Agda/Visma** | 110 | 9.2 users | 30 users |
| **Flexite** | 110 | 9.2 users | 30 users |
| **Idus** | 18 (mid-estimate) | 1.5 users | 2 users |
| **Ascendo** | 12 | 1 user | 1 user |
| **TOTAL** | **250 users/year** | **20.8 users/month** | **63 users** |

---

### 2B. Training Time Per Session

**Your specification:** 30-45 minutes per session, max 1 hour

**Calculation basis:** 30-45 minutes average = **37.5 minutes per user**

---

### 2C. Annual Training Time Calculation

| System | New Users/Year | Minutes per User | Hours/Year |
|--------|---------------|------------------|------------|
| Agda/Visma | 110 | 37.5 min | 68.75 hrs |
| Flexite | 110 | 37.5 min | 68.75 hrs |
| Idus | 18 | 37.5 min | 11.25 hrs |
| Ascendo | 12 | 37.5 min | 7.5 hrs |
| **TOTAL** | **250** | | **156.25 hrs/year** |

**Rounded: 156 hours/year**

---

### 2D. Monthly Training Time (With Seasonality)

**Average month (normal hiring):**
- 20.8 users × 37.5 min = 780 min = **13 hours/month**

**Peak months (March, April, May):**
- 63 users × 37.5 min = 2,362 min = **39.4 hours/month**

**Low months:**
- 5 users × 37.5 min = 187 min = **3.1 hours/month**

**Annual average: 156 hrs ÷ 12 months = 13 hrs/month**

**BUT:** Since hiring is concentrated in 3 peak months:
- Peak months (Mar-May): 3 months × 39.4 hrs = 118 hrs
- Normal months (9 months): 9 months × 4.2 hrs = 38 hrs
- **Total: 156 hrs/year**

**For calculation purposes, using weighted monthly average:**
- (118 + 38) ÷ 12 = **13 hrs/month average**
- **But actual monthly range: 3-39 hrs/month**

---

### 2E. Technical Onboarding Training Summary

**Annual: 156 hours/year = 8.5% FTE**
**Monthly average: 13 hours/month**
**Peak month: 39.4 hours/month**
**Normal month: 3-4 hours/month**

**What IT covers in 30-45 minutes:**
- System access (login URL, credentials)
- Password reset procedures
- Basic navigation overview
- Who to contact for technical vs business issues
- Where to find help documentation

**What IT does NOT cover (stays with business):**
- Business process training
- Workflow procedures
- Compliance requirements
- Business rules and policies

---

## Part 3: Documentation Burden

### 3A. Year 1 Documentation Creation

**Technical guides for all 4 systems:**
- Setup time: 12-15 hours one-time
- **Monthly equivalent (Year 1): 12-15 hrs ÷ 12 = 1.0-1.25 hrs/month**

**Using: 13 hours/year = 1.1 hrs/month in Year 1**

---

### 3B. Year 2+ Documentation Maintenance

**Annual review and updates:**
- 4-5 hours/year
- **Monthly equivalent: 4-5 hrs ÷ 12 = 0.33-0.42 hrs/month**

**Using: 4 hours/year = 0.33 hrs/month ongoing**

---

### 3C. Documentation Summary

**Year 1:** 13 hours one-time = 1.1 hrs/month = 0.7% FTE
**Year 2+:** 4 hours/year = 0.33 hrs/month = 0.2% FTE

---

## Part 4: Hidden Operational Burdens

### 4A. Request Management & Communication Overhead

**What it includes:**
- Processing account requests (emails, tickets)
- Clarifying requirements with business approvers
- Sending confirmations to users
- Following up on pending requests
- Managing request queue

**Time per transaction:**
- Account creation request: 5-10 min
- Password reset request: 2-3 min
- Permission change: 5 min
- General inquiry: 3-5 min

**Volume per month:**
- New accounts: 20 × 5 min = 100 min
- Account removals: 15 × 3 min = 45 min
- Password resets: 10 × 2 min = 20 min
- Permission changes: 5 × 5 min = 25 min
- Other requests: 10 × 3 min = 30 min

**Total: 220 minutes/month = 3.7 hrs/month = 2.4% FTE**

---

### 4B. Process Development & Refinement

**Year 1 setup:**
- Account request workflows: 8 hrs
- Permission templates: 12 hrs
- Procedure documentation: 8 hrs
- Email templates: 4 hrs
- **Total: 32 hours one-time**

**Ongoing (Year 2+):**
- Monthly refinement: 1 hr/month
- Quarterly review: 2 hrs/quarter = 0.67 hrs/month
- **Total: 1.7 hrs/month = 1.1% FTE**

---

### 4C. Ticketing System Configuration

**Year 1 setup (existing system, just configure):**
- Create categories: 4 hrs
- Configure workflows: 6 hrs
- Set up routing: 4 hrs
- Define SLAs: 2 hrs
- Train IT staff: 4 hrs
- **Total: 20 hours one-time**

**Ongoing:**
- Weekly ticket review: 30 min/week = 2 hrs/month
- Monthly cleanup: 30 min/month = 0.5 hrs/month
- **Total: 2.5 hrs/month = 1.6% FTE**

---

### 4D. Business Team Coordination

**Setup phase (Months 1-6):**
- Weekly sync with each super user: 4 × 30 min × 4 weeks = 8 hrs/month
- Ad-hoc clarifications: 2 hrs/month
- **Total: 10 hrs/month**

**Steady state (Months 7+):**
- Bi-weekly syncs: 4 × 30 min × 2 = 4 hrs/month
- Ad-hoc coordination: 1 hr/month
- Monthly Service Owner meeting: 1 hr/month
- **Total: 6 hrs/month = 3.9% FTE**

**Peak months (March-May):**
- Additional coordination for sommarvikarier: +5 hrs/month
- **Peak total: 11 hrs/month**

---

### 4E. Metrics & Reporting

**Year 1 setup:**
- Create dashboards: 8 hrs
- Set up reports: 6 hrs
- Define KPIs: 4 hrs
- **Total: 18 hours one-time**

**Ongoing:**
- Weekly SLA monitoring: 15 min/week = 1 hr/month
- Monthly report creation: 1 hr/month
- Quarterly analysis: 2 hrs/quarter = 0.67 hrs/month
- **Total: 2.7 hrs/month = 1.7% FTE**

---

### 4F. Knowledge Transfer from Business Teams

**Year 1 only:**
- Deep dive per system: 4 hrs × 4 = 16 hrs
- Shadowing: 8 hrs
- Documentation: 6 hrs
- **Total: 30 hours one-time**

**First 6 months ongoing:**
- Weekly clarifications: 1 hr/week = 4 hrs/month
- Decreasing to 1 hr/month after Month 6

**Average Year 1: (6 × 4) + (6 × 1) = 30 hrs spread = 2.5 hrs/month**

---

### 4G. Security & Compliance Activities

**Quarterly access reviews:**
- Review accounts: 8 hrs/quarter
- Identify inactive: 1 hr/quarter
- GDPR compliance (1-month retention): 1 hr/quarter
- Documentation: 2 hrs/quarter
- **Total: 12 hrs/quarter = 4 hrs/month**

**Annual:**
- Security audit support: 8 hrs/year
- GDPR documentation: 4 hrs/year
- **Total annual: 12 hrs**

**Combined average: (48 + 12) ÷ 12 = 5 hrs/month = 3.3% FTE**

---

### 4H. System Upgrades & Change Management

**Additional to infrastructure (communication/documentation):**
- User communication per upgrade: 2 hrs × 8 upgrades/year = 16 hrs
- Documentation updates: 1 hr × 8 = 8 hrs
- **Total: 24 hrs/year = 2 hrs/month = 1.3% FTE**

---

### 4I. Service Owner Governance

**Monthly:**
- Meeting preparation: 30 min/month
- **Total monthly: 0.5 hrs**

**Quarterly:**
- Business review meeting: 2 hrs/quarter = 0.67 hrs/month
- Preparation: 2 hrs/quarter = 0.67 hrs/month
- **Total quarterly: 1.3 hrs/month**

**Annual:**
- Planning session: 4 hrs/year = 0.33 hrs/month

**Total: 2.2 hrs/month = 1.4% FTE**

---

### 4J. Continuous Improvement & Optimization

**Year 1:** Minimal (focus on getting it working)
- 0.5 hrs/month

**Year 2+:**
- Identify automation: 1 hr/month
- Implement improvements: 2 hrs/quarter = 0.67 hrs/month
- **Total: 1.7 hrs/month = 1.1% FTE**

---

### 4K. Escalation Handling & Problem Management

**Complex issues beyond routine:**
- Complex escalations: 2/month × 2 hrs = 4 hrs
- Root cause analysis: 1 hr/month
- Post-incident reviews: 1 hr/quarter = 0.33 hrs/month
- **Total: 5.3 hrs/month = 3.5% FTE**

---

### 4L. Hidden Burdens Summary

| Hidden Burden | Hours/Month | FTE % | Notes |
|---------------|-------------|-------|-------|
| Request management | 3.7 hrs | 2.4% | Communication overhead |
| Process development | 1.7 hrs | 1.1% | Ongoing refinement |
| Ticketing system | 2.5 hrs | 1.6% | Management, not just use |
| Business coordination | 6 hrs | 3.9% | Meetings, clarifications |
| Metrics & reporting | 2.7 hrs | 1.7% | SLA tracking, reports |
| Knowledge transfer | 0 hrs* | 0% | Year 1 only |
| Security & compliance | 5 hrs | 3.3% | Quarterly reviews, GDPR |
| System upgrades | 2 hrs | 1.3% | User communication |
| Governance | 2.2 hrs | 1.4% | Formal meetings |
| Continuous improvement | 1.7 hrs | 1.1% | Automation, optimization |
| Escalation handling | 5.3 hrs | 3.5% | Complex issues |
| | | | |
| **TOTAL HIDDEN** | **32.8 hrs/month** | **21.4% FTE** | **Steady state** |

*Knowledge transfer is Year 1 only setup work

**One-time setup work (Year 1):**
- Process development: 32 hrs
- Ticketing config: 20 hrs
- Metrics setup: 18 hrs
- Knowledge transfer: 30 hrs
- **Total: 100 hours one-time**

---

## Part 5: Complete IT Burden - All Components

### 5A. Year 1 Complete Picture

| Component | Hours/Month | Hours/Year | FTE % | Type |
|-----------|-------------|------------|-------|------|
| **Core Service Owner tasks** | 10.2 hrs | 122 hrs | 6.6% | Ongoing |
| **Technical onboarding** | 13 hrs* | 156 hrs | 8.5% | Ongoing |
| **Documentation creation** | 1.1 hrs | 13 hrs | 0.7% | One-time |
| **Hidden burdens (ongoing)** | 32.8 hrs | 394 hrs | 21.4% | Ongoing |
| **Setup tasks** | - | 100 hrs | 5.4% | One-time |
| | | | | |
| **YEAR 1 TOTAL** | **57.1 hrs/month** | **785 hrs/year** | **42.7% FTE** | |

*Training average - actual range 3-39 hrs/month depending on hiring season

**Per IT person (2 staff):** 28.5 hrs/month = **7.1 hrs/week = 85 minutes/day**

---

### 5B. Year 2+ Steady State

| Component | Hours/Month | Hours/Year | FTE % | Type |
|-----------|-------------|------------|-------|------|
| **Core Service Owner tasks** | 10.2 hrs | 122 hrs | 6.6% | Ongoing |
| **Technical onboarding** | 13 hrs* | 156 hrs | 8.5% | Ongoing |
| **Documentation maintenance** | 0.33 hrs | 4 hrs | 0.2% | Ongoing |
| **Hidden burdens** | 32.8 hrs | 394 hrs | 21.4% | Ongoing |
| | | | | |
| **YEAR 2+ TOTAL** | **56.3 hrs/month** | **676 hrs/year** | **36.7% FTE** | |

*Training average - actual range 3-39 hrs/month depending on hiring season

**Per IT person (2 staff):** 28.2 hrs/month = **7.0 hrs/week = 84 minutes/day**

---

### 5C. Monthly Breakdown by Component (Steady State)

```
Total IT Service Owner Work: 56.3 hrs/month (36.7% FTE)

Component Breakdown:
████████████████████████████████████ Hidden Burdens: 32.8 hrs (58%)
█████████████████████ Technical Onboarding: 13 hrs (23%)
█████████████ Core Tasks: 10.2 hrs (18%)
▓ Documentation: 0.33 hrs (1%)
```

**Key insight:** Hidden burdens are larger than core tasks + training combined!

---

### 5D. Peak Month Impact (March, April, May)

**During sommarvikarier preparation:**

| Component | Normal Month | Peak Month | Difference |
|-----------|-------------|------------|------------|
| Core Service Owner | 10.2 hrs | 10.2 hrs | - |
| Technical onboarding | 13 hrs | 39.4 hrs | +26.4 hrs |
| Documentation | 0.33 hrs | 0.33 hrs | - |
| Business coordination | 6 hrs | 11 hrs | +5 hrs |
| Request management | 3.7 hrs | 7 hrs | +3.3 hrs |
| Other hidden burdens | 23.1 hrs | 23.1 hrs | - |
| | | | |
| **TOTAL** | **56.3 hrs** | **91 hrs** | **+34.7 hrs** |

**Peak month per IT person:** 45.5 hrs/month = **11.4 hrs/week = 137 minutes/day**

**Peak months are 62% higher workload than normal months!**

---

## Part 6: Visual Breakdown - Where Does the Time Go?

### 6A. Percentage Breakdown (Steady State)

| Component | Hours/Month | % of Total |
|-----------|-------------|------------|
| **Hidden Burdens** | | |
| Business coordination | 6.0 hrs | 11% |
| Escalation handling | 5.3 hrs | 9% |
| Security & compliance | 5.0 hrs | 9% |
| Request management | 3.7 hrs | 7% |
| Reporting & metrics | 2.7 hrs | 5% |
| Ticketing system | 2.5 hrs | 4% |
| Governance | 2.2 hrs | 4% |
| System upgrades | 2.0 hrs | 4% |
| Process refinement | 1.7 hrs | 3% |
| Continuous improvement | 1.7 hrs | 3% |
| **Subtotal Hidden** | **32.8 hrs** | **58%** |
| | | |
| **Technical Onboarding** | 13.0 hrs | 23% |
| | | |
| **Core Service Owner** | | |
| User accounts | 5.6 hrs | 10% |
| Technical support | 3.2 hrs | 6% |
| Password resets | 1.0 hrs | 2% |
| Technical vendor | 0.4 hrs | 1% |
| **Subtotal Core** | **10.2 hrs** | **18%** |
| | | |
| **Documentation** | 0.33 hrs | 1% |
| | | |
| **GRAND TOTAL** | **56.3 hrs/month** | **100%** |

---

### 6B. Top 10 Time Consumers

| Rank | Activity | Hours/Month | % of Total |
|------|----------|-------------|------------|
| 1 | **Technical onboarding training** | 13.0 hrs | 23% |
| 2 | **Business team coordination** | 6.0 hrs | 11% |
| 3 | **User account management** | 5.6 hrs | 10% |
| 4 | **Escalation handling** | 5.3 hrs | 9% |
| 5 | **Security & compliance** | 5.0 hrs | 9% |
| 6 | **Request management overhead** | 3.7 hrs | 7% |
| 7 | **Technical support** | 3.2 hrs | 6% |
| 8 | **Metrics & reporting** | 2.7 hrs | 5% |
| 9 | **Ticketing system management** | 2.5 hrs | 4% |
| 10 | **Service Owner governance** | 2.2 hrs | 4% |
| | **Top 10 Total** | **48.2 hrs** | **86%** |

**These 10 activities account for 86% of all Service Owner work!**

---

## Part 7: Comparison to Original Estimates

### 7A. What We Originally Thought vs Reality

| Estimate Type | Hours/Month | FTE % | Reality Check |
|---------------|-------------|-------|---------------|
| **Original: Core tasks only** | 10.2 hrs | 6.6% | ❌ Too optimistic |
| **+ Training (old 15 min estimate)** | 11.4 hrs | 7.4% | ❌ Training underestimated |
| **+ Training (correct 37.5 min)** | 23.2 hrs | 15% | ⚠️ Still incomplete |
| **+ All hidden burdens** | **56.3 hrs** | **36.7%** | ✅ **Complete picture** |

**The real burden is 5.5X larger than the original core tasks estimate!**

---

### 7B. What Changed from Original Analysis

**Corrections made:**
1. ✅ Training time: 15 min → 37.5 min per user (2.5X increase)
2. ✅ Training volume: Validated with actual 2025 hiring data (110 people)
3. ✅ Added all hidden operational burdens (32.8 hrs/month)
4. ✅ Included setup work for Year 1 (100 hours one-time)
5. ✅ Accounted for seasonal peaks (March-May)

---

## Part 12: Summary Tables

### 12A. Complete IT Burden Summary

| Component | Monthly | Annual | FTE % | Peak Month |
|-----------|---------|--------|-------|------------|
| **Core Service Owner** | 10.2 hrs | 122 hrs | 6.6% | 10.2 hrs |
| **Technical Onboarding** | 13.0 hrs | 156 hrs | 8.5% | 39.4 hrs |
| **Documentation (Y2+)** | 0.3 hrs | 4 hrs | 0.2% | 0.3 hrs |
| **Hidden Burdens** | 32.8 hrs | 394 hrs | 21.4% | 41.1 hrs |
| **TOTAL STEADY STATE** | **56.3 hrs** | **676 hrs** | **36.7%** | **91.0 hrs** |

---

### 12B. Hidden Burdens Detailed Breakdown

| Category | Hours/Month | FTE % | Type |
|----------|-------------|-------|------|
| Business coordination | 6.0 hrs | 3.9% | Meetings, clarifications |
| Escalation handling | 5.3 hrs | 3.5% | Complex issues |
| Security & compliance | 5.0 hrs | 3.3% | Quarterly reviews |
| Request management | 3.7 hrs | 2.4% | Communication overhead |
| Metrics & reporting | 2.7 hrs | 1.7% | SLA tracking |
| Ticketing system | 2.5 hrs | 1.6% | Management |
| Governance | 2.2 hrs | 1.4% | Formal meetings |
| System upgrades | 2.0 hrs | 1.3% | User communication |
| Process refinement | 1.7 hrs | 1.1% | Ongoing improvement |
| Continuous improvement | 1.7 hrs | 1.1% | Automation |
| **TOTAL** | **32.8 hrs** | **21.4%** | |

---

## Conclusion

**The complete IT Service Owner burden is:**
- **56.3 hours/month (676 hours/year)**
- **36.7% FTE**
- **14.0 hours/week (normal)**
- **22.8 hours/week (peak)**

**This is 5.5X larger than the original 10.2 hrs/month estimate!**

**The difference is hidden operational burdens:**
- Coordination (6 hrs)
- Escalations (5.3 hrs)
- Compliance (5 hrs)
- Communication (3.7 hrs)
- Reporting (2.7 hrs)
- Governance (2.2 hrs)
- And more... (8.9 hrs)

**Plus technical onboarding training:**
- 13 hours/month average
- 39 hours/month during peak season


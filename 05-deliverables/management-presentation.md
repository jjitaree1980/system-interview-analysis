# IT Systems Portfolio Assessment - Kubal

**Date:** January 2026  
**Purpose:** Present assessment findings, highlight gaps, and get approval for next steps  

---

## What This Assessment Is About

We assessed all 4 business-critical IT systems at Kubal over a 2-month period (December 2025 - January 2026).   
Each system was evaluated through structured interviews with the super users who manage them daily.

**The 4 systems:**

| # | System | What It Does | Who Uses It |
|---|--------|-------------|-------------|
| 1 | **Idus** | CMMS | ~15-30 technicians & shift leaders |
| 2 | **Agda/Visma** | HR & payroll | All employees (~400) |
| 3 | **Flexite** | Safety incident reporting & compliance | All employees |
| 4 | **Ascendo** | Invoice scanning, processing & payment | 3-4 economy staff |

---

## 1. OVERALL PORTFOLIO HEALTH

```
                PORTFOLIO STATUS: HEALTHY
           3 out of 4 systems performing well

    System        Health                     Action
    ────────────────────────────────────────────────────────────
    Ascendo       ██████████  Excellent    → Maintain
    Agda/Visma    ████████──  Strong       → Train users
    Flexite       ███████───  Adequate     → Optional upgrade
    Idus          ██────────  Uncertain    → Validate first
```

> **Key message:** This is NOT a crisis. Most of our IT portfolio works well.
> There is one system (Idus) that need more information before acting.

---

## 2. SYSTEM-BY-SYSTEM COMPARISON

### At-a-Glance Matrix

| | Ascendo | Agda/Visma | Flexite | Idus |
|--|---------|-----------|---------|------|
| **Core function** | Excellent | Excellent | Good | Unclear |
| **SAP integration** | Perfect | N/A | N/A (standalone) | Reported broken |
| **User adoption** | 100% | Partial (training gap) | 100% | One person + Excel |
| **IT support needed** | Rarely | Never | Rarely | Rarely, but need IT support <br>for external inhouse app <br>(WH search & Downtime) |
| **Data confidence** | HIGH | HIGH | HIGH | LOW |
| **Investment needed** | Optional | Low (training) <br> Optional| Optional | Must validate first |

> **Note for investment needed**
> 
> Ascendo: Need to expand features for more capabilities   
> Agda/Visma: Interested in Onboard feature    
> Flexite: Users report satisfaction, but assessment reveals missing analytics capabilities. For long-term value realization, investment in analytics features is recommended.

### What Each System Does Well

| System | Strength |
|--------|----------|
| **Ascendo** | Fully automated invoice flow. OCR at 95-100% accuracy. SAP posting is instant and error-free. Saves 900-1,800 hours/year. |
| **Agda/Visma** | Perfect payroll compliance. Strong vendor (Visma). Zero IT support needed. Feature-rich platform. |
| **Flexite** | 100% incident reporting compliance. All employees use it. Manual analysis produces safety outcomes. |
| **Idus** | Manages work orders and spare parts. Core CMMS functionality appears adequate. But we only have one person's view. |

---

## 3. PAIN POINTS - Where It Hurts

### Pain Point 1 (HIGH): Idus - Everything Goes Through One Person

```
HOW MAINTENANCE WORK ORDERS FLOW TODAY:

    Technician/Operator spots a problem
                  |
                  v
    Shift Leader logs it in EXCEL             <-- Can't access Idus
                  |
                  v
    Verbal/email report to Tom                <-- Bottleneck
                  |
                  v
    Tom enters into Idus                       <-- Single point of failure
                  |
                  v
    Work order created
                  |
                  v
    Review SAP stock from external app         <-- Integration reported broken
                  |
                  v
    Idus does not support validated work plan creation
                  
```

**Why this hurts:**
- If Tom is sick or on leave, work orders don't get created unless he has a replacement
- Equipment faults can sit 2-3 days before reaching the system
- Everything is typed twice (Excel then Idus)
- Inventory visibility requires external application access, causing delays and preventing validated work plan creation in Idus.

**Need more validation:**
This finding is based on a single user report and requires validation through interviews with technicians, shift leaders, and operators before actionable conclusions can be drawn.

---

### Pain Point 2 (HIGH): Hidden Excel Layer

Shift leaders maintain personal Excel spreadsheets as their primary tracking tool. This creates double work and data that never reaches formal systems.

**The critical comparison:**

```
SAME SHIFT LEADERS, TWO DIFFERENT BEHAVIOURS:

    For MAINTENANCE (Idus):           For SAFETY (Flexite):
    ─────────────────────────         ─────────────────────────
    Use Excel workarounds             Enter data directly
    Can't access the system           Have full system access
    Adoption: Poor                    Adoption: 100%

    WHY THE DIFFERENCE?
    → They don't have Idus access, the license is maintain up to 30 licenses.
    → They DO have Flexite access
    → Same people. Same capability. Different access.
```
> By this practice, the issue may be about INTENTIONAL WORKFLOW CONTROL, not system limitation even Idus try to maintain license upto 30 licenses.
> The felanmälan system appears to function as an approval checkpoint where UH reviews fault reports before creating Idus work orders.
> If true, what looks like "inefficiency" may actually be purposeful process governance - and the question becomes whether this control justifies its operational cost.

---

### Pain Point 3 (MEDIUM): Agda/Visma - Employees Don't Use What They Have

- System has self-service features (shift preferences, digital payslips, schedule swaps)
- Employees don't know about them or don't use them
- Helena (HR) manually handles requests the system could automate
- Estimated waste: ~75K SEK/year

**This is a training problem, not a system problem.** 

---

### Pain Point 4 (LOW): Flexite - Manual Government Reporting

- Exporting data for Arbetsmiljöverket requires manual formatting and manual reporting
- User does trend analysis manually (but does it well)
- Annual cost of manual work: ~66K SEK/year
- Most of this is part of their core role, not pure waste

**Low priority.** System is meeting its purpose.
However, the system would be more efficient with built-in analytical capabilities.

---

## 4. GAPS SUMMARY

| Gap | System | Severity | Could Be Easy to Fix? |
|-----|--------|----------|-----------------------|
| Shift leaders locked out | Idus | HIGH | YES - if it's just permissions  |
| SAP integration broken | Idus | HIGH (if confirmed) | Unknown - needs IT assessment |
| One-person dependency | Idus | HIGH | MEDIUM - needs backup training |
| Employee feature awareness | Agda/Visma | MEDIUM | YES - training campaign |
| Key-person dependencies | All systems | MEDIUM | MEDIUM - cross-training |
| Government report automation | Flexite | LOW | MEDIUM - vendor feature or alternative replacement |
| Analytics capability | Flexite | LOW | Optional enhancement - no immediate business case, but potential long-term value. |

**Pattern:** Idus contains most high-severity gaps, but validation is required before committing to solutions.

---

## 5. THE CONFIDENCE PROBLEM - Why We Can't Act on Idus Yet

| System | Who We Interviewed | Confidence |
|--------|-------------------|------------|
| **Ascendo** | Rhodora + Inna (2 users, questionnaire) | HIGH |
| **Agda/Visma** | Helena (super user, face-to-face) | HIGH |
| **Flexite** | Jan-Eric (super user, face-to-face) | HIGH |
| **Idus** | Tom only (super user, face-to-face) | LOW |

**Why Idus confidence is LOW:**
- Only 1 person interviewed out of 15-30 users
- Tom is the gatekeeper of the system - potential bias
- Waste figures are his estimates, not measured data
- No technician or shift leader perspective included
- SAP integration status not verified with Rusal IT team

**The Idus waste figures are NOT validated.** Potential waste areas have been identified, but actual numbers could be significantly different - higher or lower - once more stakeholders are consulted and technical facts are confirmed.

---

## 6. OPPORTUNITIES TO IMPROVE - Ranked by Priority

### PRIORITY 1: Agda Training (DO NOW)

| | Detail |
|--|--------|
| **What** | Training sessions for employees on self-service features |
| **Investment** | ~25K SEK |
| **Expected return** | ~75K SEK/year in reduced manual work |
| **Payback** | ~4 months |
| **Risk** | Low - validated with Helena |
| **Confidence** | HIGH |
| **Timeline** | Q1 2026 |

**Why first:** Cheapest investment. Clearest return. Lowest risk. Proven need.

---

### PRIORITY 2: Idus Validation Study (INVESTIGATE NOW)

| | Detail |
|--|--------|
| **What** | Broader assessment: interview 8-10 users, test SAP, track Excel usage, compare alternatives |
| **Why** | Current data is single-source and unvalidated. We need facts before spending. |
| **Deliverable** | Data-driven improvement roadmap with validated priorities and costs |
| **Risk of skipping** | Investing in wrong priorities or overspending |
| **Confidence** | Study will PRODUCE the confidence we currently lack |
| **Timeline** | Month 1-3 study, Month 4 decision |

**What the study answers:**
1. Is the SAP integration truly broken, or misconfigured?
2. Do shift leaders actually want direct Idus access?
3. Would giving them access eliminate the Excel problem?
4. What do technicians actually need (mobile? desktop? both?)
5. Is the current system worth upgrading, or should we look at alternatives?

**After the study, we choose one path:**

```
    STUDY COMPLETE (Month 4)
              |
     ┌────────┼────────┐
     v        v        v
   PATH A   PATH B   PATH C
   Full     Targeted  Alternative
   upgrade  fixes     solution

   (if all  (if some  (if better
   issues   issues    options
   confirmed) minor)  exist)
```

---

### PRIORITY 3: Flexite Reporting (DEFER)

| | Detail |
|--|--------|
| **What** | Automate government report formatting |
| **Investment** | ~60-90K SEK |
| **Expected return** | ~10K SEK/year |
| **Risk** | Low, but ROI is weak |
| **Timeline** | Q2 2026 at earliest |

**Why defer:** Return doesn't justify urgency. Current process works.
Bring up only if there's remaining budget after priorities 1 and 2.

---

## 7. WHAT ASCENDO TEACHES US

Ascendo is our internal proof that excellent IT integration is achievable.

```
ASCENDO WORKFLOW (Reference Standard):

    Invoice arrives
        |
        v
    [AUTO] Ascendo captures it           No manual entry
        |
        v
    [AUTO] OCR reads the data            95-100% accuracy
        |
        v
    [AUTO] Routes to the right approver  Smart routing
        |
        v
    Approval click
        |
        v
    [AUTO] Posts to SAP immediately      Real-time
        |
        v
    [AUTO] Schedules payment             Fully automated
        |
        v
    RESULT: Zero reconciliation issues
```

**Value:** ~386K SEK/year in automation savings

**Why this matters for the Idus discussion:**
- SAP integration IS achievable at Kubal (Ascendo proves it)
- Successful integration requires effective vendor partnership with IT
- Concern: Did the Idus vendor deliver on agreed integration features during implementation?
- Question: Was seamless SAP integration part of the original Idus contract specifications?
- Ascendo sets the benchmark for what "good" looks like and should be the standard when evaluating any system

---

## 8. RECOMMENDED TIMELINE

```
MONTH 1-3                    MONTH 4                 MONTH 5+
─────────────────────        ──────────────────      ─────────────────
Launch Agda training         Present Idus study      Execute chosen
Start Idus validation        results to mgmt         Idus path
  - User interviews
  - SAP technical check      DECISION POINT:         Monitor Agda
  - Excel tracking           Choose Path A/B/C       training results
  - Alternative research     for Idus investment
  - Shadow excel workflow                             Optional: Flexite
                             Approve budget           reporting upgrade
```

---

## 9. WHAT NEED FOR DECISION

### Decision 1: Approve Agda Training Campaign
- Budget: ~25K SEK
- Recommendation: Approve (validated, clear ROI)

### Decision 2: Approve Idus Validation Study
- This is the critical decision
- **Option A (Recommended):** Run the validation study first, then decide
- **Option B:** Skip validation, invest in Idus directly (faster, but higher risk)
- **Option C:** Defer all Idus work (cheapest now, but issues continue)

### Decision 3: Flexite Reporting
- Recommendation: Defer to Q2. Not urgent.

---

## 10. SUMMARY

**1. The portfolio is healthy.**
Three out of four systems work well. This is optimization, not crisis management.

**2. Idus findings need validation.**  
We found potential issues, but they come from one person. The waste figures
are not validated. We need a broader study before committing budget.

**3. The Excel insight changes the equation.**  
Shift leaders maintain shadow Excel workflows as approval checkpoints before entries reach Idus or Flexite.   
This suggests the issue is about intentional workflow control requiring manual triage decisions, not only system capabilities.   
The solution may be redesigning the approval process to enable direct system entry with appropriate governance built in.

**4. There's a clear quick win.**
Agda training: 25K investment, 75K/year return, 4-month payback.
This can start immediately.

**5. Ascendo is the benchmark.**
It proves our team can achieve excellent system integration.
Use as the benchmark for Idus and other system improvements.

---

**Document:** Management Presentation - IT Systems Portfolio Assessment
**Version:** 1.0
**Source:** Executive Summary v3, Detailed Analysis Final Report
**Status:** Ready for presentation

# Management Presentation
## IT Systems Portfolio Assessment - Kubal

**Date:** January 2026
**Presenter:** Jitaree
**Duration:** ~15-20 minutes
**Purpose:** Present assessment findings, highlight gaps, and get approval for next steps

---

## OPENING - What This Assessment Is About

We assessed all 4 business-critical IT systems at Kubal over a 2-month period
(December 2025 - January 2026). Each system was evaluated through structured
interviews with the super users who manage them daily.

**The 4 systems:**

| # | System | What It Does | Who Uses It |
|---|--------|-------------|-------------|
| 1 | **Idus** | Maintenance management (work orders, spare parts) | ~15-30 technicians & shift leaders |
| 2 | **Agda/Visma** | HR, payroll, scheduling | All employees (~60-80) |
| 3 | **Flexite** | Safety incident reporting & compliance | All employees |
| 4 | **Ascendo** | Invoice scanning, processing & payment | 2-3 economy staff |

---

## 1. OVERALL PORTFOLIO HEALTH

```
                PORTFOLIO STATUS: HEALTHY
           3 out of 4 systems performing well

    System        Health         Action
    ─────────────────────────────────────────
    Ascendo       ██████████  Excellent    → Maintain
    Agda/Visma    ████████──  Strong       → Train users
    Flexite       ███████───  Adequate     → Optional upgrade
    Idus          ██────────  Uncertain    → Validate first
```

> **Key message:** This is NOT a crisis. Most of our IT portfolio works well.
> We have one system (Idus) where we need more information before acting.

---

## 2. SYSTEM-BY-SYSTEM COMPARISON

### At-a-Glance Matrix

| | Ascendo | Agda/Visma | Flexite | Idus |
|--|---------|-----------|---------|------|
| **Core function** | Excellent | Excellent | Good | Unclear |
| **SAP integration** | Perfect | Under review | N/A (standalone) | Reported broken |
| **User adoption** | 100% | Partial (training gap) | 100% | One person + Excel |
| **IT support needed** | Rarely | Never | Rarely | Rarely |
| **Data confidence** | HIGH | HIGH | HIGH | LOW |
| **Investment needed** | None | Low (training) | Optional | Must validate first |

### What Each System Does Well

| System | Strength |
|--------|----------|
| **Ascendo** | Fully automated invoice flow. OCR at 95-100% accuracy. SAP posting is instant and error-free. Saves 900-1,800 hours/year. |
| **Agda/Visma** | Perfect payroll compliance. Strong vendor (Visma). Zero IT support needed. Feature-rich platform. |
| **Flexite** | 100% incident reporting compliance. All employees use it. Jan-Eric's manual analysis produces excellent safety outcomes. |
| **Idus** | Manages work orders and spare parts. Core CMMS functionality appears adequate. But we only have one person's view. |

---

## 3. PAIN POINTS - Where It Hurts

### Pain Point 1 (HIGH): Idus - Everything Goes Through One Person

```
HOW MAINTENANCE WORK ORDERS FLOW TODAY:

    Technician/Operator spots a problem
                  |
                  v
    Shift Leader logs it in EXCEL       <-- Can't access Idus
                  |
                  v
    Verbal/email report to Tom          <-- Bottleneck
                  |
                  v
    Tom enters into Idus                <-- Single point of failure
                  |
                  v
    Work order created
                  |
                  v
    Manual export to SAP                <-- Integration reported broken
```

**Why this hurts:**
- If Tom is sick or on leave, work orders don't get created
- Equipment faults can sit 2-3 days before reaching the system
- Everything is typed twice (Excel then Idus)
- SAP reportedly not receiving data automatically

**But we need to be careful:**
This picture comes from Tom alone. We have not spoken to technicians,
shift leaders, or IT. We need to verify before acting.

---

### Pain Point 2 (HIGH): Hidden Excel Layer

Shift leaders maintain personal Excel spreadsheets as their primary
tracking tool. This creates double work and data that never reaches
formal systems.

**The critical comparison:**

```
SAME SHIFT LEADERS, TWO DIFFERENT BEHAVIOURS:

    For MAINTENANCE (Idus):           For SAFETY (Flexite):
    ─────────────────────────         ─────────────────────────
    Use Excel workarounds             Enter data directly
    Can't access the system           Have full system access
    Adoption: Poor                    Adoption: 100%

    WHY THE DIFFERENCE?
    → They don't have Idus access
    → They DO have Flexite access
    → Same people. Same capability. Different access.
```

> **This is the most important finding in the whole assessment.**
> It tells us the problem may be about ACCESS, not about system features
> or user capability. If true, the fix could be much simpler and cheaper
> than a full system upgrade.

---

### Pain Point 3 (MEDIUM): Agda/Visma - Employees Don't Use What They Have

- System has self-service features (shift preferences, digital payslips, schedule swaps)
- Employees don't know about them or don't use them
- Helena (HR) manually handles requests the system could automate
- Estimated waste: ~75K SEK/year

**This is a training problem, not a system problem.** Easy to fix.

---

### Pain Point 4 (LOW): Flexite - Manual Government Reporting

- Exporting data for Arbetsmiljoeverket requires manual formatting
- Jan-Eric does trend analysis manually (but does it well)
- Annual cost of manual work: ~66K SEK/year
- Most of this is part of Jan-Eric's core role, not pure waste

**Low priority.** System is meeting its purpose.

---

## 4. GAPS SUMMARY

| Gap | System | Severity | Could Be Easy to Fix? |
|-----|--------|----------|-----------------------|
| Shift leaders locked out | Idus | HIGH | YES - if it's just permissions |
| SAP integration broken | Idus | HIGH (if confirmed) | Unknown - needs IT assessment |
| One-person dependency | Idus | HIGH | MEDIUM - needs backup training |
| Employee feature awareness | Agda/Visma | MEDIUM | YES - training campaign |
| Key-person dependencies | All systems | MEDIUM | MEDIUM - cross-training |
| Government report automation | Flexite | LOW | YES - vendor feature |
| Analytics capability | Flexite | LOW | Not needed currently |

**Pattern:** Most high-severity gaps are concentrated in Idus,
and most of them need validation before we know the real fix.

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
- SAP integration status not verified with IT team

**The Idus waste figures are NOT validated.** We identified potential
waste areas, but the actual numbers could be significantly different -
higher or lower - once we talk to more people and check the technical
facts.

> **We should not commit budget to Idus improvements based on
> one person's assessment.** That's the core recommendation.

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
- The IT team has done it before
- If Idus-SAP integration is truly broken, we know fixing it is possible
- Ascendo sets the benchmark for what "good" looks like

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
                                                     Optional: Flexite
                             Approve budget           reporting upgrade
```

---

## 9. WHAT WE NEED FROM MANAGEMENT

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

## 10. SUMMARY - Five Things to Remember

**1. The portfolio is healthy.**
Three out of four systems work well. This is optimization, not crisis management.

**2. Idus findings need validation.**
We found potential issues, but they come from one person. The waste figures
are not validated. We need a broader study before committing budget.

**3. The Excel insight changes the equation.**
Same shift leaders who "can't use" Idus successfully use Flexite at 100%.
The problem is likely access, not capability. The fix could be simple.

**4. There's a clear quick win.**
Agda training: 25K investment, 75K/year return, 4-month payback.
This can start immediately.

**5. Ascendo is the benchmark.**
It proves our team can achieve excellent system integration.
Use it as the standard for Idus improvements.

---

**Document:** Management Presentation - IT Systems Portfolio Assessment
**Version:** 1.0
**Source:** Executive Summary v3, Detailed Analysis Final Report
**Status:** Ready for presentation

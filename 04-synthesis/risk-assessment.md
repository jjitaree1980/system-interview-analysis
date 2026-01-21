# IT Systems: Investment Decision Framework
**Kubal Manufacturing - January 2026**

---

## 🎯 THE DECISION YOU NEED TO MAKE

**Question:** Which systems get investment priority in 2026?

**Answer:** Clear priorities exist for 3 of 4 systems. The 4th (Idus) requires a GO/NO-GO decision first.

---

## 📊 PORTFOLIO AT A GLANCE

### System Health Cards

```
╔═══════════════════════════════════════════════════════════════╗
║  IDUS (Maintenance System)                        Status: 🔴  ║
╠═══════════════════════════════════════════════════════════════╣
║  Annual Waste:     4.73M SEK (claimed, UNVALIDATED)          ║
║  Confidence:       🔴 LOW (single interview, bias indicators) ║
║  Users:            30 technicians + 1 super user (Tom)        ║
║  Critical Issue:   SAP integration broken, Excel bottleneck   ║
║                                                               ║
║  DECISION NEEDED:  Invest 800K in upgrade OR start RFP?      ║
║  Timeline:         Must decide by Month 3 (Q1 2026)          ║
╚═══════════════════════════════════════════════════════════════╝

╔═══════════════════════════════════════════════════════════════╗
║  AGDA/VISMA (HR & Payroll)                    Status: 🟢      ║
╠═══════════════════════════════════════════════════════════════╣
║  Annual Waste:     75K SEK (validated, confirmed)            ║
║  Confidence:       🟢 HIGH (multiple stakeholders)           ║
║  Users:            100 employees, 2 HR staff                 ║
║  Critical Issue:   Unused self-service features              ║
║                                                               ║
║  ACTION REQUIRED:  Training campaign (30-70K investment)      ║
║  ROI:              4-18 months payback, LOW RISK             ║
╚═══════════════════════════════════════════════════════════════╝

╔═══════════════════════════════════════════════════════════════╗
║  FLEXITE (Safety & Incidents)                 Status: 🟡      ║
╠═══════════════════════════════════════════════════════════════╣
║  Annual Waste:     60-90K SEK (validated)                    ║
║  Confidence:       🟢 HIGH (100% user compliance)            ║
║  Users:            All employees, 1 H&S manager (Jan-Eric)   ║
║  Critical Issue:   No government integration (144 rpts/year) ║
║                                                               ║
║  ACTION REQUIRED:  Integration roadmap (100-150K investment) ║
║  ROI:              12-30 months, compliance risk reduction   ║
╚═══════════════════════════════════════════════════════════════╝

╔═══════════════════════════════════════════════════════════════╗
║  ASCENDO (Invoice Processing)                 Status: ⚪      ║
╠═══════════════════════════════════════════════════════════════╣
║  Annual Waste:     Unknown (assessment in progress)          ║
║  Confidence:       TBD (questionnaire due next Wednesday)    ║
║  Users:            3 invoice processors (Rhodora, Ksenia)    ║
║  Critical Issue:   Unknown until assessment completes        ║
║                                                               ║
║  NEXT STEP:        Complete assessment, update in Week 2     ║
╚═══════════════════════════════════════════════════════════════╝
```

---

## 🚨 THE IDUS QUESTION: Why This Dominates Your Risk

### The Claim
"Idus has 4.73M SEK annual waste. We should invest 800K to fix it."

### The Reality
```
┌─────────────────────────────────────────────────────────────┐
│  DATA QUALITY BREAKDOWN                                     │
├────────────────────────────┬────────────────────────────────┤
│  Validated Facts           │  Unvalidated Estimates         │
├────────────────────────────┼────────────────────────────────┤
│ ✅ SAP integration broken  │ ❓ 1.55M SEK/year from manual  │
│ ✅ Tom is sole super user  │    work (no time-tracking)     │
│ ✅ Excel workflow exists   │                                │
│ ✅ No mobile access        │ ❓ 981K SEK/year productivity  │
│ ✅ Reporting takes 2 days  │    loss (estimated at 5-10%)   │
│                            │                                │
│                            │ ❓ 627K SEK performance loss   │
│                            │    (10% productivity assumed)  │
│                            │                                │
│                            │ ❓ All estimates from Tom only │
│                            │    (no corroboration)          │
└────────────────────────────┴────────────────────────────────┘

CONFIDENCE LEVEL: 🔴 LOW
- Single source (Tom)
- No time-tracking data
- Bias indicators present (status quo preference, professional identity)
- Comparison to 2016 Maximo, not modern alternatives
```

### The Risk
Making 800K investment decision based on unvalidated estimates could result in:
- ❌ Wrong solution for the actual problem
- ❌ 5-10 year commitment to suboptimal platform
- ❌ Opportunity cost (better alternatives missed)
- ❌ Continued waste if root causes misunderstood

---

## 💡 THREE DECISION PATHS FOR IDUS

### Path 1: The Validation Study (RECOMMENDED)
```
┌──────────────────────────────────────────────────────────┐
│  VALIDATE FIRST, DECIDE LATER                           │
├──────────────────────────────────────────────────────────┤
│  Investment:   100K SEK (4 months)                       │
│  Activities:   • Time-tracking study (measure, don't     │
│                  estimate waste)                         │
│                • Multi-user interviews (technicians,     │
│                  production team)                        │
│                • Modern CMMS market evaluation           │
│                  (Planon, Ultimo, Fiix)                  │
│                • 5-year TCO comparison                   │
│                                                          │
│  Outcome:      Data-driven decision gate at Month 4      │
│  Risk Level:   LOW - Protects 800K decision (8:1 ratio) │
└──────────────────────────────────────────────────────────┘
```

### Path 2: Commit to Upgrade NOW
```
┌──────────────────────────────────────────────────────────┐
│  INVEST IN IDUS IMMEDIATELY                              │
├──────────────────────────────────────────────────────────┤
│  Investment:   800K SEK                                  │
│  Activities:   • Version upgrade (restore SAP)           │
│                • Purchase reporting module               │
│                • Deploy mobile platform                  │
│                • Implement quick-logging                 │
│                                                          │
│  Bet:          Tom's estimates are accurate              │
│  Risk Level:   🔴 HIGH - Single-source unvalidated data │
│  Consequence:  5-10 year commitment if wrong             │
└──────────────────────────────────────────────────────────┘
```

### Path 3: Start CMMS Replacement RFP
```
┌──────────────────────────────────────────────────────────┐
│  REPLACE IDUS WITH MODERN ALTERNATIVE                    │
├──────────────────────────────────────────────────────────┤
│  Investment:   1.5-3M SEK (12-18 month project)          │
│  Activities:   • RFP for Planon, Ultimo, Fiix, eMaint    │
│                • Vendor selection and contracting        │
│                • Data migration and implementation       │
│                • Modern integration capabilities         │
│                                                          │
│  Bet:          Modern CMMS delivers 10x value            │
│  Risk Level:   🟡 MEDIUM - Migration risk, but known    │
│  Consequence:  Higher upfront cost, better long-term     │
└──────────────────────────────────────────────────────────┘
```

### ⚠️ Path 4: Do Nothing (NOT VIABLE)
```
Cost: SAP integration stays broken (1.55M/year minimum)
Risk: Technical debt compounds, forced emergency upgrade
Time: Problem doesn't age well - gets worse monthly
```

---

## 🎯 RECOMMENDED IMMEDIATE ACTIONS (This Month)

### ✅ Execute Without Further Study (LOW RISK)

**1. Agda/Visma Training Campaign**
```
Investment:  30-70K SEK
Savings:     75K SEK/year (validated)
Payback:     4-18 months
Risk:        LOW (confirmed waste, proven solution)
Action:      Approve budget, launch training program
Owner:       HR + Helena
```

**2. Cross-Training Program (Tom & Jan-Eric)**
```
Investment:  Low (internal labor)
Benefit:     Eliminates single points of failure
Risk:        NONE (pure risk reduction)
Action:      Assign backup super users, begin training
Timeline:    3-6 months to full competency
Owner:       IT + Department Managers
```

**3. Diagnose Excel Workflow Barrier**
```
Investment:  Negligible (2 weeks analysis)
Benefit:     Clarifies 688K/year opportunity
Risk:        NONE (information gathering only)
Action:      Audit permissions, pilot direct access
Timeline:    2 weeks diagnosis + 2 weeks pilot
Owner:       IT + Tom + Shift Leaders
```

### 🔴 Decide This Quarter (HIGH STAKES)

**4. Idus Decision Framework**
```
Deadline:    Month 3 (end Q1 2026)
Options:     Validation study OR immediate commitment
Decision:    Management must choose Path 1, 2, or 3
Consequence: Delaying past Q1 = continued 1.55M/year SAP waste
```

### 🟡 Plan for Q2-Q3 (MEDIUM PRIORITY)

**5. Flexite Integration Roadmap**
```
Priority 1:  Government integration (compliance risk)
Priority 2:  Analytics automation (efficiency gain)
Priority 3:  Idus integration (IF keeping Idus)
Investment:  100-150K SEK total
Timeline:    Q2-Q3 2026
```

**6. Complete Ascendo Assessment**
```
Due:         Next Wednesday (questionnaire collection)
Action:      Analyze responses, update portfolio view
Timeline:    Week 2 completion
```

---

## 📈 WHAT SUCCESS LOOKS LIKE

### Month 3 (End Q1 2026)
- ✅ Agda/Visma training launched, 50%+ employee adoption
- ✅ Tom backup super user identified and training started
- ✅ Jan-Eric backup H&S personnel identified and training started
- ✅ Excel workflow barrier diagnosed (root cause known)
- ✅ Idus decision made: Path 1, 2, or 3 selected
- ✅ Ascendo assessment complete, portfolio view updated

### Month 6 (End Q2 2026)
- ✅ Agda/Visma waste reduced by 50K+ SEK/year (if training successful)
- ✅ Backup super users functional (can cover absences)
- ✅ Excel workflow pilot complete (direct access tested)
- ✅ Idus path executing (validation study complete OR upgrade started OR RFP in progress)
- ✅ Flexite government integration planned/contracted

### Month 12 (End 2026)
- ✅ Idus situation resolved (upgraded OR replaced OR status quo with targeted fixes)
- ✅ Flexite integrations implemented (government + analytics)
- ✅ All systems have backup capacity (no single points of failure)
- ✅ Annual waste reduced by minimum 200K SEK (validated savings)

---

## 💰 FINANCIAL DECISION MATRIX

### Investment Scenarios - 12 Month View

```
╔════════════════════════════════════════════════════════════════╗
║  SCENARIO A: Minimal Investment (Status Quo + Quick Wins)     ║
╠════════════════════════════════════════════════════════════════╣
║  Year 1 Investment:      130-220K SEK                          ║
║    • Agda training:      30-70K                                ║
║    • Cross-training:     Negligible                            ║
║    • Excel diagnosis:    Negligible                            ║
║    • Flexite gov integ:  50-100K                               ║
║    • Ascendo TBD:        50K buffer                            ║
║                                                                ║
║  Year 1 Savings:         ~200K SEK                             ║
║    • Agda improvement:   50-75K                                ║
║    • Flexite efficiency: 30-60K                                ║
║    • Excel pilot (if success): 100K+                           ║
║                                                                ║
║  Idus Status:            Continues bleeding 1.55M+ SEK/year    ║
║  Risk Level:             🟡 MEDIUM - Kicks can, postpones big  ║
║                          decision                              ║
╚════════════════════════════════════════════════════════════════╝

╔════════════════════════════════════════════════════════════════╗
║  SCENARIO B: Validate Then Decide (RECOMMENDED)               ║
╠════════════════════════════════════════════════════════════════╣
║  Year 1 Investment:      230-320K SEK                          ║
║    • Quick wins:         130-220K (from Scenario A)            ║
║    • Idus validation:    100K                                  ║
║                                                                ║
║  Year 1 Savings:         ~200K SEK (same as Scenario A)        ║
║                                                                ║
║  Decision Gate:          Month 4 - Data-driven Idus choice     ║
║  Risk Level:             🟢 LOW - Protects 800K decision       ║
║                          (8:1 insurance ratio)                 ║
║                                                                ║
║  Year 2 Path:            Either upgrade (800K) OR replace      ║
║                          (1.5-3M) based on validation          ║
╚════════════════════════════════════════════════════════════════╝

╔════════════════════════════════════════════════════════════════╗
║  SCENARIO C: Commit to Idus Upgrade NOW                       ║
╠════════════════════════════════════════════════════════════════╣
║  Year 1 Investment:      1.03-1.12M SEK                        ║
║    • Quick wins:         130-220K (from Scenario A)            ║
║    • Idus upgrade:       800K                                  ║
║    • Contingency:        100K                                  ║
║                                                                ║
║  Year 1 Savings:         ~3.2M SEK (IF estimates accurate)     ║
║    • Quick wins:         200K                                  ║
║    • Idus improvements:  3M+ (claimed, unvalidated)            ║
║                                                                ║
║  Payback:                3-4 months (IF claims validate)       ║
║  Risk Level:             🔴 HIGH - Betting on single-source    ║
║                          unvalidated estimates                 ║
╚════════════════════════════════════════════════════════════════╝

╔════════════════════════════════════════════════════════════════╗
║  SCENARIO D: Replace Idus with Modern CMMS                    ║
╠════════════════════════════════════════════════════════════════╣
║  Year 1 Investment:      130-220K SEK (quick wins only)        ║
║  Year 2 Investment:      1.5-3M SEK (replacement project)      ║
║                                                                ║
║  Year 1-2 Savings:       Minimal (during migration)            ║
║  Year 3+ Savings:        Address root causes with modern       ║
║                          platform capabilities                 ║
║                                                                ║
║  Timeline:               12-18 months to go-live               ║
║  Risk Level:             🟡 MEDIUM - Migration risk but        ║
║                          eliminates technical debt             ║
╚════════════════════════════════════════════════════════════════╝
```

### Recommendation: **SCENARIO B**
- Lowest risk (protects major decision with data)
- Enables quick wins while studying complex decision
- 100K validation study has 8:1 risk reduction ratio
- Decision gate at Month 4 provides strategic flexibility

---

## 🚨 THE REAL RISKS (Not What You Think)

### ❌ WRONG: "Idus might fail and shut down operations"
**Reality:** Idus won't suddenly fail. It's been running for years. The risk is **chronic waste, not acute failure**.

### ❌ WRONG: "We need to fix all 15 Idus risks"
**Reality:** Many "risks" are just different views of the same problem (SAP integration). Focus on root causes, not symptom lists.

### ❌ WRONG: "We must validate everything before any action"
**Reality:** Quick wins (Agda, Excel diagnosis, cross-training) have validated ROI. Execute those NOW.

### ✅ RIGHT: "Making 800K decision on unvalidated data"
**This is the actual risk.** Not system failure - wrong strategic choice that compounds for 5-10 years.

### ✅ RIGHT: "Tom and Jan-Eric are single points of failure"
**Operational continuity risk.** If either is unavailable, critical business functions stop. This is addressable through training.

### ✅ RIGHT: "We don't know if Idus barriers are fixable"
**Excel workflow barrier might be unfixable system complexity.** If true, upgrade doesn't solve it. Must diagnose before investing.

---

## 📋 DECISION CHECKLIST FOR MANAGEMENT

### This Week
- [ ] Approve Agda/Visma training budget (30-70K SEK) - **YES/NO**
- [ ] Approve cross-training initiative - **YES/NO**
- [ ] Approve Excel workflow diagnosis - **YES/NO**
- [ ] Choose Idus path: Validation Study (Path 1) OR Immediate Upgrade (Path 2) OR RFP (Path 3) - **DECISION REQUIRED**

### Next Week
- [ ] Complete Ascendo assessment
- [ ] Update portfolio view with Ascendo data
- [ ] Begin execution on approved quick wins

### By Month 3
- [ ] Agda/Visma training showing adoption results
- [ ] Excel workflow barrier diagnosed (root cause known)
- [ ] Backup super users identified and training started
- [ ] Idus decision executed (study underway OR upgrade starting OR RFP launched)

### By Month 6
- [ ] Validation study complete (if Path 1 chosen) with final Idus recommendation
- [ ] First wave of savings realized (Agda improvements)
- [ ] Backup capacity functional (Tom/Jan-Eric coverage exists)

---

## 📞 WHO OWNS WHAT

**IT Leadership:**
- Idus decision execution (validation study OR upgrade OR RFP)
- Excel workflow diagnosis
- System integration oversight
- Technical resource allocation

**HR + Helena:**
- Agda/Visma training campaign
- Employee adoption tracking
- Self-service portal promotion

**Operations + Tom:**
- Cross-training backup super users
- Idus validation study participation (if Path 1)
- Excel workflow pilot testing

**H&S + Jan-Eric:**
- Flexite integration planning
- Backup H&S personnel training
- Government reporting automation

**Finance:**
- Budget approvals
- ROI tracking
- Investment scenario modeling

**Management:**
- **THIS WEEK:** Choose Idus path (1, 2, or 3)
- Strategic direction and priority setting
- Resource allocation decisions

---

## 💬 QUESTIONS MANAGEMENT MIGHT ASK

**Q: "Why can't we just fix Idus gradually without big investment?"**
A: SAP integration is broken and unfixable without version upgrade. Minimum viable fix = upgrade (800K). Can't fix "a little bit."

**Q: "What if we just accept the waste and do nothing?"**
A: 1.55M SEK/year minimum continues (SAP waste alone). Technical debt compounds - problem gets worse monthly, not stable.

**Q: "How confident are you in these numbers?"**
A: Agda/Visma (75K) = 🟢 HIGH confidence. Flexite (60-90K) = 🟢 HIGH confidence. Idus (4.73M) = 🔴 LOW confidence. That's why validation study exists.

**Q: "Can we validate Idus faster than 4 months?"**
A: Time-tracking study = 2-4 weeks. Market research = 3-4 weeks. Multi-user interviews = 2-3 weeks. Add synthesis and TCO modeling = 4 months is realistic minimum.

**Q: "What's the worst case if we choose wrong path for Idus?"**
A: Path 2 (upgrade now) worst case = 800K invested in platform that doesn't solve root causes, 5-10 year wrong commitment. Path 3 (replace) worst case = migration pain, 1.5-3M investment. Path 1 (validate) worst case = 100K spent, 4 months delayed action.

**Q: "Why not just ask Tom if his estimates are right?"**
A: Professional identity bias - Tom has 7+ years invested in Idus, naturally defends it. Need external validation and time-tracking data, not opinion.

**Q: "What happens to Idus if Tom leaves?"**
A: Currently? Crisis. No backup, knowledge loss, system administration stops. This is why cross-training is urgent regardless of Idus decision.

**Q: "Should we involve employees in Idus decision?"**
A: Yes - validation study includes technician interviews, production team input, occasional user perspectives. Single super user view is insufficient.

---

## 🎯 BOTTOM LINE

**The ONE decision that matters this week:**

```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║  CHOOSE YOUR IDUS PATH:                                       ║
║                                                               ║
║  [ ] Path 1: Validate First (100K, 4 months) ← RECOMMENDED   ║
║  [ ] Path 2: Upgrade Now (800K immediately)                   ║
║  [ ] Path 3: Replace (start RFP, 1.5-3M year 2)              ║
║                                                               ║
║  Deadline: End of Month 1 (this month)                        ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝
```

Everything else (Agda training, cross-training, Excel diagnosis) = straightforward execution.

**The question:** Do you bet 800K on unvalidated single-source estimates, or invest 100K to validate first?

---

**Next Review:** After Ascendo assessment (Week 2) and based on Idus path chosen

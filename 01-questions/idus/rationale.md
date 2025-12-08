# Idus (CMMS) Interview Questions - Rationale Guide
## Table Format - Question by Question

---

## Section 1: Opening & Overview

| Question | Rationale |
|----------|-----------|
| **What is your role, and how long have you been the super user for Idus?** | Establishes Tom's credibility and experience depth. Long tenure (3+ years) = deep knowledge, historical context, and reliable recommendations. Newer super users have fresh perspectives but limited context. Also reveals if maintenance is dedicated role (strategic) or add-on responsibility (tactical). High turnover in role suggests system or organizational problems. |
| **In your own words, what is Idus used for in our maintenance operations?** | Tests Tom's understanding of system scope and strategic purpose. Should mention: work orders, PM, asset tracking, inventory, reporting. Limited answer ("we log maintenance") suggests underutilization or knowledge gap. Comprehensive answer indicates full system understanding. Misalignment between Tom's view and actual purpose reveals training or communication issues. |
| **How many maintenance requests does the system handle per month? How many assets are tracked?** | Establishes scale for cost-per-request and cost-per-asset calculations. Low volume could mean excellent PM (good) or severe underreporting (bad). High volume could mean good reporting culture or equipment problems. Asset count determines coverage completeness. Industry benchmark: 400-1,500 SEK per asset per year for CMMS. Compare to actual cost to assess value. |

---

## Section 2: Business Value & Impact

| Question | Rationale |
|----------|-----------|
| **Does Idus help reduce equipment downtime or prevent failures?** | THE fundamental CMMS value question. Equipment downtime costs 50,000-200,000 SEK/hour. If Idus doesn't reduce downtime, it's not delivering core value. "Yes, we've reduced downtime 30-40%" = Excellent ROI. "Not really" = System failure. "Don't know" = Not measuring value (management problem). Even preventing one major failure per year can justify entire CMMS investment. |
| **What types of maintenance does Idus handle? What's the mix?** | Reveals maintenance maturity. Reactive (fix after breakdown) = Most expensive, immature. Preventive (scheduled before failure) = 3-5× cheaper, maturing. Predictive (data-driven) = Most efficient, advanced. Target ratio: 20% reactive / 80% preventive. If 70% reactive = High costs, Idus not being used strategically. Shift to preventive can save 1-2 million SEK annually. |
| **How well is preventive maintenance being tracked and executed? PM compliance rate?** | PM is THE highest value CMMS feature. Compliance should be 90%+. Low compliance (<70%) means: PM schedules exist but aren't followed (process failure), or equipment will fail prematurely (cost consequence), or Idus isn't enabling what it should (system failure). If PM frequently skipped due to "production pressure" = Cultural problem requiring management intervention. |
| **On a scale of 1-10, how critical is this system? Why?** | Quick comparison metric but reasoning matters most. For production facility, CMMS should rate 7-9. Rating 9-10 with clear reasoning (processes rely on it, no alternative, prevents downtime) = Justified investment. Rating 5-6 = Question value or fix utilization. Rating 3-4 = System has failed. The "why" reveals dependencies, value drivers, and credibility of rating. |
| **What would happen if Idus was unavailable for a week?** | Tests true criticality vs. perceived importance. "Operations would suffer significantly" = Mission critical, justifies investment in redundancy. "We'd manage with whiteboards/Excel" = Important but not critical, backup exists (good planning). "Wouldn't affect us much" = Low value, question investment. Also reveals business continuity preparedness. Having backup process is smart, not a sign system isn't needed. |

---

## Section 3: Usage & Adoption

| Question | Rationale |
|----------|-----------|
| **How frequently do you use Idus?** | Usage frequency indicates system integration into workflows. Daily use = Core to operations. Weekly = Regular but not essential. Monthly = Limited engagement or highly automated (need context). Infrequent use by super user suggests either excellent automation or poor utilization. Compare Tom's frequency to typical user frequency for perspective. |
| **Walk me through a typical maintenance workflow in Idus.** | Reveals actual system usage vs. intended design. Ideal flow: Request → Assign → Parts → Execute → Complete → Document. Gaps in workflow indicate process issues or missing functionality. Extensive workarounds suggest system limitations. Manual steps that should be automated = Efficiency waste. Listen for pain points in workflow description. |
| **Do people actually use Idus to submit requests, or do they still call/email you?** | **THE CRITICAL ADOPTION QUESTION.** If people bypass Idus (call/email instead), system has FAILED. Phone/email creates: no documentation trail, no searchable history, can't analyze patterns, can't track completion, no audit trail. "Mostly call me" = System too complicated, not user-friendly, or cultural resistance. This means you're paying for software but operating manually. Adoption failure is #1 CMMS implementation problem. |
| **What % of maintenance work is logged in Idus vs. handled informally?** | Measures true adoption. Should be 90%+ logged. If only 60% logged = 40% of maintenance is invisible to management, can't track costs, can't identify problem equipment, incomplete history damages resale value. Informal maintenance = "tribal knowledge" that leaves when people leave. Low logging rate indicates: system too complex, cultural issues, Tom is bottleneck, or unclear processes. |
| **Do production teams submit requests through Idus, or do they bypass it?** | Production team adoption is critical - they're closest to equipment and spot problems first. If they bypass system, you lose: early problem detection, operator knowledge, complete incident history. Why they bypass: don't know system exists, no access, too complicated, or don't see value. Bypass rate >30% = Serious adoption problem requiring attention. |
| **Can technicians easily access Idus from production floor? Mobile access?** | Technicians work in the field, not at desks. If no mobile access or it doesn't work well = They write notes on paper and enter later (inefficiency and data loss), or don't document at all (invisible work). Modern CMMS must be mobile-first. QR codes on equipment for instant access = Best practice. Poor mobile access is top reason for adoption failure in maintenance. |

---

## Section 4: User Experience & Pain Points

| Question | Rationale |
|----------|-----------|
| **What do maintenance technicians appreciate most about Idus?** | Identifies strengths to preserve. Common: easy work order tracking, equipment history at fingertips, automated PM schedules, mobile access. These features must be maintained in any system change. Also reveals what users value - might differ from management assumptions. If Tom struggles to name positives = Poor user satisfaction, system may be wrong fit. |
| **What are your top 3 frustrations?** | Forces prioritization of problems. Every system has issues - need to know which actually impact productivity. Top 3 become: vendor negotiation points, replacement evaluation criteria, or improvement priorities. Common frustrations: slow performance, poor search, complicated workflows, inadequate mobile. Frustrations = Time waste = Money waste. Quantify impact: "slow system wastes 10 min/day × 5 technicians = 200 hours/year = 100,000 SEK." |
| **Can technicians easily access equipment history and documentation?** | Equipment history speeds troubleshooting and repairs. If technician can see "this motor fails every 6 months" they can address root cause. If history is hard to access = Longer repair times = More downtime = Higher costs. Documentation (manuals, specs) accessibility prevents: ordering wrong parts, incorrect repairs, safety issues. If difficult = Technicians waste time searching or work without proper information. |
| **How complete is the asset/equipment database in Idus?** | Complete asset database = Complete insights and informed decisions. Incomplete = Blind spots. Should include ALL critical assets with: specs, location, maintenance history, parts lists, manuals. If only 60% of assets tracked = Can't optimize maintenance spend, can't identify problem equipment, can't make replacement decisions. Incomplete database often means: initial setup rushed, no ongoing governance, or system too complex to maintain. |

---

## Section 5: Integration & Efficiency

| Question | Rationale |
|----------|-----------|
| **Does Idus integrate with other systems? Do you manually transfer data?** | Integration multiplies CMMS value. Production system integration = Auto-trigger maintenance based on runtime hours. Inventory integration = Real-time parts availability. Procurement integration = Auto-order parts. Manual data transfer = Time waste, errors, delays. If Tom manually exports/imports data = Paying for integration but not getting it. Example: 5 hours/month manual work × 12 months = 60 hours/year = 30,000 SEK wasted. Poor integration is major reason to replace systems. |
| **Can you generate reports on equipment performance and maintenance costs?** | Reporting enables optimization. Should easily answer: Which equipment costs most to maintain? Are costs increasing or decreasing? Which assets should be replaced vs. repaired? What's our PM compliance trend? If reporting is difficult = Data exists but isn't actionable. This prevents: cost optimization, budget forecasting, strategic planning. "Takes me 8 hours to build monthly report" = 96 hours/year = 50,000 SEK + opportunity cost of not having timely data. |

---

## Section 6: Support & Data Quality

| Question | Rationale |
|----------|-----------|
| **How often do you engage IT support for Idus issues?** | IT support frequency indicates system stability and usability. Daily support = Major problems with system or users. Monthly = Typical. Rarely = Very stable or Tom doesn't bother reporting issues. High support burden = Hidden cost. Calculate: 10 IT hours/month × 800 SEK/hour = 96,000 SEK/year in support costs beyond license. Also indicates if system is appropriate for user skill level. |
| **How confident are you in data accuracy in Idus?** | Data quality determines decision quality. Garbage in = Garbage out. If Tom doesn't trust data = Won't use reports, makes decisions based on gut feel, can't demonstrate value. Common data quality issues: duplicate records, incomplete information, outdated data, inconsistent entry. Low confidence indicates: poor data governance, inadequate validation rules, lack of training, or system doesn't enforce standards. Without good data, CMMS provides false security - looks like you're managing maintenance but actually operating blind. |

---

## Section 7: Future Outlook

| Question | Rationale |
|----------|-----------|
| **Is Idus meeting current maintenance management needs?** | Overall satisfaction assessment. "Yes, fully" = System is working well. "Partially" = Gaps exist that should be investigated. "No" = Serious problems requiring action. Follow up on "partially/no" with: What specific needs aren't being met? This reveals whether issues are: system limitations (might need replacement), configuration problems (can be fixed), process issues (not system's fault), or training gaps (need education). |
| **What capabilities do you wish Idus had?** | Innovation opportunities and competitive analysis. Common missing features: Better mobile app, IoT sensor integration, AI-powered predictive maintenance, better analytics, automated scheduling. These become: Vendor negotiation points ("we need feature X or we'll switch"), replacement evaluation criteria, or custom development opportunities. Also reveals Tom's awareness of industry trends. If he's researching competitors, he's frustrated. |
| **If we were to replace or upgrade, what would be essential to keep?** | Identifies non-negotiable features and nice-to-haves. Essential features must be in any replacement system. "Could let go" features were probably vendor-pushed during sales but don't deliver value. This question helps: Build replacement requirements, Negotiate with current vendor (threaten to leave, drop unused features), Understand what actually matters vs. what sounds good in demos. |
| **Would you recommend: invest more, maintain, or explore alternatives?** | THE ultimate question. Tom's daily experience makes his recommendation highly valuable. "Invest more" = System working well, expand use. "Maintain" = Acceptable, no changes needed. "Explore alternatives" = Serious problems warrant investigation. His reasoning reveals: Satisfaction level, awareness of alternatives, pain point severity. If he's passively accepting vs. actively recommending = Different implications. Management should heavily weight this answer in decision-making. |
| **Any other thoughts about Idus?** | Open-ended catch-all for issues not covered. Often reveals: Cultural issues, relationship with vendor, change management concerns, politics, upcoming changes. Listen for hesitations or lowered voice (sensitive topics). Statements like "between you and me..." often contain most valuable insights. This is where Tom shares what he didn't want to say on record earlier. |

---

## Key Red Flags to Watch For

| Red Flag | Implication |
|----------|-------------|
| People bypass system (call/email instead) | System has FAILED - adoption crisis |
| <70% of work logged | Incomplete data, can't manage what you can't see |
| PM compliance <70% | Equipment will fail prematurely, missing core CMMS value |
| >50% reactive maintenance | Expensive approach, not using preventive features |
| No mobile access or it doesn't work | Technicians can't use it effectively |
| Tom doesn't know if downtime reduced | Not measuring value, can't justify investment |
| Manual data transfer between systems | Integration failure, wasted time |
| Incomplete asset database | Can't make informed decisions |
| Low data quality confidence | Garbage in, garbage out - decisions based on bad data |
| Tom recommends exploring alternatives | Serious dissatisfaction requiring investigation |

---

## Key Green Flags to Watch For

| Green Flag | Implication |
|----------|-------------|
| 90%+ of work logged in system | Strong adoption, complete data |
| PM compliance >90% | Preventive maintenance working, core value delivered |
| Measurable downtime reduction | Clear ROI, investment justified |
| Strong production team adoption | Early problem detection, complete picture |
| Good mobile access and usage | Technicians can work efficiently |
| Automatic integrations working | Efficiency multiplier, reduced manual work |
| Complete asset database | Informed decision-making possible |
| Tom confidently recommends continuing | System meeting needs, investment justified |

---

**Document Version:** 1.0  
**Format:** Table-based Rationale  
**Created:** December 2025  
**Purpose:** Quick reference guide for understanding interview question strategic value

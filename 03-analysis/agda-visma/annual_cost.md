# Agda PS - Annual Waste Cost Analysis

## Calculation Methodology

**Assumptions:**
- 12 payroll cycles per year (monthly)
- Average HR/payroll hourly rate: 400 SEK/hour
- 52 working weeks per year

**Important Context:** 
Some manual processes may represent intentional risk management controls rather than pure "waste." This analysis distinguishes between confirmed waste and costs that require validation with Ekonomi team.

---

## Confirmed Waste Costs

### 1. Shift Calculation Manual Review (Temporary)
**Time:** 1-2 hours per payroll cycle × 12 cycles = 12-24 hours/year
**Cost:** 4,800-9,600 SEK/year
**Status:** Clear waste - temporary configuration issue

### 2. Paper Leave Requests & Manual Entry
**Time:** 2-4 hours per week × 52 weeks = 104-208 hours/year
**Cost:** 41,600-83,200 SEK/year
**Status:** Clear waste - underutilization of available self-service features

### 3. Incomplete Time Data Follow-up
**Time:** ~0.5 hours per cycle × 12 cycles = 6 hours/year
**Cost:** 2,400 SEK/year
**Status:** Clear waste - preventable through better validation

### 4. Manual Pension Data Generation
**Time:** ~0.5 hours per cycle × 12 cycles = 6 hours/year
**Cost:** 2,400 SEK/year
**Status:** Likely waste - low priority automation opportunity

**Confirmed Waste Subtotal:** 53,200-98,600 SEK/year

---

## Costs Requiring Validation (Potential Waste vs. Risk Controls)

### 5. Manual Banking Data Transfer
**Time:** 1-2 hours per payroll cycle × 12 cycles = 12-24 hours/year
**Cost:** 4,800-9,600 SEK/year

**Status:** **REQUIRES EKONOMI TEAM VALIDATION**
- May be intentional risk control for validation before salary payments
- Ekonomi team preference reflects risk-mitigation approach
- Provides final validation checkpoint before irreversible bank transfers
- **If intentional control:** Not waste, but cost of risk management
- **If automation desired:** Could use semi-automated approach with approval gates

**Classification:** Uncertain - requires stakeholder input

### 6. Manual Accounting Data Transfer  
**Time:** 1-2 hours per payroll cycle × 12 cycles = 12-24 hours/year
**Cost:** 4,800-9,600 SEK/year

**Status:** **REQUIRES EKONOMI TEAM VALIDATION**
- Similar risk management considerations as banking
- May be intentional control for validation before accounting entries
- Provides flexibility in timing and reconciliation opportunity
- **If intentional control:** Not waste, but cost of risk management
- **If automation desired:** Could use semi-automated approach

**Classification:** Uncertain - requires stakeholder input

**Uncertain Costs Subtotal:** 9,600-19,200 SEK/year

---

## Total Annual Waste Cost

### Conservative Estimate (Confirmed Waste Only)
**Confirmed Waste:** 53,200-98,600 SEK/year
**Mid-Range:** ~**76,000 SEK/year**

### Maximum Estimate (If All Manual Processes Are Waste)
**Total Including Uncertain Items:** 62,800-117,800 SEK/year
**Mid-Range:** ~**90,000 SEK/year**

---

## Waste Cost Breakdown by Classification

### High-Confidence Waste (Actionable Now)
- **Paper leave requests:** 41,600-83,200 SEK/year (66-84% of confirmed waste)
- **Shift calculation:** 4,800-9,600 SEK/year (8-10%)
- **Incomplete data:** 2,400 SEK/year (2-3%)
- **Pension data:** 2,400 SEK/year (2-3%)

**Subtotal:** 53,200-98,600 SEK/year

### Uncertain Classification (Requires Validation)
- **Banking transfer:** 4,800-9,600 SEK/year
- **Accounting transfer:** 4,800-9,600 SEK/year

**Subtotal:** 9,600-19,200 SEK/year
**Note:** These may be intentional risk controls, not waste

---

## Key Insights

1. **Self-service adoption is the largest confirmed waste** - 66-84% of confirmed waste comes from employees not using available features

2. **Integration "gaps" may be risk controls** - What appeared as waste may actually be deliberate validation checkpoints valued by Ekonomi team

3. **Most confirmed waste is addressable** - Self-service adoption and shift validation can be resolved with known solutions

4. **Need stakeholder validation** - Cannot accurately classify 15-20% of potential waste without Ekonomi team input

5. **Waste is relatively low** - Even at maximum estimate (90K SEK/year), waste is manageable for mission-critical payroll system

---

## ROI Analysis - Revised

### Addressable Now (High Confidence)

**Self-Service Adoption Improvement:**
- Potential savings: 41,600-83,200 SEK/year
- Implementation cost: Low (training and change management)
- Payback: Immediate
- **ROI: Very High**

**Shift Calculation Automation:**
- Potential savings: 4,800-9,600 SEK/year
- Implementation cost: Minimal (Visma support included)
- Payback: Immediate
- **ROI: Very High**

**Combined Confirmed Waste Elimination:** 46,400-92,800 SEK/year

### Requires Validation

**Banking/Accounting Integration:**
- Potential savings: 9,600-19,200 SEK/year (if validated as waste)
- **OR** Cost of risk control: 9,600-19,200 SEK/year (if intentional)
- Implementation cost: Unknown (integration setup)
- **ROI: Unknown until Ekonomi team consultation**

**Critical Question:** Is the benefit of automation greater than the value of manual validation control?

---

## Risk Management Perspective

### If Manual Processes Are Risk Controls

**Value of Manual Control:**
- Final validation before irreversible transactions
- Catch errors before financial impact
- Clear accountability and audit trail
- Flexibility in timing
- Risk mitigation for sensitive data

**Cost of Manual Control:** 9,600-19,200 SEK/year

**Assessment:** This may be **appropriate cost for risk management** rather than waste, especially for:
- Salary payments (high employee impact)
- Banking transactions (financial risk)
- Accounting entries (audit and compliance)

### Alternative: Semi-Automated with Controls

Could achieve best of both worlds:
- Automated data generation (time savings)
- Manual approval gates (maintains control)
- Validation checkpoints preserved
- Estimated savings: 50-70% of manual effort while keeping controls

---

## Revised Prioritization

### Priority 1: Clear High-ROI Opportunities
1. **Self-service adoption** - 41,600-83,200 SEK/year, low implementation cost
2. **Shift calculation** - 4,800-9,600 SEK/year, minimal cost

**Total Addressable:** 46,400-92,800 SEK/year

### Priority 2: Validate Before Acting
3. **Banking/accounting processes** - Interview Ekonomi team first
   - If waste: Consider semi-automated approach
   - If risk control: Maintain current process or optimize handoffs
   - **Do not assume these are waste without stakeholder validation**

### Priority 3: Low-Impact Items
4. **Pension data** - 2,400 SEK/year, low priority
5. **Data validation** - 2,400 SEK/year, low priority

---

## Critical Next Step

**Interview Ekonomi Team** to understand:
1. Is manual banking/accounting transfer intentional risk control or inefficiency?
2. What is their validation process and requirements?
3. Would semi-automated approach with approval gates be acceptable?
4. What is the true cost/burden on their workflow?
5. What risks concern them about full automation?

**Only after this consultation** can we accurately calculate total waste and determine appropriate automation strategy.

---

## Summary

**Confirmed Waste Cost:** 53,200-98,600 SEK/year (mid-range: ~76,000 SEK)
**Uncertain Classification:** 9,600-19,200 SEK/year (may be intentional controls)
**Maximum Possible Waste:** 62,800-117,800 SEK/year (mid-range: ~90,000 SEK)

**Key Distinction:** Not all manual processes are waste. Some represent deliberate risk management controls that provide value through validation and error prevention. Proper waste cost analysis requires understanding stakeholder intent and process purpose.

---

**Document Status:** Draft - Requires Ekonomi Team Input
**Last Updated:** December 2025
**Critical Dependency:** Ekonomi team interview to validate classification of manual processes

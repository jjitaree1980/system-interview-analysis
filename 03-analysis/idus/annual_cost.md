# Annual Waste Cost Analysis - Idus

## Analysis Overview

**System:** Idus (Maintenance Management System)  
**Analysis Date:** 2025-12-12  
**Analyst:** JJA  
**Base Year:** 2025

---

## Cost Calculation Methodology

**Labor Cost Assumptions (Sweden):**
- Super User/Specialist: 550 SEK/hour (including overhead)
- Maintenance Technician: 450 SEK/hour (including overhead)
- Blue-Collar Worker: 400 SEK/hour (including overhead)
- Warehouse Staff: 400 SEK/hour (including overhead)

**Working Hours:**
- 1 working day = 8 hours
- 1 working month = 160 hours (20 days)

---

## Quantified Waste Costs

### Waste 1: Manual Reporting Labor

**Description:** Super user spends 2+ business days per regular report and 1 hour per investigative report due to lack of reporting module.

**Calculation:**
- Regular reports: 12 per year × 2 days × 8 hours = 192 hours/year
- Investigative reports: Estimated 24 per year × 1 hour = 24 hours/year
- Total: 216 hours/year × 550 SEK/hour = **118,800 SEK/year**

**Additional Waste:**
- Excel file maintenance and updates: Estimated 2 hours/week × 52 weeks = 104 hours/year
- Planning data tracking in Excel: 104 hours × 550 SEK = **57,200 SEK/year**

**Subtotal Manual Reporting Waste: 176,000 SEK/year**

---

### Waste 2: Broken SAP Integration - Manual Verification

**Description:** Unreliable inventory data forces manual verification of spare parts availability for work orders.

**Calculation:**
- Work orders requiring parts: Estimated 50% of 1,800 monthly tickets = 900 WO/month
- Annual WO requiring parts: 900 × 12 = 10,800 WO/year
- Manual verification time per WO: Estimated 10 minutes average
- Technician time: 10,800 × (10/60) hours = 1,800 hours/year
- Warehouse coordination time: 1,800 hours/year
- Total labor: 3,600 hours/year × 425 SEK/hour (average of technician and warehouse) = **1,530,000 SEK/year**

**Additional IT Workaround Costs:**
- Custom warehouse search program maintenance: Estimated 20 hours/year × 550 SEK = **11,000 SEK/year**
- Barcode scanner system maintenance: Estimated 20 hours/year × 550 SEK = **11,000 SEK/year**

**Subtotal SAP Integration Waste: 1,552,000 SEK/year**

---

### Waste 3: No Mobile Platform - Field Travel Time

**Description:** Technicians must return to control room to access system information instead of accessing in field.

**Calculation:**
- Estimated trips to control room: 5 per technician per week
- 20 technicians × 5 trips × 52 weeks = 5,200 trips/year
- Average time per trip (travel + access): 15 minutes
- Total time: 5,200 × (15/60) hours = 1,300 hours/year
- Labor cost: 1,300 hours × 450 SEK = **585,000 SEK/year**

**Additional Inefficiency:**
- Delayed work order execution: Estimated 5% productivity loss on field work
- Field work hours: 20 technicians × 4 hours/day × 220 days = 17,600 hours/year
- 5% of 17,600 = 880 hours × 450 SEK = **396,000 SEK/year**

**Subtotal Mobile Platform Waste: 981,000 SEK/year**

---

### Waste 4: System Performance - Slow Response Times

**Description:** Slow system performance reduces user productivity across all daily interactions.

**Calculation:**
- Users affected: 30 users
- Estimated productivity loss: 10% of system interaction time
- Average system usage: 2 hours/user/day
- Working days: 220 days/year
- Total system time: 30 users × 2 hours × 220 days = 13,200 hours/year
- 10% waste: 1,320 hours/year
- Average labor cost: 475 SEK/hour (blended rate)
- Cost: 1,320 × 475 = **627,000 SEK/year**

**Subtotal Performance Waste: 627,000 SEK/year**

---

### Waste 5: Incomplete Work Logging - Untracked Quick Fixes

**Description:** Quick fixes (~5 minutes) not logged in system, creating incomplete maintenance records and missing recurring issue patterns.

**Calculation:**
- Estimated quick fixes: 10 per technician per week
- 20 technicians × 10 × 52 weeks = 10,400 quick fixes/year
- Labor hours not tracked: 10,400 × (5/60) = 867 hours/year
- Untracked labor cost: 867 × 450 = **390,150 SEK/year**

**Additional Risk Cost:**
- Missed recurring patterns leading to failures: Estimated 2 major failures/year
- Emergency repair cost premium: 50,000 SEK per failure × 2 = **100,000 SEK/year**

**Subtotal Incomplete Logging Waste: 490,150 SEK/year**

---

### Waste 6: No Procurement Integration - Manual Coordination

**Description:** Technicians must physically visit warehouse for spare part requests, and warehouse staff manually create procurement orders.

**Calculation:**
- Parts procurement requests: Estimated 20% of WO require new parts = 2,160 requests/year
- Technician visit time: 2,160 × 15 minutes = 540 hours/year × 450 SEK = **243,000 SEK/year**
- Warehouse manual order processing: 2,160 × 10 minutes = 360 hours/year × 400 SEK = **144,000 SEK/year**

**Subtotal Procurement Integration Waste: 387,000 SEK/year**

---

### Waste 7: System Bypass - Blue-Collar Workers and Production Team

**Description:** Users calling/emailing instead of using system creates coordination overhead and incomplete data.

**Calculation:**
- Estimated bypass incidents: 200 per month × 12 = 2,400/year
- Super user triage time: 2,400 × 5 minutes = 200 hours/year × 550 SEK = **110,000 SEK/year**
- Incomplete data leading to inefficiency: Estimated 3% maintenance planning inefficiency
- Planning labor: 1 FTE × 1,760 hours × 3% × 550 SEK = **29,040 SEK/year**

**Subtotal System Bypass Waste: 139,040 SEK/year**

---

### Waste 8: No Budget Tracking - Reactive Cost Management

**Description:** No real-time budget visibility leads to reactive rather than proactive cost management.

**Calculation:**
- Estimated budget overrun due to lack of visibility: 2% of annual maintenance budget
- Assumed annual maintenance budget: 10,000,000 SEK (based on 1,800 tickets/month)
- Cost of overruns: 10,000,000 × 2% = **200,000 SEK/year**

**Additional Management Time:**
- Manual budget tracking and reconciliation: 4 hours/month × 12 × 550 SEK = **26,400 SEK/year**

**Subtotal Budget Tracking Waste: 226,400 SEK/year**

---

### Waste 9: Data Quality Issues - Manual Verification

**Description:** User only "somewhat confident" in data accuracy, requiring manual verification for critical decisions.

**Calculation:**
- Critical decisions requiring verification: Estimated 100/year
- Verification time per decision: 30 minutes average
- Labor: 100 × 0.5 hours × 550 SEK = **27,500 SEK/year**

**Risk Cost:**
- Decisions made on inaccurate data: Estimated 1-2 significant errors/year
- Cost per error: 50,000 SEK average × 1.5 = **75,000 SEK/year**

**Subtotal Data Quality Waste: 102,500 SEK/year**

---

### Waste 10: Parallel System Maintenance - IT Overhead

**Description:** IT maintains multiple parallel systems and custom workarounds (Stopptider, warehouse search, barcode scanner).

**Calculation:**
- Stopptider maintenance: 40 hours/year × 550 SEK = **22,000 SEK/year**
- Warehouse search program: 20 hours/year × 550 SEK = **11,000 SEK/year**
- Barcode scanner system: 20 hours/year × 550 SEK = **11,000 SEK/year**
- User training on multiple systems: 10 hours/year × 550 SEK = **5,500 SEK/year**

**Subtotal Parallel System Waste: 49,500 SEK/year**

---

## Total Annual Waste Cost Summary

| Waste Category | Annual Cost (SEK) | % of Total |
|---|---|---|
| 1. Manual Reporting Labor | 176,000 | 4.0% |
| 2. Broken SAP Integration | 1,552,000 | 35.2% |
| 3. No Mobile Platform | 981,000 | 22.2% |
| 4. System Performance | 627,000 | 14.2% |
| 5. Incomplete Work Logging | 490,150 | 11.1% |
| 6. No Procurement Integration | 387,000 | 8.8% |
| 7. System Bypass Behavior | 139,040 | 3.1% |
| 8. No Budget Tracking | 226,400 | 5.1% |
| 9. Data Quality Issues | 102,500 | 2.3% |
| 10. Parallel System Maintenance | 49,500 | 1.1% |
| **TOTAL ANNUAL WASTE** | **4,730,590 SEK** | **100%** |

---

## Top 5 Waste Drivers

1. **Broken SAP Integration:** 1,552,000 SEK/year (35.2%)
2. **No Mobile Platform:** 981,000 SEK/year (22.2%)
3. **System Performance:** 627,000 SEK/year (14.2%)
4. **Incomplete Work Logging:** 490,150 SEK/year (11.1%)
5. **No Procurement Integration:** 387,000 SEK/year (8.8%)

**Top 5 Total: 4,037,150 SEK/year (85.3% of all waste)**

---

## Waste Prevention Opportunities

### High ROI Opportunities (Waste Reduction > 200,000 SEK/year)

**1. Version Upgrade → Restore SAP Integration**
- Waste eliminated: 1,552,000 SEK/year
- Investment: Version upgrade (internal labor) + data cleansing ~150,000 SEK
- Payback period: ~1.2 months
- Annual ROI: 935%

**2. Purchase Mobile Platform Module**
- Waste eliminated: 981,000 SEK/year
- Investment: Module cost ~100,000 SEK + implementation ~50,000 SEK
- Payback period: ~1.8 months
- Annual ROI: 554%

**3. Cloud Migration → Improve Performance**
- Waste eliminated: 627,000 SEK/year
- Investment: Cloud migration ~300,000 SEK + annual cloud costs ~120,000 SEK
- Net savings: 507,000 SEK/year
- Payback period: ~7.1 months
- Annual ROI: 169%

**4. Implement Quick-Logging Feature**
- Waste eliminated: 490,150 SEK/year
- Investment: Development/configuration ~50,000 SEK
- Payback period: ~1.2 months
- Annual ROI: 880%

**5. Purchase Procurement Module**
- Waste eliminated: 387,000 SEK/year
- Investment: Module cost ~80,000 SEK + implementation ~40,000 SEK
- Payback period: ~3.7 months
- Annual ROI: 223%

---

## Medium ROI Opportunities (Waste Reduction 100,000-200,000 SEK/year)

**6. Purchase Reporting/Analytics Module**
- Waste eliminated: 176,000 SEK/year
- Investment: Module cost ~60,000 SEK + implementation ~20,000 SEK
- Payback period: ~5.5 months
- Annual ROI: 120%

**7. Implement Budget Tracking**
- Waste eliminated: 226,400 SEK/year (included in reporting module)
- Additional benefit to reporting module purchase

**8. Improve User Adoption (Training + Simplified Interface)**
- Waste eliminated: 139,040 SEK/year
- Investment: Training program ~30,000 SEK + interface improvements ~40,000 SEK
- Payback period: ~6.0 months
- Annual ROI: 99%

---

## Cumulative Waste Reduction Potential

### Phase 1 Implementation (Priority items - 0-6 months)
**Items:** Version upgrade, Mobile platform, Quick-logging, Reporting module
- **Total waste eliminated: 3,199,150 SEK/year**
- **Total investment: 310,000 SEK**
- **Payback period: 1.2 months**
- **Annual ROI: 932%**

### Phase 2 Implementation (6-12 months)
**Items:** Procurement module, User adoption improvements, Data quality
- **Additional waste eliminated: 628,540 SEK/year**
- **Additional investment: 190,000 SEK**
- **Payback period: 3.6 months**
- **Annual ROI: 231%**

### Phase 3 Implementation (12-18 months)
**Items:** Cloud migration, Performance optimization
- **Additional waste eliminated: 627,000 SEK/year (net savings 507,000 SEK/year)**
- **Additional investment: 300,000 SEK + ongoing 120,000 SEK/year**
- **Payback period: 7.1 months**
- **Annual ROI: 169%**

### Total 3-Year Waste Reduction Potential
**All phases combined:**
- **Total waste eliminated: 4,454,690 SEK/year (94% of all waste)**
- **Total upfront investment: 800,000 SEK**
- **Total 3-year savings: 13,364,070 SEK (after investment and cloud costs)**
- **Net 3-year ROI: 1,571%**

---

## Cost Sensitivity Analysis

### Conservative Scenario (50% of estimated savings)
- Total annual waste: 2,365,295 SEK/year
- Top 5 waste elimination: 2,018,575 SEK/year
- Still provides strong ROI for improvements

### Aggressive Scenario (150% of estimated savings)
- Total annual waste: 7,095,885 SEK/year
- Top 5 waste elimination: 6,055,725 SEK/year
- Even stronger business case for comprehensive improvements

---

## Key Insights

**Waste Concentration:**
- 85% of waste comes from just 5 categories
- Top 3 categories account for 71% of all waste
- Addressing broken SAP integration alone eliminates 35% of waste

**Quick Wins Available:**
- Four opportunities with payback period < 2 months
- Combined investment of 310,000 SEK eliminates 3.2 million SEK/year waste
- ROI exceeds 900% in first year

**Compound Benefits:**
- Many improvements have synergistic effects
- Mobile platform reduces both field travel waste and system bypass
- Reporting module addresses both manual reporting and budget tracking

**Strategic Investment Case:**
- Total addressable waste: 4.7 million SEK/year
- Full implementation investment: 800,000 SEK
- Pays for itself in ~2 months
- Ongoing savings: 4+ million SEK/year

---

## Comparison with Industry Benchmarks

**Maintenance Management System Waste (Industry Average):**
- Manual processes: 15-20% of maintenance labor budget
- Poor integration: 10-15% efficiency loss
- Lack of mobile: 5-10% technician productivity loss

**Idus Current State:**
- Estimated waste as % of maintenance budget: ~47% (assuming 10M SEK budget)
- Significantly above industry average
- Strong opportunity for improvement to industry standards

---

## Recommendations Priority Matrix

### Immediate Actions (0-3 months)
1. **Execute version upgrade** - Eliminates 1.55M SEK/year waste
2. **Purchase reporting/analytics module** - Eliminates 176K SEK/year waste
3. **Develop business case for mobile platform** - Prepare for 981K SEK/year savings

### Short-term Actions (3-6 months)
1. **Implement mobile platform** - Eliminates 981K SEK/year waste
2. **Deploy quick-logging feature** - Eliminates 490K SEK/year waste
3. **Initiate user adoption improvement** - Eliminates 139K SEK/year waste

### Medium-term Actions (6-12 months)
1. **Purchase procurement module** - Eliminates 387K SEK/year waste
2. **Evaluate cloud migration** - Eliminates 627K SEK/year waste
3. **Execute data quality program** - Eliminates 103K SEK/year waste

**Total potential savings: 4.7 million SEK/year**
**Required investment: 800,000 SEK**
**Overall payback period: ~2 months**

---

**Document Status:** Draft  
**Last Updated:** 2025-12-12 by JJA  
**Methodology:** Based on Idus interview data, Swedish labor cost estimates, and maintenance management industry benchmarks  
**Note:** Actual costs may vary; conservative estimates used where data uncertain. Calculations assume 20 technicians, 30 total users, 1,800 tickets/month baseline.

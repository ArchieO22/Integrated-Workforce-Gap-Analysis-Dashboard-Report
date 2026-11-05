# GlobalTech Workforce Gap Analysis & Power BI Analytics — Capstone Portfolio

## Executive Summary & Capstone Overview
This capstone portfolio project presents a complete People Analytics & Financial Decision-Support System for GlobalTech Financial Services.

### Key Capstone Results:
- **Total Headcount Shortfall**: +401 Net FTE Gap across 6 critical technical roles by Year 3 (364 baseline → 765 target FTEs).
- **Board Financial Authorization**: $46.10M Allocated Spend + $5.0M Contingency Reserve, preserving a $3.90M Safety Buffer under the $50.0M Board Ceiling.
- **CHRO Internal Mobility Mandate**: Achieved 41.6% Internal Mobility (167 internal conversions), exceeding the 40% strategic threshold and saving ~$14.5M in recruiting fees.
- **Turnover Exposure Mitigation**: Managed $22.19M 3-Year Attrition Exposure via targeted $4.10M retention pools.
- **Power BI Implementation**: Star Schema data model, 3 Dimension & 3 Fact tables, and active 1:* relationships.

---

## Business Case Scenario & Strategic Mandate
GlobalTech Financial Services is 18 months into a 36-month Digital Transformation Program (DTP). While technology delivery is progressing on schedule, human capital capability development is severely lagging.

### Governance Rules & Constraints:
1. **$50.0M Board Budget Ceiling**
2. **40% Internal Mobility Target** (Reskilling traditional advisors and IT personnel)
3. **Q4 2024 Audit Deadline** for Cybersecurity Specialists

---

## Power BI Technical Implementation & Star Schema Architecture

### Data Model Structure:
- **Dimension Tables**: `dim_rolesegment`, `dim_skill_domain`, `dim_horizon`
- **Fact Tables**: `fact_demand_forecast`, `fact_current_skills`, `fact_attrition_risk`
- **Relationships**: Active 1-to-many (1:*) relationships. Bidirectional cross-filtering between `dim_rolesegment` and `fact_attrition_risk` enables Risk Rating slicers to filter upstream across all 4 visuals.

---

## Visual Dashboard Overview
- **Visual 1 (Demand vs. Supply Capacity)**: Dynamic headcount demand trajectory across Year 1 (523 FTEs), Year 2 (649 FTEs), and Year 3 (765 FTEs).
- **Visual 2 (Skill Gap Heatmap)**: Baseline employee proficiency grid (1.0 to 5.0 scale) highlighting severe gaps in AI/ML (2.83) and Cyber (2.52).
- **Visual 3 (Composite Risk Matrix)**: Priority rankings from P1 Data Engineers (9.2) to P6 RegTech (4.2).
- **Visual 4 (Financial Investment Donut)**: Phased $46.10M budget deployment with dynamic center totals.

---

## Strategic Recommendations (C-Suite Roadmap)
1. **Fast-Track Year 1 Cyber & Data Hiring**: Deploy $14.2M toward Cybersecurity (+29 FTEs) and Data Engineering (+28 FTEs) for Q4 2024 audit readiness.
2. **Launch Advisory Reskilling Academy**: Convert 90 Retail Advisors to Digital Advisors, saving ~$7.8M in recruiter fees.
3. **Deploy Retention Bonuses**: Allocate $4.1M to curb AI/ML turnover from 20% to 12%.
4. **Implement Stage-Gated Financial Releases**: Release Y2 ($16.3M) and Y3 ($46.1M) funds based on audit and reskilling milestones.
5. **Operationalize Power BI PMO Reviews**: Use monthly dashboard tracking to monitor hiring velocity and budget burn rates.

---

## Repository Portfolio Assets
- Executive Capstone Word Report (`GlobalTech_Workforce_Gap_Analysis_Report_Final_v3.docx`)
- 9-Slide Capstone Presentation Deck (`GlobalTech_Workforce_Gap_Analysis_Presentation.pptx`)

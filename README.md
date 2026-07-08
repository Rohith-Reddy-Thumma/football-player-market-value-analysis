# Football Player Market Value & Wage Efficiency Analysis

A business analytics case study using football player market value, wage, age, club, position, and performance data to identify wage inefficiency, recruitment opportunities, and age-related valuation risk.

---

## Recruiter Summary

| Area | Details |
|---|---|
| Project Type | Business analytics / sports analytics case study |
| Dataset | Top 100 football players from 2019 |
| Business Goal | Identify wage inefficiency, undervalued players, overpaid contracts, and age-related valuation risk |
| Tools Used | Microsoft Excel, CSV, Word/PDF, GitHub |
| Key Metrics | Market Value, Wage, Wage Efficiency Ratio, Value per Wage, Age Risk Band, Player Strategy Segment |
| Main Output | Dashboard, calculated metrics, visual analysis, and written case study |
| Target Roles | Data Analyst, Business Analyst, BI Analyst, Product Analyst |

---

## Executive Summary

This project analyzes the market value, wage structure, age profile, club distribution, position type, and performance attributes of the top 100 football players from 2019.

The goal is to simulate how a football club’s recruitment, scouting, or finance team could use analytics to identify undervalued players, overpaid contracts, age-related market risk, and club-level wage concentration.

The analysis found that wages generally increase with market value, but the relationship is not perfectly aligned. Some players appear to carry higher wage costs relative to their market value, suggesting potential contract inefficiency. Age also affects player valuation differently by position: goalkeepers showed a stronger age-related valuation decline than non-goalkeepers.

The final recommendation is to evaluate players using a combined framework of market value, wage efficiency, age risk, club wage structure, and position type instead of relying on market value alone.

---

## Business Problem

Football clubs make expensive recruitment and contract decisions under uncertainty. A player with a high market value may still be financially inefficient if their wage is disproportionately high. Similarly, an older player may carry resale-value risk even if their current performance remains strong.

This project asks:

**How can a football club use player market value, wage, age, club, position, and performance data to identify efficient contracts, risky contracts, and recruitment opportunities?**

Instead of looking only at raw market value, this analysis builds a decision framework around wage efficiency, age risk, and player segmentation.

---

## Dataset Overview

The dataset contains the top 100 football players from 2019. It includes player demographic, club, financial, and performance information.

### Key Variables

| Category | Examples |
|---|---|
| Player Information | Name, Age, Nationality, Club, Position |
| Financial Metrics | Wage, Market Value |
| Technical Attributes | Crossing, Finishing, Short Passing, Long Passing, Ball Control, Dribbling |
| Physical Attributes | Acceleration, Sprint Speed, Agility, Strength, Stamina |
| Goalkeeper Attributes | Diving, Handling, Kicking, Reflexes, Positioning |

The dataset includes both categorical and quantitative variables, making it suitable for descriptive analytics, segmentation, and business-focused visual analysis.

---

## Stakeholder Questions

This case study was designed around business-style questions a football club, recruitment team, or finance department might ask:

1. Which players provide the strongest market value relative to wage cost?
2. Which players may represent contract risk because their wages are high relative to market value?
3. Does age affect market value differently for goalkeepers and non-goalkeepers?
4. Which clubs show the highest wage concentration among top players?
5. How can players be segmented into recruitment targets, elite assets, depth options, and contract-risk profiles?
6. How can clubs evaluate player value using more than market value alone?

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, calculated fields, pivot tables, charts, dashboard design |
| CSV | Raw and processed data storage |
| Word/PDF | Written analysis and case study documentation |
| GitHub | Project documentation and portfolio publishing |

---

## Methodology

The project followed a descriptive analytics workflow:

1. **Data Collection**  
   Acquired a real-world football player dataset containing player, club, financial, and performance attributes.

2. **Data Cleaning**  
   Cleaned the raw dataset, standardized fields, and prepared the data for analysis in Excel.

3. **Feature Engineering**  
   Created new business-focused metrics such as Wage Efficiency Ratio, Value per Wage, Age Risk Band, and Player Strategy Segment.

4. **Exploratory Analysis**  
   Analyzed relationships between wage, market value, age, position type, and club.

5. **Visualization**  
   Built charts to compare player value, wage distribution, age-related valuation patterns, and club wage strategy.

6. **Business Interpretation**  
   Converted descriptive findings into recruitment, contract review, and wage-efficiency recommendations.

---

## KPI Framework

| Metric | Purpose |
|---|---|
| Market Value | Measures estimated player valuation |
| Wage | Measures recurring financial cost |
| Wage Efficiency Ratio | Identifies wage cost relative to market value |
| Value per Wage | Measures how much market value is generated per wage unit |
| Age Risk Band | Segments players by career stage |
| Position Type | Separates goalkeepers from non-goalkeepers |
| Player Strategy Segment | Classifies players into recruitment or contract-risk categories |
| Club Wage Concentration | Compares wage distribution across clubs |

---

## Calculated Metrics

### 1. Wage Efficiency Ratio

```text
Wage Efficiency Ratio = Wage / Market Value

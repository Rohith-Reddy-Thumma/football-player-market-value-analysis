# Player Valuation Strategy Dashboard

## Identifying Wage Inefficiency, Age-Related Valuation Risk, and Club Compensation Patterns

A product analytics-style case study analyzing football player market value, wages, age, position, and club affiliation to identify valuation patterns, wage inefficiencies, and potential contract risk.

---

## Project Overview

Football clubs make expensive decisions when signing, renewing, or selling players. However, player wages and market values are not always perfectly aligned. Some players may be highly paid relative to their market value, while others may provide stronger value compared to their compensation.

This project uses a dataset of the top 100 football players from 2019 to analyze how player age, position, wages, market value, and club affiliation influence valuation and compensation patterns.

The goal is to move beyond basic data visualization and build a decision-support case study that helps stakeholders understand:

- Which player groups are more sensitive to age-related value decline
- Whether player wages align with market value
- Which clubs show high-wage concentration
- Where potential wage inefficiency or contract risk may exist
- How a football club could use analytics to support recruitment, renewal, and compensation decisions

---

## Business Problem

Football clubs need to make high-cost roster decisions under uncertainty. A player may appear valuable based on reputation or current performance, but their wage, age, position, and market value may tell a different story.

Without a structured analytics framework, clubs risk:

- Overpaying players whose market value is declining
- Missing undervalued players with efficient wage profiles
- Applying the same valuation logic to different positions
- Failing to benchmark wage structures against competitors
- Making contract decisions based on intuition instead of evidence

This case study analyzes player valuation and compensation patterns to help clubs identify wage inefficiency and contract risk.

---

## Stakeholder Questions

This analysis is designed for a club operations, finance, recruitment, or strategy team.

Key stakeholder questions:

1. Which player groups show the strongest relationship between age and market value?
2. Are goalkeepers and non-goalkeepers valued differently as they age?
3. Do higher market-value players always receive higher wages?
4. Which clubs show the highest concentration of expensive wage brackets?
5. Where might clubs identify wage inefficiency or contract risk?
6. How can valuation segments support better contract and recruitment decisions?

---

## Dataset Description

The dataset contains information about the top 100 football players from 2019.

It includes categorical variables such as:

- Player name
- Nationality
- Club
- Age
- Position

It also includes quantitative variables such as:

- Wage
- Market value
- Crossing
- Finishing
- Heading accuracy
- Short passing
- Volleys
- Dribbling
- Curve
- Free-kick accuracy
- Long passing
- Ball control
- Acceleration
- Sprint speed
- Agility
- Other technical and physical attributes

These variables make it possible to analyze both player demographics and performance-related valuation patterns.

---

## Tools Used

- Microsoft Excel
- Data cleaning
- Pivot tables
- Calculated fields
- Scatter plots
- Bar charts
- Descriptive analytics
- Product analytics framing
- Business insight storytelling

---

## Key Metrics

| Metric | Description | Why It Matters |
|---|---|---|
| Market Value | Estimated financial value of each player | Helps evaluate player worth in the transfer market |
| Wage | Player compensation | Shows club spending and salary commitment |
| Age | Player age | Helps evaluate contract risk and value decline |
| Position | Player role on the field | Allows comparison across player groups |
| Club | Player's team | Helps compare compensation strategies across clubs |
| Wage-to-Value Ratio | Wage divided by market value | Helps identify possible wage inefficiency |
| Valuation Segment | Player category based on wage and value | Supports decision-making and risk prioritization |

---

## Calculated Metrics

### Wage-to-Value Ratio

```text
Wage-to-Value Ratio = Wage / Market Value
```

This metric helps identify whether a player is expensive relative to their market value.

A higher wage-to-value ratio may indicate potential contract risk, while a lower ratio may indicate stronger wage efficiency.

---

## Valuation Segments

Players can be grouped into four business-friendly valuation segments:

| Segment | Meaning |
|---|---|
| High Value / Efficient Wage | High market value with relatively lower wage |
| High Value / High Wage | High market value with high wage |
| Low Value / High Wage | Lower market value with high wage; possible contract risk |
| Low Value / Low Wage | Lower market value with lower wage commitment |

This segmentation turns the analysis into a decision-support tool rather than just a descriptive report.

---

## Analysis Approach

The analysis followed these steps:

1. Collected and reviewed the raw football player dataset
2. Cleaned and documented the dataset in Excel
3. Separated players into goalkeeper and non-goalkeeper groups
4. Analyzed the relationship between age and market value
5. Compared wage and market value relationships
6. Reviewed wage distribution across clubs
7. Added product-style metrics such as wage-to-value ratio
8. Created valuation segments to identify contract risk and wage efficiency
9. Developed insights and recommendations for decision-makers

---

## Dashboard Design

The dashboard is designed to help a stakeholder quickly evaluate player valuation and wage patterns.

Recommended dashboard components:

### KPI Cards

- Total Players
- Average Market Value
- Average Wage
- Average Age
- Highest Wage-to-Value Ratio

### Core Visuals

- Age vs. Market Value for Goalkeepers
- Age vs. Market Value for Non-Goalkeepers
- Wage vs. Market Value
- Wage-to-Value Ratio by Player
- Average Wage-to-Value Ratio by Position
- Valuation Segment Count
- Club Wage Distribution

### Filters

- Position
- Club
- Age Group
- Valuation Segment

---

## Key Findings

### 1. Goalkeeper market value is more age-sensitive

The analysis showed a clear negative relationship between goalkeeper age and market value. As goalkeepers age, their market value tends to decline. The relationship was stronger for goalkeepers than for other players, suggesting that clubs may need a separate valuation model for this position group.

### 2. Non-goalkeeper market value depends on more than age

For non-goalkeepers, the relationship between age and market value was weaker. This suggests that other factors such as performance, position, club reputation, technical ability, and role may have a larger influence on valuation.

### 3. Wage and market value are related, but not perfectly aligned

Higher-value players generally earn higher wages, but the relationship is not perfectly consistent. Some players with similar market values receive different wages, likely due to experience, contract negotiation, reputation, club strategy, or performance history.

### 4. Wage growth shows signs of diminishing returns

The wage vs. market value analysis suggests that wages generally rise with market value, but not always proportionally. At higher market values, wage increases may begin to flatten or vary more widely.

### 5. Club wage structures vary significantly

Clubs such as Real Madrid, FC Barcelona, Manchester City, and Paris Saint-Germain had players across higher wage brackets, reflecting strong financial investment in top talent. Other clubs showed more conservative wage distributions.

### 6. Wage-to-value ratio can help identify contract risk

Players with high wages relative to market value may represent potential contract inefficiency. Players with lower wages relative to market value may represent stronger roster value.

---

## Business Recommendations

Based on the analysis, a football club decision-maker could:

1. Use separate valuation models for goalkeepers and non-goalkeepers because age impacts these groups differently.
2. Monitor players with high wage-to-value ratios to identify potential contract inefficiencies.
3. Compare wage structure by club to benchmark compensation strategy against competitors.
4. Use valuation segments to prioritize which players require contract review.
5. Combine market value, wage, age, and position before making renewal or transfer decisions.
6. Avoid relying on market value alone when estimating wage expectations.
7. Investigate high-wage outliers before making long-term contract commitments.

---

## Product Analyst Takeaway

This project demonstrates how raw sports data can be transformed into a decision-support framework.

Instead of only reporting descriptive trends, the analysis creates metrics, segments players by valuation risk, and provides recommendations that could help stakeholders make better contract, recruitment, and compensation decisions.

The same approach can be applied to product analytics by:

- Segmenting users or customers
- Identifying high-risk cohorts
- Creating efficiency metrics
- Comparing behavior across groups
- Translating data patterns into business recommendations
- Building dashboards that help stakeholders make decisions

---

## Why This Project Matters

This project is not just about football. It demonstrates a repeatable analytics process that can be applied in product, business, and operations environments.

The workflow shows how an analyst can:

1. Understand a business problem
2. Clean and structure data
3. Define useful metrics
4. Segment observations into meaningful groups
5. Build visualizations
6. Interpret patterns
7. Recommend actions
8. Communicate insights to stakeholders

These are core skills for Product Analyst, Business Analyst, and Data Analyst roles.

---

## Suggested Repository Structure

```text
player-valuation-strategy-dashboard/
│
├── README.md
│
├── data/
│   ├── raw_football_player_data.csv
│   └── cleaned_football_player_data.xlsx
│
├── analysis/
│   └── analysis_workbook.xlsx
│
├── visuals/
│   ├── dashboard_overview.png
│   ├── wage_to_value_ratio.png
│   ├── valuation_segments.png
│   ├── age_market_value_goalkeepers.png
│   ├── age_market_value_non_goalkeepers.png
│   └── club_wage_distribution.png
│
└── reports/
    ├── football_player_market_value_insights.docx
    └── project_requirements.pdf
```

---

## File Descriptions

| File | Description |
|---|---|
| `raw_football_player_data.csv` | Original raw dataset |
| `cleaned_football_player_data.xlsx` | Cleaned and documented dataset |
| `analysis_workbook.xlsx` | Excel workbook containing analysis and charts |
| `football_player_market_value_insights.docx` | Written insights and interpretation |
| `project_requirements.pdf` | Original project requirement document |
| `dashboard_overview.png` | Final dashboard screenshot |
| `wage_to_value_ratio.png` | Wage efficiency chart |
| `valuation_segments.png` | Player valuation segment chart |

---

## Skills Demonstrated

- Data cleaning
- Data documentation
- Descriptive analytics
- Product analytics thinking
- Business problem framing
- Metric creation
- Segmentation analysis
- Data visualization
- Dashboard design
- Insight communication
- Recommendation development
- Stakeholder-focused storytelling

---

## Resume Version

**Player Valuation Strategy Dashboard | Excel, Data Cleaning, Product Analytics, Data Visualization**

Built a product analytics-style dashboard analyzing 100 football players to identify wage inefficiency, age-related valuation risk, and club compensation patterns. Created calculated metrics including wage-to-value ratio and valuation segments, comparing goalkeeper and non-goalkeeper value trends to support contract, recruitment, and compensation decision-making.

---

## Future Improvements

Future versions of this project could include:

- A Power BI dashboard
- SQL-based analysis
- Python data cleaning and modeling
- Player clustering based on performance attributes
- Predictive modeling for market value
- Position-specific valuation models
- Interactive filters for club, position, and wage segment
- Additional seasons of player data for trend analysis

---

## Conclusion

This case study shows how football player data can be used to support smarter valuation and compensation decisions.

By combining market value, wages, age, position, and club-level wage distribution, the analysis identifies patterns that can help stakeholders evaluate wage efficiency and contract risk.

The project demonstrates the full analytics process: cleaning data, defining metrics, creating visualizations, interpreting insights, and turning findings into business recommendations.

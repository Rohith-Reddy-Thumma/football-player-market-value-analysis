# Football Player Market Value & Wage Analysis

## Project Overview
This project analyzes the top 100 football players from the 2019 player dataset to understand how age, position, club, market value, and wages relate to one another. The goal was to turn raw player attributes into business-style insights that could help a football club, analyst, or scouting department evaluate player valuation, compensation patterns, and squad investment strategy.

The analysis focuses on three key questions:

1. How does age affect player market value?
2. Do goalkeepers and non-goalkeepers follow different valuation patterns?
3. How closely are wages aligned with market value across players and clubs?

## Business Problem
Football clubs make major financial decisions when signing, renewing, or selling players. A player's market value is influenced by age, position, performance, reputation, contract terms, and club demand. However, wages do not always move perfectly with market value.

This project explores whether clubs are paying players in line with their market value and whether player age affects different positions in different ways.

## Dataset
The dataset contains 100 football players from 2019 and includes both categorical and quantitative variables.

### Categorical Variables
- Player name
- Nationality
- Club
- Position

### Quantitative Variables
- Age
- Market value
- Wage
- Technical attributes such as crossing, finishing, short passing, dribbling, ball control, acceleration, sprint speed, agility, and more

The final cleaned dataset includes 100 player records and 42 columns.

## Tools Used
- Microsoft Excel for data cleaning, exploration, and visualization
- Descriptive analytics for trend identification
- Correlation analysis for relationship testing
- Scatter plots and bar charts for visual storytelling
- Data dictionary documentation for field definitions

## Data Preparation
The original dataset was reviewed, cleaned, and documented before analysis. The data preparation process included:

- Reviewing available player attributes
- Separating categorical and quantitative variables
- Cleaning and organizing the dataset in Excel
- Creating a data dictionary to explain each variable
- Building visualizations to compare age, value, wage, position, and club patterns

## Analysis Questions

### 1. Does age reduce player market value?
The analysis found a negative relationship between age and market value. As players get older, their market value generally decreases, but the strength of that relationship differs by position.

### 2. Are goalkeepers valued differently from other players?
Yes. Goalkeepers showed a much stronger age-related decline in market value than non-goalkeepers.

For goalkeepers, age explained about 58% of the variation in market value. This suggests that goalkeeper valuation in this dataset is strongly tied to age.

For non-goalkeepers, age explained only about 12% of the variation in market value. This means other factors such as performance, attacking contribution, club, and reputation likely play a larger role.

### 3. Are wages aligned with market value?
Wages and market value showed a positive relationship. Higher-valued players generally earned higher wages, but the relationship was not perfect. Some players earned much higher wages than their market value alone would suggest, while others appeared to provide strong value relative to their wage.

This indicates that wages are influenced by more than just market value. Contract negotiations, player reputation, club financial strength, age, experience, and star power may also affect salary decisions.

## Key Findings

### Finding 1: Goalkeepers lose market value faster with age
Goalkeepers had a stronger negative correlation between age and market value than non-goalkeepers. In this dataset, older goalkeepers showed a sharper drop in market value, while younger goalkeepers had higher valuation potential.

**Business takeaway:** Clubs should be cautious when investing heavily in older goalkeepers unless the player brings exceptional experience, leadership, or short-term performance value.

### Finding 2: Non-goalkeeper value depends on more than age
Non-goalkeepers showed a weaker relationship between age and market value. Their values were more spread out, suggesting that attacking output, position, club, technical skill, and reputation play a larger role.

**Business takeaway:** For outfield players, clubs should avoid using age alone as a valuation factor. Performance attributes and role-specific contribution should be included in scouting and contract decisions.

### Finding 3: Market value and wages are related, but not identical
Players with higher market value generally earned more, but the scatter plot showed exceptions. Some players had very high wages compared to their market value, while others had high market value with relatively lower wages.

**Business takeaway:** Clubs can use value-to-wage analysis to identify potential overpaid players and undervalued talent.

### Finding 4: Elite clubs carry higher wage concentration
Clubs such as Real Madrid, FC Barcelona, Manchester City, Juventus, and Paris Saint-Germain had multiple players in higher wage brackets. This reflects the financial strength of elite clubs and their ability to attract and retain top talent.

**Business takeaway:** Wage structure is a major indicator of club strategy. Clubs with deeper wage budgets can build stronger squad depth, but they may also carry higher financial risk if wages are not aligned with performance.

## Sample Metrics From the Analysis

| Metric | Result |
|---|---:|
| Total players analyzed | 100 |
| Average player age | 28 years |
| Average market value | $51.6M |
| Average wage | $196K |
| Highest market value | Neymar Jr - $118.5M |
| Highest wage | Lionel Messi - $565K |
| Correlation between wage and market value | 0.59 |
| Goalkeeper age-value R-squared | 0.58 |
| Non-goalkeeper age-value R-squared | 0.12 |

## Visualizations Created

The project includes the following visuals:

1. Goalkeeper age vs. market value scatter plot
2. Non-goalkeeper age vs. market value scatter plot
3. Wage vs. market value scatter plot
4. Club wage distribution bar chart

These visuals help compare valuation trends by role, player economics, and club-level wage strategy.

## Recommendations

### Recommendation 1: Use position-specific valuation models
Goalkeepers and outfield players should not be evaluated using the same age-based assumptions. Goalkeeper market value appears more sensitive to age, while non-goalkeeper value depends more on other performance and market factors.

### Recommendation 2: Track wage efficiency
Clubs should compare market value against wage levels to identify players who may be overpaid or undervalued. This can support contract renewals, transfer decisions, and salary negotiations.

### Recommendation 3: Combine financial and performance attributes
Market value and wages are useful, but they should be analyzed alongside technical skills such as finishing, passing, dribbling, sprint speed, and ball control. A more complete model would help clubs understand not only what players cost, but also what they contribute.

### Recommendation 4: Monitor squad-level wage distribution
Club wage structure can reveal whether spending is concentrated in a few star players or distributed across squad depth. This matters for long-term financial planning and competitive balance.

## What I Learned
This project helped me practice the full analytics workflow:

- Finding and validating a real-world dataset
- Cleaning and documenting variables
- Creating a data dictionary
- Building visualizations for business questions
- Interpreting relationships between categorical and quantitative variables
- Translating analysis into business recommendations

The biggest learning was that descriptive analytics becomes more valuable when the insights are connected to a decision. Instead of only reporting charts, this project explains what the patterns mean for player valuation and club financial strategy.

## Future Improvements
If I continue developing this project, I would add:

- A Power BI or Tableau dashboard
- Position-level filtering
- Value-to-wage efficiency ranking
- Regression modeling to predict market value
- Comparison across multiple seasons
- More advanced features such as contract length, minutes played, goals, assists, and injury history

## Repository Structure

```text
football-player-market-value-analysis/
├── README.md
├── data/
│   ├── raw_data.csv
│   └── cleaned_player_data.xlsx
├── visuals/
│   ├── goalkeeper_age_value.png
│   ├── non_goalkeeper_age_value.png
│   ├── wage_market_value.png
│   └── club_wage_distribution.png
└── reports/
    └── insights_summary.docx
```

## Portfolio Summary
This project analyzes football player market value and wage patterns using a dataset of the top 100 players from 2019. I cleaned and documented the data, created visualizations, compared goalkeeper and non-goalkeeper valuation trends, and translated the findings into business recommendations for player valuation, wage efficiency, and squad investment strategy.

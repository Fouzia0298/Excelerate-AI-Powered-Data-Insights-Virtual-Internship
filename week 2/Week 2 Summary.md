# Week 2: Exploratory Data Analysis (EDA)

## Objective
To understand learner demographics, behavior patterns, and seasonal trends through visualizations and statistical summaries. This helps inform future modeling and strategic decision-making.

## Key Insights

### Demographics
- **Age Distribution**: Majority of learners are aged 21–25 (~1,750 learners), with a peak at age 24.
- **Gender Distribution**: Male participants dominate (~1,500), followed by females (~1,000), while only a few chose not to specify.
- **Top Countries**: India leads with ~1,100 learners, followed by the USA (~1,000), Nigeria (~400), Pakistan (~300), and Ghana (~200).
- **Majors**: Information Systems (~550) and Computer Science (~480) are the most common majors.

### Opportunity Categories
- **Courses**: Most popular (~1,600 learners)
- **Events**: ~400 learners
- **Internships**: ~300 learners
- **Competitions**: ~300 learners
- **Engagement Opportunities**: Least popular (~100 learners)

### Status Distribution
- **Team Allocated**: Largest category (~1,800 learners)
- **Dropped Out**: ~250 learners
- **Started**: ~500 learners
- **Withdrawn/Rewards Awarded**: Very low counts

### Seasonal Trends
- **Peak Signups**: March, June, and September aligning with academic cycles.
- **Sharp Decline in 2024**: Early months show high sign-ups, but numbers dropped significantly starting March 2024.

### Engagement Patterns
- **Engagement Duration**: Varies widely; recent users tend to engage more quickly than earlier ones.
- **Opportunity Duration vs. Engagement Duration**: Strong positive correlation (r = 0.83) – longer opportunities lead to longer engagement.
- **Low Engagement Scores**: 76% of learners scored below 0.5, indicating limited involvement.

## Visualizations
- Histograms and KDE plots for age distribution
- Bar charts for gender, opportunity categories, status description
- Time series and heatmap for signup trends
- Boxplots for engagement duration by gender and opportunity type

## Recommendations
- Optimize campaign timing around peak months (March, June, September)
- Revitalize underperforming categories like "Engagement"
- Explore reasons behind the 2024 decline in signups
- Improve visibility and accessibility of competitions

## Tools Used
- Microsoft Excel (data inspection)
- Python (Pandas, Matplotlib, Seaborn)

## Outcomes
- Rich understanding of user behavior
- Identification of key trends and potential issues
- Foundation for churn analysis and predictive modeling

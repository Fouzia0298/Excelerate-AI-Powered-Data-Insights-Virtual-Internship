# Week 3: Churn Analysis & Predictive Modeling

## Objective
Identify students likely to drop out using historical data and build predictive models to support retention strategies.

## Key Insights
- **Churn Rate**: 91.7% of students were classified as churned (2,269 out of 2,475).
- **Drivers of Churn**:
  - Inactive for over 126 days → **23.6x more likely to churn**
  - Low Engagement Score (<1.2) → **18.2x more likely to churn**
  - Each additional opportunity type reduces churn likelihood by **63%**
- **Dropout by Category**:
  - Internships showed the highest dropout rate
  - Competitions had **34% lower churn** compared to courses

## Models Built
- **Logistic Regression**
- **Random Forest**
- **XGBoost**

## Model Performance
| Metric       | Value     |
|--------------|-----------|
| Test Accuracy| ~50%      |
| Recall (Churn)| 0.45     |
| F1-Score     | 0.75      |

## Top Features
- Engagement Duration
- Opportunity Category
- Opportunity Duration
- Signup Month
- Age

## Recommendations
- Launch personalized re-engagement campaigns for inactive users
- Expand competition-based opportunities
- Encourage multi-opportunity participation
- Implement real-time monitoring dashboard for at-risk students
- Use segmented communication strategies (e.g., gender-based)

## Tools Used
- Scikit-learn
- SMOTE for class imbalance
- GridSearchCV for hyperparameter tuning

## Outcomes
- Predictive model identifying at-risk students
- Actionable strategies to reduce churn
- Estimated $34,600 annual savings with 10% churn reduction

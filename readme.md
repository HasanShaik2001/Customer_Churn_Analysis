# Customer_Churn_Analysis

### Overview
This project aims to analyze customer churn behavior in a telecom company using Power BI and SQL Server. The goal is to uncover key patterns and insights that help the business understand why customers leave and how to reduce churn.

### Data Set
The dataset used for this analysis contains customer information such as:

- Demographics (gender, senior citizen, dependents, etc.)
- Services opted (InternetService, PhoneService, StreamingTV, etc.)
- Account info (tenure, contract type, payment method)
- Churn label (Yes/No)

### Source
 [Customer Churn Dataset](https://pivotalstats.com/end-end-churn-analysis-portfolio-project/)

### Objectives

- Cleaning and preprocessing the data
- Visualizing churn distribution across various features
- Identifying key drivers of customer churn
- Providing actionable business insights

### Actionable Insights

- Overall Churn Rate is High
Out of 6418 customers, around 1,732 customers churned, giving an overall churn rate of 27%. This means more than 1 in 4 customers left the service, highlighting a critical area of business loss.

### Month-to-Month Contracts Drive Churn

- 88% of churned customers were on month-to-month contracts.

- Churn rate for this group is 43%, compared to only 11% for 1-year and 3% for 2-year contracts.

- Actionable Insight: Promote long-term contracts using discounts, loyalty rewards, or free value-added services.

### Senior Citizens Are More Likely to Churn

- 42% of senior citizens (SeniorCitizen = Yes) churned, compared to only 24% of non-seniors.

- Although senior citizens make up just 16% of the customer base, they represent a disproportionately high share of churned users.

- Actionable Insight: Provide simplified plans, better onboarding, and personalized support for older users.

### Value-Added Services Improve Retention

- Customers without Online Security have a churn rate of 35%, vs only 15% with it.

- Similarly, churn is 33% without Tech Support vs 14% with it.

- Actionable Insight: Offer bundled packages that include Online Security, Backup, and Tech Support to increase stickiness.

### Electronic Check Payments Signal High Risk

- Churn rate among customers using Electronic Check is 45% — the highest of all payment methods.

- In contrast, Bank Transfer (automatic) and Credit Card (automatic) users have churn rates under 17%.

- Actionable Insight: Offer discounts or loyalty points for switching to auto-payment methods.

### Dependents & Partners Reduce Churn

- Customers without dependents churn at 32%, vs only 16% for those with dependents.

- Likewise, single/unpartnered users churn at 31%, compared to 17% for those with partners.

- Actionable Insight: Family/group plans or multi-line offers can significantly enhance retention.

### Fiber Optic Users Have Highest Churn

- Among customers with Fiber optic internet, the churn rate is 42% — much higher than DSL (19%) or No Internet (7%).

- Actionable Insight: Investigate service quality, pricing, and competition in areas with high fiber churn.

### Streaming Services Have Mixed Impact

- Churn is slightly higher among users with Streaming TV (30%) and Movies (29%) than those without.

- These optional services may not anchor retention but could be used to enhance long-term plans.

### Multiple Lines = Lower Churn

- Users with multiple phone lines churn at 19%, compared to 27% for those with a single line.

- Actionable Insight: Promote family or shared plans to lock in multiple users and lower churn likelihood.

### Tenure Shows Inverse Relationship to Churn

- Customers with tenure under 12 months have a churn rate over 50%.

- Those with tenure over 24 months have a churn rate under 10%.

- Actionable Insight: Introduce retention offers or rewards in the first year of service to prevent early dropout.




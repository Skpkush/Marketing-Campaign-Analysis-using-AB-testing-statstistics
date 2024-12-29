# Marketing-Campaign-Analysis-using-AB-testing-statstistics

# Marketing Campaign Performance Analysis

## Project Overview
This project analyzes the performance of two digital advertising campaigns - Facebook Ads and Google AdWords - conducted throughout 2019. The analysis aims to help marketing agencies make data-driven decisions about budget allocation and campaign optimization by comparing key performance metrics across both platforms.

## Business Problem
Marketing agencies need to maximize ROI for their clients' advertising campaigns. This analysis addresses the challenge of identifying the most effective advertising platform by examining:
- Click-through rates and conversion patterns
- Cost efficiency across platforms
- Long-term performance trends

## Dataset Description
The dataset contains daily performance metrics for both Facebook and Google AdWords campaigns throughout 2019 (365 days). Key metrics include:
- Ad Views (Impressions)
- Ad Clicks
- Conversions
- Campaign Costs
- Click-Through Rate (CTR)
- Conversion Rate
- Cost per Click (CPC)

## Key Findings

### 1. Conversion Performance
- Facebook averaged 11.74 conversions per day vs 5.98 for AdWords
- Facebook showed higher variation in daily conversions
- Facebook had more high-conversion days (10+ conversions) while AdWords mostly stayed in the 6-10 range

### 2. Click-to-Conversion Correlation
- Facebook: Strong positive correlation (0.87) between clicks and conversions
- AdWords: Moderate positive correlation (0.45) between clicks and conversions
- Facebook showed more consistent conversion performance from clicks

### 3. Statistical Analysis
- T-test results (p-value: 9.35e-134) confirmed Facebook's significantly higher conversion rate
- Linear regression model for Facebook conversions achieved 76.35% accuracy (R² score)
- Cointegration analysis revealed a stable long-term relationship between ad spend and conversions

### 4. Temporal Patterns
- Highest conversions occurred on Mondays and Tuesdays
- Monthly conversion trends showed gradual improvement over the year
- Cost Per Conversion (CPC) was most favorable during May and November

## Tools and Technologies Used
- Python 3.x
- Libraries:
  - pandas: Data manipulation and analysis
  - matplotlib & seaborn: Data visualization
  - scipy: Statistical analysis
  - scikit-learn: Regression modeling
  - statsmodels: Time series analysis

## Recommendations
1. Prioritize Facebook advertising for conversion-focused campaigns
2. Optimize campaign timing around early weekday performance
3. Consider increasing budget allocation during months with historically lower CPC
4. Leverage the predictable relationship between ad spend and conversions for budget planning

## Future Work
- Incorporate seasonal adjustment factors
- Analyze ad creative performance
- Include competitor benchmarking
- Develop automated reporting system

## Contributors
[Your Name]

## License
This project is licensed under the MIT License - see the LICENSE file for details

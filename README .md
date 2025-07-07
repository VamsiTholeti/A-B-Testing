
# 📊 Optimizing Conversion Rates Using A/B Testing: A Marketing Analytics Case Study

## ✅ Project Overview
A/B Testing (also known as Split Testing) is a powerful statistical technique used in marketing analytics to compare two different experiences and determine which one performs better in achieving a specific business objective — in this case, **user conversion**.

## 🎯 Objective
Evaluate whether displaying advertisements (Ad Group) leads to a higher conversion rate compared to public service announcements (PSA Group) using real user behavior data.

## 🧾 Dataset Description
The dataset includes key user interaction metrics:

| Column Name     | Description                                        |
|------------------|----------------------------------------------------|
| user_id         | Unique identifier for each user                    |
| test_group      | Ad group (experiment) or PSA group (control)       |
| converted       | 1 if the user converted, 0 otherwise               |
| total_ads       | Number of ads seen by the user                     |
| most_ads_day    | Day user saw the most ads                          |
| most_ads_hour   | Hour user saw the most ads                         |

- **Ad Group:** Users shown advertisements  
- **PSA Group:** Users shown public service announcements  

## 🧪 Methodology
1. Randomly split users into two groups:
   - Group A (Control): PSA group
   - Group B (Treatment): Ad group
2. Used a **Chi-Square Test** to assess statistical significance between groups.

## 🐍 Python Tools & Techniques Used
- **Pandas & NumPy:** Data cleaning and manipulation  
- **Matplotlib & Seaborn:** Data visualization  
- **SciPy:** Statistical testing (Chi-Square Test)  
- **EDA:** To identify user patterns and ad performance impact  

## 📈 Statistical Analysis (Chi-Square Test Results)

| Metric          | Ad Group   | PSA Group |
|------------------|------------|------------|
| Users           | 5,64,577   | 23,524     |
| Conversions     | 14,423     | 420        |
| Conversion Rate | 2.55%      | 1.79%      |

- **Chi2 Statistic:** 54.01  
- **p-value:** 1.99 × 10⁻¹³  

**Interpretation:** The p-value is well below 0.05, indicating that the difference in conversion rates is statistically significant.

## 📊 Key Insights
- The Ad Group saw a **0.76 percentage point** increase in conversions.
- This is a **42.5% relative uplift** in conversions over the PSA group.
- The results are **statistically and practically significant**.

## 🚀 Business Recommendation
- ✅ Continue or scale up the ad campaign due to its proven effectiveness.
- 💡 Reinvest in targeted advertising based on performance uplift.
- 📈 Use A/B testing regularly for future campaign validation.

## 📝 Summary
This A/B Testing project showcases how **data science and statistical analysis** can drive business decisions. By comparing the conversion performance of ads vs. PSAs, we conclude that advertising significantly boosts user conversions. These insights are valuable for strategic marketing planning and optimization.

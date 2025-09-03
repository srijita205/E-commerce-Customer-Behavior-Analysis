# E-commerce-Customer-Behavior-Analysis
![OIP](https://github.com/user-attachments/assets/d6792933-1205-4004-bd24-3c258d7b06dc)

# 1. Introduction

The objective of this analysis is to study customer behaviour patterns, spending habits, and satisfaction levels based on demographic and membership factors. The dataset includes details such as gender, age, membership type, spending, discounts applied, and satisfaction levels.

# 2. Data Preprocessing
The dataset was checked for missing values, duplicates, and inconsistencies. Data was grouped and categorized for hypothesis testing. Age groups and membership categories were used to form contingency tables and perform statistical tests.

# 3. Exploratory Data Analysis (EDA)
- Descriptive statistics such as mean and standard deviation were calculated for spending.
- Frequency distributions were created for membership type, gender, and satisfaction levels.
- Correlation analysis was performed to study relationships between spending and other variables.
- Visualizations included bar plots and correlation heatmaps to highlight relationships.
  
# 4. Hypothesis Testing
a) Two-sample t-test: Discount vs No Discount
Result: p-value = 0.0016 → Reject H₀. Spending differs between customers with and without discounts.
b) Membership Type Comparisons (t-tests):
 - Gold vs Silver: p-value ≈ 0 → Significant difference in spending.
 - Gold vs Bronze: p-value ≈ 0 → Significant difference in spending.
c) Chi-Square Tests:
 - Gender vs Membership Type: p-value ≈ 0 → Strong association.
 - Age Group vs Satisfaction Level: p-value ≈ 0 → Strong association.
 - Membership Type vs Discount Applied: p-value = 0.97 → No significant association.
d) ANOVA Test:
 - Result: p-value ≈ 0 → Significant difference. At least one membership type has a different average spend.
   
# 5. Results & Interpretation
- Customers with discounts spend significantly differently compared to those without discounts.
- Gold members spend much more on average compared to Silver and Bronze members.
- Gender and membership type are strongly associated, indicating preferences across genders.
- Age group strongly affects satisfaction levels, with younger groups showing higher satisfaction.
- Discounts are evenly distributed across membership types (no significant association).
- ANOVA confirms that spending behaviour significantly varies by membership type.
# 6. Conclusion & Recommendation
The analysis reveals that Gold members are the most valuable customers, showing significantly higher spending. Discounts impact spending behaviour, making promotions effective. Age and gender play important roles in shaping satisfaction and membership preferences. Businesses should prioritize Gold members for premium services, while also targeting specific age groups to improve satisfaction. Discount strategies should be applied uniformly as they influence spending across all memberships. Recommendation.

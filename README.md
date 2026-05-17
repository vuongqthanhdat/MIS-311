# MIS 311 - Introduction to Business Analytics
## Dataset Overview
This project analyses a retail sales dataset containing transaction records from different cities and product categories. The dataset includes information such as branch, city, customer type, product name, product category, quantity purchased and total sales value.

- Original dataset size: 253 rows × 8 columns
- Cleaned dataset size: 239 rows × 8 columns
- Tools used: Microsoft Excel, Pivot Table, Descriptive Statistics and Charts

Business context: The primary objective of this analysis is to evaluate sales performance and identify purchasing patterns across product categories and geographic locations. Specifically, the analysis aims to answer the following questions: Which product categories drive the highest revenue? How does sales performance vary across cities?

## Data Cleaning
Before conducting the analysis, the dataset was cleaned to improve accuracy and consistency.

### Missing Values
Several rows contained missing values in critical fields such as quantity, customer_type and product_category. A total of 11 rows with incomplete data were identified. These rows were removed because missing key values could mess up revenue calculations and make the category analysis less accurate.

### Duplicate Records
The dataset also contained duplicate transaction records. 3 duplicate records were identified and removed to avoid double-counting sales values and quantities.
After cleaning, the dataset was reduced from 253 rows to 239 rows. The cleaned dataset was used for all analyses and visualisations.

## Descriptive Statistics

### Descriptive Statistics Analysis

<img width="515" height="362" alt="image" src="https://github.com/user-attachments/assets/7d8ccf56-8bfd-42b3-b309-57fa7c6d6481" />

The descriptive statistics indicate that the average quantity purchased per transaction was approximately 10.78 items, while the median quantity was 11 items. Since the mean and median are very close, customer purchasing quantities were relatively balanced across transactions.

For total sales value, the average transaction amount was 127.04, whereas the median value was 106.59. The higher mean compared to the median suggests that several high-value purchases increased the overall average sales revenue. This indicates that while most customers spent moderate amounts, a smaller number of transactions contributed significantly higher sales values.

### Sales Analysis by Product Category

<img width="1760" height="659" alt="image" src="https://github.com/user-attachments/assets/e25e0e1f-9454-4eba-87ab-e383ed34a56a" />

Insight 1: Fruits generated the highest revenue at 7,450.12 (approximately 24.5% of total sales), while Personal Care recorded the lowest performance (nearly 4,509.59). This suggests that Fruits benefit from strong and consistent consumer demand, likely driven by frequent purchases rather than high pricing. In contrast, the underperformance of Personal Care may indicate weaker demand or less effective product positioning.

Business implication: This suggests that the company should prioritise improving underperforming categories such as Personal Care through targeted promotions, pricing adjustments or product repositioning. Additionally, high-performing categories like Fruits should be leveraged through inventory expansion and cross-selling strategies to maximise revenue growth.

### Sales Analysis by City

<img width="1529" height="661" alt="image" src="https://github.com/user-attachments/assets/696179db-2fe8-4aa7-8f80-2e9de2c55bd8" />

Insight 2: Chicago and New York are the top-performing cities with similar revenue levels, at 10,813.94 and 10,613.69 respectively, indicating stable and consistent demand in these core markets. In contrast, Los Angeles generates significantly lower revenue (about 8935.31), suggesting underperformance relative to its potential. This gap highlights an opportunity for the company to improve sales through targeted strategies in the Los Angeles market.

Business implication: This indicates that the company is highly dependent on Chicago and New York as its core revenue drivers. To reduce this reliance and achieve more balanced growth, the company should prioritise improving performance in Los Angeles through targeted promotions, localised product offerings and pricing strategies aligned with customer demand.

## Conclusion

In general, the business demonstrates stable performance, with revenue relatively balanced across product categories and concentrated in two core markets, Chicago and New York. Nevertheless, there are some opportunities exist to improve underperforming segments, particularly Personal Care and the Los Angeles market. By optimising weaker categories and strengthening performance in less-developed locations, the company can achieve more balanced growth and enhance overall revenue efficiency.

## References

- GitHub Docs. (2024). Getting started with GitHub. Retrieved from https://docs.github.com/





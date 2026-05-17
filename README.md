# MIS 311 - Introduction to Business Analytics
## Dataset Overview
This project analyses a retail sales dataset containing transaction records from different cities and product categories. The dataset includes information such as branch, city, customer type, product name, product category, quantity purchased and total sales value.
> Original dataset size: 253 rows × 8 columns

> Cleaned dataset size: 239 rows × 8 columns

> Tools used: Microsoft Excel, Pivot Table and Charts

> Business context: The primary objective of this analysis is to evaluate sales performance and identify purchasing patterns across product categories and geographic locations. Specifically, the analysis aims to answer the following questions: Which product categories drive the highest revenue? How does sales performance vary across cities?

## Data Cleaning
Before conducting the analysis, the dataset was cleaned to improve accuracy and consistency.

### Missing Values
Several rows contained missing values in critical fields such as quantity, customer_type and product_category. A total of 11 rows with incomplete data were identified. These rows were removed because missing key values could mess up revenue calculations and make the category analysis less accurate.

### Duplicate Records
The dataset also contained duplicate transaction records. 3 duplicate records were identified and removed to avoid double-counting sales values and quantities.
After cleaning, the dataset was reduced from 253 rows to 239 rows. The cleaned dataset was used for all analyses and visualisations

## Descriptive Statistics

### Sales Analysis by Product Category

<img width="1262" height="614" alt="image" src="https://github.com/user-attachments/assets/d54feb80-e7fb-4bb7-8ff5-0e9955ca719f" />

Insight 1: Fruits generated the highest revenue at 7,450.12 (24.5% of total sales), while Personal Care recorded the lowest performance. This suggests that Fruits benefit from strong and consistent consumer demand, likely driven by frequent purchases rather than high pricing. In contrast, the underperformance of Personal Care may indicate weaker demand or less effective product positioning.

Business implication: This suggests that the company should prioritise improving underperforming categories such as Personal Care through targeted promotions, pricing adjustments or product repositioning. Additionally, high-performing categories like Fruits should be leveraged through inventory expansion and cross-selling strategies to maximise revenue growth.

### Sales Analysis by City

<img width="1061" height="568" alt="image" src="https://github.com/user-attachments/assets/18abfbcf-534d-4f4c-b3a1-34c6842fb554" />

Insight 2: Chicago and New York are the top-performing cities with similar revenue levels, at 10,813.94 and 10,613.69 respectively, indicating stable and consistent demand in these core markets. In contrast, Los Angeles generates significantly lower revenue, suggesting underperformance relative to its potential. This gap highlights an opportunity for the company to improve sales through targeted strategies in the Los Angeles market.

Business implication: This indicates that the company is highly dependent on Chicago and New York as its core revenue drivers. To reduce this reliance and achieve more balanced growth, the company should prioritise improving performance in Los Angeles through targeted promotions, localised product offerings and pricing strategies aligned with customer demand.

## Conclusion

In general, the business demonstrates stable performance, with revenue relatively balanced across product categories and concentrated in two core markets, Chicago and New York. Nevertheless, there are some opportunities exist to improve underperforming segments, particularly Personal Care and the Los Angeles market. By optimising weaker categories and strengthening performance in less-developed locations, the company can achieve more balanced growth and enhance overall revenue efficiency.



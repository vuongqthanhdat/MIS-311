# MIS 311 - Introduction to Business Analytics
## Dataset Overview
This project analyses a retail sales dataset containing transaction records from different cities and product categories. The dataset includes information such as branch, city, customer type, product name, product category, quantity purchased and total sales value.
> Original dataset size: 250 rows × 8 columns

> Cleaned dataset size: 239 rows × 8 columns

> Tools used: Microsoft Excel, Pivot Table and Charts

> Business context: This dataset represents sales transactions from a retail business operating in multiple cities. The goal of the analysis is to identify customer purchasing patterns and evaluate business performance across different product categories and customer types.

## Data Cleaning
Before conducting the analysis, the dataset was cleaned to improve accuracy and consistency.

### Missing Values
Several rows contained missing values in important columns such as:
> quantity

> customer_type

> product_category

Rows with incomplete information were removed because missing values could negatively affect descriptive statistics and visual analysis accuracy.

### Duplicate Records
The dataset also contained duplicate transaction records. Duplicate rows were identified and removed to avoid double-counting sales values and quantities.
After cleaning, the dataset was reduced from 250 rows to 239 rows. The cleaned dataset was used for all analyses and visualisations

## Descriptive Statistics

### Sales Analysis by Product Category
<img width="1262" height="614" alt="image" src="https://github.com/user-attachments/assets/d54feb80-e7fb-4bb7-8ff5-0e9955ca719f" />

Insight 1: Fruits generated the highest revenue at 7,450.12, while Beverages, Stationery and Household products also contributed relatively strong and similar revenue levels. This shows that overall sales are mainly driven by high-frequency everyday purchases across multiple essential categories rather than a single dominant product line. However, Personal Care lags behind at 4,509.59, suggesting weaker demand or lower purchase frequency compared to other categories, which may require further investigation in pricing or product mix.

Business implication: The company should continue focusing on its strong-performing essential categories while looking into why Personal Care is underperforming, whether it is due to pricing, product appeal or lack of promotion.

### Sales Analysis by City
<img width="1060" height="568" alt="image" src="https://github.com/user-attachments/assets/516066e5-ff27-4a6a-8864-2f4ddba76f6f" />

Insight 2: Chicago and New York contributed the majority of revenue, at 10,813.94 and 10,613.69 respectively, showing strong and relatively balanced performance between the two key markets. In contrast, Los Angeles lagged behind at 8,935.31, indicating weaker market penetration or lower customer engagement in that region. This suggests the company should prioritize growth strategies in Los Angeles while leveraging Chicago and New York as stable revenue for sustained performance.

Business implication: While Chicago and New York act as stable revenue drivers, the company should prioritize improving performance in Los Angeles through targeted marketing, localized strategies or customer segmentation to achieve more balanced geographic growth.





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

Insight 1: Fruits generated the highest revenue at 7,450.12, accounting for approximately 24.5% of total sales. Beverages, Stationery, and Household products also showed relatively similar performance, indicating a balanced contribution across key essential categories. Personal Care recorded the lowest revenue at 4,509.59, creating a noticeable gap compared to other categories.

Business implication: This implies that growth can be achieved by adjusting the performance of existing product categories rather than restructuring the entire product portfolio.

### Sales Analysis by City
<img width="1060" height="568" alt="image" src="https://github.com/user-attachments/assets/516066e5-ff27-4a6a-8864-2f4ddba76f6f" />

Insight 2: Chicago and New York generated the highest revenue at 10,813.94 and 10,613.69 respectively, while Los Angeles ranked lower at 8,935.31. The small gap between Chicago and New York shows that both cities perform at a similar and consistent level as the company’s main markets.

Business implication: This indicates strong reliance on two core markets, while Los Angeles presents potential for improvement through targeted market strategies to balance overall geographic performance.

## Conclusion

Sales are relatively balanced across main product categories, with Chicago and New York performing strongest among cities. Overall, the business demonstrates stable performance, with potential for incremental improvement in weaker segments.




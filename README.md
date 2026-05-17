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

Among all product categories, Fruits generated the highest total sales revenue, reaching 7450.12. This suggests that fruit products were highly demanded by customers and contributed significantly to the company’s revenue. Nevertheless, Personal Care products recorded the lowest sales (about 4509.59), indicating lower customer demand compared to other categories.

### Sales Analysis by City
<img width="1060" height="568" alt="image" src="https://github.com/user-attachments/assets/516066e5-ff27-4a6a-8864-2f4ddba76f6f" />

Chicago generated the highest total sales among the three cities, slightly outperforming New York. This indicates that Chicago may represent the strongest market for the business. Additionally, Los Angeles recorded the lowest total sales, suggesting potential opportunities for marketing improvements or sales growth strategies in that region.




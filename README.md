# Sales-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/944b40d7-7117-4ab1-8517-0ea60d324f92/ReportSection?experience=power-bi

## Problem Statement

Develop an interactive dashboard to analyze and track online sales data from two CSV files: Orders and Details. The Orders file contains columns such as Order ID, Order Date, Customer Name, State, and City. The Details file contains columns such as Order ID, Amount, Profit, Quantity, Category, Sub-Category, and Payment Mode.

The dashboard should utilize complex parameters to allow users to drill down into specific worksheets and customize views using filters and slicers. Additionally, establish connections between the two files, join new tables, and perform calculations to manipulate data, enabling user-driven parameters for visualizations.

Implement various types of customized visualizations, including bar charts, pie charts, donut charts, clustered bar charts, scatter charts, line charts, area charts, maps, and slicers, to provide detailed insights into sales performance and customer behavior.

## Steps followed 

### Step_1. Data Loading: 
The sales data from the E-commerce platform was loaded into Power BI, including information such as order ID, product details, customer information, and sales amount.

### Step_2. Data Preparation: 
The data was cleaned and preprocessed to ensure accuracy and consistency. Missing values were handled, duplicates were removed, and data types were formatted as needed.

### Step_3. Data Modeling: 
A data model was created by establishing relationships between the different tables in the dataset, such as orders, products, and customers.

### Step_4. Dashboard Design: 
The layout of the dashboard was designed, including the selection of visuals and their placement. Key metrics and insights were considered for highlighting.

### Step_5. Visualizations: 
Various visualizations were created to represent the sales data, such as bar charts for sales by product category, line charts for trends over time, and pie charts for sales distribution.

### Step_6. Interactive Elements: 
Interactive elements such as filters, slicers, and drill-down capabilities were added to allow users to explore the data dynamically.

### Step_7. Key Metrics: 
Key metrics such as total sales, average order value, and sales growth rate were included to provide an overview of the sales performance.

### Step_8. Customer Segmentation: 
Customer data was used to segment customers based on their purchasing behavior, such as new vs. returning customers or high-value vs. low-value customers.

### Step_9. Performance Analysis: 
The performance of different product categories, customer segments, and sales channels was analyzed to identify areas for improvement.

### Step_10. Dashboard Publishing: 
The report was then published to Power BI Service for sharing with stakeholders.

![Publish_Messag](https://github.com/vsk07/Sales-Dashboard/assets/143631160/488e5a4f-9fe6-4a2b-83b7-d7e3884d5820)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/vsk07/Sales-Dashboard/assets/143631160/cba63b1d-92c2-408c-93c6-23ebacea8392)

# Report Snapshot (Power BI DESKTOP)

![DashBoard](https://github.com/vsk07/Sales-Dashboard/assets/143631160/8b76fcf4-9c60-4ffa-96a6-f9692527303e)


# insights:

### 1. Overview:
The dashboard provides a comprehensive view of online sales data, including quantity, profit, and amount metrics. It offers insights into payment modes, categories, sub-categories, monthly profits, top states by amount, and top customers by amount.

### 2. Payment Mode Analysis
- COD has the highest sum of quantity, indicating a preference for cash on delivery.
- UPI and Debit Card follow, with significant but lower quantities.
- Credit Card and EMI have the lowest quantities, suggesting room for growth in these payment modes.

![Sum of Quantity by Payment Mode](https://github.com/vsk07/Sales-Dashboard/assets/143631160/10beb24c-9e02-4d1a-a44c-f027c4d0100e)

### 3. Category Analysis

- Clothing dominates with the highest sum of quantity, followed by Electronics and Furniture.
- This indicates a higher demand for clothing compared to other categories.

![Quantity_Category](https://github.com/vsk07/Sales-Dashboard/assets/143631160/c391db1d-3f3f-43ce-872d-3d2e5a5d4613)

### 4. Sub-category Profit Analysis

- Printers and Bookcases have the highest sum of profits, indicating these are lucrative sub-categories.
- Saree and Accessories follow, suggesting potential areas for profit improvement.

![Sum of profit subCate](https://github.com/vsk07/Sales-Dashboard/assets/143631160/c175b755-19f9-4cf3-971d-bd7c8681b40d)

### 5. Monthly Profit Analysis

- January, March, and October show the highest profits, while May, June, and July show losses.
- This indicates seasonal trends and areas for profit optimization.

![Profit_Month](https://github.com/vsk07/Sales-Dashboard/assets/143631160/e3582bc3-ba4c-4d21-ac34-fea19a691994)

### 6. Top States by Amount

- Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi are the top states by amount.
- This highlights key markets for the business.

![Sum of amount_State](https://github.com/vsk07/Sales-Dashboard/assets/143631160/896e110d-28e2-41b2-94df-6ad9032ac767)

### 7. Top Customers by Amount

- Harivansh, Madhav, and Madan Mohan are the top customers by amount.
- Understanding their preferences and behaviors could help in customer retention and acquisition strategies.

![Sum of amount_Customer Name](https://github.com/vsk07/Sales-Dashboard/assets/143631160/86a3a7f1-81dd-4c06-bc7a-b49c60112fd6)

### 8. Overall Performance

- The total sum of amount and profit indicates the overall financial health of the business.
- The average order value (AOV) provides insight into the average spending per transaction.

![sum of quantity](https://github.com/vsk07/Sales-Dashboard/assets/143631160/ca71485b-f72b-422a-9333-b49c7b8baaa9)

![Sum of Amount](https://github.com/vsk07/Sales-Dashboard/assets/143631160/129918bc-0c79-4877-a822-1b71e6f1cce8)

![sum of profit](https://github.com/vsk07/Sales-Dashboard/assets/143631160/cb151dd1-fbcf-44ac-b1cb-40a3eec3ec06)

![Sum of AOV](https://github.com/vsk07/Sales-Dashboard/assets/143631160/4f31bef0-2ec5-40ff-8684-ff81afe063f1)

### 9. Filters

- Quarters, State, and Payment Mode filters allow for further exploration and analysis based on specific criteria.

### 10. Recommendations:

-     The company should focus on promoting online payment methods to reduce dependency on cash transactions.
-     Clothing is the most popular category, suggesting a strong demand for apparel products.
-     Printers and Bookcases are the most profitable sub-categories, indicating potential areas for further investment.
-     The company should analyze the reasons for losses in May, June, and July to identify areas for improvement.
-     Maharashtra, Madhya Pradesh, and Uttar Pradesh are key markets, requiring targeted marketing strategies.
-     The top customers should be provided with personalized offers to maintain their loyalty and increase sales.

# Conclusion:

The dashboard provides valuable insights for the business to enhance customer satisfaction, improve profitability, and optimize operations. By focusing on areas with potential for improvement, such as payment modes, sub-categories, and states, the business can drive growth and success.

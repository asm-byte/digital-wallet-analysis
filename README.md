# Digital-Wallet-Analysis
Analysis of digital wallet transactions using Excel


## 📊 Project Overview
This project involves a comprehensive analysis of an e-commerce/digital wallet transaction dataset. The goal is to derive insights into customer spending behavior, product performance, merchant relationships, and the financial efficacy of loyalty programs like cashback and points.

## 🛠️ Tools Used
- **Microsoft Excel:** Power Query, Pivot Tables, Pivot Charts, Formulas (XLOOKUP, SUMIFS), Dashboards

## 📁 Dataset Overview
Challenge: Track and analyze 5,000 transactions for 2023, 2024.

Solution: 
• Created dynamic PivotTable dashboards 
• Used conditional formatting to highlight key patterns and trends
The dataset contains transactions with the following key columns:
- `user_id`, `merchant_id`: Unique identifiers for customers and merchants.
- `product_category`, `product_name`: Details of the purchased items.
- `product_amount`, `Paid Amount`: The listed price and the final amount paid after fees/cashback.
- `transaction_fee`, `cashback`, `loyalty_points`: Financial and loyalty metrics.
- `payment_method`, `transaction_status`, `device_type`, `location`: Contextual information about the transaction.

## 🔍 Analysis & Key Insights

### 1. 📈 Overall Business Performance
*   **Total Sales Volume:** from  successful transactions.
*   **Average Transaction Value
*   **Total Fees Collected
*   **Total Cashback Given

### 2. 👥 Customer Behavior Analysis
*   **Top Spenders:** Identified the top 5 users by total `Paid Amount`.
*   **Customer Segmentation:** Grouped users based on spending habits (e.g., frequent small purchases vs. occasional large ones) using Pivot Tables.

### 3. 🏪 Merchant Performance
*   **Key Partners:** Ranked merchants by total sales volume and number of transactions.
*   **Most Profitable Partnerships:** Analyzed which merchants generate the most `transaction_fee` revenue.

### 4. 📊 Product & Category Analysis
*   **Best-Selling Categories**
*   **Product Performance** 
### 5. 💳 Payment & Loyalty Program Efficacy
*   **Preferred Payment Method**
*   **Loyalty Program Cost** 

### 6. 🌐 Geographical & Device Trends
*   **Location Trends**.
*   **Device Usage**

## 📋 Excel Dashboard Features
The interactive dashboard provides filters for:
- **Date Range** (`transaction_date`)
- **Product Category**
- **Merchant Name**
- **Location**
Key metrics update dynamically to show:
- Total Sales, Fees, and Cashback
- Trends over time (Line Chart)
- Top Merchants and Product Categories (Bar Charts)


## 🧠 Conclusion & Strategic Recommendations
1.  **Double Down on Top Categories:** Increase marketing and stock for the top-performing product categories (**\[Category Name\]**).
2.  **Merchant Incentives:** Create tiered partnership programs for top merchants (**\[Merchant Name\]**) to further increase sales volume.
3.  **Optimize Loyalty Program:** The cashback program is effective at driving volume. Consider offering bonus points for using the `[Most Profitable Payment Method]` to steer user behavior.
4.  **Mobile-First Strategy:** Since most users are on `[Device Type]`, ensure the app and checkout process are optimized for that platform.

## 🔗 How to Explore This Project
1.  Download the file from this repository.
2.  Open it in Microsoft Excel.
3.  Interact with the Pivot Table filters and charts on the dashboard to explore the data yourself!

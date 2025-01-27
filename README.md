# CoffeeSalesDashboard

This analysis examines coffee sales performance using data from Orders, Customers, and Products tables in Excel. Key insights reveal trends in sales, customer behavior, product preferences, and loyalty card usage. By cleaning, transforming, and integrating data, actionable findings were derived to enhance understanding of market demand and customer purchasing patterns.

![image](https://github.com/user-attachments/assets/7612e23a-f7ed-4307-8961-e69bc8bfed12)


## Key Insights:
1.The month with the highest sales is September, which coincides with the holiday season.

2.The country with the highest sales per capita is the United States.

3.The most popular coffee type is Arabica, which is also the most expensive.

4.Loyalty card holders spend more on average than non-loyalty card holders.

### 1.Overall Sales Trend:
Total sales have been increasing steadily from January to December, with a significant spike in September.
This suggests strong demand for coffee throughout the year, particularly during the holiday season.

### 2.Sales by Country:
The United States has the highest sales volume, followed by India and Germany.
This indicates a global market for coffee, with significant demand in these three countries.

### 3.Sales by Size:
10kg bags are the most popular size, followed by 25kg and 0.5kg bags.
This suggests that customers prefer larger quantities of coffee, possibly for commercial or bulk purchases.

### 4.Sales by Coffee Type:
Arabica is the most popular type of coffee, followed by Robusta and Liberica.
This indicates a preference for high-quality Arabica beans among consumers.

### 5.Sales of the Individual:
Al Parinds is the top-selling individual, followed by Rov Der and Jan Feb Mar Apr May.

### 6.Loyalty Card Usage:
More customers have loyalty cards than do not.
This suggests that loyalty programs are effective in encouraging repeat purchases.

## Analysis process
In this analysis, I leveraged data from three key tables: Orders, Customers, and Products, to gain valuable insights into the coffee sales performance. The primary focus was on understanding customer purchasing behavior, product preferences, and overall sales trends.

### 1.Data Cleaning and Transformation:
The Orders table was first cleaned and preprocessed to ensure accurate analysis, removing any duplicate records or inconsistencies. Various functions were applied to normalize and filter the data, enabling more efficient analysis.

### 2.Customer Analysis:
Using the XLOOKUP function, customer-related information such as Name, Email, and Country were extracted from the Customers table. This allowed us to link customer demographics with their purchase history for a more targeted analysis of customer behavior.

### 3.Product Insights:
Data from the Products table was integrated into the analysis using the INDEX-MATCH function. This provided insights into key product details such as Coffee Type, Roast Type, Size, Unit Price, and Loyalty Card Usage.
By matching these details with the respective orders, I was able to identify top-performing coffee products, evaluate price sensitivity, and understand which product variants (e.g., size, roast) are most preferred by customers.

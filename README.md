# Data Cleaning - EDA on Retail Dataset
Exploratory Data Analysis (EDA) is a critical step in understanding and analyzing any retail dataset. Here are several reasons why conducting EDA on a retail dataset is beneficial:

Understand the Data Structure:
EDA helps you gain a comprehensive understanding of the structure of the retail dataset. You can explore the number of rows and columns, data types, and overall data distribution.

Identify Missing Values:
EDA allows you to identify missing values in the dataset. Knowing where data is missing is crucial for making informed decisions about data imputation or handling missing values appropriately.

Detect Outliers:
Outliers can significantly impact analysis and modeling. EDA helps identify and understand outliers in the retail data, enabling you to decide whether to remove or handle them in a specific way.

Support Decision-Making:
EDA provides valuable insights that can inform business decisions. For example, it might help optimize pricing strategies, inventory management, or marketing campaigns.

In summary, conducting EDA on a retail dataset is essential for gaining insights, addressing data quality issues, and making informed decisions. It sets the foundation for subsequent data modeling and analysis tasks, enabling more accurate and meaningful results.

**Questions Answered**
1. Check if all order_id is unique or not to confirm if there are any duplicates in the orders.
2. Confirm the warehouses that are closest to customers.
3. Confirm that the order_totals (after all discount and delivery charges are applied) are correct or there is some problem with the totals. If there are errors in the totals, fix it.
4. Check for outliers in the order_total column and get the Inter Quartile Range (IQR).
5. Remove all outliers from the dataset, displaying only regular records.
6. Analyze customer satisfaction percentage.

# **Sales Data Analysis**

### **1. Project Overview**

This project analyzes sales data from multiple monthly reports. The dataset is merged, cleaned, and analyzed to extract valuable insights on sales trends, product performance, and customer behavior.

### **2. Dataset**

The dataset consists of 12 months of sales data stored in CSV files. Each file contains the following columns:

Order ID: Unique identifier for each transaction

Product: Name of the product sold

Quantity Ordered: Number of units sold

Price Each: Price per unit

Order Date: Timestamp of the order

Purchase Address: Address where the order was placed


### **3. Installation & Setup**

Install the required Python libraries:

pip install pandas matplotlib seaborn

Ensure that all monthly sales files are in the Sales_Data directory.



### **4. Data Processing Steps**

Merging Data: Combine 12 months of sales data into a single file (all_data.csv).

Cleaning Data: Handle missing values, incorrect data formats, and duplicate entries.

Data Transformation: Extract new features like Month and City from existing columns.

### **5. Analysis & Insights**

Best-Selling Products: Identify top-selling products by quantity and revenue.

Sales Trends: Analyze sales performance across different months and locations.

Customer Behavior: Understand purchasing patterns based on order timestamps.

### **6. Visualization**

Bar charts and line plots to illustrate sales trends

Heatmaps to highlight sales concentration in different regions

### **7. Results & Findings**

Peak sales occur in December, possibly due to holiday shopping.

Certain products have high cross-selling potential (e.g., phone chargers and iPhones).

Specific cities contribute significantly to overall sales.

### **8. Future Enhancements**

Implement machine learning models for sales forecasting.

Automate data processing with scheduled scripts.

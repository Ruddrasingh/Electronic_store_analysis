# Electronic store analysis  [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

Using Python, Pandas & Matplotlib i explore 12 months’ worth of sales data from an electronics store. The dataset includes information on purchases broken down by month, product type, cost, and purchase address. As a data analyst, our goal is to uncover insights and answer key business questions.
### Data Overview

Overview of the sales data used for analysis. It includes details on purchases, product types, costs, and other relevant information

![App Screenshot](https://snipboard.io/31niNx.jpg)
### Data Preparation

To facilitate comprehensive analysis, I merged the individual CSV files representing each month’s sales data into a single CSV file. This allows for seamless analysis of all 12 months’ worth of data in one go.

![image](https://github.com/user-attachments/assets/850d36e9-8eed-45fb-9b9a-7cf53bdf1c87)

**Data Cleaning**

- Removed missing values (NaN) from the dataset.

![image](https://github.com/user-attachments/assets/f96bbdee-355d-463e-bda7-9bc35b714838)

- Converted columns to appropriate data types.

![image](https://github.com/user-attachments/assets/cee29e3f-439e-480f-ab64-6cdb5f020c7e)

- Filtered out rows based on conditions. During this process, I encountered some errors and discovered that some column names were repeating as rows in the data.

![image](https://github.com/user-attachments/assets/69a3a057-3aaf-44fe-a98e-1226dcd45879)

- Added some additional columns.

![image](https://github.com/user-attachments/assets/136bc0a7-1542-444b-9ba0-3d078a63b174)

**Business Questions Explored**
 After preparing the data, I explored several key business questions to uncover valuable insights:

#### What was the best month for sales? How much was earned that month?

![image](https://github.com/user-attachments/assets/43f8dc4f-5fe6-4f01-85fe-325f5d44780f)

Explanation: The chart shows the total sales for each month. The highest sales were recorded in December, with total earnings of over $4 million. This indicates that December was the best month for sales, likely due to the holiday season driving higher consumer spending.

#### What city sold the most products?

![image](https://github.com/user-attachments/assets/7fd075d5-220d-4f81-beb7-b18250f8a9a5)

Explanation: The chart illustrates the total sales for various cities. San Francisco (CA) had the highest sales, reaching close to $8 million. This indicates that San Francisco is a key market for the electronics store.

#### What time should we display advertisements to maximize the likelihood of customers buying products?

![image](https://github.com/user-attachments/assets/051131fe-d0f4-46d2-b058-966852bf4c2b)

Explanation: The chart shows the number of orders placed at different hours of the day. The data indicates two peak periods: around 12 (12 pm) and late 19 (7 pm). To maximize the likelihood of customers buying products, advertisements should be displayed during these peak hours when customer activity is highest.

#### What products are most often sold together?

![image](https://github.com/user-attachments/assets/c8119e65-8daa-4f7b-85a0-d27a106e6bcd)

Explanation: The table lists the combinations of products that are most frequently sold together. The most common combination is the iPhone and Lightning Charging Cable, with 1001 occurrences. This suggests that customers often purchase these items together.

#### What product sold the most? Why do you think it sold the most?

![image](https://github.com/user-attachments/assets/598d2773-c736-4891-aec8-69bea961f9cb)

Explanation: The chart shows the quantity ordered and the average price for various products. AA and AAA batteries had by far the most quantity sold because they were cheaper. This affordability likely drove their high sales volume, as they are essential for many electronic devices.

**To tackle these questions, I explored various methods in pandas and matplotlib. Here’s a rundown of the techniques I used:**

- String Manipulation: By parsing cells as strings with the .str accessor, I created new columns from existing data.

- Applying Functions: I utilized the .apply() method to perform custom operations on DataFrame elements.

- Aggregating Data: Using groupby, I conducted aggregate analysis to summarize the data effectively.

- Visualizing Results: I plotted bar charts and line graphs to visualize the results, making the data insights more accessible.

- Labeling Graphs: I ensured that all graphs were properly labeled for clarity.

- Joining Data: Using .join to combine DataFrames.

- Accessing Data: Using .get to safely access data.

- Date Manipulation: Working with datetime for date-related operations.

- Splitting Strings: Using split() to break down strings into meaningful parts.

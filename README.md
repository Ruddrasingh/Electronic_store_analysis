
# Electronic Store Sales Analysis [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

Using **Python**, **Pandas**, and **Matplotlib**, I analyzed 12 months of sales data from an electronics store. The dataset provides insights into purchases by month, product type, cost, and purchase location. The aim of this analysis is to uncover key business insights and provide actionable recommendations.

## 1. Background and Overview

**Fictional Electronics Store Analysis:**
This analysis is based on a fictional dataset representing 12 months of sales data from an electronics store. The dataset includes details such as product types, purchase amounts, locations, and times. The goal is to extract valuable insights that can address key business challenges and improve sales performance.

**Key Areas of Focus:**
**Monthly Sales Performance:** Identify the top sales months and key drivers behind peak periods, like seasonal demand or promotions.

**City-Level Sales Insights:** Analyze sales by city to pinpoint key markets and target marketing efforts.

**Optimal Advertisement Timing:** Determine the best times to display ads based on peak purchase hours.

**Frequently Purchased Product Combinations:** Uncover common product pairs to explore bundling or cross-promotion opportunities.

**Top-Selling Products:** Identify best-selling products and understand their success factors (e.g., price, demand).
## 2. Data Structure Overview

The dataset used for this analysis contains monthly sales data with information on:
- Purchase date and time
- Product type and cost
- Purchase location (city, state)
- Sales volume

![Data Overview](https://snipboard.io/31niNx.jpg)

### Data Preparation:
- Combined individual CSV files for each month into a single dataset to facilitate holistic analysis.
- Cleaned the data by removing missing values, correcting data types, and resolving errors like duplicate column names.

![Data Cleaning](https://github.com/user-attachments/assets/cee29e3f-439e-480f-ab64-6cdb5f020c7e)

## 3. Executive Summary

**Key Business Questions Answered:**
- What was the best month for sales? How much revenue was generated that month?
- Which city recorded the highest sales?
- At what time should advertisements be displayed to maximize purchases?
- What product combinations are frequently purchased together?
- Which product sold the most, and why?

## 4. Insights Deep Dive

**Best Month for Sales:**
December was the highest-performing month with over $4 million in sales, likely driven by holiday season demand.

![Monthly Sales](https://github.com/user-attachments/assets/43f8dc4f-5fe6-4f01-85fe-325f5d44780f)

**Top City for Sales:**
San Francisco had the highest sales, with nearly $8 million in revenue.

![City Sales](https://github.com/user-attachments/assets/7fd075d5-220d-4f81-beb7-b18250f8a9a5)

**Optimal Advertisement Timing:**
The busiest shopping hours were around **12 PM** and **7 PM**, suggesting these times are optimal for displaying advertisements.

![Ad Timing](https://github.com/user-attachments/assets/051131fe-d0f4-46d2-b058-966852bf4c2b)

**Popular Product Combinations:**
The most common product combination was the **iPhone** and **Lightning Charging Cable**, with 1001 occurrences.

![Product Combinations](https://github.com/user-attachments/assets/c8119e65-8daa-4f7b-85a0-d27a106e6bcd)

**Top Selling Product:**
Batteries (AA and AAA) sold the most units, driven by their lower price points and essential usage for many devices.

![Top Product](https://github.com/user-attachments/assets/598d2773-c736-4891-aec8-69bea961f9cb)

## 5. Recommendations

**1. Maximize Sales During Peak Hours:**
- Run targeted advertising campaigns around **12 PM** and **7 PM** to capture peak customer attention.

**2. Highlight Best-Selling Product Combinations:**
- Bundle products like the **iPhone** and **Lightning Charging Cable** for promotional offers, as customers frequently buy these together.

**3. Focus on Affordability:**
- Increase marketing efforts for lower-priced, essential products like **batteries**, which have the highest sales volume.

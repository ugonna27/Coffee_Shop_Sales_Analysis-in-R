PROJECT OVERVIEW

This project analyzes transactional sales data from a multi-location coffee shop business using R. The objective is to uncover customer purchasing patterns, identify top-performing products and locations, evaluate sales trends over time, and generate actionable recommendations that support revenue growth and operational efficiency.

The analysis follows a complete data analytics workflow including:

1. Data collection and preparation
2. Data cleaning and transformation
3. Exploratory Data Analysis (EDA)
4. Product performance analysis
5. Store performance analysis
6. Time-based sales analysis
7. Business recommendations

Business Problem

Coffee shop management wants to better understand customer purchasing behavior across multiple locations.

Key questions addressed include:

A. Which products generate the highest revenue?
B. Which locations perform best?
C. What days and times generate the most sales?
D. Are there seasonal sales patterns?
E. How can the business improve profitability and customer retention?

Dataset

The dataset contains transactional sales records collected from multiple coffee shop locations.

Key Fields:
Transaction Date,
Transaction Time,
Store Location,
Product Category,
Product Name,
Quantity Sold,
Unit Price,
Net Sales,
Discounts

The dataset was cleaned and transformed using R before analysis.

PACKAGES USED:
Tidyverse(
dplyr
ggplot2
lubridate)

DATA PREPARATION:
The following data preparation steps were performed:
1. Checked for inconsistencies
2. Created additional column for Sales using Unit Price * Quantity Sold
3. Also, extracted the date from the datetime field.

ANALYSIS PERFORMED

1. Product Performance Analysis
-Identified highest revenue-generating categories
-Identified top-selling products
-Compared category performance across locations

2. Store Performance Analysis
-Evaluated sales by location
-Compared transaction volume and revenue generation
-Measured profitability differences between stores

3. Customer Purchase Behaviour
-Analyzed purchasing patterns by day of week
-Examined transaction frequency
-Evaluated average transaction value

4. Time-Based Analysis
-Revenue trends by month
-Sales trends by weekday
-Seasonal purchasing behaviour

5. Revenue Analysis
-Total sales by category
-Revenue contribution by store
-High-value product identification

KEY INSIGHTS
Store Insigts
-Hell's Kitchen brought in the most overall sales followed by Astoria and Lower Manhattan
-
# Product Insights
-the Gourmet Brewed coffee in the Coffee category sells the most cups followed by Barista Espresso, the least being "Premium
Brewed Coffee"

-Coffee and Tea are the most popular categories by quantity, followed by Bakery and 
Drinking Chocolate

# Seasonal Insights
-June saw the highest sales revenue followed by May, more than double the revenue in January. Also, if Coffee is being sold more in Summer months, it's possible that there is a potential to bring in more revenue in January. This can be done through seasonal products and promotions, and it also has the benefit of raising customer engagement. The company can look into introducing new products or promoting already existing products.

- There is an upward trend of increase in the revenue from January to June with the exception of February that saw a decrease from the previous month. Further investigation can be carried out to uncover the reason for the decline.

- Weekday Sales bring in more revenue than Weekend Sales. Though this is expected since the majority of the stores' customers are working class individuals. They may look into attracting customers on the weekend, for example through Loyalty programs. They can also take advantage of events nearby on the weekend to increase sales.

- Weekend sales can also be increased through weekend discounts. Other kinds of discounts can be introduced, where customers buy something during the week and get a discount on their purchase on the weekend.

- They can also take advantage of events happening over the weekend to sell to more customers.

# OTHER STRATEGIC BUSINESS INSIGHTS

# Revenue concentration risk
A large percentage of revenue comes from a small number of products. The business may be vulnerable if demand for those products declines.
# Store-specific product preferences
Customer preferences vary by location. Product assortment should be localized rather than standardized across all stores.


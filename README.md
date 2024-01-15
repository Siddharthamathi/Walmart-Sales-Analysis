**Walmart Sales Data Analysis**

This project aims to explore Walmart Sales data to understand top-performing branches and products, sales trends of different products, and customer behavior. The aim is to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transactions from three different branches of Walmart, respectively located in Mandalay, Yangon, and Naypyitaw. The data contains 17 columns and 1000 rows.

**Analysis Carried Out**

**1. Product Analysis**

Analyze the data to understand the different product lines, the product lines performing best, and the product lines that need to be improved.

**2. Sales Analysis**

This analysis aims to answer the question of the sales trends of products. The result of this can help measure the effectiveness of each sales strategy the business applies and what modifications are needed to gain more sales.

**3. Customer Analysis**

This analysis aims to uncover the different customer segments, purchase trends, and the profitability of each customer segment.

**Approaches Employed**

**1. Data Wrangling**: This is the first step where data inspection is done to ensure NULL values and missing values are detected and data replacement methods are used to replace missing or NULL values.

      (I) Build a database.
      
     (ii) Create a table and insert the data.
     
    (iii) Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.
    
**2. Feature Engineering**: This will help generate some new columns from existing ones.

      (i) Add a new column named 'time_of_day' to give an insight into sales in the morning, afternoon, and evening. This will help answer the question of which part of the day most sales are made.
      
     (ii) Add a new column named 'day_name' that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question of which week of the day each branch is busiest.
      
    (iii) Add a new column named 'month_name' that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). This helps in determining which month of the year has the most sales and profit.
      
**3. Exploratory Data Analysis (EDA)**: Exploratory data analysis is done to answer the listed questions and aims of this project.

**Business Questions** 

**General Question**

1. How many unique cities does the data have?

2. In which city is each branch?
   
**Product-related Questions**

1. How many unique product lines does the data have?

2. What is the most common payment method?

3. What is the most selling product line?

4. What is the total revenue by month?

5. What month had the largest COGS?

6. What product line had the largest revenue?

7. What is the city with the largest revenue?

8. What product line had the largest VAT?

9. Fetch each product line and add a column to those product lines showing "Good", and "Bad" (Good if it's greater than average sales).

10. Which branch sold more products than the average product sold?

11. What is the most common product line by gender?

12. What is the average rating of each product line?

**Sales**

1. Number of sales made at each time of the day per weekday

2. Which of the customer types brings the most revenue?

3. Which city has the largest tax percentage/ VAT (Value Added Tax)?

4. Which customer type pays the most in VAT?

**Customer**

1. How many unique customer types does the data have?

2. How many unique payment methods does the data have?

3. What is the most common customer type?

4. Which customer type buys the most?

5. What is the gender of most of the customers?

6. What is the gender distribution per branch?

7. Which time of the day do customers give the most ratings?

8. Which time of the day do customers give the most ratings per branch?

9. Which day fo the week has the best avg ratings?

10. Which day of the week has the best average ratings per branch?


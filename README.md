# **Sales & Product Performance Analysis on Fast Card Supermarket**
---

![Image](https://github.com/user-attachments/assets/d5ecb699-d139-4142-bced-09675e2f4ea4)

## **Table of Content**
 - [Project Overview](#project-overview)
 - [Introduction](#introduction)
 - [Data Source](#data-source)
 - [Data Cleaning](#data-cleaning)
 - [Methodologies](#methodologies)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Notable Trends and Patterns](#notable-trends-and-patterns)
 - [Recommendation](#recommendation)

### **PROJECT OVERVIEW**
---

The dataset from January to March 2019 shows sales transactions across various product categories, store locations, and customer behaviours for Fast Card supermarket. The data analysis project seeks to review the sales and product performance of the supermarket while uncovering insights to increase profitability.

## **INTRODUCTION**

**What if data could help Business Owners sell smarter and stock better?**

Fast Card Supermarket has been growing fast. But lately, things aren’t adding up. Sales are dropping in some branches. Some products are flying off the shelves, others just sit there. They run promos, but don’t even know if they’re working.
They have the data, sales numbers, inventory lists, and customer ratings, but it’s all over the place, and they’re not really using it. This project was created to fix that.

We looked at product performance, sales across different locations, which days sell best, and whether those promos are even helping.
The goal is simple: help Fast Card know what’s working, what’s not, and where they can grow,  by uncovering trends, pinpointing top products generating the highest revenue, identifying store locations with the highest sales performance, and evaluating revenue metrics to support data-driven decisions within the business.

### **DATA SOURCE**
The primary dataset used for this analysis was already imported to the excel file, containing detailed information about each sale made by the company.

## **DATA CLEANING STEPS TAKEN**
I opened the dataset in Excel and cleaned it up step by step to get it ready for proper analysis. Here's what I did:

1. First, I checked for duplicate rows using the Remove Duplicates tool. Luckily, there were none.
2. I made sure all dates looked the same by formatting the date column properly.
3. All payment-related columns like Unit Price, Revenue, Tax, and Revenue Including Tax were formatted to currency so everything looked neat and was easy to compare.
4. I removed columns that weren’t useful for this project, like Branch, Time, and I renamed some columns to make them clearer. 
5. I checked for any blank cells using filters, and no blanks were found.
6. I used the TRIM function on text columns to clean out any extra spaces. For number columns, I used Find and Replace to clear spaces as well.
7. For the Rating column, which had decimals, I used the ROUND function to convert them to whole numbers. Then I created a new column called Group Rating and grouped the ratings into Poor, Average, and Good.
8. I also cleaned and categorized Gender, Customer Type, and Rating using simple IF formulas to make analysis easier.
9. Finally, I used the PROPER function to clean up text formatting in columns like Store City and Payment Method, so each word starts with a capital letter.
10. After cleaning each column, I copied and pasted the results as values so everything stayed clean and organized in the final dataset
 
## **METHODOLOGIES**
To better understand the sales performance and customer patterns in this dataset, I used a few helpful Excel approaches:

1. Pivot Tables helped me break down the data by product category, store city, customer type, and payment method. This made it easier to spot trends in revenue, product popularity, and buying behavior.
2. I created different Charts and Graphs (like bar charts, column charts, and pie charts) to make the data easier to read and compare. These visuals helped show how each store and product category was performing, and how customer types and payment methods affected sales.
3. 
These methods made it easier to analyze everything clearly and spot what was working and what needed attention.

## **EXPLORATORY DATA ANALYSIS**
**OBJECTIVES**

The goal of this analysis is to answer key business questions and provide useful insights to help Fast Card Supermarket make smarter decisions. Some of the questions explored in this report include:

1. Which product categories bring in the most revenue?
2. Which store branch performs best in terms of total sales?
3. What are the top-selling products in each branch?
4. Which customer types (Member or Normal) generate the most sales?
5. How do payment methods impact total revenue?
6. Which month generated the highest revenue?
7. What’s the average rating for each product category?
8. How do male and female customers differ in their buying patterns?
9. Are there patterns between customer ratings and revenue?

## **NOTABLE TRENDS AND PATTERNS**
**KEY METRICS**

1. Fast Card Supermarket recorded a total revenue of $307,590 from January to March 2019.
2. A total of 5,510 items were sold across all branches during the 3 months.
3. The Naypyitaw store had the highest sales, bringing in $105,300 in total revenue.
4. January was the best-performing month in terms of revenue.
5. The Food and Beverages category led in sales, generating $53,470 in total revenue.
6. The most revenue-generating payment method was Cash, followed by E-wallet and Credit Card.
7. Member customers (with subscription) spent more than Normal customers, contributing to the highest revenue generated.
8. Female customers slightly outspent Male customers in overall revenue contribution.
9. The average customer rating across all stores was 7 out of 10, with most falling in the "Good" category.
10. Products in the Fashion Accessories and Food and Beverages categories had some of the highest average ratings.
11. Yangon had the lowest revenue among the three cities, with a total of $97,467.

### **RECOMMENDATION**

Based on the above analysis, we recommend the following sections;
 1. Setting benchmarks and performance targets for each branch while reviewing its operating expenses regularly.
 2. Negotiate better prices or payment terms with suppliers to reduce the cost of goods sold.
 3. Purchase materials in bulk to take advantage of volume discounts.
 4. Focus on high-margin products and consider discontinuing low-margin ones.
 5. Have SMART detailed action plans for each strategy.
 6. Enhance customer service by training employees on customer service best practices like resolving issues promptly and effectively.
 7. Source high-quality products and conduct regular quality checks to improve product quality. 
 8. Maintain transparency and showcase positive customer testimonials and reviews to build brand reputation
 9. Have a user-friendly website or app with fast and reliable delivery service, and easy return and exchange policies.
 10. Adopt Digital Payment Methods as they provide valuable data that can be analyzed for insights into customer behavior, purchasing patterns, and payment preferences.
 11. Also we recommend conducting surveys while continuously monitoring payment trends and adapting to new technologies and customer preferences as they evolve.
 12. Regularly review progress against objectives and adjust strategies as needed.



















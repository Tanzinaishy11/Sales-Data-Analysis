# Sales-Data-Analysis 
Data Analysis Project for improving customer experience by analyzing the sales data and increasing sales.

# Objective: 
The primary objective of the Sales Analysis Project is to gain comprehensive insights into the company's sales data, understand customer behavior, and identify opportunities for business growth. The project aims to analyze various facets of sales, including demographic trends, purchasing patterns, and regional variations, to inform strategic decision-making.

# Data Source: 
The primary dataset use for this analysis is the "Sales_analysis.csv" file which contains information about customers and products.

# Tool:
Python

# Data Cleaning And wrangling :
1. Data Loading and inspection
2. Checking the shape of dataset
3. Checking the column name and information
4. Dropping the null columns
5. Finding and dropping null values
6. Changing data types

# Exploratory Data Analysis and Visualization:
1. Demographic Analysis:
- Explore the age distribution of customers to understand the target demographic.
- Analyze the gender distribution to identify the company's customer base.

2. Purchasing Behavior:
- Investigate the average number of orders per customer to gauge purchasing frequency.
- Examine the 'Amount' column to assess the financial dimension of transactions.

3. Customer Segmentation:
- Segment customers into categories such as "Frequent," "Repeat," and "One-Time" to tailor marketing strategies.

4. Regional Analysis:
- Evaluate sales performance across different regions to identify geographic trends.
- Compare total sales and average sales per transaction to discern regional variations.

5. Product Category Insights:
- Identify top-performing product categories based on sales revenue.
- Analyze the popularity of product categories among different customer segments.

6. Customer Retention:
- Calculate the customer retention rate to measure loyalty and repeat business.

7. Recommendations and Strategies:
- Provide actionable recommendations to enhance sales revenue and customer experience.
- Propose strategies for product diversification, targeted marketing, and regional optimization.

8. Visualizations and Reporting:
- Utilize data visualizations, including charts and graphs, to present key findings.
- Generate a comprehensive report summarizing insights and actionable strategies.

# Result/Findings:
1. Demographic Insights:
- The majority of customers are around 35 years old, with the age range of 27 to 43 being most prevalent.
- The average number of orders per customer is approximately 2, with a range from 1 to 4.
- The average transaction amount ('Amount' column) is 9453.61.

2. Gender Distribution:
The majority of customers are female, comprising 7832 individuals, while males constitute 3407.

3. Purchasing Power:
Females contribute significantly more to total sales compared to males. The 'Amount' column indicates a higher purchasing power among females.

4. Age Distribution:
- Around 7406 customers fall into the "Young" category (age range: 12-38). They spend a total amount of 69206761 on shopping.
- Approximately 3526 customers are classified as "Middle-Aged" (age range: 39-65).  They spend a total amount of 34074033 on shopping.
- Fewer customers are categorized as "Old" (age range: 66-92). They spend a total amount of 2968335 on shopping.
- Young people spend more money on shopping.

5. Purchase Frequency Distribution:
- The Purchase Frequency Distribution chart indicates that the majority of customers make 6 or more purchases.
- On average more than 50% of customers buy 6 - 13 items. there are very few people who did a time purchase
- The Customer Retention Rate is exceptionally high at 99.84%, suggesting strong repeat customer behavior.
- Retention percentage indicates the proportion of customers who made repeat purchases relative to the total number of unique customers in the dataset. In this case, a retention rate of 99.84% suggests that a very high percentage of customers have made more than one purchase. A high retention rate is generally considered positive for business performance. It indicates that a significant majority of customers are making repeat purchases, which is essential for sustained revenue. A high retention rate is associated with a higher customer lifetime value, indicating that customers are likely to contribute more revenue over the long term.

6. Customer Segmentation:
- After doing segmentation, we find that there are 5538 frequent purchase Customers, 2893 repeat purchase customers and 2808 one-time purchase customers.
- The segmentation into "Frequent," "Repeat," and "One-Time" customers enables targeted marketing strategies for each segment. It allows for the development of targeted marketing strategies for each customer segment. Frequent customers may receive loyalty rewards, repeat customers might get targeted promotions, and efforts can be made to convert one-time customers into repeat customers.

7. Top Performing Product Categories:
- The top 5 performing product categories are Food, Clothing & Apparel, Electronics & Gadgets, Footwear & Shoes, and Furniture.
Product Category         Total Revenue
Food                     33933883
Clothing & Apparel       16495019
Electronics & Gadgets    15643846
Footwear & Shoes         15575209
Furniture                 5440051

8. Regional Analysis:
- Delhi has the highest total sales, while Haryana has the highest average sales per transaction.
- Delhi : Delhi has a large number of transactions, resulting in a substantial total sales figure. This might be due to a large population or high market demand. Despite the high total sales, the average value per transaction in Delhi is lower. This could be because there's a diverse customer base with varying spending capacities, including budget-conscious consumers.
 Haryana : Even though Haryana has a smaller total sales figure, the average value per transaction is higher. This indicates that customers in Haryana, on average, are willing to spend more money per purchase.The total sales in Haryana might be lower due to a smaller number of transactions compared to Delhi. However, each transaction is more valuable.
- The sales distribution graphs reveal variations in purchasing patterns across different regions.
- Food is the highest-selling product and total sale of food is highest in Uttar Pradesh.

9. State with Highest Transactions:
- Uttar Pradesh state is showing the highest transaction . It indicates a significant demand for products or services in Uttar Pradesh. It Reflects active engagement of consumers in buying and willingness to make purchase. It represents an opportunity for businesses to tap into the market potential in Uttar Pradesh.

10. Gender-Based Purchasing Ratio:
- The Transaction Count by Product Category for Male and Female provides insights into purchasing preferences.

11. Most Popular Product Category:
- Clothing & Apparel emerges as the most popular product category among both male and female customers.

12. Revenue vs. Popularity Dynamics:
- Food is the highest-selling category by revenue, while Clothing & Apparel is the most popular in terms of transaction frequency.
- Pricing Dynamics: Food items may have a higher individual cost, contributing to higher total sales, while clothing items may be more affordable but purchased more often.

# Strategies for Improvement:
According to revenue Food is the highest selling catagory where Clothing and apperal is the popular product in case of transaction frequency.In this case improving the customer experience can be approached strategically.

Cloth: If the sales volume for clothing is high but the revenue generated is not as high as food, it indicates that clothing items may have a lower average transaction value. To improve the sales revenue of clothing, company can implement various strategies: 
1. Introduce premium or higher-priced clothing items to increase the average transaction value. This can attract customers looking for exclusive or higher-quality products.
2. Introduce limited-time promotions or discounts for specific clothing items or collections. Creating a sense of urgency can prompt customers to make quicker purchase decisions
3. Collaborate with other brands or influencers to create exclusive partnerships. Joint ventures can attract a wider audience and position the clothing brand as premium. 
4. Introduce seasonal collections with limited availability. Create anticipation and demand for new and unique clothing items that are only available for a limited time.
5. Provide an exceptional customer experience, including excellent customer service, fast shipping, and hassle-free returns. A positive overall experience can justify higher spending on clothing.

Food: If the sales revenue for food is high, indicating a higher average transaction value, but the sales volume is lower compared to clothing, there are strategies company can implement to improve both sales revenue and popularity of food items: 
1. Introduce a wider variety of food items to attract a broader customer base. Include popular and trending items to increase the appeal of the food category.
2. Create special bundles or meal deals that encourage customers to purchase multiple food items together. Bundles can provide value for money and increase the average transaction value 3. Introduce seasonal or holiday-themed food promotions. Offer special items or packages during holidays and events to capitalize on increased demand.
3. Identify the reasons of low sell in states like Rajasthan, kerala , Bihar. Collect customer feedback to understand their necessity of food items. It can increase the sell also the revenue.

# Recommendations:
- Implement targeted marketing campaigns based on customer segmentation.
- Enhance the online shopping experience with improved UI/UX.
- Diversify the food product range and introduce premium clothing items.
- Explore collaborations and partnerships for exclusive offerings.
- Monitor and address regional variations in purchasing behavior.

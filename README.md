# Olist Store Sales Analysis

## 🏆 Overview
This project presents a comprehensive sales analysis of Olist, focusing on customer metrics, delivery performance, payment trends, and overall sales data. The analysis is performed using Excel, supported by visual dashboards to uncover valuable insights. Through this project, we aim to assist Olist in improving operational efficiency, understanding customer behavior, and optimizing payment methods.

---

## 📝 Introduction
Olist is an online marketplace that connects sellers to customers across Brazil. With thousands of transactions happening every day, understanding the sales patterns, delivery timelines, and customer reviews is crucial for scaling the business. This project uses data from Olist to conduct a detailed analysis of sales trends, customer satisfaction, and payment behaviors.

The project leverages Excel to visualize key metrics and trends, making it easier for decision-makers to interpret large volumes of data. An ETL (Extract, Transform, Load) process is applied to clean, transform, and analyze the data, culminating in an insightful Excel dashboard.

---

## 🚨 Business Problem
Olist faces several key challenges that affect its ability to scale profitably:

- **High Delivery Times**: Long delivery times for certain product categories lead to lower customer satisfaction, as evidenced by review scores.
- **Weekend vs Weekday Sales Disparity**: Sales volumes drop significantly on weekends, affecting overall revenue consistency.
- **Payment Method Preferences**: Understanding the payment method preferences and their correlation with customer satisfaction is critical for refining the checkout experience.
- **Category-Wise Delivery Performance**: Certain categories such as **Fashion Calçados** experience significantly higher delivery times, potentially affecting repeat customers and overall satisfaction.

---

## 🎯 Objectives
The primary objectives of this analysis are as follows:

1. **Analyze Customer and Sales Performance**:
   - Identify key metrics such as total customers, sales, and profit across various years.
   - Understand the customer behavior by tracking reviews, delivery performance, and sales trends.

2. **Delivery Time vs Review Scores**:
   - Investigate how delivery time affects customer satisfaction, represented by review scores.
   - Identify potential inefficiencies in delivery processes for different product categories.

3. **Payment Method Analysis**:
   - Understand customer payment preferences, specifically focusing on credit card payments and their correlation with customer review scores.

4. **Weekday vs Weekend Sales**:
   - Compare weekday and weekend payment trends to identify any notable differences in customer purchasing behavior.

5. **Regional Insights**:
   - Highlight key trends in specific regions, such as Sao Paulo, where sales prices and payment values differ significantly.

---
## 🛠️ Tools Used

- **Excel**: For data processing and visualization
- **ETL Pipeline**: Extract, Transform, Load processes to clean and analyze the data
- **Pivot Tables & Charts**: For generating insights and interactive visualizations
- **Data Filters**: Filter data by year (2016-2018) and days of the week (Mon-Sun) for a more in-depth analysis
---
## 🔑 Key Insights from the Dashboard

1. **Total Metrics Overview**
   - Total Customers: 104K
   - Total Sales: 16M 
   - Total Profit: 4M

## 2. Delivery Days vs Review Score

The relationship between delivery time and customer satisfaction is one of the most telling insights of the analysis. As delivery times decrease, review scores show a clear upward trend, suggesting that faster deliveries lead to happier customers.

- **1-star reviews**: On average, customers who left a 1-star review experienced delivery times of around **20 days**. This extended delivery period significantly contributed to negative feedback.

- **5-star reviews**: Customers giving 5-star ratings had much shorter delivery times, averaging **11 days**. This shows that the quicker the delivery, the better the customer satisfaction. Thus, improving delivery times could be a key factor in raising overall customer satisfaction and increasing the likelihood of repeat business.

---

## 3. Orders by Payment Method (Credit Card)

Credit card payments emerge as a dominant payment method among customers, particularly those who gave higher review scores. This could indicate that customers who use credit cards for purchases might expect a more seamless shopping and payment experience, and this contributes to their satisfaction.

- **5-star reviews**: A significant number of highly satisfied customers (those who left 5-star reviews) made their payments via credit card. Specifically, **45,369 orders** with 5-star reviews were paid using credit cards, highlighting the importance of offering efficient and convenient payment methods.

- **1-star reviews**: On the other hand, customers who left 1-star reviews made **8,135 orders** using credit cards. This discrepancy between low and high-rated orders might suggest that issues with the delivery or product rather than the payment method itself are causing dissatisfaction among these customers.

This analysis underscores the need to ensure that payment processes remain efficient and that other factors, such as delivery and product quality, are enhanced to retain the satisfaction of credit card users.

---

## 4. Weekday vs Weekend Payments

A clear difference in customer behavior is observed between weekday and weekend sales. The analysis reveals that customers are far more active during the week, which could be linked to several factors, such as work-week schedules, higher engagement in online shopping, or even targeted promotions.

- **Weekday Payments**: Weekdays account for the majority of sales, with **12.6 million BRL** in transactions. This could be due to customer habits during the workweek when they may be more likely to make purchases during lunch breaks, or after work, and are more likely to browse online stores. Businesses could optimize weekday traffic by offering timed promotions or flash sales.

- **Weekend Payments**: Weekend transactions are considerably lower, totaling **3.7 million BRL**. The decline in weekend sales could indicate that customers engage in more offline activities during these days, or they prefer to make bigger purchases during the week. To increase weekend sales, Olist could implement special weekend promotions, discounts, or offers to draw customers back to the platform during these slower sales periods.

---

## 5. Category-wise Delivery Time

Different product categories have different average delivery times, which is a critical factor in determining customer satisfaction within each category. Addressing the outliers where delivery times are particularly high could enhance customer satisfaction across categories.

- **Fashion Calçados**: This category has the longest average delivery time, with products typically taking around **15 days** to be delivered. This extended wait period is likely to lead to customer dissatisfaction, as seen with lower review scores. Reducing delivery times for this category would likely result in higher ratings and improved customer retention.

- **Artesanato**: In contrast, products in the **Artesanato** (Handicrafts) category are delivered in a much shorter time frame, averaging only **6 days**. The fast delivery times here may contribute to higher customer satisfaction within this category. Maintaining or further improving delivery efficiency in categories like Artesanato can provide a competitive advantage for Olist.

Addressing delivery inefficiencies in product categories such as Fashion Calçados could lead to better customer feedback and increased customer loyalty.
- **Petshop**: Average delivery time is 11 days.
---

## 6. Sao Paulo Insights

The data from Sao Paulo, one of the most significant markets, reveals two important trends regarding pricing and payment values. These trends could reflect regional pricing strategies, taxes, or additional charges that influence the overall payment value.

- **Average Price**: The average product price in Sao Paulo is **111 BRL**, which indicates the typical cost of goods purchased by customers in this region. However, this alone does not fully explain the total financial value of transactions in Sao Paulo.

- **Average Payment Value**: The average payment value for transactions in Sao Paulo is higher than the average price, at **139 BRL**. This difference could be due to additional fees, such as taxes, shipping, or other service charges that are passed on to customers at checkout. Understanding this gap between the product price and the final payment is crucial, as it might reveal hidden costs that could deter customers if not communicated effectively. Businesses can refine pricing strategies and potentially absorb some of these fees or highlight their value to the customer to improve transparency.

---
## DASHBOARD
![Screenshot 2024-09-19 201157](https://github.com/user-attachments/assets/c5d2deb1-54d2-4fdc-bcdf-d8b490b6bfcb)

---
## 🔍 Conclusion
This analysis provides valuable insights into Olist's operations. Here are the key takeaways:

1. **Faster Deliveries Improve Customer Satisfaction**: Reducing delivery times can lead to improved review scores, which in turn drive customer loyalty and repeat purchases.
   
2. **Credit Cards Are Preferred by Happy Customers**: Customers who provide positive reviews (4-5 stars) are more likely to use credit cards for their purchases, indicating the importance of streamlining this payment method.

3. **Sales Decline on Weekends**: To improve sales performance, Olist can explore marketing strategies to boost weekend transactions.

4. **Product Category Impacts Delivery Time**: Categories such as Fashion Calçados need operational improvements to reduce delivery times and enhance customer satisfaction.

5. **Regional Insights Offer Growth Opportunities**: Analyzing regions like Sao Paulo provides deeper insights into localized pricing strategies and payment behaviors, allowing Olist to refine their regional offerings.

By addressing these insights, Olist can enhance its customer experience, streamline its operations, and increase profitability.

---

## 📈 Recommendation

1. **Optimize Delivery Times**: Implement strategies to reduce delivery delays, especially in categories with higher delivery times.
2. **Weekend Sales Campaigns**: Launch marketing campaigns aimed at increasing weekend sales through special promotions or incentives.
3. **Enhance Credit Card Payment Experience**: Ensure a smooth payment process, as satisfied customers tend to use credit cards more often.
4. **Deep Dive into Regional Data**: Expand the analysis to other regions beyond Sao Paulo to further customize the business strategy for localized preferences.



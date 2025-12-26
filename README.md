**ECOMMERCE CUSTOMER BEHAVIOR ANALYTICS**

**Dataset Description:**

This is a comprehensive Customer Engagement and Churn Analytics Dataset containing behavioral, demographic, and transactional data for 50,000 customers across a global e-commerce/subscription platform. The dataset captures 25 distinct features that provide a 360-degree view of customer interactions and engagement patterns.

**Dataset Source:**

https://www.kaggle.com/datasets/dhairyajeetsingh/ecommerce-customer-behavior-dataset

**Column Description:**
| Column Name              | Description                                          |
| ------------------------ | ---------------------------------------------------- |
| Age                      | Customer age                                         |
| Gender                   | Customer gender                                      |
| Country                  | Customer country                                     |
| City                     | Customer city                                        |
| Membership_Years         | Duration of customer membership                      |
| Login_Frequency          | Number of logins within a given period               |
| Session_Duration_Avg     | Average duration of each session                     |
| Pages_Per_Session        | Average number of pages visited per session          |
| Mobile_App_Usage         | Percentage of activity via mobile app                |
| Total_Purchases          | Total number of purchases made                       |
| Discount_Usage_Rate      | Frequency of discount usage                          |
| Returns_Rate             | Percentage of returned purchases                     |
| Returned_Items_Count     | Number of items returned                             |
| Days_Since_Last_Purchase | Days since the last purchase                         |
| Churned                  | Customer churn status (1 = churned, 0 = not churned) |

**Process and Methodology:**
1. Exploratory Data Analysis (EDA)
2. Data Visualization:
   
   a. What is the distribution of customers’ age and gender?
   
   b. Which countries or cities have the highest number of customers?
   
   c. Is there a relationship between login frequency and average session duration?
   
   d. How does age relate to mobile app usage?
   
   e. Which age groups tend to have the highest total purchases?
   
   f. Which age groups use discounts most frequently?
   
   g. Does higher total purchase lead to higher discount usage?
   
   h. Do customers who log in less frequently have a higher chance of churn?
   
   i. Do customers with fewer purchases have a higher chance of churn?
   
   j. Do customers with longer days since their last purchase have a higher chance of churning?
   
4. Predictive Modeling
   
   a. Logistic Regression

   b. Random Forest

**Visualizations Conclusion:**

Based on the overall data analysis, the majority of customers fall within the 36–45 age group and are predominantly female. This may be due to the fact that individuals in this age range are generally more financially stable, actively shopping for household or personal needs, and familiar with digital platforms. The dominance of female customers is also consistent with real-world shopping behavior, where females tend to be more active in online purchasing. In contrast, the smallest customer segment comes from the 66–75 age group, which may indicate lower adoption of online shopping or less engagement with digital technology among older users.

However, when analyzing the average total purchases by age group, all age groups show very similar average values. This suggests that although the 36–45 age group has the largest number of customers, their purchase quantity per customer is not significantly higher than other age groups. This may indicate that customers in the dominant age group tend to make smaller or more moderate purchases, while customers in other age groups make purchases less frequently but in comparable amounts. As a result, the average total purchases across age groups remain relatively consistent.

A similar pattern is observed in average mobile app usage by age group, where usage levels are nearly the same across all ages. This indicates that mobile applications are widely adopted regardless of age, and age alone does not strongly influence mobile app usage behavior. The same applies to discount usage where all age groups show almost identical average discount usage rates. This suggests that discount usage is not age-driven and that customers across all age groups respond similarly to promotional offers.

From a geographical perspective, among the eight countries in the dataset, the United States has the highest number of customers, making it the company’s primary market. This may be driven by stronger market penetration, higher purchasing power, or more effective marketing strategies. Further analysis of cities within the top-performing countries shows that certain cities, such as Houston, act as major customer hubs. This highlights the importance of location-based performance and suggests that customer distribution varies more by region than by age.

When examining login frequency and average session duration using a min–max approach, a clear pattern emerges: customers with lower login frequency tend to have shorter average session durations, while customers who log in more frequently tend to spend more time per session. This indicates a positive relationship between login frequency and user engagement, where frequent logins reflect higher interest and interaction with the platform.

The relationship between total purchases and discount usage shows a weak positive trend. Customers with lower total purchases tend to use discounts slightly more often, which may indicate a marketing strategy aimed at encouraging less active customers to increase their purchasing activity. On the other hand, customers with higher total purchases appear to rely less on discounts, suggesting that loyal or frequent customers have a stronger purchase intention and are less price-sensitive.

Finally, the churn analysis provides important insights into customer retention. The boxplot shows that churned customers have a lower median login frequency compared to non-churned customers, indicating that customers who log in less frequently are more likely to churn. In addition, customers with low purchase frequency also represent a higher churn risk, as they tend to be less engaged overall. These findings highlight login frequency and total purchases as key indicators of customer engagement, loyalty, and retention.

**Recommendations:**

1. **Increase customer engagement by encouraging more frequent logins**

Customers who log in more often tend to stay longer on the platform and are less likely to churn. Sending personalized notifications, reminders, or highlighting new features can motivate customers to return more frequently and maintain their engagement.

2. **Apply discounts strategically to less active customers**

The analysis shows that customers with lower total purchases tend to use discounts more often. This suggests that discounts are more effective as a tool to encourage inactive or low-engagement customers, rather than offering large discounts to already loyal customers who are less price-sensitive.

3. **Strengthen loyalty programs for frequent buyers**

Customers with higher purchase frequency are less likely to churn and do not strongly depend on discounts. Rewarding them with loyalty points, exclusive offers, or early access to products can help maintain long-term retention and increase customer lifetime value.

4. **Focus marketing efforts on high-performing regions and cities**

Countries and cities with a high number of customers, such as the USA and major customer hubs, contribute significantly to overall performance. Strengthening campaigns in these areas can maximize returns, while targeted and localized strategies can be used to grow customer bases in underperforming regions.

5. **Provide additional support for older customers**

Older age groups show lower participation levels, possibly due to lower familiarity with digital platforms. Offering simplified user interfaces, clearer instructions, and customer support can help increase their comfort and engagement with the platform.

**Predict Modeling Result:**



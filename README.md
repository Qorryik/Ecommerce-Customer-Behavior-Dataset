# **E-Commerce Customer Behavior Analytics**

## 📌 Project Overview

This project analyzes customer behavior data from a global e-commerce platform to understand engagement patterns, purchasing behavior, and churn risk. The analysis combines exploratory data analysis, data visualization, and machine learning models to derive actionable business insights.

---

## 📂 Dataset Information

**Source:**
🔗 [https://www.kaggle.com/datasets/dhairyajeetsingh/ecommerce-customer-behavior-dataset](https://www.kaggle.com/datasets/dhairyajeetsingh/ecommerce-customer-behavior-dataset)

**Description:**
A comprehensive dataset containing behavioral, demographic, and transactional data for **50,000 customers**, with **25 features** representing customer engagement, activity, and churn behavior.

---

## 🧾 Column Description

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

---

## 🔍 Analysis Workflow

### 1. Exploratory Data Analysis (EDA)

* Data consistency checks
* Handling anomalies and missing values
* Feature understanding

### 2. Data Visualization

Key questions explored:

* What is the distribution of customers’ age and gender?

* Which countries or cities have the highest number of customers?

* Is there a relationship between login frequency and average session duration?

* How does age relate to mobile app usage?

* Which age groups tend to have the highest total purchases?

* Which age groups use discounts most frequently?

* Does higher total purchase lead to higher discount usage?

* Do customers who log in less frequently have a higher chance of churn?

* Do customers with fewer purchases have a higher chance of churn?

* Do customers with longer days since their last purchase have a higher chance of churning?

### 3. Predictive Modeling

* Logistic Regression 
* Random Forest 

---

## 📊 Key Insights from Visualization

* The largest customer segment comes from the **36–45 age group**, dominated by **female customers**
* The **66–75 age group** has the fewest customers, likely due to lower digital adoption
* Average **total purchases**, **mobile app usage**, and **discount usage** are **similar across age groups**
* The **USA** is the largest market, with cities like **Houston** acting as major customer hubs
* Higher **login frequency** is associated with **longer session duration**
* Customers with **lower total purchases** tend to use discounts slightly more
* Customers with **low login frequency and low purchases** show a higher risk of churn

---

## 🎯 Churn Insights

* Churned customers have a **lower median login frequency**
* Customers who purchase less frequently are **more likely to churn**
* Login frequency and total purchases are strong indicators of **customer engagement and loyalty**

---

## 💡 Recommendations

1. **Encourage frequent logins**
   Frequent logins indicate higher engagement. Personalized notifications and reminders can help reduce churn.

2. **Use discounts strategically**
   Discounts are more effective for low-activity customers rather than loyal buyers.

3. **Strengthen loyalty programs**
   High-purchase customers value exclusivity more than discounts.

4. **Focus on high-performing regions**
   Strengthen marketing in top cities while using localized strategies in underperforming regions.

5. **Support older customers**
   Simplified interfaces and better guidance can improve engagement among older users.

---

## 🤖 Machine Learning Results

### Logistic Regression

* Accuracy: ~78%
* Recall (churn): ~42%
* ROC-AUC: ~0.79
  → Suitable as a baseline but limited in identifying churned customers.

### Random Forest (Tuned)

* Accuracy: ~90.7%
* ROC-AUC improved from **0.86 → 0.92**
* Higher recall for churned customers
  → Stronger discrimination and better business applicability.

---

## ✅ Final Conclusion

This analysis shows that customer engagement especially login frequency and purchasing activity plays a more important role in churn behavior than demographic factors such as age. While age and gender describe customer distribution, behavioral metrics are stronger predictors of retention. The tuned Random Forest model provides the most effective solution for churn prediction and can support data-driven retention strategies.

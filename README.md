# Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The aim is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 📊 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - Customer demographics (Age, Gender, Location, Subscription Status)  
  - Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)  
  - Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type)  
- **Missing Data:** 37 values in *Review Rating* column  

## 🐍 Exploratory Data Analysis (Python)
- Data cleaning and preprocessing using **pandas**  
- Missing values imputed with median rating per product category  
- Feature engineering: age groups, purchase frequency in days  
- Redundant columns dropped (e.g., promo_code_used)  
- Integration with **PostgreSQL** for structured SQL analysis  

## 🗄️ SQL Analysis (Business Transactions)
Key insights derived using SQL queries:
1. **Revenue by Gender:** Male customers generated ~2x revenue compared to females.  
2. **High-Spending Discount Users:** 839 customers used discounts but still spent above average.  
3. **Top Products by Rating:** Gloves, Sandals, Boots, Hat, and Skirt ranked highest.  
4. **Shipping Type Comparison:** Express shipping had slightly higher average purchase amounts.  
5. **Subscribers vs. Non-Subscribers:** Non-subscribers contributed 73% of revenue.  
6. **Discount-Dependent Products:** Hats, Sneakers, Coats, Sweaters, and Pants had the highest discount usage.  
7. **Customer Segmentation:** Majority were *Loyal* (3,116), followed by *Returning* (701) and *New* (83).  
8. **Top Products per Category:** Jewelry, Blouse, Sandals, Jacket were leading items.  
9. **Repeat Buyers & Subscriptions:** Repeat buyers (>5 purchases) were more likely to subscribe.  
10. **Revenue by Age Group:** Young Adults contributed the highest revenue (~62K).  

## 📈 Dashboard (Power BI)
An interactive dashboard was built to visualize:
- Subscription status distribution  
- Revenue and sales by category  
- Customer demographics (age group, gender)  
- Shipping type comparisons  
- Average purchase amount and review ratings  

## 💡 Business Recommendations
- **Boost Subscriptions:** Offer exclusive benefits to increase subscriber base.  
- **Customer Loyalty Programs:** Reward repeat buyers to strengthen loyalty.  
- **Review Discount Policy:** Balance margin control with sales growth.  
- **Product Positioning:** Highlight top-rated and best-selling products in campaigns.  
- **Targeted Marketing:** Focus on high-revenue age groups and express-shipping users.  

---

### 🔗 About
This project is part of a data analytics portfolio showcasing skills in **Python, SQL, and Power BI**. It demonstrates the ability to transform raw transactional data into meaningful insights for business applications.

# EDA_retail_sales

# 🛒 Retail Sales Analysis

This project focuses on exploring and analyzing a retail sales dataset using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. The goal is to gain business insights from transaction-level sales data including customer demographics, product categories, and purchasing trends.

---

## 📁 Dataset Overview

- **Total Records**: 1,000 transactions  
- **Columns**:
  - `Transaction ID`: Unique identifier for each transaction
  - `Date`: Transaction date
  - `Customer ID`: Unique identifier per customer
  - `Gender`: Customer gender (Male/Female)
  - `Age`: Age of the customer
  - `Product Category`: Category of purchased product
  - `Quantity`: Number of units purchased
  - `Price per Unit`: Unit price of the product
  - `Total Amount`: Total cost for the transaction

---

## 🔧 Data Preprocessing

- Converted `Date` column to datetime format for time-based analysis.
- Removed duplicates to ensure transaction uniqueness.
- Validated `Total Amount` by recalculating it using `Quantity × Price per Unit`.
- Extracted **Month**, **Weekday**, and created **Age Groups** for segment-wise analysis.

---

## 📊 Statistical Summary

Using **NumPy**, we applied various statistical functions:

- Average Quantity Purchased
- Average Price per Unit
- Maximum Transaction Value
- Standard Deviation in Quantity & Price
- Correlation matrix between Quantity, Price, and Total Amount

---

## ❓ Key Business Questions Answered

- **Which product categories are most popular?**
- **What are the monthly sales trends across the year?**
- **Is there any gender difference in overall spending?**
- **Which age group spends the most?**
- **Which weekdays have the highest sales?**

---

## 📈 Visualizations

- Bar plot of top product categories
- Monthly sales trend line chart
- Gender-wise total sales bar plot
- Box plot for Age group vs spending
- Weekday-wise revenue breakdown

Visualizations were created using **Matplotlib** and **Seaborn** to support data-driven storytelling.

---

## 🚀 Tools & Libraries

- `pandas` for data manipulation
- `numpy` for statistical calculations
- `matplotlib` & `seaborn` for data visualization

---

## 📌 Conclusion

This analysis helps retail businesses:
- Understand customer demographics and buying behavior
- Optimize inventory based on popular categories
- Identify peak sales days and months
- Personalize marketing strategies based on age/gender segments

---

## 🧠 Author

-Manthan Palde
(Data Science and AI Enthusiast)

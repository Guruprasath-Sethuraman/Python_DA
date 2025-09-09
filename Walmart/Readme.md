# 🛒 Walmart Sales Analysis Project

This project analyzes **Walmart transaction data** to answer a series of **business and analytical questions** using Python, Pandas, and SQL-style operations.  

The dataset contains transactional-level details such as:  
- **Invoice ID** 
- **Branch & City**
- **date & time**  
- **Category**  
- **Unit Price**  
- **Quantity**  
- **Total Sales**  
- **Payment Method**  
- **Rating**  
- **Profit Margin**
- **total**

---

## 📊 Questions & Analysis

### 🔹 Basic Data Retrieval
1. **What are the details of the transaction with invoice_id 3?**  
2. **List all transactions where the payment method was 'Ewallet'.**  
3. **Show all sales that occurred in the city of 'Harlingen'.**  
4. **Which transactions are from the 'Health and beauty' category?**  
5. **Retrieve all invoices where the unit price was greater than $80.**  

---

### 🔹 Aggregate & Summary
6. **What is the total revenue (sum of the total column) for all transactions in this sample?**  
7. **What is the average customer rating given across all sales?**  
8. **How many unique branches are represented in this data?**  
9. **What is the total quantity of items sold for the 'Electronic accessories' category?**  
10. **Which branch made the highest single sale (largest total value)?**  

---

### 🔹 Analytical & Insight-Driven
11. **Which product category has the highest average profit margin?**  
12. **Is there a correlation between the payment method (Cash, Ewallet, Credit card) and the customer rating?**  
13. **Calculate the total profit for each transaction. Which transaction was the most profitable?**  
14. **What is the total sales volume for each city? Which city is the top performer in this sample?**  
15. **On the available dates, which date had the highest number of transactions?**  

---

## 🚀 Tools & Techniques
- **Python** → Data cleaning, transformation, and aggregation  
- **Pandas** → GroupBy, filtering, `.agg()`, and analytical queries  
- **SQL-style thinking** → Translating business questions into queries  

---

## 📈 Key Outcomes
- Identified **top-performing cities, branches, and product categories**  
- Compared **customer behavior by payment method**  
- Measured **profitability per transaction and per category**  
- Analyzed **sales distribution across branches and cities**  
- Prepared insights that simulate **real-world retail reporting**  

---

## 📌 How to Run
1. Clone this repository or download the dataset.  
2. Install required libraries:  
   ```bash
   pip install pandas

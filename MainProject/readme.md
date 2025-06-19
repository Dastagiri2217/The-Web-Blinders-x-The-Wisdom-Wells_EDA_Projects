# 🛒 Online Retail Dataset - Exploratory Data Analysis (EDA)

This project performs an Exploratory Data Analysis (EDA) on the **Online Retail Dataset**, available from Kaggle. The objective is to analyze customer transactions and understand product sales, returns, trends, and revenue patterns.

📌 **Dataset Source**:  
[Online Retail Dataset - Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset)

---

## 📂 Project Structure

├── online_retail_eda.ipynb # Main Jupyter Notebook with analysis
├── README.md # Project overview
└── datasetlink.txt

---

## 📊 Key Objectives

- Understand the structure of online retail transaction data
- Identify top-selling products and revenue drivers
- Analyze return patterns
- Observe seasonal and geographic transaction trends
- Derive actionable business insights

---

## 🔎 Questions Explored

1. **What are the top 10 selling products (by quantity)?**
2. **What are the most common return items?** (based on quantity < 0)
3. **What is the monthly trend of transactions over time?**
4. **Which countries have the highest number of transactions?**
5. **Which products generate the highest total revenue?**

---

## 📌 Dataset Description

The dataset contains over 500,000 transactions for a UK-based online retail store from 2010 to 2011.

**Key columns:**
- **InvoiceNo**: Invoice number (returns start with 'C')
- **StockCode**: Product code
- **Description**: Product name
- **Quantity**: Quantity ordered (negative = returns)
- **InvoiceDate**: Date and time of purchase
- **UnitPrice**: Price per unit
- **CustomerID**: Unique ID of customer
- **Country**: Country of transaction

---

## 📈 Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📍 EDA Highlights

- Extracted and visualized top-selling and top-returned products
- Aggregated monthly sales trends
- Identified revenue-driving products using calculated revenue (`Quantity × UnitPrice`)
- Analyzed customer activity by country
- Cleaned and preprocessed missing/invalid data

---

## 🧾 Key Conclusions

1. **Top Selling Products**:  
   The most frequently sold items include **gliders and bags**, which are commonly used in colder climates.

2. **Most Returned Items**:  
   **Glass and paper items** are returned the most, possibly due to fragility during delivery.

3. **Monthly Transaction Trend**:  
   The highest number of transactions occur in **November and December**, likely due to holiday shopping.

4. **Top Country by Transactions**:  
   The **United Kingdom (UK)** accounts for the majority of transactions.

5. **Top Revenue Generator**:  
   The product **“DOTCOM POSTAGE”** generated the highest revenue, earning over **£200,000**.

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone [https://github.com/your-username/online-retail-eda.git](https://github.com/Dastagiri2217/The-Web-Blinders-x-The-Wisdom-Wells_EDA_Projects/edit/main/MainProject)


# SMIT-Assignment-2
# Superstore Data Analysis  
A complete exploratory data analysis (EDA) of the Superstore dataset, including data cleaning, statistical summaries, visualizations, and business insights.

---

## Project Overview
This project analyzes the **Superstore Sales Dataset**, which contains 9,994 retail transactions.  
The analysis includes:

- Data Cleaning  
- Data Overview  
- Generating Statistical Summaries  
- Exploratory Data Analysis (EDA)  
- Visualizations  
- Insight & Conclusion Report  

The goal is to understand sales behavior, profit trends, discount impact, and shipping performance.

---

## Dataset
The dataset can be downloaded from Kaggle:

**Superstore Dataset**  
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/data

---

## 1. Data Cleaning
Key cleaning steps include:

- Converted `Order Date` and `Ship Date` to datetime format  
- Created new features:
  - `Order_Year`  
  - `Order_Month`  
  - `Shipping_Delay_Days`
- Removed potential duplicates  
- Corrected data types for analysis  
- Checked for missing values (none critical)

---

## 2. Statistical Summary

### **Numerical Columns Summary**
| Metric | Sales | Quantity | Discount | Profit |
|--------|--------|----------|----------|---------|
| Mean | 229.86 | 3.79 | 0.156 | 28.65 |
| Std | 623.24 | 2.22 | 0.20 | 234.26 |
| Min | 0.44 | 1 | 0.0 | -6599.97 |
| 25% | 17.28 | 2 | 0.0 | 1.72 |
| 50% | 54.49 | 3 | 0.2 | 8.66 |
| 75% | 209.94 | 5 | 0.2 | 29.36 |
| Max | 22638.48 | 14 | 0.8 | 8399.97 |

### **Shipping Delay Summary**
| Statistic | Value |
|----------|--------|
| Min | 0 days |
| Max | 7 days |
| Average Delay | 3.95 days |

---

## 3. Exploratory Data Analysis (EDA)

### **Sales Distribution**
- Highly right-skewed  
- Majority of transactions under \$500  

### **Profit Distribution**
- Many low-profit transactions  
- Significant portion shows **negative profit**  

### **Discount vs Profit**
- Higher discounts = lower profits  
- At 0.8 discount, profits are mostly negative  

### **Quantity Patterns**
- Most customers buy 1–5 items  
- Large quantity orders are rare but high revenue drivers  

### **Shipping Analysis**
- Average delay: ~4 days  
- Most deliveries completed within 3–5 days  

### **Time Trends**
- Sales consistently increased from **2014 → 2017**  
- Highest sales in **November & December**

---

## 4. Key Insights

- **High sales do not guarantee high profit**  
- **Discounts significantly reduce profitability**  
- **Shipping operations are stable and consistent**  
- **Clear seasonal trends during holiday months**  
- **Year-over-year sales growth shows positive business expansion**

---

## 5. Conclusion
The Superstore dataset reveals strong business growth but inconsistent profitability due to high discounts. Better discount policies and category-level optimization could improve margins. Logistics performance is reliable, with most orders delivered on time.

This analysis provides a complete understanding of sales patterns, profit behavior, and operational efficiency.

---

## 6. Notebook Link
Add your Colab / GitHub Notebook link here:

🔗 **Colab Notebook:** https://colab.research.google.com/drive/1wKpr9W81O87yJFjTc9Kv8H8B6xW9zOY6?usp=sharing  
🔗 **GitHub Notebook:** https://github.com/Khuzi13/SMIT-Assignment-2/blob/main/Sample_Superstore_csv.ipynb

---

## 📬 Contact
For queries or guidance, feel free to connect.

---



# 🍽️ UFood Marketing Campaign Analysis

## 📌 Overview
Analysis of UFood's customer marketing data to uncover spending patterns, 
campaign effectiveness, and customer segments. UFood is the leading food 
delivery app in Brazil, operating across 1,000+ cities.

This project was completed as part of my Python and Data Analysis learning 
journey using the Analyst Builder course.

---

## 📊 Dataset
- **File:** u_food_marketing.csv
- **Rows:** 2,205 customers
- **Columns:** 39 features
- **Source:** UFood Data Analyst Case (provided dataset)

---

## 🎯 Project Objectives
1. Explore the data deeply — go beyond averages, find cause and effect
2. Propose a customer segmentation based on spending behaviour
3. Visualise findings and provide written reasoning behind each insight

---

## 🔍 Key Findings

**Spending**
- Wines and meat products account for nearly 70% of average customer spend
- Income is the strongest driver of total spend (r = 0.82)
- Customers with children spend significantly less — dropping from $1,120 
  (no kids) to $249 (two kids)

**Campaigns**
- 67% of customers accepted zero campaigns — engagement is low overall
- Past campaign acceptance is the strongest predictor of future response 
  (r = 0.72)
- High-income, child-free, recently active customers respond the most

**Channels**
- Physical stores are the dominant channel (5.8 avg purchases per customer)
- Catalogue purchasing is almost exclusively a high-income behaviour
- The website has a conversion problem — visits and purchases show 
  near-zero correlation (-0.056)

**Segmentation**
Four customer segments identified using income and total spend:

| Segment | Customers | Avg Income | Avg Spend |
|---|---|---|---|
| Premium | ~900 | $70,596 | $1,163 |
| Budget | ~900 | $32,971 | $101 |
| Bargain Hunter | ~110 | $43,503 | $602 |
| Potential | ~105 | $57,975 | $213 |

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Files
| File | Description |
|---|---|
| `UFood Campaign Analysis.ipynb` | Main analysis notebook |
| `u_food_marketing.csv` | Dataset |
| `UFood Data Analyst Case.pdf` | Original case brief |
| `ufood_marketing_Dictionary.png` | Data dictionary |

---

## 📈 Analysis Sections
1. Business Context
2. Exploratory Data Analysis
3. Spending Analysis — Who Spends What?
4. Campaign Analysis — Who Responds and Why?
5. Channel Analysis — Where Do Customers Buy?
6. Correlation Analysis
7. Customer Segmentation
8. Final Conclusion & Business Recommendations

---

## 👤 Author
**Abhishek Thapa**  
Aspiring Data Analyst | Python & Pandas | Working toward ML  
GitHub: [abhishek-analytics-14](https://github.com/abhishek-analytics-14)

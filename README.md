# 🛍️ Customer Segmentation & Market Basket Analysis

## 📌 Overview

This project analyzes **1 million retail transactions** to understand customer purchasing behavior and identify product associations using **K-Means Clustering** and **FP-Growth**.

The results provide actionable insights to support customer segmentation, cross-selling opportunities, and data-driven marketing strategies.

📄 **This project has been published in the Journal of National Technology and Information Systems (TEKNOSI).**

---

# 🎯 Business Problem

Retail businesses often struggle to:

- Identify different customer purchasing behaviors
- Personalize marketing campaigns
- Discover products frequently purchased together
- Improve cross-selling and promotional strategies

This project addresses these challenges by combining customer segmentation with market basket analysis.

---

# 📊 Dataset

- Source: Kaggle Retail Transactions Dataset
- Total Transactions: **1,000,000**
- Features:
  - Customer ID
  - Product Category
  - Total Amount
  - Quantity
  - Age
  - Gender
  - Payment Method
  - Purchase Date

---

# ⚙️ Methodology

## Data Preprocessing

- Missing value handling
- Duplicate removal
- Feature selection
- Data transformation
- Transaction encoding

---

## Customer Segmentation

Algorithm:

- K-Means Clustering

Evaluation:

- Elbow Method
- Davies-Bouldin Index

Result:

- **3 customer segments**

---

## Market Basket Analysis

Algorithm:

- FP-Growth

Parameters:

- Minimum Support = 0.002
- Minimum Confidence = 0.30

Result:

- **16 association rules**

---

# 📈 Results

## Customer Segmentation

Three customer groups were identified based on purchasing behavior:

### Segment 1
- High spending customers
- Highest purchasing frequency
- Recommended strategy:
  - Premium promotions
  - Loyalty rewards

### Segment 2
- Moderate purchasing behavior
- Recommended strategy:
  - Product recommendations
  - Personalized offers

### Segment 3
- Low purchasing frequency
- Recommended strategy:
  - Discount campaigns
  - Customer reactivation

---

## Market Basket Analysis

The FP-Growth algorithm discovered **16 association rules** that reveal products frequently purchased together.

Example business applications:

- Product bundling
- Store layout optimization
- Cross-selling recommendations
- Promotional campaign design

---

# 💡 Business Impact

This project demonstrates how retail transaction data can support:

- Customer segmentation
- Personalized marketing
- Product recommendation
- Cross-selling strategy
- Business decision making

---

# 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- MLxtend
- Matplotlib
- Seaborn

---

# 📸 Visualizations

- Elbow Method
- Customer Segment Distribution
- Cluster Visualization
- Association Rules
- Product Network (optional)

---

# 📄 Publication

**Integration of FP-Growth and K-Means for Market Basket Analysis and Customer Segmentation**

Published in:

**Jurnal Nasional Teknologi dan Sistem Informasi (TEKNOSI)**

🔗 https://doi.org/10.25077/TEKNOSI.v11i2.2025.128-135

---

# 🚀 Future Improvements

- Apply RFM Analysis before clustering.
- Compare K-Means with DBSCAN or Hierarchical Clustering.
- Build an interactive dashboard using Looker Studio or Power BI.
- Deploy recommendation results through a web application.

# 🚀 Customer Churn Prediction, RFM Analysis & Customer Segmentation

---

## 📌 Project Overview

This project builds a **complete data science pipeline** to:
- 📉 Predict customer churn using Machine Learning  
- 📊 Perform RFM (Recency, Frequency, Monetary) analysis  
- 👥 Segment customers using clustering techniques  
- 📈 Generate actionable business insights  

---

## 🎯 Objectives

- Identify customers likely to churn  
- Understand customer behavior patterns  
- Segment customers for targeted marketing  
- Support data-driven business decisions  

---

## ⚙️ Project Workflow

### 1️⃣ 📚 Import Required Libraries
- Pandas, NumPy  
- Seaborn, Matplotlib, Plotly  
- Scikit-learn  

---

### 2️⃣ 📂 Load and Explore Customer Data
- Loaded dataset using Pandas  
- Checked:
  - Data types  
  - Missing values  
  - Basic statistics  

---

### 3️⃣ 🔍 Exploratory Data Analysis (EDA)

Performed visual analysis to understand patterns:

- 📊 Count plots for categorical variables  
- 📉 Boxplots for numerical features  
- 🔥 Correlation heatmap  

#### 🔑 Key Observations:
- High recency → higher churn  
- Low session frequency → higher churn  
- High cart abandonment → strong churn indicator  

---

### 4️⃣ ⚙️ Feature Engineering

Created new features:

- 📊 `engagement_score = session_frequency × avg_session_duration`  
- 💰 `value_score = avg_order_value × session_frequency`  

These features improved model performance.

---

### 5️⃣ 🧹 Data Preprocessing

- Converted categorical variables using one-hot encoding  
- Split dataset into training and testing sets  
- Prepared data for machine learning models  

---

### 6️⃣ 🌳 Random Forest Classification Model

- Built a **Random Forest Classifier**  
- Captured non-linear relationships in data  
- Improved prediction performance over baseline  

---

### 7️⃣ 📈 Model Evaluation

Evaluated model using:

- ✔ Accuracy  
- ✔ Precision  
- ⭐ Recall (important for churn prediction)  
- 📉 Confusion Matrix  

---

## 📊 RFM Analysis

---

### 8️⃣ 🧠 RFM Analysis Fundamentals

Defined:
- 🕒 Recency → Time since last activity  
- 🔁 Frequency → Number of interactions  
- 💰 Monetary → Customer spending  

---

### 9️⃣ 🔢 RFM Scoring and Segmentation

- Created RFM scores using quantiles  
- Segmented customers into:

  - 🏆 Champions  
  - 💎 Loyal Customers  
  - ⚡ Potential Customers  
  - ⚠️ At Risk Customers  

---

### 🔟 💡 RFM Business Insights

- Champions → Low churn risk  
- At Risk → High churn probability  
- Loyal → Opportunity for upselling  

---

## 🤖 Customer Segmentation

---

### 1️⃣1️⃣ 📌 K-Means Clustering on RFM Features

- Applied K-Means clustering  
- Grouped customers based on behavior  
- Identified distinct customer segments  

---

### 1️⃣2️⃣ 🌐 3D Interactive Visualization (Plotly)

- Visualized clusters using **Plotly 3D scatter plot**  
- Dimensions:
  - Recency  
  - Frequency  
  - Monetary  

👉 Helped in understanding cluster separation clearly  

---

## 💡 Business Insights & Recommendations

- 📉 Customers with low engagement are likely to churn  
- 🛒 High cart abandonment signals churn risk  
- 💎 High-value customers require retention strategies  

### 🎯 Actions:
- Offer discounts to “At Risk” users  
- Improve engagement via notifications  
- Provide loyalty rewards to high-value customers  

---

## 🛠️ Tech Stack

- 🐍 Python  
- 📊 Pandas, NumPy  
- 📉 Seaborn, Matplotlib  
- 🌐 Plotly  
- 🤖 Scikit-learn  

---

## 📁 Project Structure
┣ 📂 data
┣ 📂 notebooks
┗ 📄 README.md
## ⭐ Support

If you found this project useful:
- ⭐ Star the repository  
- 🔗 Share with others  

---

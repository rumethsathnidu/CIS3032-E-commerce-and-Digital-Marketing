# Customer Segmentation Using Data Mining Techniques for Personalized Marketing

## 📘 Project Overview
This project is developed as part of the **CIS3032 – E-commerce and Digital Marketing** module under the *Bachelor of Computing (Hons) in Information Systems*, University of Sri Jayewardenepura.

It focuses on **customer segmentation using data mining and machine learning techniques** to enable personalized marketing strategies in e-commerce environments.

The study integrates **RFM analysis, clustering, dimensionality reduction, and predictive modelling** to extract actionable insights from transactional customer data.

---

## 🎯 Objectives
- Develop a unified **RFM (Recency, Frequency, Monetary) customer segmentation framework**
- Apply **K-Means clustering** to identify customer behavior groups
- Use **PCA (Principal Component Analysis)** for dimensionality reduction
- Build a **Random Forest churn prediction model**
- Evaluate customer value using **Customer Lifetime Value (CLV) analysis**
- Improve marketing efficiency through data-driven segmentation

---

## 📊 Dataset
- Source: Online Retail transactional dataset
- Level: Customer-level aggregated transactional data
- Key attributes:
  - Invoice transactions
  - Product descriptions
  - Quantity and unit price
  - Customer IDs

### 🔧 Data Preprocessing
- Removed missing Customer IDs
- Eliminated cancelled transactions
- Aggregated data into customer-level features
- Constructed RFM variables (Recency, Frequency, Monetary)

---

## 🧠 Methodology

### 1. RFM Analysis
Customers are segmented based on:
- **Recency** – Time since last purchase
- **Frequency** – Number of purchases
- **Monetary** – Total spending

### 2. K-Means Clustering
Used to group customers into behavioral segments:
- Champions
- Loyal Customers
- Potential Loyalists
- At Risk Customers
- Lost Customers

### 3. PCA (Dimensionality Reduction)
- Reduces feature complexity
- Improves clustering visualization and efficiency

### 4. Predictive Modelling
- Algorithm: **Random Forest Classifier**
- Purpose: Churn prediction
- Evaluation metrics:
  - ROC Curve
  - Confusion Matrix
  - Feature Importance

---

## 🛠️ Tools & Technologies
- Python (Jupyter Notebook)
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Machine Learning (Clustering & Classification)
- Data Visualization

---

## 📈 Key Findings
- Customer spending behavior is highly **skewed**
- Small percentage of customers contribute majority of revenue (Pareto Principle)
- **Frequency and Monetary value** are the strongest predictors of customer value
- K-Means clustering effectively identifies meaningful customer segments
- Random Forest model shows strong performance in churn prediction
- High-value customers generate disproportionate business impact

---

## 💡 Business Insights
- Focus marketing on **high-value customer segments (Champions)**
- Implement **retention strategies for at-risk customers**
- Use CLV-based targeting for better ROI
- Apply predictive churn models for proactive decision-making
- Optimize marketing budget allocation using segmentation outputs

---

## 🚀 How to Run the Project

```bash
# Clone repository
git clone <repository-link>

# Install dependencies
pip install pandas numpy scikit-learn matplotlib

# Run Jupyter Notebook
jupyter notebook

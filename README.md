# Retail Customer & Sales Analytics 🛒📊

This project provides a comprehensive analytical framework for retail managers to optimize supermarket operations. By leveraging machine learning algorithms, the project transforms raw sales data into actionable insights regarding customer segmentation and sales performance.

## 🚀 Project Overview
The core objective is to help organizational leaders manage their supermarkets more effectively using data-driven decisions. The project utilizes a full data pipeline—from SQL database integration to advanced clustering and predictive classification.

## 🛠️ Tech Stack
- **Languages:** Python
- **Database:** SQL Server (integrated via `pyodbc`)
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-Learn (KMeans, DBSCAN, Decision Tree, Random Forest, Gradient Boosting, Logistic Regression)
- **Visualization:** Matplotlib, Seaborn

## 📋 Key Features
1. **Data Ingestion:** Seamlessly reads data from a SQL Server database for real-time processing.
2. **Local Storage:** Optimizes performance by saving processed data to CSV for faster subsequent access.
3. **Robust Preprocessing:** Handles missing values and performs label encoding to prepare categorical data for ML models.
4. **Customer Segmentation:** Implements **KMeans** and **DBSCAN** to group customers into 5 distinct clusters based on behavior.
5. **Advanced Classification:** Uses a **Voting Classifier** (Ensemble Learning) including Decision Trees and Random Forests to categorize customers based on cluster labels.
6. **Synthetic Insight Generation:** Automatically generates ratings and reviews based on product performance and sales volume.
7. **Exploratory Data Analysis (EDA):** Detailed visualizations including total sales by group and sales distributions.

Install Requirements:
Bash

`pip install -r requirements.txt`

## ⚙️ Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ahmedayad0168/retail-analytics.git](https://github.com/ahmedayad0168/retail-analytics.git)

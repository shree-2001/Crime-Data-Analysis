# Crime Data Predictive Analytics – Academic Project

## 📌 Overview
This project analyzes **Chicago street crime** using **predictive analytics** and **machine learning** to identify **patterns, hotspots, and temporal trends** that can aid in **crime prevention, public safety, and policy-making**.  
It applies advanced ML models to forecast crime types and locations, enabling **data-driven resource allocation** and **community-focused safety initiatives**.

---

## 🎯 Objectives
- Identify **spatial crime hotspots** and **temporal patterns**.
- Apply multiple **machine learning models** to forecast crime occurrence.
- Provide **actionable insights** for **law enforcement** and **urban planners**.
- Enhance **community trust** through transparent, data-driven approaches.

---

## 🧵 Methodology

### 1️⃣ Data Collection & Preprocessing
- Source: Public Chicago crime dataset.
- Cleaning: Removed duplicates, handled missing values, standardized formats.
- Feature Engineering: Extracted `Month`, `Day`, `Hour`, `Season`, `isWeekend`, and location coordinates.

### 2️⃣ Exploratory Data Analysis (EDA)
- Pair plots to visualize relationships between temporal and spatial features.
- Distribution charts for **top 15 crime categories** (theft, battery, criminal damage, assault, etc.).
- Heatmap of feature correlations.

### 3️⃣ Model Development
Implemented and compared:
- **Random Forest** – Robust baseline, low overfitting.
- **Gradient Boosting** – Sequential error correction, reduced bias.
- **XGBoost** – Optimized gradient boosting with regularization.
- **LightGBM** – Fast, memory-efficient tree-based boosting.
- **Multi-Layer Perceptron (MLP)** – Neural network for complex non-linear patterns.

### 4️⃣ Evaluation
- Metrics: **Accuracy**, **Precision**, **Recall**, **F1-score**.
- Used **Confusion Matrices** to examine misclassifications.
- Tuned models with grid/random search.

---

## 📊 Key Insights
- **Hotspots**: Near North Side, Austin — high theft & assault rates.
- **Peak Times**: Late evenings & weekends, especially in warmer months.
- **Top Crimes**: Theft, battery, and criminal damage make up 50%+ of all crimes.

---

## 💡 Business Value
- **Resource Allocation**: Deploy officers where and when they’re needed most.
- **Policy Making**: Guide socioeconomic and community engagement programs.
- **Public Awareness**: Design safety campaigns for peak crime periods.
- **Urban Planning**: Improve lighting, surveillance, and infrastructure in high-risk areas.
- **Community Trust**: Transparent use of data builds public confidence.

---

## 🛠️ Tech Stack
- **Python** – pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, lightgbm.
- **Jupyter Notebook** – analysis and visualizations.
- **Machine Learning** – classification models for crime prediction.

---

## 👥 Contributors
- **Dineshkumar Lingapandiyan** – Data analysis, modeling.
- **Jayashree Rajkumar** – EDA, documentation.
- **Nagalakshmi Ramakrishna** – Model evaluation, insights.

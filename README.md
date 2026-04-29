# 📊 Business vs Entertainment Data Analytics

### Comparative Analysis: Customer Churn & Netflix Titles

---

## 📋 Project Overview

This project presents a comparative analysis of two different domains using data analytics:

* 📉 **Customer Churn Analysis (Telecom Industry)**
* 🎬 **Netflix Titles Analysis (Entertainment Industry)**

The goal is to apply a **common data science workflow** to extract insights and support decision-making in both domains.

---

## 🎯 Project Objectives

| Project        | Domain                | Goal                   | Dataset Size                 |
| -------------- | --------------------- | ---------------------- | ---------------------------- |
| Customer Churn | Business (Telecom)    | Predict customer churn | 7,043 customers, 21 features |
| Netflix Titles | Entertainment (Media) | Analyze content trends | 8,800+ titles, 12 features   |

---

# 📊 Project 1: Customer Churn

## 📌 Problem Statement

Identify customers who are likely to leave the telecom service and understand the factors influencing churn.

---

## 🔍 Key Findings

* Month-to-month contract customers show the highest churn rate
* Most churn occurs within the first 12 months
* Customers with higher monthly charges are more likely to churn
* Customers using multiple services tend to stay longer
* Tenure and contract type are strong indicators of churn

---

## ⚙️ Features Created

| Feature      | Description                         |
| ------------ | ----------------------------------- |
| TenureGroup  | Categorized tenure into time groups |
| ServiceCount | Total number of services used       |

---

## 💡 Recommendations

* Promote long-term contracts to reduce churn
* Provide offers for new customers (0–12 months)
* Reduce high monthly charges with discounts
* Encourage bundled service usage
* Promote automatic payment methods

---

# 🎬 Project 2: Netflix Titles

## 📌 Problem Statement

Analyze Netflix’s content library to identify trends, popular genres, and distribution patterns.

---

## 🔍 Key Findings

* Movies dominate Netflix content compared to TV shows
* Content production increased significantly over time
* Drama and comedy are among the most popular genres
* USA produces the most content
* Mature-rated content dominates the platform

---

## ⚙️ Features Created

| Feature           | Description                        |
| ----------------- | ---------------------------------- |
| Release Trends    | Used for analyzing content growth  |
| Duration Analysis | Extracted movie duration & seasons |
| Content Type      | Movie vs TV Show classification    |

---

## 💡 Recommendations

* Increase investment in TV shows
* Expand international content
* Focus on popular genres
* Release content during peak seasons
* Diversify content ratings

---

# 📈 Comparative Analysis

## 🔄 Same Workflow, Different Domains

| Step                | Customer Churn                               | Netflix Titles                         |
| ------------------- | -------------------------------------------- | -------------------------------------- |
| Data Cleaning       | Handled missing values, converted data types | Cleaned text data, handled null values |
| Feature Engineering | Tenure groups, service count                 | Duration, release trends               |
| Visualization       | Bar charts, boxplots, heatmaps               | Line plots, bar charts, pie charts     |
| Key Insight         | Contract affects churn                       | Movies dominate content                |
| Business Action     | Retention strategies                         | Content strategy                       |

---

## ⚖️ Key Differences

| Aspect        | Churn (Business)        | Netflix (Entertainment) |
| ------------- | ----------------------- | ----------------------- |
| Focus         | Customer behavior       | Content trends          |
| Data Type     | Numerical + categorical | Text + categorical      |
| Goal          | Retention               | Growth                  |
| Time Analysis | Tenure                  | Release trends          |

---

# 📊 Visualizations Gallery

## 📉 Customer Churn Visuals

* Customer churn distribution (count plot)
* Contract type vs churn (bar chart)
* Internet service vs churn (bar chart)
* Payment method impact (bar chart)
* Monthly charges distribution (histogram)
* Monthly charges vs churn (boxplot)
* Total charges vs churn (boxplot)
* Tenure distribution (histogram)
* Tenure vs churn (density plot)
* Demographic analysis (gender, senior citizen)
* Correlation heatmap
* Feature importance (bar chart)
* Confusion matrix
* ROC curve

---

## 🎬 Netflix Titles Visuals

* Movies vs TV shows (count plot)
* Movies vs TV shows (pie chart)
* Content release trend (line plot)
* Top 10 genres (bar chart)
* Top 10 countries (bar chart)
* Rating distribution (bar chart)
* Duration distribution (histogram)
* Content growth over time (line plot)
* Genre distribution (bar chart)
* Country-wise content analysis
* Word cloud of descriptions
* Content trend heatmap

---

# 🛠️ Technologies Used

| Category         | Tools                           |
| ---------------- | ------------------------------- |
| Language         | Python                          |
| Data Processing  | Pandas, NumPy                   |
| Visualization    | Matplotlib, Seaborn             |
| Machine Learning | Scikit-learn                    |
| Environment      | Jupyter Notebook / Google Colab |

---

# 📝 Presentation Topics

* Project Overview
* Data Cleaning & Feature Engineering
* Exploratory Data Analysis
* Model Building & Evaluation
* Key Insights
* Business Recommendations

---

# ✅ Key Learnings

## 🔧 Technical Takeaways

* Data cleaning is the most important step
* Feature engineering improves model accuracy
* Visualization helps understand patterns
* Proper preprocessing improves performance

---

## 💼 Business Takeaways

* Customer behavior drives churn
* Early-stage customers need attention
* Content strategy drives engagement
* Clear insights are more valuable than complex models

---

# 🎯 Final Conclusion

This project demonstrates that the **data science workflow is universal**.
Whether analyzing telecom customer churn or Netflix content trends, the same steps apply effectively.

The key difference lies in **domain knowledge**, which helps transform data into actionable insights.

---

## ⭐

If you found this project useful, give it a star!

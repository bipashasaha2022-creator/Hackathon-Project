# 🛒 NovaKart Digital Commerce System

> An AI-driven analytical and predictive framework for understanding customer interactions and predicting success outcomes in digital commerce systems.

---

## 📌 Overview

NovaKart Digital Commerce System is a machine learning and data analytics project developed to analyze structured and unstructured e-commerce interaction data.  

The project focuses on:
- Understanding customer behavior patterns
- Extracting insights from customer reviews
- Performing exploratory and statistical analysis
- Building predictive models for interaction success prediction
- Visualizing relationships between different commerce factors

This project was developed as part of a hackathon/problem-solving initiative focused on intelligent digital commerce systems.

---

## 🎯 Problem Statement

Modern e-commerce platforms generate massive amounts of customer interaction data including:
- Pricing information
- Ratings and reviews
- Delivery metrics
- Customer engagement
- Product preferences

The goal of this project is to develop a robust analytical system capable of:
1. Identifying important business factors
2. Understanding customer perceptions
3. Predicting successful interactions
4. Generating actionable business insights

---

# 📊 Dataset Features

The dataset contains both structured and unstructured data.

## Structured Features
- Price
- Discount Percent
- Average Rating
- Number of Reviews
- Delivery Time (Days)
- Customer Age
- Past Purchase Count
- Return Rate
- Time Spent on Page
- Product Category
- Brand Tier
- Customer Region
- Device Used
- Payment Method

## Unstructured Feature
- Review Text

## Target Variable
- Success Label

---

# ⚙️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| NLP | TF-IDF Vectorization |
| Notebook Environment | Google Colab / Jupyter Notebook |

---

# 🧠 Machine Learning Workflow

## 1️⃣ Data Preprocessing
- Missing value handling
- Encoding categorical variables
- Feature scaling using StandardScaler
- Text preprocessing

## 2️⃣ Feature Engineering
- One Hot Encoding
- TF-IDF Vectorization for review text
- Numerical feature standardization

## 3️⃣ Exploratory Data Analysis
- Correlation heatmaps
- Distribution plots
- Category analysis
- Success rate analysis
- Review sentiment exploration

## 4️⃣ Model Development
Implemented:
- Baseline Models
- Advanced Predictive Models

## 5️⃣ Model Evaluation
- Cross Validation Accuracy
- Classification Metrics
- Comparative Model Performance Analysis

---

# 📈 Key Insights

- Customer reviews significantly influence interaction success.
- Higher ratings generally correlate with successful outcomes.
- Discount percentage affects engagement behavior.
- Delivery time impacts customer satisfaction.
- Time spent on page provides meaningful predictive value.
- Heatmap analysis revealed strong relationships among customer interaction variables.

---

# 🔍 NLP Implementation

The project uses TF-IDF Vectorization to transform review text into meaningful numerical representations.

This helps the model understand:
- Customer sentiment
- Product perception
- Subjective experiences
- Behavioral patterns from textual reviews

---

# 📊 Visualizations Included

- Correlation Heatmaps
- Rating Distribution Graphs
- Success Label Analysis
- Category-wise Comparisons
- Pie Charts
- Feature Importance Graphs

---

# 🚀 How to Run the Project

## Clone Repository
`bash
git clone https://github.com/your-username/novakart-digital-commerce-system.git

## Open Notebook or Google colab
https://colab.research.google.com/drive/1cEcy99bdyxPuzHEUmEtoq9n9Yh5cnwQn?usp=sharing

## Install required libraries
pandas
numpy
matplotlib
seaborn
scikit=learn
nltk
wordcloud
jupyter

requirements.txt
pip install -r requirements.txt

## Conclusion
This project shows how clear and accurate analysis with a sample prediction for e-commerce sales using python

## Author
Bipasha Saha

CodeStorm Hackathon Project

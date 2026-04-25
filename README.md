# 🎫 Support Ticket Classification System

## 📌 Overview
This project focuses on automating the classification of customer support tickets using Natural Language Processing (NLP) and Machine Learning. It predicts the type of support ticket based on the ticket description and provides insights into customer support operations.

---

## 🎯 Objectives
- Classify support tickets into predefined categories
- Analyze ticket priority and response times
- Extract meaningful insights to improve support efficiency
- Reduce manual effort in ticket handling

---

## 🛠️ Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn (TF-IDF, Naive Bayes)
- Matplotlib

---

## 📂 Dataset Features
The dataset includes:
- Ticket Description (input text)
- Ticket Type (target label)
- Ticket Priority
- Ticket Channel
- Time to Resolution
- First Response Time
- Customer Satisfaction Rating

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Converted text to lowercase
- Removed special characters
- Cleaned and prepared text data

### 2. Feature Extraction
- Used TF-IDF Vectorization to convert text into numerical features

### 3. Model Training
- Applied Naive Bayes classifier
- Split dataset into training and testing sets

### 4. Model Evaluation
- Accuracy score
- Classification report (precision, recall, F1-score)

### 5. Business Analysis
- Ticket type distribution
- Priority distribution
- Channel usage
- Customer satisfaction analysis
- Response and resolution time analysis

---

## 📊 Key Insights
- Majority of tickets belong to specific categories (e.g., technical or billing issues)
- High priority tickets are resolved faster than low priority tickets
- Certain support channels handle more traffic than others
- Customer satisfaction varies across ticket types

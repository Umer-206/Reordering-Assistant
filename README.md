# 🛒 One-Click Reordering Assistant

## 📌 Project Overview
The **One-Click Reordering Assistant** is an AI-powered solution for e-commerce platforms.  
It simplifies reordering by recommending frequently purchased items and suggesting **smart bundles**.

- **Objective**: Enhance customer experience with quick reordering + bundling.  
- **Scope**: AI recommendation system + (planned) web dashboard.  
- **Developed under**: Team Next Internship Project

---

## 👥 Team Roles
- **AI Developer (Completed)** → Data collection, preprocessing, ML models for recommendations & bundling.  
- **Web Developer (Left)** → Flask web app (dashboard, API integration).  
- **App Developer (Left)** → Cross-device testing & optimization.  
- **Graphic Designer (Left)** → UI/UX design.  

✅ This repository contains the **AI Developer’s completed work**.

---

## ⚙️ AI Implementation

### 1. Data Collection
- Dataset: Public e-commerce order history (Kaggle).  
- Processed into: `amazon_preprocessed_first_100.csv` & `orders_clean_preprocessed.csv`.  

### 2. Data Preprocessing
- Cleaned & encoded data, handled missing values, derived features (order frequency, product associations).  
- Tools: Pandas, NumPy, Scikit-learn.  

### 3. ML Model – Order Recommendation
- Algorithm: Collaborative Filtering (SVD).  
- Output: `recommendations_top10.csv` (10 personalized products per user).  

### 4. ML Model – Smart Bundling
- Algorithm: Apriori (Association Rules).  
- Outputs:  
  - `frequent_itemsets.csv`  
  - `association_rules.csv`  
  - `bundles_top_pairs.csv`  
  - `bundles_top_triplets.csv`  

### 5. Testing
- Metrics: Precision, Recall, F1-score.  
- Reports:  
  - `part1_accuracy_report.csv`  
  - `part2_valid_rules_report.csv`  
- Results showed valid & strong bundling rules.

---
## 📂 Repository Structure
Reordering-Assistant/
│
├── data/ # CSV datasets
│ ├── amazon_preprocessed_first_100.csv
│ ├── orders_clean_preprocessed.csv
│
├── notebooks/ # Main AI notebook
│ └── Reordering-Assistant.ipynb
│
├── reports/ # PDF report + model outputs
│ ├── Reordering Assistant Report.pdf
│ ├── recommendations_top10.csv
│ ├── frequent_itemsets.csv
│ ├── association_rules.csv
│ ├── bundles_top_pairs.csv
│ ├── bundles_top_triplets.csv
│ ├── part1_accuracy_report.csv
│ └── part2_valid_rules_report.csv
│
├── requirements.txt # Required libraries
└── README.md # Project overview

---

## 🛠 Tools & Technologies
- **Data Handling**: Pandas, NumPy  
- **ML**: Scikit-learn, Surprise (SVD), MLxtend (Apriori)  
- **Development**: Google Colab  
- **Collaboration**: GitHub  
- **Testing**: Scikit-learn metrics  

---

## 🔖 GitHub Topics (Tags)
`machine-learning` · `recommendation-system` · `apriori` · `svd` · `ai-project` · `ecommerce` · `python`  

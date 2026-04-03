# 🎓 Data Mining & Business Intelligence Project  
## University Performance Analysis using THE Rankings Dataset

---

## 📌 Overview

This project explores global university performance using the **Times Higher Education (THE) World University Rankings dataset (2011–2016)**.  

The analysis applies **data mining and machine learning techniques** to:
- Predict university performance
- Identify patterns and relationships
- Discover natural groupings
- Generate interpretable rules

The workflow was implemented using **Orange Data Mining**, supported by preprocessing in Excel.

---

## 📊 Dataset Information

- **Source:** Times Higher Education World University Rankings  
- **Size:** 2,603 rows × 14 attributes  
- **Time Span:** 2011 – 2016  
- **Format:** CSV  

### Key Features:
- Teaching score  
- Research score  
- Citations  
- International outlook  
- Industry income  
- Total score (target variable)  
- Country, student ratios, demographics  

---

## 🎯 Objectives

- Perform **data preprocessing and cleaning**
- Conduct **exploratory data analysis (EDA)**
- Build **predictive models** (Regression & Classification)
- Apply **clustering techniques**
- Generate **association rules**
- Extract **actionable insights**

---

## ⚙️ Tools & Technologies

- **Orange Data Mining**
- Python-based ML concepts
- Excel (data cleaning)
- Visualization tools (built into Orange)

---

## 🔄 Workflow Pipeline

1. Data Cleaning (handling missing values)
2. Feature Selection
3. Data Transformation (Normalization & Encoding)
4. Exploratory Data Analysis
5. Machine Learning:
   - Regression
   - Classification
   - Clustering
   - Rule-Based Learning
6. Model Evaluation

---

## 🧹 Data Preprocessing

- Replaced missing values (`-`) with nulls
- Imputed:
  - Numerical → Mean
  - Categorical → Mode
- Normalized data to `[0,1]`
- Applied **one-hot encoding**
- Final dataset:
  - **2,603 rows**
  - **132 features**
  - No missing values

---

## 📈 Exploratory Data Analysis (EDA)

### Key Insights:
- **Right-skewed distributions** (elite universities are rare)
- Strong correlations:
  - Research ↔ Citations
  - Teaching ↔ Total Score
- Weak correlation:
  - International outlook ↔ Total Score

---

## 🤖 Machine Learning Models

### 🔹 Regression

| Model | Performance |
|------|------------|
| Linear Regression (Lasso) | Moderate accuracy |
| Random Forest | ⭐ Best performance |

**Key Finding:**  
> Research and citations are the strongest predictors of total score.

---

### 🔹 Classification

- Target: Performance tiers (High, Medium, Low)
- Models used:
  - Logistic Regression
  - Random Forest

**Results:**
- High accuracy across models
- Random Forest performed best
- Misclassifications mainly in **medium class**

---

### 🔹 Clustering

- Methods:
  - K-Means (k=3)
  - Hierarchical Clustering

**Findings:**
- Three natural clusters:
  - High-performing universities
  - Medium-performing universities
  - Low-performing universities

---

### 🔹 Association Rule Mining (CN2)

Generated interpretable rules such as:

- Low international students → Medium performance  
- Country-based performance patterns  
- High internationalization ≠ always high performance  

---

## 📊 Model Evaluation Summary

| Method | Strength | Limitation |
|--------|--------|-----------|
| Random Forest | High accuracy | Less interpreable |
| Logistic Regression | Simple | Limited complexity |
| K-Means | Clear grouping | Requires k selection |
| Hierarchical | Visual structure | Sensitive to distance |
| CN2 Rules | Interpretable | Lower predictive power |

---

## 🔍 Key Insights

1. **Research & Citations drive rankings**
2. Teaching quality strongly influences performance
3. Income impacts institutional success
4. Internationalisation has mixed effects
5. Regional patterns influence rankings

---

## 💡 Recommendations

- Invest in **research output and publications**
- Improve **teaching quality**
- Diversify **income sources**
- Balance **international student intake**
- Strengthen **global collaborations**

---

## 📖 References

- Bishop, C.M. (2006) *Pattern Recognition and Machine Learning*
- Breiman, L. (2001) *Random Forests*
- Han, J. et al. (2012) *Data Mining: Concepts and Techniques*
- Demsar, J. et al. (2013) *Orange Data Mining Toolbox*
- Times Higher Education Dataset (2016)

---

## 👥 Authors

- Omonigho Alexander Ogheneochuko  
- Walter Oluchukwu Ugwueze  
- Agun Stephen Ojeagbase  
- Christopher Frank  

---

## 📅 Submission Date

**3rd April 2026**

---

## 📌 License

This project is for academic purposes only.

---

## 🚀 How to Use

1. Clone the repository  
2. Load dataset into **Orange Data Mining**
3. Follow the workflow pipeline
4. Run models and explore results

---

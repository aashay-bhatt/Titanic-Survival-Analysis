# 🚢 Titanic Survival Analysis

This repository contains an exploratory data analysis (EDA) of the Titanic dataset.  
The project is divided into thematic notebooks to answer specific questions about survival patterns, family and social ties, and demographics.

------

## 🎯 Objectives

- Explore **survival patterns** across gender, class, and embarkation port.
- Investigate the role of **family and social structure** in survival odds.
- Analyze **age and demographic factors** to see how they influenced outcomes.
- Build clear visualizations to communicate findings.

---

## 📓 Notebooks

### 1. Survival Patterns
- What percentage of passengers survived overall?
- How does survival differ by gender and class?
- Did embarkation port affect survival?
- Are there interaction effects (e.g., gender × class)?

### 2. Family and Social Structure
- Does traveling with family (`SibSp`, `Parch`) increase survival odds?
- What is the survival rate for passengers traveling alone?
- How does survival vary with family size?
- Can engineered features like `FamilyCategory` reveal new insights?

### 3. Age and Demographics (Upcoming)
- What is the age distribution of survivors vs. non-survivors?
- Are there survival differences across age groups (children, adults, seniors)?
- How does survival vary by titles (Mr., Mrs., Miss) extracted from names?

---

## 📊 Visualizations

- Bar plots of survival by gender and class
- Histograms of family size vs. survival
- KDE plots of age distributions
- Heatmaps of survival rates by multiple features

---

## 🛠️ Tools & Libraries

- **Python** (Pandas, NumPy)
- **Seaborn** & **Matplotlib** for visualization
- **Jupyter Notebook** for analysis

---

## ✅ Next Steps

- Complete Notebook 3 (Age and Demographics).
- Add predictive modeling (logistic regression, decision trees).
- Enhance README with results and key insights.

---

## 📜 Acknowledgments

Dataset provided by [Seaborn Titanic dataset](https://seaborn.pydata.org/generated/seaborn.load_dataset.html).  
Inspired by the classic Kaggle Titanic challenge.

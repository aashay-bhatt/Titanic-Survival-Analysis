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
- Are there survival differences across age groups (children, adults, seniors)
---

## 📈 Results & Findings

### Notebook 1: Survival Patterns
- **Overall survival rate:** ~38% of passengers survived.  
- **By gender:**
  - Female survival rate: ~74%  
  - Male survival rate: ~19%  
- **By class:**
  - First Class survival rate: ~63%  
  - Second Class survival rate: ~47%  
  - Third Class survival rate: ~24%  
- **By embarkation port:**
  - Cherbourg passengers had the highest survival rate (~55%).  
  - Southampton passengers had the lowest (~33%).  

### Notebook 2: Family and Social Structure
- **Traveling alone vs. with family:**
  - Alone survival rate: ~30%  
  - With family survival rate: ~50%  
- **Family size effect:**
  - Small families (2–4 members) had better survival odds than very large families (>5).  
- **Engineered feature (`family_status`):**
  - Passengers labeled `"with family"` showed consistently higher survival rates compared to `"alone"`.
 
### Notebook 3: Age and Demographics
- Age distribution: Children had significantly higher survival rates compared to adults and seniors
- Age groups: Survival odds declined with age, especially for men
- Demographic insights: Younger passengers and women had the strongest survival advantage

---

## 📊 Visualizations

- Bar plots of survival by gender and class
- Histograms of family size vs. survival
- Heatmaps of survival rates by multiple features

---

## 🛠️ Tools & Libraries

- **Python** (Pandas, NumPy)
- **Seaborn** & **Matplotlib** for visualization
- **Jupyter Notebook** for analysis

---

## 📜 Acknowledgments

Dataset provided by [Seaborn Titanic dataset](https://seaborn.pydata.org/generated/seaborn.load_dataset.html).  
Inspired by the classic Kaggle Titanic challenge.

# Titanic Dataset Exploratory Data Analysis (Task 2 - Elevvo Training)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the classic Titanic dataset from Kaggle.  
The goal is to analyze survival patterns and generate insights using Python, Pandas, Seaborn, and Matplotlib.

---

---

## Tools & Libraries
- Google colab
- Python 3.x  
- Pandas  
- Seaborn  
- Matplotlib  
- Numpy  

> All libraries are commonly used for data analysis and visualization in Python.

---

## Key Analyses
1. **Data Cleaning & Handling Missing Values**  
   - Removed or imputed missing values in `Age`, `Embarked`, `Cabin`  
   - Standardized `Sex` column  

2. **Survival Analysis**  
   - By **Gender** → Bar plot showing survival %  
   - By **Passenger Class (Pclass)** → Survival % by class  
   - By **Age Groups** → Children, Teens, Adults, Seniors  
   - By **Family Size** → Survival vs family size  

3. **Correlation Analysis & Heatmap**  
   - Pearson correlation matrix of numerical features  
   - Visualized using a **full blue heatmap** with annotations for clear insights  

---

## Insights
- Females had higher survival rates than males  
- Passengers in higher classes (Pclass=1) survived more  
- Children and adults in small to medium families had higher survival  
- Large families or passengers alone had lower survival rates  
- Fare and Family Size have slight positive correlation with survival  

---

## Dataset
- Kaggle Titanic Dataset: [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)  
- If included locally: `data/train.csv`

---

## How to Run
1. Clone this repository:
```bash
git clone <[https://github.com/ShaimaaMahmoud-6/Titanic_EDA_Eleevo]>

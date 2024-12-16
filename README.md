# Titanic-Survival-Prediction
This project analyzes the Titanic dataset to determine survival probabilities based on passenger attributes. It involves data cleaning, exploratory data analysis (EDA), feature engineering, and training machine learning models to compare their performance.

## 🔍 Data Source

The dataset includes the following key variables:

- **Survived:** 0 = No, 1 = Yes  
- **Pclass:** Ticket class (1st, 2nd, 3rd)  
- **Sex:** Gender of passenger  
- **Age:** Age in years  
- **SibSp:** Number of siblings/spouses aboard  
- **Parch:** Number of parents/children aboard  

For further details, refer to the complete project documentation.

---

## 🚀 Implementation Workflow

1. **Data Cleaning & Preparation**
   - Handling missing values for `Age` and removing irrelevant columns like `Cabin` and `Name`.
   - Encoding categorical variables like `Sex` and `Pclass` using dummy variables.

2. **Exploratory Data Analysis**
   - Visualized relationships between survival rate, gender, passenger class, and age.
   - Identified significant correlations:
     - Females had a **74% survival rate**.
     - 1st class passengers had a higher chance of survival.

3. **Machine Learning Models**
   - Decision Tree: Accuracy **87%**  
   - Logistic Regression: Accuracy **80%**  
   - Naive Bayes: Accuracy **81.8%**  
   - K-Nearest Neighbors (KNN): Accuracy **85.3%**

---

## 📈 Visualizations

1. **Survival by Gender**  
   - Females had a significantly higher survival rate.

2. **Survival by Passenger Class**  
   - 1st Class passengers were more likely to survive.

3. **Age Distribution**  
   - Most passengers were aged **20 to 40**.

---

## 🛠️ Technologies Used

- **R Programming**
- Libraries: `rpart`, `e1071`, `class`, `dplyr`, `ggplot2`

---

## 📊 Results

- Decision Tree outperformed other models with an accuracy of **87%**.
- Logistic Regression, Naive Bayes, and KNN also showed strong performance.

---

## 📝 Conclusion

The analysis revealed clear patterns:
1. Females and 1st-class passengers had higher survival rates.
2. Decision Trees proved most effective for this dataset, but ensemble methods like **Random Forest** could further enhance accuracy.

---

## 🔗 Download Project Files

You can access the complete project source code and documentation here:  
📥 [Download Titanic Survival Project](#)

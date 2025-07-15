

# 🚢 Titanic Data Analysis using Python

This project involves an in-depth **exploratory data analysis (EDA)** on the iconic Titanic dataset. The goal is to understand passenger demographics, survival patterns, and critical factors that influenced outcomes during the tragic sinking of the Titanic.

---

## 📌 Project Highlights

### ✅ **Dataset Overview**

* **Rows:** 891 passengers
* **Key Features:** Age, Sex, Fare, Passenger Class, Embarkation Port, Cabin, Family Details

### 🔍 **Data Preprocessing**

* Checked for null values (`Age`, `Cabin`, and `Embarked` had missing entries)
* Performed initial statistical summary using `.info()` and `.describe()`
* Median and distribution analysis of numerical columns
* Identified outliers and anomalies, particularly in `Fare` and `Age`

---

## 📊 Visual Analysis

### 📈 Univariate & Bivariate Visualizations

* **Histograms & KDEs** for continuous features (Age, Fare)
* **Boxplots** for detecting outliers
* **Bar plots** for survival rate by:

  * Sex
  * Passenger Class (`Pclass`)
  * Embarkation Port (`Embarked`)
  * Siblings/Spouses (`SibSp`) and Parents/Children (`Parch`)

### 🧩 Correlation & Relationships

* **Correlation heatmap** for numeric variables
* **Pairplots** to study feature interactions
* **Stacked histograms** of `Age` vs `Survived`

---

## 🧠 Key Insights

* **Gender Matters:** Females had a much higher survival rate than males — clear evidence of the "women and children first" policy.
* **Class Disparity:** First-class passengers were more likely to survive than those in third class, reflecting socio-economic influences.
* **Age Factor:** Children under 10 had better chances of survival; most deaths occurred among adults aged 20–40.
* **Fare Outliers:** Passengers who paid high fares (>\$300) were mostly survivors — mostly first-class.
* **Family Size:** Survival was higher for passengers traveling with 1–2 family members. Those alone or with large families had lower chances.
* **Embarkation Impact:** Passengers from Cherbourg had higher survival rates than those who boarded at Southampton.

---

## 📁 Technologies Used

* **Python**
* **Pandas**, **Seaborn**, **Matplotlib**
* **Plotly** (for interactive visualizations)

---

## 🔗 Notebook Access

All analyses and visuals were executed using Jupyter/Google Colab.

> You can run the notebook interactively using this dataset: `Titanic-Dataset.csv`

---

## 💡 What's Next?

* Feature engineering for machine learning
* Classification model to predict survival
* Handling missing values (Cabin) using advanced imputation

---

### 🧾 Conclusion

This analysis of the Titanic dataset not only uncovers deep patterns in passenger survival but also serves as a solid foundation for building predictive models and understanding the power of exploratory data analysis in real-world datasets.

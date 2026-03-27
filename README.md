# 🏥 Health Data Analysis using Inferential Statistics

## 📌 Project Overview

This project focuses on applying **inferential statistical techniques** to analyze a healthcare dataset. The goal is to evaluate multiple hypotheses and identify significant factors affecting disease occurrence such as diabetes and hypertension.

The analysis includes hypothesis testing, confidence intervals, correlation analysis, and statistical tests like T-test, Chi-square, and ANOVA.

---

## 🎯 Objective

* Apply inferential statistics to real-world health data
* Perform hypothesis testing and draw conclusions
* Identify relationships between lifestyle factors and diseases

---

## 📊 Dataset Description

The dataset contains health records of individuals with the following attributes:

* Age, Age Group
* Gender, Region
* Smoking Status
* Exercise Frequency
* BMI (Body Mass Index)
* Blood Pressure
* Diabetes (True/False)
* Hypertension (True/False)
* Cholesterol Level
* Glucose Level
* Visit Date

---

## 🧠 Theoretical Concepts Covered

* Inferential Statistics
* Hypothesis Testing
* Confidence Interval
* P-value
* Type I & Type II Errors
* T-test, Chi-Square Test, ANOVA
* Covariance & Correlation

---

## 🔍 Hypotheses Formulated

### 1. Smoking vs BMI

* H₀: No significant difference in BMI between smokers and non-smokers
* H₁: Significant difference in BMI exists

### 2. Smoking vs Diabetes

* H₀: Smoking and diabetes are independent
* H₁: Smoking affects diabetes

### 3. Age Group vs Glucose Level

* H₀: Mean glucose levels are equal across age groups
* H₁: At least one age group differs

### 4. Age vs BMI

* H₀: No correlation between age and BMI
* H₁: Correlation exists

---

## ⚙️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* SciPy

---

## 📈 Statistical Analysis Performed

### ✅ Confidence Interval

* 95% Confidence Interval (Age): **(41.21, 44.06)**
* Indicates the true population mean age lies within this range

---

### ✅ T-Test (BMI: Smokers vs Non-Smokers)

* P-value: **0.9083**
* Result: Fail to reject H₀
* Conclusion: No significant difference in BMI

---

### ✅ Chi-Square Test (Smoking vs Diabetes)

* P-value: **0.0643**
* Result: Fail to reject H₀
* Conclusion: No significant association (borderline case)

---

### ✅ ANOVA Test (Age Group vs Glucose)

* P-value: **7.33e-14**
* Result: Reject H₀
* Conclusion: Significant difference in glucose levels across age groups

---

### ✅ Correlation & Covariance (Age vs BMI)

* Covariance: **19.69**
* Correlation: **0.35**
* Conclusion: Moderate positive relationship

---

## 📊 Key Insights

* Smoking does not significantly affect BMI
* Weak evidence of relationship between smoking and diabetes
* Age has a strong impact on glucose levels
* BMI slightly increases with age
* Health outcomes depend on multiple factors

---

## 📌 Conclusion

The analysis demonstrates that while some lifestyle factors like smoking show limited statistical impact, age plays a significant role in influencing glucose levels. The study highlights the importance of applying appropriate statistical techniques to derive meaningful insights from healthcare data.

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy scipy
   ```
3. Run the Python script or Jupyter Notebook

---

## 💼 Project Value

This project showcases:

* Practical application of statistical concepts
* Data analysis and interpretation skills
* Real-world problem-solving ability

---

## 👨‍💻 Author

**Yakshraj Gohil**

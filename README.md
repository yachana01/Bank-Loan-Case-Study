# 📊 Bank Loan Case Study (Excel EDA Project)

## 🔍 Project Overview
 This project analyses loan application data to identify patterns that 
influence the likelihood of loan default focusing on understanding the key factors and 
customer behaviour behind loan default.

The objective of this project is to perform **Exploratory Data Analysis (EDA)** in Excel to uncover patterns, detect risks, and ensure that capable applicants are not unfairly rejected.  

---

## 🛠️ Tasks Performed

### **A. Identify Missing Data**
- Used `COUNTBLANK()` to identify missing values in the dataset.  
- Highlighted columns with more than **60% missing values** using **Conditional Formatting**.  
- For columns with **<40% missing values**:
  - Numerical columns: imputed using **AVERAGE()**.  
  - Categorical columns: replaced with `"Unknown"`.  

### **B. Identify Outliers**
- Detected outliers in numerical variables using:
  - **Quartiles (`QUARTILE()` function)**  
  - **Interquartile Range (IQR)** method.  

### **C. Analyze Data Imbalance**
- Checked **class imbalance** in target variable (loan approval status).  
- Used **Pivot Tables** and Excel formulas to calculate imbalance ratio.  

### **D. Perform Data Analysis**
- **Univariate Analysis:** Distribution of income range, loan amount range, age range, etc.  
- **Segmented Univariate Analysis:** Compared applicant attributes (income, loan amount, age) with the target variable.  
- **Bivariate Analysis:** Compared income range with average credit amount using Pivot Tables & Charts.  

### **E. Identify Top Correlations**
- Calculated correlations for numerical variables using Excel’s **CORREL()** function.  
- Visualized correlations with **Conditional Formatting heatmaps**.  

---

## 📈 Key Insights
- Applicants with **good credit history** had higher approval rates.  
- **Income-to-loan ratio** strongly predicted repayment ability.  
- Certain groups (e.g., self-employed with no credit history) showed **higher default risk**.  

---

## 🖥️ Tools & Skills Used
- **Excel Functions:** COUNTBLANK, AVERAGE, QUARTILE, CORREL.  
- **Excel Features:** Pivot Tables, Pivot Charts, Conditional Formatting, Data Cleaning.  
- **Techniques:** Missing Value Treatment, Outlier Detection, Data Imbalance Check, Univariate & Bivariate EDA, Correlation Analysis.  

---

## 📊 Dashboard & Visualizations
Built interactive Excel charts for:
- columns for missing values more than 60%
- outlier scatter plots for the client's income, client's employment years and number of children the client has
- column chart univariate analysis for number of applicants for income range, loan amount range and age range
- column chart segmented univariate analysis for target for income range, loan amount range and age range
- bivariate analysis with average credit amount with income range
- top correlation with conditional formatting  
- Applicant demographic breakdowns.  

---

## 🚀 Impact
- Helped identify **high-risk applicants** early.  
- Reduced loan default rates by detecting key risk factors.  
- Ensured that **eligible applicants** were not rejected due to insufficient credit history.  

---


## ✅ Author
Yachana Tamang | [LinkedIn](www.linkedin.com/in/yachana01) | [GitHub](github.com/yachana01)

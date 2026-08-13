# HR Data Analysis and EDA

## 📌 Project Overview

This project focuses on cleaning, analyzing, and visualizing an HR dataset using Python. The project demonstrates the complete data analysis process, from handling messy data to generating meaningful insights through visualizations.

## 🎯 Objectives

* Clean and prepare the HR dataset
* Handle missing and inconsistent data
* Convert columns to appropriate data types
* Perform Exploratory Data Analysis (EDA)
* Analyze employee demographics, salaries, performance, and joining trends
* Create meaningful visualizations
* Identify patterns and relationships in the data

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Dataset

The dataset contains HR-related information such as:

* Name
* Age
* Salary
* Gender
* Department
* Position
* Joining Date
* Performance Score
* Email
* Phone Number

## 🧹 Data Cleaning

The following data-cleaning tasks were performed:

* Checked missing values
* Cleaned and converted numerical columns
* Converted `Joining Date` into datetime format
* Handled mixed date formats
* Handled missing email and phone number values
* Checked categorical values
* Checked duplicate records
* Validated the cleaned dataset

## 📊 Exploratory Data Analysis

### Univariate Analysis

* Employee distribution by department
* Employee distribution by gender
* Age distribution
* Salary distribution
* Employee distribution by performance score
* Number of employees who joined each year

### Bivariate Analysis

* Average salary by department
* Salary distribution by department
* Relationship between age and salary
* Average salary by position

### Multivariate Analysis

* Average salary by department and gender
* Age vs Salary by department

### Correlation Analysis

A correlation heatmap was created to analyze relationships between:

* Age
* Salary
* Performance Score

The analysis showed an almost negligible linear relationship between Age and Salary.

## 🔍 Key Insights

* Gender distribution is relatively balanced.
* Most employees are between 35 and 40 years old.
* Salaries are mainly concentrated around ₹58,000–₹62,000.
* Average salaries across departments are relatively similar.
* Average salaries across positions are also relatively similar.
* Employee joining increased from 2018 to 2020.
* Age and Salary have almost no linear correlation.
* Salary differences across genders and departments are relatively small.

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/HR-Data-Analysis-and-EDA.git
```

2. Open the project folder.

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the notebook:

```bash
jupyter notebook
```

5. Run `handle_messy_HR_data.ipynb`.

## 📌 Conclusion

This project demonstrates the complete workflow of an HR data analysis project, including data cleaning, exploratory analysis, visualization, correlation analysis, and interpretation of findings.

---

**Created using Python 🐍 | Pandas | Matplotlib | Seaborn**

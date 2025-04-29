# Employee Attrition Project

---

## 🔗 Project Overview

This project focuses on analyzing Employee Attrition using a large real-world dataset with **~1 lakh rows**.

The project is divided into two phases:
- **Data Cleaning and Feature Engineering** using **Python (Jupyter Notebook)**
- **Data Visualization** using **Power BI** to create an interactive and insightful dashboard.

---

## 📉 Tools Used

- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Power BI Desktop
- GitHub

---

## 💡 Project Highlights

### Data Cleaning and Preparation (Python)

- **Handled missing values** across multiple columns using median/mode imputation.
- **Fixed data types** (e.g., converted MonthlyIncome to numeric).
- **Removed duplicate rows**.
- **Treated outliers** using **IQR Method** (Age and MonthlyIncome).
- **Cleaned categorical columns** (standardized text casing, spelling corrections).

### Feature Engineering (Python)

- **Tenure Group**: Categorized YearsAtCompany into New, Junior, Mid, Senior groups.
- **Income Category**: Created Low, Medium, High income segments.
- **Satisfaction Average**: Averaged EnvironmentSatisfaction and JobSatisfaction scores.
- **OverTime Flag**: Converted OverTime Yes/No into binary 1/0.

**Final Cleaned Dataset** saved as: `employee_attrition_cleaned.csv`

---

### Data Visualization (Power BI)

- **KPIs:**
  - Total Employees
  - Attrition Rate
  - Average Monthly Income

- **Visuals:**
  - Pie Chart: Attrition by Gender
  - Bar Chart: Attrition by Department
  - Stacked Column Chart: Attrition Distribution by Tenure Group
  - Clustered Column Chart: Attrition by Income Category
  - Line Chart: Average Monthly Income by Age
  - Clustered Bar Chart: Attrition by Job Role

- **Slicers:**
  - Department
  - Gender
  - Income Category
  - Attrition

**Power BI File:** `Employee_Attrition_Analysis.pbix`  
**Dashboard Screenshot:** `dashboard.png`

---

## 🌟 Key Insights

- Higher attrition seen among "New" and "Junior" tenure groups.
- Sales department and low-income employees show higher attrition.
- Younger employees tend to have lower salaries, which could correlate with higher attrition risk.
- Certain job roles like Sales Executive show a relatively higher attrition rate.

---

## 📂 Folder Structure

```bash
Employee Attrition Project/
├── Employee Attrition Project.ipynb      # Python Notebook
├── employee_attrition_cleaned.csv        # Cleaned Data
├── Employee_Attrition_Analysis.pbix      # Power BI Dashboard
├── dashboard.png                         # Dashboard Screenshot (optional)
├── README.md                             # This file

# 📊 HR Analytics Dashboard

An interactive HR Analytics Dashboard built using **Power BI** to analyze employee attrition, workforce demographics, salary distribution, and other key HR metrics. This dashboard helps HR professionals identify trends and make data-driven decisions to improve employee retention.

---

## 📸 Dashboard Preview

<img width="1325" height="729" alt="dashboard" src="https://github.com/user-attachments/assets/b85ebca5-c9af-46bf-88cc-c8707f2a8d96" />


---

## 🎯 Project Objective

The objective of this project is to analyze HR data and uncover insights related to employee attrition. The dashboard enables users to monitor workforce statistics, identify high-risk employee groups, and understand the factors contributing to employee turnover.

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel / CSV Dataset**

---

## 📁 Dataset

- **Dataset:** IBM HR Analytics Employee Attrition Dataset
- **Total Employees:** 1470
- **Records:** Employee-level HR data including:
  - Age
  - Department
  - Job Role
  - Gender
  - Education
  - Monthly Income
  - Years at Company
  - Attrition Status
  - Job Satisfaction
  - Performance Rating
  - And other HR-related attributes

---

## 📈 Dashboard Features

### KPI Cards
- 👥 Total Employees
- 🚪 Total Attrition
- 📉 Attrition Rate
- 🎂 Average Age
- 💰 Average Salary
- 📅 Average Years at Company

### Visualizations
- Attrition by Gender
- Attrition by Education Field
- Attrition by Age Group
- Attrition by Salary Slab
- Attrition by Job Role
- Attrition by Years at Company
- Employee Distribution by Job Role
- Department Filter (HR, R&D, Sales)

---

## 📊 DAX Measures Used

Some of the DAX measures used in this project include:

```DAX
Overall Employees = COUNT(HR_Analytics[EmployeeNumber])

Attrition = CALCULATE(
    COUNTROWS(HR_Analytics),
    HR_Analytics[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE([Attrition], [Overall Employees]) * 100

Average Age =
AVERAGE(HR_Analytics[Age])

Average Salary =
AVERAGE(HR_Analytics[MonthlyIncome])

Average Years at Company =
AVERAGE(HR_Analytics[YearsAtCompany])
```

---

## 🔍 Key Business Insights

- Employees earning **less than ₹5K/month** have the highest attrition.
- The **Sales Representative** role experiences one of the highest attrition rates.
- Employees with **1–3 years of experience** are more likely to leave the organization.
- **Life Sciences** graduates account for the largest share of employee attrition.
- The majority of employees fall within the **26–35 age group**.
- Attrition is slightly higher among **male employees** compared to female employees.

---

## 💡 Skills Demonstrated

- Data Cleaning using Power Query
- Data Modeling
- DAX Calculations
- KPI Development
- Dashboard Design
- Interactive Filtering
- Business Intelligence
- Data Visualization
- HR Analytics

---

## 📂 Repository Structure

```
HR-Analytics-Dashboard/
│
├── HR Analytics Dashboard.pbix
├── HR_Analytics.csv
├── README.md
└── images/
    └── dashboard.png
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Refresh the dataset if required.
4. Explore the interactive dashboard using the department filters and visuals.

---

## 📷 Dashboard Screenshot

<img width="1325" height="729" alt="dashboard" src="https://github.com/user-attachments/assets/b85ebca5-c9af-46bf-88cc-c8707f2a8d96" />

---

## 📌 Future Improvements

- Add drill-through pages for employee-level analysis.
- Create report tooltips for enhanced user interaction.
- Include trend analysis using historical HR data.
- Integrate with Power BI Service for scheduled refresh.
- Add predictive analytics to estimate employee attrition risk.

---

## 👨‍💻 Author

**Kanishka Dwivedi**

BCA Student | Aspiring Data Analyst

### Skills

- Power BI
- SQL
- Python
- Excel
- DAX
- Power Query
- Data Visualization

---

## ⭐ If you found this project useful, consider giving it a star!

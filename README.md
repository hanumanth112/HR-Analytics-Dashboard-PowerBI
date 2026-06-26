# 📊 HR Analytics Dashboard | Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Project Overview

The **HR Analytics Dashboard** is an interactive Business Intelligence solution developed using **Power BI**, **DAX**, and **Power Query** to analyze employee attrition, workforce demographics, salary distribution, job satisfaction, and department performance.

This project transforms raw HR data into meaningful insights through interactive dashboards, enabling HR teams and business leaders to make informed, data-driven workforce decisions.

---

# 📸 Dashboard Preview

The dashboard provides an interactive overview of workforce metrics, employee attrition, salary distribution, demographics, and departmental performance.

![HR Analytics Dashboard](Images/HR_Dashboard.png)

---

# 🎯 Business Problem

Employee attrition directly impacts organizational productivity, recruitment costs, and workforce planning. HR teams require an interactive reporting solution to identify trends, monitor employee metrics, and improve retention strategies.

This dashboard helps answer key business questions such as:

- What is the overall employee attrition rate?
- Which departments have the highest employee turnover?
- Which salary slabs experience the highest attrition?
- Which age groups make up the workforce?
- How does job satisfaction influence employee attrition?
- Which departments have the highest employee count?

---

# 📊 Dataset Information

| Property | Details |
|----------|----------|
| Records | 1,470+ Employees |
| Columns | 37 |
| File Format | CSV |
| Dashboard Tool | Power BI Desktop |

### Dataset Includes

- Employee ID
- Age
- Gender
- Department
- Job Role
- Education
- Business Travel
- Job Satisfaction
- Monthly Income
- Salary Slab
- Total Experience
- Years at Company
- Attrition
- Marital Status
- Overtime

---

# 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- CSV Dataset

---

# ⭐ Project Highlights

- Built an interactive HR Analytics Dashboard using Power BI.
- Developed KPI cards using DAX measures.
- Performed data cleaning and transformation using Power Query.
- Created dynamic slicers for Age Groups and Departments.
- Designed multiple business-focused visualizations.
- Converted raw HR data into actionable business insights.

---

# 📈 Dashboard KPIs

- 👥 Total Employees
- ✅ Active Employees
- ❌ Attrition Count
- 📉 Attrition Rate
- 🎂 Average Employee Age
- 💼 Average Experience

---

# 📊 Dashboard Features

- Department-wise Attrition Analysis
- Salary Slab Analysis
- Job Satisfaction Matrix
- Department-wise Employee Count
- Employee Age Distribution
- Gender-wise Attrition Analysis
- Experience Trend Analysis
- Interactive Department Filter
- Dynamic Age Group Slicer

---

# 🧹 Data Cleaning & Transformation

Data preprocessing was performed using **Power Query**.

### Tasks Performed

- Removed unnecessary columns
- Verified missing values
- Corrected data types
- Standardized categorical values
- Created Age Groups
- Created Salary Slab categories
- Prepared data model for reporting

---

# 📐 DAX Measures

```DAX
Total Employees =
COUNT(HR[EmpID])

Attrition Count =
CALCULATE(
COUNT(HR[EmpID]),
HR[Attrition] = "Yes"
)

Active Employees =
[Total Employees] - [Attrition Count]

Attrition Rate =
DIVIDE([Attrition Count],[Total Employees])

Average Age =
AVERAGE(HR[Age])

Average Experience =
AVERAGE(HR[TotalExperienceYears])
```

---

# 📈 Key Business Insights

- Employee Attrition Rate is **16.3%**
- Operations has the largest workforce.
- Lower salary slabs experience higher employee attrition.
- Employees aged **26–35 years** represent the largest workforce segment.
- Male employees account for the majority of employees.
- Lower job satisfaction is associated with higher employee attrition.

---

# ❓ Business Questions Answered

- Which department experiences the highest attrition?
- Which salary category has the highest employee turnover?
- Which employee age group is the largest?
- How does job satisfaction relate to employee attrition?
- Which departments employ the most people?
- What is the organization's overall attrition rate?

---

# 🔄 Project Workflow

```text
Raw HR Dataset
        │
        ▼
Power Query
(Data Cleaning & Transformation)
        │
        ▼
Data Modeling
        │
        ▼
DAX Measures
        │
        ▼
Interactive Dashboard
        │
        ▼
Business Insights & KPI Reporting
```

---

# 💼 Skills Demonstrated

- Power BI
- DAX
- Power Query
- Data Cleaning
- Data Transformation
- Data Modeling
- Dashboard Design
- Data Visualization
- Business Intelligence
- HR Analytics
- KPI Reporting

---

# 📁 Repository Structure

```
HR-Analytics-Dashboard-PowerBI
│
├── Dashboard
│   └── HR_Analytics_Dashboard.pbix
│
├── Dataset
│   └── HR_Analytics_Dataset.csv
│
├── Images
│   └── HR_Dashboard.png
│
├── README.md
└── LICENSE
```

---

# 🚀 Future Enhancements

- Employee Performance Dashboard
- Recruitment Analytics Dashboard
- Monthly Attrition Trend Analysis
- Predictive Attrition using Machine Learning
- Department Drill-through Reports

---

# 💼 Resume Project Summary

Designed and developed an interactive HR Analytics Dashboard using Power BI, DAX, and Power Query to analyze employee attrition, workforce demographics, salary distribution, job satisfaction, and departmental performance. Built KPI reports, interactive dashboards, and business insights to support data-driven HR decision-making.

---

# 👨‍💻 Author

## Hanumantha B

**Aspiring Data Analyst | SQL | Python | Power BI | Excel**

### GitHub

https://github.com/hanumanth112

### LinkedIn

https://www.linkedin.com/in/hanumantha-b-673938374

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!

# HR-Analytcs
👥 HR Analytics Dashboard
**Power BI · DAX · Human Resources · Employee Attrition Analysis**

![Power BI Dashboard](https://github.com/abhisheknirmal02-lab/HR-Analytcs/blob/main/HR%20Anaytics.pbit)
![DAX Code](https://github.com/abhisheknirmal02-lab/HR-Analytcs/blob/main/HR%20Analatics%20DAX.xlsx)
![HR Analytics Data](https://github.com/abhisheknirmal02-lab/HR-Analytcs/blob/main/HR%20Analatics.csv)

---

## 📌 Project Overview

An interactive Power BI dashboard analysing **employee attrition patterns** across a workforce of **1,470 employees**. The report surfaces attrition rates by department, education field, age group, and gender — equipping HR teams with actionable intelligence to reduce turnover and improve retention strategies.

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Overall Employees | 1,470 |
| Total Attrition | 237 |
| Attrition Rate | 16.12% |
| Active Employees | 1,233 |
| Average Age | 36.92 |

---

## 🧮 DAX Measures

```dax
Active Employees = SUM(Sheet1[Employee Count]) - SUM(Sheet1[Attrition count])

Attrition Rate   = SUM(Sheet1[Attrition count]) / SUM(Sheet1[Employee Count])
```

Both measures respond dynamically to the Education filter (Associates · Bachelor's · Doctoral · High School · Master's Degree).

---

## 🔍 Analytical Findings

**Department-wise Attrition**
- R&D leads at **56.12%** (133 employees) — biggest retention challenge
- Sales follows at **38.82%** (92 employees)
- HR has the lowest attrition at **5.06%** (12 employees)

**Age Group Analysis**
- **25–34** has the highest absolute attrition count at 112 employees
- **Under 25** has the highest attrition rate — 61.61% male
- **35–44 females** show 72.55% attrition — highest female bracket

**Education Field**
- **Life Sciences** (89) and **Medical** (63) are the top attrition fields
- **Sales Representatives** show the lowest job satisfaction scores (rating 1–2 dominant)

---

## 💡 Business Recommendations

- Focus retention on **R&D** — 56% of all attrition; investigate workload & career growth
- Introduce **early-career mentoring** for the 25–34 band — highest leaver count
- Review **Sales Representative satisfaction** — consistently low engagement scores
- Investigate **female attrition spike in 35–44** — possible flexibility or progression issues
- Develop targeted career paths for **Life Sciences & Medical graduates**

---

## 🛠 Tools & Techniques

`Power BI Desktop` `DAX Measures` `Data Modelling` `HR Analytics` `Attrition Analysis`
`KPI Cards` `Donut Charts` `Clustered Bar Charts` `Matrix Table` `Education Slicer` `Age Band Analysis`

---

## 📁 Repository Files

| File | Description |
|---|---|
| ![HR Analytics Dashboard.pbix](https://github.com/abhisheknirmal02-lab/HR-Analytcs/blob/main/HR%20Anaytics.pbit) | Power BI template — single-page interactive dashboard |
| [HR_Analatics_DAX.xlsx](https://github.com/abhisheknirmal02-lab/HR-Analytcs/blob/main/HR%20Analatics%20DAX.xlsx) | DAX measures documented |

---

## 🖼️ Dashboard Preview

![HR Analytics Dashboard](https://github.com/abhisheknirmal02-lab/HR-Analytcs/blob/main/HR%20Analytics.png)

---

📁 `.pbit` included &nbsp;|&nbsp; 🧮 2 DAX measures &nbsp;|&nbsp; 📦 1,470 employee records &nbsp;|&nbsp; 👤 Data Analyst portfolio project**

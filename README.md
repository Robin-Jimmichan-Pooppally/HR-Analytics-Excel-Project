# 📊 HR Analytics Dashboard – Employee Attrition & Retention Insights

[![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoft-excel)](https://www.microsoft.com/excel)
[![HR Analytics](https://img.shields.io/badge/Type-Attrition_Analysis-blue)](https://github.com)
[![Workforce Analytics](https://img.shields.io/badge/Analysis-Employee_Retention-orange)](https://github.com)

A comprehensive Excel solution built to analyze employee attrition patterns and identify key factors influencing resignation and retention. It transforms raw employee-level data into actionable insights — enabling HR teams to understand why employees leave, identify high-risk segments, and develop targeted retention strategies to improve workforce stability.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Dataset Description](#dataset-description)
- [Tools Used](#tools-used)
- [Key Metrics Calculated](#key-metrics-calculated)
- [Dashboard Insights](#dashboard-insights)
- [Installation & Prerequisites](#installation--prerequisites)
- [How to Use](#how-to-use)
- [Strategic Insights](#strategic-insights)
- [Tech Stack](#tech-stack)
- [Skills Demonstrated](#skills-demonstrated)

---

## 📊 Project Overview

This Excel project provides an **interactive analysis of employee attrition patterns and retention drivers** using pivot tables, pivot charts, and calculated metrics. It enables monitoring of:

- 📈 **Overall employee attrition rate** (Resigned vs Stayed percentage)
- 👥 **Attrition by age group** (Resignation trends across age demographics)
- 🏢 **Department-wise attrition** (Departmental turnover analysis)
- 💼 **Job role-wise attrition** (Role-specific resignation patterns)
- 😊 **Job satisfaction vs attrition** (Correlation between satisfaction and turnover)
- ⚖️ **Work-life balance vs attrition** (Balance rating impact on retention)
- 💰 **Income band-wise attrition** (Salary range and turnover correlation)
- 📊 **Job level-wise attrition** (Hierarchical level resignation patterns)

---

## 🎯 Project Objective

To analyze employee attrition patterns and identify key factors influencing resignation and retention:

✅ **Identify attrition drivers** across employee demographics and roles  
✅ **Segment high-risk employee groups** for targeted interventions  
✅ **Analyze satisfaction and work-life balance** impact on retention  
✅ **Evaluate departmental and role-specific attrition patterns**  
✅ **Generate actionable insights** for HR retention strategies  
✅ **Support data-driven decision-making** in workforce planning  

---

## ⚙️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data organization, analysis, dashboard creation |
| **Pivot Tables** | Employee segmentation and attrition aggregation |
| **Pivot Charts** | Visual attrition trends (Bar Charts, Pie Charts) |
| **Conditional Formatting** | Data highlighting and performance indicators |
| **Slicers** | Dynamic filtering for dimensional analysis |
| **Data Visualization** | Clear presentation of attrition patterns |

---

## 📁 Dataset Description

### Dataset Overview

The dataset contains employee-level information including demographics, job details, satisfaction metrics, and attrition status. Each record represents one employee with comprehensive HR attributes.

### Columns Included

| Column | Description |
|--------|-------------|
| **Age Group** | Employee age range category |
| **Department** | Organizational department assignment |
| **Job Role** | Specific job title or function |
| **Job Level** | Hierarchical level in organization |
| **Job Satisfaction** | Satisfaction score (1–5 scale) |
| **Work-Life Balance** | Work-life balance rating (1–4 scale) |
| **Monthly Income** | Salary in specified income range |
| **Attrition** | Employment status (Stayed / Resigned) |

---

## 📈 Key Metrics Calculated

| Metric | Description |
|--------|-------------|
| **Overall Attrition Rate** | % of employees who resigned |
| **Department-wise Attrition** | Resignation trend by department |
| **Job Role-wise Attrition** | Attrition patterns across job titles |
| **Age Group-wise Attrition** | Comparison of resignation trends by age |
| **Satisfaction-based Attrition** | Attrition distribution by job satisfaction scores |
| **Work-Life Balance vs Attrition** | Correlation between balance rating and turnover |
| **Income Band-wise Attrition** | Attrition rate by salary range |
| **Job Level-wise Attrition** | Attrition across employee hierarchy levels |

---

## 📈 Dashboard Insights

### 1️⃣ Overall Employee Attrition

**Attrition Rate:** 11.05%

| Status | Percentage |
|--------|-----------|
| **Resigned** | 11.05% |
| **Stayed** | 88.95% |

**Insight:** A low overall attrition rate indicates good retention, but a focused strategy can further improve employee longevity.

---

### 2️⃣ Attrition by Age Group

| Age Group | Resigned (%) | Stayed (%) |
|-----------|--------------|-----------|
| **21–25** | 12.93% | 87.07% |
| **26–30** | 11.86% | 88.14% |
| **31–35** | 10.02% | 89.98% |
| **36–40** | 11.50% | 88.50% |
| **41–45** | 8.00% | 92.00% |
| **46–50** | 9.43% | 90.57% |
| **51–55** | 8.33% | 91.67% |

**Insight:** Attrition is highest among employees aged 21–25 (12.93%) and 36–40 (11.50%), while 41–55 age groups have the lowest attrition (<9%). Retention efforts should focus on younger employees.

---

### 3️⃣ Department-wise Attrition

| Department | Resigned (%) | Stayed (%) |
|-----------|--------------|-----------|
| **Finance** | 13.33% | 86.67% |
| **HR** | 11.58% | 88.42% |
| **IT** | 13.95% | 86.05% |
| **Marketing** | 9.71% | 90.29% |
| **Operations** | 11.05% | 88.95% |
| **R&D** | 8.02% | 91.98% |
| **Sales** | 10.75% | 89.25% |

**Insight:** IT department has the highest attrition (13.95%), while R&D has the lowest attrition (8.02%). HR and Operations show moderate attrition (~11%). Tailored retention strategies are needed for IT and HR departments.

---

### 4️⃣ Job Role-wise Attrition

| Department | Highest Attrition Role | % | Lowest Attrition Role | % |
|-----------|------------------------|----|-----------------------|-----|
| **Finance** | Accountant | 13.33% | Analyst | 8.33% |
| **HR** | Talent Acquisition | 20.00% | HR Executive | 5.77% |
| **IT** | IT Manager | 17.00% | Software Engineer | 9.68% |
| **Marketing** | Marketing Executive | 12.90% | Marketing Manager | 6.19% |
| **Operations** | Operations Manager | ~11% | Operations Executive | ~10% |
| **R&D** | Data Scientist | 10.17% | Research Associate | 7.04% |
| **Sales** | Sales Manager | 14.02% | Account Manager | 8.98% |

**Insight:** Roles like Talent Acquisition, IT Manager show higher attrition risk. HR should prioritize engagement programs for these job functions.

---

### 5️⃣ Job Satisfaction vs Attrition

| Satisfaction Score | Resigned (%) | Stayed (%) |
|-------------------|--------------|-----------|
| **1** | 18.41% | 81.59% |
| **2** | 12.89% | 87.11% |
| **3** | 10.40% | 89.60% |
| **4** | 4.62% | 95.38% |
| **5** | 5.41% | 94.59% |

**Insight:** Employees with low job satisfaction (1–2) have the highest attrition, while those with high satisfaction (4–5) have very low attrition. Improving job satisfaction can significantly reduce turnover.

---

### 6️⃣ Work-Life Balance vs Attrition

| Score | Resigned (%) | Stayed (%) |
|-------|--------------|-----------|
| **1** | 12.35% | 87.65% |
| **2** | 11.16% | 88.84% |
| **3** | 10.96% | 89.04% |
| **4** | 10.37% | 89.63% |

**Insight:** Employees with lower work-life balance scores (1–2) experience higher attrition. Work-life balance improvement initiatives can further reduce resignations.

---

### 7️⃣ Income Band vs Attrition

| Income Band | Resigned (%) | Stayed (%) |
|------------|--------------|-----------|
| **0–20k** | 100.00% | 0.00% |
| **20–40k** | 11.29% | 88.71% |
| **40–60k** | 11.40% | 88.60% |
| **80k+** | 10.79% | 89.21% |

**Insight:** Although 0–20k has only 1 record (statistically insignificant), attrition decreases slightly as income increases. Competitive pay helps in retaining employees.

---

### 8️⃣ Job Level vs Attrition

| Job Level | Resigned (%) | Stayed (%) |
|-----------|--------------|-----------|
| **1** | 10.65% | 89.35% |
| **2** | 12.36% | 87.64% |
| **3** | 10.44% | 89.56% |
| **4** | 11.97% | 88.03% |
| **5** | 9.50% | 90.50% |

**Insight:** Attrition is highest at junior levels (Level 2) and lowest among senior employees (Level 5). Retention strategies should focus on early-career employees.

---

## ⚙️ Installation & Prerequisites

### System Requirements

- **Microsoft Excel** (2016 or later recommended)
- **Windows 10** or later / **macOS** with Excel installed
- **2GB RAM** minimum (4GB+ recommended)
- **100MB** free disk space

### Installation Steps

```
1. Download the Excel File
   → HR-Analytics-Dashboard-[Excel].xlsx

2. Open Microsoft Excel

3. File → Open → Select HR-Analytics-Dashboard-[Excel].xlsx

4. Wait for file to load completely

5. Navigate to Dashboard sheet to view visuals
```

---

## 📊 How to Use

### Accessing the Dashboard

**Step 1: Open the File**
```
Microsoft Excel → File → Open → HR-Analytics-Dashboard-[Excel].xlsx
```

**Step 2: Navigate to Dashboard Sheet**
- Select the Dashboard tab/sheet from the sheet tabs at the bottom
- All visualizations and metrics are displayed on this sheet

**Step 3: Use Interactive Elements**

| Feature | Action |
|---------|--------|
| **Overall Attrition KPI** | View overall attrition rate and stayed percentage |
| **Age Group Chart** | Analyze attrition trends across age demographics |
| **Department Chart** | Compare departmental attrition rates |
| **Job Role Analysis** | Explore role-specific resignation patterns |
| **Satisfaction Chart** | Assess satisfaction score impact on attrition |
| **Work-Life Balance Chart** | Review balance rating correlation with retention |
| **Income Band Analysis** | Examine salary range and attrition relationship |
| **Job Level Chart** | Track attrition across organizational hierarchy |
| **Slicers** | Filter by department, age group, or other dimensions |

### Interpreting the Data

- **Overall Attrition Rate** → High-level retention status overview
- **Age Group Chart** → Age segments most at risk of resignation
- **Department Chart** → Departmental performance comparison
- **Job Role Table** → Role-specific retention challenges
- **Satisfaction Chart** → Strong correlation between satisfaction and turnover
- **Work-Life Balance Chart** → Impact of balance on employee retention
- **Income Band Chart** → Salary range impact on attrition
- **Job Level Chart** → Hierarchical level patterns in resignation
- **Slicers** → Drill down into specific segments for detailed analysis

---

## 💡 Strategic Insights

### High-Risk Segments

✅ **Age 21–25:** Highest attrition (12.93%) — focus on early-career employee development

✅ **IT Department:** Highest departmental attrition (13.95%) — requires specific retention initiatives

✅ **Talent Acquisition Role:** Highest role-level attrition (20.00%) — critical engagement needed

✅ **Low Satisfaction (1–2):** Attrition reaches 18.41% — job satisfaction improvements essential

### Retention Focus Areas

✅ **Improve satisfaction & work-life balance** — Direct correlation with reduced attrition

✅ **Strengthen early-career employee support** — Junior levels (Level 2) show higher attrition

✅ **Review compensation for low-income groups** — Competitive pay supports retention

✅ **Department-specific interventions in IT and HR** — Tailored strategies for high-attrition departments

### Priority Actions

✅ **Satisfaction Enhancement:** Employees with scores 4–5 show <6% attrition vs 18% for score 1

✅ **Work-Life Balance:** Even modest improvements (score 1→4) reduce attrition by ~2%

✅ **Role-Based Engagement:** Target Talent Acquisition, IT Manager, and similar high-risk roles

✅ **Senior Level Retention:** Lower attrition at Level 5 (9.50%) suggests effective senior-level retention

---

## 🧰 Tech Stack

| Component | Technology |
|-----------|------------|
| **Platform** | Microsoft Excel |
| **Analysis Tool** | Pivot Tables & Pivot Charts |
| **Data Visualization** | Excel Charts (Bar, Pie) |
| **Filtering & Interactivity** | Slicers & Conditional Formatting |
| **Metrics** | Attrition %, Satisfaction Correlation, Level Analysis |
| **Data Source** | Employee HR dataset |

---

## 📁 Project Files

**File:** `HR-Analytics-Dashboard-[Excel].xlsx`
- Excel workbook with employee data and interactive dashboard
- Contains employee records, pivot tables, attrition analysis, and comprehensive visualization
- Ready for immediate use and HR strategy planning

---

## 💼 Skills Demonstrated

✅ **Data Organization & Structure** in Excel  
✅ **Pivot Table Creation** for multi-dimensional HR analysis  
✅ **Pivot Chart Design** for attrition trend visualization  
✅ **Conditional Formatting** for performance highlighting  
✅ **Slicers Implementation** for interactive filtering  
✅ **Dashboard Design & Layout** for HR insights presentation  
✅ **Employee Analytics** and attrition pattern interpretation  
✅ **Retention Strategy** analysis and recommendations  
✅ **Data Visualization** for HR metrics  
✅ **Workforce Planning** support through data insights  

---

## 📝 Notes

- Dataset contains comprehensive employee-level information with demographics and performance metrics
- All attrition calculations based on employee counts and resignation status
- Pivot tables enable flexible analysis by department, role, age group, and satisfaction level
- Conditional formatting supports quick visual identification of high-risk segments
- Slicers enable dynamic filtering across multiple HR dimensions
- Analysis directly supports workforce retention planning and HR strategy development
- Insights highlight satisfaction and work-life balance as key retention drivers

---

*This Excel-based HR Analytics Dashboard demonstrates practical workforce analytics expertise, combining employee data aggregation through pivot tables, multi-dimensional attrition analysis, and interactive visualization to enable data-driven decision-making through comprehensive monitoring of employee retention patterns, high-risk segments, satisfaction drivers, and strategic retention opportunities across departments, roles, age groups, and job levels.*

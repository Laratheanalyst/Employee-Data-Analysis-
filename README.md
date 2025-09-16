
<h1 align="center">📊 Employee Data Analysis</h1>
<p align="center">
  <b>A detailed analysis of workforce distribution, departmental performance, and strategic HR insights.</b>
</p>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" alt="Status Badge">
  <img src="https://img.shields.io/badge/Employees-3000-blue?style=flat-square" alt="Employees Badge">
  <img src="https://img.shields.io/badge/Departments-6-orange?style=flat-square" alt="Departments Badge">
</p>

---

## 📑 Table of Contents
- [Introduction](#-introduction)
- [Objectives](#-objectives)
- [Scope](#-scope)
- [Dataset Overview](#-dataset-overview)
- [Data Cleaning Process](#-data-cleaning-process)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Key Insights](#-key-insights)
- [Strategic Recommendations](#-strategic-recommendations)
- [Conclusion](#-conclusion)

---

## 🧾 Introduction
The employee dataset is a comprehensive collection of information related to the workforce within an organization, focusing on departments.  
It provides valuable insights into attributes such as employee IDs, names, job titles, departments, race description, performance scores, gender codes, date of birth, division, and business unit.  
These attributes characterize each employee, enabling effective HR management and strategic decision-making.

---

## 🎯 Objectives
1. Analyze performance metrics to assess departmental effectiveness.
2. Optimize staffing levels and budget allocation to minimize costs.
3. Identify high-performing departments and develop training for weaker ones.
4. Detect skill gaps to tailor training programs and support career growth.
5. Evaluate interdepartmental collaboration to improve teamwork.
6. Provide insights for restructuring, expansion, and resource reallocation.

---

## 🗂 Scope
This report examines:
- *Department Performance*: Efficiency evaluation by department.
- *Employee Turnover Rates*: Retention analysis.
- *Workforce Planning*: Identifying staffing needs.
- *Performance Reviews*: Tracking departmental performance.
- *Budgeting*: Allocating resources based on departmental needs.

---

## 📊 Dataset Overview
- *Data Source*: Collected from a reliable internal channel.  
- *Dataset Size*: 3,000 employee records.

### 🔑 Key Columns
| Column | Description |
|--------|-------------|
| Employee ID | Unique identifier for each employee |
| First Name | Employee’s first name |
| Last Name | Employee’s last name |
| Department Type | Department where employee works (Admin, IT/IS, Sales, etc.) |
| Position/Title | Job title |
| Email | Work email address |
| Date of Birth | Employee’s birth date |
| Division | Employee’s division |
| State | Employee’s state |
| Job Function | Brief job description |
| Performance Score | Evaluation score from reviews |
| Race Desc | Employee race (White, Hispanic, Black, Asian) |

---

## 🧹 Data Cleaning Process
1. *Removed Duplicates* using Power Query to ensure unique records.
2. *Handled Missing Values* by checking for nulls and filling where appropriate.
3. *Standardized Formats* for dates (TEXT()) and text case (UPPER()/LOWER()).
4. *Corrected Data Entry Errors* using SUBSTITUTE() for common typos.
5. *Filtered Unnecessary Data* to focus only on relevant fields.

---

## 🔍 Exploratory Data Analysis

### 👥 Employees Overview
- *Total Employees*: 3,000  
- *Gender Breakdown*: 1,682 females (56%), 1,318 males (44%)


### 🏢 Department Overview
| Department | Employees | Divisions | Female | Male |
|-----------|-----------|-----------|--------|------|
| Admin Offices | 80 | 19 | 44 | 36 |
| Executive Office | 24 | 12 | 1 | 23 |
| IT/IS | 430 | 23 | 211 | 219 |
| Production | 2,020 | 25 | 1,262 | 758 |
| Sales | 331 | 23 | 115 | 216 |
| Software Engineering | 115 | 19 | 49 | 66 |

### 🧑‍💼 Employee Status
- *Production*: 1,588 Active, 287 Voluntarily Terminated, 69 Leave of Absence
- *Executive Office*: 24 Active (0 turnover)
- *IT/IS*: 375 Active, 31 Terminated for Cause

### 💰 Pay Zone Distribution
- *Admin Offices*: 42.5% (Zone A) – highest proportion  
- *Software Engineering*: 36.5% (Zone C) – highest proportion  

### 💍 Marital Status
Production department has the highest number of married employees (534), while Executive Office has the fewest.

### 🌍 Race Distribution
Production has the largest number of Asian (430), White (413), and Black (400) employees.  
Executive Office has the smallest racial diversity.

### 📈 Performance Score
- *Production Department*: 1,521 Fully Meets, 295 Exceeds, 141 Needs Improvement
- *Executive Office*: Lower performance with 5 on PIP (Performance Improvement Plan)
- *Software Engineering*: 100% Fully Meets Expectations

---

## 📌 Key Insights
- *Production Department* dominates workforce size but has highest turnover.
- *Executive Office* is the smallest department but shows potential resourcing challenges.
- *Admin Offices* have the highest share in Pay Zone A, suggesting higher-paid roles.
- *Software Engineering* shows perfect performance score but lowest Pay Zone A representation.
- *Gender Distribution* is slightly female-dominated (56%), requiring monitoring for balance.
- *High PIP and turnover rates* indicate potential engagement and workload issues in Production.

---

## 🧠 Strategic Recommendations
- *Monitor Gender Balance*: Implement inclusion strategies where imbalance is high.
- *Optimize Department Effectiveness*: Review Production department scalability and workload.
- *Investigate Turnover Causes*: Conduct exit interviews and engagement surveys in Production.
- *Review Pay Equity*: Ensure fair pay structures across departments.
- *Tailor Benefits*: Align benefits with employee life stages (flexible schedules, family support).
- *Address Underperformance*: Root cause analysis of PIP cases in Production and Executive Office.

---

## 🏁 Conclusion
The analysis reveals disparities across departments in size, gender, pay zones, and performance.  
Key concerns include *high turnover* and *underperformance* in Production, and potential *resourcing issues* in the Executive Office.  
Addressing these issues through *equity, engagement, and tailored support programs* will improve retention, performance, and organizational balance.

---

## DASHBOARD
<img width="1185" height="656" alt="Screenshot 2025-09-16 050252" src="https://github.com/user-attachments/assets/6257b06e-2a0e-4183-8710-8cc0cbf8ff75" />




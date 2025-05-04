# HR leaver Analysis Dashboard

## 📋 Overview
This project explores patterns in employee leaver to help HR teams understand turnover drivers and design retention strategies. Built using Power BI and a simulated HR dataset.

## 🎯 Objectives
- Identify factors correlated with employee leaver (e.g., overtime, satisfaction, tenure)
- Visualize trends across departments, age groups, and job roles
- Provide actionable insights and HR recommendations

## ❓ Business Questions
- What factors contribute most to early employee leaver (within 1–2 years of joining)?
- Does promotion or salary increase reduce leaver—or are current reward strategies ineffective?
- Which groups of employees are most at risk of leaving, and how can HR better support them?

## 🛠️ Tools & Technologies
- Power Query (for data cleaning and preparation)
- Power BI (for interactive dashboards)

## 📊 Dataset
- Source: [IBM HR Analytics Employee leaver & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Size: 1,470 employee records
- Key Variables: Age, Department, MonthlyIncome, JobSatisfaction, Overtime, Attrition
⚠ Note: This dashboard assumes all data reflects employee records as of 2024. Tenure and attrition metrics are based on a snapshot without a time-series dimension. We assume that all of them left voluntarily, i.e. resignation.

## 🚀 Project Workflow
1. Data Cleaning (Power Query)
2. Exploratory Data Analysis (EDA)
3. Dashboard Development (Power BI)
4. Insights & Recommendations

## 🔍 Key Observations from Exploratory Data Analysis (EDA)

- **Level 1 employees are most likely to leave**: Entry-level staff show significantly higher leaver rates, highlighting a retention risk among early-career employees.

- **Leavers score slightly lower in satisfaction and support**: Job Satisfaction, Work-Life Balance, Relationship with Manager, and Salary Hike are all modestly lower among leavers compared to those who stayed.

- **The differences are not drastic**: These gaps (0.09–0.35 on a 4-point scale) suggest they may contribute to resignation but are unlikely to be the sole cause.

- **Hidden drivers may be influencing early resignation**: The high volume of exits from Year 1 employees — especially younger, less experienced staff — indicates possible issues like expectation mismatch, onboarding experience, or generation-related needs.

## 🔍 Dashboard Insights & Strategic Takeaways

### 📌 Page 1: Overview
- Research & Development has the highest leaver rate across departments.
- Job Level 1 employees show the highest leaver rate, indicating a risk among early-career staff.
- The overall leaver rate is concentrated within the first few years of employment.

### 📌 Page 2: Exit Trends (All Tenures)
- Majority of leavers fall within the 1–3 year tenure group.
- Leavers have slightly lower average scores in:
  - Job Satisfaction
  - Work-Life Balance
  - Relationship with Manager
- Median monthly income and salary hikes are slightly lower among leavers, but not drastically different.
- Leaver appears to be influenced by a combination of factors rather than compensation alone.

### 📌 Page 3: Year 1 Leaver Deep Dive
- High concentration of exits from R&D, Level 1, and younger employees with low total working years.
- Many Year 1 leavers likely exited before being eligible for promotion or meaningful salary growth.
- This suggests potential gaps in onboarding, early support, and expectation on career growth.

### ✅ Recommendations
- Conduct focus groups with early-tenure employees to better understand unmet expectations and early disengagement.
- Establish a structured exit interview process (if not already in place) to collect actionable, qualitative data on why employees choose to leave.
- Review and enhance the onboarding program, focusing on the first-year experience; regularly collect feedback from new hires to identify improvement areas.
- Strengthen early-career development support and clearly communicate progression paths to improve engagement and demonstrate long-term growth opportunities within the company.

## 📁 Folder Structure
├── 📊 PowerBI_Dashboard/       
│   └── HR_Attrition_Dashboard.pbix      # Final Power BI file
│
├── 📄 Documentation/
│   ├── README.md                        # Project overview and key insights
│   └── Assumptions_and_Notes.md        # Assumptions, limitations, decisions
│
├── 📁 Data/
│   ├── raw/                             # Original dataset
│   │   └── IBM_HR_Attrition.csv
│   └── cleaned/                         # Cleaned/transformed version (if any)
│       └── HR_Attrition_Cleaned.xlsx
│
├── 📸 Screenshots/
│   └── Dashboard_Overview.png           # Dashboard images for README
│
└── 📚 References/
    └── Source_Link.txt                  # Kaggle dataset / articles etc.

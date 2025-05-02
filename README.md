# HR Attrition Analysis Dashboard

## 📋 Overview
This project explores patterns in employee attrition to help HR teams understand turnover drivers and design retention strategies. Built using Power BI and a simulated HR dataset.

## 🎯 Objectives
- Identify factors correlated with employee attrition (e.g., overtime, satisfaction, tenure)
- Visualize trends across departments, age groups, and job roles
- Provide actionable insights and HR recommendations

## ❓ Business Questions
- What factors contribute most to early employee attrition (within 1–2 years of joining)?
- Does promotion or salary increase reduce attrition—or are current reward strategies ineffective?
- Which groups of employees are most at risk of leaving, and how can HR better support them?

## 🛠️ Tools & Technologies
- SQL (for data querying)
- Power Query (for data cleaning and preparation)
- Power BI (for interactive dashboards)

## 📊 Dataset
- Source: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Size: 1,470 employee records
- Key Variables: Age, Department, MonthlyIncome, JobSatisfaction, Overtime, Attrition

## 🚀 Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Dashboard Development (Power BI)
4. Insights & Recommendations

## 🔍 Key Observations from Exploratory Data Analysis (EDA)

- **High Early Attrition**: A significant proportion of employees who leave do so within their first year at the company. This suggests potential gaps in onboarding experience or expectation management.

- **High Job Satisfaction but Still Attriting**: Surprisingly, some employees with high Job Satisfaction scores still choose to leave, implying that factors beyond immediate job satisfaction (such as career advancement or external opportunities) play a role.

- **Low Salary Increase Linked to Higher Attrition**: Employees who received a salary increase of less than 15% exhibit a significantly higher attrition rate. Competitive salary growth appears important for retention.

- **Employees Who Just Got Promoted Still Leave**: Contrary to expectations, employees with 0 years since their last promotion — meaning they were recently promoted — have a high attrition rate. This suggests that a promotion alone may not be enough to retain employees, or that it could trigger new pressures or unmet expectations leading to resignation, especially for employees at level 1.

- **Entry-Level Employees Without Promotions Have the Highest Attrition**: Specifically, Job Level 1 employees with no promotions demonstrate the highest attrition rates, highlighting the importance of clear career progression paths for early-career talent.

- **Salary Increases Appear Unrelated to Promotions**: Assuming performance reviews are held annually, employees who were recently promoted received similar salary hike percentages to those who were not promoted. This suggests that promotions may not be effectively rewarded with meaningful compensation increases, potentially reducing their impact as retention tools.

- **Mid-Early Tenure Employees Are Most Likely to Leave**: Employees with less than 10 years of service represent the majority of attrition cases. While attrition peaks at the 1-year mark (indicating onboarding and early mismatch issues), sustained risk continues throughout the first decade, suggesting retention challenges beyond just the new hire phase.

- **Employees with Only One Prior Employer Are More Likely to Leave**: The analysis shows that individuals who have only worked at one company ("NumCompaniesWorked = 1") have the highest attrition rate. This suggests that first-job employees may be more likely to switch roles early in their careers, potentially due to unmet expectations, job fit, or a desire to explore new opportunities.

- **Salary Increases Are Unrelated to Overtime**: Employees who work overtime receive similar salary hike percentages as those who do not. This may lead to perceived unfairness and reduced motivation among high-effort employees, especially if extra work is not recognized through compensation.

- **One-Year Employees Show the Highest Attrition — Regardless of Promotion Status**: Employees with one year of tenure demonstrate the highest attrition rate across the dataset. Interestingly, this applies both to those who were promoted and those who were not. This pattern suggests that some employees may enter the company expecting career progression within their first year, and leave due to unmet expectations or dissatisfaction even after being promoted.


## 📈 Key Dashboards
_(Screenshots and Power BI link to be added)_

- Attrition Overview
- Attrition by Department and Age Group
- Overtime and Satisfaction Risk Analysis

## ✅ Recommendations
_(Will summarize after final analysis)_

## 📁 Folder Structure

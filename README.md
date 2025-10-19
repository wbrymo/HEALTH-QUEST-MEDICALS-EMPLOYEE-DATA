# 💊 Health Quest Medicals – Employee Data Analytics

Analyzing workforce demographics, satisfaction, and compensation trends to uncover actionable insights for HR and management using data analytics and visualization.

# Project Overview

This project focuses on conducting a comprehensive workforce analytics study for Health Quest Medicals, a leading pharmaceutical company committed to advancing healthcare innovation.
The HR department required a deeper understanding of employee demographics, attrition trends, job satisfaction, income patterns, and promotion cycles to make data-driven decisions for retention and engagement.

As the data analyst, I examined 1,470 employee records using Python-based analytics and visualization techniques.
The goal was to translate raw HR data into insights that reveal workforce behavior, compensation fairness, and organizational strengths.

# Objectives

Analyze key workforce variables such as age, education, experience, and monthly income.

Identify attrition rate, satisfaction levels, and factors influencing employee turnover.

Assess gender-based pay equity and departmental income distribution.

Visualize correlations between years of service, promotions, and job satisfaction.

Recommend strategic HR actions for workforce optimization.

# Tools, Libraries & Tech Stack

Programming Language: Python

Libraries:

Pandas, NumPy – data cleaning and transformation

Matplotlib, Seaborn – visualization and storytelling

Jupyter Notebook – analysis environment

Excel – initial data exploration and validation

Techniques:
Exploratory Data Analysis (EDA), Statistical Analysis, Data Visualization, Workforce Insights

# Workflow / Steps to Execute
1️⃣ Data Collection

The dataset was provided by the HR department, containing demographic and employment information such as:
Age, Gender, Department, JobRole, MonthlyIncome, YearsAtCompany, JobSatisfaction, WorkLifeBalance, Attrition, and Promotion History.

2️⃣ Data Cleaning

Handled missing values and inconsistent labels.

Converted categorical variables into descriptive labels for readability.

Verified numerical distributions and outliers for income and experience fields.

3️⃣ Exploratory Data Analysis (EDA)

Conducted multiple statistical and visual analyses to answer HR-driven questions:

What is the average age and education level distribution across departments?

Which job roles have the lowest income range?

What is the overall attrition rate in the company?

How satisfied are employees with their work environment?

Is there gender discrimination in pay?

How frequently are employees promoted over time?

4️⃣ Data Visualization

Plotted bar charts, pie charts, and box plots for key metrics.

Used correlation heatmaps to explore relationships among numeric features.

Illustrated income comparisons across job roles and education levels.

5️⃣ Deriving Insights

Calculated descriptive statistics such as mean, median, and standard deviation for income and age.

Identified attrition trends, satisfaction clusters, and promotion patterns.

Developed summary dashboards for HR management presentation.

# Results & Key Insights
Metric	Insight
Average Age	--------------------------37 years overall, with Human Resources slightly higher at 38.

Education	----------------------------Bachelor’s degree holders were the most represented group (572 employees).

Environment Satisfaction -------------61% of employees reported high or very high satisfaction levels.

Attrition Rate------------------------Only 16% of employees left — indicating a low turnover rate.

Gender Pay Gap------------------------No significant pay gap observed between male and female employees.

Lowest Income Role--------------------Sales Representatives earned the lowest average salary (≈ ₦2,626).

Top-earning Roles---------------------Managers and Research Directors had the highest average income (> ₦16,000).

Promotion Trends----------------------Promotions decreased sharply after 5 years in service, indicating slow career progression.

Job Satisfaction----------------------Research & Development employees showed the highest satisfaction (65%), while HR had the lowest (4%).
# Business Recommendations

Retention Strategy:
Focus retention initiatives on Sales and Human Resources departments where satisfaction and income are lowest.

Compensation Review:
Re-evaluate the pay structure for Sales Representatives to promote fairness and motivation.

Promotion Policy:
Create clearer, time-based promotion frameworks to prevent stagnation beyond the 5-year mark.

Employee Engagement:
Maintain the strong satisfaction culture in Research & Development through recognition programs and flexible scheduling.

Diversity Monitoring:
Continue monitoring gender pay parity to maintain equality and organizational credibility.

# Business Impact

Provided HR leadership with quantitative insight into workforce well-being and compensation equity.

Supported the development of a data-driven HR strategy for recruitment and retention.

Enabled visual dashboards for tracking key workforce metrics.

Improved understanding of attrition dynamics, leading to proactive interventions.

# How to Run Locally
# Clone this repository
git clone https://github.com/<your-username>/Health-Quest-Medicals-Employee-Data.git
cd Health-Quest-Medicals-Employee-Data

# Install dependencies
pip install -r requirements.txt

# Open Jupyter Notebook
jupyter notebook


Then open the main notebook file:

HealthQuest_Employee_Analytics.ipynb

📁 Folder Structure
Health-Quest-Medicals-Employee-Data/
│
├── data/
│   └── health_quest_employee.csv
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── Visualization.ipynb
│
├── visuals/
│   ├── attrition_rate.png
│   ├── income_distribution.png
│
├── README.md
└── requirements.txt


# Outcome Summary

This project successfully transformed raw HR data into actionable insights that enhanced organizational understanding of employee satisfaction and compensation.
With a low attrition rate and clear departmental trends, the analysis positioned Health Quest Medicals to make informed, data-driven HR decisions.

The project demonstrates proficiency in data cleaning, visualization, statistical reasoning, and business insight generation — essential skills for data analyst and data scientist roles

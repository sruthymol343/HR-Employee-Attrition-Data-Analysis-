Employee Attrition Analysis

 Problem Statement

A company is experiencing high employee turnover and wants to understand the factors contributing to employee attrition. High turnover can lead to increased recruitment costs, loss of experienced talent, reduced productivity, and lower employee morale.
The objective of this project is to analyze employee data and identify the key reasons employees leave the organization, enabling HR teams to make informed decisions and improve employee retention.

 Project Objectives

•	Analyze employee attrition trends. 
•	Identify factors influencing employee turnover. 
•	Examine the relationship between attrition and employee characteristics. 
•	Generate actionable insights for HR decision-making. 
•	Recommend strategies to reduce attrition rates. 

Dataset

Dataset: IBM HR Analytics Employee Attrition Dataset
The dataset contains employee information such as:
•	Age 
•	Gender 
•	Department 
•	Job Role 
•	Monthly Income 
•	Marital Status 
•	Education 
•	Overtime 
•	Job Satisfaction 
•	Environment Satisfaction 
•	Work-Life Balance 
•	Years at Company 
•	Years Since Last Promotion 
•	Attrition Status (Yes/No) 
Target Variable:
•	Attrition 

 Technologies Used

•	Python 
•	Jupyter Notebook 
•	Pandas 
•	NumPy 
•	Matplotlib 
•	Seaborn 

Project Workflow

1. Data Collection

The employee attrition dataset was imported into Python for analysis.
import pandas as pd

df = pd.read_csv('WA_Fn-UseC_-HR-Employee-Attrition.csv')
 
2. Data Cleaning

Performed the following preprocessing steps:
•	Checked for missing values 
•	Removed duplicates 
•	Verified data types 
•	Prepared data for analysis 

3. Exploratory Data Analysis (EDA)

Analyzed:
•	Overall attrition rate 
•	Department-wise attrition 
•	Job role-wise attrition 
•	Overtime impact 
•	Salary distribution 
•	Job satisfaction levels 
•	Work-life balance 
•	Promotion history 

4. Data Visualization

Created visualizations such as:
•	Count Plots 
•	Bar Charts 
•	Pie Charts 
•	Histograms 
•	Box Plots 
•	Correlation Heatmaps 

 
Key Findings

1. Overtime is a Major Factor

Employees who work overtime show significantly higher attrition rates.
Impact:
•	Increased stress 
•	Burnout 
•	Reduced work-life balance 
2. Low Job Satisfaction Increases Attrition

Employees with lower satisfaction scores are more likely to leave.
Impact:
•	Reduced engagement 
•	Lower motivation 
•	Poor workplace experience 

3. Lower Income Leads to Higher Turnover

Employees earning lower salaries tend to leave more frequently.
Impact:
•	Better opportunities elsewhere 
•	Compensation dissatisfaction 

4. Limited Career Growth Affects Retention

Employees who have not received promotions for several years are more likely to leave.
Impact:
•	Career stagnation 
•	Lack of advancement opportunities 


5. Poor Work-Life Balance Contributes to Attrition

Employees struggling to maintain work-life balance show higher turnover rates.

6. Certain Roles Experience Higher Attrition

Some job roles and departments have noticeably higher attrition rates than others.

Business Insights

The analysis suggests that employee turnover is primarily driven by:

•	Excessive overtime 
•	Low job satisfaction 
•	Inadequate compensation 
•	Poor work-life balance 
•	Lack of career advancement opportunities 
•	Role-specific challenges 

Recommendations

To reduce employee attrition, the company should:
Improve Work-Life Balance
•	Reduce excessive overtime 
•	Introduce flexible working arrangements 
Increase Employee Satisfaction
•	Conduct regular feedback surveys 
•	Recognize employee achievements 
Review Compensation Policies
•	Benchmark salaries against industry standards 
•	Offer competitive benefits packages 
Strengthen Career Development
•	Create clear promotion pathways 
•	Provide training and upskilling opportunities 
Monitor High-Risk Departments
•	Conduct department-specific retention analysis 
•	Address role-specific concerns 
 
Expected Business Impact

By implementing these recommendations, the company can:
•	Reduce employee turnover 
•	Improve employee engagement 
•	Lower recruitment and training costs 
•	Increase workforce productivity 
•	Enhance organizational performance 

 Project Structure

Employee-Attrition-Analysis/
│
├── pythonpj.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
└── requirements.txt

How to Run

1.	Clone the repository 
git clone https://github.com/your-username/Employee-Attrition-Analysis.git
2.	Install dependencies 
pip install pandas numpy matplotlib seaborn
3.	Open Jupyter Notebook 
jupyter notebook
4.	Run pythonpj.ipynb 

Author

Sruthy Mol R

This project demonstrates how data analytics can be used to identify the root causes of employee attrition and support data-driven HR strategies for improving employee retention.

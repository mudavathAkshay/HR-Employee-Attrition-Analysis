💼 HR Employee Attrition Analysis
📊 Overview

This project explores the factors that lead to employee attrition (resignation or turnover) using the IBM HR Analytics Employee Attrition Dataset.
The goal is to identify key drivers behind attrition, visualize important patterns, and predict attrition using a machine learning model.

🎯 Objectives

Understand Current Turnover Trends
Analyze overall attrition rates and demographic breakdowns by age, gender, department, and job role.

Identify Key Influencing Factors
Explore job satisfaction, work-life balance, distance from home, and income levels.

Predict Attrition
Use a Random Forest Classifier to predict whether an employee is likely to leave.

📦 Dataset

Source: IBM HR Analytics (fictional dataset)

File Name: WA_Fn-UseC_-HR-Employee-Attrition.csv

Attributes include:

Demographics (Age, Gender, Education)

Job details (JobRole, Department, YearsAtCompany)

Satisfaction metrics (JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance)

Salary and performance factors

🧰 Tools & Technologies Used
Category	Tools / Libraries
Language	Python
Data Handling	pandas, numpy
Visualization	matplotlib, seaborn
Machine Learning	scikit-learn
IDE	Jupyter Notebook
⚙️ Project Workflow
1️⃣ Data Loading and Exploration

Import CSV using pandas

Check dataset structure, missing values, and data types

2️⃣ Data Cleaning

Encoded categorical columns

Converted “Attrition” to numeric (1 = Yes, 0 = No)

3️⃣ Exploratory Data Analysis (EDA)

Visualized insights using Seaborn & Matplotlib:

Attrition by Gender, Job Role, Department

Distance from Home vs Attrition

Monthly Income by Education

Correlation Heatmap

4️⃣ Predictive Modeling

Trained a Random Forest Classifier

Evaluated using accuracy score, confusion matrix, and classification report

5️⃣ Key Insights

High attrition seen in Sales & Laboratory roles

Employees with low job satisfaction & poor work-life balance tend to leave

Lower monthly income correlates with higher attrition

Distance from home also plays a role

📈 Results Snapshot
Metric	Result
Accuracy	~88%
Best Predictors	MonthlyIncome, JobSatisfaction, Age, WorkLifeBalance
🚀 How to Run This Project

1️⃣ Clone this repository

git clone https://github.com/<your-username>/HR-Employee-Attrition-Analysis.git


2️⃣ Navigate to project folder

cd HR-Employee-Attrition-Analysis


3️⃣ Install dependencies

pip install -r requirements.txt


4️⃣ Open Jupyter Notebook

jupyter notebook


5️⃣ Run
Open HR_Attrition_Analysis.ipynb and run all cells.

📷 Sample Visualizations

(Add screenshots from your notebook EDA)

images/
 ├── attrition_distribution.png
 ├── jobrole_vs_attrition.png
 ├── heatmap_correlation.png

🧑‍💻 Author

Your Name: Akshay Mudavath
Role: Data Analyst Intern
Email: mudavathakki4@gmail.com


📜 License

This project is open source under the MIT License — feel free to use and modify.


Use badges 

![Screenshot_21-10-2025_193851_localhost](https://github.com/user-attachments/assets/4e9df4ae-ec7d-4e7a-8789-e09657f05c29)
![Screenshot_21-10-2025_193921_localhost](https://github.com/user-attachments/assets/8831bbe0-3394-40f4-94c4-c0917bb9c3e7)
![Screenshot_21-10-2025_193957_localhost](https://github.com/user-attachments/assets/421bd479-7114-42ff-827a-f4b00a0614e8)
![Screenshot_21-10-2025_194035_localhost](https://github.com/user-attachments/assets/80687568-eb08-43f4-92d4-8795c2fcfcf6)



Would you like me to generate a ready-to-upload ZIP with all files (README, requirements.txt, notebook template, and folder structure)?
I can prepare that so you just extract and push to GitHub directly.

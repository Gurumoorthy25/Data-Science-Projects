# 📊 Exploratory Data Analysis on Job Market Dataset

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on a Job Market dataset to uncover insights about job roles, salaries, required skills, and hiring trends.  
The main goal is to understand patterns in the data and provide useful insights for job seekers and employers.

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset
- Source: Kaggle / Job market dataset  
- Contains information about job postings such as:
  - Job Title  
  - Company  
  - Location  
  - Skills Required  
  - Salary Range  

---

## 🔑 Key Steps
1. **Data Cleaning**
   - Handled missing values  
   - Removed duplicates  
   - Standardized column names  

2. **Exploratory Data Analysis**
   - Distribution of job titles and companies  
   - Salary range visualization  
   - Top skills required in the market  
   - Job availability across locations  

3. **Data Visualization**
   - Histograms, bar plots, pie charts, and boxplots  
   - Correlation analysis between job factors  

---

## 📊 Results & Insights
- Identified that 'Data Scientist' role has moe opportunities among the other roles  
- Found that 'Amazon.com' hire the most candidate, follow by 'Ball Aerospace', 'Microsoft' and 'Google'
- The top 5 cities that hire the most data science related job are 'Seattle', 'New York', 'Cambridge', 'Boston', and 'San Francisco'
- 'California' state has more job opportunities related to Data Science among other states  

---

## 🚀 How to Run
```bash
git clone <repo-link>
cd EDA_On_Job_Market
pip install -r requirements.txt
jupyter notebook EDA_On_Job_Market_Project.ipynb

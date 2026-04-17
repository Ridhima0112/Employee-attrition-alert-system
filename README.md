# 📊 Employee Attrition Analysis & Prediction System

## 🚀 Project Overview
This project helps organizations identify employees who are at risk of leaving the company using automation and data visualization.

It combines:
- Google Forms (data collection)
- Google Sheets (data storage)
- n8n (automation & risk calculation)
- Power BI (interactive dashboard)

---

## ❗ Problem Statement

TechNova Solutions is facing a high attrition rate of **35%**, especially among junior employees.

### Key Issues:
- Low job satisfaction
- Poor manager feedback
- Long working hours
- Lack of career growth
- No automated system to identify at-risk employees

---

## 🛠️ Tools & Technologies Used

- Google Forms  
- Google Sheets  
- n8n (Workflow Automation)  
- Power BI  

---

## 🔄 Workflow Architecture

Google Form → Google Sheets → n8n → Risk Classification → Power BI Dashboard

---

## 📋 Survey Questions Used

1. Job Satisfaction (1–5 scale)  
2. Manager Support & Feedback (1–5 scale)  
3. Working Hours (numeric)  
4. Career Growth Opportunities (Yes/No)  
5. Likelihood of Leaving (1–6 scale)  

---

## 🧠 Risk Classification Logic (n8n)

### 🔴 High Risk
- Satisfaction < 3  
- OR Leaving Likelihood ≥ 5  

### 🟠 Medium Risk
- Manager Rating < 3  
- OR Working Hours > 9  
- OR Career Growth = No  

### 🟢 Low Risk
- All other employees  

---

## ⚙️ n8n Workflow Steps

1. Google Sheets Trigger (Read Data)  
2. Function Node (Calculate Risk Level)  
3. IF Node (Check Risk Conditions)  
4. Google Sheets Node (Save Processed Data)  

---

## 📊 Power BI Dashboard Features

- 👥 Total Employees Count  
- 📉 Risk Level Distribution (Donut Chart)  
- 📊 Risk vs Working Hours (Bar Chart)  
- 📈 Manager Feedback vs Risk (Line Chart)  
- 🎛️ Filters:
  - Working Hours  
  - Career Growth  

---

## 📸 Dashboard Preview

<img width="1213" height="627" alt="Screenshot 2026-04-04 225156" src="https://github.com/user-attachments/assets/01150da1-5580-48ce-a490-9dd96d8e34d6" />


---

## 🔗 Data Source

Google Sheets connected to Power BI using CSV export link.

---

## 📈 Key Insights

- Employees working more than **9 hours/day** show higher attrition risk  
- Poor manager feedback strongly impacts employee retention  
- Lack of career growth is a major reason for leaving  
- High-risk employees can be identified early using automation  

---

## 🎯 Business Impact

This system helps HR teams to:
- Identify at-risk employees in advance  
- Reduce attrition rate  
- Improve employee satisfaction  
- Take data-driven decisions  

---

## 👩‍💻 Author

Ridhima  

---

## ⭐ Project Status

Completed ✔️

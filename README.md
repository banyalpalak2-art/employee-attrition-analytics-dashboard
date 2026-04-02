# 📊 Employee Attrition Analytics Dashboard

This project is an end-to-end employee attrition monitoring system that combines workflow automation with interactive data visualization. It helps identify high-risk employees, analyze job satisfaction trends, and support data-driven HR decisions.

---

## 🚀 Features

- 📈 **Attrition Dashboard**
  - Job satisfaction analysis
  - Risk score tracking
  - Leave intent insights
  - High-risk employee identification

- ⚙️ **Automated Workflow**
  - Google Sheets trigger for real-time data updates
  - Risk score calculation
  - Employee classification (High / Low risk)
  - Alert message formatting
  - Data preparation for storage

- 📊 **Data Insights**
  - Risk level distribution (pie chart)
  - Career growth vs risk correlation
  - Risk score vs job satisfaction comparison
  - Tabular employee-level breakdown

---

## 🛠️ Tech Stack

- **Data Source:** Google Sheets  
- **Automation:** Workflow automation tool (node-based pipeline)  
- **Visualization:** Power BI / Dashboarding tool  
- **Logic:** Custom risk scoring & classification rules  

---

## 🔄 Workflow Overview

1. **Google Sheets Trigger**
   - Detects new employee records  

2. **Calculate Risk Score**
   - Computes risk based on:
     - Job satisfaction  
     - Work hours  
     - Other factors  

3. **Route by Risk Level**
   - Classifies employees into:
   - ![WhatsApp Image 2026-04-02 at 10 00 17](https://github.com/user-attachments/assets/8c257570-4dc3-4f07-b073-6262fcb44ffd)

     - High Risk  
     - Low Risk
       




4. **Format Alert Message**
   - Generates alerts for high-risk employees  

5. **Prepare Data for Storage**
   - Structures processed data for reporting/dashboard  

---

## 📊 Dashboard Highlights

- **Total Responses:** Tracks number of employees analyzed  
- **Average Job Satisfaction:** Measures overall satisfaction level  
- **Leave Intent Score:** Predicts attrition likelihood  
- **Risk Score:** Aggregated employee risk indicator  
- **High-Risk Employees:** Count of employees needing attention
-  ![WhatsApp Image 2026-04-02 at 10 00 18](https://github.com/user-attachments/assets/d35217ac-b05f-4410-9d10-e104dc0324b7)


---

## 📌 Sample Insights

- Majority of employees fall under **Low Risk (71%)**  
- Higher job satisfaction correlates with **lower risk scores**  
- Lack of career growth increases attrition risk significantly  

---

## 📂 Project Structure

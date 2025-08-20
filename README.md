# 🏥 Hospital Analytics Dashboard (Excel)

*"Healthcare runs on data, but insight comes from analytics."*  

## 📌 Project Overview
This project presents an **interactive Hospital Dashboard** built in Excel using a **multi-table healthcare dataset**.  
The data includes patients, providers, encounters, diagnoses, medications, and labs, making it closer to **real-world hospital information systems**.  

The dashboard provides a **unified view of hospital operations, patient health trends, and provider performance**.

---

## ❓ Problem Statement
Hospitals collect massive amounts of data from patients, doctors, encounters, lab results, and prescriptions.  
The challenge is to bring these **disconnected data tables** together to:  
- Monitor hospital KPIs (patients, visits, doctors, cities).  
- Track patient inflow by visit type (Emergency, OPD, Inpatient, Telemedicine).  
- Identify the most common problems and diagnoses.  
- Analyze doctor performance and patient volume.  
- Combine lab, medication, and diagnosis data for deeper insights.  

---

## 💡 Solution
Using **Excel (Power Query + Pivot Tables)**, I integrated multiple CSV files into a single model and created an **interactive dashboard**.  
This allows decision-makers to quickly filter, explore, and visualize healthcare trends.

---

## 📂 Dataset Details
The dataset is divided into **7 interrelated tables**:

1. **Patients (`medical_patients.csv`)**  
   - Patient demographics (ID, gender, age, state, etc.)  

2. **Providers (`medical_providers.csv`)**  
   - Doctor/provider details (name, specialization, city)  

3. **Encounters/Visits (`medical_encounters.csv`)**  
   - Patient visits (visit ID, type, provider, date, city)  

4. **Diagnoses (`medical_diagnoses.csv`)**  
   - ICD-10 codes and diagnoses linked to encounters  

5. **Medications (`medical_medications.csv`)**  
   - Prescriptions and medications assigned to patients  

6. **Lab Orders (`medical_lab_orders.csv`)**  
   - Ordered lab tests linked to patients and visits  

7. **Lab Results (`medical_lab_results.csv`)**  
   - Results of lab tests (normal/abnormal values)  

---

## 📊 Dashboard Features
- **KPIs:** Total Patients, Visits, Doctors, Cities  
- **Patient vs. Doctor Diagnoses** (Pie Chart)  
- **Visits by Type** (Emergency, OPD, Inpatient, Telemedicine)  
- **Top 5 Doctors by Patient Volume**  
- **Most Frequent Problems & Diagnoses**  
- **Hospital Working Hours Trend (Line Chart)**  
- **Patient Distribution by State & Gender**  

---

## ⚙️ Tools & Skills
- **Microsoft Excel**  
  - Power Query (Merging & Cleaning Multiple CSV Files)  
  - Pivot Tables & Pivot Charts  
  - Dashboard Interactivity with Slicers  
  - Data Modeling (joining Patients, Encounters, Providers, Diagnoses, etc.)  

---

## 🚀 How to Use
1. Load all CSV files (`medical_patients.csv`, `medical_providers.csv`, `medical_encounters.csv`, etc.) into Excel Power Query.  
2. Perform transformations and join tables on appropriate keys (Patient ID, Encounter ID, Provider ID).  
3. Use Pivot Tables to design charts.  
4. Explore the dashboard with slicers for Visit Type, Gender, Month, and State.  

---

## 📷 Dashboard Preview
(./Screenshot 2025-08-20 183827.png)

---

## 📌 Key Learnings
- Handling **multi-table healthcare datasets** in Excel.  
- Using **Power Query** for ETL (Extract, Transform, Load).  
- Applying **data storytelling** to hospital analytics.  
- Designing **interactive dashboards** for real-world healthcare insights.  

---

## 🔮 Future Improvements
- Automate data refresh using Power BI.  
- Incorporate **predictive analytics** (e.g., forecasting visits or lab results using Python).  
- Expand to an **end-to-end data pipeline** for healthcare analytics.  

---

## 🙌 Acknowledgement
This project is part of my **Data Analytics portfolio**, showcasing how raw medical datasets can be combined into **actionable insights** using Excel.

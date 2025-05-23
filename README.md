# Deloitte Australia Data Analytics Job Simulation (Forage) – Feb 2025

This repository contains my completed tasks from the **Deloitte Australia Data Analytics Virtual Experience Program** on **Forage**, completed in **February 2025**. The simulation involved solving real-world business problems using tools such as **Tableau** and **Excel**, simulating work done by Deloitte’s data analytics and forensic teams.

---

## 📊 Project 1: Factory Telemetry Analysis (Tableau)

### 🔍 Objective:
Analyze telemetry data collected from 4 global Daikibo factories to answer:
- In which **location** did machines break the most?
- Which **machine types** broke most often in that location?

### 📁 Dataset:
- A unified 25 lacs+ lines of JSON file containing one month of telemetry data (May 2021), with 9 machine types sending messages every 10 minutes from:
  - 🏭 Meiyo Factory – Tokyo, Japan  
  - 🏭 Seiko Factory – Osaka, Japan  
  - 🏭 Berlin Factory – Berlin, Germany  
  - 🏭 Shenzhen Factory – Shenzhen, China  

### ✅ Tasks Completed:
- Created a calculated field `Unhealthy` = 10 for each "unhealthy" machine message.
- Built **2 interactive bar charts** in Tableau:
  - **Down Time per Factory**
  - **Down Time per Device Type**
- Developed a **dashboard** that filters machine types by factory.
- Identified the **factory with the most down time** and the **worst-performing machines**.

### 📸 Screenshot:

Dashboard images included in the repository.

<p align="center">
  <img src="Tableau dashboard 1.png" width="45%" alt="Dashboard Screenshot 1"/>
  <img src="Tableau dashboard 2.png" width="45%" alt="Dashboard Screenshot 2"/>
</p>

---

## 🕵️ Project 2: Gender Pay Equality Audit (Excel Forensics Task)

### 🔍 Objective:
Investigate gender pay equality issues within Daikibo Industrials by analyzing role-based compensation equality scores.

### 📁 Dataset:
- Excel file with:
  - `Factory`
  - `Job Role`
  - `Equality Score` (ranging from -100 to +100)

### ✅ Tasks Completed:
- Created a new column `Equality Class` based on score:
  - `Fair` → Score between -10 and +10  
  - `Unfair` → Score < -10 or > 10  
  - `Highly Discriminative` → Score < -20 or > 20
- Labeled every role accordingly in Excel.

---

## 📌 Key Takeaways
- 📈 Gained hands-on experience with **Tableau** for data visualization and interactive dashboards.
- 📊 Applied **data classification and logic** in Excel for forensic analysis.
- 🤝 Simulated **real-world consulting tasks** performed by Deloitte’s data analytics teams.
- ⏱️ Managed analysis of over **100,000+ rows** of telemetry and salary data.

---

### 📸 Screenshot:

Dashboard images included in the repository.

<p align="center">
  <img src="Equality class.png" width="45%" alt="Excel Screenshot 1"/>
</p>

---

## 📂 Files Included
- `.png files` – Tableau dashboard screenshot  
- `Task 2 Equality Table.xlsx` – Completed Excel classification task  
- `README.md` – Project documentation
- `daikibo-telemetry-data.json` - 25 lacs+ lines of telementory factory -machine json data 

---

## 🌐 About the Program

> [Deloitte Australia x Forage – Data Analytics Job Simulation](https://www.theforage.com/)  
> Designed to help students and early professionals gain practical experience in the data analytics field through real-world case studies.

---

## 🏅 Certificate of Completion

📄 [View Certificate (PDF)](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/9PBTqmSxAf6zZTseP/io9DzWKe3PTsiS6GG_9PBTqmSxAf6zZTseP_x4YgQ7Xcfq6kZbdwt_1740407677545_completion_certificate.pdf)

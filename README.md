# 🏥 Health Intelligence Platform
### An End-to-End Healthcare Analytics System

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📌 Project Overview

A professional-grade, end-to-end healthcare analytics platform built on **101,766 real patient records** from 130 US hospitals. This system integrates SQL data warehousing, Python analytics, and an interactive Power BI dashboard to deliver actionable insights for hospital management and clinical decision-making.

This project simulates what senior healthcare data analysts build for hospitals, health ministries, and global health organizations like WHO and NHS.

---

## 🎯 Business Problem

Hospital readmissions cost the US healthcare system over **$26 billion annually**. Every patient readmitted within 30 days represents a clinical failure and a financial penalty for hospitals under CMS regulations.

This platform answers 3 critical questions:
- **Who** is most likely to be readmitted within 30 days?
- **Why** are certain patient groups at higher risk?
- **What** clinical interventions can reduce readmission rates?

---

## 📊 Key Findings

| Insight | Finding |
|---|---|
| Total patients analyzed | 101,766 |
| 30-day readmission rate | 11.1% (11,357 patients) |
| Highest risk age group | 70–80 years (3,069 readmissions) |
| Avg hospital stay | 4.81 days (age 80–90) |
| Patients NOT readmitted | 54,864 (53.9%) |

---

## 🏗️ Architecture

```
Data Sources          Processing              Output
─────────────         ──────────              ──────
UCI Hospital Data ──► Python ETL         ──► PostgreSQL
WHO API           ──► pandas cleaning    ──► Power BI Dashboard
CMS Medicare      ──► SQL analysis       ──► Jupyter Reports
ClinicalTrials    ──► Visualization      ──► GitHub Portfolio
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python** | Data ingestion, cleaning, analysis |
| **Pandas & NumPy** | Data manipulation |
| **PostgreSQL** | Data warehouse |
| **SQLAlchemy** | Database connection |
| **Power BI** | Interactive dashboard |
| **Jupyter Notebook** | Analysis & documentation |

---

## 📁 Project Structure

```
health-intelligence-platform/
├── notebooks/
│   ├── 01_load_data.ipynb        # ETL pipeline
│   └── 02_sql_analysis.ipynb     # SQL insights
├── dashboard/
│   └── health_platform.pbix      # Power BI dashboard
├── themes/
│   └── healthcare_dark_theme.json # Custom dark theme
├── data/
│   └── README.md                 # Dataset instructions
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/health-intelligence-platform.git
cd health-intelligence-platform
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download the dataset
Download from UCI Machine Learning Repository:
👉 https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

Place `diabetic_data.csv` in `data/raw/`

### 4. Set up PostgreSQL
```sql
CREATE DATABASE health_db;
```

### 5. Run notebooks in order
```
01_load_data.ipynb      → loads data into PostgreSQL
02_sql_analysis.ipynb   → runs SQL analysis
```

### 6. Open Power BI Dashboard
Open `dashboard/health_platform.pbix` in Power BI Desktop

---

## 📈 Dashboard Pages

| Page | Description |
|---|---|
| 🏥 Health Overview | KPI cards — total patients, avg stay, medications |
| ⚠️ Readmission Risk | Age group analysis, gender breakdown |
| 🚨 Outbreak Monitor | Diagnosis trends, admission patterns |
| 💊 Clinical KPIs | Medications and procedures by age |
| 🤖 Predictive Alerts | High risk patient identification |

---

## 📦 Requirements

```
pandas
numpy
sqlalchemy
psycopg2-binary
jupyter
matplotlib
seaborn
```

---

## 🌍 About This Project

Built as part of a professional healthcare analytics portfolio targeting global remote opportunities with WHO, NHS Digital, Health Catalyst, and international health organizations.

**Dataset:** Diabetes 130-US Hospitals (UCI Machine Learning Repository)
**Records:** 101,766 patient visits across 130 US hospitals (1999–2008)
**Features:** 50 clinical variables including diagnoses, medications, and outcomes

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)

---

⭐ **If this project helped you, please give it a star!**

# Recruitment Analytics Dashboard for Energy & Mining Company

## 📌 Project Overview

This project simulates the role of a Data Analyst in the Human Capital (HR) division of an Energy & Mining company. The objective is to analyze candidate recruitment data, identify applicant characteristics, and build an interactive dashboard with Power BI to support recruitment decision-making.

> **Note**
>
> The dataset used in this project originally comes from a public registration form. To fit the business case, several columns were renamed and interpreted based on the recruitment context of an Energy & Mining company.

---

## 🎯 Business Problem

The Human Capital division needs to understand the characteristics of recruitment candidates to support strategic hiring decisions.

This project aims to answer questions such as:

- What is the demographic profile of candidates applying for recruitment?
- Which provinces contribute the highest number of candidates?
- What is the distribution of Fresh Graduates and Experienced Candidates?
- Which recruitment channels are the most effective in attracting candidates?
- What are the most common skills possessed by the candidates?
- What are the primary career goals of the candidates?
- How does the number of applications change over the recruitment period?

---

## 📂 Dataset

The dataset contains **682 candidate records**. Data cleaning included identifying and removing duplicate entries based on the **Full Name** column as the reference, which for duplicate detection. 

After the cleaning process, **644 unique candidate records** remained and were used for exploratory data analysis (EDA) and Power BI dashboard development.

### Data Preparation Assumptions

| Original Column | Assumed As |
|-----------------|------------|
| Tools yang Ingin Dipelajari | Kemampuan Karyawan |
| Target Join Komunitas | Target Masuk Perusahaan |
| Tau Seara Data Dari Mana? | Mengetahui Perusahaan Dari Mana |
| Pekerjaan & Instansi Saat Ini | Removed |

To protect participant privacy, personally identifiable information (PII) such as **Email Address, and WhatsApp Number** has been removed from the published dataset.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed using Python:

- Removed duplicate records
- Handled missing values
- Standardized text formatting
- Removed leading/trailing whitespace
- Standardized WhatsApp number formatting
- Converted Timestamp into datetime format
- Renamed columns according to the business scenario
- Removed unnecessary columns

---

## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand candidate characteristics through:

- Candidate Status Distribution
- Top 10 Candidate Domiciles
- Top 5 Employee Skills
- Top 5 Target Companies
- Applicant Trend Overtime

---

## 📈 Dashboard

The interactive dashboard was developed to provide recruitment insights through:

- KPI Overview
- Candidate Status Distribution
- Candidate Distribution by Province
- Recruitment Source Analysis
- Candidate Skills Analysis
- Career Goals Analysis
- Applicant Trend Over Time
- Interactive Dashboard Filters (Slicers)

### Dashboard Preview

none

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Pbi
- Git
- GitHub

---

## 📁 Project Structure

```text
Recruitment-Analytics-Energy-Mining/
│
├── dashboard/
│   └── Recruitment_Dashboard.jpeg
│
├── data/
│   ├── Database Seara Data.xlsx
│   └── Database_Seara_Data_Clean.csv
│
├── notebook/
│   ├── cleaningdata.ipynb
│   └── ExploratoryDataAnalysis.ipynb
│
└── README.md
```

---

## 💡 Key Insights

- The recruitment dataset consists of 644 unique candidates after the data cleaning process, providing a reliable foundation for recruitment analysis.
- Experienced Candidates account for the largest proportion of applicants, indicating that the recruitment process attracts more experienced professionals than fresh graduates.
- Candidates are distributed across 34 provinces, with Central Java contributing the highest number of applicants, highlighting a key talent pool for future recruitment campaigns.
- LinkedIn is the most effective recruitment channel, generating the highest number of candidate applications among all recruitment sources.
- Excel is the most common skill reported by candidates, indicating a strong foundation in data processing and analysis.
- Networking is the most common career goal among candidates, suggesting that many applicants are seeking to expand their professional connections and career opportunities.
- Application volume fluctuated throughout the recruitment period, with the highest number of applications recorded on 18 January 2026, indicating a peak recruitment period that can help optimise future recruitment campaigns.


---

🚀 Business Impact

- Prioritise recruitment campaigns in provinces with the highest candidate participation.
- Allocate recruitment budgets to the most effective recruitment channels.
- Design hiring and onboarding strategies based on the dominant candidate profile (Fresh Graduate vs Experienced).
- Align training and recruitment programmes with the most common candidate skill sets.
- Schedule recruitment campaigns around peak application periods to maximise candidate reach.

---

## 🚀 Future Improvements

- Candidate segmentation using Machine Learning.
- Predictive recruitment analytics.
- Interactive recruitment dashboard with real-time database integration.

---

## 👤 Author 1

Siti Nur Aisyah

GitHub: https://github.com/nura0201

LinkedIn: https://www.linkedin.com/in/aisyahsn/

## 👤 Author 2

Fadia Rahmawati

GitHub: https://github.com/

LinkedIn: https://www.linkedin.com/in/


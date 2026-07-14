# Recruitment Analytics Dashboard for Energy & Mining Company

## 📌 Project Overview

This project simulates the role of a Data Analyst in the Human Capital (HR) division of an Energy & Mining company. The objective is to analyze candidate recruitment data, identify applicant characteristics, and build an interactive dashboard to support recruitment decision-making.

> **Note**
>
> The dataset used in this project originally comes from a public registration form. To fit the business case, several columns were renamed and interpreted based on the recruitment context of an Energy & Mining company.

---

## 🎯 Business Problem

The Human Capital division needs to understand the characteristics of recruitment candidates to support strategic hiring decisions.

This project aims to answer questions such as:

- Who are the dominant candidates based on demographics?
- What skills are most commonly possessed by candidates?
- What are the primary motivations of candidates joining the company?
- Which recruitment channels are the most effective?

---

## 📂 Dataset

The dataset contains **681 candidate records**.

### Data Preparation Assumptions

| Original Column | Assumed As |
|-----------------|------------|
| Tools yang Ingin Dipelajari | Kemampuan Karyawan |
| Target Join Komunitas | Target Masuk Perusahaan |
| Tau Seara Data Dari Mana? | Mengetahui Perusahaan Dari Mana |
| Pekerjaan & Instansi Saat Ini | Removed |

To protect participant privacy, personally identifiable information (PII) such as **Full Name, Email Address, and WhatsApp Number** has been removed from the published dataset.

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
- Top 5 Candidate Domiciles
- Top 5 Employee Skills
- Top 5 Target Companies

---

## 📈 Dashboard

The interactive dashboard was developed to provide recruitment insights through:

- Recruitment Overview
- Candidate Profile
- Employee Skills Analysis
- Recruitment Channel Analysis

### Dashboard Preview

*(Insert dashboard screenshots here)*

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
├── data/
│   ├── Database Seara Data.xlsx
│   └── Database_Seara_Data_Clean.csv
│
├── notebook/
│   ├── cleaningdata.ipynb
│   └── ExploratoryDataAnalysis.ipynb
│
├── dashboard/
│   └── Recruitment_Dashboard.pbix
│
├── README.md
│
└── requirements.txt
```

---

## 💡 Key Insights

Example:

- Most candidates are Fresh Graduates.
- The majority of applicants come from several dominant domiciles.
- Upskilling is the primary motivation among candidates.


---

## 🚀 Future Improvements

- Candidate segmentation using Machine Learning.
- Predictive recruitment analytics.
- Interactive recruitment dashboard with real-time database integration.

---

## 👤 Author

Siti Nur Aisyah

GitHub: https://github.com/nura0201

LinkedIn: https://www.linkedin.com/in/aisyahsn/

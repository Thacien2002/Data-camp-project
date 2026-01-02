# Data-camp-project
this is the work form Data camp certfication project 
Perfect, Thacien 👍
Below is a **clean, professional GitHub README.md** that you can **copy-paste directly into GitHub (online)**.
It is **simple English**, **short**, and clearly explains your **Python analysis, metrics, and visuals**.

# 📊 Outbound Nursing Call & Screening Analysis

## 📌 Project Overview

This project analyzes **outbound nursing calls and patient screening completion** using Python.
The goal is to understand **screening distribution**, **call effectiveness**, and **completion rates**, and to define **business metrics** that can help improve healthcare outreach performance.

The analysis uses **real-world healthcare operational data** and focuses on producing **clear, percentage-based visual insights** that can also be replicated in **Power BI**.

## 🧾 Dataset Description

The dataset contains **1,988 records** with the following key fields:

* `patient_id` – Unique patient identifier
* `screening_type` – Type of screening (COL, CBP, BCS, EED, OMW)
* `reached_ind` – Whether the patient was reached by phone (1 = Yes, 0 = No)
* `screening_completed_ind` – Whether screening was completed (1 = Yes, 0 = No)
* `latest_call_date` – Date of last call
* `screening_date` – Date screening was completed

## 🧹 Data Validation & Cleaning

* Removed invalid screening types
* Standardized call reach and completion indicators
* Converted date columns to proper datetime format
* Handled missing values carefully to reflect real business situations (e.g., not yet called)
## 📈 Exploratory Data Analysis (EDA)

### Visuals Created:

1. **Distribution of Screening Types (%)**
2. **Outbound Call Outcomes (%)**
3. **Screening Completion Rate by Call Reach Status (%)**
4. **Completion Rate by Number of Eligible Screenings**
5. **Screening Completion Rate by Screening Type (%)**

All charts include **percentage labels** for easy interpretation and business communication.

## 📊 Key Business Metrics

* **Overall Screening Compliance Rate:** **81.81%**
* **Call-Assisted Screening Completion Rate (CASCR):** **79.84%**
* **Call Reach Rate:** ~**59%**

These values serve as the **baseline metrics** for monitoring future performance.

## 🔍 Key Insights

* Colorectal Cancer (COL) and High Blood Pressure (CBP) screenings make up the **largest workload**
* Screening completion is **high overall (~80%)**
* CASCR is very close to overall compliance, showing that **calls help but are not the only driver**
* Around **40% of patients** are not reached or not yet called
* Patients with **10–35 eligible screenings** show lower completion rates and may need more follow-up

## ✅ Recommendations

* Improve **call reach rate**, especially for patients not yet contacted
* Prioritize **high-volume screenings** (COL and CBP)
* Add targeted follow-ups for **mid-volume patients (10–35 screenings)**
* Standardize call workflows to improve consistency and efficiency


## 🛠️ Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
## 📎 Future Work

* Build an interactive **Power BI dashboard** using the same metrics
* Add time-based trend analysis
* Segment performance by clinic or region

---

## 👤 Author

**HARAGIRIMANA Thacien**



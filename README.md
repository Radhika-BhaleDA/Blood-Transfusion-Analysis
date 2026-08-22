# 🩸 BOTS — Blood Order Transfusion System Data Analysis

This project analyzes real hospital blood transfusion data from multiple
hospitals across Madhya Pradesh, India (December 2025 – July 2026).
By combining patient demographics, blood group records, component issued
data, and turnaround time metrics, this study explores how hospitals can
optimize blood bank operations, reduce delays, and improve patient safety.

---

## 📁 Project Structure

BOTS-Blood-Transfusion-Analysis/
│
├── BOTS_Dataset_Project.ipynb   # All analysis and visualizations in Google Colab
├── README.md                    # Overview and instructions
│
└── outputs/                     # Visualization exports
    ├── blood_group_distribution.png
    ├── gender_distribution.png
    ├── age_group_distribution.png
    ├── blood_components_issued.png
    ├── monthly_request_trend.png
    ├── tat_distribution.png
    ├── hospital_wise_requests.png
    └── blood_group_discrepancy.png

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 🚀 How to Run the Notebook

1. Open `BOTS_Dataset_Project.ipynb` in Google Colab.
2. Upload the Excel file `MP_BOTS_Data_14072026.xlsx` when prompted.
3. Run all cells in sequence to reproduce:
   * Data cleaning and duplicate removal
   * TAT parsing and feature engineering
   * 8 visualizations
   * Final summary report
4. All plots will render inline inside the notebook.

---

## 📊 Visual Outputs

The following charts were generated and included in the analysis:

* Blood Group Distribution of Patients
* Gender Distribution
* Age Group Distribution
* Blood Components Issued to Patients
* Monthly Blood Transfusion Request Trend
* Turnaround Time Distribution (Request to Issue)
* Hospital Wise Blood Transfusion Requests
* Blood Group Discrepancy in Transfusions

These charts support the operational insights documented in the final summary report.

---

## 🎯 Objective Summary

The goal of this analysis is to identify demand patterns, measure hospital
response efficiency through turnaround time, detect data quality issues such
as blood group discrepancies, and provide actionable recommendations that
hospital management can use to optimize blood bank operations and ensure
patient safety.

---

Prepared by: Radhika Bhale
B.Tech — Artificial Intelligence & Data Science
Jawaharlal Nehru Engineering College, MGM — 2026


## 📸 Project Snapshots

### 🩸 Blood Group Distribution
<img width="1189" height="490" alt="blood_group_distribution" src="https://github.com/user-attachments/assets/42a1fa1b-c7c9-4f96-aebc-42a0811f7b21" />

### 👥 Gender Distribution
<img width="503" height="490" alt="gender_distribution" src="https://github.com/user-attachments/assets/16bdf904-9501-4afd-b4b8-b82cfffdab36" />

### 👶 Age Group Distribution
<img width="1189" height="490" alt="age_group_distribution" src="https://github.com/user-attachments/assets/187c70aa-b90e-4fe8-a077-73e67f4b265d" />

### 📅 Monthly Request Trend
<img width="1189" height="490" alt="monthly_request_trend" src="https://github.com/user-attachments/assets/a8d82b9d-5340-4288-a22a-e6efc1a6f3c2" />

### ⏱️ Turnaround Time Distribution
<img width="1189" height="490" alt="tat_distribution" src="https://github.com/user-attachments/assets/31cdba93-9140-46ea-b158-99e00844733c" />

### ⚠️ Blood Group Discrepancy
<img width="666" height="690" alt="blood_group_discrepancy" src="https://github.com/user-attachments/assets/c01cd43b-febd-4a73-b594-6c3d32b13c61" />





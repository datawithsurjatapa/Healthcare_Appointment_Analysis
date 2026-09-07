# Healthcare_Appointment_Analysis
Data Analytics Project by Python(Pandas,Numpy,Matplotlib & Seaborn)

---

## 📌 Project Overview

This project analyzes **10,000 healthcare appointment records** to identify patterns in patient attendance, no-shows, and clinic operations.

The analysis uses **Python, Pandas, Matplotlib, and Seaborn** to clean the data, perform exploratory data analysis (EDA), visualize trends, and generate meaningful business insights.

---

## 🎯 Business Objective

The main objective of this project is to understand:

- Patient attendance and no-show patterns
- Factors associated with missed appointments
- Appointment trends across different clinics and appointment types
- The impact of SMS reminders on attendance
- The relationship between waiting time and attendance
- Patient characteristics associated with higher no-show rates
- Operational areas where healthcare providers can improve appointment management

---

## ❓ Key Business Questions

1. What is the overall attendance and no-show rate?
2. Which clinic has the highest attendance rate?
3. Which appointment types have the highest no-show rates?
4. How does attendance vary across different age groups?
5. Does previous no-show history affect future attendance?
6. Is there a relationship between SMS reminders and appointment attendance?
7. Does waiting time between scheduling and appointment affect attendance?
8. Does travel distance influence the likelihood of missing an appointment?
9. How does attendance vary by insurance type?
10. Do patients with chronic conditions show different attendance patterns?
11. Which patient or appointment segments require greater operational attention?

---

## 📊 Dataset

The dataset contains **10,000 healthcare appointment records**.

### Main Features

| Column | Description |
|---|---|
| `patient_id` | Unique patient identifier |
| `appointment_id` | Unique appointment identifier |
| `age` | Patient age |
| `gender` | Patient gender |
| `scheduled_date` | Date when appointment was scheduled |
| `appointment_date` | Actual appointment date |
| `clinic` | Clinic where appointment was scheduled |
| `appointment_type` | Type of healthcare appointment |
| `hypertension` | Indicates hypertension status |
| `diabetes` | Indicates diabetes status |
| `chronic_condition_count` | Number of chronic conditions |
| `previous_no_shows` | Number of previous missed appointments |
| `sms_sent` | Whether an SMS reminder was sent |
| `insurance_type` | Patient insurance category |
| `distance_km` | Distance travelled to the clinic |
| `appointment_hour` | Scheduled appointment hour |
| `attended` | Whether the patient attended |
| `visit_cost_inr` | Appointment/visit cost in INR |

---

## 📂 Dataset Source

This project uses a synthetic healthcare appointment dataset generated with the assistance of ChatGPT for educational and portfolio purposes.

## 🧹 Data Cleaning & Preprocessing

The following data preparation steps were performed:

- Checked dataset dimensions and data types
- Identified and handled missing values
- Checked duplicate records
- Converted date columns into appropriate datetime format
- Validated categorical values
- Created additional analytical features
- Calculated waiting time between scheduled and appointment dates
- Prepared the dataset for exploratory analysis and visualization

---

## 🔎 Exploratory Data Analysis

### Patient Demographics

- Age distribution
- Gender distribution

### Appointment Analysis

- Appointments by insurance type
- Clinic-wise appointment volume
- Attendance rate by clinic

### No-Show Analysis

- No-show rate by age group
- No-show rate by clinic
- No-show rate by appointment type
- SMS reminders vs. attendance
- Waiting days vs. attendance
- Distance from Clinic by Attendance Status

---

### Financial Analysis
-- Distribution of Visit Costs
-- Average Visit Cost by Appointment Type

---
## 📈 Data Visualization

The project uses **Matplotlib and Seaborn** to create visualizations such as:

- Bar charts
- Count plots
- Histograms
- Box plots
- Stacked bar charts
- Comparative categorical visualizations
- Attendance and no-show analysis charts

---

## 💡 Key Insights

The analysis focuses on identifying actionable insights related to:

- Overall patient attendance and no-show behavior
- Clinics with comparatively higher or lower attendance
- Appointment types associated with greater no-show risk
- Age groups with different attendance patterns
- The relationship between SMS reminders and appointment attendance
- The impact of waiting time on no-show behavior

---

## 📁 Project Structure

```text
Healthcare-Appointment-Analysis/
│
├── Healthcare_Appointment_Analysis(raw data).csv
├── Healthcare_Appointment_Analysis.ipynb
├── Healthcare_Appointment_Analysis_ppt.pptx
└── README.md
```

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Numpy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 👩‍💻 Author

**Surjatapa Mukherjee**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

---

> ## ⭐ Support

If you find this project useful or interesting, please consider giving the repository a **⭐ Star on GitHub**.

Your support is greatly appreciated!

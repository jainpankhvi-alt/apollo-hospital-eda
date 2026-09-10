# Apollo Hospitals Appointment No-Show and Patient Engagement Analysis (Python EDA)

## Project Overview

This project analyzes **75,000 hospital appointments** from **Apollo Hospitals (2022–2024)** to understand patient booking behavior, appointment no-shows, patient engagement, financial performance, and doctor service quality.

The objective was to perform **Exploratory Data Analysis (EDA)** using **Python**, **Pandas**, and **Plotly** to identify actionable business insights that can help reduce no-shows, improve patient experience, and optimize hospital operations.

---

## Business Problem

Apollo Hospitals receives appointments through multiple booking channels, including the Apollo App, website, call centre, walk-ins, and partner applications. A significant number of booked appointments result in **no-shows**, affecting:

- Doctor utilization
- Hospital revenue
- Patient health outcomes
- Scheduling efficiency

This analysis investigates where and why these no-shows occur while also evaluating revenue performance and service quality.

---

## Dataset Information

### Files Used

| File | Description |
|------|-------------|
| `apollo_appointments_fact.csv` | 75,000 appointment records with 52 columns |
| `apollo_doctors_dim.csv` | 320 doctor records with 15 columns |

Both datasets were joined using **`doctor_id`** for doctor-level analysis.

---

## Tools & Libraries

- Python
- Pandas
- Plotly Express
- Jupyter Notebook

---

## Project Workflow

1. Data Import
2. Data Cleaning & Validation
3. Exploratory Data Analysis
4. Business Insights
5. Data Visualization
6. Final Recommendations

---

# Analysis Performed

## 1. Business Overview

- Monthly appointment trends (2022–2024)
- Quarterly appointment trends
- Appointment status distribution
- Booking channel analysis

### Visuals

- Line Charts
- Bar Charts
- Donut Charts

---

## 2. No-Show Analysis

- No-show rate by specialty
- No-show rate by city
- Booking lead time analysis
- Time slot comparison
- Weekend vs weekday analysis
- Appointment type risk
- Booking channel risk

### Business Focus

Identify which patients are most likely to miss appointments.

---

## 3. Reminder & Patient Engagement

- Reminder type effectiveness
- Previous no-show behavior
- Apollo member vs non-member comparison
- Repeat vs first-time patient attendance

### Goal

Evaluate which engagement strategies improve attendance.

---

## 4. Patient & Demographic Segmentation

- Age group no-show analysis
- Gender comparison
- Chronic condition analysis
- Most common visit reasons
- High-dropout visit reasons
- Age distribution across:
  - Paediatrics
  - Gynaecology
  - Psychiatry

---

## 5. Financial Performance

- Estimated revenue lost due to no-shows
- Average revenue by specialty
- Average revenue by appointment type
- Revenue by city
- Payment mode distribution
- Insurance vs out-of-pocket payment analysis

### Important Business Rule

Revenue analysis was performed **only on completed appointments**, as specified in the project requirements.

---

## 6. Doctor Utilisation & Service Quality

- Doctor utilization by specialty
- Average waiting time by specialty
- Waiting time by time slot
- Consultation duration vs patient satisfaction
- Doctor experience vs consultation fee

Doctor information was analyzed after joining the doctor dimension table.

---

# Key Insights

- Appointment demand changed across months and quarters.
- No-show rates varied across specialties, cities, booking channels, and patient groups.
- Previous no-show history helped identify higher-risk patients.
- Reminder methods showed different attendance outcomes.
- Certain specialties generated higher revenue while others experienced greater revenue loss from no-shows.
- Waiting times and doctor utilization differed across specialties.
- More experienced doctors generally showed differences in consultation fee patterns.

---

# Business Recommendations

- Strengthen reminder campaigns for high-risk patients.
- Improve scheduling in specialties with longer waiting times.
- Focus retention efforts on first-time and non-member patients.
- Reduce revenue leakage by targeting high no-show departments.
- Balance doctor workloads using utilization insights.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Aggregation with Pandas
- Business Insight Generation
- Healthcare Data Analysis
- Data Visualization with Plotly
- Joining Multiple Datasets
- Professional Notebook Documentation

---

## Project Outcome

This project demonstrates how **Python-based Exploratory Data Analysis** can transform raw healthcare appointment data into actionable business insights that support better patient engagement, improved operational efficiency, and stronger revenue management.
